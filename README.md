# مدل ocr برای حل کپچا و کار های دیگر

شما میتوانید از این پروژه برای پروژه هایی که نیاز به تایید کپچای متنی دارند استفاده کنید و یا بسته به نیاز از این پروژه به عنوان یک ocr قدرتمند استفاده کنید

## این پروژه از زبان فارسی پشتیبانی نمیکند

* [نصب](#نصب)
* [استفاده از پروژه](#استفاده-از-پروژه)
* [حمایت مالی](#حمایت-مالی)
* [شبکه های اجتماعی](#شبکه-های-اجتماعی)

# نصب

برای نصب این پروژه، کافی است دستور زیر را وارد کنید

`pip install git+https://github.com/SafaSafari/ddddocr`

در صورتی که به اینترنتی پایدار متصل باشید، نصب با موفقیت انجام خواهد شد

# استفاده از پروژه

برای استفاده از پروژه، کافیست کد زیر را در پروژه خود بگنجانید و به راحتی از ocr استفاده کنید

```python
import ddddocr
det = ddddocr.DdddOcr(det=False, beta=True, show_ad=False)
with open('image.png', 'rb') as f:
  image = f.read()
ocr = det.classification(image)
print(ocr)
```

# حمایت مالی
Rial: [نکست پی](https://nextpay.org/nx/irp/safa)

Btc: `bc1qgrlfzelx6dn6hym7c73jpp2w2p4hdy7lgftudr`

Ltc: `ltc1ql02lg3yrtgy7xfnnl5jvgrwv2ffxkhyn54qyj0`

Usdt(trc20): `TH8PcLF25uGhT4joJy7K5YQP43oYxs7ouY`

Tron: `TH8PcLF25uGhT4joJy7K5YQP43oYxs7ouY`

# شبکه های اجتماعی
[Twitter](https://twitter.com/SafaSafari3)

[Telegram](https://SafaSafari.t.me)

[Youtube](https://youtube.com/@SafaSafari)

[Instagram](https://instagram.com/SafaSafari.ss)
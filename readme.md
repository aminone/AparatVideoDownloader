### Aparat Video Downloader

با این اسکریپت میشه تمام ویدیو‌های یک کانال آپارات یا ویدیوهایی که لینک صفحه آپاراتشون رو تو یه فایل گذاشتید رو با کیفیتی که می‌خواید دانلود کنید. کافیه به عنوان اولین آرگومان آدرس کامل کانال (یا آدرس فایل لینک‌ها) و به عنوان دومین آرگومان کیفیتی که می‌خواد ویدیو دانلود بشه(۷۲۰، ۳۶۰ و ...) رو پاس بدید.

اسم فایل ویدیوها همون عنوانی میشه که روی سایت هست و نه یک رشته بی‌معنی و ویدیوها تو یه دایرکتوری با اسم کانال ذخیره میشن

**پیش‌نیازها**

- دسترسی اجرا :)

- aria2c

**نحوه استفاده**

- `./videoDownloader.sh https://www.aparat.com/<CHANEL_NAME>`   
همه ویدیو‌های کانال رو با کیفیت پیش‌فرض ۷۲۰ دانلود می‌کنه

- `./videoDownloader.sh https://www.aparat.com/<CHANEL_NAME> 360`   
همه ویدیو‌های کانال رو با کیفیت مشخص شده دانلود می‌کنه

- `./videoDownloader.sh <PAGES_LINK_LIST_FILE>`   
ویدیوی لینک‌های داخل فایل با کیفیت پیش‌فرض دانلود میشه

- `./videoDownloader.sh <PAGES_LINK_LIST_FILE> 144`   
ویدیوی لینک‌های داخل فایل با کیفیت مشخص شده دانلود میشه




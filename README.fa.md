[read in english](README.en.md)
<div dir='ltr'>
# ربات تلگرام فیلتر رنگی

ربات تلگرام فیلتر رنگی یک ربات است که به شما امکان می‌دهد فیلترهای رنگی مختلفی را به تصاویر خود اضافه کنید. این ربات قادر است تصاویر ارسالی شما را به سیاه و سفید تبدیل کند، فیلترهای رنگی مانند آبی یا قرمز اضافه کند، و حتی یک افکت سه‌بعدی قرمز و آبی ایجاد کند.

## نحوه استفاده

برای استفاده از این ربات، ابتدا باید آن را در تلگرام جستجو و سپس شروع به چت کنید. پس از شروع چت، دستورات زیر را می‌توانید استفاده کنید:

- `/start`: شروع کار با ربات و دریافت دستورالعمل‌های ابتدایی.
- `/help`: دریافت راهنمایی در مورد نحوه استفاده از ربات.
- `/black_white`: تبدیل تصویر ارسالی به سیاه و سفید.
- `/blue`: اضافه کردن فیلتر آبی به تصویر.
- `/red`: اضافه کردن فیلتر قرمز به تصویر.
- `/3d`: ایجاد افکت سه‌بعدی قرمز و آبی.

## نصب و راه‌اندازی

برای راه‌اندازی این ربات بر روی سرور یا محیط توسعه‌ی خود، مراحل زیر را دنبال کنید:

1. ابتدا اطمینان حاصل کنید که `python3` و `pip` بر روی سیستم شما نصب شده است.
2. کتابخانه‌های مورد نیاز را با استفاده از فایل `requirements.txt` نصب کنید:

```bash
pip install -r requirements.txt
```
3. یک فایل `.env` در ریشه پروژه ایجاد کنید و توکن ربات تلگرام خود را به این صورت اضافه کنید:

```bash
TELEGRAM_TOKEN=your_telegram_bot_token_here
```
4. اسکریپت ربات را با دستور زیر اجرا کنید:

```bash
python bot.py
```

## مشارکت

مشارکت‌ها در بهبود این اسکریپت خوش آمد است. لطفاً برای ارائه تغییرات، یک Pull Request ایجاد کنید.

</div>

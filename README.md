# server-client-json-command-with-zeromq

این ریپازیتوری شامل یک پروژه برای ارتباط کلاینت و سرور از طریق مسیج بروکر ZEROMQ است

## معرفی
در این پروژه ما تلاش میکنیم که ارتباطی بین کلاینت و سرور با استفاده از django به زبان پایتون با مسیج بروکر ZEROMQ شکل دهیم.در اینجا ما دو اپ سرور و کلاینت داریم که از طریق پورت یکسان با همدیگر بایند میشوند و سعی شده که مدیریت پورت و ارور ها داینامیک انجام بشه.
## ویژگی‌ها
- پیاده‌سازی API با استفاده از Django.
- پیاده سازی ارتباط کلاینت و سرور با استفاده از ZEROMQ
- پشتیبانی از اجرای دستورات سیستمی مشخص (با محدودیت‌های امنیتی).
- قابلیت انجام محاسبات ریاضی.
- مدیریت و پردازش داده‌های JSON.
  

## نصب و راه‌اندازی

### پیش‌نیازها:
برای اجرای این پروژه، ابتدا موارد زیر باید روی سیستم شما نصب باشد:
- Python نسخه 3
- pip
- Django
- pyzmq
- subprocess

### مراحل نصب:

1. ابتدا ریپازیتوری را کلون کنید:
   ```bash
   git clone https://github.com/amirfaramarzi76/interview_task.git
2.سپس سرور را از طریق CMD در پوشه اپ سرور با دستور:
 ```bash
start python server
```

ران کنید
و سپس در ترمینال پروژه را با دستور 
 ```bash
python -m manage runserver
```
اجرا کنید و سپس فایل json را اپلود کنید.

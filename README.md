# nikvpn-codespace
Free VLESS proxy using GitHub Codespaces - NikVPN for Iran
# NikVPN Codespace - پروکسی رایگان VLESS+xHTTP با گیت‌هاب کداسپیس

[![NikVPN for Iran](https://img.shields.io/badge/NikVPN-Iran-blue)](https://github.com/nikvpn-ir/nikvpn-codespace)

این ریپازیتوری به شما امکان می‌دهد در کمتر از ۵ دقیقه یک **پروکسی VLESS با ترانسپورت xHTTP و TLS** روی GitHub Codespaces راه‌اندازی کنید. این روش بر اساس تنظیمات موفق کانفیگ‌های کارا طراحی شده است.

## 🔧 ویژگی‌ها
- کاملاً رایگان (سهمیه ۶۰ ساعت در ماه)
- پروتکل VLESS + xHTTP + TLS با `mode=packet-up`
- استفاده از دامنه معتبر گیت‌هاب (عدم فیلتر شدن آی‌پی)
- Keepalive خودکار
- لینک آماده برای v2rayNG، Nekobox، Streisand و...

## 🚀 نحوه استفاده

### مرحله ۱: ساخت کداسپیس
1. یک اکانت گیت‌هاب بسازید.
2. این ریپو را **Fork** کنید.
3. روی **Code** > **Codespaces** > **Create codespace on main** کلیک کنید.
4. صبر کنید تا اسکریپت اجرا شود (حدود ۱-۲ دقیقه).

### مرحله ۲: دریافت لینک
در ترمینال یک لینک VLESS نمایش داده می‌شود. آن را کپی کنید.

### مرحله ۳: عمومی کردن پورت
- در ترمینال کداسپیس، تب **PORTS** را باز کنید.
- پورت **443** را پیدا کنید.
- روی **Visibility** کلیک کرده و **Public** را انتخاب کنید.
- آدرس «Forwarded Address» را یادداشت کنید (مثلاً `https://psychic-umbrella...-443.app.github.dev`). اگر لینک خودکار کار نکرد، این آدرس را به عنوان `sni` و `host` در لینک قرار دهید.

### مرحله ۴: اتصال
لینک را در اپلیکیشن پروکسی خود وارد کنید. اتصال باید بلافاصله برقرار شود (حتی از داخل ایران).

## ⚠️ نکات مهم
- هر ماه ۶۰ ساعت رایگان. بعد از استفاده، Codespace را **Stop** کنید.
- اگر اتصال برقرار نشد، از `allowInsecure=1` استفاده کنید (در لینک هست).
- در برخی کلاینت‌ها باید `type` را روی `xhttp` و `mode` را روی `packet-up` تنظیم کنید.

## 🤝 حمایت
**⭐ ستاره** فراموش نشود!  
کانال یوتیوب: [NikVPN for Iran](https://youtube.com/@nikvpn4iran)

# MasscanGUI – Interface for Masscan

<div dir="rtl">


## [فارسی](#fa) | [English](#en)


<a name="en"></a>
## English

### Introduction
**MasscanGUI** is a professional graphical user interface for the famous **Masscan** port scanner. It provides all Masscan features and parameters in a simple, user-friendly environment. No need to download Masscan separately – the executable is included alongside the GUI in the release package.

### Key Features
- ✅ **Full support for all Masscan parameters** (basic & advanced)
- 🌍 **Country‑based scanning** (IP ranges for 18 countries + custom ranges)
- 📝 **Multiple output formats** including `IP:PORT`, JSON, XML, Grepable, etc.
- 🚀 **Real‑time output display** while scanning
- ⚙️ **Network adapter settings** (adapter, IP, MAC, VLAN, source port)
- 📄 **Save & resume scans** + rotating output files
- 🔍 **Read binary scan files** and convert to text formats
- 🧩 **Sharding support** for distributed scans
- 🖥️ **No command line required** – everything is clickable

### How to Use
1. Place `MasscanGUI.exe` and `masscan.exe` in the same folder.
2. Run the application.
3. In the **Scan** tab, enter the IP range or target address.
4. Select ports (presets available).
5. Optionally adjust advanced settings (rate, retries, sharding, etc.).
6. Click **Start Scan** and watch results appear in the **Results** tab.

> **Note:** The masscan executable is included in the release – no separate installation or download is required.

### Country‑Based Scanning
- Go to the **Countries** tab.
- Select a country – its IP ranges will be displayed.
- You can also enter custom ranges in the text box below.
- Click **Scan This Country** to start scanning.

### IP:PORT Output
In the **Output** tab, choose the `IP:PORT` format. The output will look like:
```
192.168.1.1:80
192.168.1.5:443
```

### Requirements
- Windows (7, 8, 10, 11) – also runs on Linux/macOS with Python 3 if using the source.
- No Python installation needed (standalone .exe provided)

### Download
Download the executable (along with masscan.exe) from the **[Releases](https://github.com/mehdirzfx/MasscanGUI/releases)** section.

### GitHub Repository
[https://github.com/mehdirzfx/MasscanGUI](https://github.com/mehdirzfx/MasscanGUI)

### Author
**Mehdi Rezaei Far (s3nat0r)**

## ⭐️ Support This Project

If you find this project useful, please consider giving it a **star** on GitHub.  
Your support helps increase visibility and encourages further development.

[![GitHub stars](https://img.shields.io/github/stars/mehdirzfx/MasscanGUI?style=for-the-badge&logo=github&color=yellow)](https://github.com/mehdirzfx/MasscanGUI/stargazers)
</div>
<a name="fa"></a>

## فارسی

### معرفی
**MasscanGUI** یک رابط کاربری گرافیکی حرفه‌ای برای ابزار معروف **Masscan** است. این برنامه تمامی امکانات و پارامترهای Masscan را در یک محیط ساده و کاربرپسند ارائه می‌دهد. نیازی به دانلود جداگانه Masscan نیست – فایل اجرایی در کنار GUI در فایل ضمیمه (Release) قرار دارد.

### امکانات اصلی
- ✅ **پشتیبانی از تمام پارامترهای Masscan** (ساده و پیشرفته)
- 🌍 **اسکن بر اساس کشور** (رنج آی‌پی‌های ۱۸ کشور + امکان رنج دلخواه)
- 📝 **خروجی به فرمت‌های مختلف** شامل `IP:PORT`، JSON، XML، Grepable و...
- 🚀 **اسکن همزمان و نمایش لحظه‌ای نتایج**
- ⚙️ **تنظیمات شبکه** (آداپتور، آی‌پی، مک، VLAN، پورت منبع)
- 📄 **ذخیره و Resume اسکن** + خروجی چرخشی (Rotate)
- 🔍 **باز کردن فایل باینری Masscan** و تبدیل به فرمت متنی
- 🧩 **Sharding** برای اسکن توزیع‌شده
- 🖥️ **بدون نیاز به خط فرمان** – تمام تنظیمات با کلیک

### نحوه استفاده
1. فایل‌های `MasscanGUI.exe` و `masscan.exe` را در یک پوشه قرار دهید.
2. برنامه را اجرا کنید.
3. در تب **Scan**، آیپی رنج یا آدرس هدف را وارد کنید.
4. پورت‌ها را انتخاب کنید (پیش‌تنظیمات آماده).
5. در صورت نیاز، تنظیمات پیشرفته (نرخ، بیدر، شاردینگ و...) را اعمال کنید.
6. دکمه **Start Scan** را بزنید و نتایج را در تب **Results** ببینید.

> **نکته:** فایل اجرایی masscan در ریلیز همراه با GUI قرار داده شده است – نیازی به نصب یا دانلود جداگانه نیست.

### اسکن بر اساس کشور
- به تب **Countries** بروید.
- کشور مورد نظر را انتخاب کنید – لیست رنج‌های آی‌پی آن نمایش داده می‌شود.
- می‌توانید رنج دلخواه خود را نیز در قسمت پایین وارد کنید.
- با کلیک روی **Scan This Country** اسکن شروع می‌شود.

### خروجی IP:PORT
در تب **Output**، فرمت `IP:PORT` را انتخاب کنید. خروجی به این شکل خواهد بود:
```
192.168.1.1:80
192.168.1.5:443
```

### نیازمندی‌ها
- ویندوز (۷، ۸، ۱۰، ۱۱) – همچنین روی لینوکس و مک با پایتون ۳ قابل اجراست.
- بدون نیاز به نصب پایتون (فایل exe ارائه شده)

### دانلود
فایل اجرایی (همراه با masscan.exe) را از بخش **[Releases](https://github.com/mehdirzfx/MasscanGUI/releases)** دانلود کنید.

### لینک پروژه در گیتهاب
[https://github.com/mehdirzfx/MasscanGUI](https://github.com/mehdirzfx/MasscanGUI)

## ⭐️ حمایت شما

اگر این پروژه برای شما مفید است، لطفاً با **ستاره دادن** به آن در GitHub از ما حمایت کنید.  
این کار به دیده شدن بیشتر پروژه و ادامه توسعه آن کمک شایانی می‌کند.

[![GitHub stars](https://img.shields.io/github/stars/mehdirzfx/MasscanGUI?style=for-the-badge&logo=github&color=yellow)](https://github.com/mehdirzfx/MasscanGUI/stargazers)
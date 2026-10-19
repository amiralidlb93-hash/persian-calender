<div align="center">

# 🌷 نوروزی (Nowroozi)

### داشبورد جشن نوروز — شمارش معکوس تحویل سال، تقویم شمسی، فال حافظ و هفت‌سین 🎉
version : 1.0
<br/>

[![Live Demo](https://img.shields.io/badge/🌐_دموی_زنده-باز_کن-34d399?style=for-the-badge)](https://amiralidlb93-hash.github.io/persian-calender/)
[![License: MIT](https://img.shields.io/badge/لیسانس-MIT-fef08a?style=for-the-badge)](LICENSE)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dependencies](https://img.shields.io/badge/وابستگی-صفر-6ee7b7?style=flat-square)
![RTL](https://img.shields.io/badge/RTL-راست‌چین-052a22?style=flat-square)

<br/>

**🌱 سبزه • 🍎 سیب • 🧄 سیر • 🍚 سمنو • 🌿 سنجد • 🥁 سماق • 🪙 سکه**

<br/>

### 👉 [amiralidlb93-hash.github.io/persian-calender](https://amiralidlb93-hash.github.io/persian-calender/) 👈

</div>

---

<div dir="rtl">

## ✨ امکانات

| | ویژگی | توضیح |
|---|---|---|
| 📅 | **تاریخ شمسی زنده** | تبدیل خودکار میلادی ← جلالی با نام روز هفته، ماه شمسی و **اعداد فارسی** |
| 🕐 | **ساعت لحظه‌ای** | ساعت دیجیتال که هر ثانیه آپدیت می‌شود |
| ⏳ | **شمارش معکوس تحویل سال** | روز، ساعت، دقیقه و ثانیه تا اعتدال بهاری |
| 🪶 | **فال حافظ** | نیت کن، کلیک کن، غزل و تعبیرش را بخوان |
| 🪴 | **هفت‌سین** | هفت سین با آیکون و معنی هرکدام و انیمیشن هاور |
| 🎨 | **تم نوروزی** | پس‌زمینه سبز تیره، متن گرادیانی و کارت‌های شیشه‌ای (Glassmorphism) |
| 📱 | **ریسپانسیو** | از موبایل تا دسکتاپ، چیدمان خودکار هفت‌سین |

---

## 🚀 شروع سریع

پروژه **هیچ نیازی به نصب و بیلد ندارد**؛ فقط یک فایل `index.html`!

```bash
# ۱) کلون کن
git clone https://github.com/amiralidlb93-hash/persian-calender.git

# ۲) وارد پوشه شو
cd persian-calender

# ۳) فایل index.html رو توی مرورگر باز کن 🎊
```

یا اگر سرور لوکال می‌خوای:

```bash
npx serve .
# یا
python -m http.server 8000
```

---

## 🛠 تکنولوژی‌ها

| ابزار | کاربرد |
|---|---|
| 🧱 **HTML5** | ساختار صفحه، با `lang="fa"` و `dir="rtl"` |
| 🎨 **CSS3** | گرادیان، `backdrop-filter`، Grid، انیمیشن و Media Query |
| ⚡ **JavaScript (Vanilla)** | منطق ساعت، شمارش معکوس و فال، بدون هیچ فریم‌ورک |
| 🧮 **الگوریتم جلالی** | تبدیل تاریخ بدون کتابخانه خارجی |
| 🔤 **Vazirmatn** | فونت پیش‌فرض (در نبود آن Tahoma / system-ui) |

---

## 📁 ساختار پروژه

```
persian-calender/
├── index.html    # کل اپلیکیشن: ساختار + استایل + منطق 🎛
├── LICENSE       # لیسانس MIT 📄
└── README.md     # همین فایل 📖
```

---

## 🧠 پشت صحنه

**📅 تبدیل تاریخ:** تابع `toJalali(gy, gm, gd)` با یک الگوریتم حسابی (چرخه‌های ۳۳ ساله) تاریخ میلادی را به جلالی تبدیل می‌کند و خروجی با تابع `fa()` به ارقام فارسی نوشته می‌شود.

**⏳ شمارش معکوس:** هدف، تقریبی از لحظه اعتدال بهاری یعنی **۲۰ مارس، ساعت ۰۸:۳۰ به وقت UTC** است. اگر این لحظه در سال جاری گذشته باشد، خودکار به سال بعد می‌رود.

> ⚠️ لحظه دقیق تحویل سال هر سال کمی فرق دارد؛ این پروژه فقط یک **تقریب** است.

**🪶 فال حافظ:** مجموعه‌ای از غزل‌ها در آرایه `FAALS` ذخیره شده و با هر کلیک یکی به‌صورت تصادفی نمایش داده می‌شود.

**🪴 هفت‌سین:** آرایه `HAFTSIN` شامل آیکون، نام و معنی هر سین است و کارت‌ها با جاوااسکریپت ساخته می‌شوند.

---


```bash
git checkout -b feature/my-idea
git commit -m "✨ add my idea"
git push origin feature/my-idea
```

---

## 📄 لیسانس

این پروژه تحت لیسانس **MIT** منتشر شده؛ آزاد مثل باد بهاری 🌬

</div>

<br/>

<div align="center">

ساخته‌شده با ❤️ و چای تازه‌دم 🍵 برای نوروزِ ایرانی

**عیدتون مبارک! 🎊 — Eid-e shoma mobarak!**

⭐ اگر خوشت اومد، یه ستاره بهش بده ⭐

</div>

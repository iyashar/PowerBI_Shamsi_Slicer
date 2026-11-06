# 📅 Shamsi Date Slicer for Power BI | اسلایسر تاریخ شمسی پاور بی‌آی

[![Power BI Custom Visual](https://img.shields.io/badge/Power_BI-Custom_Visual-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![API Version](https://img.shields.io/badge/API-5.11.0_%7C_4.7.0(PBIRS)-green.svg)](https://learn.microsoft.com/en-us/power-bi/developer/visuals/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

[English](#english) | [فارسی](#فارسی)

---

## فارسی

### معرفی پروژه
**اسلایسر تاریخ شمسی (Shamsi Date Slicer)** یک ویژوال سفارشی، سریع، مدرن و کاملاً راست‌به‌چپ (RTL) برای Power BI است که امکان فیلتر کردن گزارش‌ها بر اساس تقویم هجری خورشیدی (جلالی) را با بالاترین سرعت و زیباترین رابط کاربری فراهم می‌کند.

این ابزار جایگزینی کامل و بومی برای اسلایسرهای میلادی پیش‌فرض Power BI است و چالش قدیمی هماهنگ‌سازی اسلایسرها (Sync Slicers) بین صفحات مختلف گزارش را به طور کامل حل می‌کند.

---

### ✨ قابلیت‌های کلیدی
- 🗓️ **فیلترهای پیش‌فرض هوشمند و پویا:** انتخاب سریع بازه‌های زمانی مانند:
  - امروز، دیروز
  - این هفته، هفته گذشته
  - این ماه، ماه گذشته
  - سال جاری، سال گذشته
  - ۳۰ روز اخیر، ۹۰ روز اخیر، ۱ سال اخیر
- 🔄 **پشتیبانی کامل از Sync Slicers:** فیلتر هم‌زمان و پایدار بین تمامی صفحات گزارش بدون بروز خطا در کش یا تداخل با سایر ویژوال‌ها.
- 📐 **چیدمان‌های متنوع (Layouts):** نمایش افقی (کپسولی/دکمه‌ای)، عمودی و بازه‌ای (اسلایدر کشویی).
- ✏️ **ورودی دستی تاریخ:** امکان تایپ یا انتخاب مستقیم تاریخ با تقویم کشویی پاپ‌آپ شمسی.
- 🎨 **تایپوگرافی اصیل ایرانی:** مجهز به فونت‌های استاندارد فارسی نظیر وزیرمتن (Vazirmatn)، ایران‌یکان، ساحل و شبنم با اعداد فارسی.
- 🏢 **سازگاری کامل سازمانی:** قابل استفاده در Power BI Desktop، سرویس ابری (Cloud Service) و سرور محلی مایکروسافت (PBIRS).

---

### 📥 راهنمای نصب و استفاده
1. فایل `Shamsi_Date_Slicer_PowerBI.pbiviz` را از بخش [Releases](../../releases) دانلود کنید.
2. در نرم‌افزار Power BI Desktop، در پنل **Visualizations** روی سه نقطه (`...`) کلیک کرده و گزینه **Import a visual from a file** را انتخاب کنید.
3. فایل دانلود شده را انتخاب کنید.
4. ستون تاریخ (شمسی یا میلادی استاندارد) جدول خود را به بخش **Date Field** ویژوال درگ کنید.

---

### 🛠️ ساخت از سورس‌کد (Build from Source)
```bash
# کلون مخزن
git clone https://github.com/your-username/shamsi-date-slicer.git
cd shamsi-date-slicer

# نصب پیش‌نیازها
npm install

# اجرای محیط توسعه لوکال
npm start

# بسته‌بندی ویژوال نهایی (.pbiviz)
npm run package
```

---

## English

### Overview
**Shamsi Date Slicer** is a high-performance, native RTL custom visual for Microsoft Power BI designed specifically for the Persian (Solar Hijri / Jalali) calendar system. It provides an executive and intuitive user experience for temporal slicing and filtering in dashboards.

### ✨ Key Features
- **Dynamic Relative Presets:** Quick filtering for Today, Yesterday, This Week, This Month, Last Month, Year-to-Date (YTD), Last 30/90/365 Days, etc.
- **Flawless Sync Slicers:** Full compatibility with Power BI's cross-page filter synchronization.
- **Multiple Layout Modes:** Horizontal button pills, vertical list, and continuous date range slider.
- **Native Typography:** Embedded clean Persian fonts (Vazirmatn, Sahel, Shabnam) and localized Persian numeral rendering.
- **Enterprise Ready:** Full backwards compatibility with Power BI Desktop, Cloud Service, and Power BI Report Server (PBIRS).

### 🚀 Quick Start
1. Download the latest `.pbiviz` package from [Releases](../../releases).
2. Open Power BI Desktop, go to the **Visualizations** pane -> Click `...` -> **Import a visual from a file**.
3. Drag your date column into the visual's **Date Field** role.

### 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

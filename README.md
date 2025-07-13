<div align="center">
  
![Preview](preview.png)

# 📌 قالب صفحه کاربری پنل مرزبان - MrClock

<p align="center">
  <a href="#معرفی">معرفی</a> •
  <a href="#ویژگی‌ها">ویژگی‌ها</a> •
  <a href="#نصب">نصب</a> •
  <a href="#به‌روزرسانی">به‌روزرسانی</a> •
  <a href="#شخصی‌سازی">شخصی‌سازی</a>
</p>

</div>

<a name="معرفی"></a>
## 🎨 معرفی

<p dir="rtl">
قالب صفحه کاربری پنل مرزبان با طراحی مینیمال و کاربرپسند. این پروژه با الهام از 
<a href="https://github.com/dermv/marzbanify-template/tree/main">قالب Marzbanify</a>
و با کسب مجوز از توسعه‌دهنده اصلی، توسعه و ساده‌سازی شده است. در این تمپلیت دو اپلیکیشن قرار دارد: hiddify و sing-box. پیشنهاد میکنم برای استفاده هرچه بهتر از اپلیکیشن sing-box از 
<a href="https://github.com/Mrclocks/MrClock-SingBox-Template">این تمپلیت</a>
استفاده کنید.
</p>

<a name="تغییرات"></a>
## 📋 جزئیات آخرین آپدیت
<details dir="rtl">
<summary>🔄 مشاهده تغییرات آپدیت تیر / جولای</summary>

<div dir="rtl">

- اضافه شدن اپ Happ
- اضافه شدن کپی تمام کانفیگ ها
- آپدیت لینک برنامه ها
- اصلاح و بهینه‌سازی کدها

</div>
</details>

<details dir="rtl">
<summary>🔄 مشاهده تغییرات آپدیت اردیبهشت / اپریل</summary>

<div dir="rtl">

- اضافه شدن لوگو برند
- باز طراحی دکمه ها
- خوانایی بیشتر رنگ ها
- بهبود فاصله ها و اندازه ها
- اصلاح و بهینه‌سازی کدها

</div>
</details>
<details dir="rtl">
<summary>🔄 مشاهده تغییرات آپدیت فروردین / اپریل</summary>

<div dir="rtl">

- اضافه شدن تم روشن
- اضافه شدن زبان انگلیسی
- اضافه شدن QR کد
- اضافه شدن تیتر برند
- بروزرسانی لینک‌ برنامه‌ها
- اصلاح و بهینه‌سازی کدها
- بهینه‌سازی طراحی و رابط کاربری

</div>
</details>

<a name="ویژگی‌ها"></a>
## ✨ ویژگی‌های کلیدی

<div dir="rtl" align="center">

| ویژگی | توضیحات |
|:-----:|---------|
| **⚡ سبک و سریع** | حجم کم و بارگذاری سریع بدون المان‌های اضافه |
| **🎨 طراحی مدرن** | رابط کاربری زیبا و مینیمال با تجربه کاربری بهبودیافته |
| **🛠 نصب آسان** | راه‌اندازی سریع با چند دستور ساده |
| **📱 واکنش‌گرا** | سازگاری کامل با تمام دستگاه‌ها (موبایل، تبلت و دسکتاپ) |
| **🌓 تم روشن و تیره** | پشتیبانی از حالت روشن و تاریک برای خوانایی بهتر |
| **🌐 چند زبانه** | پشتیبانی از زبان‌های فارسی و انگلیسی |
| **⚙️ تنظیمات اتوماتیک** | تنظیمات خودکار برای سهولت در استفاده |

</div>

<a name="نصب"></a>
## 📥 نصب و راه‌اندازی

<div>

### 1️⃣ دانلود فایل قالب

</div>

```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/Mrclocks/MrClock-Subscription-Template/main/index.html
```

<div>

### 2️⃣ ثبت تنظیمات در محیط مرزبان

</div>

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```

<div>

#### 📝 روش جایگزین: اضافه کردن مستقیم به فایل `.env`

مقادیر زیر را مستقیماً در فایل `.env` واقع در `/opt/marzban/` اضافه کنید:

</div>

```bash
CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"
SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
```

<div>

### 3️⃣ راه‌اندازی مجدد مرزبان

</div>

```bash
marzban restart
```

<div>

## 🔄 به‌روزرسانی قالب

<div dir="rtl" align="right">
  <p>برای دریافت آخرین نسخه قالب، کافیست مرحله اول (دانلود فایل قالب) را دوباره اجرا کنید.</p>
</div>

<a name="شخصی‌سازی"></a>
## 🛠 شخصی‌سازی

<div dir="rtl" align="center">

| بخش | توضیحات |
|:-----:|---------|
| **تغییر لینک پشتیبانی** | ویرایش خط 905 |
| **تغییر تیتر صفحه (برند)** | ویرایش خط 559 و 604 |
| **تغییر لوگو صفحه (برند)** | ویرایش خط 555 |
| **تغییر لینک سینگ باکس** | ویرایش خط 1098 |
| **تغییر رنگ‌ها** | ویرایش خط 19 تا 51 |

</div>

<div dir="rtl" align="right">
  <p> از برنامه هایی شبیه VS code برای ویرایش کد ها استفاده کنید. همچنین می‌توانید با استفاده از ابزارهای هوش مصنوعی مانند deepseek به راحتی بخش‌های مختلف را با سلیقه خود تغییر دهید. لازم به ذکر است بیشتر تغییرات صورت گرفته در این کد‌ها توسط هوش مصنوعی انجام شده است.</p>
</div>

---


<div align="center">
  <p dir="rtl">🌟 اگر از این پروژه خوشتان آمد، لطفاً به آن ستاره دهید 🌟</p>
  
  <p>
    <a href="https://github.com/Mrclocks/MrClock-Subscription-Template">
      <img src="https://img.shields.io/github/stars/Mrclocks/MrClock-Subscription-Template?style=social" alt="ستاره‌های گیت‌هاب">
  </p>
  
  <p dir="rtl">با ❤️ توسط MrClock</p>
</div>

# Fingerify Smart Split (ZeroOmega Config)

**Smart Traffic Splitting Solution for Freelancers and Professional Users**

This repository contains an exclusive Rule List configuration for the **ZeroOmega** (or SwitchyOmega) browser extension. The goal is to enable intelligent split tunneling for users within the **[Fingerify Ecosystem](https://github.com/Fingerify/Fingerify-Desktop)**.

By using this setup, your browser intelligently determines which websites (Iranian banks, domestic services) should be accessed using a **Direct/Local connection** and which websites (ِYoutube, general foreign traffic) must pass through your **Server With Fingerify**.

---

## ⚠️ Crucial Warnings
> **❌ IMPORTANT:** These settings are exclusively for standard browsers (e.g., Chrome or standard Edge). **DO NOT** apply these settings to secure or dedicated privacy browsers (e.g., Fingerify Secure Browser or "Blue Chrome"), as this may compromise your identity verification and lead to IP leaks.

---

## 🚀 Zero Omega Setup Guide (Auto Switch Mode)

This method allows you to subscribe to the rules list via URL, enabling automatic updates whenever the list is changed in this repository.

### 1. Configure the Rule List Source
1.  Open the ZeroOmega (or SwitchyOmega) Options and click on **Auto Switch** in the left menu.
2.  Scroll down to the **Rule List Config** section:
    * Set the **Rule List Format** checkbox to **Switchy**.
    * In the **Rule List URL** box, precisely copy and paste the following link:

> `https://raw.githubusercontent.com/fingerify/Fingerify-Smart-Split-ZeroOmega-Config/main/ZeroOmega_Rule_List_Config.sorl`

3.  Click the **Download Profile Now** button. (A green `Rule list downloaded` message should appear).

### 2. Configure the Switching Logic (Switch Rules)
Scroll back up to the **Switch rules** section:
1.  In the **Rule list rules** row (which now contains the Iranian list), set the action menu to **`[Direct]`**.
2.  In the final row, **Default**, set the action menu to your proxy profile (e.g., **Fingerify** or Proxy).

### 3. Save and Activate
1.  Click the **Apply Changes** button from the left menu.
2.  Click the extension icon in your browser toolbar and select the **Auto Switch** profile to activate the configuration.

---

## 🔗 Attribution and Source
This list is based on publicly available data derived from the open-source repository **[Iran Hosted Domains](https://github.com/bootmortis/iran-hosted-domains)**. We acknowledge the contributors of that project. This repository only provides the specific configuration format optimized for ZeroOmega/SwitchyOmega.

---
Maintained by **[Fingerify Team](https://github.com/fingerify)**

---

<details>
<summary>🇮🇷 مشاهده راهنما به زبان فارسی (Farsi Guide)</summary>
    
# 🇮🇷 فارسی: راهکار تفکیک هوشمند ترافیک

**تفکیک هوشمند ترافیک برای فریلنسرها و کاربران حرفه‌ای**

این مخزن حاوی «لیست قوانین» (Rule List) اختصاصی برای افزونه **ZeroOmega** (یا SwitchyOmega) است. هدف این کانفیگ، تفکیک هوشمند ترافیک برای کاربران **[Fingerify](https://github.com/Fingerify/Fingerify-Desktop)** است.

با استفاده از این تنظیمات، مرورگر شما به‌طور هوشمند تشخیص می‌دهد که کدام سایت‌ها (بانک‌ها، خدمات داخلی) باید با **اینترنت عادی** باز شوند و کدام سایت‌ها (Youtube) باید از **Fingerify و آی‌پی سرور** عبور کنند.

---

## ⚠️ هشدارهای مهم
> **❌ توجه بسیار مهم:** این تنظیمات صرفاً برای مرورگرهای عادی (مانند Chrome یا Edge استاندارد) طراحی شده است. **به هیچ عنوان** این تنظیمات را روی مرورگرهای امنیتی خاص (مانند کروم آبی یا Fingerify Secure Browser) اعمال نکنید، زیرا ممکن است باعث نشت هویت شود.

---

## 🚀 آموزش تنظیم Zero Omega (حالت Auto Switch)

این روش به شما امکان می‌دهد لیست دامنه‌ها را به صورت URL وارد کرده و به‌طور خودکار آپدیت دریافت کنید.

### ۱. تنظیم منبع قوانین (Rule List)
1.  وارد تنظیمات (Options) افزونه ZeroOmega شده و از منوی سمت چپ روی گزینه **Auto Switch** کلیک کنید.
2.  به پایین صفحه اسکرول کنید تا بخش **Rule List Config** را ببینید.
    * تیک گزینه **Rule List Format** را روی حالت **Switchy** بگذارید.
    * در کادر **Rule List URL**، لینک زیر را دقیقاً کپی و وارد کنید:

> `https://raw.githubusercontent.com/fingerify/Fingerify-Smart-Split-ZeroOmega-Config/main/ZeroOmega_Rule_List_Config.sorl`

3.  روی دکمه **Download Profile Now** کلیک کنید. (باید پیام سبز رنگ `Rule list downloaded` ظاهر شود).

### ۲. پیکربندی رفتار (Switch Rules)
به بالای همان صفحه برگردید (بخش Switch rules):
1.  در ردیف **Rule list rules** (که اکنون شامل لیست ایران است)، منوی روبرو را روی حالت **`[Direct]`** قرار دهید.
2.  در ردیف آخر یعنی **Default**، منو را روی پروفایل پروکسی خود (مثلاً **Fingerify** یا Proxy) بگذارید.

### ۳. ذخیره و فعال‌سازی
1.  از منوی سمت چپ، دکمه **Apply Changes** را بزنید.
2.  روی آیکون افزونه در نوار بالای مرورگر کلیک کنید و آن را روی حالت **Auto Switch** قرار دهید.

---

## 🔗 منبع و قدردانی
این لیست بر اساس داده‌های عمومی و متن‌باز مخزن **[Iran Hosted Domains](https://github.com/bootmortis/iran-hosted-domains)** تهیه شده است. ما ضمن قدردانی از توسعه‌دهندگان آن پروژه، اعلام می‌کنیم که این مخزن جهت تسهیل استفاده کاربران Fingerify ایجاد شده و صرفاً پیکربندی بهینه را ارائه می‌دهد.

---
توسعه یافته توسط **[Fingerify Team](https://github.com/fingerify)**
</details>

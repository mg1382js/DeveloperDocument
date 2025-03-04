# جاوا اسکریپت
## <code style="color : Gold">مقدمه ای بر معرفی جاوااسکریپت</code>

### <code style="color : Green">جاواسکریپت چیست؟</code>
جاوا اسکریپت (JavaScript) یک زبان برنامه‌نویسی سطح بالا، تفسیر شده و پویا است که عمدتاً برای ایجاد تعامل و پویایی در صفحات وب استفاده می‌شود. جاوا اسکریپت یکی از فناوری‌های اصلی وب، به همراه HTML و CSS است و به طور گسترده در توسعه وب استفاده می‌شود.

#### ویژگی‌های کلیدی جاوا اسکریپت
- اسکریپت نویسی سمت کلاینت: جاوا اسکریپت عمدتاً برای اسکریپت‌نویسی سمت کلاینت استفاده می‌شود و به توسعه‌دهندگان امکان می‌دهد تا صفحات وب را تعاملی و پویا کنند.

- چندمنظوره: علاوه بر استفاده در مرورگرها، جاوا اسکریپت برای برنامه‌نویسی سمت سرور با استفاده از محیط‌هایی مانند Node.js، توسعه برنامه‌های موبایل و حتی توسعه برنامه‌های دسکتاپ استفاده می‌شود.

- رویداد محور: جاوا اسکریپت به راحتی می‌تواند رویدادهای کاربر مانند کلیک‌ها، ارسال فرم‌ها و فشردن کلیدها را مدیریت کند، که این امر به توسعه‌دهندگان اجازه می‌دهد تا رابط‌های کاربری تعاملی ایجاد کنند.

- مبتنی بر نمونه (Prototype-based): جاوا اسکریپت از نمونه‌ها برای وراثت استفاده می‌کند، که این امر آن را از وراثت کلاس‌محور موجود در زبان‌هایی مانند جاوا و ++C متمایز می‌کند.

- توابع درجه اول: توابع در جاوا اسکریپت اشیای درجه اول هستند، به این معنا که می‌توانند در متغیر‌ها ذخیره شوند، به عنوان آرگومان به توابع دیگر پاس داده شوند و از توابع بازگردانده شوند.

- برنامه‌نویسی غیرهمزمان: جاوا اسکریپت از برنامه‌نویسی غیرهمزمان پشتیبانی می‌کند که امکان اجرای عملیات‌هایی مانند درخواست‌های شبکه‌ای را بدون مسدود کردن رشته اصلی فراهم می‌کند. این امر معمولاً با استفاده از کال‌بک‌ها، پرامیس‌ها و async/await انجام می‌شود.

- سبک و تفسیر شده: جاوا اسکریپت یک زبان سبک و تفسیر شده است که این امر به سرعت و کارایی آن کمک می‌کند.

#### کاربردهای رایج جاوا اسکریپت
1. توسعه وب:
- دستکاری DOM: تغییر ساختار و محتوای صفحات وب به صورت پویا.
- اعتبارسنجی فرم: بررسی ورودی‌های کاربر در فرم‌ها قبل از ارسال به سرور.
- AJAX: بارگذاری محتوا بدون نیاز به بازنشانی صفحه.
2. توسعه سمت سرور:

- نود جی اس Node.js: محیط جاوا اسکریپت که امکان اسکریپت‌نویسی سمت سرور و ساخت برنامه‌های شبکه‌ای مقیاس‌پذیر را فراهم می‌کند.
3. توسعه موبایل:


- ری اکت نیتیو React Native:چارچوبی برای ساخت برنامه‌های موبایل بومی با استفاده از جاوا اسکریپت و
- React.Ionic: چارچوبی برای ساخت برنامه‌های موبایل هیبریدی.
4. توسعه برنامه‌های دسکتاپ:

- Electron: چارچوبی برای ساخت برنامه‌های دسکتاپ چندسکویی با استفاده از جاوا اسکریپت، HTML و CSS.
- توسعه بازی: جاوا اسکریپت به همراه HTML5 canvas و WebGL برای ساخت بازی‌های مبتنی بر مرورگر استفاده می‌شود.

مثال کد
در اینجا یک مثال ساده از کد جاوا اسکریپت که محتوای یک عنصر HTML را هنگام کلیک بر روی یک دکمه تغییر می‌دهد:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>JavaScript Example</title>
</head>
<body>
    <h1 id="myHeader">سلام، دنیا!</h1>
    <button onclick="changeText()">روی من کلیک کن</button>

    <script>
        function changeText() {
            document.getElementById("myHeader").innerHTML = "سلام، جاوا اسکریپت!";
        }
    </script>
</body>
</html>
```

در این مثال:

HTML شامل یک هدر (`<h1>`) و یک دکمه است.
دکمه دارای یک ویژگی onclick است که تابع changeText را هنگام کلیک فراخوانی می‌کند.
تابع changeText محتوای داخل عنصر `<h1>` را تغییر می‌دهد.

#### تاریخچه و تکامل
- ایجاد توسط برندان آیک: جاوا اسکریپت در سال 1995 توسط برندان آیک در حالی که در شرکت Netscape Communications کار می‌کرد، ایجاد شد.
- استاندارد ECMAScript: جاوا اسکریپت تحت مشخصات ECMAScript (ECMA-262) استاندارد شده است که توسط Ecma International نگهداری می‌شود.
- تکامل پیوسته: جاوا اسکریپت به طور قابل توجهی در طول سال‌ها با به‌روزرسانی‌های عمده مانند ES5 (2009)، ES6/ES2015 (2015) و نسخه‌های سالانه بعدی که ویژگی‌ها و بهبودهای جدیدی را معرفی کرده‌اند، تکامل یافته است.

جاوا اسکریپت همچنان یکی از محبوب‌ترین و پرکاربردترین زبان‌های برنامه‌نویسی است و نقش کلیدی در توسعه وب مدرن و فراتر از آن ایفا می‌کند.

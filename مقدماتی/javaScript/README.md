# javaScript
## <code style="color : Gold">introduction to javascript</code>

### <code style="color : Green">what is javascript?</code>

JavaScript is a high-level, interpreted programming language primarily used to create interactive effects within web browsers. It is a key technology of the World Wide Web, alongside HTML and CSS, and is essential for developing dynamic and responsive web applications.

#### Key Features of JavaScript
1. Client-Side Scripting: JavaScript is mainly used for client-side scripting, enabling interactive web pages by manipulating the Document Object Model (DOM).

2. Versatility: While traditionally used in web browsers, JavaScript is also used in server-side programming with environments like Node.js, mobile app development, and desktop application development.

3. Event-Driven: JavaScript handles user inputs and browser events, such as clicks, form submissions, and key presses, allowing developers to create highly interactive user interfaces.

4. Prototype-Based: JavaScript uses prototypes for inheritance, which is different from the class-based inheritance found in languages like Java and C++.

5. First-Class Functions: Functions in JavaScript are first-class objects, meaning they can be stored in variables, passed as arguments to other functions, and returned from functions.

6. Asynchronous Programming: JavaScript supports asynchronous programming, making it possible to handle operations like network requests without blocking the main thread. This is often achieved using callbacks, promises, and async/await.

7. Lightweight and Interpreted: JavaScript is a lightweight language that is interpreted at runtime, which contributes to its speed and efficiency.

#### Common Uses of JavaScript
1. Web Development:

   - DOM Manipulation: Changing the structure and content of web pages dynamically.
   - Form Validation: Checking user input in forms before sending it to the server.
   - AJAX: Asynchronous JavaScript and XML for loading content without refreshing the page.

2. Server-Side Development:

   - Node.js: JavaScript runtime that allows server-side scripting and building scalable network applications.

3. Mobile Development:

   - React Native: Framework for building native mobile apps using JavaScript and React.
   - Ionic: Framework for building hybrid mobile apps.

4. Desktop Applications:

   - Electron: Framework for building cross-platform desktop apps using JavaScript, HTML, and CSS.
5. Game Development: JavaScript, along with HTML5 canvas and WebGL, is used for creating browser-based games.

Example Code

Here's a simple example of JavaScript code that changes the content of an HTML element when a button is clicked:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>JavaScript Example</title>
</head>
<body>
    <h1 id="myHeader">Hello, World!</h1>
    <button onclick="changeText()">Click me</button>

    <script>
        function changeText() {
            document.getElementById("myHeader").innerHTML = "Hello, JavaScript!";
        }
    </script>
</body>
</html>
```
In this example:
- The HTML contains a header (`<h1>`) and a button.
- The button has an onclick attribute that calls the changeText function when clicked.
- The changeText function changes the text inside the <`h1`> element.

#### History and Evolution
- Created by Brendan Eich: JavaScript was created by Brendan Eich in 1995 while he was working at Netscape Communications Corporation.
- ECMAScript: JavaScript is standardized under the ECMAScript specification (ECMA-262), maintained by Ecma International.
- Continuous Evolution: JavaScript has evolved significantly over the years with major updates like ES5 (2009), ES6/ES2015 (2015), and subsequent annual releases introducing new features and syntax improvements.

JavaScript remains one of the most popular and widely used programming languages, playing a crucial role in modern web development and beyond.


### <code style="color : Green">how to run javascript?</code>

To run JavaScript, you have several options depending on your environment and use case. Here are some common methods:

1. Running JavaScript in a Web Browser
   Most commonly, JavaScript is run in a web browser. Here's how you can do it:

   a. Using the Browser Console
   1. Open your web browser (e.g., Chrome, Firefox).
   2. Open the Developer Tools (usually accessible via F12 or Ctrl+Shift+I).
   Go to the "Console" tab.
   Type your JavaScript code and press Enter to run it.

  Example:
```js
console.log("Hello, World!");
```

   b. Embedding JavaScript in an HTML File
   1.  Create an HTML file (e.g., index.html).
   2. Embed your JavaScript code within <`script`> tags.

Example:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>JavaScript Example</title>
</head>
<body>
    <script>
        console.log("Hello, World!");
    </script>
</body>
</html>
```

Open the HTML file in a web browser to see the output
2.  Running JavaScript with Node.js
   Node.js is a JavaScript runtime that allows you to run JavaScript on the server side or outside the browser.
 
      a. Installing Node.js
      Download and install Node.js from the [official website](https://nodejs.org/).
   
- Running JavaScript Code
   - Open a terminal or command prompt.
   - Create a JavaScript file (e.g., app.js).
   - Write your JavaScript code in the file.

Example (app.js):
```js
console.log("Hello, World!");
```
Run the file using Node.js:
```
node app.js
```

3. Online JavaScript Editors
You can also run JavaScript code using online editors and playgrounds such as:

- [JSFiddle](https://jsfiddle.net/)
- [CodePen](https://codepen.io/)
- [JSBin](https://jsbin.com/)

These platforms allow you to write, run, and share JavaScript code directly in your web browser.

4. Integrated Development Environments (IDEs)
   You can use IDEs like Visual Studio Code, WebStorm, or Sublime Text to write and run JavaScript code. These tools often provide integrated terminals and debugging tools to make development easier.

Example with Visual Studio Code
- Install Visual Studio Code from the official website.
- Open or create a new JavaScript file.
- Write your JavaScript code.
- Open the integrated terminal (Ctrl+).
- Run the file using Node.js:
```
node yourfile.js
```
These are some of the most common ways to run JavaScript code. Depending on your project and development environment, you can choose the method that best suits your needs.







---------------------------------------------------------------------------------

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

- Node.js: محیط جاوا اسکریپت که امکان اسکریپت‌نویسی سمت سرور و ساخت برنامه‌های شبکه‌ای مقیاس‌پذیر را فراهم می‌کند.
3. توسعه موبایل:


- React Native:چارچوبی برای ساخت برنامه‌های موبایل بومی با استفاده از جاوا اسکریپت و 
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





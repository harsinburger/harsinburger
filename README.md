<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>هرسین برگر | بهترین برگر شهر</title>
    <style>
        /* استایل کلی */
        body {
            font-family: 'Vazir', 'Tanha', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            text-align: center;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        /* هدر و ناوبری */
        header {
            background-color: #d35400; /* نارنجی جذاب برای غذا */
            color: white;
            padding: 20px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        /* بخش معرفی */
        .hero {
            padding: 60px 20px;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1551782450-17144efb9c50?ixlib=rb-4.0.3');
            background-size: cover;
            background-position: center;
            color: white;
        }
        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .btn {
            display: inline-block;
            background-color: #e67e22;
            color: white;
            padding: 12px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
        }

        /* بخش منو */
        .menu {
            padding: 60px 20px;
            background-color: #fff;
        }
        .menu-items {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 40px;
        }
        .menu-item {
            background: #f8f8f8;
            border-radius: 10px;
            padding: 20px;
            width: 250px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }
        .menu-item img {
            width: 100%;
            border-radius: 8px;
            height: 160px;
            object-fit: cover;
        }

        /* فوتر */
        footer {
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 30px 0;
            margin-top: 40px;
        }
        .contact-info {
            margin-bottom: 20px;
        }
    </style>
    <!-- لینک فونت فارسی Vazir (اختیاری) -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rastikerdar/vazir-font@v30.1.0/dist/font-face.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>هرسین برگر</h1>
            <nav>
                <a href="#menu">منو</a>
                <a href="#about">درباره ما</a>
                <a href="#contact">تماس</a>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>لذیذترین برگرها را در هرسین برگر تجربه کنید</h1>
            <p>با بهترین مواد اولیه و دستور پخت خاص</p>
            <a href="#menu" class="btn">مشاهده منو</a>
        </div>
    </section>

    <section id="menu" class="menu">
        <div class="container">
            <h2>منوی ما</h2>
            <div class="menu-items">
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1551782450-a2132b4ba21d?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="برگر کلاسیک">
                    <h3>برگر کلاسیک</h3>
                    <p>نان برگر، همبرگر ۱۵۰ گرمی، پنیر چدار، کاهو، گوجه</p>
                    <p><strong>۱۲۰,۰۰۰ تومان</strong></p>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="برگر ویژه">
                    <h3>برگر ویژه هرسین</h3>
                    <p>برگر دوبل، پنیر، قارچ، پیاز کاراملی، سس ویژه</p>
                    <p><strong>۱۸۰,۰۰۰ تومان</strong></p>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1571091718767-18b5b1457add?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80" alt="سیب زمینی سرخ کرده">
                    <h3>سیب زمینی ویژه</h3>
                    <p>سیب زمینی خلالی با پوست و ادویه مخصوص</p>
                    <p><strong>۴۵,۰۰۰ تومان</strong></p>
                </div>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>درباره هرسین برگر</h2>
            <p>ما از سال ۱۴۰۰ با عشق به غذاهای باکیفیت و سرویس سریع شروع به کار کردیم. هدف ما رضایت شماست.</p>
        </div>
    </section>

    <footer id="contact">
        <div class="container">
            <div class="contact-info">
                <h3>راه های ارتباطی</h3>
                <p>آدرس: شهر هرسین، بلوار اصلی، برگر هرسین</p>
                <p>تلفن سفارش: ۰۸۱۳ XXX XXXX (شماره خود را جایگزین کنید)</p>
                <p>اینستاگرام: <a href="https://instagram.com/harsinburger" style="color: #ecf0f1;">@harsinburger</a></p>
            </div>
            <p><strong>هرسین برگر © ۱۴۰۳</strong></p>
        </div>
    </footer>

</body>
</html>

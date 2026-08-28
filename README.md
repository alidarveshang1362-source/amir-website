<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>سایت من 😎</title>

    <style>
        * {
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            font-family: Tahoma, Arial, sans-serif;
            background: #f1f3f6;
            color: #222;
        }

        /* منوی سایت */
        nav {
            position: sticky;
            top: 0;
            z-index: 100;
            background: #111;
            padding: 16px;
            text-align: center;
        }

        nav a {
            display: inline-block;
            color: white;
            text-decoration: none;
            margin: 5px 10px;
            padding: 10px 16px;
            border-radius: 12px;
            transition: 0.3s;
        }

        nav a:hover {
            background: white;
            color: #111;
            transform: translateY(-3px);
        }

        /* صفحه اصلی */
        header {
            min-height: 75vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 30px;
            background: linear-gradient(135deg, #222, #555);
            color: white;
        }

        header h1 {
            font-size: 45px;
            margin-bottom: 10px;
            animation: appear 1s ease;
        }

        header p {
            font-size: 20px;
        }

        /* کارت‌ها */
        .card {
            background: white;
            width: 85%;
            max-width: 600px;
            margin: 50px auto;
            padding: 35px;
            border-radius: 25px;
            text-align: center;
            box-shadow: 0 8px 25px #bbb;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
        }

        /* دکمه */
        button {
            border: none;
            background: #222;
            color: white;
            padding: 14px 28px;
            border-radius: 14px;
            font-size: 17px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            transform: scale(1.08);
            background: #444;
        }

        footer {
            text-align: center;
            background: #111;
            color: white;
            padding: 25px;
            margin-top: 60px;
        }

        @keyframes appear {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>

<body>

    <nav>
        <a href="#home">🏠 خانه</a>
        <a href="#about">👤 درباره من</a>
        <a href="#contact">📞 تماس با من</a>
    </nav>

    <header id="home">
        <h1>سلام! 😎</h1>
        <p>به سایت من خوش آمدی</p>

        <button onclick="welcome()">
            کلیک کن 🚀
        </button>
    </header>

    <section class="card" id="about">
        <h2>👤 درباره من</h2>
        <p>
            سلام! من صاحب این سایت هستم.
            این اولین سایت منه و دارم برنامه‌نویسی یاد می‌گیرم.
        </p>
    </section>

    <section class="card" id="contact">
        <h2>📞 تماس با من</h2>
        <p>
            این قسمت را می‌توانیم بعداً با اطلاعات تماس یا شبکه‌های اجتماعی کامل کنیم.
        </p>
    </section>

    <footer>
        ساخته شده با ❤️ و کدنویسی
    </footer>

    <script>
        function welcome() {
            alert("سلام! خوش اومدی 😎🚀");
        }
    </script>

</body>
</html>

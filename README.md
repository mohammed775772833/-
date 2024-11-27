<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ملوك التنجيد</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center; /* محاذاة النص في الوسط */
        }
        header {
            background-color: #8B4513; /* بني داكن */
            color: white;
            padding: 20px 0;
        }
        nav {
            background-color: #D2B48C; /* بني فاتح */
            display: flex;
            justify-content: center;
            padding: 15px 0;
        }
        nav a {
            color: #8B4513; /* بني داكن */
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .marquee {
            background: #FFD700; /* ذهبي */
            color: #8B4513; /* بني داكن */
            font-size: 20px;
            padding: 10px;
            overflow: hidden;
            white-space: nowrap;
        }
        .marquee div {
            display: inline-block;
            animation: marquee 10s linear infinite;
        }
        @keyframes marquee {
            from { transform: translateX(100%); }
            to { transform: translateX(-100%); }
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        h1 {
            font-size: 20px; /* الخط العريض */
            font-weight: bold;
            color: #FFD700; /* ذهبي */
        }
        h2 {
            font-size: 24px;
            margin-top: 20px;
            color: #8B4513; /* بني داكن */
        }
        .icon-container {
            display: flex;
            justify-content: center;
            margin-top: 20px;
            flex-wrap: wrap;
        }
        .icon {
            text-align: center;
            transition: transform 0.3s;
            background: #D2B48C; /* بني فاتح */
            border-radius: 50%;
            width: 80px;
            height: 80px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            margin: 10px;
        }
        .icon:hover {
            transform: scale(1.1);
        }
        .icon i {
            font-size: 36px;
            color: #8B4513; /* بني داكن */
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #777;
        }
        @media (max-width: 600px) {
            .icon {
                width: 60px;
                height: 60px;
            }
            .icon i {
                font-size: 28px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>ملوك التنجيد</h1>
</header>

<div class="marquee">
    <div>مرحبًا بكم في ملوك التنجيد، حيث نقدم أفضل خدمات التنجيد الاحترافي!</div>
</div>

<nav>
    <a href="#about">من نحن</a>
    <a href="#vision">الرؤية والرسالة</a>
    <a href="#contact">تواصل معنا</a>
</nav>

<div class="container">
    <section id="about">
        <h1>من نحن</h1>
        <p>نحن ملوك التنجيد، نقدم أفضل خدمات التنجيد الاحترافي في اليمن. نلتزم بتقديم أعلى مستويات الجودة والابتكار في تصميم وتنفيذ خدمات التنجيد.</p>
    </section>

    <section id="vision">
        <h2>الرؤية</h2>
        <p>أن نكون الرائدين في مجال خدمات التنجيد الاحترافي في اليمن.</p>
        
        <h2>الرسالة</h2>
        <p>نحن نلتزم بتقديم خدمات تنجيد كراسي السيارات بأعلى معايير الجودة والاحترافية.</p>
    </section>

    <section id="services">
        <h2>خدماتنا</h2>
        <div class="icon-container">
            <div class="icon">
                <i class="fas fa-couch"></i>
            </div>
            <div class="icon">
                <i class="fas fa-car"></i>
            </div>
            <div class="icon">
                <i class="fas fa-paint-brush"></i>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>تواصل معنا</h2>
        <p>للتواصل معنا، يمكنك استخدام المعلومات التالية:</p>
        <p>فيسبوك: <strong>@carym.ye</strong></p>
        <p>رقم الاتصال: <strong>775772833</strong></p>
        <p>العنوان: <strong>الإدارة العامة، صنعاء</strong></p>
    </section>
</div>

<footer>
    <p>جميع الحقوق محفوظة &copy; 2023 ملوك التنجيد</p>
</footer>

</body>
</html>

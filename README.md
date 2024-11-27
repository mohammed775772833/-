html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ملوك التنجيد لخدمات التنجيد</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        header {
            background: #35424a;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #35424a;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ff5722;
        }
        section {
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #777;
        }
        .marquee {
            background: #ff5722;
            color: white;
            font-size: 24px;
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
        .icon-container {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .icon {
            text-align: center;
            transition: transform 0.3s;
        }
        .icon:hover {
            transform: scale(1.1);
        }
        .icon i {
            font-size: 40px;
            color: #ff5722;
        }
    </style>
</head>
<body>

<header>
    <h1>ملوك التنجيد لخدمات التنجيد</h1>
</header>

<div class="marquee">
    <div>ملوك التنجيد ترحب بكم</div>
</div>

<nav>
    <a href="#">الرئيسية</a>
    <a href="#">من نحن</a>
    <a href="#">خدماتنا</a>
    <a href="#">الرؤية</a>
    <a href="#">تواصل معنا</a>
</nav>

<section>
    <h2>الرؤية</h2>
    <p>أن نكون الرائدين في مجال خدمات التنجيد الاحترافي في اليمن، من خلال تقديم أعلى مستويات الجودة والابتكار في تصميم وتنفيذ خدمات التنجيد، مما يسهم في تلبية احتياجات عملائنا، حيث تسعى دائماً لتقديم الأفضل وتوسيع نطاق خدماتها لتلبية احتياجات السوق.</p>
</section>

<section>
    <h2>الرسالة</h2>
    <p>نحن في "ملوك التنجيد" نلتزم بتقديم خدمات تنجيد كراسي السيارات بأعلى معايير الجودة والاحترافية. نسعى لتحقيق رضا العملاء من خلال استخدام أفضل المواد والتقنيات الحديثة، مع التركيز على الابتكار والاهتمام بالتفاصيل. هدفنا هو تحويل كل سيارة إلى تجربة فريدة تعكس ذوق العميل واحتياجاته.</p>
</section>

<section>
    <h2>الشحن</h2>
    <p>الشحن متاح إلى أنحاء الجمهورية اليمنية.</p>
</section>

<section>
    <h2>من نحن</h2>
    <p>في ملوك التنجيد، نُقدّم لكم أكثر من مجرد خدمة تنجيد. نُقدّم لكم تجربةً فريدةً تجمع بين الحرفية العالية والتصميم الراقي، لنُضفي على أثاثكم لمسةً من الفخامة والتميّز.</p>
</section>

<section>
    <h2>خدماتنا</h2>
    <div class="icon-container">
        <div class="icon">
            <i class="fas fa-couch"></i>
            <p>تنجيد الأثاث</p>
        </div>
        <div class="icon">
            <i class="fas fa-car"></i>
            <p>تنجيد السيارات</p>
        </div>
        <div class="icon">
            <i class="fas fa-paint-brush"></i>
            <p>تصميم مخصص</p>
        </div>
    </div>
</section>

<footer>
    <p>جميع الحقوق محفوظة &copy; 2023 ملوك التنجيد</p>
</footer>

</body>
</html>

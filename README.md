<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Arai Consulting | Заңгерлік Көмек</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --gold: #D4AF37;
            --black: #0d0d0d;
            --card-bg: rgba(22, 22, 22, 0.9);
            --white: #ffffff;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            background-color: var(--black);
            color: var(--white);
            font-family: 'Inter', sans-serif;
            overflow-x: hidden;
        }

        /* БАННЕРДІ (ФОНДЫ) РЕТТЕУ */
        .hero {
            width: 100%;
            min-height: 50vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-end; /* Мазмұнды төменге ығыстыру */
            padding-bottom: 30px;
            background-image: linear-gradient(to bottom, rgba(13,13,13,0.5), var(--black)), 
                              url('https://images.unsplash.com/photo-1589829545856-d10d557cf95f?q=80&w=1000');
            /* background-position: center 20% - фонды төмен түсіреді */
            background-position: center 25%;
            background-size: cover;
            background-repeat: no-repeat;
        }

        /* ЛОГОТИП СТИЛІ */
        .logo-box {
    width: 180px;  /* Ені */
    height: 180px; /* Биіктігі (Екеуі бірдей болуы керек!) */
    margin-bottom: 15px;
    filter: drop-shadow(0 0 15px rgba(212, 175, 55, 0.5));
    overflow: hidden; /* Артық жерлерін кесіп тастайды */
}

       .logo-img {
    width: 100%;
    height: 100%; /* Биіктігін де 100% қыламыз */
    display: block;
    object-fit: cover; /* Сурет созылып кетпеуі үшін өте маңызды */
    border-radius: 50%; /* Міне, осы жол фотоны домалақ қылады */
    border: 3px solid var(--gold); /* Айналасына алтын жиек қосады */
}

        .main-title {
            font-size: 1.8rem;
            text-transform: uppercase;
            font-weight: 800;
            background: linear-gradient(to right, #BF953F, #FCF6BA, #B38728);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            letter-spacing: 1px;
        }

        .tagline {
            color: var(--gold);
            font-size: 0.85rem;
            font-weight: 600;
            margin-top: 5px;
            letter-spacing: 3px;
        }

        /* ПРАЙС БӨЛІМІ */
        .container {
            width: 100%;
            max-width: 480px;
            margin: 0 auto;
            padding: 10px 15px 40px 15px;
        }

        .price-item {
            background: var(--card-bg);
            margin-bottom: 10px;
            padding: 18px 20px;
            border-radius: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border: 1px solid #222;
            backdrop-filter: blur(5px);
        }

        .service { display: flex; align-items: center; gap: 12px; }
        .service i { color: var(--gold); font-size: 1.1rem; width: 20px; text-align: center; }
        .name { font-size: 0.95rem; color: #efefef; }
        .price { color: var(--gold); font-weight: 700; font-size: 1rem; }

        /* БАТЫРМАЛАР */
        .contact-group {
            display: grid;
            gap: 12px;
            margin-top: 25px;
        }

        .btn {
            padding: 16px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: 700;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            transition: 0.3s;
        }

        .btn-wa { background: #25D366; color: white; }
        .btn-insta { background: linear-gradient(45deg, #f09433, #dc2743, #bc1888); color: white; }

        /* FLOAT BUTTON */
        .float-wa {
            position: fixed;
            bottom: 25px;
            right: 25px;
            background: #25D366;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            color: white;
            box-shadow: 0 5px 15px rgba(0,0,0,0.4);
            z-index: 1000;
        }
    </style>
</head>
<body>

    <div class="hero">
        <div class="logo-box">
            <img src="logo.png" alt="Arai Consulting" class="logo-img" onerror="this.src='https://i.ibb.co/Xz9kH0h/image.png'">
        </div>
        <h1 class="main-title">Arai Consulting</h1>
        <p class="tagline">I WILL LIFT BANK ARRESTS</p>
    </div>

    <div class="container">
        <div class="price-list">
            <div class="price-item"><div class="service"><i class="fas fa-file-invoice"></i><span class="name">Нотариальный</span></div><span class="price">5 000 ₸</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-gavel"></i><span class="name">Сот</span></div><span class="price">15 000 ₸</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-university"></i><span class="name">Банкроттыққа</span></div><span class="price">20 000 ₸+</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-bolt"></i><span class="name">Ускоренный</span></div><span class="price">10 000 ₸+</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-laptop"></i><span class="name">Егов</span></div><span class="price">1 000 ₸+</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-car-crash"></i><span class="name">Страховка</span></div><span class="price">10%</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-chart-line"></i><span class="name">Рейтинг көтеру</span></div><span class="price">20 000 ₸</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-baby"></i><span class="name">Алимент</span></div><span class="price">10 000 ₸</span></div>
            <div class="price-item"><div class="service"><i class="fas fa-user-shield"></i><span class="name">Жұмыссыздық</span></div><span class="price">7 000 ₸</span></div>
        </div>

        <div class="contact-group">
            <a href="https://wa.me/77716574345" class="btn btn-wa"><i class="fab fa-whatsapp"></i> WhatsApp-қа жазу</a>
            <a href="https://www.instagram.com/arai_aueskhanovna?igsh=dzVnenAwZDA1ZHRt" target="_blank" class="btn btn-insta"><i class="fab fa-instagram"></i> Instagram</a>
        </div>
    </div>

    <a href="https://wa.me/77716574345" class="float-wa"><i class="fab fa-whatsapp"></i></a>

</body>
</html>

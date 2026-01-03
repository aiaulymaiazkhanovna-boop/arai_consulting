<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arai Consulting | Толық Прайс</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root { --gold: #D4AF37; --black: #0d0d0d; }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { background-color: var(--black); color: white; font-family: sans-serif; }

        /* БАННЕР */
        .hero {
            width: 100%;
            min-height: 40vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: linear-gradient(to bottom, rgba(0,0,0,0.4), var(--black)), 
                        url('https://images.unsplash.com/photo-1589829545856-d10d557cf95f?q=80&w=1000');
            background-position: center 25%;
            background-size: cover;
            padding: 40px 20px;
        }

        /* ДОМАЛАҚ ЛОГОТИП */
        .logo-box {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid var(--gold);
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.5);
            margin-bottom: 15px;
            background: black;
        }

        .logo-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .main-title {
            font-size: 1.8rem;
            background: linear-gradient(to right, #BF953F, #FCF6BA, #B38728);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 800;
            text-transform: uppercase;
            text-align: center;
        }

        /* КОНТЕЙНЕР ЖӘНЕ ПРАЙС КАРТОЧКАЛАРЫ */
        .container { width: 100%; max-width: 450px; margin: 0 auto; padding: 20px; }
        
        .price-card {
            background: #1a1a1a;
            margin-bottom: 8px;
            padding: 14px 18px;
            border-radius: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-left: 3px solid var(--gold);
            font-size: 0.95rem;
        }

        .price-card b { color: var(--gold); }

        /* БАТЫРМАЛАР */
        .btn-group { display: grid; gap: 10px; margin-top: 25px; padding-bottom: 30px; }
        .btn { padding: 16px; border-radius: 12px; text-decoration: none; text-align: center; font-weight: bold; display: flex; align-items: center; justify-content: center; gap: 10px; }
        .btn-wa { background: #25D366; color: white; }
        .btn-insta { background: linear-gradient(45deg, #f09433, #dc2743, #bc1888); color: white; }
    </style>
</head>
<body>

    <div class="hero">
        <div class="logo-box">
            <img src="logo.png" onerror="this.src='https://i.ibb.co/Xz9kH0h/image.png'">
        </div>
        <h1 class="main-title">Arai Consulting</h1>
        <p style="color: var(--gold); letter-spacing: 2px; font-size: 0.75rem; margin-top: 5px;">МЕН АРЕСТТЕРДІ ШЕШЕМІН</p>
    </div>

    <div class="container">
        <div class="price-card"><span>Нотариальный</span><b>5 000 ₸</b></div>
        <div class="price-card"><span>Сот</span><b>15 000 ₸</b></div>
        <div class="price-card"><span>Банкроттыққа</span><b>20 000 ₸+</b></div>
        <div class="price-card"><span>Ускоренный</span><b>10 000 ₸+</b></div>
        <div class="price-card"><span>Егов</span><b>1 000 ₸+</b></div>
        <div class="price-card"><span>Страховка қайтару</span><b>10%</b></div>
        <div class="price-card"><span>Кредиттік рейтинг</span><b>20 000 ₸</b></div>
        <div class="price-card"><span>Алимент</span><b>10 000 ₸</b></div>
        <div class="price-card"><span>Жұмыссыздық бойынша</span><b>7 000 ₸</b></div>
        
        <div class="btn-group">
            <a href="https://wa.me/77716574345" class="btn btn-wa"><i class="fab fa-whatsapp"></i> WhatsApp жазу</a>
            <a href="https://www.instagram.com/arai_aueskhanovna" target="_blank" class="btn btn-insta"><i class="fab fa-instagram"></i> Instagram</a>
        </div>
    </div>

</body>
</html>

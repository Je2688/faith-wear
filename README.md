# faith-wear<!DOCTYPE html>
<html>
<head>
    <title>Faith Wear - Christian Clothing Brand</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: Arial, sans-serif; }
        
        header {
            background: white;
            padding: 20px 40px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .logo {
            font-size: 28px;
            font-weight: bold;
        }
        
        .hero {
            background: linear-gradient(to right, #2d5016, #1a3010);
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        
        .hero h1 {
            font-size: 60px;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 24px;
            margin-bottom: 30px;
        }
        
        .container {
            max-width: 1200px;
            margin: 80px auto;
            padding: 0 20px;
        }
        
        h2 {
            text-align: center;
            font-size: 40px;
            margin-bottom: 50px;
        }
        
        .products {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 40px;
        }
        
        .product {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .product img {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }
        
        .product-info {
            padding: 25px;
        }
        
        .product h3 {
            font-size: 22px;
            margin-bottom: 10px;
        }
        
        .verse {
            color: #2d5016;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .price {
            font-size: 28px;
            font-weight: bold;
            margin-top: 20px;
        }
        
        .mission {
            background: #1a1a1a;
            color: white;
            text-align: center;
            padding: 80px 20px;
        }
        
        .mission p {
            font-size: 20px;
            max-width: 800px;
            margin: 0 auto 20px;
            line-height: 1.8;
        }
        
        .highlight {
            color: #4CAF50;
            font-weight: bold;
        }
        
        footer {
            background: black;
            color: white;
            text-align: center;
            padding: 40px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">✝ Faith Wear</div>
    </header>

    <div class="hero">
        <h1>Wear Your Faith</h1>
        <p>Bold designs. Biblical truth. Authentic style.</p>
    </div>

    <div class="container">
        <h2>Our Collection</h2>
        <div class="products">
            <div class="product">
                <img src="https://i.imgur.com/miEFHur.jpeg" alt="Cross Pendant Necklace">
                <div class="product-info">
                    <h3>Cross Pendant Necklace</h3>
                    <div class="verse">Matthew 16:24</div>
                    <p>Elegant striped cross pendant on adjustable yellow cord - carry your faith with you</p>
                    <div class="price">$35</div>
                </div>
            </div>

            <div class="product">
                <img src="https://i.imgur.com/vzQBj64.jpeg" alt="Faith Over Fear Sticker">
                <div class="product-info">
                    <h3>Faith Over Fear Sticker</h3>
                    <div class="verse">2 Timothy 1:7</div>
                    <p>Durable vinyl sticker - perfect for laptops, water bottles, and more</p>
                    <div class="price">$4</div>
                </div>
            </div>

            <div class="product">
                <img src="https://i.imgur.com/f2p5sK7.jpeg" alt="Cross Sticker">
                <div class="product-info">
                    <h3>Cross Sticker</h3>
                    <div class="verse">John 3:16</div>
                    <p>Classic blue cross design sticker - share your faith everywhere</p>
                    <div class="price">$4</div>
                </div>
            </div>
        </div>
    </div>

    <div class="mission">
        <h2>Our Mission</h2>
        <p>Faith Wear exists to create high-quality Christian apparel that empowers believers to share their faith boldly and authentically.</p>
        <p><span class="highlight">10% of all profits</span> go directly to supporting Bible translation projects and church planting efforts globally.</p>
    </div>

    <footer>
        <p>&copy; 2024 Faith Wear. All rights reserved.</p>
        <p>Philippians 4:13</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Faith Wear - Christian Clothing Brand</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: white;
            padding: 20px 40px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 32px;
            font-weight: bold;
            color: #2d5016;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .hero {
            background: linear-gradient(135deg, #2d5016 0%, #1a3010 100%);
            color: white;
            text-align: center;
            padding: 120px 20px;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg"><path d="M45 10h10v35h35v10H55v35H45V55H10V45h35V10z" fill="rgba(255,255,255,0.03)"/></svg>');
            opacity: 0.3;
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .hero h1 {
            font-size: 64px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            animation: fadeInUp 1s ease;
        }

        .hero p {
            font-size: 26px;
            margin-bottom: 40px;
            opacity: 0.95;
            animation: fadeInUp 1s ease 0.2s backwards;
        }

        .btn {
            display: inline-block;
            background: white;
            color: #2d5016;
            padding: 18px 40px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 18px;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            animation: fadeInUp 1s ease 0.4s backwards;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.3);
            background: #f0f0f0;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .container {
            max-width: 1200px;
            margin: 100px auto;
            padding: 0 40px;
        }

        h2 {
            text-align: center;
            font-size: 48px;
            margin-bottom: 20px;
            color: #2d5016;
        }

        .subtitle {
            text-align: center;
            font-size: 20px;
            color: #666;
            margin-bottom: 60px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .product {
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            overflow: hidden;
            transition: all 0.4s ease;
        }

        .product:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0,0,0,0.15);
        }

        .product img {
            width: 100%;
            height: 380px;
            object-fit: cover;
            transition: transform 0.4s ease;
        }

        .product:hover img {
            transform: scale(1.05);
        }

        .product-info {
            padding: 30px;
        }

        .product h3 {
            font-size: 24px;
            margin-bottom:

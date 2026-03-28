Em sử dụng Google Germini
Đoạn code HTML ban đầu :
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>MacBook Neo - Pure HTML Version</title>
</head>
<body bgcolor="#f5f5f7" text="#1d1d1f">

    <center>
        <font size="2" face="Arial">
            Chọn quốc gia hoặc khu vực khác để xem nội dung dành riêng cho vị trí của bạn và mua sắm trực tuyến.
            <select>
                <option>Việt Nam</option>
                <option>United States</option>
            </select>
            <button><b>Tiếp Tục</b></button>
        </font>
    </center>

    <hr size="1" color="#d2d2d7">

    <center>
        <font size="2" face="Arial">
            <b>🍎</b> &nbsp;&nbsp;
            <a href="#">Store</a> &nbsp;&nbsp;
            <a href="#">Mac</a> &nbsp;&nbsp;
            <a href="#">iPad</a> &nbsp;&nbsp;
            <a href="#">iPhone</a> &nbsp;&nbsp;
            <a href="#">Watch</a> &nbsp;&nbsp;
            <a href="#">Vision</a> &nbsp;&nbsp;
            <a href="#">AirPods</a> &nbsp;&nbsp;
            <a href="#">TV & Home</a> &nbsp;&nbsp;
            <a href="#">Support</a> &nbsp;&nbsp;
            🔍 &nbsp; 🛍️
        </font>
    </center>

    <br>

    <center>
        <font face="Arial">
            <br><br>
            <h1><font size="7">MacBook Neo</font></h1>
            <p><font size="5">Amazing Mac. Surprising price.</font></p>
            
            <p>
                <a href="#"><b><font color="#0071e3">Learn more ></font></b></a> 
                &nbsp;&nbsp;&nbsp;
                <a href="#"><b><font color="#0071e3">Buy ></font></b></a>
            </p>

            <br>
            
            <img src="https://images2.thanhnien.vn/528068263637045248/2026/3/4/1-1772602806217212488364.jpg" 
                 alt="MacBook" 
                 width="600">
        </font>
    </center>

    <br><br>

</body>
</html>

Sau khi sử Ai và ra lệnh thì em được đoạn code sau:
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MacBook Neo - Apple Style</title>
    <style>
        /* 1. CÀI ĐẶT CHUNG: Font chữ và Reset lề */
        body {
            margin: 0;
            padding: 0;
            font-family: "SF Pro Display", "Helvetica Neue", Arial, sans-serif;
            background-color: #ffffff;
            color: #1d1d1f;
            line-height: 1.5;
        }

        /* 2. THANH THÔNG BÁO VỊ TRÍ (Top Banner) */
        .top-banner {
            background-color: #f5f5f7;
            padding: 12px 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 15px;
            font-size: 12px;
            border-bottom: 1px solid #d2d2d7;
        }
        .top-banner select {
            border: 1px solid #d2d2d7;
            border-radius: 4px;
            padding: 2px 8px;
            background: white;
        }
        .btn-continue {
            background-color: #0071e3;
            color: white;
            border: none;
            padding: 4px 12px;
            border-radius: 12px;
            cursor: pointer;
            font-size: 11px;
        }

        /* 3. THANH ĐIỀU HƯỚNG (Navigation Bar) */
        .navbar {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 12px 0;
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px); /* Hiệu ứng mờ nền của Apple */
        }
        .navbar a {
            text-decoration: none;
            color: #1d1d1f;
            font-size: 12px;
            margin: 0 15px;
            opacity: 0.8;
            transition: opacity 0.3s;
        }
        .navbar a:hover {
            opacity: 1;
        }

        /* 4. VÙNG NỘI DUNG CHÍNH (Hero Section) */
        .hero {
            text-align: center;
            padding-top: 60px;
        }
        .hero h1 {
            font-size: 56px;
            font-weight: 600;
            margin: 0;
            letter-spacing: -0.005em;
        }
        .hero p {
            font-size: 26px;
            margin: 10px 0 20px;
            font-weight: 400;
        }

        /* 5. NÚT BẤM (Call to Action Buttons) */
        .cta-group {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 40px;
        }
        .btn-blue {
            background-color: #0071e3;
            color: white;
            padding: 8px 18px;
            border-radius: 980px;
            text-decoration: none;
            font-weight: 400;
        }
        .btn-outline {
            color: #0071e3;
            border: 1px solid #0071e3;
            padding: 8px 18px;
            border-radius: 980px;
            text-decoration: none;
        }
        .btn-blue:hover { background-color: #0077ed; }

        /* 6. HÌNH ẢNH SẢN PHẨM */
        .product-img {
            max-width: 800px;
            width: 100%;
            height: auto;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <div class="top-banner">
        <span>Chọn quốc gia hoặc khu vực khác để xem nội dung dành riêng cho vị trí của bạn và mua sắm trực tuyến.</span>
        <select>
            <option>Việt Nam</option>
            <option>United States</option>
        </select>
        <button class="btn-continue">Tiếp Tục</button>
    </div>

    <nav class="navbar">
        <a href="#" style="font-size: 18px;"></a>
        <a href="#">Store</a>
        <a href="#">Mac</a>
        <a href="#">iPad</a>
        <a href="#">iPhone</a>
        <a href="#">Watch</a>
        <a href="#">Vision</a>
        <a href="#">AirPods</a>
        <a href="#">TV & Home</a>
        <a href="#">Support</a>
        <a href="#">🔍</a>
        <a href="#">🛍️</a>
    </nav>

    <section class="hero">
        <h1>MacBook Neo</h1>
        <p>Amazing Mac. Surprising price.</p>
        
        <div class="cta-group">
            <a href="#" class="btn-blue">Learn more</a>
            <a href="#" class="btn-outline">Buy</a>
        </div>

        <img src="https://images2.thanhnien.vn/528068263637045248/2026/3/4/1-1772602806217212488364.jpg" 
             alt="MacBook Neo" 
             class="product-img">
    </section>

</body>
</html>

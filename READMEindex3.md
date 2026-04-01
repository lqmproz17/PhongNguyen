
---
## I. AI
Nền tảng: Google Germini

---

## II. Lệnh cho AI
> Đoạn code HTML ban đầu :
```
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
```
**Yêu cầu chỉnh sửa sao cho khớp với giao diện trong hình ảnh được gửi:**
<img width="1290" height="644" alt="image" src="https://github.com/user-attachments/assets/d7407148-c3cb-4cdc-b46a-3473f970c3a9" />
**Các lệnh CSS do AI phát sinh:**
```
1. Cài đặt chung (Global Styles)
*  Nhóm này thiết lập nền tảng cho toàn bộ trang web như font chữ, màu sắc chủ đạo và cách hiển thị mặc định.

           * margin: 0; padding: 0;: Loại bỏ khoảng cách mặc định của trình duyệt.

           * font-family: "SF Pro Display", ...;: Sử dụng font chữ đặc trưng của Apple.

           * background-color: #ffffff;: Nền trắng sạch sẽ.

           * color: #1d1d1f;: Màu chữ đen đặc trưng (không đen hoàn toàn).

           * line-height: 1.5;: Khoảng cách giữa các dòng chữ.

2. Thanh thông báo vị trí (.top-banner)
*  Phần dải băng mỏng nằm ở trên cùng của trang.

           * background-color: #f5f5f7;: Màu xám nhạt để phân biệt với nội dung chính.

           * display: flex; justify-content: center; align-items: center;: Căn giữa tất cả nội dung bên trong theo cả chiều dọc và ngang.

           * gap: 15px;: Tạo khoảng cách giữa chữ, ô chọn và nút bấm.

           * font-size: 12px;: Cỡ chữ nhỏ.

           * border-bottom: 1px solid #d2d2d7;: Đường kẻ mảnh ngăn cách phía dưới.

3. Thanh điều hướng (.navbar)
*  Menu chính chứa các liên kết sản phẩm.

           * display: flex; justify-content: center;: Sắp xếp các link nằm hàng ngang và căn giữa.

           * backdrop-filter: blur(10px);: Hiệu ứng làm mờ nền khi cuộn qua (đặc sản của Apple).

           * background: rgba(255, 255, 255, 0.8);: Nền trắng có độ trong suốt 80%.

           * transition: opacity 0.3s;: Tạo hiệu ứng đổi màu mượt mà khi di chuột vào link.

4. Vùng nội dung chính (.hero)
*  Phần giới thiệu sản phẩm MacBook Neo.

           * text-align: center;: Căn giữa toàn bộ văn bản và hình ảnh.

           * font-size: 56px;: Kích thước chữ tiêu đề rất lớn để gây ấn tượng.

           * letter-spacing: -0.005em;: Thu hẹp khoảng cách giữa các chữ cái (tạo cảm giác chuyên nghiệp).

           * font-weight: 600;: Độ đậm của chữ.

5. Nút bấm và Tương tác (.cta-group, .btn-...)
*  Các nút "Learn more" và "Buy".

           * border-radius: 980px;: Bo tròn tối đa để tạo nút hình viên thuốc.

           * background-color: #0071e3;: Màu xanh dương thương hiệu Apple.

           * text-decoration: none;: Loại bỏ đường gạch chân mặc định của liên kết.

           * cursor: pointer;: Thay đổi con trỏ chuột thành hình bàn tay khi di vào nút.

6. Hình ảnh sản phẩm (.product-img)
*  max-width: 800px;: Giới hạn chiều rộng tối đa của ảnh.

           * width: 100%; height: auto;: Đảm bảo ảnh tự co giãn theo màn hình (Responsive) mà không bị méo.
---

## III. Kết quả
> Sau khi ra lệnh cho AI thì em được đoạn code sau:
```
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

<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Dự án xây dựng sân thể thao</title>

  <style>
    html { scroll-behavior: smooth; }

    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      line-height: 1.6;
      background-image: url("https://images.unsplash.com/photo-1508098682722-e99c43a406b2");
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }

    header {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6));
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header img {
      width: 90px;
      margin-bottom: 10px;
    }

    nav {
      background-color: #1f6b43;
      padding: 12px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover { text-decoration: underline; }

    .container {
      padding: 25px;
      max-width: 900px;
      margin: 30px auto;
      background: rgba(255, 255, 255, 0.92);
      border-radius: 14px;
    }

    h2 { color: #2e8b57; }

    ul { padding-left: 20px; }

    .image-row {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px 0;
    }

    .image-row img {
      width: 100%;
      max-width: 420px;
      border-radius: 12px;
      box-shadow: 0 6px 12px rgba(0,0,0,0.3);
    }

    footer {
      background-color: #2e8b57;
      color: white;
      text-align: center;
      padding: 25px 15px;
    }

    .slogan {
      font-size: 20px;
      font-weight: bold;
      margin-top: 10px;
      color: #ffeb3b;
      letter-spacing: 1px;
    }

    .chat-bubble {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #2e8b57;
      color: white;
      padding: 14px 18px;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
    }
  </style>
</head>

<body>

<header>
  <img src="https://cdn-icons-png.flaticon.com/512/861/861512.png">
  <h1>DỰ ÁN XÂY DỰNG SÂN THỂ THAO</h1>
  <p>Công trình thể thao xanh – hiện đại – bền vững</p>
  <p><b>Lớp:</b> 12C6</p>
</header>

<nav>
  <a href="#gioithieu">Giới thiệu</a>
  <a href="#bongda">Sân bóng đá</a>
  <a href="#bongchuyen">Sân bóng chuyền</a>
  <a href="#thanhvien">Thành viên</a>
</nav>

<div class="container">

<section id="gioithieu">
  <h2>Giới thiệu dự án</h2>
  <p>
    Dự án xây dựng sân thể thao nhằm tạo ra môi trường học tập và rèn luyện
    lành mạnh, giúp học sinh nâng cao sức khỏe, tinh thần đoàn kết và phát triển toàn diện.
  </p>
</section>

<section id="bongda">
  <h2>Sân bóng đá</h2>

  <div class="image-row">
    <div>
      <img src="https://sf-static.upanhlaylink.com/img/image_202602042e55a0f262a414f07b4fc8adafabc5dd.jpg">
      <p style="text-align:center;font-style:italic;">
        Hình 1: Sân bóng đá cỏ nhân tạo hiện đại
      </p>
    </div>

    <div>
      <img src="https://sf-static.upanhlaylink.com/img/image_202602043154c6e3c935fa80a01ae14856cbdab2.jpg">
      <p style="text-align:center;font-style:italic;">
        Hình 2: Sơ đồ thiết kế và kích thước sân bóng đá
      </p>
    </div>
  </div>

  <p>
    Sân bóng đá được thiết kế theo tiêu chuẩn thi đấu, mặt cỏ nhân tạo chất lượng cao,
    hệ thống thoát nước tốt, đảm bảo an toàn cho học sinh trong quá trình sử dụng.
  </p>
</section>

<section id="bongchuyen">
  <h2>Sân bóng chuyền</h2>

  <div class="image-row">
    <div>
      <img src="https://sf-static.upanhlaylink.com/img/image_202602047943d63aaf993ad3396b480840f6f18a.jpg">
      <p style="text-align:center;font-style:italic;">
        Hình 3: Sân bóng chuyền ngoài trời
      </p>
    </div>

    <div>
      <img src="https://sf-static.upanhlaylink.com/img/image_20260204abe9d94f7dee7951bab263e23295f8db.jpg">
      <p style="text-align:center;font-style:italic;">
        Hình 4: Hoạt động thi đấu và tập luyện bóng chuyền
      </p>
    </div>
  </div>

  <p>
    Sân bóng chuyền được xây dựng nhằm đa dạng hóa các hoạt động thể thao trong nhà trường,
    giúp học sinh rèn luyện thể lực, kỹ năng phối hợp và tinh thần đồng đội.
  </p>
</section>

<section id="thanhvien">
  <h2>Thành viên tham gia</h2>
  <ul>
    <li>Khoa</li>
    <li>Vỹ</li>
    <li>Thanh</li>
    <li>Tuấn</li>
  </ul>
</section>

</div>

<footer>
  <p>© 2026 | Dự án xây dựng sân thể thao | Nhóm 12C6</p>
  <div class="slogan">HỌC HẾT GA – CHƠI HẾT MÌNH</div>
</footer>

<a href="tel:0832688426" class="chat-bubble">
  📞 0832 688 426
</a>

</body>
</html>

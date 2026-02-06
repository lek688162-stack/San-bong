<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Dự án xây dựng sân cầu lông</title>

  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      line-height: 1.6;
      background: linear-gradient(135deg, #ffb6c1, #fff59d);
      background-attachment: fixed;
    }

    header {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5));
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header img {
      width: 90px;
      margin-bottom: 10px;
      border-radius: 50%;
    }

    nav {
      background: #f06292;
      text-align: center;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
      animation: fadeIn 1s ease;
    }

    h2 {
      color: #d81b60;
    }

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
      transition: transform 0.3s;
    }

    .image-row img:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: #f48fb1;
      color: #4a148c;
      text-align: center;
      padding: 15px;
      font-weight: bold;
    }

    .chat-bubble {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #f06292;
      color: white;
      padding: 14px 18px;
      border-radius: 50px;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
      z-index: 999;
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.08); }
      100% { transform: scale(1); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>

<body>

<header>
  <img src="https://sf-static.upanhlaylink.com/img/image_202602056aae233299bb7d3658a53e8eec6904f0.jpg" alt="Logo cầu lông">
  <h1>DỰ ÁN XÂY DỰNG SÂN CẦU LÔNG</h1>
  <p>Công trình thể thao xanh – hiện đại – bền vững</p>
  <p>HỌC HẾT GA – CHƠI HẾT MÌNH</p>
  <p><b>Lớp:</b> 12C6</p>
</header>

<nav>
  <a href="#gioithieu">Giới thiệu</a>
  <a href="#muctieu">Mục tiêu</a>
  <a href="#hinhanh">Hình ảnh</a>
  <a href="#thanhvien">Thành viên</a>
</nav>

<div class="container">

  <section id="gioithieu">
    <h2>Giới thiệu công trình</h2>
    <p>
      Dự án xây dựng sân cầu lông nhằm tạo môi trường luyện tập và thi đấu
      hiện đại, an toàn, thân thiện với môi trường, góp phần nâng cao sức khỏe học sinh.
    </p>
  </section>

  <section id="muctieu">
    <h2>Mục tiêu dự án</h2>
    <ul>
      <li>Xây dựng sân cầu lông đạt tiêu chuẩn</li>
      <li>Phát triển phong trào thể thao học đường</li>
      <li>Tạo sân chơi lành mạnh</li>
      <li>Nâng cao thể chất học sinh</li>
    </ul>
  </section>

  <section id="hinhanh">
    <h2>Hình ảnh minh họa</h2>
    <div class="image-row">
      <div>
        <img src="https://sf-static.upanhlaylink.com/img/image_202602050460f8a4d07394f9dcb69278aa171000.jpg">
        <p style="text-align:center;font-style:italic;">Hình 1: Sơ đồ sân cầu lông tiêu chuẩn.</p>
      </div>
      <div>
        <img src="https://sf-static.upanhlaylink.com/img/image_20260205864d02e081960e144070c628e949502c.jpg">
        <p style="text-align:center;font-style:italic;">Hình 2: Sân cầu lông ngoài trời.</p>
      </div>
    </div>
  </section>

  <section id="thanhvien">
    <h2>Thành viên nhóm</h2>
    <ul>
      <li>Duy Khang</li>
    </ul>
  </section>

</div>

<footer>
  © 2026 | Dự án sân cầu lông | Nhóm 12C6
</footer>

<a href="https://www.facebook.com/share/1FfT2nC8YT/?mibextid=wwXIfr"
   target="_blank"
   style="display:block;text-align:center;margin:15px;font-weight:bold;">
   • Xem CLB trên Facebook •
</a>

<a href="tel:0832687903" class="chat-bubble">
  📞 Liên hệ: 0832 687 903
</a>

</body>
</html>

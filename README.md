[Uploading style.css…]()
body {
  margin: 0;
  font-family: sans-serif;
  background: #ffe6f2;
}
.hero {
  background: linear-gradient(135deg, #ff4d94, #ff99c2);
  padding: 60px 20px;
  text-align: center;
  color: white;
}
.products {
  padding: 30px;
}
.products h2 {
  text-align: center;
  margin-bottom: 20px;
}
.grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: center;
}
.item {
  background: white;
  padding: 15px;
  border-radius: 12px;
  width: 250px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}
.item img {
  width: 100%;
  border-radius: 10px;
}
.info {
  padding: 20px;
}
footer {
  text-align: center;
  padding: 20px;
  color: #555;
}

<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Em Nuôi Tôi – BabyCare</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header class="hero">
  <h1>Em Nuôi Tôi</h1>
  <p>Đồ chăm sóc em bé – An toàn • Dịu nhẹ • Chính hãng</p>
</header>

<section class="products">
  <h2>Sản phẩm nổi bật</h2>
  <div class="grid">
    <div class="item">
      <img src="https://via.placeholder.com/300x300.png?text=Sua+tam+em+be" />
      <h3>Sữa tắm em bé</h3>
      <p>150.000đ</p>
    </div>

    <div class="item">
      <img src="https://via.placeholder.com/300x300.png?text=Bim+em+be" />
      <h3>Bỉm em bé</h3>
      <p>280.000đ</p>
    </div>

    <div class="item">
      <img src="https://via.placeholder.com/300x300.png?text=Kem+du+ong" />
      <h3>Kem dưỡng ẩm</h3>
      <p>120.000đ</p>
    </div>
  </div>
</section>

<section class="info">
  <h2>Liên hệ</h2>
  <p>Địa chỉ: 45 Nguyễn Trãi, Quận 1, TP. HCM</p>
  <p>Hotline: 0988 123 456</p>
  <p>Ngân hàng: Vietcombank – 1036333871 – HOANG DONG THAI</p>
</section>

<footer>
  <p>© 2025 Em Nuôi Tôi</p>
</footer>

</body>
</html>

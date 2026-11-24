
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lumière Soap</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
  <h1>Lumière Soap</h1>
  <nav>
    <a href="#home">หน้าแรก</a>
    <a href="#products">สินค้า</a>
    <a href="#contact">ติดต่อเรา</a>
  </nav>
</header>

<section id="home">
  <h2>Pure Care, Pure Beauty</h2>
  <p>สบู่สำหรับการดูแลผิวในทุกวัน</p>
  <a href="#products">เลือกซื้อสินค้า</a>
</section>

<section id="products">
  <h2>Our Products</h2>

  <div class="product">
    <img src="images/milk-soap.jpg" alt="Milk Soap">
    <h3>Lumière Milk Soap</h3>
    <p>SKU: LS001</p>
    <p>ราคา 89 บาท</p>
    <button onclick="addCart('LS001')">
      เพิ่มลงตะกร้า
    </button>
  </div>

  <div class="product">
    <img src="images/aloe-soap.jpg" alt="Aloe Soap">
    <h3>Lumière Aloe Soap</h3>
    <p>SKU: LS002</p>
    <p>ราคา 99 บาท</p>
    <button onclick="addCart('LS002')">
      เพิ่มลงตะกร้า
    </button>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>Lumière Soap</p>
</section>

<script src="js/script.js"></script>
</body>
</html>

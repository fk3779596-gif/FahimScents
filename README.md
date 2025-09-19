<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Fahim Scents – Luxury Perfumes</title>
  <meta name="description" content="Fahim Scents – Elegance in every drop. Discover luxury perfumes crafted with passion.">
  <style>
    body{margin:0;font-family:Arial, sans-serif;background:#fafafa;color:#222}
    header{background:#111;color:#fff;padding:20px;text-align:center}
    header h1{margin:0;font-size:32px}
    header p{margin:5px 0 0;font-size:18px;color:#ccc}
    nav{margin-top:10px}
    nav a{color:#fff;text-decoration:none;margin:0 12px;font-size:16px}
    .container{max-width:1000px;margin:auto;padding:20px}
    section{margin:50px 0}
    h2{text-align:center;margin-bottom:20px}
    .products{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
    .card{background:#fff;border:1px solid #eee;border-radius:12px;box-shadow:0 4px 12px rgba(0,0,0,.05);padding:15px;text-align:center}
    .card img{max-width:100%;border-radius:10px}
    .btn{display:inline-block;margin-top:10px;padding:10px 16px;background:#111;color:#fff;text-decoration:none;border-radius:6px}
    footer{text-align:center;padding:15px;background:#111;color:#fff;margin-top:40px;font-size:14px}
  </style>
</head>
<body>

  <header>
    <h1>Fahim Scents</h1>
    <p>Elegance in every drop</p>
    <nav>
      <a href="#about">About</a>
      <a href="#products">Perfumes</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">
    <section id="about">
      <h2>About Us</h2>
      <p><b>Fahim Scents</b> is a premium perfume brand blending timeless aromas with modern elegance. Each fragrance is carefully crafted to reflect sophistication, confidence, and style. Our mission is to bring you scents that define your personality and leave a lasting impression.</p>
    </section>

    <section id="products">
      <h2>Our Perfumes</h2>
      <div class="products">
        <div class="card">
          <img src="https://via.placeholder.com/300x400" alt="Perfume Bottle">
          <h3>Fahim Noir</h3>
          <p>Dark, bold and elegant fragrance for special nights.</p>
          <a href="#" class="btn">Shop Now</a>
        </div>
        <div class="card">
          <img src="https://via.placeholder.com/300x400" alt="Perfume Bottle">
          <h3>Fahim Bloom</h3>
          <p>A fresh floral scent that brightens your day.</p>
          <a href="#" class="btn">Shop Now</a>
        </div>
        <div class="card">
          <img src="https://via.placeholder.com/300x400" alt="Perfume Bottle">
          <h3>Fahim Oud</h3>
          <p>Traditional Arabic oud with a luxurious twist.</p>
          <a href="#" class="btn">Shop Now</a>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: <a href="mailto:info@fahimscents.com">info@fahimscents.com</a></p>
      <p>WhatsApp: <a href="https://wa.me/923000000000" target="_blank">+92 300 0000000</a></p>
      <p>Follow us on <a href="#">Instagram</a></p>
    </section>
  </div>

  <footer>
    © <span id="year"></span> Fahim Scents — All Rights Reserved
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>

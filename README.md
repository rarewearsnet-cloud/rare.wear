<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Rare Waer | Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="shop.html">Shop</a>
    <a href="contact.html">Contact</a>
  </header>
  <div class="container">
    <h1>Welcome to Rare Waer</h1>
    <p>Premium quality oversized T-shirts & hoodies. Minimal design. Maximum comfort.</p>
    <a href="shop.html" class="btn">Shop Now</a>
  </div>
  <footer>
    © <span id="year"></span> Rare Waer
  </footer>
  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>

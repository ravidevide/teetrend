# teetrend
Print on Demand Storefront
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TeeTrend - Print Your Style</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
    header { background: #111; color: #fff; padding: 20px 0; text-align: center; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; font-weight: bold; }
    .hero { background: url('https://images.unsplash.com/photo-1618354691419-94a35d03d88b') center/cover no-repeat; color: white; text-align: center; padding: 100px 20px; }
    .hero h1 { font-size: 3em; margin-bottom: 10px; }
    .hero p { font-size: 1.2em; margin-bottom: 20px; }
    .hero a { background: #ff4500; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; }
    .products { display: flex; flex-wrap: wrap; justify-content: center; padding: 40px 20px; }
    .product { background: white; margin: 10px; padding: 20px; border-radius: 10px; width: 250px; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .product img { width: 100%; height: auto; border-radius: 10px; }
    .product h3 { margin: 10px 0 5px; }
    .product p { margin: 5px 0; }
    .product button { background: #111; color: white; padding: 10px; border: none; border-radius: 5px; cursor: pointer; }
    footer { background: #222; color: white; text-align: center; padding: 20px; margin-top: 40px; }
    .contact-info { margin-top: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>TeeTrend</h1>
    <nav>
      <a href="#shop">Shop</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Print Your Style</h1>
    <p>Discover trending T-Shirts & Hoodies with premium quality printing.</p>
    <a href="#shop">Shop Now</a>
  </section>

  <section id="shop" class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1585386959984-a41552254ef2" alt="T-Shirt">
      <h3>Graphic T-Shirt</h3>
      <p>₹500</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1602810317371-6e6e68e94e92" alt="Hoodie">
      <h3>Custom Hoodie</h3>
      <p>₹500</p>
      <button>Add to Cart</button>
    </div>
  </section>

  <footer id="contact">
    <h3>Contact Us</h3>
    <div class="contact-info">
      <p>Email: shanayshanvish123@gmail.com</p>
      <p>Phone: 7011866314</p>
    </div>
    <p>&copy; 2025 TeeTrend. All rights reserved.</p>
  </footer>
</body>
</html>

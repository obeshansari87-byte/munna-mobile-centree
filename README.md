<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Munna Mobile Centre</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }

    header {
      background: #111;
      color: white;
      padding: 15px;
      text-align: center;
    }

    nav {
      background: #222;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 40px;
      background: linear-gradient(45deg, #ff6a00, #ee0979);
      color: white;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .price {
      color: green;
      font-weight: bold;
    }

    button {
      background: #111;
      color: white;
      border: none;
      padding: 8px 12px;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 5px;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Munna Mobile Centre</h1>
    <p>Your Trusted Mobile Accessories Shop</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h2>Best Mobile Accessories in One Place</h2>
    <p>Chargers • Earphones • Covers • Power Banks</p>
  </section>

  <section class="products">

    <div class="card">
      <h3>Fast Charger</h3>
      <p class="price">₹299</p>
      <button>Add to Cart</button>
    </div>

    <div class="card">
      <h3>Earphones</h3>
      <p class="price">₹199</p>
      <button>Add to Cart</button>
    </div>

    <div class="card">
      <h3>Mobile Cover</h3>
      <p class="price">₹149</p>
      <button>Add to Cart</button>
    </div>

    <div class="card">
      <h3>Power Bank</h3>
      <p class="price">₹999</p>
      <button>Add to Cart</button>
    </div>

  </section>

  <footer>
    <p>Contact: 9155416433 | Munna Mobile Centre © 2026</p>
  </footer>

</body>
</html>

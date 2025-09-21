# NovaTrader-GoldBTC
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GoldBTC.io</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #fff8dc, #f0f0f0);
      color: #333;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 20px;
      background: #fff;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 100;
    }
    header h1 {
      color: #d4af37;
      margin: 0;
    }
    nav a {
      margin-left: 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      color: #d4af37;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 15px;
      color: #d4af37;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 25px;
    }
    .hero button {
      padding: 12px 25px;
      font-size: 1rem;
      background-color: #d4af37;
      border: none;
      color: white;
      border-radius: 25px;
      cursor: pointer;
    }
    .hero button:hover {
      background-color: #bfa135;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 50px 20px;
    }
    .feature-card {
      background: #fff;
      padding: 25px;
      border-radius: 20px;
      width: 280px;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .feature-card h3 {
      margin-bottom: 10px;
      color: #d4af37;
    }
    .newsletter {
      text-align: center;
      padding: 50px 20px;
      background: #fff;
      box-shadow: inset 0 0 10px rgba(0,0,0,0.05);
    }
    .newsletter input {
      padding: 10px 15px;
      border-radius: 25px;
      border: 1px solid #ccc;
      width: 250px;
      margin-right: 10px;
    }
    .newsletter button {
      padding: 10px 20px;
      border-radius: 25px;
      border: none;
      background: #d4af37;
      color: white;
      cursor: pointer;
    }
    .newsletter button:hover {
      background: #bfa135;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #777;
    }
    @media (max-width: 600px) {
      .features {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>GoldBTC.io</h1>
  <nav>
    <a href="#features">Features</a>
    <a href="#newsletter">Subscribe</a>
  </nav>
</header>

<section class="hero">
  <h2>Gold Meets Bitcoin</h2>
  <p>The future of wealth: Secure your assets with the power of gold & crypto.</p>
  <button>Get Started</button>
</section>

<section id="features" class="features">
  <div class="feature-card">
    <h3>Crypto Insights</h3>
    <p>Stay updated with the latest Bitcoin & Gold market trends.</p>
  </div>
  <div class="feature-card">
    <h3>Investment Guides</h3>
    <p>Learn how to diversify your portfolio with Gold & BTC.</p>
  </div>
  <div class="feature-card">
    <h3>Community</h3>
    <p>Join a growing network of investors & enthusiasts.</p>
  </div>
</section>

<section id="newsletter" class="newsletter">
  <h3>Stay Updated</h3>
  <p>Subscribe to get the latest news on Gold & Bitcoin.</p>
  <input type="email" placeholder="Enter your email" />
  <button>Subscribe</button>
</section>

<footer>
  © 2025 GoldBTC.io — All Rights Reserved
</footer>

</body>
</html>

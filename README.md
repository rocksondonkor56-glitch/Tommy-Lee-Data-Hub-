
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tommy Lee Data Shop</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f4f7fb;
      color: #222;
    }

    header {
      background: linear-gradient(135deg, #0066ff, #00aaff);
      color: white;
      padding: 35px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 17px;
    }

    nav {
      background: #003b8f;
      padding: 14px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 40px 20px;
    }

    .hero h2 {
      color: #0066ff;
      font-size: 30px;
      margin-bottom: 10px;
    }

    .hero p {
      color: #555;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }

    .plans {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 25px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .card h3 {
      color: #0066ff;
      font-size: 25px;
      margin-bottom: 10px;
    }

    .price {
      font-size: 24px;
      font-weight: bold;
      margin: 15px 0;
    }

    .buy {
      display: inline-block;
      background: #00a859;
      color: white;
      padding: 12px 22px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    .buy:hover {
      background: #007d43;
    }

    .contact {
      background: white;
      margin-top: 40px;
      padding: 30px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    }

    .contact h2 {
      color: #0066ff;
      margin-bottom: 15px;
    }

    .contact p {
      margin: 8px 0;
    }

    footer {
      background: #003b8f;
      color: white;
      text-align: center;
      padding: 25px;
      margin-top: 40px;
    }

    @media(max-width: 600px) {
      header h1 {
        font-size: 28px;
      }

      nav a {
        margin: 0 7px;
        font-size: 14px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>📱 Tommy Lee Data Shop</h1>
    <p>Affordable Internet Data Bundles</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#data">Data Plans</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <h2>Buy Data Easily</h2>
    <p>Choose your preferred data bundle and contact Tommy Lee to place your order.</p>
  </section>

  <div class="container" id="data">

    <h2 style="text-align:center;">Available Data Plans</h2>

    <div class="plans">

      <div class="card">
        <h3>1 GB</h3>
        <p>Internet Data</p>
        <div class="price">GH₵ 5</div>
        <a class="buy"
           href="https://wa.me/233538737766?text=Hello%20Tommy%20Lee,%20I%20want%20to%20buy%201GB%20data.">
           Buy Now
        </a>
      </div>

      <div class="card">
        <h3>2 GB</h3>
        <p>Internet Data</p>
        <div class="price">GH₵ 10</div>
        <a class="buy"
           href="https://wa.me/233538737766?text=Hello%20Tommy%20Lee,%20I%20want%20to%20buy%202GB%20data.">
           Buy Now
        </a>
      </div>

      <div class="card">
        <h3>5 GB</h3>
        <p>Internet Data</p>
        <div class="price">GH₵ 20</div>
        <a class="buy"
           href="https://wa.me/233538737766?text=Hello%20Tommy%20Lee,%20I%20want%20to%20buy%205GB%20data.">
           Buy Now
        </a>
      </div>

      <div class="card">
        <h3>10 GB</h3>
        <p>Internet Data</p>
        <div class="price">GH₵ 35</div>
        <a class="buy"
           href="https://wa.me/233538737766?text=Hello%20Tommy%20Lee,%20I%20want%20to%20buy%2010GB%20data.">
           Buy Now
        </a>
      </div>

      <div class="card">
        <h3>20 GB</h3>
        <p>Internet Data</p>
        <div class="price">GH₵ 60</div>
        <a class="buy"
           href="https://wa.me/233538737766?text=Hello%20Tommy%20Lee,%20I%20want%20to%20buy%2020GB%20data.">
           Buy Now
        </a>
      </div>

      <div class="card">
        <h3>50 GB</h3>
        <p>Internet Data</p>
        <div class="price">GH₵ 120</div>
        <a class="buy"
           href="https://wa.me/233538737766?text=Hello%20Tommy%20Lee,%20I%20want%20to%20buy%2050GB%20data.">
         
           Buy Now
        </a>
      </div>

    </div>

    <div class="contact" id="contact">
  <h2>Contact Tommy Lee</h2>

  <p><strong>📞 Phone:</strong> 0538737766</p>

  <p>
    <strong>📧 Email:</strong>
    rocksondonkor56@gmail.com
  </p>

  <p>
    <strong>📍 Location:</strong>
    Western North, Bibiani, Ghana
  </p>

  <br> 
      <a
  href="https://wa.me/233538737766?text=Hello%20Tommy%20Lee%2C%20I%20want%20to%20buy%20data."
  target="_blank"
  style="
    display:inline-block;
    background:#25D366;
    color:white;
    padding:14px 22px;
    border-radius:10px;
    text-decoration:none;
    font-weight:bold;
  "
>
  💬 Order on WhatsApp
</a>

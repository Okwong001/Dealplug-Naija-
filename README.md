<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>DealPlug Naija</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f0f4f8;
      color: #333;
    }
    header {
      background: #004aad;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
    }
    main {
      max-width: 1000px;
      margin: 20px auto;
      padding: 0 20px;
    }
    section {
      margin-bottom: 40px;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .product {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      width: calc(33% - 13px);
      padding: 15px;
      box-sizing: border-box;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 4px;
    }
    .product h3 {
      margin: 10px 0 5px;
      font-size: 1.1em;
      color: #004aad;
    }
    .product p {
      margin: 0;
      font-weight: bold;
      color: #27ae60;
    }
    footer {
      background: #222;
      color: #aaa;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }
    a.phone-link {
      color: #004aad;
      font-weight: bold;
      text-decoration: none;
    }
    .whatsapp-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 12px 18px;
      border-radius: 50px;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      z-index: 1000;
    }
    .whatsapp-btn:hover {
      background: #1ebe5b;
    }
    @media (max-width: 700px) {
      .product {
        width: calc(50% - 10px);
      }
    }
    @media (max-width: 450px) {
      .product {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>DealPlug Naija</h1>
    <p>Your trusted reselling partner in Oron, Akwa Ibom</p>
  </header>

  <main>
    <section>
      <h2>Featured Products</h2>
      <div class="products">
        <div class="product">
          <img src="https://via.placeholder.com/250x150?text=Smart+TV" alt="Smart TV" />
          <h3>Smart TV</h3>
          <p>₦150,000</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/250x150?text=Men's+T-Shirt" alt="T-Shirt" />
          <h3>Men's T-Shirt</h3>
          <p>₦3,000</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/250x150?text=Microwave" alt="Microwave" />
          <h3>Microwave Oven</h3>
          <p>₦40,000</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/250x150?text=Bluetooth+Speaker" alt="Bluetooth Speaker" />
          <h3>Bluetooth Speaker</h3>
          <p>₦12,000</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/250x150?text=Sneakers" alt="Sneakers" />
          <h3>Trendy Sneakers</h3>
          <p>₦15,000</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/250x150?text=Smartphone" alt="Smartphone" />
          <h3>Smartphone</h3>
          <p>₦80,000</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Contact Us</h2>
      <p>Call or WhatsApp us at: <a class="phone-link" href="tel:+2347043996851">07043996851</a></p>
      <p><a class="phone-link" href="https://wa.me/2347043996851" target="_blank">Chat with us on WhatsApp</a></p>
    </section>
  </main>

  <a class="whatsapp-btn" href="https://wa.me/2347043996851" target="_blank">📲 Order via WhatsApp</a>

  <footer>
    &copy; 2025 DealPlug Naija — All rights reserved.
  </footer>
</body>
</html>

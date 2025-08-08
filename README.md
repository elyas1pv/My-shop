<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>فروشگاه ساده من</title>
  <style>
    body {
      font-family: Tahoma, sans-serif;
      background: #f9f9f9;
      margin: 0;
      padding: 20px;
      direction: rtl;
      color: #333;
    }
    header {
      text-align: center;
      margin-bottom: 30px;
    }
    h1 {
      margin: 0;
      color: #2c3e50;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .product img {
      max-width: 100%;
      border-radius: 6px;
      margin-bottom: 10px;
    }
    .product h2 {
      margin: 0 0 10px 0;
      font-size: 20px;
      color: #34495e;
    }
    .product p {
      flex-grow: 1;
      margin-bottom: 15px;
    }
    .price {
      font-weight: bold;
      margin-bottom: 10px;
      color: #27ae60;
      font-size: 18px;
    }
    .order-btn {
      background: #2980b9;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
      transition: background 0.3s ease;
      text-align: center;
      text-decoration: none;
      display: block;
    }
    .order-btn:hover {
      background: #1c5980;
    }
    footer {
      margin-top: 40px;
      text-align: center;
      font-size: 14px;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>فروشگاه من</h1>
    <p>برای سفارش محصولات، لطفاً از طریق تلگرام با ما تماس بگیرید:</p>
    <p><strong><a href="https://t.me/YourTelegramID" target="_blank">@YourTelegramID</a></strong></p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=محصول+1" alt="محصول 1" />
      <h2>محصول 1</h2>
      <p>توضیحات کوتاه درباره محصول شماره 1.</p>
      <div class="price">100,000 تومان</div>
      <a href="https://t.me/YourTelegramID?text=سلام، می‌خواهم محصول 1 را سفارش دهم." target="_blank" class="order-btn">سفارش از طریق تلگرام</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=محصول+2" alt="محصول 2" />
      <h2>محصول 2</h2>
      <p>توضیحات کوتاه درباره محصول شماره 2.</p>
      <div class="price">150,000 تومان</div>
      <a href="https://t.me/YourTelegramID?text=سلام، می‌خواهم محصول 2 را سفارش دهم." target="_blank" class="order-btn">سفارش از طریق تلگرام</a>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/

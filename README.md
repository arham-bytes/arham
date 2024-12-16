<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    .header {
      background-color: #333;
      color: white;
      padding: 10px 20px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product-card {
      background: white;
      padding: 15px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
      text-align: center;
    }
    .product-card img {
      max-width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .product-card h3 {
      margin: 10px 0;
    }
    .product-card p {
      color: #555;
    }
    .product-card button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 10px 15px;
      cursor: pointer;
      border-radius: 5px;
    }
    .product-card button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Welcome to My Shop</h1>
  </div>
  <div class="products">
    <div class="product-card">
      <img src="https://via.placeholder.com/150" alt="Product 1">
      <h3>Product 1</h3>
      <p>$10.00</p>
      <button>Add to Cart</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/150" alt="Product 2">
      <h3>Product 2</h3>
      <p>$15.00</p>
      <button>Add to Cart</button>
    </div>
    <div class="product-card">
      <img src="https://via.placeholder.com/150" alt="Product 3">
      <h3>Product 3</h3>
      <p>$20.00</p>
      <button>Add to Cart</button>
    </div>
  </div>
</body>
</html>

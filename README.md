# H-viansho
Deals with phonecase
<!DOCTYPE html>
<html>
<head>
  <title>Hàvian Shop</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>🛍️ Hàvian Shop</h1>
<p>Your #1 phone accessories store</p>

<div class="products">

  <div class="product">
    <h2>Phone Case</h2>
    <p>KES 1000</p>
    <button onclick="buy('Phone Case')">Buy</button>
  </div>

  <div class="product">
    <h2>Screen Protector</h2>
    <p>KES 500</p>
    <button onclick="buy('Screen Protector')">Buy</button>
  </div>

</div>

<script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial;
  text-align: center;
  background: #f5f5f5;
}

.products {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.product {
  background: white;
  padding: 20px;
  border-radius: 10px;
  width: 200px;
}function buy(product) {
  alert("You selected: " + product);
}
body {
  font-family: Arial;
  text-align: center;
  background: #f5f5f5;
}

.products {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.product {
  background: white;
  padding: 20px;
  border-radius: 10px;
  width: 200px;
}function buy(product) {
  alert("You selected: " + product);
}

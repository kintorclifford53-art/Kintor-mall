<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Cliff1 Shopping Mall</title>

<style><img 
    src="images/iphone-11.jpg" 
    alt="Apple iPhone 11"
    loading="lazy"
><img 
    src="images/iphone-11.jpg" 
    alt="Apple iPhone 11"
    loading="lazy"
><img 
/* PRODUCT PICTURES */
.product img {
    width: 100%;
    height: 220px;
    object-fit: contain;
    display: block;
    margin: 0 auto 15px;
    border-radius: 12px;
    background: #f8f8f8;
}

.product {
    overflow: hidden;
}<div class="product">

    <img 
        src="images/iphone-11.jpg" 
        alt="Apple iPhone 11"
        loading="lazy"
    >

    <h3>iPhone 11</h3>

    <p class="old-price">GHC 4,000</p>

    <h2>GHC 2,800</h2>

    <strong>30% OFF</strong>

    <button>View</button>

</div>

@media (max-width: 600px) {
    .product img {
        height: 180px;
    }
}images/iphone-11.jpg
images/iphone-11-pro.jpg
images/iphone-11-pro-max.jpg
images/iphone-12.jpg
images/iphone-12-pro.jpg
images/iphone-12-pro-max.jpg
images/iphone-13.jpg
images/iphone-13-pro.jpg
images/iphone-13-pro-max.jpg
images/iphone-14.jpg
images/iphone-14-pro.jpg
images/iphone-15.jpg
images/iphone-15-pro.jpg
images/iphone-15-pro-max.jpg
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f4f4;
  color: #222;
}

header {
  background: #111;
  color: white;
  text-align: center;
  padding: 25px 15px;
}

header h1 {
  margin: 0;
  font-size: 32px;
}

header p {
  margin: 8px;
}

.search {
  padding: 15px;
  text-align: center;
  background: white;
}

.search input {
  width: 90%;
  max-width: 500px;
  padding: 13px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 16px;
}

.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 15px;
  padding: 20px;
}

.product {
  background: white;
  border-radius: 12px;
  padding: 15px;
  text-align: center;
  box-shadow: 0 2px 8px #bbb;
}

.product h2 {
  font-size: 19px;
}

.old {
  color: #888;
  text-decoration: line-through;
}

.price {
  font-size: 20px;
  font-weight: bold;
}

.discount {
  color: green;
  font-weight: bold;
}

button {
  background: #111;
  color: white;
  border: none;
  padding: 10px 15px;
  border-radius: 7px;
  cursor: pointer;
}

button:hover {
  background: #333;
}

section h2 {
  text-align: center;
  margin-top: 30px;
}

footer {
  background: #111;
  color: white;
  text-align: center;
  padding: 30px;
  margin-top: 30px;
}
</style>
</head>

<body>

<header>
  <h1>CLIFF1 SHOPPING MALL</h1>
  <p>Phones • Accessories • Repairs • Digital Services</p>
  <p>Selected products: 30% OFF</p>
</header>

<div class="search">
  <input type="text" id="search"
  placeholder="Search phones or services..."
  onkeyup="searchProducts()">
</div>

<section>
<h2>📱 PHONES</h2>

<div class="products" id="products">

<!-- iPHONES -->

<div class="product">
<h2>iPhone 11</h2>
<p class="old">GH₵ 4,000</p>
<p class="price">GH₵ 2,800</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 11 Pro</h2>
<p class="old">GH₵ 5,000</p>
<p class="price">GH₵ 3,500</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 11 Pro Max</h2>
<p class="old">GH₵ 5,500</p>
<p class="price">GH₵ 3,850</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 12</h2>
<p class="old">GH₵ 5,000</p>
<p class="price">GH₵ 3,500</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 12 Pro</h2>
<p class="old">GH₵ 6,000</p>
<p class="price">GH₵ 4,200</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 12 Pro Max</h2>
<p class="old">GH₵ 6,500</p>
<p class="price">GH₵ 4,550</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 13</h2>
<p class="old">GH₵ 6,500</p>
<p class="price">GH₵ 4,550</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 13 Pro</h2>
<p class="old">GH₵ 7,500</p>
<p class="price">GH₵ 5,250</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 13 Pro Max</h2>
<p class="old">GH₵ 8,000</p>
<p class="price">GH₵ 5,600</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 14</h2>
<p class="old">GH₵ 7,500</p>
<p class="price">GH₵ 5,250</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 14 Pro</h2>
<p class="old">GH₵ 9,000</p>
<p class="price">GH₵ 6,300</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 14 Pro Max</h2>
<p class="old">GH₵ 10,000</p>
<p class="price">GH₵ 7,000</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 15</h2>
<p class="old">GH₵ 9,000</p>
<p class="price">GH₵ 6,300</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 15 Pro</h2>
<p class="old">GH₵ 11,000</p>
<p class="price">GH₵ 7,700</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 15 Pro Max</h2>
<p class="old">GH₵ 12,000</p>
<p class="price">GH₵ 8,400</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 16</h2>
<p class="old">GH₵ 10,000</p>
<p class="price">GH₵ 7,000</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>iPhone 16 Pro</h2>
<p class="old">GH₵ 12,000</p>
<p class="price">GH₵ 8,400</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<!-- SAMSUNG -->

<div class="product">
<h2>Samsung Galaxy S9</h2>
<p class="old">GH₵ 2,000</p>
<p class="price">GH₵ 1,400</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Samsung Galaxy S10</h2>
<p class="old">GH₵ 2,500</p>
<p class="price">GH₵ 1,750</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Samsung Galaxy S20</h2>
<p class="old">GH₵ 3,500</p>
<p class="price">GH₵ 2,450</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Samsung Galaxy S21</h2>
<p class="old">GH₵ 4,000</p>
<p class="price">GH₵ 2,800</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Samsung Galaxy S22</h2>
<p class="old">GH₵ 5,000</p>
<p class="price">GH₵ 3,500</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Samsung Galaxy S23</h2>
<p class="old">GH₵ 6,000</p>
<p class="price">GH₵ 4,200</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Samsung Galaxy S24</h2>
<p class="old">GH₵ 8,000</p>
<p class="price">GH₵ 5,600</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Samsung Galaxy S25</h2>
<p class="old">GH₵ 10,000</p>
<p class="price">GH₵ 7,000</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<!-- OTHER PHONES -->

<div class="product">
<h2>Google Pixel 7</h2>
<p class="old">GH₵ 4,500</p>
<p class="price">GH₵ 3,150</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Google Pixel 8</h2>
<p class="old">GH₵ 6,000</p>
<p class="price">GH₵ 4,200</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Tecno Camon</h2>
<p class="old">GH₵ 3,000</p>
<p class="price">GH₵ 2,100</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Tecno Spark</h2>
<p class="old">GH₵ 2,500</p>
<p class="price">GH₵ 1,750</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Infinix Hot</h2>
<p class="old">GH₵ 2,500</p>
<p class="price">GH₵ 1,750</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Infinix Note</h2>
<p class="old">GH₵ 3,500</p>
<p class="price">GH₵ 2,450</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Redmi Note</h2>
<p class="old">GH₵ 2,800</p>
<p class="price">GH₵ 1,960</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>OnePlus 11</h2>
<p class="old">GH₵ 6,000</p>
<p class="price">GH₵ 4,200</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Huawei P30</h2>
<p class="old">GH₵ 3,000</p>
<p class="price">GH₵ 2,100</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

<div class="product">
<h2>Nokia G20</h2>
<p class="old">GH₵ 2,000</p>
<p class="price">GH₵ 1,400</p>
<p class="discount">30% OFF</p>
<button>View</button>
</div>

</div>
</section>

<section>
<h2>🛠️ CLIFF1 SERVICES</h2>

<div class="products">

<div class="product"><h2>Phone Screen Repair</h2><p>From GH₵ 150</p><button>Contact</button></div>
<div class="product"><h2>Battery Replacement</h2><p>From GH₵ 100</p><button>Contact</button></div>
<div class="product"><h2>Phone Software Repair</h2><p>From GH₵ 50</p><button>Contact</button></div>
<div class="product"><h2>Phone Cleaning</h2><p>From GH₵ 30</p><button>Contact</button></div>
<div class="product"><h2>Phone Setup</h2><p>From GH₵ 30</p><button>Contact</button></div>
<div class="product"><h2>Data Transfer</h2><p>From GH₵ 40</p><button>Contact</button></div>
<div class="product"><h2>Phone Accessories</h2><p>Available</p><button>Contact</button></div>
<div class="product"><h2>Phone Unlocking</h2><p>Price varies</p><button>Contact</button></div>

</div>
</section>

<footer>
<h2>CLIFF1 SHOPPING MALL</h2>
<p>Phone: YOUR-BUSINESS-NUMBER</p>
<p>WhatsApp: YOUR-BUSINESS-NUMBER</p>
<p>© 2026 Cliff1 Shopping Mall</p>
</footer>

<script>
function searchProducts() {
  let input = document.getElementById("search").value.toLowerCase();
  let products = document.querySelectorAll(".product");

  products.forEach(function(product) {
    let text = product.innerText.toLowerCase();

    if (text.includes(input)) {
      product.style.display = "block";
    } else {
      product.style.display = "none";
    }
  });
}
</script>

</body>
</html># Kintor-mall
Affordable housing 

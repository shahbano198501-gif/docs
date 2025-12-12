<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Royal Collections</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Roboto&display=swap" rel="stylesheet">
<style>
* { margin:0; padding:0; box-sizing:border-box; }
body { font-family:'Roboto', sans-serif; background:#f9f9f9; color:#333; }

header { background:#1E3A8A; color:white; padding:25px 0; text-align:center; }
header h1 { font-family:'Montserrat', sans-serif; font-size:2.2em; display:flex; align-items:center; justify-content:center; gap:10px; }
header img { height:40px; }
header p { font-size:1.1em; margin-top:5px; }
nav { margin-top:15px; }
nav a { color:white; text-decoration:none; margin:0 12px; font-weight:bold; transition:0.3s; }
nav a:hover { text-decoration:underline; }

.hero { background:#FFD700 url('https://images.unsplash.com/photo-1587574293340-1ec2702d3c2d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=1080') center/cover no-repeat; color:#1E3A8A; padding:100px 20px; text-align:center; border-bottom:5px solid #1E3A8A; border-radius:0 0 15px 15px;}
.hero h2 { font-size:2.2em; margin-bottom:15px; font-family:'Montserrat', sans-serif; font-weight:bold; }
.hero p { font-size:1.2em; margin-bottom:25px; }
.hero .cta-button { background:#1E3A8A; color:#FFD700; padding:15px 30px; border-radius:8px; text-decoration:none; font-weight:bold; transition:0.3s; margin:5px; display:inline-block; }
.hero .cta-button:hover { background:#0f236b; }

.container { width:90%; max-width:1200px; margin:40px auto; }

.products { display:flex; flex-wrap:wrap; gap:20px; justify-content:center; }
.product { background:white; border-radius:15px; box-shadow:0 5px 15px rgba(0,0,0,0.1); width:220px; text-align:center; padding:15px; transition:0.3s; }
.product:hover { transform:translateY(-5px); box-shadow:0 10px 20px rgba(0,0,0,0.2); }
.product img { width:100%; border-radius:10px; height:250px; object-fit:cover; }
.product h3 { margin:10px 0; font-size:1.1em; color:#1E3A8A; }
.product p { font-weight:bold; margin:5px 0; }
.product .cta-button { background:#FFD700; color:#1E3A8A; padding:10px 15px; border-radius:5px; text-decoration:none; font-weight:bold; transition:0.3s; display:inline-block; }
.product .cta-button:hover { background:#e6c200; }

section { margin:60px 0; }
h2 { text-align:center; margin-bottom:25px; font-family:'Montserrat', sans-serif; color:#1E3A8A; }

.reviews, .categories { display:flex; flex-wrap:wrap; gap:20px; justify-content:center; }
.card { background:white; border-radius:15px; padding:20px; box-shadow:0 5px 15px rgba(0,0,0,0.1); width:250px; text-align:center; transition:0.3s; }
.card:hover { transform:translateY(-5px); box-shadow:0 10px 20px rgba(0,0,0,0.2); }

table { width:100%; border-collapse: collapse; margin-top:15px; background:white; border-radius:10px; overflow:hidden; box-shadow:0 5px 15px rgba(0,0,0,0.1); }
th, td { border:1px solid #ccc; padding:12px; text-align:center; }
th { background:#1E3A8A; color:white; }

#contact { background:#1E3A8A; color:white; padding:40px 20px; border-radius:15px; text-align:center; }
#contact a { color:#FFD700; text-decoration:none; font-weight:bold; }
#contact a:hover { text-decoration:underline; }
#contact .cta-button { background:#FFD700; color:#1E3A8A; padding:12px 25px; border-radius:8px; text-decoration:none; font-weight:bold; display:inline-block; margin-top:15px; transition:0.3s; }
#contact .cta-button:hover { background:#e6c200; }

footer { background:#0f236b; color:white; text-align:center; padding:25px 10px; border-radius:15px 15px 0 0;}
footer .social a { margin:0 8px; color:white; text-decoration:none; font-weight:bold; transition:0.3s; }
footer .social a:hover { color:#FFD700; }

@media(max-width:768px){ .products, .reviews, .categories { flex-direction:column; align-items:center; } header h1 { flex-direction:column; gap:5px; } }
</style>
</head>
<body>

<header>
<h1><img src="https://i.ibb.co/ZJc8J4k/royal-logo.png" alt="Royal Collections Logo"> Royal Collections</h1>
<p>New Fashion Collection</p>
<nav>
<a href="#products">Shop</a>
<a href="#about">About Us</a>
<a href="#reviews">Reviews</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero">
<h2>Premium Style, Direct Factory Price</h2>
<p>Latest Fashion T-Shirts, Hoodies & Jeans</p>
<a href="#products" class="cta-button">Shop Now</a>
<a href="https://wa.me/918810368375?text=Hello%2C%20I%20want%20to%20order%20from%20Royal%20Collections" class="cta-button">Order via WhatsApp</a>
</div>

<div class="container">

<section id="products">
<h2>Our Products</h2>
<div class="products">
<div class="product">
<img src="https://images.unsplash.com/photo-1618354691870-4017f82e69b3?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=500" alt="Men's T-Shirt">
<h3>Men's T-Shirt</h3>
<p>₹299</p>
<a href="https://wa.me/918810368375?text=Hello%2C%20I%20want%20to%20order%20Men's%20T-Shirt" class="cta-button">Buy Now</a>
</div>
<div class="product">
<img src="https://images.unsplash.com/photo-1593032465176-1a2ab9d43f6c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=500" alt="Men's Shirt">
<h3>Men's Shirt</h3>
<p>₹499</p>
<a href="https://wa.me/918810368375?text=Hello%2C%20I%20want%20to%20order%20Men's%20Shirt" class="cta-button">Buy Now</a>
</div>
<div class="product">
<img src="https://images.unsplash.com/photo-1600185365195-f9b3c4b0b3b5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=500" alt="Hoodie">
<h3>Hoodie</h3>
<p>₹799</p>
<a href="https://wa.me/918810368375?text=Hello%2C%20I%20want%20to%20order%20Hoodie" class="cta-button">Buy Now</a>
</div>
<div class="product">
<img src="https://images.unsplash.com/photo-1592496001023-4f6ed37c96e0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&w=500" alt="Denim Jeans">
<h3>Denim Jeans</h3>
<p>₹899</p>
<a href="https://wa.me/918810368375?text=Hello%2C%20I%20want%20to%20order%20Denim%20Jeans" class="cta-button">Buy Now</a>
</div>
</div>
</section>

<section id="about">
<h2>About Us</h2>
<p>Royal Collections is a premium clothing brand where you get the latest fashion, best quality, and the right price. We provide T-shirts, Shirts, Hoodies, and Jeans at direct factory rates.</p>
</section>

<section id="reviews">
<h2>Customer Reviews</h2>
<div class="reviews">
<div class="card">
<p>⭐⭐⭐⭐⭐</p>
<p>"Quality is amazing! Price is perfect. Highly recommended!" – Sameer</p>
</div>
<div class="card">
<p>⭐⭐⭐⭐⭐</p>
<p>"Fast delivery and premium quality clothes." – Irfan</p>
</div>
<div class="card">
<p>⭐⭐⭐⭐⭐</p>
<p>"Best clothing store, cheapest prices!" – Rahul</p>
</div>
</div>
</section>

<section id="categories">
<h2>Shop by Category</h2>
<div class="categories">
<div class="card">Men</div>
<div class="card">Women</div>
<div class="card">Kids</div>
</div>
</section>

<section id="size-chart">
<h2>Size Chart</h2>
<table>
<tr><th>Size</th><th>Chest (inches)</th><th>Length (inches)</th></tr>
<tr><td>S</td><td>36</td><td>26</td></tr>
<tr><td>M</td><td>38</td><td>27</td></tr>
<tr><td>L</td><td>40</td><td>28</td></tr>
<tr><td>XL</td><td>42</td><td>29</td></tr>
</table>
</section>

<section id="contact">
<h2>Contact Us</h2>
<p>📞 Phone: 8810368375</p>
<p>📩 WhatsApp: <a href="https://wa.me/918810368375?text=Hello%2C%20I%20want%20to%20order%20from%20Royal%20Collections">Chat Now</a></p>
<p>📍 Location: India</p>
<a href="https://wa.me/918810368375?text=Hello%2C%20I%20want%20to%20order%20from%20Royal%20Collections" class="cta-button">Order via WhatsApp</a>
</section>

</div>

<footer>
<p>Accepted Payments: UPI | Paytm | PhonePe | Google Pay | Cash on Delivery</p>
<div class="social">
<a href="#">Instagram</a> | <a href="#">Facebook</a> | <a href="#">YouTube</a>
</div>
<p>© 2025 Sabir Clothing Store | All Rights Reserved</p>
</footer>

</body>
</html>

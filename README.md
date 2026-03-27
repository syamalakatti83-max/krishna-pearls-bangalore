<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Krishna Pearls Bangalore</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: #000;
  color: #fff;
}

/* Navbar */
nav {
  display: flex;
  justify-content: space-between;
  padding: 15px 50px;
  background: rgba(0,0,0,0.8);
  position: fixed;
  width: 100%;
  top: 0;
}

nav h1 {
  color: gold;
}

nav a {
  color: #fff;
  margin-left: 20px;
  text-decoration: none;
}

/* Hero */
.hero {
  height: 100vh;
  background: url('YOUR-LOGO-IMAGE.jpg') center/contain no-repeat, linear-gradient(#000,#111);
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero h2 {
  font-size: 40px;
  color: gold;
}

.btn {
  margin-top: 20px;
  padding: 10px 25px;
  background: gold;
  color: black;
  border: none;
  cursor: pointer;
}

/* Sections */
section {
  padding: 80px 20px;
  text-align: center;
}

.products {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
  gap: 20px;
}

.card {
  background: #111;
  padding: 15px;
  border-radius: 10px;
}

.card img {
  width: 100%;
  border-radius: 10px;
}

/* Footer */
footer {
  background: #111;
  padding: 20px;
  text-align: center;
}

/* WhatsApp */
.whatsapp {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: green;
  color: white;
  padding: 15px;
  border-radius: 50%;
  text-decoration: none;
}
</style>

</head>

<body>

<!-- Navbar -->
<nav>
  <h1>Krishna Pearls</h1>
  <div>
    <a href="#">Home</a>
    <a href="#products">Collections</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- Hero -->
<div class="hero">
  <div>
    <h2>Pure Elegance in Every Pearl</h2>
    <button class="btn">Shop Now</button>
  </div>
</div>

<!-- Products -->
<section id="products">
  <h2>Our Collections</h2>
  <div class="products">
    
    <div class="card">
      <img src="https://via.placeholder.com/300" alt="">
      <h3>Pearl Necklace</h3>
      <p>₹2,999</p>
      <button class="btn">Buy Now</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300" alt="">
      <h3>Pearl Earrings</h3>
      <p>₹999</p>
      <button class="btn">Buy Now</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/300" alt="">
      <h3

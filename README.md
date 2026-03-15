<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Camfire Cafe</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#111;
color:white;
}

header{
background:url('https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb') center/cover;
height:80vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
}

header h1{
font-size:60px;
letter-spacing:3px;
}

header p{
margin-top:10px;
font-size:20px;
color:#ddd;
}

.btn{
margin-top:20px;
padding:12px 25px;
background:#ff5a1f;
border:none;
color:white;
font-size:16px;
border-radius:5px;
cursor:pointer;
text-decoration:none;
}

section{
padding:70px 10%;
}

h2{
font-size:35px;
margin-bottom:20px;
color:#ff5a1f;
}

.about{
max-width:800px;
line-height:1.7;
}

.menu{
text-align:center;
}

.menu a{
display:inline-block;
margin-top:20px;
padding:15px 35px;
background:#ff5a1f;
color:white;
text-decoration:none;
border-radius:5px;
}

.reviews{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.review{
background:#1c1c1c;
padding:20px;
border-radius:8px;
}

.contact p{
margin:10px 0;
font-size:18px;
}

footer{
background:#000;
text-align:center;
padding:20px;
color:#aaa;
}
</style>

</head>
<body>

<header>
<div>
<h1>Camfire Cafe</h1>
<p>Authentic Thai Food • Chill Cafe Experience</p>
<a class="btn" href="#menu">View Menu</a>
</div>
</header>

<section class="about">
<h2>About Us</h2>
<p>
Welcome to <b>Camfire Cafe</b>, a cozy and chill cafe located in Pasir Gudang.
We serve delicious Thai food and Western dishes with authentic flavours.
Our Tom Yam, Thai Salad, and Fish & Chips are some of the favourites among our customers.
</p>

<p>
With meals priced around <b>RM20 - RM40 per person</b>, we offer great food,
comfortable ambience, and friendly service.
</p>
</section>

<section class="menu" id="menu">
<h2>Our Menu</h2>
<p>Explore our full menu online</p>
<a href="https://v3.feedme.cc/63327ee39bbffb001b800764" target="_blank">View Full Menu</a>
</section>

<section>
<h2>Customer Reviews ⭐⭐⭐⭐⭐</h2>

<div class="reviews">

<div class="review">
<p>Everything is great. Authentic Thai food especially the Tom Yum and seafood drinks. Nice ambience!</p>
</div>

<div class="review">
<p>Dory and chips highly recommended. The tartar sauce and fish batter are amazing. Better than many places I've tried.</p>
</div>

<div class="review">
<p>The ambience was chill and charming. Food was amazing and the price is worth the portion.</p>
</div>

<div class="review">
<p>Delicious food! Tom Yam and Thai salad taste authentic. Highly recommended restaurant.</p>
</div>

</div>
</section>

<section class="contact">
<h2>Visit Us</h2>

<p><b>Location:</b><br>
Jalan Belatuk 4, Taman Scientex<br>
81700 Pasir Gudang, Johor Darul Ta’azin
</p>

<p><b>Phone:</b> 07-2551573</p>

<p><b>Opening Hours:</b><br>
Open Daily • Closes 10 PM</p>

</section>

<footer>
<p>© 2026 Camfire Cafe | Pasir Gudang</p>
</footer>

</body>
</html>

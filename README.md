<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Focus TV Studio</title>

<style>

body{
margin:0;
font-family:Arial, Helvetica, sans-serif;
background:#0d0d0d;
color:white;
}

header{
background:black;
padding:20px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:28px;
font-weight:bold;
color:gold;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
}

.hero{
height:90vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),
url('https://images.unsplash.com/photo-1516035069371-29a1b244cc32');
background-size:cover;
background-position:center;
}

.hero h1{
font-size:55px;
color:gold;
}

.hero p{
font-size:20px;
}

.btn{
background:gold;
color:black;
padding:15px 30px;
text-decoration:none;
font-weight:bold;
border-radius:6px;
}

.services{
padding:60px 20px;
text-align:center;
}

.services h2{
color:gold;
margin-bottom:40px;
}

.service-box{
display:inline-block;
width:250px;
margin:15px;
padding:25px;
background:#1a1a1a;
border-radius:10px;
}

.gallery{
padding:60px 20px;
text-align:center;
}

.gallery h2{
color:gold;
margin-bottom:30px;
}

.gallery img{
width:300px;
margin:10px;
border-radius:10px;
}

.about{
padding:60px;
text-align:center;
background:#111;
}

.about h2{
color:gold;
}

.contact{
padding:60px;
text-align:center;
}

.whatsapp{
background:#25D366;
padding:15px 30px;
color:white;
text-decoration:none;
font-weight:bold;
border-radius:8px;
}

footer{
text-align:center;
padding:20px;
background:black;
color:#aaa;
}

</style>
</head>

<body>

<header>

<div class="logo">FOCUS TV</div>

<nav>
<a href="#">Home</a>
<a href="#services">Services</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero">

<div>
<h1>Focus TV Studio</h1>
<p>Photography • Video Coverage • Flex Banner • Photo Books</p>
<br>
<a class="btn" href="https://wa.me/2347028273863">Book Now</a>
</div>

</section>

<section id="services" class="services">

<h2>Our Services</h2>

<div class="service-box">
<h3>Photography</h3>
<p>Professional photography for weddings, birthdays and events.</p>
</div>

<div class="service-box">
<h3>Video Coverage</h3>
<p>High quality video recording and editing.</p>
</div>

<div class="service-box">
<h3>Photo Book</h3>
<p>Beautiful printed photo albums.</p>
</div>

<div class="service-box">
<h3>Flex Banner</h3>
<p>Banner design and printing for events and business.</p>
</div>

</section>

<section id="gallery" class="gallery">

<h2>Our Work</h2>

<img src="https://images.unsplash.com/photo-1492724441997-5dc865305da7">
<img src="https://images.unsplash.com/photo-1502920917128-1aa500764cbd">
<img src="https://images.unsplash.com/photo-1510127034890-ba27508e9f1c">

</section>

<section class="about">

<h2>Why Choose Focus TV</h2>

<p>
We capture your best memories with professional cameras and creative editing.
Focus TV provides high quality photography, video coverage, photo books and flex banner designs.
</p>

</section>

<section id="contact" class="contact">

<h2>Book Us Today</h2>

<p>WhatsApp: 07028273863</p>

<br>

<a class="whatsapp" href="https://wa.me/2347028273863">
Chat on WhatsApp
</a>

</section>

<footer>

<p>© 2026 Focus TV Studio</p>

</footer>

</body>
</html>

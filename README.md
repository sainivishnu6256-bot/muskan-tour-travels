<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Muskan Tour and Travels</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#0f0f0f;
color:white;
}

header{
background:linear-gradient(135deg,#111,#222);
padding:25px;
text-align:center;
border-bottom:2px solid gold;
}

header h1{
font-family:'Playfair Display',serif;
font-size:32px;
color:gold;
}

nav{
text-align:center;
padding:15px;
background:#111;
}

nav a{
color:white;
margin:0 20px;
text-decoration:none;
font-weight:500;
transition:0.3s;
}

nav a:hover{
color:gold;
}

.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1501785888041-af3ef285b470') center/cover;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background-blend-mode:overlay;
background-color:rgba(0,0,0,0.6);
}

.hero h2{
font-size:45px;
font-family:'Playfair Display',serif;
color:gold;
}

.hero p{
margin:20px 0;
font-size:18px;
}

.btn{
background:gold;
color:black;
padding:12px 30px;
border-radius:30px;
text-decoration:none;
font-weight:bold;
transition:0.3s;
}

.btn:hover{
background:white;
}

section{
padding:80px 10%;
}

h2{
text-align:center;
margin-bottom:50px;
color:gold;
font-family:'Playfair Display',serif;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:rgba(255,255,255,0.05);
padding:30px;
border-radius:15px;
backdrop-filter:blur(10px);
border:1px solid rgba(255,215,0,0.3);
transition:0.4s;
}

.card:hover{
transform:translateY(-10px);
border:1px solid gold;
}

.route{
background:linear-gradient(135deg,#111,#1a1a1a);
padding:40px;
border-radius:20px;
text-align:center;
border:1px solid gold;
}

form input, form textarea{
width:100%;
padding:12px;
margin:10px 0;
border-radius:10px;
border:none;
}

form button{
background:gold;
color:black;
padding:12px;
border:none;
border-radius:10px;
cursor:pointer;
font-weight:bold;
}

footer{
background:#111;
text-align:center;
padding:25px;
border-top:1px solid gold;
margin-top:40px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px;
border-radius:50%;
font-size:22px;
text-decoration:none;
}

.call{
position:fixed;
bottom:90px;
right:20px;
background:gold;
color:black;
padding:15px;
border-radius:50%;
font-size:20px;
text-decoration:none;
}
</style>
</head>

<body>

<header>
<h1>Muskan Tour and Travels</h1>
<p>Safar Vishwas Ka – Since 2010 | 15+ Years Experience</p>
</header>

<nav>
<a href="#about">About</a>
<a href="#vehicles">Vehicles</a>
<a href="#tours">Tours</a>
<a href="#route">Route</a>
<a href="#booking">Booking</a>
</nav>

<div class="hero">
<h2>Luxury Rajasthan & All India Tours</h2>
<p>Travel with Comfort, Safety & Experience</p>
<a href="#booking" class="btn">Book Now</a>
</div>

<section id="about">
<h2>About Us</h2>
<p style="text-align:center;">
Serving since 2010, Muskan Tour and Travels provides premium travel services from Jaipur across Rajasthan and India.
</p>
</section>

<section id="vehicles">
<h2>Our Premium Fleet</h2>
<div class="cards">
<div class="card"><h3>Kia Carens Clavis</h3><p>Luxury Family Travel</p></div>
<div class="card"><h3>Force Tufan</h3><p>Group Tours</p></div>
<div class="card"><h3>Maruti Eeco (2)</h3><p>Budget Travel</p></div>
<div class="card"><h3>Small Cars</h3><p>Economy Trips</p></div>
</div>
</section>

<section id="route">
<h2>Daily Special Route</h2>
<div class="route">
Jaipur → Khatu Shyam Ji → Jeen Mata → Harsh Parvat → Lakshmi Mata → Salasar Balaji → Jaipur
</div>
</section>

<section id="booking">
<h2>Book Your Luxury Ride</h2>
<form>
<input type="text" placeholder="Your Name" required>
<input type="tel" placeholder="Phone Number" required>
<input type="text" placeholder="Pickup Location" required>
<input type="text" placeholder="Destination" required>
<input type="date" required>
<textarea placeholder="Message"></textarea>
<button type="submit">Submit Booking</button>
</form>
</section>

<footer>
© 2026 Muskan Tour and Travels | Jaipur Rajasthan
</footer>

<a href="https://wa.me/917891586517" class="whatsapp">💬</a>
<a href="tel:+917891586517" class="call">📞</a>

</body>
</html>

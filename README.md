<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Muskan Tour and Travels</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f4f9ff;
}

header{
background:linear-gradient(135deg,#0077b6,#00b4d8);
color:white;
padding:20px;
text-align:center;
}

nav{
background:#023e8a;
padding:15px;
text-align:center;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-weight:500;
}

.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1501785888041-af3ef285b470') center/cover;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
color:white;
text-align:center;
padding:20px;
}

.hero h2{
font-size:40px;
}

.hero p{
margin:20px 0;
font-size:18px;
}

.btn{
background:orange;
padding:12px 25px;
color:white;
border-radius:30px;
text-decoration:none;
font-weight:bold;
}

section{
padding:70px 10%;
}

h2{
text-align:center;
margin-bottom:40px;
color:#023e8a;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
}

.route{
background:#0077b6;
color:white;
padding:40px;
border-radius:15px;
text-align:center;
font-weight:500;
}

form input, form textarea{
width:100%;
padding:12px;
margin:10px 0;
border-radius:8px;
border:1px solid #ccc;
}

form button{
background:#0077b6;
color:white;
padding:12px;
border:none;
border-radius:8px;
cursor:pointer;
}

footer{
background:#023e8a;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

/* WhatsApp Button */
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

/* Call Button */
.call{
position:fixed;
bottom:90px;
right:20px;
background:#0077b6;
color:white;
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
<a href="#route">Daily Route</a>
<a href="#booking">Booking</a>
</nav>

<div class="hero">
<h2>Explore Rajasthan & All India With Comfort</h2>
<p>Reliable Taxi & Tour Services from Jaipur</p>
<a href="#booking" class="btn">Book Now</a>
</div>

<section id="about">
<h2>About Us</h2>
<p style="text-align:center;">
Muskan Tour and Travels has been serving since 2010.  
We provide Rajasthan tours, All India travel services, Jaipur sightseeing and outstation taxi services with professional drivers.
</p>
</section>

<section id="vehicles">
<h2>Our Vehicles</h2>
<div class="cards">
<div class="card"><h3>Kia Carens Clavis</h3><p>Comfort family travel</p></div>
<div class="card"><h3>Force Tufan</h3><p>Group & Tour Trips</p></div>
<div class="card"><h3>Maruti Eeco (2)</h3><p>Budget Friendly</p></div>
<div class="card"><h3>Small Cars</h3><p>Economy Travel</p></div>
</div>
</section>

<section id="tours">
<h2>Tour Packages</h2>
<div class="cards">
<div class="card"><h3>Rajasthan Tour</h3><p>Jaipur, Udaipur, Jodhpur, Jaisalmer</p></div>
<div class="card"><h3>All India Tour</h3><p>Delhi, Agra, Mumbai, Goa & More</p></div>
<div class="card"><h3>Jaipur Sightseeing</h3><p>Full Day Local Tour</p></div>
</div>
</section>

<section id="route">
<h2>Daily Special Route</h2>
<div class="route">
Jaipur → Khatu Shyam Ji → Jeen Mata → Harsh Parvat → Lakshmi Mata → Salasar Balaji → Jaipur
</div>
</section>

<section id="booking">
<h2>Book Your Trip</h2>
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

# gernell2116.github.io<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gernell's Barber Studio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#111;
    color:white;
}

header{
    background:black;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#d4af37;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    transition:.3s;
}

nav a:hover{
    color:#d4af37;
}

.hero{
    height:90vh;
    background:linear-gradient(rgba(0,0,0,.7),
    rgba(0,0,0,.7)),
    url('https://images.unsplash.com/photo-1621605815971-fbc98d665033');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
}

.hero-content h1{
    font-size:60px;
    margin-bottom:20px;
}

.hero-content p{
    font-size:20px;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:15px 35px;
    background:#d4af37;
    color:black;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

section{
    padding:80px 8%;
}

.section-title{
    text-align:center;
    font-size:40px;
    margin-bottom:50px;
    color:#d4af37;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1c1c1c;
    padding:30px;
    border-radius:10px;
    text-align:center;
}

.card h3{
    margin-bottom:15px;
    color:#d4af37;
}

.about{
    text-align:center;
    max-width:800px;
    margin:auto;
    line-height:1.8;
}

.pricing{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.price-box{
    background:#1c1c1c;
    padding:30px;
    text-align:center;
    border-radius:10px;
}

.price{
    font-size:32px;
    color:#d4af37;
    margin:15px 0;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px 0;
    font-size:18px;
}

footer{
    background:black;
    text-align:center;
    padding:20px;
    color:#888;
}

@media(max-width:768px){
.hero-content h1{
    font-size:40px;
}
}
</style>
</head>

<body>

<header>
    <div class="logo">💈 Gernell's Barber Studio</div>

    <nav>
        <a href="#services">Services</a>
        <a href="#about">About</a>
        <a href="#pricing">Pricing</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Fresh Cuts. Sharp Style.</h1>
        <p>Professional barber services with precision and confidence.</p>

        <a href="https://wa.me/5920000000" class="btn">
            Book Appointment
        </a>
    </div>
</section>

<section id="services">
    <h2 class="section-title">Our Services</h2>

    <div class="services">

        <div class="card">
            <h3>Classic Haircut</h3>
            <p>Clean and stylish haircut tailored to you.</p>
        </div>

        <div class="card">
            <h3>Skin Fade</h3>
            <p>Sharp fades with professional finishing.</p>
        </div>

        <div class="card">
            <h3>Beard Grooming</h3>
            <p>Precision trimming and beard shaping.</p>
        </div>

        <div class="card">
            <h3>Kids Haircuts</h3>
            <p>Fresh styles for young gentlemen.</p>
        </div>

    </div>
</section>

<section id="about">
    <h2 class="section-title">About Us</h2>

    <div class="about">
        <p>
            At Gernell's Barber Studio, we believe every haircut is a
            statement. Our goal is to provide professional grooming,
            exceptional customer service, and modern styles that keep
            our clients looking their absolute best.
        </p>
    </div>
</section>

<section id="pricing">
    <h2 class="section-title">Pricing</h2>

    <div class="pricing">

        <div class="price-box">
            <h3>Haircut</h3>
            <div class="price">$2,000</div>
        </div>

        <div class="price-box">
            <h3>Fade</h3>
            <div class="price">$2,500</div>
        </div>

        <div class="price-box">
            <h3>Haircut + Beard</h3>
            <div class="price">$3,500</div>
        </div>

    </div>
</section>

<section id="contact">
    <h2 class="section-title">Contact Us</h2>

    <div class="contact">
        <p>📍 Georgetown, Guyana</p>
        <p>📞 +592 746 7605</p>
        <p>📱 WhatsApp Available</p>
        <p>✉️ gernellseecharranxx21@gmail.com</p>
    </div>
</section>

<footer>
    © 2026 Gernell's Barber Studio. All Rights Reserved.
</footer>

</body>
</html>
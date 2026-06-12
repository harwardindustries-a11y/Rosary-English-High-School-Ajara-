<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rosary English High School, Ajara</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family: Arial, sans-serif;
    line-height:1.6;
    color:#333;
}

/* Navigation */
nav{
    position:fixed;
    top:0;
    width:100%;
    background:rgba(0,0,0,0.85);
    z-index:1000;
    padding:15px 0;
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
}

nav ul li{
    margin:0 20px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    transition:0.3s;
}

nav ul li a:hover{
    color:#ffd700;
}

/* Hero Section */
.hero{
    height:100vh;
    background:url("campus.jpg") center/cover no-repeat;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero-content{
    background:rgba(0,0,0,0.6);
    padding:40px;
    border-radius:10px;
}

.hero h1{
    font-size:60px;
}

.hero p{
    font-size:24px;
    margin-top:10px;
}

/* Sections */
section{
    padding:80px 10%;
}

h2{
    text-align:center;
    margin-bottom:30px;
    color:#003366;
    font-size:40px;
}

p{
    font-size:18px;
    margin-bottom:15px;
}

/* Logo Section */
.logo{
    text-align:center;
}

.logo img{
    width:220px;
    margin-bottom:20px;
}

/* Cards */
.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:10px;
    padding:25px;
    box-shadow:0 4px 10px rgba(0,0,0,0.15);
}

.card h3{
    color:#003366;
    margin-bottom:10px;
}

/* Church */
.church{
    background:#f4f4f4;
}

.church img{
    width:100%;
    max-width:900px;
    display:block;
    margin:auto;
    border-radius:10px;
    margin-bottom:25px;
}

/* Gallery */
.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    border-radius:10px;
    height:250px;
    object-fit:cover;
    box-shadow:0 4px 8px rgba(0,0,0,0.2);
}

/* Contact */
.contact{
    background:#003366;
    color:white;
    text-align:center;
}

.contact h2{
    color:white;
}

/* Footer */
footer{
    background:#001f3f;
    color:white;
    text-align:center;
    padding:20px;
}

@media(max-width:768px){

.hero h1{
    font-size:38px;
}

.hero p{
    font-size:18px;
}

nav ul{
    flex-wrap:wrap;
}
}
</style>
</head>

<body>

<!-- Navigation -->
<nav>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#logo">Logo</a></li>
<li><a href="#church">Church</a></li>
<li><a href="#facilities">Facilities</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<!-- Hero Section -->
<section class="hero" id="home">
<div class="hero-content">
<h1>Rosary English High School, Ajara</h1>
<p>LET YOUR LIGHT SHINE</p>
</div>
</section>

<!-- About Section -->
<section id="about">
<h2>About Us</h2>

<p>
Rosary English High School, Ajara is a distinguished educational institution
committed to providing quality education from Nursery to Higher Secondary and
Junior College levels. The school nurtures academic excellence, character,
discipline, and leadership among students.
</p>

<p>
Our institution offers education from Nursery, Junior KG, Senior KG,
Classes I to VII, Secondary Education from Classes VIII to X,
and Higher Secondary/Junior College Classes XI and XII.
</p>

<p>
We strive to create a learning environment that develops intellectual,
social, emotional, and moral values while preparing students for future success.
</p>
</section>

<!-- Logo Section -->
<section class="logo" id="logo">
<h2>Our School Logo</h2>

<img src="logo.png" alt="School Logo">

<p>
The emblem of Rosary English High School symbolizes knowledge,
faith, service, and enlightenment. The lamp represents wisdom and
education, while the cross signifies Christian values and moral strength.
</p>

<p>
The motto <strong>"LET YOUR LIGHT SHINE"</strong> inspires students
to become responsible citizens and future leaders.
</p>
</section>

<!-- Church Section -->
<section class="church" id="church">

<h2>Rosary Church, Ajara</h2>

<img src="church.jpg" alt="Rosary Church">

<p>
Rosary Church is an important spiritual and cultural landmark associated
with the history and values of the institution. It symbolizes faith,
compassion, discipline, and community service.
</p>

<p>
The church has inspired generations of students to uphold moral values,
respect, and service towards society.
</p>

</section>

<!-- Vision & Mission -->
<section>

<h2>Vision & Mission</h2>

<div class="cards">

<div class="card">
<h3>Our Vision</h3>
<p>
To create a dynamic learning environment that promotes academic excellence,
innovation, leadership, and strong moral values.
</p>
</div>

<div class="card">
<h3>Our Mission</h3>
<p>
To provide quality education that nurtures intellectual growth,
scientific thinking, creativity, discipline, and social responsibility.
</p>
</div>

</div>

</section>

<!-- Facilities -->
<section id="facilities">

<h2>Facilities</h2>

<div class="cards">

<div class="card">
<h3>Computer Laboratory</h3>
<p>
Modern computers and digital learning tools help students develop
essential technology skills.
</p>
</div>

<div class="card">
<h3>Science Laboratory</h3>
<p>
A well-equipped laboratory that encourages scientific exploration
through practical learning.
</p>
</div>

<div class="card">
<h3>Physics Laboratory</h3>
<p>
Advanced facilities for higher secondary students to perform
experiments and understand scientific concepts.
</p>
</div>

<div class="card">
<h3>Library</h3>
<p>
A rich collection of books and educational resources to promote
reading and self-learning.
</p>
</div>

<div class="card">
<h3>Sports Facilities</h3>
<p>
Playgrounds and sports activities that support physical fitness
and teamwork.
</p>
</div>

<div class="card">
<h3>Smart Classrooms</h3>
<p>
Interactive learning environments that enhance student engagement.
</p>
</div>

</div>

</section>

<!-- Gallery -->
<section id="gallery">

<h2>Photo Gallery</h2>

<div class="gallery">

<img src="campus.jpg" alt="Campus">

<img src="church.jpg" alt="Church">

<img src="logo.png" alt="Logo">

</div>

</section>

<!-- Contact -->
<section class="contact" id="contact">

<h2>Contact Us</h2>

<p><strong>Rosary English High School, Ajara</strong></p>

<p>Ajara, Kolhapur District, Maharashtra, India</p>

<p>Email: info@rosaryschoolajara.in</p>

<p>Phone: +91 XXXXXXXXXX</p>

</section>

<!-- Footer -->
<footer>
<p>© 2025 Rosary English High School, Ajara. All Rights Reserved.</p>
</footer>

</body>
</html>

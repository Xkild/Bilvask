<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Xkild | Professional Website Developer</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: #0f172a;
    color: white;
}

header {
    padding: 20px 10%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: 700;
    color: #38bdf8;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 25px;
    transition: 0.3s;
}

nav a:hover {
    color: #38bdf8;
}

.hero {
    height: 90vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 0 10%;
}

.hero h1 {
    font-size: 50px;
}

.hero span {
    color: #38bdf8;
}

.hero p {
    margin: 20px 0;
    font-size: 18px;
    max-width: 600px;
}

.btn {
    display: inline-block;
    padding: 12px 30px;
    background: #38bdf8;
    color: black;
    text-decoration: none;
    border-radius: 30px;
    font-weight: 600;
    transition: 0.3s;
}

.btn:hover {
    background: white;
}

section {
    padding: 80px 10%;
}

.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.card {
    background: #1e293b;
    padding: 30px;
    border-radius: 15px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
    background: #334155;
}

footer {
    text-align: center;
    padding: 30px;
    background: #1e293b;
    margin-top: 50px;
}
</style>
</head>
<body>

<header>
    <div class="logo">Xkild</div>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero">
    <h1>I Build <span>Professional Websites</span> for Companies</h1>
    <p>Helping businesses grow online with modern, fast, and high-converting websites.</p>
    <a href="#contact" class="btn">Work With Me</a>
</div>

<section id="about">
    <h2>About Me</h2>
    <p>I am Xkild, a professional website developer helping companies build powerful online presence. I create modern, responsive, and fast websites designed to convert visitors into customers.</p>
</section>

<section id="services">
    <h2>My Services</h2>
    <div class="services">
        <div class="card">
            <h3>Business Websites</h3>
            <p>Professional websites for companies and brands.</p>
        </div>
        <div class="card">
            <h3>E-Commerce</h3>
            <p>Online stores that convert visitors into customers.</p>
        </div>
        <div class="card">
            <h3>Website Redesign</h3>
            <p>Modern redesigns to improve performance and branding.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: your@email.com</p>
    <p>Instagram: @xkild</p>
</section>

<footer>
    <p>© 2026 Xkild | All Rights Reserved</p>
</footer>

</body>
</html>

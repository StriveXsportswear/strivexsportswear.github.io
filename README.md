[index.html]
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>StriveX Sportswear</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
<h1>StriveX</h1>
<nav>
<a href="#about">About</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>
</header>
<section class="hero">
<h2>Custom Sublimated Kits for Teams</h2>
<p>Built for performance. Designed to stand out.</p>
<a href="https://www.instagram.com/strivex_sports" target="_blank" class="btn">Order Now</a>
</section>
<section id="about" class="section">
<h2>About StriveX</h2>
<p>Premium custom sublimated kits for clubs and teams.</p>
</section>
<section id="gallery" class="section">
<h2>Our Work</h2>
<div class="gallery">
<img src="images/kit1.jpg">
<img src="images/kit2.jpg">
<img src="images/team.jpg">
</div>
</section>
<section id="contact" class="section">
<h2>Contact</h2>
<p>Email: strivexsportswear@gmail.com</p>
<p>Instagram: @strivex_sports</p>
<p>Facebook: StriveX Sportswear</p>
</section>
</body>
</html>
[style.css]
body {
background: #0a0f0a;
color: white;
font-family: Arial;
}
header {
display: flex;
justify-content: space-between;
padding: 20px;
background: black;
}
h1 { color: #00ff88; }
.hero {
text-align: center;
padding: 80px;
background: linear-gradient(black, #001a0f);
}
.btn {
background: #00ff88;
padding: 10px 20px;
color: black;
}
.gallery {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
gap: 10px;
}
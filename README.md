<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Moses Paul | Portfolio</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#0d1117;
color:white;
line-height:1.6;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:#161b22;
position:sticky;
top:0;
}

.logo{
font-size:28px;
font-weight:bold;
color:#00bfff;
}

nav a{
text-decoration:none;
color:white;
margin-left:25px;
transition:.3s;
}

nav a:hover{
color:#00bfff;
}

.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
padding:20px;
}

.hero h1{
font-size:60px;
}

.hero span{
color:#00bfff;
}

.hero p{
margin:20px 0;
font-size:20px;
color:#bbb;
max-width:600px;
}

button{
padding:15px 35px;
border:none;
background:#00bfff;
color:white;
font-size:18px;
border-radius:30px;
cursor:pointer;
transition:.3s;
}

button:hover{
transform:scale(1.05);
}

section{
padding:80px 10%;
}

h2{
font-size:40px;
margin-bottom:30px;
text-align:center;
color:#00bfff;
}

.about p{
text-align:center;
max-width:700px;
margin:auto;
font-size:18px;
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:20px;
margin-top:40px;
}

.skill{
background:#161b22;
padding:30px;
border-radius:15px;
text-align:center;
transition:.3s;
}

.skill:hover{
transform:translateY(-10px);
background:#1f2937;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
}

.card{
background:#161b22;
border-radius:15px;
overflow:hidden;
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
}

.card h3{
padding:15px;
}

.card p{
padding:0 15px 20px;
color:#ccc;
}

.contact{
text-align:center;
}

.contact input,
.contact textarea{
width:100%;
padding:15px;
margin:10px 0;
background:#161b22;
border:none;
color:white;
border-radius:10px;
}

footer{
text-align:center;
padding:20px;
background:#161b22;
margin-top:50px;
}

@media(max-width:768px){

.hero h1{
font-size:40px;
}

nav{
display:none;
}

}
</style>

</head>
<body>

<header>

<div class="logo">Moses.</div>

<nav>
<a href="#">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Hello, I'm <span>Moses Paul</span></h1>

<p>
A passionate Front-End Web Developer who loves creating modern,
responsive and beautiful websites.
</p>

<a href="https://wa.me/2348126424446" target="_blank" class="btn">
<button>Requst for CV Download</button></a>

</section>

<section class="about" id="about">

<h2>About Me</h2>

<p>
I am a web developer who enjoys building responsive websites with
HTML and CSS. I am constantly improving my skills and working on
new projects to become a professional developer.
</p>

</section>

<section id="skills">

<h2>My Skills</h2>

<div class="skills">

<div class="skill">
<h3>HTML5</h3>
</div>

<div class="skill">
<h3>CSS3</h3>
</div>

<div class="skill">
<h3>Responsive Design</h3>
</div>

<div class="skill">
<h3>UI Design</h3>
</div>

</div>

</section>

<section id="projects">

<h2>Projects</h2>

<div class="projects">

<div class="card">
<img src="https://picsum.photos/600/400?1">
<h3>Portfolio Website</h3>
<p>Modern responsive portfolio created with HTML and CSS.</p>
</div>

<div class="card">
<img src="https://picsum.photos/600/400?2">
<h3>Restaurant Website</h3>
<p>Responsive restaurant landing page.</p>
</div>

<div class="card">
<img src="https://picsum.photos/600/400?3">
<h3>Travel Website</h3>
<p>Beautiful travel website UI.</p>
</div>

</div>

</section>

<section class="contact" id="contact">

<h2>Contact Me</h2>

<input type="text" placeholder="Your Name">

<input type="email" placeholder="Your Email">

<textarea rows="6" placeholder="Your Message"></textarea>

<a href="https://wa.me/2348126424446" target="_blank" class="btn"><button>Send Message</button></a>

</section>

<footer>

<p>© 2026 Moses Paul. All Rights Reserved.</p>

</footer>

</body>
</html>
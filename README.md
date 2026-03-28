<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>D_varun_1</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

<style>
:root {
    --bg:#0a0a0a;
    --text:#ffffff;
    --card:#111;
    --accent:#f59e0b;
}

.light-mode {
    --bg:#ffffff;
    --text:#111;
    --card:#f2f2f2;
}

html { scroll-behavior: smooth; }

body {
    margin:0;
    font-family:'Poppins',sans-serif;
    background:var(--bg);
    color:var(--text);
}

/* INTRO */
#intro {
    position:fixed;
    width:100%;
    height:100%;
    background:#0a0a0a;
    display:flex;
    justify-content:center;
    align-items:center;
    z-index:9999;
}

.intro-text {
    font-size:2.5rem;
    font-weight:600;
    opacity:0;
    transform:translateY(30px);
    animation:introAnim 1.5s forwards;
}

@keyframes introAnim {
    to {opacity:1; transform:translateY(0);}
}

/* TOGGLE */
.toggle {
    position:fixed;
    top:15px;
    right:15px;
    background:var(--card);
    padding:10px;
    border-radius:8px;
    cursor:pointer;
}

/* HEADER */
header {
    text-align:center;
    padding:40px 20px;
}

.logo {
    width:110px;
    border-radius:50%;
}

.name {
    font-size:2rem;
    font-weight:600;
}

.bio {
    max-width:500px;
    margin:auto;
    opacity:0.9;
}

/* BUTTON */
.btn {
    display:inline-block;
    margin:10px 5px;
    padding:10px 18px;
    background:var(--accent);
    color:black;
    border-radius:6px;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}

.btn:hover { transform:scale(1.05); }

/* SECTION */
.section {
    padding:30px 20px;
    max-width:900px;
    margin:auto;
}

.fade {
    opacity:0;
    transform:translateY(30px);
    transition:0.8s;
}

.fade.show {
    opacity:1;
    transform:translateY(0);
}

/* CARD */
.card {
    background:var(--card);
    padding:20px;
    border-radius:10px;
    transition:0.3s;
}

.card:hover { transform:translateY(-8px); }

/* SHORTS */
.feed {
    display:flex;
    flex-direction:column;
    align-items:center;
}

.short {
    width:100%;
    max-width:400px;
    aspect-ratio:9/16;
    margin:15px 0;
    border-radius:12px;
    overflow:hidden;
    transition:0.3s;
}

.short:hover { transform:scale(1.02); }

.short iframe {
    width:100%;
    height:100%;
    border:none;
}

/* CONTACT */
.phone {
    font-weight:600;
    font-size:18px;
}
</style>
</head>

<body>

<!-- INTRO -->
<div id="intro">
  <h1 class="intro-text">D_varun_1</h1>
</div>

<!-- THEME -->
<div class="toggle" onclick="toggleTheme()">🌙 / ☀️</div>

<header>
<img src="https://raw.githubusercontent.com/varundosuri-hub/My-website/main/channels4_profile.jpg" class="logo">

<h1 class="name">D_varun_1</h1>

<p class="bio">
I create modern, fast and professional websites for businesses 🚀  
Helping you grow online with design & promotion.
</p>

<a href="https://youtube.com/@d_varun_1?si=psJrYtxwx1C7k0Tl" target="_blank" class="btn">🎥 My YouTube</a>
<a href="#contact" class="btn">📞 Hire Me</a>
</header>

<!-- SERVICES -->
<div class="section fade">
<h2>💼 My Services</h2>
<div class="card">
<p>✔ Website design for your business</p>
<p>✔ YouTube & Instagram promotion</p>
<p>✔ Mobile friendly & fast websites</p>
</div>
</div>

<!-- SHORTS -->
<div class="section fade">
<h2>🔥 My Shorts</h2>
<div class="feed">
<div class="short"><iframe src="https://www.youtube.com/embed/cYzlmet1p8I"></iframe></div>
<div class="short"><iframe src="https://www.youtube.com/embed/k-QDnRax-7U"></iframe></div>
<div class="short"><iframe src="https://www.youtube.com/embed/SxylT8zFU44"></iframe></div>
<div class="short"><iframe src="https://www.youtube.com/embed/v8WKEaIHsuo"></iframe></div>
</div>
</div>

<!-- PRICING -->
<div class="section fade">
<h2>💰 Pricing Plans</h2>

<div class="card">
<h3>Basic Website</h3>
<span style="background:#ff4d4d;color:white;padding:4px 10px;border-radius:6px;font-size:12px;">60% OFF</span>
<p>✔ 1 Page Website</p>
<p>✔ Mobile Friendly</p>
<p>✔ Fast Delivery</p>
<p><span style="text-decoration:line-through;color:gray;">₹999</span> <strong style="font-size:22px;">₹399</strong></p>
<a href="https://wa.me/919440640277?text=I want Basic Website" class="btn">Choose Plan</a>
</div>

<div class="card" style="margin-top:20px;">
<h3>Standard Website</h3>
<span style="background:#ff4d4d;color:white;padding:4px 10px;border-radius:6px;font-size:12px;">50% OFF</span>
<p>✔ 3-5 Pages Website</p>
<p>✔ Modern Design</p>
<p>✔ WhatsApp Integration</p>
<p><span style="text-decoration:line-through;color:gray;">₹1599</span> <strong style="font-size:22px;">₹799</strong></p>
<a href="https://wa.me/919440640277?text=I want Standard Website" class="btn">Choose Plan</a>
</div>

<div class="card" style="margin-top:20px;">
<h3>Premium Website</h3>
<span style="background:#ff4d4d;color:white;padding:4px 10px;border-radius:6px;font-size:12px;">40% OFF</span>
<p>✔ Full Business Website</p>
<p>✔ Advanced Design</p>
<p>✔ SEO + Speed Optimized</p>
<p><span style="text-decoration:line-through;color:gray;">₹2499</span> <strong style="font-size:22px;">₹1499</strong></p>
<a href="https://wa.me/919440640277?text=I want Premium Website" class="btn">Choose Plan</a>
</div>

</div>

<!-- CONTACT -->
<div class="section fade" id="contact">
<h2>📞 Contact</h2>
<div class="card" style="text-align:center;">
<p>Let’s build your website 🚀</p>
<p class="phone">9440640277</p>
<a href="https://wa.me/919440640277" class="btn">WhatsApp</a>
</div>
</div>

<!-- FOOTER -->
<footer style="text-align:center;padding:25px;font-size:14px;opacity:0.7;">
© 2026 D_varun_1 • All Rights Reserved
</footer>

<script>
// INTRO
setTimeout(()=>{
 document.getElementById("intro").style.opacity="0";
 document.getElementById("intro").style.transition="0.8s";
 setTimeout(()=>{document.getElementById("intro").style.display="none";},800);
},2500);

// THEME
function toggleTheme(){
 document.body.classList.toggle("light-mode");
}

// SCROLL
const observer = new IntersectionObserver(entries=>{
 entries.forEach(entry=>{
  if(entry.isIntersecting){
    entry.target.classList.add("show");
  }
 });
});
document.querySelectorAll('.fade').forEach(el=>observer.observe(el));
</script>

</body>
</html>

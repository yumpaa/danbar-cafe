<!DOCTYPE html>
<html lang="so">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Danbar Cafe & Restaurant - Ultimate</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body {font-family:'Poppins',sans-serif;background:#0a0a0a;color:white;scroll-behavior:smooth}

.hero {height:100vh;background:url('https://images.unsplash.com/photo-1554118811-1e0d58224f24') center/cover no-repeat;display:flex;align-items:center;justify-content:center;text-align:center;position:relative}
.hero::after{content:'';position:absolute;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.75)}
.hero-content{position:relative;z-index:2;padding:20px}
.hero h1 {font-size:60px}
.hero p {margin-top:10px;color:#ddd}
.button {background:linear-gradient(45deg,#25D366,#1ebe5d);color:white;padding:16px 35px;border-radius:50px;text-decoration:none;display:inline-block;margin-top:25px;font-weight:600;box-shadow:0 5px 25px rgba(37,211,102,0.5)}

.container {padding:80px 20px;text-align:center;max-width:1100px;margin:auto}
.section {margin-top:80px}

.menu-grid {display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:20px}
.card {background:#141414;padding:25px;border-radius:20px;transition:0.3s}
.card:hover {transform:translateY(-8px)}

.features {display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.feature {background:#111;padding:30px;border-radius:20px}

.gallery {display:flex;gap:15px;overflow-x:auto}
.gallery img {width:300px;border-radius:20px}

iframe {border-radius:20px;margin-top:20px}

.cta {background:linear-gradient(45deg,#111,#1a1a1a);padding:50px;border-radius:20px}

.footer {margin-top:80px;color:#666}
</style>
</head>
<body>

<section class="hero">
  <div class="hero-content">
    <h1>Danbar Cafe & Restaurant ☕🍽️</h1>
    <p>Kafee + Cunto + Nasasho + Sawiro = Hal Meel</p>
    <a class="button" href="https://wa.me/252615769696">Dalbo / Book WhatsApp</a>
  </div>
</section>

<div class="container">

<div class="section">
<h2>🍽️ Menu</h2>
<div class="menu-grid">
<div class="card">Coffee & Drinks</div>
<div class="card">Meals</div>
<div class="card">Fast Food</div>
<div class="card">Desserts</div>
</div>
</div>

<div class="section">
<h2>✨ Experience</h2>
<div class="features">
<div class="feature">📸 Photo Spots</div>
<div class="feature">🛋️ Relax Areas</div>
<div class="feature">👥 Friends & Family</div>
<div class="feature">🎉 Events</div>
</div>
</div>

<div class="section">
<h2>📸 Gallery</h2>
<div class="gallery">
<img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93">
<img src="https://images.unsplash.com/photo-1521017432531-fbd92d768814">
<img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085">
</div>
</div>

<div class="section">
<h2>🎥 TikTok</h2>
<iframe src="https://www.tiktok.com/embed/@danbar.cafe" width="350" height="600"></iframe>
</div>

<div class="section cta">
<h2>📲 Book Now</h2>
<p>Dalbo ama Booqo maanta</p>
<a class="button" href="https://wa.me/252614019292">WhatsApp</a>
</div>

<div class="section">
<h2>📍 Location</h2>
<iframe src="https://maps.google.com/maps?q=baidoa%20somalia&t=&z=13&ie=UTF8&iwloc=&output=embed" width="100%" height="300"></iframe>
</div>

<div class="footer">
<p>© 2026 Danbar Cafe - Ultimate Experience</p>
</div>

</div>

<script>
// simple animation on scroll
const cards = document.querySelectorAll('.card, .feature');
window.addEventListener('scroll', () => {
  cards.forEach(c => {
    const top = c.getBoundingClientRect().top;
    if(top < window.innerHeight - 50){
      c.style.opacity = 1;
      c.style.transform = 'translateY(0)';
    }
  });
});
</script>

</body>
</html>



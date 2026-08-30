<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ATG Creative</title>
  <style>
    *{margin:0;padding:0;box-sizing:border-box}
    body{font-family:Arial,sans-serif;background:#050505;color:#fff;scroll-behavior:smooth}
    header{position:fixed;width:100%;top:0;background:rgba(0,0,0,.7);backdrop-filter:blur(12px);padding:18px 8%;display:flex;justify-content:space-between;align-items:center;z-index:1000}
    header h1{color:#D4AF37;font-size:26px}
    nav a{color:#fff;text-decoration:none;margin-left:18px;font-size:14px}
    nav a:hover{color:#D4AF37}

    .hero{height:100vh;background:linear-gradient(rgba(0,0,0,.75),rgba(0,0,0,.9)),url('images/hero.jpg') center/cover;display:flex;align-items:center;justify-content:center;text-align:center;padding:20px}
    .hero h2{font-size:56px;color:#D4AF37}
    .hero p{margin:20px auto;font-size:18px;max-width:650px;color:#ddd}
    .btn{display:inline-block;background:#D4AF37;color:#000;padding:14px 32px;border-radius:40px;text-decoration:none;font-weight:bold;transition:.3s}
    .btn:hover{transform:scale(1.05);box-shadow:0 0 20px #D4AF37}

    section{padding:90px 8%}
    h3.title{text-align:center;color:#D4AF37;font-size:36px;margin-bottom:50px}

    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:25px}
    .card{background:#111;border:1px solid #222;padding:30px;border-radius:20px;text-align:center;transition:.3s}
    .card:hover{transform:translateY(-8px);border-color:#D4AF37;box-shadow:0 0 20px rgba(212,175,55,.35)}
    .card h4{color:#D4AF37;margin:18px 0}

    .portfolio-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
    .item{background:#111;border-radius:18px;overflow:hidden;transition:.3s}
    .item img{width:100%;display:block}
    .item h4{padding:15px;color:#D4AF37}
    .item p{padding:0 15px 20px;color:#bbb;font-size:14px}
    .item:hover{transform:scale(1.03);box-shadow:0 0 20px rgba(212,175,55,.35)}

    .stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:20px;text-align:center}
    .stat{background:#111;padding:30px;border-radius:18px}
    .stat h2{color:#D4AF37;font-size:38px}

    .contact{text-align:center}
    .socials a{display:inline-block;margin:10px;padding:14px 24px;border:1px solid #D4AF37;border-radius:40px;color:#D4AF37;text-decoration:none;transition:.3s}
    .socials a:hover{background:#D4AF37;color:#000}

    footer{text-align:center;padding:30px;color:#888;border-top:1px solid #222}

    @media(max-width:700px){
      .hero h2{font-size:40px}
      nav{display:none}
    }
  </style>
</head>
<body>

<header>
  <h1>ATG CREATIVE</h1>
  <nav>
    <a href="#services">Hizmetler</a>
    <a href="#portfolio">Portfolyo</a>
    <a href="#about">Hakkımızda</a>
    <a href="#contact">İletişim</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h2>ATG CREATIVE</h2>
    <p>Premium sosyal medya tasarımları, video edit, logo ve marka kimliği çözümleri.</p>
    <a href="#portfolio" class="btn">Portfolyoyu İncele</a>
  </div>
</section>

<section id="services">
  <h3 class="title">Hizmetlerimiz</h3>
  <div class="services">
    <div class="card"><h4>Video Edit</h4><p>Reels, TikTok, YouTube Shorts ve reklam videoları.</p></div>
    <div class="card"><h4>Sosyal Medya Tasarımı</h4><p>Instagram, Facebook ve markalara özel içerikler.</p></div>
    <div class="card"><h4>Logo Tasarımı</h4><p>Minimal ve premium kurumsal logolar.</p></div>
    <div class="card"><h4>Kurumsal Kimlik</h4><p>Renk paleti, kartvizit ve marka dili.</p></div>
    <div class="card"><h4>Reklam Kreatifleri</h4><p>Ürün ve kampanya görselleri.</p></div>
    <div class="card"><h4>Thumbnail Tasarımı</h4><p>YouTube ve sosyal medya kapak görselleri.</p></div>
  </div>
</section>

<section id="portfolio">
  <h3 class="title">Portfolyo</h3>

  <div class="portfolio-grid">

    <div class="item">
      <img src="images/social1.jpg" alt="social1">
      <h4>Luxury Watch Campaign</h4>
      <p>Instagram Premium Tasarımı</p>
    </div>

    <div class="item">
      <img src="images/social2.jpg" alt="social2">
      <h4>Fitness Motivation</h4>
      <p>Sosyal Medya Postu</p>
    </div>

    <div class="item">
      <img src="images/social3.jpg" alt="social3">
      <h4>Coffee Branding</h4>
      <p>Marka Tanıtımı</p>
    </div>

    <div class="item">
      <img src="images/social4.jpg" alt="social4">
      <h4>Streetwear Collection</h4>
      <p>Moda Tasarımı</p>
    </div>

    <div class="item">
      <img src="images/social5.jpg" alt="social5">
      <h4>Luxury Perfume</h4>
      <p>Premium Reklam</p>
    </div>

    <div class="item">
      <img src="images/social6.jpg" alt="social6">
      <h4>Business Success</h4>
      <p>Kurumsal Tasarım</p>
    </div>

    <div class="item">
      <img src="images/logo1.png" alt="logo1">
      <h4>ATG Logo Concept</h4>
      <p>Minimal Logo Tasarımı</p>
    </div>

    <div class="item">
      <img src="images/logo2.png" alt="logo2">
      <h4>Luxury Brand Logo</h4>
      <p>Kurumsal Kimlik</p>
    </div>

    <div class="item">
      <img src="images/ad1.jpg" alt="ad1">
      <h4>Advertising Poster</h4>
      <p>Reklam Tasarımı</p>
    </div>

    <div class="item">
      <img src="images/ad2.jpg" alt="ad2">
      <h4>Product Promotion</h4>
      <p>Ürün Kampanyası</p>
    </div>

    <div class="item">
      <img src="images/video1.jpg" alt="video1">
      <h4>Cinematic Video Edit</h4>
      <p>Video Portfolyosu</p>
    </div>

    <div class="item">
      <img src="images/video2.jpg" alt="video2">
      <h4>Reels & Shorts</h4>
      <p>Video Edit Showcase</p>
    </div>

  </div>
</section>

<section id="about">
  <h3 class="title">ATG Creative Hakkında</h3>
  <p style="max-width:800px;margin:auto;text-align:center;color:#ccc;line-height:1.8">
    ATG Creative, sosyal medya tasarımı, video edit ve dijital marka kimliği üzerine kurulu premium bir kreatif stüdyodur.
    Modern tasarım anlayışıyla markalara dikkat çekici içerikler üretiyoruz.
  </p>
</section>

<section>
  <h3 class="title">Rakamlarla ATG</h3>
  <div class="stats">
    <div class="stat"><h2>150+</h2><p>Tasarım</p></div>
    <div class="stat"><h2>50+</h2><p>Video Edit</p></div>
    <div class="stat"><h2>30+</h2><p>Logo</p></div>
    <div class="stat"><h2>100%</h2><p>Premium Kalite</p></div>
  </div>
</section>

<section id="contact" class="contact">
  <h3 class="title">İletişim</h3>
  <p style="color:#bbb;margin-bottom:30px">Projeni birlikte hayata geçirelim.</p>

  <div class="socials">
    <a href="#">WhatsApp</a>
    <a href="#">Instagram</a>
    <a href="#">E-Mail</a>
  </div>
</section>

<footer>
  © 2026 ATG Creative — Premium Creative Studio
</footer>

<script>
const observer=new IntersectionObserver(entries=>{
 entries.forEach(e=>{
   if(e.isIntersecting){
     e.target.animate([
       {opacity:0,transform:'translateY(40px)'},
       {opacity:1,transform:'translateY(0)'}
     ],{duration:700,fill:'forwards'});
   }
 })
});

document.querySelectorAll('section,.card,.item,.stat').forEach(el=>observer.observe(el));
</script>

</body>
</html>

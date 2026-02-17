<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Rolos Band | La Escuela de la Salsa</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',sans-serif;}

body{
  background:#000814;
  color:white;
}

/* HERO */
.hero{
  position:relative;
  height:95vh;
  display:flex;
  align-items:center;
  justify-content:center;
  overflow:hidden;
}

.hero-bg{
  position:absolute;
  width:100%;
  height:100%;
  object-fit:cover;
  z-index:-2;
}

.hero-overlay{
  position:absolute;
  width:100%;
  height:100%;
  background:linear-gradient(120deg,rgba(0,0,0,.75),rgba(255,0,0,.4));
  z-index:-1;
}

.hero-content{
  text-align:center;
  padding:20px;
}

.hero-content h1{
  font-size:3em;
  color:#ffd700;
  text-shadow:0 0 20px gold;
}

.hero-content h2{
  font-size:4em;
  color:#00eaff;
  text-shadow:0 0 30px #00eaff;
}

.hero-content p{
  margin-top:15px;
  font-size:1.2em;
}

.hero-btn{
  margin-top:30px;
  display:inline-block;
  padding:18px 40px;
  background:linear-gradient(45deg,#ffd700,#ff2e2e);
  color:black;
  border-radius:40px;
  text-decoration:none;
  font-weight:bold;
  box-shadow:0 0 30px gold;
}

/* MENSAJE */
.mensaje{
  max-width:900px;
  margin:auto;
  padding:70px 20px;
  text-align:center;
  line-height:1.6;
}

.mensaje h2{
  color:#00eaff;
  font-size:2.2em;
  margin-bottom:20px;
}

/* CTA */
.cta{
  background:rgba(255,215,0,.12);
  padding:50px 20px;
  text-align:center;
  margin:40px auto;
  border-radius:20px;
  max-width:800px;
  box-shadow:0 0 30px gold;
}

.cta a{
  display:inline-block;
  margin-top:25px;
  padding:15px 40px;
  background:#00eaff;
  color:#000814;
  font-weight:bold;
  border-radius:30px;
  text-decoration:none;
}

/* CLASES */
.clases{
  padding:80px 20px;
  text-align:center;
}

.clases h2{
  color:#00eaff;
  font-size:2.5em;
  margin-bottom:50px;
}

.clases-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:30px;
  max-width:1200px;
  margin:auto;
}

.clase{
  background:rgba(0,255,255,.1);
  border-radius:20px;
  padding:25px;
  box-shadow:0 0 20px #00eaff;
  text-decoration:none;
  color:white;
  transition:.3s;
}

.clase:hover{
  transform:scale(1.05);
}

.clase img{
  width:120px;
  margin-bottom:15px;
  filter:drop-shadow(0 0 12px #00eaff);
}

/* FOOTER */
footer{
  text-align:center;
  padding:40px;
  background:#000814;
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <img class="hero-bg" src="https://i.imgur.com/A0HGX0u.png">
  <div class="hero-overlay"></div>

  <div class="hero-content">
    <h1>La Escuela de la Salsa</h1>
    <h2>ROLOS BAND</h2>
    <p>Conecta con tu ritmo, sana con la música</p>
    <a class="hero-btn" href="https://wa.me/573133231571">🎁 Clase de cortesía</a>
  </div>
</section>

<!-- MENSAJE -->
<section class="mensaje">
<h2>¿Estrés, depresión o ansiedad?</h2>
<p><strong>Dilo con la salsa y la percusión.</strong></p>
<p>En Rolos Band – La Escuela de la Salsa en Ciudad Verde, no solo enseñamos a tocar; construimos bienestar.</p>
<p>La percusión reduce el estrés y libera endorfinas.</p>
<p>Niños, adultos y abuelos encuentran aquí una terapia musical.</p>
<p><strong>📍 Ciudad Verde, Soacha<br>📲 313 323 1571</strong></p>
<p><em>“Porque un tambor que suena es un corazón que sana.”</em></p>
</section>

<!-- CTA -->
<div class="cta">
<h2>🎁 Tu primera clase es gratis</h2>
<p>Escríbenos ahora mismo y vive la experiencia Rolos Band.</p>
<a href="https://wa.me/573133231571">Hablar por WhatsApp</a>
</div>

<!-- CLASES -->
<section class="clases" id="clases">
<h2>Explora tus Clases</h2>

<div class="clases-grid">

<a class="clase" href="https://www.tiktok.com/@maoescobarysurolosband/video/7515589742797393158" target="_blank">
<img src="https://i.imgur.com/NHXm3y9.png"><h3>Conga</h3>
</a>

<a class="clase" href="https://www.tiktok.com/@maoescobarysurolosband/video/7192222000545271045" target="_blank">
<img src="https://i.imgur.com/Vi7jQ43.png"><h3>Timbal</h3>
</a>

<a class="clase" href="https://www.tiktok.com/@maoescobarysurolosband/video/7201627786195389701" target="_blank">
<img src="https://i.imgur.com/DnGDjho.png"><h3>Bongo</h3>
</a>

<a class="clase" href="https://www.youtube.com/watch?v=7ybvRwyTvYY" target="_blank">
<img src="https://i.imgur.com/iN3R95d.png"><h3>Piano</h3>
</a>

<a class="clase" href="https://www.youtube.com/watch?v=CR8ZbY6FQVM" target="_blank">
<img src="https://i.imgur.com/eFPNV4E.png"><h3>Canto</h3>
</a>

</div>
</section>

<footer>
© 2026 Rolos Band – La Escuela de la Salsa
</footer>

</body>
</html>

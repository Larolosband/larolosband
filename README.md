<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Rolos Band | La Escuela de la Salsa</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',sans-serif;}

body{
  background:radial-gradient(circle at top,#061a2e,#000814);
  color:white;
}

/* HERO */
.hero{
  background:linear-gradient(180deg,#000814,#061a2e);
  text-align:center;
  padding:60px 20px;
}

.hero img{
  width:160px;
  margin-bottom:20px;
  filter:drop-shadow(0 0 20px #00eaff);
}

.hero h1{
  font-size:3em;
  color:#00eaff;
  text-shadow:0 0 20px #00eaff;
}

.hero p{
  font-size:1.2em;
  margin-top:10px;
  color:#b0f7ff;
}

/* MENSAJE */
.mensaje{
  max-width:900px;
  margin:auto;
  padding:60px 20px;
  text-align:center;
  line-height:1.6;
}

.mensaje h2{
  color:#00eaff;
  font-size:2em;
  margin-bottom:20px;
}

.mensaje p{
  font-size:1.1em;
  margin-bottom:15px;
}

/* CTA */
.cta{
  background:rgba(0,255,255,0.08);
  padding:40px 20px;
  text-align:center;
  border-radius:20px;
  max-width:800px;
  margin:40px auto;
  box-shadow:0 0 30px rgba(0,255,255,0.3);
}

.cta h3{
  color:#00eaff;
  font-size:1.8em;
  margin-bottom:15px;
}

.cta a{
  display:inline-block;
  margin-top:20px;
  padding:15px 35px;
  background:#00eaff;
  color:#000814;
  font-weight:bold;
  border-radius:30px;
  text-decoration:none;
  font-size:1.1em;
  box-shadow:0 0 25px #00eaff;
  transition:.3s;
}

.cta a:hover{
  background:#0ff;
  box-shadow:0 0 40px #0ff;
}

/* CLASES */
.clases{
  padding:80px 20px;
  text-align:center;
}

.clases h2{
  font-size:2.5em;
  color:#00eaff;
  margin-bottom:50px;
  text-shadow:0 0 15px #00eaff;
}

.clases-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:30px;
  max-width:1200px;
  margin:auto;
}

.clase{
  background:rgba(0,255,255,0.08);
  border-radius:20px;
  padding:25px;
  box-shadow:0 0 25px rgba(0,255,255,0.3);
  transition:.4s;
  backdrop-filter:blur(10px);
}

.clase:hover{
  transform:translateY(-10px) scale(1.03);
  box-shadow:0 0 40px #00eaff;
}

.clase img{
  width:120px;
  margin-bottom:15px;
  filter:drop-shadow(0 0 12px #00eaff);
}

.clase h3{
  color:#00eaff;
  margin-bottom:10px;
}

/* FOOTER */
footer{
  text-align:center;
  padding:40px 20px;
  background:#000814;
  color:#b0f7ff;
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <img src="https://i.imgur.com/8C0YkqZ.png" alt="Rolos Band Logo">
  <h1>ROLOS BAND</h1>
  <p>La Escuela de la Salsa</p>
</section>

<!-- MENSAJE -->
<section class="mensaje">
  <h2>🥁 ¿Estrés, Depresión o Ansiedad?</h2>
  <p><strong>Dilo con la Salsa y la Percusión.</strong></p>

  <p>En <strong>La Escuela de la Salsa Rolos Band</strong>, ubicados en <strong>Ciudad Verde</strong>, no solo enseñamos a tocar; construimos bienestar.</p>

  <p>Tocar percusión reduce el cortisol (estrés) y libera endorfinas.</p>

  <p>✅ Niños: atención y disciplina<br>
     ✅ Adultos: el mejor escape del día<br>
     ✅ Abuelos: memoria y coordinación</p>

  <p>No necesitas instrumento propio. Solo ganas de conectar con tu ritmo.</p>

  <p><strong>📍 Ciudad Verde, Soacha</strong><br>
     <strong>📲 Info y Clase de cortesía: 313 323 1571</strong></p>

  <p><em>“Porque un tambor que suena es un corazón que sana.”</em></p>
</section>

<!-- CTA -->
<div class="cta">
  <h3>🎁 Toma tu Clase de Cortesía</h3>
  <p>Escríbenos ahora y vive tu primera experiencia salsera GRATIS.</p>
  <a href="https://wa.me/573133231571" target="_blank">Hablar por WhatsApp</a>
</div>

<!-- CLASES -->
<section class="clases">
  <h2>🎶 Explora tus Clases</h2>
  <div class="clases-grid">

    <div class="clase">
      <img src="https://i.imgur.com/NHXm3y9.png">
      <h3>Conga</h3>
      <p>El corazón rítmico de la salsa.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/Vi7jQ43.png">
      <h3>Timbal</h3>
      <p>La energía y los cortes.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/DnGDjho.png">
      <h3>Bongo</h3>
      <p>El pulso y la improvisación.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/iN3R95d.png">
      <h3>Piano</h3>
      <p>Montunos y armonía salsera.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/eFPNV4E.png">
      <h3>Canto</h3>
      <p>Tu voz como instrumento.</p>
    </div>

  </div>
</section>

<footer>
  © 2026 Rolos Band – La Escuela de la Salsa
</footer>

</body>
</html>

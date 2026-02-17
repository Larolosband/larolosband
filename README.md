<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Rolos Band | La Escuela de la Salsa</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
  font-family: 'Segoe UI', sans-serif;
}

body{
  background: radial-gradient(circle at top, #061a2e, #000814);
  color:white;
}

/* HEADER */
header{
  text-align:center;
  padding:50px 20px;
  background: linear-gradient(180deg, #000814, #061a2e);
}

header h1{
  font-size:3em;
  color:#00eaff;
  text-shadow:0 0 20px #00eaff;
}

header p{
  margin-top:15px;
  font-size:1.2em;
  color:#b0f7ff;
}

/* CLASES */
.clases{
  padding:80px 20px;
  text-align:center;
}

.clases h2{
  font-size:2.8em;
  color:#00eaff;
  margin-bottom:50px;
  text-shadow:0 0 15px #00eaff;
}

.clases-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(220px, 1fr));
  gap:30px;
  max-width:1200px;
  margin:auto;
}

.clase{
  background:rgba(0,255,255,0.08);
  border-radius:20px;
  padding:25px;
  box-shadow:0 0 25px rgba(0,255,255,0.3);
  transition:0.4s;
  backdrop-filter:blur(10px);
}

.clase:hover{
  transform:translateY(-12px) scale(1.03);
  box-shadow:0 0 40px #00eaff;
}

.clase img{
  width:120px;
  margin-bottom:15px;
  filter:drop-shadow(0 0 12px #00eaff);
}

.clase h3{
  color:#00eaff;
  font-size:1.5em;
  margin-bottom:10px;
}

.clase p{
  color:white;
  font-size:1em;
  line-height:1.4;
}

/* FOOTER */
footer{
  text-align:center;
  padding:40px;
  background:#000814;
  color:#00eaff;
}
</style>
</head>

<body>

<header>
  <h1>ROLOS BAND</h1>
  <p>La Escuela Digital de la Salsa</p>
</header>

<section class="clases">
  <h2>🎶 Explora tus clases</h2>

  <div class="clases-grid">

    <div class="clase">
      <img src="https://i.imgur.com/NHXm3y9.png">
      <h3>Conga</h3>
      <p>Domina el tumbao, los golpes abiertos y el corazón rítmico de la salsa.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/Vi7jQ43.png">
      <h3>Timbal</h3>
      <p>Aprende cortes, fills y la energía explosiva de la salsa moderna.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/DnGDjho.png">
      <h3>Bongo</h3>
      <p>Controla el martillo, acompañamientos y solos en salsa y latin jazz.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/iN3R95d.png">
      <h3>Piano</h3>
      <p>Montunos, armonía y acompañamiento profesional para salsa.</p>
    </div>

    <div class="clase">
      <img src="https://i.imgur.com/eFPNV4E.png">
      <h3>Canto</h3>
      <p>Entrena tu voz para coros, melodía y puesta en escena salsera.</p>
    </div>

  </div>
</section>

<footer>
  © 2026 Rolos Band – La Escuela de la Salsa
</footer>

</body>
</html>

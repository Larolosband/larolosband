<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>La Escuela de la Salsa – Rolos Band</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body{
    margin:0;
    font-family:'Segoe UI', sans-serif;
    background:linear-gradient(135deg,#ff0066,#ffcc00);
    color:white;
    text-align:center;
}

header{
    padding:40px 20px;
    background:url('https://i.imgur.com/A0HGX0u.png') center/cover no-repeat;
    position:relative;
}

header::after{
    content:"";
    position:absolute;
    inset:0;
    background:rgba(0,0,0,0.6);
}

header *{
    position:relative;
    z-index:1;
}

h1{
    font-size:42px;
    margin-bottom:10px;
}

h2{
    font-weight:300;
}

.section{
    padding:60px 20px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:30px;
    max-width:1000px;
    margin:auto;
}

.card{
    background:rgba(0,0,0,0.4);
    border-radius:20px;
    padding:20px;
    cursor:pointer;
    transition:0.3s;
}

.card:hover{
    transform:scale(1.05);
    background:rgba(0,0,0,0.6);
}

.card img{
    width:100px;
    margin-bottom:15px;
}

iframe{
    width:100%;
    max-width:600px;
    height:340px;
    border:none;
    border-radius:20px;
    margin-top:20px;
}

footer{
    padding:20px;
    background:black;
}
</style>
</head>

<body>

<header>
    <h1>La Escuela de la Salsa</h1>
    <h2>Rolos Band</h2>
</header>

<div class="section" id="clases">
    <h2>Explora tus Clases</h2>

    <div class="grid">

        <div class="card" onclick="mostrar('https://www.tiktok.com/embed/7515589742797393158')">
            <img src="https://i.imgur.com/NHXm3y9.png">
            <h3>Conga</h3>
        </div>

        <div class="card" onclick="mostrar('https://www.tiktok.com/embed/7192222000545271045')">
            <img src="https://i.imgur.com/Vi7jQ43.png">
            <h3>Timbal</h3>
        </div>

        <div class="card" onclick="mostrar('https://www.tiktok.com/embed/7201627786195389701')">
            <img src="https://i.imgur.com/DnGDjho.png">
            <h3>Bongo</h3>
        </div>

        <div class="card" onclick="mostrar('https://www.youtube.com/embed/CR8ZbY6FQVM')">
            <img src="https://i.imgur.com/eFPNV4E.png">
            <h3>Canto</h3>
        </div>

        <div class="card" onclick="mostrar('https://www.youtube.com/embed/7ybvRwyTvYY')">
            <img src="https://i.imgur.com/iN3R95d.png">
            <h3>Piano</h3>
        </div>

    </div>

    <div id="video"></div>

</div>

<footer>
    © Rolos Band – La Escuela de la Salsa
</footer>

<script>
function mostrar(url){
    document.getElementById("video").innerHTML =
    `<iframe src="${url}" allowfullscreen></iframe>`;
    window.scrollTo({top:document.getElementById("video").offsetTop-50, behavior:"smooth"});
}
</script>

</body>
</html>

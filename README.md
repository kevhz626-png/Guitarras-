<!KORDOGUITARS html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KordoGuitars</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}
html, body{
    width:100%;
    overflow-x:hidden;
}
body{
    background:#0f0f0f;
    color:white;
    line-height:1.7;
}

header{
    background:#000;
    padding:20px;
    border-bottom:2px solid #ff9800;
    position:sticky;
    top:0;
    z-index:1000;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:#ff9800;
    font-size:32px;
    font-weight:bold;
}

nav ul{
    display:flex;
    list-style:none;
    gap:20px;
}

nav a{
    color:white;
    text-decoration:none;
    transition:0.3s;
}

nav a:hover{
    color:#ff9800;
}

.hero{
    height:90vh;
    background:url('https://images.unsplash.com/photo-1510915361894-db8b60106cb1?q=80&w=1600&auto=format&fit=crop') center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
}

.hero-content{
    background:rgba(0,0,0,0.7);
    padding:40px;
    border-radius:20px;
    width:100%;
    max-width:100%;
}
}

.hero-content h1{
    color:#ff9800;
    font-size:60px;
    margin-bottom:20px;
}

.hero-content p{
    font-size:22px;
}

section{
    padding:70px 5%;
}

.section-title{
    text-align:center;
    color:#ff9800;
    font-size:40px;
    margin-bottom:45px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:30px;
}

.card{
    background:#1a1a1a;
    border-radius:20px;
    overflow:hidden;
    transition:0.3s;
    border:1px solid #2f2f2f;
}

.card:hover{
    transform:translateY(-8px);
    box-shadow:0 0 20px rgba(255,152,0,0.4);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card-content{
    padding:20px;
}

.card-content h3{
    color:#ff9800;
    margin-bottom:10px;
}

.info-box{
    background:#1a1a1a;
    padding:30px;
    border-radius:20px;
    margin-bottom:30px;
    border-left:5px solid #ff9800;
}

.info-box h3{
    color:#ff9800;
    margin-bottom:15px;
}

.timeline{
    display:grid;
    gap:25px;
}

.step{
    background:#1b1b1b;
    padding:25px;
    border-radius:15px;
    border-left:4px solid #ff9800;
}

.step h4{
    color:#ff9800;
    margin-bottom:10px;
}

footer{
    background:#000;
    text-align:center;
    padding:25px;
    border-top:2px solid #ff9800;
}

footer p{
    color:#bbb;
}

</style>
</head>

<body>

<header>

<nav>

<div class="logo">🎸 KordoGuitars</div>

<ul>
<li><a href="#vendidas">Más famosas</a></li>
<li><a href="#fabricacion">Fabricación</a></li>
<li><a href="#aprender">Aprender</a></li>
<li><a href="#datos">Curiosidades</a></li>
</ul>

</nav>

</header>

<section class="hero">

<div class="hero-content">

<h1>Docerolas</h1>

<p>
Descubre el universo de las guitarras de doce cuerdas:
su sonido brillante, su construcción y por qué son tan especiales.
</p>

</div>

</section>

<section id="vendidas">

<h2 class="section-title">🎶 Docerolas Más Conocidas</h2>

<div class="cards">

<div class="card">

<img src="https://images.unsplash.com/photo-1516280440614-37939bbacd81?q=80&w=1200&auto=format&fit=crop">

<div class="card-content">

<h3>Takamine Legacy 12</h3>

<p>
Reconocida por su sonido profundo y brillante.
Muy usada en música acústica y regional.
</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1525201548942-d8732f6617a0?q=80&w=1200&auto=format&fit=crop">

<div class="card-content">

<h3>Yamaha FG820-12</h3>

<p>
Popular entre principiantes y músicos intermedios por su comodidad y calidad.
</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1511379938547-c1f69419868d?q=80&w=1200&auto=format&fit=crop">

<div class="card-content">

<h3>Guild F-2512E</h3>

<p>
Una docerola famosa por su volumen potente y resonancia espectacular.
</p>

</div>

</div>

</div>

</section>

<section id="fabricacion">

<h2 class="section-title">🛠️ ¿Cómo se hacen las docerolas?</h2>

<div class="timeline">

<div class="step">

<h4>1. Selección de madera</h4>

<p>
Las docerolas usan maderas resistentes para soportar la tensión extra de las 12 cuerdas.
</p>

</div>

<div class="step">

<h4>2. Construcción reforzada</h4>

<p>
El cuerpo y el mástil llevan refuerzos especiales para evitar deformaciones.
</p>

</div>

<div class="step">

<h4>3. Instalación del puente y clavijas</h4>

<p>
Se colocan doce clavijas y un puente preparado para soportar mayor presión.
</p>

</div>

<div class="step">

<h4>4. Acabado y pintura</h4>

<p>
La guitarra se pinta y barniza cuidadosamente para proteger la madera.
</p>

</div>

<div class="step">

<h4>5. Ajustes finales</h4>

<p>
Se colocan las doce cuerdas y se calibra el instrumento para lograr un sonido equilibrado.
</p>

</div>

</div>

</section>

<section id="aprender">

<h2 class="section-title">📚 ¿Es difícil aprender docerola?</h2>

<div class="info-box">

<h3>Más desafiante que una guitarra normal 🎵</h3>

<p>
Las docerolas requieren más fuerza en los dedos debido a la tensión y cantidad de cuerdas.
</p>

</div>

<div class="info-box">

<h3>¿Qué cambia?</h3>

<p>
Los acordes suenan más llenos y brillantes, pero el mástil suele sentirse más ancho.
</p>

</div>

<div class="info-box">

<h3>¿Vale la pena?</h3>

<p>
Sí. Su sonido tiene una textura única que hace que cualquier canción se escuche enorme y envolvente.
</p>

</div>

</section>

<section id="datos">

<h2 class="section-title">🌟 Curiosidades sobre las docerolas</h2>

<div class="cards">

<div class="card">

<img src="https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f?q=80&w=1200&auto=format&fit=crop">

<div class="card-content">

<h3>12 cuerdas, 6 pares</h3>

<p>
Las cuerdas están agrupadas en pares para crear un efecto más brillante y amplio.
</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1511192336575-5a79af67a629?q=80&w=1200&auto=format&fit=crop">

<div class="card-content">

<h3>Sonido característico</h3>

<p>
El sonido de una docerola suele sentirse más grande y resonante que una guitarra común.
</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1507838153414-b4b713384a76?q=80&w=1200&auto=format&fit=crop">

<div class="card-content">

<h3>Muy usadas en baladas</h3>

<p>
Muchas canciones acústicas famosas usan docerolas para dar profundidad al sonido.
</p>

</div>

</div>

</div>

</section>

<footer>

<p>
🎸 KordoGuitars | Especialistas en docerolas | 2026
</p>

</footer>

</body>
</html>

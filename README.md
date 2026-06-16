<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tecnologia no Mar: Inovação que Navega</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
scroll-behavior:smooth;
}

body{
background:linear-gradient(180deg,#001f3f,#003f7f,#0077b6);
color:white;
}

header{
background:rgba(0,0,0,0.3);
padding:15px;
position:sticky;
top:0;
backdrop-filter:blur(10px);
z-index:1000;
}

nav{
display:flex;
justify-content:center;
gap:25px;
}

nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:90vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
padding:20px;
background:url('https://images.unsplash.com/photo-1500375592092-40eb2168fd21?auto=format&fit=crop&w=1400&q=80');
background-size:cover;
background-position:center;
}

.hero-content{
background:rgba(0,0,0,0.55);
padding:30px;
border-radius:20px;
max-width:700px;
}

.hero h1{
font-size:3rem;
margin-bottom:15px;
}

.hero p{
font-size:1.2rem;
}

section{
padding:60px 10%;
}

h2{
text-align:center;
margin-bottom:30px;
font-size:2rem;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:rgba(255,255,255,0.1);
padding:20px;
border-radius:20px;
backdrop-filter:blur(8px);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

.galeria{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
}

.galeria img{
width:100%;
height:220px;
object-fit:cover;
border-radius:15px;
}

.curiosidade{
background:#00b4d8;
padding:20px;
border-radius:15px;
margin-bottom:15px;
}

.quiz{
max-width:700px;
margin:auto;
background:rgba(255,255,255,0.1);
padding:25px;
border-radius:20px;
}

button{
background:#00d4ff;
border:none;
padding:12px 20px;
border-radius:10px;
font-weight:bold;
cursor:pointer;
margin-top:15px;
}

footer{
text-align:center;
padding:30px;
background:rgba(0,0,0,0.3);
}
</style>
</head>

<body>

<header>
<nav>
<a href="#inicio">Início</a>
<a href="#tecnologias">Tecnologias</a>
<a href="#galeria">Galeria</a>
<a href="#curiosidades">Curiosidades</a>
<a href="#quiz">Quiz</a>
</nav>
</header>

<section class="hero" id="inicio">
<div class="hero-content">
<h1>🌊 Tecnologia no Mar: Inovação que Navega</h1>
<p>
Descubra como robôs submarinos, satélites, drones e navios inteligentes
estão transformando a exploração e a proteção dos oceanos.
</p>
</div>
</section>

<section id="tecnologias">
<h2>🤖 Tecnologias Marítimas</h2>

<div class="cards">

<div class="card">
<h3>Robôs Submarinos</h3>
<p>
Exploram grandes profundidades e ajudam cientistas a estudar áreas
que seriam difíceis para humanos alcançarem.
</p>
</div>

<div class="card">
<h3>Satélites</h3>
<p>
Monitoram os oceanos, o clima e ajudam na previsão de tempestades.
</p>
</div>

<div class="card">
<h3>Drones Marítimos</h3>
<p>
Coletam informações sobre a qualidade da água e a vida marinha.
</p>
</div>

<div class="card">
<h3>Energia Eólica Offshore</h3>
<p>
Produz energia limpa utilizando a força dos ventos no mar.
</p>
</div>

</div>
</section>

<section id="galeria">
<h2>🖼️ Galeria Tecnológica</h2>

<div class="galeria">

<img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b?auto=format&fit=crop&w=800&q=80">

<img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80">

<img src="https://images.unsplash.com/photo-1493558103817-58b2924bce98?auto=format&fit=crop&w=800&q=80">

<img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21?auto=format&fit=crop&w=800&q=80">

</div>
</section>

<section id="curiosidades">
<h2>💡 Curiosidades</h2>

<div class="curiosidade">
🌍 Mais de 70% da superfície terrestre é coberta por oceanos.
</div>

<div class="curiosidade">
🤖 Alguns robôs submarinos conseguem trabalhar por meses sem retornar à superfície.
</div>

<div class="curiosidade">
🛰️ Satélites ajudam a monitorar mudanças climáticas e correntes marítimas.
</div>

</section>

<section id="quiz">
<h2>❓ Quiz Interativo</h2>

<div class="quiz">

<p><b>1. Qual tecnologia é usada para explorar grandes profundidades?</b></p>

<input type="radio" name="q1" value="0"> Bicicleta<br>
<input type="radio" name="q1" value="1"> Robô Submarino<br>
<input type="radio" name="q1" value="0"> Patins<br><br>

<p><b>2. O que os satélites ajudam a monitorar?</b></p>

<input type="radio" name="q2" value="1"> Oceanos e clima<br>
<input type="radio" name="q2" value="0"> Apenas estradas<br>
<input type="radio" name="q2" value="0"> Apenas prédios<br><br>

<button onclick="corrigir()">Ver Resultado</button>

<h3 id="resultado"></h3>

</div>
</section>

<footer>
🌊 Projeto Educativo - Tecnologia no Mar: Inovação que Navega
</footer>

<script>
function corrigir(){

let pontos = 0;

let q1 = document.querySelector('input[name="q1"]:checked');
let q2 = document.querySelector('input[name="q2"]:checked');

if(!q1 || !q2){
document.getElementById("resultado").innerHTML =
"Responda todas as perguntas!";
return;
}

pontos += Number(q1.value);
pontos += Number(q2.value);

document.getElementById("resultado").innerHTML =
"Você fez " + pontos + " de 2 pontos! 🎉";
}
</script>

</body>
</html>
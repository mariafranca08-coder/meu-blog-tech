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
<p>Exploram grandes profundidades e ajudam cientistas.</p>
</div>

<div class="card">
<h3>Satélites</h3>
<p>Monitoram oceanos, clima e tempestades.</p>
</div>

<div class="card">
<h3>Drones Marítimos</h3>
<p>Coletam dados da água e da vida marinha.</p>
</div>

<div class="card">
<h3>Energia Eólica Offshore</h3>
<p>Produz energia limpa com ventos do mar.</p>
</div>

</div>
</section>

<section id="galeria">
<h2>🖼️ Galeria de Fotos</h2>

<div class="galeria">

<img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b?auto=format&fit=crop&w=800&q=80">

<img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=800&q=80">

<img src="https://images.unsplash.com/photo-1493558103817-58b2924bce98?auto=format&fit=crop&w=800&q=80">

<img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21?auto=format&fit=crop&w=800&q=80">

</div>
</section>

<section id="curiosidades">
<h2>💡 Curiosidades</h2>

<div class="curiosidade">🌍 Mais de 70% do planeta é coberto por oceanos.</div>
<div class="curiosidade">🤖 Robôs submarinos funcionam por meses sem parar.</div>
<div class="curiosidade">🛰️ Satélites ajudam a prever o clima global.</div>

</section>

<section id="quiz">
<h2>❓ Quiz Interativo</h2>

<div class="quiz">

<p><b>1. Qual tecnologia explora grandes profundidades?</b></p>
<input type="radio" name="q1" value="0"> Bicicleta<br>
<input type="radio" name="q1" value="1"> Robô Submarino<br>
<input type="radio" name="q1" value="0"> Skate<br><br>

<p><b>2. O que satélites monitoram?</b></p>
<input type="radio" name="q2" value="1"> Oceanos e clima<br>
<input type="radio" name="q2" value="0"> Apenas ruas<br>
<input type="radio" name="q2" value="0"> Apenas prédios<br><br>

<p><b>3. Qual coleta dados no mar?</b></p>
<input type="radio" name="q3" value="1"> Drone Marítimo<br>
<input type="radio" name="q3" value="0"> Carro<br>
<input type="radio" name="q3" value="0"> Bicicleta<br><br>

<p><b>4. Energia eólica offshore usa:</b></p>
<input type="radio" name="q4" value="1"> Ventos do mar<br>
<input type="radio" name="q4" value="0"> Gasolina<br>
<input type="radio" name="q4" value="0"> Carvão<br><br>

<p><b>5. Benefício da tecnologia no mar:</b></p>
<input type="radio" name="q5" value="1"> Proteger oceanos<br>
<input type="radio" name="q5" value="0"> Poluir mais<br>
<input type="radio" name="q5" value="0"> Parar pesquisas<br><br>

<p><b>6. Robôs submarinos ajudam a:</b></p>
<input type="radio" name="q6" value="1"> Explorar oceanos profundos<br>
<input type="radio" name="q6" value="0"> Construir casas<br>
<input type="radio" name="q6" value="0"> Plantar árvores<br><br>

<button onclick="corrigir()">Ver Resultado</button>

<h3 id="resultado"></h3>

</div>
</section>

<footer>
🌊 Projeto Educativo - Tecnologia no Mar
</footer>

<script>
function corrigir(){
let pontos = 0;

for(let i = 1; i <= 6; i++){
let resposta = document.querySelector('input[name="q'+i+'"]:checked');

if(!resposta){
document.getElementById("resultado").innerHTML =
"Responda todas as perguntas!";
return;
}

pontos += Number(resposta.value);
}

document.getElementById("resultado").innerHTML =
"Você fez " + pontos + " de 6 pontos! 🎉";
}
</script>

</body>
</html>
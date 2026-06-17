<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Oceano Inteligente</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:linear-gradient(180deg,#001f3f,#003f7f,#0077b6);
color:white;
transition:0.4s;
}

body.dark{
background:#0b0b0b;
color:#eaeaea;
}

header{
background:rgba(0,0,0,0.4);
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
flex-wrap:wrap;
}

nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

.lua-btn{
position:fixed;
top:20px;
right:20px;
width:55px;
height:55px;
border-radius:50%;
border:none;
cursor:pointer;
font-size:22px;
background:#111;
color:white;
z-index:2000;
}

.top-title{
text-align:center;
padding:20px;
background:#00152d;
}

.top-title h1{
color:#00d4ff;
font-size:2.2rem;
text-shadow:0 0 10px #00d4ff;
}

.search-box{
text-align:center;
padding:15px;
}

#pesquisa{
padding:10px 15px;
width:300px;
max-width:90%;
border:none;
border-radius:20px;
outline:none;
}

.posts{
padding:50px 10%;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.post{
background:rgba(255,255,255,0.1);
border-radius:15px;
overflow:hidden;
backdrop-filter:blur(8px);
transition:0.3s;
}

body.dark .post{
background:#1a1a1a;
}

.post img{
width:100%;
height:200px;
object-fit:cover;
}

.post-content{
padding:15px;
}

.actions{
display:flex;
justify-content:space-between;
margin-top:10px;
}

button{
padding:8px 12px;
border:none;
border-radius:10px;
cursor:pointer;
}

.like{background:#00d4ff;}
.dislike{background:#ff4d4d;}

.hidden{
display:none !important;
}

footer{
text-align:center;
padding:30px;
background:rgba(0,0,0,0.3);
margin-top:40px;
}

</style>
</head>

<body>

<button class="lua-btn" onclick="toggleTema()">🌙</button>

<header>
<nav>
<a href="#inicio">Início</a>
<a href="#posts">Posts</a>
</nav>
</header>

<div class="top-title">
<h1>🌊 Oceano Inteligente</h1>
<p>Tecnologia e inovação nos oceanos</p>
</div>

<div class="search-box">
<input type="text" id="pesquisa" placeholder="Pesquisar posts...">
</div>

<section class="posts" id="posts">

<!-- 1 -->
<div class="post">
<img src="https://images.unsplash.com/photo-1582967788606-a171c1080cb0?auto=format&fit=crop&w=800&q=80">
<div class="post-content">
<h3>🤖 Robôs Submarinos</h3>
<p>
Os robôs submarinos são equipamentos desenvolvidos para explorar regiões profundas do oceano onde a presença humana não é possível devido à pressão extrema e à ausência de luz natural. Eles são equipados com câmeras, sensores avançados e sistemas de coleta de dados que permitem analisar o ambiente marinho com precisão.
<br><br>
Essas tecnologias são utilizadas em pesquisas científicas, exploração de recursos naturais e estudos sobre ecossistemas marinhos ainda pouco conhecidos.
</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<!-- 2 -->
<div class="post">
<img src="https://images.unsplash.com/photo-1559827260-dc66d52bef19?auto=format&fit=crop&w=800&q=80">
<div class="post-content">
<h3>🛰️ Satélites Oceânicos</h3>
<p>
Satélites em órbita da Terra desempenham um papel fundamental no monitoramento dos oceanos. Eles coletam informações sobre temperatura da superfície, correntes marítimas e padrões climáticos em escala global.
<br><br>
Esses dados são essenciais para previsões meteorológicas, estudos ambientais e prevenção de desastres naturais, como tempestades e furacões.
</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<!-- 3 -->
<div class="post">
<img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21?auto=format&fit=crop&w=800&q=80">
<div class="post-content">
<h3>🌊 Sensores Marinhos</h3>
<p>
Sensores instalados no oceano são utilizados para coletar dados ambientais como temperatura, salinidade, nível de poluição e movimentação das águas. Esses equipamentos funcionam de forma contínua e enviam informações em tempo real para centros de pesquisa.
<br><br>
Essas medições ajudam cientistas a entender melhor a saúde dos oceanos e seus impactos no clima global.
</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<!-- 4 -->
<div class="post">
<img src="https://images.unsplash.com/photo-1567899378494-47b22a2ae96a?auto=format&fit=crop&w=800&q=80">
<div class="post-content">
<h3>🚢 Navios Inteligentes</h3>
<p>
Navios modernos utilizam sistemas de inteligência artificial para otimizar rotas, aumentar a segurança e reduzir o consumo de combustível. Esses sistemas analisam dados em tempo real para evitar acidentes e melhorar a eficiência da navegação.
<br><br>
A automação no transporte marítimo representa um avanço importante para a logística global e para a segurança no mar.
</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<!-- 5 -->
<div class="post">
<img src="https://images.unsplash.com/photo-1504198453319-5ce911bafcde?auto=format&fit=crop&w=800&q=80">
<div class="post-content">
<h3>🔋 Energia das Ondas</h3>
<p>
A energia das ondas é uma forma de energia renovável que aproveita o movimento natural do mar para gerar eletricidade. Essa tecnologia utiliza estruturas instaladas no oceano para converter o movimento das ondas em energia elétrica.
<br><br>
Esse tipo de fonte energética é estudado como alternativa sustentável para reduzir a dependência de combustíveis fósseis.
</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

</section>

<footer>
🌊 Oceano Inteligente
</footer>

<script>

function toggleTema(){
document.body.classList.toggle("dark");
}

function like(btn){
let span = btn.querySelector("span");
span.innerText = Number(span.innerText) + 1;
}

function dislike(btn){
let span = btn.querySelector("span");
span.innerText = Number(span.innerText) + 1;
}

document.getElementById("pesquisa").addEventListener("input", function(){

let texto = this.value.toLowerCase();

document.querySelectorAll(".post").forEach(post=>{
post.classList.toggle(
"hidden",
!post.innerText.toLowerCase().includes(texto)
);
});

});

</script>

</body>
</html>

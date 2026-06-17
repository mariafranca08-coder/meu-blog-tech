<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Ocean Tech Blog</title>

<style>

/* ===== BASE ===== */
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

/* ===== MODO ESCURO ===== */
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

.top-blog{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
flex-wrap:wrap;
gap:15px;
background:#00152d;
}

#pesquisa{
padding:10px 15px;
border-radius:20px;
border:none;
width:250px;
}

/* ===== BOTÃO LUA ===== */
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
box-shadow:0 0 10px rgba(255,255,255,0.3);
z-index:2000;
}

/* ===== POSTS ===== */
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

.post h3{
margin-bottom:10px;
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

/* ===== HERO ===== */
.hero{
padding:80px 10%;
text-align:center;
}

/* ===== FOOTER ===== */
footer{
text-align:center;
padding:30px;
background:rgba(0,0,0,0.3);
margin-top:40px;
}

</style>
</head>

<body>

<!-- BOTÃO LUA -->
<button class="lua-btn" onclick="toggleTema()">🌙</button>

<header>
<nav>
<a href="#">Início</a>
<a href="#posts">Posts</a>
</nav>
</header>

<div class="top-blog">
<div>
<h1>🌊 Ocean Tech Blog</h1>
<p>Tecnologia e inovação nos oceanos</p>
</div>

<input type="text" id="pesquisa" placeholder="Pesquisar posts...">
</div>

<section class="hero">
<h1>Tecnologia no Mar 🌊</h1>
<p>Robôs submarinos, IA oceânica, sensores e exploração dos oceanos</p>
</section>

<!-- POSTS -->
<section class="posts" id="posts">

<div class="post">
<img src="pexels-mehmetography-2153058108-33299503.jpg">
<div class="post-content">
<h3>🤖 Robôs Submarinos</h3>
<p>Exploram as profundezas do oceano onde humanos não conseguem chegar.</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<div class="post">
<img src="pexels-mehmetography-2153058108-33299503.jpg">
<div class="post-content">
<h3>🛰️ Satélites Oceânicos</h3>
<p>Monitoram correntes marítimas, clima e mudanças no oceano.</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<div class="post">
<img src="pexels-mehmetography-2153058108-33299503.jpg">
<div class="post-content">
<h3>🌊 Sensores Submarinos</h3>
<p>Captam dados da água como temperatura e poluição.</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<div class="post">
<img src="pexels-mehmetography-2153058108-33299503.jpg">
<div class="post-content">
<h3>🚢 Navios Inteligentes</h3>
<p>Usam inteligência artificial para navegação mais segura.</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

<div class="post">
<img src="pexels-mehmetography-2153058108-33299503.jpg">
<div class="post-content">
<h3>🔋 Energia das Ondas</h3>
<p>Transforma o movimento do mar em energia limpa e renovável.</p>
<div class="actions">
<button class="like" onclick="like(this)">👍 <span>0</span></button>
<button class="dislike" onclick="dislike(this)">👎 <span>0</span></button>
</div>
</div>
</div>

</section>

<footer>
🌊 Ocean Tech Blog - Tecnologia no Mar
</footer>

<script>

/* ===== TEMA LUA ===== */
function toggleTema(){
document.body.classList.toggle("dark");
}

/* ===== LIKE ===== */
function like(btn){
let span = btn.querySelector("span");
span.innerText = Number(span.innerText) + 1;
}

/* ===== DISLIKE ===== */
function dislike(btn){
let span = btn.querySelector("span");
span.innerText = Number(span.innerText) + 1;
}

/* ===== PESQUISA ===== */
document.getElementById("pesquisa").addEventListener("keyup", function(){
let texto = this.value.toLowerCase();

document.querySelectorAll(".post").forEach(post=>{
post.style.display =
post.innerText.toLowerCase().includes(texto)
? "block"
: "none";
});
});

</script>

</body>
</html>
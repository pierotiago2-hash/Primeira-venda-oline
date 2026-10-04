<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Primeira Venda Online</title>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

body{
  font-family:Arial, sans-serif;
  background:#f4f6f9;
  color:#222;
  line-height:1.6;
}

header{
  background:linear-gradient(135deg,#111827,#2563eb);
  color:white;
  padding:45px 20px;
  text-align:center;
}

header h1{
  font-size:38px;
  margin-bottom:10px;
}

header p{
  font-size:18px;
  max-width:700px;
  margin:auto;
}

.btn{
  display:inline-block;
  margin-top:25px;
  padding:14px 25px;
  background:#22c55e;
  color:white;
  text-decoration:none;
  border-radius:10px;
  font-weight:bold;
  border:none;
  cursor:pointer;
  font-size:16px;
}

.btn:hover{
  transform:scale(1.03);
}

nav{
  background:white;
  padding:15px;
  text-align:center;
  position:sticky;
  top:0;
  z-index:10;
  box-shadow:0 2px 8px #0001;
}

nav a{
  color:#2563eb;
  text-decoration:none;
  margin:5px 10px;
  font-weight:bold;
}

.container{
  max-width:900px;
  margin:auto;
  padding:25px 15px;
}

.card{
  background:white;
  padding:25px;
  margin:20px 0;
  border-radius:15px;
  box-shadow:0 4px 15px #00000012;
}

h2{
  color:#2563eb;
  margin-bottom:15px;
}

h3{
  margin-top:20px;
  margin-bottom:8px;
}

ul{
  margin:15px 0 15px 25px;
}

li{
  margin:7px 0;
}

.destaque{
  background:#eff6ff;
  border-left:5px solid #2563eb;
  padding:18px;
  margin:20px 0;
  border-radius:8px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:15px;
  margin-top:20px;
}

.box{
  padding:20px;
  background:#f8fafc;
  border-radius:12px;
  border:1px solid #e5e7eb;
}

.checklist label{
  display:block;
  padding:12px;
  margin:8px 0;
  background:#f8fafc;
  border-radius:8px;
  cursor:pointer;
}

.checklist input{
  margin-right:10px;
  transform:scale(1.2);
}

.progress{
  height:12px;
  background:#ddd;
  border-radius:20px;
  overflow:hidden;
  margin:15px 0;
}

#barra{
  width:0%;
  height:100%;
  background:#22c55e;
  transition:.3s;
}

textarea{
  width:100%;
  min-height:120px;
  padding:15px;
  border:1px solid #ddd;
  border-radius:10px;
  font-size:16px;
  margin-top:10px;
}

footer{
  background:#111827;
  color:white;
  text-align:center;
  padding:35px 20px;
  margin-top:40px;
}

@media(max-width:600px){
  header h1{
    font-size:30px;
  }

  nav a{
    display:inline-block;
    font-size:14px;
  }

  .card{
    padding:20px;
  }
}
</style>
</head>

<body>

<header id="inicio">

<h1>PRIMEIRA VENDA ONLINE</h1>

<p>
Um guia prático para começar do zero, criar uma oferta,
divulgar seu produto e entender o processo de vendas online.
</p>

<a href="#comece" class="btn">COMEÇAR AGORA</a>

</header>

<nav>
<a href="#inicio">Início</a>
<a href="#conteudo">Conteúdo</a>
<a href="#plano">7 Dias</a>
<a href="#checklist">Checklist</a>
</nav>

<main class="container">

<section class="card" id="comece">

<h2>🚀 Antes de começar</h2>

<p>
Fazer uma venda pela internet não significa encontrar uma fórmula mágica.
Você precisa aprender o processo, testar sua ideia e melhorar com o tempo.
</p>

<div class="destaque">
<strong>Produto + Pessoas interessadas + Divulgação</strong>
<br><br>
Seu primeiro objetivo é aprender o processo de forma correta.
</div>

</section>

<section id="conteudo">

<div class="card">
<h2>1. Escolhendo o que vender</h2>

<p>Algumas opções de produtos digitais:</p>

<ul>
<li>E-books</li>
<li>Cursos</li>
<li>Apostilas</li>
<li>Templates</li>
<li>Checklists</li>
<li>Planilhas</li>
<li>Guias</li>
<li>Materiais de estudo</li>
</ul>

<div class="destaque">
<strong>Exemplo:</strong><br>
❌ Curso sobre internet<br>
✅ Guia para criar seu primeiro site pelo celular
</div>
</div>

<div class="card">
<h2>2. Definindo seu público</h2>

<p>Antes de criar seu produto, descubra quem precisa dele.</p>

<ul>
<li>Qual problema essa pessoa possui?</li>
<li>O que ela gostaria de aprender?</li>
<li>O que está dificultando seu objetivo?</li>
<li>Que tipo de conteúdo procura?</li>
</ul>

<div class="destaque">
<strong>Exemplo:</strong><br>
Público: iniciantes interessados em produtos digitais.<br>
Problema: não sabem por onde começar.<br>
Objetivo: aprender um processo simples.
</div>
</div>

<div class="card">
<h2>3. Criando uma oferta</h2>

<p>Uma boa oferta precisa explicar:</p>

<ul>
<li>O que é?</li>
<li>Para quem é?</li>
<li>Qual problema ajuda a resolver?</li>
<li>O que a pessoa recebe?</li>
</ul>

<div class="destaque">
Evite promessas de dinheiro garantido.
Mostre claramente o que existe dentro do produto.
</div>
</div>

<div class="card">
<h2>4. Criando seu produto digital</h2>

<div class="grid">

<div class="box">
<h3>📕 Capa</h3>
<p>Nome do produto e imagem relacionada.</p>
</div>

<div class="box">
<h3>📖 Introdução</h3>
<p>Explique o que o leitor vai aprender.</p>
</div>

<div class="box">
<h3>📚 Capítulos</h3>
<p>Organize o conteúdo em partes.</p>
</div>

<div class="box">
<h3>✅ Checklist</h3>
<p>Ajude o leitor a colocar em prática.</p>
</div>

</div>
</div>

<div class="card">
<h2>5. Página de vendas</h2>

<h3>Aprenda o processo para começar sua primeira venda online</h3>

<p>
Um guia para quem está começando e quer entender como criar
uma oferta, divulgar um produto e organizar seu processo.
</p>

<h3>Você vai aprender:</h3>

<ul>
<li>✓ Como escolher um produto</li>
<li>✓ Como definir seu público</li>
<li>✓ Como criar uma oferta</li>
<li>✓ Como divulgar</li>
<li>✓ Como criar conteúdos</li>
<li>✓ Como organizar suas primeiras vendas</li>
</ul>

<a href="#oferta" class="btn">QUERO CONHECER O GUIA</a>

</div>

<div class="card">
<h2>6. Recebendo pagamentos</h2>

<p>
Escolha uma plataforma de venda adequada ao seu produto.
Antes de publicar, confira:
</p>

<ul>
<li>Nome do produto</li>
<li>Preço</li>
<li>Descrição</li>
<li>Forma de pagamento</li>
<li>Checkout</li>
<li>Entrega do produto</li>
<li>Informações de contato</li>
</ul>
</div>

<div class="card">
<h2>7. Divulgação gratuita</h2>

<p>Você pode começar produzindo conteúdo.</p>

<div class="grid">

<div class="box">
<strong>🎥 Vídeo 1</strong>
<p>3 erros de quem tenta fazer a primeira venda.</p>
</div>

<div class="box">
<strong>🎥 Vídeo 2</strong>
<p>Como escolher um produto digital.</p>
</div>

<div class="box">
<strong>🎥 Vídeo 3</strong>
<p>Como criar uma oferta simples.</p>
</div>

<div class="box">
<strong>🎥 Vídeo 4</strong>
<p>Como montar uma página de vendas.</p>
</div>

</div>
</div>

<div class="card">
<h2>8. Como criar conteúdo</h2>

<div class="destaque">
<strong>Problema → Dica → Explicação → Chamada para ação</strong>
</div>

<p>
Exemplo: “Você criou um produto, mas ninguém compra?”
</p>

<p>
Explique que o cliente precisa entender claramente o que receberá
e qual problema o produto ajuda a resolver.
</p>
</div>

<div class="card">
<h2>9. Conversando com possíveis clientes</h2>

<p>
Se alguém demonstrar interesse, explique com clareza:
</p>

<ul>
<li>O que o produto ensina</li>
<li>Para quem é indicado</li>
<li>O que está incluído</li>
<li>Quanto custa</li>
<li>Como receberá o produto</li>
</ul>

<div class="destaque">
Não pressione ninguém a comprar.
Uma venda saudável acontece quando a pessoa entende o produto
e decide comprar por vontade própria.
</div>
</div>

<div class="card">
<h2>10. Erros que iniciantes devem evitar</h2>

<ol>
<li>Prometer resultados garantidos.</li>
<li>Criar produto sem conhecer o público.</li>
<li>Copiar produtos de outras pessoas.</li>
<li>Complicar demais.</li>
<li>Desistir rapidamente.</li>
</ol>
</div>

</section>

<section class="card" id="plano">

<h2>📅 Plano de ação de 7 dias</h2>

<div class="grid">

<div class="box">
<strong>Dia 1</strong>
<p>Escolha o produto.</p>
</div>

<div class="box">
<strong>Dia 2</strong>
<p>Defina seu público.</p>
</div>

<div class="box">
<strong>Dia 3</strong>
<p>Crie o conteúdo.</p>
</div>

<div class="box">
<strong>Dia 4</strong>
<p>Monte sua oferta.</p>
</div>

<div class="box">
<strong>Dia 5</strong>
<p>Monte a página.</p>
</div>

<div class="box">
<strong>Dia 6</strong>
<p>Crie conteúdos.</p>
</div>

<div class="box">
<strong>Dia 7</strong>
<p>Divulgue sua oferta.</p>
</div>

</div>

</section>

<section class="card" id="checklist">

<h2>✅ Checklist da primeira venda</h2>

<p>Marque os itens concluídos:</p>

<div class="checklist">

<label>
<input type="checkbox" onchange="progresso()">
Tenho um produto pronto.
</label>

<label>
<input type="checkbox" onchange="progresso()">
Sei quem é meu público.
</label>

<label>
<input type="checkbox" onchange="progresso()">
Minha oferta está clara.
</label>

<label>
<input type="checkbox" onchange="progresso()">
Minha página está funcionando.
</label>

<label>
<input type="checkbox" onchange="progresso()">
O pagamento está configurado.
</label>

<label>
<input type="checkbox" onchange="progresso()">
Sei como o cliente receberá o produto.
</label>

<label>
<input type="checkbox" onchange="progresso()">
Tenho conteúdos para divulgar.
</label>

<label>
<input type="checkbox" onchange="progresso()">
Sei responder dúvidas sobre o produto.
</label>

</div>

<div class="progress">
<div id="barra"></div>
</div>

<p id="porcentagem">0% concluído</p>

</section>

<section class="card" id="oferta">

<h2>🔥 Primeira Venda Online</h2>

<p>
Um guia prático para quem quer aprender os fundamentos
de criação, oferta e divulgação de produtos digitais.
</p>

<h3>Você recebe:</h3>

<ul>
<li>📘 Guia completo</li>
<li>📋 Checklist</li>
<li>📅 Plano de 7 dias</li>
<li>💡 Ideias de conteúdo</li>
<li>🚀 Estratégias para começar</li>
</ul>

<a href="#" class="btn" onclick="alert('Configure aqui o link do seu checkout!')">
QUERO ACESSAR O GUIA
</a>

</section>

<section class="card">

<h2>💬 Deixe sua opinião</h2>

<p>
O que você achou deste guia?
</p>

<textarea id="opiniao" placeholder="Digite sua opinião..."></textarea>

<button class="btn" onclick="enviarOpiniao()">
ENVIAR OPINIÃO
</button>

<p id="mensagem"></p>

</section>

<section class="card">

<h2>🎁 Bônus — Ideias de produtos digitais</h2>

<ul>
<li>Guia de estudos</li>
<li>Planner digital</li>
<li>E-book de organização</li>
<li>Guia para iniciantes em tecnologia</li>
<li>Templates para redes sociais</li>
<li>Checklist de criação de conteúdo</li>
<li>Apostila educativa</li>
<li>Guia de criação de sites</li>
</ul>

</section>

<section class="card">

<h2>🏁 Conclusão</h2>

<p>
A primeira venda é apenas o começo.
</p>

<div class="destaque">
<strong>
Escolher → Criar → Apresentar → Divulgar → Conversar → Vender → Melhorar
</strong>
</div>

<p>
Comece simples. Aprenda. Teste. Melhore.
</p>

</section>

</main>

<footer>

<h2>PRIMEIRA VENDA ONLINE</h2>

<p>Comece com uma ideia. Transforme em algo útil. Aprenda o processo.</p>

<p style="margin-top:15px;">
© 2026 — Todos os direitos reservados
</p>

</footer>

<script>

function progresso(){

  const caixas =
  document.querySelectorAll('.checklist input');

  let concluidos = 0;

  caixas.forEach(function(caixa){
    if(caixa.checked){
      concluidos++;
    }
  });

  const porcentagem =
  Math.round((concluidos / caixas.length) * 100);

  document.getElementById("barra").style.width =
  porcentagem + "%";

  document.getElementById("porcentagem").innerText =
  porcentagem + "% concluído";
}


function enviarOpiniao(){

  const texto =
  document.getElementById("opiniao").value;

  const mensagem =
  document.getElementById("mensagem");

  if(texto.trim() === ""){
    mensagem.innerText =
    "Digite sua opinião antes de enviar.";
    return;
  }

  localStorage.setItem("opiniaoPrimeiraVenda", texto);

  mensagem.innerText =
  "Obrigado! Sua opinião foi registrada neste dispositivo.";

  document.getElementById("opiniao").value = "";
}

</script>

</body>
</html>

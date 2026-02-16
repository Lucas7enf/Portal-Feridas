<!doctype html>
<html lang="pt-BR" class="h-full">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guia de Feridas</title>

  <!-- PWA -->
  <link rel="manifest" href="manifest.json">
  <meta name="theme-color" content="#2e7d32">

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Fonte -->
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">

  <style>
    * { font-family: 'Nunito', sans-serif; }

    .wound-card {
      transition: all 0.3s;
    }

    .wound-card:hover {
      transform: translateY(-4px);
    }

    .back-btn:hover {
      transform: translateX(-4px);
    }
  </style>
</head>

<body class="h-full" style="background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);">

<!-- BOTÃO FLUTUANTE -->
<button onclick="abrirMenu()" style="
position:fixed;
bottom:20px;
right:20px;
background:#2e7d32;
color:white;
border:none;
border-radius:50%;
width:60px;
height:60px;
font-size:24px;
z-index:999;
">
+
</button>

<!-- MENU POPUP -->
<div id="menu" style="
display:none;
position:fixed;
bottom:90px;
right:20px;
background:white;
padding:15px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.2);
z-index:999;
">
  <p><b>Acesso rápido</b></p>
  <button onclick="alert('Abrir identificação')">Identificar ferida</button><br><br>
  <button onclick="alert('Abrir conduta')">Conduta</button>
</div>

<!-- APP -->
<div id="app" class="h-full w-full overflow-auto">

  <!-- TELA PRINCIPAL -->
  <div id="main-screen" class="min-h-full p-6 text-center text-white">

    <h1 class="text-3xl font-bold mb-4">Guia de Feridas</h1>
    <p class="mb-6">Selecione o tipo de ferida:</p>

    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 max-w-xl mx-auto">

      <button onclick="showWound('corte')" class="wound-card p-4 rounded-xl bg-red-500">
        Corte
      </button>

      <button onclick="showWound('arranhao')" class="wound-card p-4 rounded-xl bg-yellow-500">
        Arranhão
      </button>

      <button onclick="showWound('perfuracao')" class="wound-card p-4 rounded-xl bg-purple-500">
        Perfuração
      </button>

      <button onclick="showWound('queimadura')" class="wound-card p-4 rounded-xl bg-orange-500">
        Queimadura
      </button>

    </div>

  </div>

  <!-- TELA DETALHE -->
  <div id="detail-screen" class="hidden p-6 text-white text-center">

    <button onclick="goBack()" class="mb-4 bg-white text-black px-4 py-2 rounded">
      Voltar
    </button>

    <h2 id="titulo" class="text-2xl font-bold mb-4"></h2>
    <p id="descricao"></p>

  </div>

</div>

<!-- SCRIPT -->
<script>

function abrirMenu() {
  let menu = document.getElementById("menu");
  menu.style.display = menu.style.display === "none" ? "block" : "none";
}

function showWound(tipo) {
  document.getElementById("main-screen").classList.add("hidden");
  document.getElementById("detail-screen").classList.remove("hidden");

  const dados = {
    corte: "Ferida com objeto cortante.",
    arranhao: "Ferida superficial por atrito.",
    perfuracao: "Ferida profunda por objeto pontiagudo.",
    queimadura: "Lesão por calor ou substância."
  };

  document.getElementById("titulo").innerText = tipo.toUpperCase();
  document.getElementById("descricao").innerText = dados[tipo];
}

function goBack() {
  document.getElementById("main-screen").classList.remove("hidden");
  document.getElementById("detail-screen").classList.add("hidden");
}

if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('sw.js');
}

</script>

</body>
</html>

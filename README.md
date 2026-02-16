<!doctype html>
<html lang="pt-BR" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guia de Prevenção LPP</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700&amp;display=swap" rel="stylesheet">
  <style>
    * { font-family: 'Plus Jakarta Sans', sans-serif; }
    .gradient-bg { background: linear-gradient(135deg, #0f766e 0%, #115e59 50%, #134e4a 100%); }
    .card-hover { transition: all 0.3s ease; }
    .card-hover:hover { transform: translateY(-4px); box-shadow: 0 20px 40px rgba(15, 118, 110, 0.15); }
    .stage-card { transition: all 0.3s ease; }
    .stage-card:hover { transform: scale(1.02); }
    .nav-link { position: relative; }
    .nav-link::after { content: ''; position: absolute; bottom: -2px; left: 0; width: 0; height: 2px; background: #14b8a6; transition: width 0.3s ease; }
    .nav-link:hover::after { width: 100%; }
    .checklist-item { transition: all 0.2s ease; }
    .checklist-item:hover { background: #f0fdfa; }
    .pulse-icon { animation: pulse 2s infinite; }
    @keyframes pulse { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.05); } }
    .scroll-section { scroll-margin-top: 80px; }
  </style>
  <style>body { box-sizing: border-box; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full bg-gray-50 overflow-auto">
  <div class="w-full min-h-full"><!-- Navigation -->
   <nav class="gradient-bg sticky top-0 z-50 shadow-lg">
    <div class="max-w-7xl mx-auto px-4 py-4">
     <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-4">
      <div class="flex items-center gap-3">
       <div class="w-10 h-10 bg-white/20 rounded-xl flex items-center justify-center">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
        </svg>
       </div><span class="text-white font-bold text-lg">Guia LPP</span>
      </div>
      <div class="flex flex-wrap gap-2 md:gap-6"><a href="#sobre" class="nav-link text-white/90 hover:text-white text-sm font-medium px-2 py-1">Sobre</a> <a href="#avaliacao" class="nav-link text-white/90 hover:text-white text-sm font-medium px-2 py-1">Avaliação</a> <a href="#decubito" class="nav-link text-white/90 hover:text-white text-sm font-medium px-2 py-1">Mudança de Decúbito</a> <a href="#pele" class="nav-link text-white/90 hover:text-white text-sm font-medium px-2 py-1">Cuidados com Pele</a> <a href="#estagios" class="nav-link text-white/90 hover:text-white text-sm font-medium px-2 py-1">Estágios</a>
      </div>
     </div>
    </div>
   </nav><!-- Hero Section -->
   <header class="gradient-bg py-16 md:py-24 px-4">
    <div class="max-w-4xl mx-auto text-center">
     <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur rounded-full px-4 py-2 mb-6"><span class="w-2 h-2 bg-emerald-400 rounded-full animate-pulse"></span> <span class="text-emerald-100 text-sm font-medium">Prevenção é o melhor tratamento</span>
     </div>
     <h1 id="main-title" class="text-3xl md:text-5xl font-bold text-white mb-4 leading-tight">Guia de Prevenção de<br>
      Lesão por Pressão</h1>
     <p id="subtitle" class="text-lg md:text-xl text-teal-100 max-w-2xl mx-auto mb-8">Orientações essenciais para cuidadores e profissionais de saúde sobre prevenção e cuidados com LPP</p>
     <div class="flex flex-wrap justify-center gap-4"><a href="#avaliacao" class="bg-white text-teal-700 px-6 py-3 rounded-xl font-semibold hover:bg-teal-50 transition-all shadow-lg"> Iniciar Avaliação </a> <a href="#decubito" class="bg-white/10 backdrop-blur text-white px-6 py-3 rounded-xl font-semibold hover:bg-white/20 transition-all border border-white/20"> Ver Cuidados </a>
     </div>
    </div>
   </header><!-- Stats -->
   <section class="py-8 px-4 bg-white border-b">
    <div class="max-w-5xl mx-auto grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
     <div>
      <div class="text-2xl md:text-3xl font-bold text-teal-600">
       95%
      </div>
      <div class="text-gray-500 text-sm">
       Preveníveis
      </div>
     </div>
     <div>
      <div class="text-2xl md:text-3xl font-bold text-teal-600">
       2h
      </div>
      <div class="text-gray-500 text-sm">
       Intervalo Máximo
      </div>
     </div>
     <div>
      <div class="text-2xl md:text-3xl font-bold text-teal-600">
       6
      </div>
      <div class="text-gray-500 text-sm">
       Posições Principais
      </div>
     </div>
     <div>
      <div class="text-2xl md:text-3xl font-bold text-teal-600">
       30°
      </div>
      <div class="text-gray-500 text-sm">
       Ângulo Ideal
      </div>
     </div>
    </div>
   </section><!-- O que é LPP -->
   <section id="sobre" class="scroll-section py-16 px-4">
    <div class="max-w-6xl mx-auto">
     <div class="text-center mb-12"><span class="inline-block bg-teal-100 text-teal-700 px-4 py-1 rounded-full text-sm font-medium mb-4">Conceito</span>
      <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-4">O que é Lesão por Pressão?</h2>
     </div>
     <div class="grid md:grid-cols-2 gap-8 items-center">
      <div class="bg-white rounded-2xl p-8 shadow-lg border border-gray-100">
       <p class="text-gray-600 leading-relaxed mb-6">A <strong class="text-teal-700">Lesão por Pressão (LPP)</strong> é um dano localizado na pele e/ou tecido subjacente, geralmente sobre uma proeminência óssea, resultante de pressão intensa e/ou prolongada combinada com cisalhamento.</p>
       <div class="space-y-4">
        <div class="flex items-start gap-3">
         <div class="w-8 h-8 bg-red-100 rounded-lg flex items-center justify-center flex-shrink-0">
          <svg class="w-4 h-4 text-red-600" fill="currentColor" viewbox="0 0 20 20"><path fill-rule="evenodd" d="M8.257 3.099c.765-1.36 2.722-1.36 3.486 0l5.58 9.92c.75 1.334-.213 2.98-1.742 2.98H4.42c-1.53 0-2.493-1.646-1.743-2.98l5.58-9.92zM11 13a1 1 0 11-2 0 1 1 0 012 0zm-1-8a1 1 0 00-1 1v3a1 1 0 002 0V6a1 1 0 00-1-1z" clip-rule="evenodd"></path>
          </svg>
         </div>
         <div>
          <h4 class="font-semibold text-gray-800">Principais Causas</h4>
          <p class="text-gray-500 text-sm">Pressão prolongada, fricção, cisalhamento e umidade excessiva</p>
         </div>
        </div>
        <div class="flex items-start gap-3">
         <div class="w-8 h-8 bg-amber-100 rounded-lg flex items-center justify-center flex-shrink-0">
          <svg class="w-4 h-4 text-amber-600" fill="currentColor" viewbox="0 0 20 20"><path d="M9 6a3 3 0 11-6 0 3 3 0 016 0zM17 6a3 3 0 11-6 0 3 3 0 016 0zM12.93 17c.046-.327.07-.66.07-1a6.97 6.97 0 00-1.5-4.33A5 5 0 0119 16v1h-6.07zM6 11a5 5 0 015 5v1H1v-1a5 5 0 015-5z"></path>
          </svg>
         </div>
         <div>
          <h4 class="font-semibold text-gray-800">Grupos de Risco</h4>
          <p class="text-gray-500 text-sm">Idosos, acamados, cadeirantes e pacientes com mobilidade reduzida</p>
         </div>
        </div>
       </div>
      </div>
      <div class="bg-gradient-to-br from-teal-50 to-emerald-50 rounded-2xl p-8 border border-teal-100">
       <h3 class="font-bold text-gray-800 mb-4 flex items-center gap-2"><span class="text-2xl">📍</span> Locais Mais Comuns</h3>
       <div class="grid grid-cols-2 gap-3">
        <div class="bg-white rounded-xl p-3 text-center shadow-sm">
         <div class="text-2xl mb-1">
          🦴
         </div><span class="text-sm text-gray-700 font-medium">Sacro</span>
        </div>
        <div class="bg-white rounded-xl p-3 text-center shadow-sm">
         <div class="text-2xl mb-1">
          🦶
         </div><span class="text-sm text-gray-700 font-medium">Calcanhares</span>
        </div>
        <div class="bg-white rounded-xl p-3 text-center shadow-sm">
         <div class="text-2xl mb-1">
          🦵
         </div><span class="text-sm text-gray-700 font-medium">Trocânteres</span>
        </div>
        <div class="bg-white rounded-xl p-3 text-center shadow-sm">
         <div class="text-2xl mb-1">
          🦴
         </div><span class="text-sm text-gray-700 font-medium">Escápulas</span>
        </div>
        <div class="bg-white rounded-xl p-3 text-center shadow-sm">
         <div class="text-2xl mb-1">
          💪
         </div><span class="text-sm text-gray-700 font-medium">Cotovelos</span>
        </div>
        <div class="bg-white rounded-xl p-3 text-center shadow-sm">
         <div class="text-2xl mb-1">
          👂
         </div><span class="text-sm text-gray-700 font-medium">Orelhas</span>
        </div>
       </div>
      </div>
     </div>
    </div>
   </section><!-- Avaliação de Risco -->
   <section id="avaliacao" class="scroll-section py-16 px-4 bg-white">
    <div class="max-w-6xl mx-auto">
     <div class="text-center mb-12"><span class="inline-block bg-blue-100 text-blue-700 px-4 py-1 rounded-full text-sm font-medium mb-4">Escala de Braden</span>
      <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-4">Avaliação de Risco</h2>
      <p class="text-gray-500 max-w-2xl mx-auto">A Escala de Braden é a ferramenta mais utilizada para avaliar o risco de desenvolvimento de LPP</p>
     </div>
     <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6 mb-10"><!-- Percepção Sensorial -->
      <div class="card-hover bg-gradient-to-br from-purple-50 to-purple-100 rounded-2xl p-6 border border-purple-200">
       <div class="w-12 h-12 bg-purple-500 rounded-xl flex items-center justify-center mb-4">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"></path>
        </svg>
       </div>
       <h3 class="font-bold text-gray-800 mb-2">Percepção Sensorial</h3>
       <p class="text-gray-600 text-sm">Capacidade de responder significativamente ao desconforto relacionado à pressão</p>
       <div class="mt-4 text-xs text-purple-700 font-medium">
        Pontuação: 1-4
       </div>
      </div><!-- Umidade -->
      <div class="card-hover bg-gradient-to-br from-blue-50 to-blue-100 rounded-2xl p-6 border border-blue-200">
       <div class="w-12 h-12 bg-blue-500 rounded-xl flex items-center justify-center mb-4">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path>
        </svg>
       </div>
       <h3 class="font-bold text-gray-800 mb-2">Umidade</h3>
       <p class="text-gray-600 text-sm">Grau de exposição da pele à umidade (suor, urina, fezes)</p>
       <div class="mt-4 text-xs text-blue-700 font-medium">
        Pontuação: 1-4
       </div>
      </div><!-- Atividade -->
      <div class="card-hover bg-gradient-to-br from-green-50 to-green-100 rounded-2xl p-6 border border-green-200">
       <div class="w-12 h-12 bg-green-500 rounded-xl flex items-center justify-center mb-4">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
        </svg>
       </div>
       <h3 class="font-bold text-gray-800 mb-2">Atividade</h3>
       <p class="text-gray-600 text-sm">Grau de atividade física (acamado, confinado à cadeira, deambula)</p>
       <div class="mt-4 text-xs text-green-700 font-medium">
        Pontuação: 1-4
       </div>
      </div><!-- Mobilidade -->
      <div class="card-hover bg-gradient-to-br from-amber-50 to-amber-100 rounded-2xl p-6 border border-amber-200">
       <div class="w-12 h-12 bg-amber-500 rounded-xl flex items-center justify-center mb-4">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15"></path>
        </svg>
       </div>
       <h3 class="font-bold text-gray-800 mb-2">Mobilidade</h3>
       <p class="text-gray-600 text-sm">Capacidade de mudar e controlar a posição do corpo</p>
       <div class="mt-4 text-xs text-amber-700 font-medium">
        Pontuação: 1-4
       </div>
      </div><!-- Nutrição -->
      <div class="card-hover bg-gradient-to-br from-red-50 to-red-100 rounded-2xl p-6 border border-red-200">
       <div class="w-12 h-12 bg-red-500 rounded-xl flex items-center justify-center mb-4">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"></path>
        </svg>
       </div>
       <h3 class="font-bold text-gray-800 mb-2">Nutrição</h3>
       <p class="text-gray-600 text-sm">Padrão usual de ingestão alimentar e hidratação</p>
       <div class="mt-4 text-xs text-red-700 font-medium">
        Pontuação: 1-4
       </div>
      </div><!-- Fricção e Cisalhamento -->
      <div class="card-hover bg-gradient-to-br from-teal-50 to-teal-100 rounded-2xl p-6 border border-teal-200">
       <div class="w-12 h-12 bg-teal-500 rounded-xl flex items-center justify-center mb-4">
        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zm0 0h12a2 2 0 002-2v-4a2 2 0 00-2-2h-2.343M11 7.343l1.657-1.657a2 2 0 012.828 0l2.829 2.829a2 2 0 010 2.828l-8.486 8.485M7 17h.01"></path>
        </svg>
       </div>
       <h3 class="font-bold text-gray-800 mb-2">Fricção e Cisalhamento</h3>
       <p class="text-gray-600 text-sm">Capacidade de evitar o atrito da pele contra superfícies</p>
       <div class="mt-4 text-xs text-teal-700 font-medium">
        Pontuação: 1-3
       </div>
      </div>
     </div><!-- Interpretação -->
     <div class="bg-gray-50 rounded-2xl p-6 md:p-8 border border-gray-200">
      <h3 class="font-bold text-gray-800 mb-6 text-center">📊 Interpretação da Pontuação Total</h3>
      <div class="grid md:grid-cols-3 gap-4">
       <div class="bg-red-500 text-white rounded-xl p-5 text-center">
        <div class="text-3xl font-bold mb-1">
         ≤ 12
        </div>
        <div class="font-semibold">
         Alto Risco
        </div>
        <div class="text-red-100 text-sm mt-2">
         Reposicionamento a cada 2h
        </div>
       </div>
       <div class="bg-amber-500 text-white rounded-xl p-5 text-center">
        <div class="text-3xl font-bold mb-1">
         13-14
        </div>
        <div class="font-semibold">
         Risco Moderado
        </div>
        <div class="text-amber-100 text-sm mt-2">
         Reposicionamento a cada 3h
        </div>
       </div>
       <div class="bg-green-500 text-white rounded-xl p-5 text-center">
        <div class="text-3xl font-bold mb-1">
         15-18
        </div>
        <div class="font-semibold">
         Baixo Risco
        </div>
        <div class="text-green-100 text-sm mt-2">
         Reposicionamento a cada 4h
        </div>
       </div>
      </div>
     </div>
    </div>
   </section><!-- Mudança de Decúbito -->
   <section id="decubito" class="scroll-section py-16 px-4 bg-gradient-to-br from-teal-50 to-emerald-50">
    <div class="max-w-6xl mx-auto">
     <div class="text-center mb-12"><span class="inline-block bg-teal-100 text-teal-700 px-4 py-1 rounded-full text-sm font-medium mb-4">Reposicionamento</span>
      <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-4">Mudança de Decúbito</h2>
      <p class="text-gray-500 max-w-2xl mx-auto">O reposicionamento regular é a principal medida de prevenção de LPP</p>
     </div><!-- Cronograma -->
     <div class="bg-white rounded-2xl p-6 md:p-8 shadow-lg mb-10 border border-teal-100">
      <h3 class="font-bold text-gray-800 mb-6 flex items-center gap-2"><span class="text-2xl">⏰</span> Cronograma de Reposicionamento (Relógio de Decúbito)</h3>
      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-4">
       <div class="bg-teal-600 text-white rounded-xl p-4 text-center">
        <div class="text-lg font-bold">
         00:00
        </div>
        <div class="text-teal-100 text-sm mt-1">
         Decúbito Dorsal
        </div>
       </div>
       <div class="bg-teal-500 text-white rounded-xl p-4 text-center">
        <div class="text-lg font-bold">
         02:00
        </div>
        <div class="text-teal-100 text-sm mt-1">
         Lateral Esquerdo
        </div>
       </div>
       <div class="bg-teal-600 text-white rounded-xl p-4 text-center">
        <div class="text-lg font-bold">
         04:00
        </div>
        <div class="text-teal-100 text-sm mt-1">
         Decúbito Dorsal
        </div>
       </div>
       <div class="bg-teal-500 text-white rounded-xl p-4 text-center">
        <div class="text-lg font-bold">
         06:00
        </div>
        <div class="text-teal-100 text-sm mt-1">
         Lateral Direito
        </div>
       </div>
       <div class="bg-teal-600 text-white rounded-xl p-4 text-center">
        <div class="text-lg font-bold">
         08:00
        </div>
        <div class="text-teal-100 text-sm mt-1">
         Decúbito Dorsal
        </div>
       </div>
       <div class="bg-teal-500 text-white rounded-xl p-4 text-center">
        <div class="text-lg font-bold">
         10:00
        </div>
        <div class="text-teal-100 text-sm mt-1">
         Lateral Esquerdo
        </div>
       </div>
      </div>
      <p class="text-gray-500 text-sm text-center mt-4">* O ciclo se repete a cada 12 horas. Adapte conforme necessidade do paciente.</p>
     </div><!-- Posições -->
     <div class="grid md:grid-cols-2 gap-6 mb-10"><!-- Decúbito Dorsal -->
      <div class="bg-white rounded-2xl p-6 shadow-lg border border-gray-100">
       <div class="flex items-center gap-3 mb-4">
        <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center text-2xl">
         🛏️
        </div>
        <div>
         <h4 class="font-bold text-gray-800">Decúbito Dorsal</h4><span class="text-blue-600 text-sm">Posição de costas</span>
        </div>
       </div>
       <ul class="space-y-2">
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Elevar cabeceira a 30° (máximo 45°)</span></li>
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Usar travesseiro sob a panturrilha</span></li>
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Calcanhares livres de pressão</span></li>
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Joelhos levemente flexionados</span></li>
       </ul>
      </div><!-- Decúbito Lateral -->
      <div class="bg-white rounded-2xl p-6 shadow-lg border border-gray-100">
       <div class="flex items-center gap-3 mb-4">
        <div class="w-12 h-12 bg-green-100 rounded-xl flex items-center justify-center text-2xl">
         🔄
        </div>
        <div>
         <h4 class="font-bold text-gray-800">Decúbito Lateral</h4><span class="text-green-600 text-sm">Posição de lado (30°)</span>
        </div>
       </div>
       <ul class="space-y-2">
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Inclinação máxima de 30°</span></li>
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Travesseiro entre os joelhos</span></li>
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Evitar pressão direta no trocânter</span></li>
        <li class="flex items-start gap-2"><span class="text-teal-500 mt-1">✓</span> <span class="text-gray-600 text-sm">Apoiar costas com coxins</span></li>
       </ul>
      </div>
     </div><!-- Dicas Importantes -->
     <div class="bg-amber-50 rounded-2xl p-6 border border-amber-200">
      <h3 class="font-bold text-amber-800 mb-4 flex items-center gap-2"><span class="text-xl">⚠️</span> Atenção ao Reposicionar</h3>
      <div class="grid md:grid-cols-2 gap-4">
       <div class="flex items-start gap-3"><span class="text-red-500 text-xl">✗</span>
        <div>
         <p class="font-medium text-gray-800">NUNCA arrastar o paciente</p>
         <p class="text-gray-500 text-sm">Use lençol móvel e técnica de elevação</p>
        </div>
       </div>
       <div class="flex items-start gap-3"><span class="text-red-500 text-xl">✗</span>
        <div>
         <p class="font-medium text-gray-800">EVITAR posição lateral a 90°</p>
         <p class="text-gray-500 text-sm">Causa pressão direta no trocânter</p>
        </div>
       </div>
       <div class="flex items-start gap-3"><span class="text-red-500 text-xl">✗</span>
        <div>
         <p class="font-medium text-gray-800">NÃO usar almofadas tipo "donut"</p>
         <p class="text-gray-500 text-sm">Causam isquemia nas bordas</p>
        </div>
       </div>
       <div class="flex items-start gap-3"><span class="text-red-500 text-xl">✗</span>
        <div>
         <p class="font-medium text-gray-800">EVITAR elevar cabeceira &gt; 45°</p>
         <p class="text-gray-500 text-sm">Aumenta cisalhamento na região sacral</p>
        </div>
       </div>
      </div>
     </div>
    </div>
   </section><!-- Cuidados com a Pele -->
   <section id="pele" class="scroll-section py-16 px-4 bg-white">
    <div class="max-w-6xl mx-auto">
     <div class="text-center mb-12"><span class="inline-block bg-pink-100 text-pink-700 px-4 py-1 rounded-full text-sm font-medium mb-4">Proteção</span>
      <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-4">Cuidados com a Pele</h2>
      <p class="text-gray-500 max-w-2xl mx-auto">Manter a integridade da pele é fundamental para prevenir lesões</p>
     </div>
     <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 mb-10"><!-- Higiene -->
      <div class="card-hover bg-white rounded-2xl p-6 shadow-lg border border-gray-100">
       <div class="w-14 h-14 bg-blue-100 rounded-2xl flex items-center justify-center text-3xl mb-4 pulse-icon">
        🚿
       </div>
       <h3 class="font-bold text-gray-800 mb-3">Higiene</h3>
       <ul class="text-gray-600 text-sm space-y-2">
        <li>• Banho com água morna</li>
        <li>• Sabonete neutro de pH balanceado</li>
        <li>• Secar sem friccionar</li>
        <li>• Atenção às dobras cutâneas</li>
       </ul>
      </div><!-- Hidratação -->
      <div class="card-hover bg-white rounded-2xl p-6 shadow-lg border border-gray-100">
       <div class="w-14 h-14 bg-teal-100 rounded-2xl flex items-center justify-center text-3xl mb-4 pulse-icon">
        💧
       </div>
       <h3 class="font-bold text-gray-800 mb-3">Hidratação</h3>
       <ul class="text-gray-600 text-sm space-y-2">
        <li>• Aplicar hidratante 2x ao dia</li>
        <li>• Evitar áreas com lesões</li>
        <li>• Usar produtos sem álcool</li>
        <li>• Massagear suavemente</li>
       </ul>
      </div><!-- Controle de Umidade -->
      <div class="card-hover bg-white rounded-2xl p-6 shadow-lg border border-gray-100">
       <div class="w-14 h-14 bg-amber-100 rounded-2xl flex items-center justify-center text-3xl mb-4 pulse-icon">
        🌡️
       </div>
       <h3 class="font-bold text-gray-800 mb-3">Controle de Umidade</h3>
       <ul class="text-gray-600 text-sm space-y-2">
        <li>• Trocar fraldas imediatamente</li>
        <li>• Usar cremes barreira</li>
        <li>• Absorventes adequados</li>
        <li>• Manter pele seca</li>
       </ul>
      </div><!-- Inspeção -->
      <div class="card-hover bg-white rounded-2xl p-6 shadow-lg border border-gray-100">
       <div class="w-14 h-14 bg-purple-100 rounded-2xl flex items-center justify-center text-3xl mb-4 pulse-icon">
        🔍
       </div>
       <h3 class="font-bold text-gray-800 mb-3">Inspeção Diária</h3>
       <ul class="text-gray-600 text-sm space-y-2">
        <li>• Verificar proeminências ósseas</li>
        <li>• Observar áreas avermelhadas</li>
        <li>• Avaliar mudança de temperatura</li>
        <li>• Documentar alterações</li>
       </ul>
      </div>
     </div><!-- Checklist -->
     <div class="bg-gradient-to-r from-teal-600 to-emerald-600 rounded-2xl p-6 md:p-8 text-white">
      <h3 class="font-bold text-xl mb-6 flex items-center gap-2"><span class="text-2xl">✅</span> Checklist Diário de Cuidados</h3>
      <div class="grid md:grid-cols-2 gap-4"><label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Realizar higiene corporal adequada</span> </label> <label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Aplicar hidratante em todo o corpo</span> </label> <label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Inspecionar proeminências ósseas</span> </label> <label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Realizar mudanças de decúbito</span> </label> <label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Manter roupa de cama esticada</span> </label> <label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Aplicar proteção nos calcanhares</span> </label> <label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Oferecer hidratação oral adequada</span> </label> <label class="checklist-item flex items-center gap-3 bg-white/10 rounded-xl p-4 cursor-pointer hover:bg-white/20 transition-all"> <input type="checkbox" class="w-5 h-5 rounded"> <span>Documentar condições da pele</span> </label>
      </div>
     </div>
    </div>
   </section><!-- Estágios da LPP -->
   <section id="estagios" class="scroll-section py-16 px-4 bg-gray-50">
    <div class="max-w-6xl mx-auto">
     <div class="text-center mb-12"><span class="inline-block bg-red-100 text-red-700 px-4 py-1 rounded-full text-sm font-medium mb-4">Classificação</span>
      <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-4">Estágios da Lesão por Pressão</h2>
      <p class="text-gray-500 max-w-2xl mx-auto">Identificar o estágio é essencial para o tratamento adequado</p>
     </div>
     <div class="space-y-6"><!-- Estágio 1 -->
      <div class="stage-card bg-white rounded-2xl p-6 shadow-lg border-l-4 border-yellow-400">
       <div class="flex flex-col md:flex-row md:items-center gap-4">
        <div class="flex items-center gap-4">
         <div class="w-16 h-16 bg-yellow-100 rounded-2xl flex items-center justify-center"><span class="text-2xl font-bold text-yellow-600">1</span>
         </div>
         <div>
          <h3 class="font-bold text-gray-800 text-lg">Estágio 1</h3><span class="text-yellow-600 font-medium">Pele Íntegra</span>
         </div>
        </div>
        <div class="flex-1 md:pl-6 md:border-l border-gray-200">
         <p class="text-gray-600">Eritema não branqueável em pele íntegra. Área pode estar dolorosa, endurecida, macia, mais quente ou mais fria que o tecido adjacente.</p>
        </div>
        <div class="bg-yellow-50 rounded-xl p-3 text-center"><span class="text-yellow-700 font-medium text-sm">Reversível com cuidados</span>
        </div>
       </div>
      </div><!-- Estágio 2 -->
      <div class="stage-card bg-white rounded-2xl p-6 shadow-lg border-l-4 border-orange-400">
       <div class="flex flex-col md:flex-row md:items-center gap-4">
        <div class="flex items-center gap-4">
         <div class="w-16 h-16 bg-orange-100 rounded-2xl flex items-center justify-center"><span class="text-2xl font-bold text-orange-600">2</span>
         </div>
         <div>
          <h3 class="font-bold text-gray-800 text-lg">Estágio 2</h3><span class="text-orange-600 font-medium">Perda Parcial</span>
         </div>
        </div>
        <div class="flex-1 md:pl-6 md:border-l border-gray-200">
         <p class="text-gray-600">Perda parcial da espessura da pele com exposição da derme. Leito da ferida rosa/vermelho, úmido. Pode apresentar bolha intacta ou rompida.</p>
        </div>
        <div class="bg-orange-50 rounded-xl p-3 text-center"><span class="text-orange-700 font-medium text-sm">Requer curativo</span>
        </div>
       </div>
      </div><!-- Estágio 3 -->
      <div class="stage-card bg-white rounded-2xl p-6 shadow-lg border-l-4 border-red-400">
       <div class="flex flex-col md:flex-row md:items-center gap-4">
        <div class="flex items-center gap-4">
         <div class="w-16 h-16 bg-red-100 rounded-2xl flex items-center justify-center"><span class="text-2xl font-bold text-red-600">3</span>
         </div>
         <div>
          <h3 class="font-bold text-gray-800 text-lg">Estágio 3</h3><span class="text-red-600 font-medium">Perda Total</span>
         </div>
        </div>
        <div class="flex-1 md:pl-6 md:border-l border-gray-200">
         <p class="text-gray-600">Perda total da espessura da pele. Gordura visível, mas osso/tendão/músculo não expostos. Pode haver descolamento e tunelização.</p>
        </div>
        <div class="bg-red-50 rounded-xl p-3 text-center"><span class="text-red-700 font-medium text-sm">Avaliação profissional</span>
        </div>
       </div>
      </div><!-- Estágio 4 -->
      <div class="stage-card bg-white rounded-2xl p-6 shadow-lg border-l-4 border-red-700">
       <div class="flex flex-col md:flex-row md:items-center gap-4">
        <div class="flex items-center gap-4">
         <div class="w-16 h-16 bg-red-200 rounded-2xl flex items-center justify-center"><span class="text-2xl font-bold text-red-800">4</span>
         </div>
         <div>
          <h3 class="font-bold text-gray-800 text-lg">Estágio 4</h3><span class="text-red-700 font-medium">Exposição Profunda</span>
         </div>
        </div>
        <div class="flex-1 md:pl-6 md:border-l border-gray-200">
         <p class="text-gray-600">Perda total da espessura da pele e tecidos com exposição de fáscia, músculo, tendão, ligamento, cartilagem ou osso.</p>
        </div>
        <div class="bg-red-100 rounded-xl p-3 text-center"><span class="text-red-800 font-medium text-sm">Tratamento especializado</span>
        </div>
       </div>
      </div>
     </div><!-- Alerta -->
     <div class="mt-10 bg-red-50 rounded-2xl p-6 border border-red-200">
      <div class="flex items-start gap-4">
       <div class="w-12 h-12 bg-red-100 rounded-xl flex items-center justify-center flex-shrink-0">
        <svg class="w-6 h-6 text-red-600" fill="currentColor" viewbox="0 0 20 20"><path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7 4a1 1 0 11-2 0 1 1 0 012 0zm-1-9a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z" clip-rule="evenodd"></path>
        </svg>
       </div>
       <div>
        <h4 class="font-bold text-red-800 mb-2">Quando Buscar Ajuda Profissional</h4>
        <ul class="text-red-700 text-sm space-y-1">
         <li>• Sinais de infecção: odor fétido, secreção purulenta, febre</li>
         <li>• Lesão que não melhora após 2 semanas de cuidados</li>
         <li>• Presença de tecido necrótico (preto ou amarelado)</li>
         <li>• Aumento do tamanho ou profundidade da lesão</li>
        </ul>
       </div>
      </div>
     </div>
    </div>
   </section><!-- Footer -->
   <footer class="gradient-bg py-12 px-4">
    <div class="max-w-6xl mx-auto">
     <div class="text-center">
      <div class="inline-flex items-center gap-2 mb-4">
       <div class="w-10 h-10 bg-white/20 rounded-xl flex items-center justify-center">
        <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
        </svg>
       </div><span class="text-white font-bold text-lg">Guia de Prevenção LPP</span>
      </div>
      <p class="text-teal-100 mb-6 max-w-md mx-auto">Conteúdo educativo para cuidadores e profissionais de saúde. Consulte sempre um profissional de saúde qualificado.</p>
      <div class="flex flex-wrap justify-center gap-4 text-sm text-teal-200"><span>📚 Material Educativo</span> <span>•</span> <span>🏥 Baseado em Evidências</span> <span>•</span> <span>💚 Prevenção é Cuidado</span>
      </div>
      <div class="mt-8 pt-6 border-t border-white/10 text-teal-200 text-sm">
       © 2025 Guia de Prevenção LPP. Todos os direitos reservados.
      </div>
     </div>
    </div>
   </footer>
  </div>
  <script>
    // Default configuration
    const defaultConfig = {
      main_title: 'Guia de Prevenção de<br>Lesão por Pressão',
      subtitle: 'Orientações essenciais para cuidadores e profissionais de saúde sobre prevenção e cuidados com LPP',
      background_color: '#0f766e',
      surface_color: '#ffffff',
      text_color: '#1f2937',
      primary_action_color: '#0d9488',
      secondary_action_color: '#14b8a6',
      font_family: 'Plus Jakarta Sans',
      font_size: 16
    };

    // Initialize Element SDK
    async function initApp() {
      if (window.elementSdk) {
        await window.elementSdk.init({
          defaultConfig,
          onConfigChange: async (config) => {
            // Update title
            const titleEl = document.getElementById('main-title');
            if (titleEl) {
              titleEl.innerHTML = config.main_title || defaultConfig.main_title;
            }

            // Update subtitle
            const subtitleEl = document.getElementById('subtitle');
            if (subtitleEl) {
              subtitleEl.textContent = config.subtitle || defaultConfig.subtitle;
            }

            // Apply colors
            const bgColor = config.background_color || defaultConfig.background_color;
            const surfaceColor = config.surface_color || defaultConfig.surface_color;
            const textColor = config.text_color || defaultConfig.text_color;
            const primaryAction = config.primary_action_color || defaultConfig.primary_action_color;
            const secondaryAction = config.secondary_action_color || defaultConfig.secondary_action_color;

            // Update gradient backgrounds
            document.querySelectorAll('.gradient-bg').forEach(el => {
              el.style.background = `linear-gradient(135deg, ${bgColor} 0%, ${bgColor}ee 50%, ${bgColor}dd 100%)`;
            });

            // Update surface colors (cards)
            document.querySelectorAll('.bg-white').forEach(el => {
              if (!el.classList.contains('bg-white/10') && !el.classList.contains('bg-white/20')) {
                el.style.backgroundColor = surfaceColor;
              }
            });

            // Update text colors
            document.querySelectorAll('.text-gray-800, .text-gray-700').forEach(el => {
              el.style.color = textColor;
            });

            // Apply font
            const fontFamily = config.font_family || defaultConfig.font_family;
            const baseFontStack = 'system-ui, sans-serif';
            document.body.style.fontFamily = `${fontFamily}, ${baseFontStack}`;

            // Apply font size
            const baseSize = config.font_size || defaultConfig.font_size;
            document.documentElement.style.fontSize = `${baseSize}px`;
          },
          mapToCapabilities: (config) => ({
            recolorables: [
              {
                get: () => config.background_color || defaultConfig.background_color,
                set: (value) => window.elementSdk.setConfig({ background_color: value })
              },
              {
                get: () => config.surface_color || defaultConfig.surface_color,
                set: (value) => window.elementSdk.setConfig({ surface_color: value })
              },
              {
                get: () => config.text_color || defaultConfig.text_color,
                set: (value) => window.elementSdk.setConfig({ text_color: value })
              },
              {
                get: () => config.primary_action_color || defaultConfig.primary_action_color,
                set: (value) => window.elementSdk.setConfig({ primary_action_color: value })
              },
              {
                get: () => config.secondary_action_color || defaultConfig.secondary_action_color,
                set: (value) => window.elementSdk.setConfig({ secondary_action_color: value })
              }
            ],
            borderables: [],
            fontEditable: {
              get: () => config.font_family || defaultConfig.font_family,
              set: (value) => window.elementSdk.setConfig({ font_family: value })
            },
            fontSizeable: {
              get: () => config.font_size || defaultConfig.font_size,
              set: (value) => window.elementSdk.setConfig({ font_size: value })
            }
          }),
          mapToEditPanelValues: (config) => new Map([
            ['main_title', (config.main_title || defaultConfig.main_title).replace(/<br>/g, ' ')],
            ['subtitle', config.subtitle || defaultConfig.subtitle]
          ])
        });
      }
    }

    // Smooth scroll for navigation
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth' });
        }
      });
    });

    // Initialize
    initApp();
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9ceda36d0761ba11',t:'MTc3MTI1MTEzMC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

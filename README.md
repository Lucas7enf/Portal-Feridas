<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Guia de Feridas</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#e94560">

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Manifest gerado via JS -->
  <script>
    const manifest = {
      name: "Guia de Feridas",
      short_name: "Feridas",
      start_url: ".",
      display: "standalone",
      background_color: "#1a1a2e",
      theme_color: "#e94560",
      icons: [
        {
          src: "https://cdn-icons-png.flaticon.com/512/2966/2966486.png",
          sizes: "512x512",
          type: "image/png"
        }
      ]
    };

    const manifestBlob = new Blob(
      [JSON.stringify(manifest)],
      { type: "application/json" }
    );

    const manifestURL = URL.createObjectURL(manifestBlob);
    const link = document.createElement("link");
    link.rel = "manifest";
    link.href = manifestURL;
    document.head.appendChild(link);
  </script>

  <style>
    body { font-family: Arial, sans-serif; }
  </style>
</head>

<body class="min-h-screen text-white"
      style="background: linear-gradient(135deg,#1a1a2e,#16213e,#0f3460)">

  <div class="p-6 max-w-xl mx-auto text-center">
    <h1 class="text-3xl font-bold mb-4">Guia de Feridas</h1>
    <p class="mb-6 text-slate-300">
      Identifique o tipo de ferida e saiba o que evitar
    </p>

    <button onclick="alert('Corte selecionado')"
      class="w-full mb-3 p-4 rounded-xl bg-red-500">
      Corte
    </button>

    <button onclick="alert('Queimadura selecionada')"
      class="w-full mb-3 p-4 rounded-xl bg-orange-500">
      Queimadura
    </button>

    <button onclick="alert('Perfuração selecionada')"
      class="w-full mb-3 p-4 rounded-xl bg-purple-500">
      Perfuração
    </button>

    <p class="mt-6 text-sm text-red-300">
      ⚠️ Em casos graves, procure atendimento médico.
    </p>
  </div>

  <!-- Service Worker embutido -->
  <script>
    if ("serviceWorker" in navigator) {
      const swCode = `
        const CACHE = "guia-feridas-v1";
        self.addEventListener("install", e => {
          e.waitUntil(
            caches.open(CACHE).then(c => c.addAll(["./"]))
          );
        });
        self.addEventListener("fetch", e => {
          e.respondWith(
            caches.match(e.request).then(r => r || fetch(e.request))
          );
        });
      `;

      const swBlob = new Blob([swCode], { type: "text/javascript" });
      const swURL = URL.createObjectURL(swBlob);

      navigator.serviceWorker.register(swURL);
    }
  </script>

</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Carregando...</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #000;
      color: #00ffff;
      font-family: Arial, sans-serif;
      font-size: 32px;
    }

    .dots::after {
      content: '';
      animation: dots 1.5s steps(4, end) infinite;
    }

    @keyframes dots {
      0% { content: ''; }
      25% { content: '.'; }
      50% { content: '..'; }
      75% { content: '...'; }
      100% { content: ''; }
    }

    .hidden {
      display: none;
      font-size: 48px;
      text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff;
    }
  </style>
</head>
<body>
  <div id="loading">Carregando<span class="dots"></span></div>
  <div id="nada" class="hidden">NADA</div>

  <script>
    setTimeout(() => {
      document.getElementById("loading").style.display = "none";
      document.getElementById("nada").style.display = "block";
    }, 4000);
  </script>
</body>
</html>

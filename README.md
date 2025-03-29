<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Landing Page Modelo</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }

    body {
      background-color: #f4f4f4;
      color: #333;
      text-align: center;
    }

    header {
      background: linear-gradient(135deg, #0a0a23, #0055ff);
      color: white;
      padding: 3rem 1rem;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    section {
      padding: 2.5rem;
      margin: 1.5rem auto;
      max-width: 900px;
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    section:hover {
      transform: scale(1.02);
    }

    h2 {
      color: #0a0a23;
    }

    .cta-button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.75rem 1.5rem;
      background: linear-gradient(135deg, #0055ff, #003ecc);
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .cta-button:hover {
      transform: scale(1.1);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
    }

    footer {
      text-align: center;
      font-size: 0.9rem;
      padding: 1.5rem;
      color: #888;
      background-color: #0a0a23;
      color: white;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    ul li {
      margin-bottom: 0.5rem;
    }

    ul li a {
      color: #0055ff;
      text-decoration: none;
      font-weight: bold;
    }

    ul li a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>AQUILA MENDES</h1>
    <p>Tecnologia, Informações e Tutoriais.</p>
  </header>

  <section>
    <h2>Links de Download</h2>
    <p>Acesse recursos e materiais exclusivos para aprimorar seus conhecimentos.</p>
    <a class="cta-button" href="#">Baixar Agora</a>
  </section>

  <section>
    <h2>Redes Sociais</h2>
    <p>Siga-me nas plataformas:</p>
    <ul>
      <li><a href="https://www.youtube.com/@aquila_mendes/featured" target="_blank">YouTube</a></li>
      <li><a href="https://www.instagram.com/aquila_mendes_channel/" target="_blank">Instagram</a></li>
      <li><a href="https://x.com/DevAquila" target="_blank">Twitter (X)</a></li>
      <li><a href="https://t.me/+BpWzdmDED805ZjI5" target="_blank">Telegram</a></li>
      <li><a href="https://www.tiktok.com/@aquila.mendes7" target="_blank">TikTok</a></li>
    </ul>
  </section>

  <footer>
    <p>2025 © Liberta. Todos os direitos reservados.</p>
  </footer>
</body>
</html>

# liug-store
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LIUG - Streetwear Real</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #0a0a0a;
      color: #fff;
    }
    header {
      background-color: #121212;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 2rem;
      font-weight: bold;
      background: linear-gradient(to bottom, #003366, #3399ff);
      -webkit-background-clip: text;
      color: transparent;
    }
    nav a {
      color: #fff;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      height: 80vh;
      background: url('https://images.unsplash.com/photo-1618375531914-b6b08a6e2f3c?auto=format&fit=crop&w=1950&q=80') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 2rem;
    }
    .hero h1 {
      font-size: 3rem;
      background: linear-gradient(to bottom, #003366, #3399ff);
      -webkit-background-clip: text;
      color: transparent;
    }
    .desc {
      max-width: 700px;
      margin: 3rem auto;
      text-align: center;
      font-size: 1.2rem;
      line-height: 1.6;
    }
    .personalizador {
      background: #1a1a1a;
      padding: 2rem;
      text-align: center;
    }
    .personalizador input, .personalizador select {
      padding: 0.6rem;
      margin: 0.5rem;
      border-radius: 5px;
      border: none;
    }
    .footer {
      background: #121212;
      padding: 2rem;
      text-align: center;
      font-size: 0.9rem;
      color: #aaa;
    }
    .social-links a {
      margin: 0 10px;
      color: #3399ff;
      text-decoration: none;
    }
    .carrinho {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #3399ff;
      color: white;
      padding: 0.8rem 1.2rem;
      border-radius: 50px;
      font-weight: bold;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">LI<br>UG</div>
    <nav>
      <a href="#">Home</a>
      <a href="#sobre">Sobre</a>
      <a href="#personalizar">Personalizar</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Vive o corre, veste a atitude.</h1>
  </section>

  <section class="desc" id="sobre">
    <p>
      A LIUG não é só roupa, é postura. Nasceu da rua, pra quem faz o corre e não abaixa a cabeça. 
      Estilo pesado, sem fingimento. Aqui é identidade, é presença, é voz.
    </p>
  </section>

  <section class="personalizador" id="personalizar">
    <h2>Monte seu estilo</h2>
    <form>
      <input type="text" placeholder="Seu nome ou tag">
      <select>
        <option>Cor da peça</option>
        <option>Preto</option>
        <option>Branco</option>
        <option>Azul</option>
        <option>Vermelho</option>
      </select>
      <select>
        <option>Tamanho</option>
        <option>P</option>
        <option>M</option>
        <option>G</option>
        <option>GG</option>
      </select>
      <br>
      <button style="margin-top: 1rem; padding: 0.8rem 1.5rem; border: none; background: #3399ff; color: #fff; font-weight: bold; border-radius: 5px;">Criar minha peça</button>
    </form>
  </section>

  <footer class="footer">
    <div class="social-links">
      <a href="https://www.instagram.com" target="_blank">Instagram</a>
      <a href="https://www.tiktok.com" target="_blank">TikTok</a>
      <a href="https://www.whatsapp.com" target="_blank">WhatsApp</a>
    </div>
    <p>© 2025 LIUG. Todos os direitos reservados.</p>
  </footer>

  <div class="carrinho">
    Carrinho (0)
  </div>
</body>
</html>




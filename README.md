<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Delícia Lanches - Lanches Gourmet</title>
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      font-family: Arial, sans-serif;
      background: #0f0f0f;
      color: #eee;
      line-height: 1.6;
    }
    header {
      background: #1a1a1a;
      padding: 25px;
      text-align: center;
      position: fixed;
      width: 100%;
      top: 0;
      border-bottom: 5px solid #ff6600;
      z-index: 100;
    }
    .logo {
      font-size: 36px;
      color: #ff6600;
      font-weight: bold;
    }
    .hero {
      background: linear-gradient(rgba(0,0,0,0.85), rgba(0,0,0,0.85)), 
                  url('https://images.unsplash.com/photo-1565299623641-0c4a4f3d0f4f?w=1600') center/cover;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      margin-top: 85px;
    }
    h1 { font-size: 3.8rem; color: #ff6600; margin-bottom: 15px; }
    .subtitle { font-size: 1.9rem; margin-bottom: 30px; }
    .btn {
      background: #ff6600;
      color: #000;
      padding: 18px 45px;
      font-size: 1.5rem;
      font-weight: bold;
      border-radius: 50px;
      text-decoration: none;
      margin-top: 30px;
      display: inline-block;
    }
    section { padding: 90px 20px; text-align: center; }
    h2 { color: #ff6600; font-size: 2.8rem; margin-bottom: 50px; }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 25px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .card {
      background: #1a1a1a;
      border-radius: 15px;
      overflow: hidden;
      border: 2px solid #333;
    }
    .card:hover { border-color: #ff6600; transform: translateY(-8px); }
    .card img { 
      width: 100%; 
      height: 220px; 
      object-fit: cover; 
    }
    .price { color: #ff6600; font-size: 2rem; font-weight: bold; }
    footer { 
      padding: 50px 20px; 
      background: #0a0a0a; 
      border-top: 4px solid #ff6600;
    }
    .whatsapp {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: #25D366;
      color: white;
      width: 70px;
      height: 70px;
      border-radius: 50%;
      font-size: 36px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      box-shadow: 0 5px 20px rgba(0,0,0,0.6);
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">🍔 DELÍCIA LANCHES</div>
  </header>

  <section class="hero">
    <div>
      <h1>LANCHES GOSTOSOS E RÁPIDOS</h1>
      <p class="subtitle">O melhor sabor da cidade!</p>
      <a href="#lanches" class="btn">VER CARDÁPIO</a>
    </div>
  </section>

  <section id="lanches">
    <h2>Nossos Lanches em Destaque</h2>
    <div class="products">

      <!-- Troque as imagens aqui -->
      <div class="card">
        <img src="https://images.unsplash.com/photo-1565299623641-0c4a4f3d0f4f?w=800" alt="X-Tudo">
        <div style="padding:25px;">
          <h3>X-Tudo Gourmet</h3>
          <p>Hambúrguer, queijo, bacon, ovo, alface e tomate</p>
          <p class="price">R$ 18,90</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1553979459-d2229dfd78dc?w=800" alt="Hot Dog">
        <div style="padding:25px;">
          <h3>Hot Dog Especial</h3>
          <p>Salsicha, milho, batata palha, molhos especiais</p>
          <p class="price">R$ 14,90</p>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1614252369475-5319f9e0c3a0?w=800" alt="Sanduíche">
        <div style="padding:25px;">
          <h3>Frango com Catupiry</h3>
          <p>Peito de frango, catupiry, bacon e molho</p>
          <p class="price">R$ 16,90</p>
        </div>
      </div>

    </div>
  </section>

  <footer>
    <p><strong>📍 Seu Endereço Aqui</strong><br>
       📞 (11) 99999-9999<br>
       🕒 Aberto todos os dias das 18h às 23h</p>
    <p style="margin-top:20px;">&copy; 2026 Delícia Lanches - Feito com ❤️</p>
  </footer>

  <!-- Botão WhatsApp -->
  <a href="https://wa.me/5511999999999" target="_blank" class="whatsapp">💬</a>

</body>
</html>

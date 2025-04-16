<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alanbique - Pinga de Respeito, Feita no Capricho</title>
  <style>
    /* Reset e estilos básicos */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #3c3c3c;
      line-height: 1.6;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    /* Cabeçalho */
    header {
      background-color: #4e2a84;
      color: white;
      text-align: center;
      padding: 20px 10px;
    }
    header h1 {
      margin-bottom: 5px;
      font-size: 2em;
    }
    header p {
      font-size: 1.2em;
    }
    /* Menu de navegação */
    nav {
      background-color: #333;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav ul li {
      margin: 0;
    }
    nav ul li a {
      padding: 14px 20px;
      display: block;
      color: white;
      font-weight: bold;
    }
    nav ul li a:hover {
      background-color: #ddd;
      color: #333;
    }
    /* Container principal */
    .container {
      padding: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    h2, h3 {
      margin-bottom: 15px;
      text-align: center;
    }
    /* Produtos */
    .product {
      background-color: white;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
      margin-bottom: 20px;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
    }
    .product img {
      width: 100%;
      max-width: 150px;
      object-fit: cover;
    }
    .product-info {
      flex: 1;
      padding: 15px;
    }
    .product-info h3 {
      margin-bottom: 10px;
      font-size: 1.5em;
    }
    .product-info p {
      margin-bottom: 10px;
      color: #666;
    }
    .product-info .price {
      font-size: 1.2em;
      color: #e94e77;
      font-weight: bold;
    }
    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px 10px;
      margin-top: 30px;
    }
    footer a {
      color: #e94e77;
      font-weight: bold;
    }
    /* Responsivo */
    @media (max-width: 768px) {
      .product {
        flex-direction: column;
        text-align: center;
      }
      .product img {
        margin: 0 auto;
      }
      .product-info {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Alanbique</h1>
    <p>Pinga de Respeito, Feita no Capricho</p>
  </header>

  <nav>
    <ul>
      <li><a href="#home">Início</a></li>
      <li><a href="#shop">Loja</a></li>
      <li><a href="#about">Sobre</a></li>
      <li><a href="#contact">Contato</a></li>
    </ul>
  </nav>

  <div class="container" id="shop">
    <h2>Loja Alanbique</h2>
    
    <!-- Seção: Acessórios -->
    <h3>Acessórios</h3>
    <!-- Aqui você pode adicionar os produtos de acessórios quando tiver as informações e imagens correspondentes -->
    
    <!-- Seção: Bebidas -->
    <h3>Bebidas</h3>
    
    <!-- Produto: Pinga de Rapadura -->
    <div class="product">
      <img src="img/pinga-rapadura.jpg" alt="Pinga de Rapadura">
      <div class="product-info">
        <h3>Pinga de Rapadura</h3>
        <p>Deliciosa pinga feita com rapadura, trazendo o sabor doce e a tradição do campo.</p>
        <p class="price">R$ 42,00</p>
      </div>
    </div>

    <!-- Produto: Pinga de Mel -->
    <div class="product">
      <img src="img/pinga-mel.jpg" alt="Pinga de Mel">
      <div class="product-info">
        <h3>Pinga de Mel</h3>
        <p>Combinação perfeita de pinga e mel, resultando em um sabor suave e adocicado.</p>
        <p class="price">R$ 21,00</p>
      </div>
    </div>

    <!-- Produto: Pinga de Canela -->
    <div class="product">
      <img src="img/pinga-canela.jpg" alt="Pinga de Canela">
      <div class="product-info">
        <h3>Pinga de Canela</h3>
        <p>A mistura única de canela e pinga, com um toque quente e picante.</p>
        <p class="price">R$ 21,00</p>
      </div>
    </div>

    <!-- Produto: Pinga de Banana -->
    <div class="product">
      <img src="img/pinga-banana.jpg" alt="Pinga de Banana">
      <div class="product-info">
        <h3>Pinga de Banana</h3>
        <p>Uma experiência saborosa com o doce sabor da banana na sua pinga artesanal.</p>
        <p class="price">R$ 21,00</p>
      </div>
    </div>

    <!-- Produto: Mel Emburana -->
    <div class="product">
      <img src="img/mel-emburana.jpg" alt="Mel Emburana">
      <div class="product-info">
        <h3>Mel Emburana</h3>
        <p>Mel de emburana, com um sabor exótico e aromático, direto das colmeias artesanais.</p>
        <p class="price">R$ 37,00</p>
      </div>
    </div>

    <!-- Produto: Pinga Salinas -->
    <div class="product">
      <img src="img/pinga-salinas.jpg" alt="Pinga Salinas">
      <div class="product-info">
        <h3>Pinga Salinas</h3>
        <p>Pinga de alta qualidade, com sabor suave e um toque da tradição das salinas.</p>
        <p class="price">R$ 37,00</p>
      </div>
    </div>
  
  </div>

  <footer id="contact">
    <p>Para pedidos, entre em contato pelo WhatsApp: <a href="tel:+5511989044051">11 98904-4051</a></p>
    <p>Siga-nos no Instagram: <a href="https://www.instagram.com/alanbique19" target="_blank">@alanbique19</a></p>
  </footer>
</body>
</html>

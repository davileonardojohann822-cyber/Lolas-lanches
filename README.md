# Lolas-lanches
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LOLA's Lanches e Açaíteria</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
<style>
  body {
    margin: 0;
    font-family: 'Montserrat', sans-serif;
    background: #fff0e6;
    color: #333;
  }
  header {
    background: linear-gradient(90deg, #ff6f61, #ffb347);
    color: white;
    text-align: center;
    padding: 25px 10px;
  }
  header h1 {
    margin: 0;
    font-size: 28px;
  }
  header p {
    margin: 5px 0 0 0;
    font-size: 14px;
  }
  .container {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .category {
    width: 100%;
    margin-bottom: 30px;
  }
  .category h2 {
    color: #ff6f61;
    border-bottom: 2px solid #ff6f61;
    padding-bottom: 5px;
    margin-bottom: 15px;
  }
  .card {
    background: white;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    padding: 15px 20px;
    margin: 10px;
    flex: 1 1 250px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    transition: transform 0.2s;
  }
  .card:hover {
    transform: scale(1.05);
  }
  .item-name {
    font-weight: 600;
  }
  .item-price {
    font-weight: bold;
    color: #ff6f61;
  }
  .whatsapp-btn {
    display: block;
    text-align: center;
    margin: 30px 0;
  }
  .whatsapp-btn a {
    background: #25D366;
    color: white;
    text-decoration: none;
    padding: 18px 25px;
    border-radius: 15px;
    font-size: 20px;
    font-weight: bold;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    transition: transform 0.2s;
  }
  .whatsapp-btn a:hover {
    transform: scale(1.05);
  }
  @media (max-width: 600px) {
    .card {
      flex-direction: column;
      align-items: flex-start;
    }
  }
</style>
</head>
<body>

<header>
  <h1>LOLA's Lanches e Açaíteria</h1>
  <p>Cora Coralina, 1319 – Santos Dumont, São Leopoldo</p>
</header>

<div class="container">

  <div class="category">
    <h2>Pratos 🍽️</h2>
    <div class="card"><span class="item-name">Ala Minuta de Frango</span><span class="item-price">R$25,00</span></div>
    <div class="card"><span class="item-name">Ala Minuta de Gado</span><span class="item-price">R$25,00</span></div>
  </div>

  <div class="category">
    <h2>Lanches 🍔</h2>
    <div class="card"><span class="item-name">Xis Salada</span><span class="item-price">R$20,00</span></div>
    <div class="card"><span class="item-name">Xis Bacon</span><span class="item-price">R$25,00</span></div>
    <div class="card"><span class="item-name">Xis Frango</span><span class="item-price">R$22,00</span></div>
    <div class="card"><span class="item-name">Xis Calabresa</span><span class="item-price">R$23,00</span></div>
    <div class="card"><span class="item-name">Xis Acebolado</span><span class="item-price">R$24,00</span></div>
    <div class="card"><span class="item-name">Xis Tudo</span><span class="item-price">R$32,00</span></div>
    <div class="card"><span class="item-name">Cachorro Quente Simples</span><span class="item-price">R$15,00</span></div>
    <div class="card"><span class="item-name">Cachorro Quente Duplo</span><span class="item-price">R$17,00</span></div>
  </div>

  <div class="category">
    <h2>Pastéis 🥟</h2>
    <div class="card"><span class="item-name">Pastel de Carne</span><span class="item-price">R$15,00</span></div>
    <div class="card"><span class="item-name">Pastel de Frango</span><span class="item-price">R$15,00</span></div>
    <div class="card"><span class="item-name">Pastel de Strogonoff</span><span class="item-price">R$19,00</span></div>
  </div>

  <div class="category">
    <h2>Batatas 🍟</h2>
    <div class="card"><span class="item-name">Batata Frita P</span><span class="item-price">R$15,00</span></div>
    <div class="card"><span class="item-name">Batata Frita M</span><span class="item-price">R$20,00</span></div>
    <div class="card"><span class="item-name">Batata Frita G</span><span class="item-price">R$25,00</span></div>
  </div>

  <div class="category">
    <h2>Açaí 🍧</h2>
    <div class="card"><span class="item-name">Açaí 300ml</span><span class="item-price">R$13,00</span></div>
    <div class="card"><span class="item-name">Açaí 500ml</span><span class="item-price">R$17,00</span></div>
    <div class="card"><span class="item-name">Açaí 700ml</span><span class="item-price">R$23,00</span></div>
  </div>

  <div class="whatsapp-btn">
    <a href="https://wa.me/5551992961070" target="_blank">📲 Fazer Pedido no WhatsApp</a>
  </div>

</div>

</body>
</html>

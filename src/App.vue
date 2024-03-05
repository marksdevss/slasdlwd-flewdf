<template>
  <div class="vlone">
  <div>
    <div class="navbar">
    <img src='../assets/vlone.png' class="logo" alt="Logo">
    <ul class="nav-links">
      <li><a href="#">Vlone Shop</a></li>
      <button id="toggle-btn">Modo Noturno</button>

    </ul>
  </div>
  </div>
  </div>
  <br>
  <br>

  <div class="container">
  <div class="row">
    <div class="col-12 col-sm-8 col-md-6 col-lg-4">
      <div class="card">
        </div>
      </div>
    </div>
  </div>
  <br>
  <br>
  <br>
  <br>
  <br>

  <div class="card">
  <img src="https://cdn.awsli.com.br/257/257889/produto/189426228/a592fa9c63.jpg" alt="Imagem 1" class="card-img">
  <div class="card-content">
    <h3 class="card-title">VLONE x POP SMOKE - Camiseta Hawk Em' "Branco" </h3>
    <p class="card-text">R$ 955,00</p>
    <a href="https://www.shop-pineapple.co/vlone-x-pop-smoke-camiseta-hawk-em-branco-novo-" class="card-link">Link</a>
  </div>
</div>
<br>
<br>

<div class="card">
  <img src="https://alakazambrasil.com/cdn/shop/files/0B5DA86B-1FFC-48EC-BEA7-80FDE9F2B6F0.jpg?v=1695383634" alt="Imagem 2" class="card-img">
  <div class="card-content">
    <h3 class="card-title">Camiseta Vlone - Flame On!</h3>
    <p class="card-text">R$179.00</p>
    <a href="https://alakazambrasil.com/products/camiseta-vlone-flame-on" class="card-link">Link</a>
  </div>
</div>
<br>
<br>
<div class="card">
  <img src="https://images.yampi.io/unsafe/fit-in/700x700/filters:background_color(white):upscale()/https://images.yampi.me/assets/stores/alpha-connect/uploads/images/camiseta-vlone-x-the-woo-pp-xs-branco-642c3b7711659-large.jpg" alt="Imagem 2" class="card-img">
  <div class="card-content">
    <h3 class="card-title">Camiseta Vlone x The Woo - Alpha Connect</h3>
    <p class="card-text">R$ 69,34</p>
    <a href="https://alphaconnect.com.br/camiseta-vlone-x-the-woo/p" class="card-link">Link</a>
  </div>
</div>

<div class="card">
  <img src="https://cdn.awsli.com.br/600x1000/1100/1100536/produto/166081507/288c98f37b.jpg" alt="Imagem 3" class="card-img">
  <div class="card-content">
    <h3 class="card-title">Camiseta Vlone Black Panther Preta</h3>
    <p class="card-text">R$ 169.90</p>
    <a href="https://www.boutique01.com.br/camiseta-vlone-black-panther-preta" class="card-link">Link</a>
  </div>
<br>
<br>

<div class="card">
  <img src="https://lojagoldstreet.com/cdn/shop/files/52a22676.jpg?v=1688262639" alt="Imagem 4" class="card-img">
  <div class="card-content">
    <h3 class="card-title">Camiseta Vlone "Staple White/Green"</h3>
    <p class="card-text">R$ 299.00</p>
    <a href="https://lojagoldstreet.com/products/camiseta-vlone-staple-white-green" class="card-link">Link</a>
  </div>
</div>
<br>
<br>
<div class="card">
  <img src="https://acdn.mitiendanube.com/stores/002/280/944/products/2a5c0628-75ba-48dd-a01e-b338c724ab571-eef46a57e48f35d86b16751894235858-640-0.webp" alt="Imagem 4" class="card-img">
  <div class="card-content">
    <h3 class="card-title">Camiseta Vlone Pop Smoke</h3>
    <p class="card-text">R$65,00</p>
    <a href="https://www.bigodewear.com.br/produtos/camiseta-vlone-pop-smoke/" class="card-link">Link</a>
  </div>
</div>
</div>
  <br>
  <br>
  <br>
  <br>
  <br>
<footer class="footer">
  <div class="footer-bottom">
    <p>&copy; 2024 VloneStore. Todos os direitos reservados.</p>
  </div>
</footer>
  </template>


<style scoped>
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #000; 
  padding: 10px 20px; 
}

.logo {
  width: 100px; 
}

.nav-links {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
}

.nav-links li {
  margin-right: 20px; 
}

.nav-links li:last-child {
  margin-right: 0; 
}

.nav-links li a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
  font-size: 16px; 
  text-align: center;
}

.card {
  width: 300px;
  background-color: #fff;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  overflow: hidden;
  margin: 20px;
}

.card-img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.card-content {
  padding: 20px;
}

.card-title {
  font-size: 20px;
  margin-bottom: 10px;
}

.card-text {
  color: #555;
  margin-bottom: 15px;
}

.card-link {
  display: inline-block;
  padding: 8px 16px;
  background-color: #007bff;
  color: #fff;
  text-decoration: none;
  border-radius: 4px;
  transition: background-color 0.3s ease;
}

.card-link:hover {
  background-color: #0056b3;
}



.footer {
  background-color: #333;
  color: #fff;
  padding: 30px 0;
}

.footer-content {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.footer-section {
  margin-bottom: 20px;
}

.footer-bottom p
{
text-align: center;
}


.dark-mode {
  background-color: #333;
  color: #fff;
}

</style>

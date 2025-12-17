<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BlueBerry Pais - Arándanos Frescos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fafafa;
      color: #333;
    }
    header {
      background: #005f73;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #0a9396;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }
    .productos {
      display: flex;
      gap: 20px;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .producto {
      background: white;
      padding: 15px;
      border: 1px solid #ccc;
      border-radius: 8px;
      width: 30%;
      min-width: 200px;
      text-align: center;
    }
    .producto img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .precio {
      font-size: 1.4em;
      color: #e63946;
      margin-top: 10px;
    }
    footer {
      background: #005f73;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

<header>
  <h1>BlueBerry Pais</h1>
  <p>Arándanos frescos de calidad — Directo a Londres, Reino Unido</p>
</header>

<nav>
  <a href="#productos">Productos</a>
  <a href="#contacto">Contacto</a>
</nav>

<main>
  <section id="productos">
    <h2>Nuestros Productos</h2>
    <div class="productos">
      
      <div class="producto">
        <h3>Arándanos 125 g</h3>
        <img src="https://via.placeholder.com/200?text=Blueberries+125g" alt="Arándanos 125g">
        <p>Frescos, jugosos y llenos de antioxidantes.</p>
        <p class="precio">£2.99</p>
      </div>

      <div class="producto">
        <h3>Arándanos 250 g</h3>
        <img src="https://via.placeholder.com/200?text=Blueberries+250g" alt="Arándanos 250g">
        <p>Pack ideal para desayunos o meriendas saludables.</p>
        <p class="precio">£4.99</p>
      </div>

      <div class="producto">
        <h3>Arándanos 500 g</h3>
        <img src="https://via.placeholder.com/200?text=Blueberries+500g" alt="Arándanos 500g">
        <p>Perfecto para familias o uso en recetas.</p>
        <p class="precio">£8.99</p>
      </div>

    </div>
  </section>

  <section id="contacto" style="margin-top: 30px;">
    <h2>Contacto</h2>
    <p>📍 Ubicación: Londres, Reino Unido</p>
    <p>📧 Email: ventas@blueberrypais.co.uk</p>
    <p>📱 WhatsApp: +44 7700 900123</p>
  </section>
</main>

<footer>
  <p>© 2025 BlueBerry Pais — Todos los derechos reservados.</p>
</footer>

</body>
</html>

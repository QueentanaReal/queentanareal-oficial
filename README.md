<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Queentana Real</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      margin: 0;
      padding: 0;
      background-color: #fff; /* Blanco limpio */
      color: #333;
      text-align: center;
    }
    header {
      background-color: #000; /* Fondo negro elegante */
      padding: 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #d4af37; /* Dorado */
    }
    header p {
      color: #fff; /* Texto blanco */
      margin: 5px 0 0;
    }
    section {
      padding: 30px 20px;
    }
    h2 {
      color: #d4af37; /* Dorado */
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .producto {
      background-color: #fff;
      border: 2px solid #d4af37; /* Borde dorado */
      border-radius: 12px;
      padding: 15px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s ease-in-out;
    }
    .producto:hover {
      transform: scale(1.05);
    }
    .producto h3 {
      color: #000;
      margin-bottom: 10px;
    }
    .producto p {
      color: #444;
    }
    footer {
      background-color: #000;
      padding: 15px;
      margin-top: 30px;
    }
    footer p {
      color: #fff;
      margin-bottom: 10px;
    }
    footer a {
      margin: 0 10px;
      text-decoration: none;
      color: #d4af37; /* Dorado */
      font-weight: bold;
    }
    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Queentana Real</h1>
    <p>Repostería con un toque de realeza</p>
  </header>

  <section>
    <h2>🍰 Nuestros Productos</h2>
    <div class="productos">
      <div class="producto">
        <h3>Carlotas</h3>
        <p>$30 c/u</p>
        <p>Con topping: $35</p>
      </div>
      <div class="producto">
        <h3>Gelatinas</h3>
        <p>$12 c/u</p>
      </div>
      <div class="producto">
        <h3>Galletas</h3>
        <p>Próximamente ✨</p>
      </div>
      <div class="producto">
        <h3>Cupcakes</h3>
        <p>Próximamente ✨</p>
      </div>
    </div>
  </section>

  <footer>
    <p>Síguenos en redes sociales:</p>
    <a href="https://instagram.com/TU-CUENTA" target="_blank">Instagram</a>
    <a href="https://facebook.com/TU-CUENTA" target="_blank">Facebook</a>
    <a href="https://tiktok.com/@TU-CUENTA" target="_blank">TikTok</a>
  </footer>
</body>
</html>

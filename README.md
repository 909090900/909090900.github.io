<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ver ESPN en Vivo</title>
  <meta name="description" content="Disfruta de ESPN en vivo en nuestra página web">
  <link rel="icon" type="image" href="/img/logo.png">
</head>

<body>
  <header>
    <h1>ESPN en Vivo</h1>
  </header>

  <main>
    <!-- Botón para cargar el canal -->
    <button id="showChannelBtn">Ver ESPN en Vivo</button>

    <!-- Contenedor donde se cargará el iframe de ESPN -->
    
      <iframe src="https://la12hd.com/vivo/canal.php?stream=espn"
             
              width="100%" 
              height="600"
              frameborder="0"
         
              loading="lazy"
              allowfullscreen="true">
      </iframe>
    </div>

    <!-- Botón para volver al menú -->
    <div id="backToMenuBtnContainer" style="display:none;">
      <button id="backToMenuBtn" onclick="window.location.href='/'">Volver al Menú</button>
    </div>
  </main>

  <footer>
    <span>&copy; 2025 Mi Página Web</span>
  </footer>
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Transmisión en Vivo - Canales</title>
  <meta name="description" content="Disfruta de tus canales favoritos en vivo directamente en nuestra página web.">
  <link rel="icon" href="/img/logo.png" type="image/png">
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    header, footer {
      text-align: center;
      padding: 10px;
    }
    .canales-lista {
      list-style-type: none;
      padding: 0;
    }
    .canales-lista li {
      margin: 10px 0;
    }
    .video-container {
      margin: 20px auto;
      width: 80%;
    }
    iframe {
      width: 100%;
      height: 600px;
      border: none;
    }
  </style>
</head>

<body>

 

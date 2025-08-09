<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mis Redes - Galard</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: url("img/galard_fondo.jpg") repeat;
      background-size: 200px; /* tamaño del papel tapiz */
      text-align: center;
      padding: 30px;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      backdrop-filter: blur(2px);
    }
    h1 {
      margin-bottom: 25px;
      font-size: 1.8rem;
      color: #4CAF50; /* verde suave */
      text-shadow: 0 0 6px rgba(0,0,0,0.4);
      font-weight: bold;
    }
    .links {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 320px;
      margin: 0 auto;
    }
    .link {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      text-decoration: none;
      padding: 15px;
      border-radius: 50px;
      color: #4CAF50;
      font-size: 1.1rem;
      font-weight: bold;
      border: 2px solid #4CAF50;
      background-color: rgba(255,255,255,0.6);
      transition: transform 0.2s ease, background-color 0.2s ease, box-shadow 0.3s ease;
    }
    .link:hover {
      transform: scale(1.08);
      background-color: rgba(255,255,255,0.85);
      box-shadow: 0 0 15px rgba(76, 175, 80, 0.7);
    }
    i {
      font-size: 1.4rem;
      color: #4CAF50;
      transition: color 0.3s ease, text-shadow 0.3s ease;
    }
    .link:hover i {
      color: #4CAF50;
      text-shadow: 0 0 10px rgba(76, 175, 80, 0.8);
    }
  </style>
</head>
<body>
  <h1>Hola soy Galard, Sígueme en todas mis redes</h1>
  <div class="links">
    <a class="link" href="https://www.facebook.com/profile.php?id=61568976388699" target="_blank">
      <i class="fab fa-facebook-f"></i> Facebook
    </a>
    <a class="link" href="https://www.youtube.com/@GalardGr33n" target="_blank">
      <i class="fab fa-youtube"></i> YouTube
    </a>
    <a class="link" href="https://instagram.com/TU_USUARIO" target="_blank">
      <i class="fab fa-instagram"></i> Instagram
    </a>
    <a class="link" href="https://open.spotify.com/show/11XEPyDlbUvOsW4PhaGBsS?si=b9ab4f6aff8d46b1" target="_blank">
      <i class="fab fa-spotify"></i> Spotify
    </a>
    <a class="link" href="https://x.com/TU_USUARIO" target="_blank">
      <i class="fab fa-x-twitter"></i> X (Twitter)
    </a>
  </div>
</body>
</html>

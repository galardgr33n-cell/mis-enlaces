<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mis Enlaces - Galard</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: #000814;
      text-align: center;
      padding: 30px;
      color: white;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    h1 {
      margin-bottom: 25px;
      font-size: 1.8rem;
      color: #00f0ff;
      text-shadow: 0 0 8px #00f0ff, 0 0 16px #00f0ff;
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
      color: white;
      font-size: 1.1rem;
      font-weight: bold;
      box-shadow: 0 0 10px rgba(0,255,170,0.8), 0 0 20px rgba(0,170,255,0.6);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .link:hover {
      transform: scale(1.08);
      box-shadow: 0 0 20px rgba(0,255,170,1), 0 0 30px rgba(0,170,255,1);
    }
    .facebook { background: rgba(0,255,170,0.15); }
    .youtube { background: rgba(0,170,255,0.15); }
    .instagram { background: rgba(0,255,170,0.15); }
    .spotify { background: rgba(0,170,255,0.15); }
    .twitter { background: rgba(0,255,170,0.15); }
    i {
      font-size: 1.4rem;
    }
  </style>
</head>
<body>
  <h1>✨ Hola soy Galard, sígueme en mis redes ✨</h1>
  <div class="links">
    <a class="link facebook" href="https://www.facebook.com/profile.php?id=61568976388699" target="_blank">
      <i class="fab fa-facebook-f"></i> Facebook
    </a>
    <a class="link youtube" href="https://www.youtube.com/@GalardGr33n" target="_blank">
      <i class="fab fa-youtube"></i> YouTube
    </a>
    <a class="link instagram" href="https://instagram.com/TU_USUARIO" target="_blank">
      <i class="fab fa-instagram"></i> Instagram
    </a>
    <a class="link spotify" href="https://open.spotify.com/show/11XEPyDlbUvOsW4PhaGBsS?si=b9ab4f6aff8d46b1" target="_blank">
      <i class="fab fa-spotify"></i> Spotify
    </a>
    <a class="link twitter" href="https://x.com/TU_USUARIO" target="_blank">
      <i class="fab fa-x-twitter"></i> X (Twitter)
    </a>
  </div>
</body>
</html>

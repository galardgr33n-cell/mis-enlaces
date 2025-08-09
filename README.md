<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mis Enlaces</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(135deg, #ff5722, #ff9800);
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
      font-size: 2rem;
    }
    .links {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 300px;
      margin: 0 auto;
    }
    .link {
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      padding: 15px;
      border-radius: 50px;
      color: white;
      font-size: 1.1rem;
      font-weight: bold;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .link:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(0,0,0,0.3);
    }
    .facebook { background: #1877F2; }
    .youtube { background: #FF0000; }
    .instagram {
      background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%);
    }
    .spotify { background: #1DB954; }
    .twitter { background: #000000; }
  </style>
</head>
<body>
  <h1>🌟 Mis Redes 🌟</h1>
  <div class="links">
    <a class="link facebook" href="https://facebook.com/GalardGr33n" target="_blank">📘 Facebook</a>
    <a class="link youtube" href="https://youtube.com/GalardGr33n" target="_blank">📺 YouTube</a>
    <a class="link instagram" href="https://instagram.com/GalardGr33n" target="_blank">📸 Instagram</a>
    <a class="link spotify" href="https://open.spotify.com/user/GalardGr33n" target="_blank">🎵 Spotify</a>
    <a class="link twitter" href="https://x.com/GalardGr33n" target="_blank">🐦 X (Twitter)</a>
  </div>
</body>
</html>

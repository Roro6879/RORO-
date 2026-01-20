
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>roro - site sécurisé</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    * { box-sizing: border-box; margin:0; padding:0; }
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: radial-gradient(circle at top, #0f0c29, #302b63, #24243e);
      color: white;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 15px;
    }

    .container {
      width: 100%;
      max-width: 420px;
      text-align: center;
      position: relative;
    }

    /* Menu hamburger néon */
    .menu-toggle {
      position: absolute;
      top: 20px;
      right: 20px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      width: 35px;
      height: 25px;
      cursor: pointer;
      z-index: 10;
    }

    .menu-toggle span {
      display: block;
      height: 4px;
      background: #00ffea;
      border-radius: 2px;
      box-shadow: 0 0 10px #00ffea;
      transition: 0.3s;
    }

    .menu {
      position: absolute;
      top: 60px;
      right: 20px;
      background: rgba(0,0,0,0.95);
      border-radius: 12px;
      padding: 15px;
      display: none;
      flex-direction: column;
      gap: 12px;
      width: 160px;
      text-align: left;
      box-shadow: 0 0 20px #00ffea;
    }

    .menu a {
      color: #00ffea;
      text-decoration: none;
      font-weight: bold;
      text-shadow: 0 0 5px #00ffea;
      transition: 0.2s;
    }

    .menu a:hover {
      color: #ffffff;
      text-shadow: 0 0 15px #00ffea;
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 10px;
      text-shadow: 0 0 10px #00ffea;
    }

    p {
      margin-bottom: 25px;
      opacity: 0.9;
    }

    a.button {
      display: block;
      width: 100%;
      text-decoration: none;
      background: #0ff;
      color: black;
      padding: 16px;
      margin: 12px 0;
      border-radius: 14px;
      font-size: 1.05rem;
      font-weight: bold;
      transition: 0.2s ease, box-shadow 0.2s;
      box-shadow: 0 0 15px #00ffea;
    }

    a.button:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px #00ffea;
      background: #00fff0;
    }

    .secure {
      font-size: 0.85rem;
      opacity: 0.7;
      margin-top: 20px;
      text-shadow: 0 0 5px #00ffea;
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- Menu hamburger -->
    <div class="menu-toggle" id="menuToggle">
      <span></span>
      <span></span>
      <span></span>
    </div>
    <div class="menu" id="menu">
      <a href="#">Connexion</a>
      <a href="#">S'inscrire</a>
      <a href="#">Aide</a>
    </div>

    <h1>@roro</h1>
    <p>Site sécurisé 🔒 | Ajoute-moi 👇</p>

    <a href="https://www.snapchat.com" class="button" target="_blank">👻 Snapchat</a>
    <a href="https://gtube.com" class="button" target="_blank">🌐 GTUBE.com</a>
    <a href="https://www.instagram.com" class="button" target="_blank">📸 Instagram</a>
    <a href="https://www.playstation.com" class="button" target="_blank">🎮 PlayStation</a>

    <div class="secure">
      🔐 Connexion sécurisée (HTTPS)
    </div>
  </div>

  <script>
    const toggle = document.getElementById('menuToggle');
    const menu = document.getElementById('menu');

    toggle.addEventListener('click', () => {
      menu.style.display = (menu.style.display === 'flex') ? 'none' : 'flex';
    });
  </script>
</body>
</html>
thumbnailfavicon
Snapchat - Say It In A Snap
snapchat.com
https://gtube.com/
http://gtube.com/
thumbnailfavicon
Instagram
instagram.com
favicon
PlayStation® Official Site: Consoles, Games, Accessories & More
playstation.com# RORO-
 bon jour venez découvrir ce site incroyable mieux que mes concurrents 

# Tushak-gaming-zone

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
  <title>Tushak Gaming Zone</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: #0b0b12;
      color: white;
      font-family: Arial, sans-serif;
    }
    header {
      text-align: center;
      padding: 30px 15px;
      background: #171728;
      border-bottom: 2px solid #7c3aed;
    }
    header h1 { color: #a78bfa; }
    nav { margin-top: 20px; }
    nav a {
      color: white;
      margin: 8px;
      text-decoration: none;
    }
    main { padding: 20px; }
    .hero {
      padding: 24px;
      background: #1c1c2e;
      border-radius: 14px;
      text-align: center;
    }
    .games {
      display: grid;
      grid-template-columns:
        repeat(auto-fit, minmax(140px, 1fr));
      gap: 14px;
      margin-top: 20px;
    }
    .card {
      background: #202033;
      padding: 18px;
      border-radius: 12px;
      border: 1px solid #393952;
    }
    .card h3 { color: #a78bfa; }
    .btn {
      display: inline-block;
      padding: 11px 16px;
      background: #7c3aed;
      color: white;
      border-radius: 8px;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 25px;
      color: #b8b8c9;
    }
  </style>
</head>
<body>
  <header>
    <h1>🎮 TUSHAK GAMING ZONE</h1>
    <p>Your World of Gaming!</p>
    <nav>
      <a href="#home">Home</a>
      <a href="#games">Games</a>
      <a href="#news">News</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <h2>Welcome, Gamers! 🔥</h2>
      <p>Gaming news, updates and your favourite games.</p>
      <a class="btn" href="#games">Explore Games</a>
    </section>

    <section id="games">
      <h2>🎯 Popular Games</h2>
      <div class="games">
        <article class="card">
          <h3>Free Fire</h3>
          <p>Battle royale gaming updates.</p>
        </article>
        <article class="card">
          <h3>BGMI</h3>
          <p>News, tips and updates.</p>
        </article>
        <article class="card">
          <h3>Minecraft</h3>
          <p>Creative worlds and adventures.</p>
        </article>
        <article class="card">
          <h3>Call of Duty</h3>
          <p>Gaming news and highlights.</p>
        </article>
      </div>
    </section>

    <section id="news">
      <h2>📰 Latest Updates</h2>
      <div class="card">
        <p>Welcome to our gaming news section!</p>
        <p>New gaming updates will appear here.</p>
      </div>
    </section>
  </main>

  <footer>
    <p>Made with ❤️ by Tushak</p>
    <p>Fan website. Not affiliated with game publishers.</p>
  </footer>
</body>
</html>

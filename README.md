# hitotsubashi-ballroomdanceclub.github.io
ALL一橋競技ダンス部のHP
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ALL一橋大学競技ダンス部</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- ナビゲーションバー --!>
  <header>
    <nav class="navbar">
      <div class="logo">ALL一橋大学競技ダンス部</div>
      <ul class="nav-links">
        <li><a href="#about">活動紹介</a></li>
        <li><a href="#members">部員紹介</a></li>
        <li><a href="#contact">お問い合わせ</a></li>
      </ul>
    </nav>
  </header>

  <!-- トップ（Heroセクション） -->
  <section class="hero">
    <div class="hero-text">
      <h1>ようこそ！ALL一橋大学競技ダンス部へ</h1>
      <p>初心者から日本１へ</p>
    </div>
  </section>
hero {
  background-image: url("dance_hero.jpg");
}
  <!-- 活動紹介 -->
  <section id="about" class="section">
    <h2>活動紹介</h2>
    <p>私たちは週3回、一橋大学東体育館で練習し、大会やイベントに出場しています！</p>
  </section>

  <!-- 部員紹介 -->
  <section id="members" class="section">
    <h2>部員紹介</h2>
    <p>個性豊かな仲間たちを紹介します！
    </p>
  </section>

  <!-- お問い合わせ -->
  <section id="contact" class="section">
    <h2>お問い合わせ</h2>
    <p>見学・体験は大歓迎！お気軽にInstagramのDMまで📩</p>
  </section>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Helvetica Neue', sans-serif;
}
body {
  line-height: 1.6;
  background-color: #fff;
  color: #333;
}
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #222;
  padding: 1rem 2rem;
  position: sticky;
  top: 0;
  z-index: 10;
}
.nav-links li a {
  color: white;
  text-decoration: none;
  transition: color 0.3s;
}
.nav-links li a:hover {
  color: #f0a500;
}
.hero {
  background-image: url("your-image.jpg");
  background-size: cover;
  background-position: center;
  height: 100vh;
  ...
}
.section {
  padding: 4rem 2rem;
  max-width: 800px;
  margin: auto;
}

</head>
<body>

  <!-- お問い合わせ -->
  <section id="contact" class="section">
    <h2>お問い合わせ</h2>
    <p>見学や体験希望の方は、以下のSNSからお気軽にご連絡ください！</p>
    <ul>
      <li>📷 Instagram: <a href="https://instagram.com/your_instagram_id" target="_blank">@tsuda_dance</a></li>
      <li>✉️ メール: tsuda.dance.club@example.com</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 津田塾大学ダンス部</p>
  </footer>

</body>
</html>

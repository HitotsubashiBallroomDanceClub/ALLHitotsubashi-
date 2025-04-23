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

<head>
<style>
  body {
    margin: 0;
    padding: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    box-sizing: border-box;
    position: relative;
  }
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
<head>
<style>
  body {
    margin: 0;
    padding: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    box-sizing: border-box;
    position: relative;
  }

  .border-with-text {
    position: relative;
    width: 100%;
    height: 100%;
    border: 20px solid #ff6347; /* 枠線の太さと色 */
    box-sizing: border-box;
  }

  .border-with-text::before , .border-with-text::after {
    content: "test test test test test test test test test test";
    position: absolute;
    width: 100%;
    text-align: center;
    font-size: 16px;
    color: #fff; /* 文字の色（必要に応じて変更） */
    font-family: Arial, sans-serif;
  }

  /* 上の枠に文字を配置 */
  .border-with-text::before {
    top: -20px; /* 枠線の上に配置 */
    left: 0;
  }

  /* 下の枠に文字を配置 */
  .border-with-text::after {
    bottom: -20px; /* 枠線の下に配置 */
    left: 0;
  }

  /* 左の枠に文字を配置 */
  .left-text {
    position: absolute;
    writing-mode: vertical-lr; /* 縦書きにする */
    text-align: center;
    left: -20px; /* 枠線の外側に配置 */
    top: 0;
    height: 100%;
    font-size: 16px;
    color: #fff;
    font-family: Arial, sans-serif;
    transform: rotate(180deg); /* 内側に向かって回転 */
    transform-origin: center center; /* 回転の基準を中心に設定 */
  }

  /* 右の枠に文字を配置 */
  .right-text {
    position: absolute;
    writing-mode: vertical-rl;
    text-align: center;
    right: -20px; /* 枠線の外側に配置 */
    top: 0;
    height: 100%;
    font-size: 16px;
    color: #fff;
    font-family: Arial, sans-serif;
  }
</style>
</head>
<body>
  <div class="border-with-text">
  <!-- 左右の縁用 -->
    <div class="left-text">test test test test test test</div>
    <div class="right-text">test test test test test test</div>
  </div>
</body>
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

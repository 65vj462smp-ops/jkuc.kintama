<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>日本金玉統一教会</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@400;700&display=swap');

    :root {
      color-scheme: dark;
      color: #d4af37;
      background: #000;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html, body {
      min-height: 100%;
      background: radial-gradient(circle at top, #191919 0%, #000 60%);
      color: #d4af37;
      font-family: 'Noto Serif JP', 'Yu Mincho', 'Times New Roman', serif;
      line-height: 1.7;
    }

    body {
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
    }

    .container {
      width: min(1100px, 100%);
      backdrop-filter: blur(8px);
      border: 1px solid rgba(212, 175, 55, 0.25);
      box-shadow: 0 0 60px rgba(212, 175, 55, 0.15);
      padding: 48px;
      border-radius: 24px;
      background: rgba(10, 10, 10, 0.88);
    }

    .title {
      text-align: center;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      font-size: clamp(2.5rem, 5vw, 4.5rem);
      font-weight: 700;
      margin-bottom: 24px;
      text-shadow: 0 0 18px rgba(212, 175, 55, 0.5);
    }

    .subtitle {
      text-align: center;
      font-size: 1.05rem;
      margin-bottom: 40px;
      opacity: 0.85;
    }

    .branch {
      text-align: center;
      font-size: 0.95rem;
      letter-spacing: 0.2em;
      margin-bottom: 10px;
      opacity: 0.8;
    }

    .hero {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 32px;
      align-items: center;
    }

    .hero img {
      width: 100%;
      height: auto;
      border-radius: 20px;
      border: 2px solid rgba(212, 175, 55, 0.35);
      box-shadow: 0 0 40px rgba(212, 175, 55, 0.18);
      background: #111;
    }

    .doctrine {
      font-size: 1rem;
      padding: 28px;
      border-radius: 18px;
      border: 1px solid rgba(212, 175, 55, 0.18);
      background: rgba(18, 18, 18, 0.82);
      box-shadow: inset 0 0 20px rgba(0, 0, 0, 0.4);
    }

    .doctrine p {
      margin-bottom: 1.6rem;
    }

    .doctrine strong {
      color: #fff0b0;
    }

    .footer {
      text-align: center;
      margin-top: 40px;
      opacity: 0.7;
      font-size: 0.95rem;
    }

    .leader {
      text-align: center;
      margin-top: 14px;
      font-size: 0.9rem;
      opacity: 0.82;
      letter-spacing: 0.12em;
    }

    @media (max-width: 900px) {
      .hero {
        grid-template-columns: 1fr;
      }

      .title {
        font-size: 3rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1 class="title">日本金玉統一教会</h1>
      <p class="branch">福井県支部</p>
      <p class="subtitle">光を求め、金色の魂を結び合わせる聖なる平面の道しるべ</p>
    </header>

    <section class="hero">
      <img src="https://via.placeholder.com/900x600/111111/ffd700?text=%E6%95%99%E7%90%86%E3%81%AE%E5%9B%BE" alt="日本金玉統一教会の象徴的なイメージ">

      <article class="doctrine">
        <p><strong>教理:</strong><br>我らは黄金の心をひとつにし、永遠の統一を目指す。暗闇にあっても、信仰の光は失われず、道は常に清くあらねばならない。</p>
        <p>日本金玉統一教会は、金玉が平面であることを信じる。平面の金玉は、円形や球体と異なり、一枚の面として静かに広がる光を宿す。すべての真理はこの平面に集まり、平面の金玉こそが我らの聖なる象徴である。</p>
        <p>平面の金玉は、調和と沈静をもたらし、光を反射するのではなく、光そのものとなる。平面であるがゆえに、金玉は世界と直に接し、平面の奥行きを超えて心を結ぶ。</p>
        <p>天と地を結ぶ祈りは、すべての存在に向けられる。調和と敬虔、そして慈悲の精神が、私たちの歩みを導く。</p>
        <p>共に歩む仲間たちと真理を探求し、金色に輝き、平面の金玉の未来を築くことこそ、我らが掲げる聖なる使命である。</p>
      </article>
    </section>

    <footer class="footer">日本金玉統一教会 | 金玉平面統一のために</footer>
    <div class="leader">われらの教祖、@takechaan0 たけ様</div>
  </div>
</body>
</html>

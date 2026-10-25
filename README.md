# panther-fox-trading-new-
Panther FX Trading - Forex Education, Market Analysis and Risk Management

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Panther The 1st FX Trading</title>
<meta name="description" content="Forex education, market analysis and risk management by Panther FX Trading.">

<style>
:root {
  --bg: #080808;
  --card: #151515;
  --gold: #d4af37;
  --white: #ffffff;
  --muted: #bdbdbd;
}
* { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; }
body {
  background: var(--bg);
  color: var(--white);
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.7;
}
header {
  padding: 18px 7%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 15px;
  border-bottom: 1px solid #3b3018;
  background: #090909;
}
.logo { color: var(--gold); font-size: 20px; font-weight: 900; }
nav { display: flex; gap: 17px; flex-wrap: wrap; }
nav a { color: white; text-decoration: none; font-size: 14px; }
nav a:hover { color: var(--gold); }

.hero {
  min-height: 78vh;
  padding: 75px 7%;
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  align-items: center;
  gap: 35px;
  background: radial-gradient(ellipse at top right, #30250e, #080808 65%);
}
.eyebrow { color: var(--gold); letter-spacing: 3px; font-size: 12px; font-weight: bold; }
h1 { font-size: clamp(38px, 6vw, 66px); line-height: 1.12; margin: 18px 0; }
h1 span, h2 span { color: var(--gold); }
p { color: var(--muted); }
.hero p { max-width: 580px; }
.actions { display: flex; gap: 13px; flex-wrap: wrap; margin-top: 28px; }
.btn {
  display: inline-block;
  padding: 12px 20px;
  border-radius: 4px;
  font-weight: bold;
  text-decoration: none;
}
.gold { background: var(--gold); color: #080808; }
.outline { border: 1px solid var(--gold); color: var(--gold); }

.chart {
  min-height: 280px;
  padding: 25px;
  border: 1px solid #59451a;
  border-radius: 12px;
  background: #101010;
  box-shadow: 0 15px 50px #000;
}
.chart h3 { color: var(--gold); margin-bottom: 15px; }
.candles {
  height: 165px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  border-bottom: 1px solid #4a3b1c;
  background: repeating-linear-gradient(to bottom, transparent 0 39px, #292319 40px);
}
.candle { width: 12px; position: relative; background: var(--gold); border-radius: 2px; }
.candle::before {
  content: "";
  position: absolute;
  width: 2px;
  height: 35px;
  background: var(--gold);
  left: 5px;
  top: -17px;
}
.c1 { height: 45px; }
.c2 { height: 70px; }
.c3 { height: 35px; }
.c4 { height: 85px; }
.c5 { height: 60px; }
.c6 { height: 100px; }
.c7 { height: 75px; }
.c8 { height: 115px; }
.chart-note { margin-top: 15px; font-size: 12px; }

section { padding: 65px 7%; }
h2 { font-size: clamp(28px, 4vw, 40px); margin-bottom: 15px; }
.intro { max-width: 720px; margin-bottom: 28px; }
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 18px;
}
.card {
  background: var(--card);
  padding: 24px;
  border: 1px solid #3a301b;
  border-radius: 8px;
}
.icon { color: var(--gold); font-size: 30px; }
.card h3 { color: var(--gold); margin: 8px 0; }
.card p { font-size: 14px; }

.about { background: #101010; }
.contact { background: #101010; }
.contact a { color: var(--gold); overflow-wrap: anywhere; }
.notice { margin-top: 25px; font-size: 12px; }
footer {
  text-align: center;
  padding: 25px 7%;
  border-top: 1px solid #3b3018;
  color: var(--muted);
  font-size: 13px;
}
.whatsapp {
  position: fixed;
  right: 18px;
  bottom: 18px;
  z-index: 5;
  background: var(--gold);
  color: #080808;
  padding: 12px 17px;
  border-radius: 30px;
  font-weight: bold;
  text-decoration: none;
  box-shadow: 0 4px 18px #000;
}
@media(max-width: 760px) {
  .hero { grid-template-columns: 1fr; padding-top: 55px; }
  header { align-items: flex-start; }
  nav { gap: 12px; }
}
</style>
</head>

<body>
<header>
  <div class="logo">♠ PANTHER FX</div>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#markets">Markets</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
<section class="hero" id="home">
  <div>
    <div class="eyebrow">DISCIPLINE • STRATEGY • KNOWLEDGE</div>
    <h1>PANTHER THE 1ST<br><span>FX TRADING</span></h1>
    <p>Understand the financial markets through forex education, technical analysis and disciplined risk management.</p>
    <div class="actions">
      <a class="btn gold" href="#services">Explore Services</a>
      <a class="btn outline" href="#contact">Contact Us</a>
    </div>
  </div>

  <div class="chart">
    <h3>MARKET INSIGHT</h3>
    <div class="candles">
      <div class="candle c1"></div>
      <div class="candle c2"></div>
      <div class="candle c3"></div>
      <div class="candle c4"></div>
      <div class="candle c5"></div>
      <div class="candle c6"></div>
      <div class="candle c7"></div>
      <div class="candle c8"></div>
    </div>
    <p class="chart-note">Illustrative chart for education only. Not live market data.</p>
  </div>
</section>

<section class="about" id="about">
  <h2>About <span>Panther FX</span></h2>
  <p class="intro">Our goal is to make forex knowledge easier to understand. We focus on learning market structure, developing strategies and understanding trading risk.</p>
  <div class="grid">
    <article class="card">
      <div class="icon">♛</div>
      <h3>Our Vision</h3>
      <p>Encourage informed decisions and continuous learning about financial markets.</p>
    </article>
    <article class="card">
      <div class="icon">◆</div>
      <h3>Our Values</h3>
      <p>Discipline, patience, honesty and responsible risk management.</p>
    </article>
  </div>
</section>

<section id="services">
  <h2>Our <span>Services</span></h2>
  <p class="intro">Explore our forex learning and market education services.</p>
  <div class="grid">
    <article class="card">
      <div class="icon">⌁</div>
      <h3>Forex Education</h3>
      <p>Learn currency pairs, candlesticks, trading sessions and key market terminology.</p>
    </article>
    <article class="card">
      <div class="icon">▤</div>
      <h3>Technical Analysis</h3>
      <p>Study trends, support and resistance, liquidity and market structure.</p>
    </article>
    <article class="card">
      <div class="icon">◇</div>
      <h3>Risk Management</h3>
      <p>Understand stop-loss planning, position sizing and capital protection.</p>
    </article>
    <article class="card">
      <div class="icon">◈</div>
      <h3>Trading Psychology</h3>
      <p>Build patience, discipline and a consistent learning routine.</p>
    </article>
  </div>
</section>

<section id="markets">
  <h2>Markets We <span>Study</span></h2>
  <p class="intro">Learn how different markets move and what can influence price.</p>
  <div class="grid">
    <article class="card">
      <h3>XAUUSD — Gold</h3>
      <p>Learn to study gold price movements, key levels and market structure.</p>
    </article>
    <article class="card">
      <h3>Forex Pairs</h3>
      <p>Explore currency pairs and the possible impact of economic news.</p>
    </article>
    <article class="card">
      <h3>Market Structure</h3>
      <p>Study trends, breakouts, reversals and multiple timeframes.</p>
    </article>
  </div>
</section>

<section class="contact" id="contact">
  <h2>Let's <span>Connect</span></h2>
  <p class="intro">Contact us for enquiries and information about our educational services.</p>
  <div class="grid">
    <article class="card">
      <h3>Email</h3>
      <p><a href="mailto:Ishimwesangoolivier@gmail.com">Ishimwesangoolivier@gmail.com</a></p>
    </article>
    <article class="card">
      <h3>WhatsApp</h3>
      <p><a href="https://wa.me/250786557229" target="_blank" rel="noopener noreferrer">Chat with Panther FX</a></p>
    </article>
    <article class="card">
      <h3>Phone</h3>
      <p><a href="tel:+250794783965">+250 794 783 965</a></p>
    </article>
  </div>
  <p class="notice">Risk warning: Forex and leveraged trading involve significant risk and may lead to the loss of money. This website provides educational information, not personalized financial advice or guaranteed profits.</p>
</section>
</main>

<a class="whatsapp" href="https://wa.me/250786557229" target="_blank" rel="noopener noreferrer">WhatsApp Us</a>

<footer>
  © 2026 Panther The 1st FX Trading. All rights reserved.
</footer>
</body>
</html>

<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Детейлинг, тонировка, оклейка плёнкой — Лос-Анджелес</title>
  <meta name="description" content="Премиум детейлинг, тонировка стёкол, полировка и оклейка плёнкой в Лос-Анджелесе. Запишитесь онлайн — сделаем так, чтобы ваш автомобиль выглядел лучше нового.">
  <style>
    :root {
      --bg: #0b0f14;
      --card: #121821;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #60a5fa;
      --accent-2: #a78bfa;
      --success: #34d399;
      --danger: #f87171;
    }
    * { box-sizing: border-box; }
    html, body { margin: 0; padding: 0; background: var(--bg); color: var(--text); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif; }
    a { color: var(--accent); text-decoration: none; }
    .header {
      position: fixed; top: 0; left: 0; right: 0;
      display: flex; align-items: center; justify-content: space-between;
      padding: 14px 22px; z-index: 50; background: rgba(11,15,20,0.55); backdrop-filter: saturate(140%) blur(10px); border-bottom: 1px solid rgba(255,255,255,0.06);
    }
    .header .brand { display:flex; align-items:center; gap:12px; }
    .header img.logo { height: 36px; width: auto; border-radius: 8px; }
    .nav a { margin-left: 16px; font-weight: 500; color: #d1d5db; }
    .nav a:hover { color: #fff; }
    .cta {
      background: linear-gradient(90deg, var(--accent), var(--accent-2));
      color: #0b0f14; padding: 10px 16px; border-radius: 999px; font-weight: 700;
    }
    .hero {
      position: relative; height: 100vh; width: 100%; overflow: hidden;
    }
    .hero video, .hero .poster {
      position: absolute; top: 0; left: 0; width: 100%; height: 100%;
      object-fit: cover; filter: brightness(0.55) contrast(1.05) saturate(1.1);
    }
    .gradient-overlay {
      position: absolute; inset: 0;
      background: radial-gradient(60% 60% at 50% 50%, rgba(14,165,233,0.20) 0%, rgba(168,85,247,0.12) 40%, rgba(0,0,0,0.55) 100%);
    }
    .hero-content {
      position: relative; z-index: 10; height: 100%; display: grid; place-items: center; text-align: center; padding: 0 18px;
    }
    .hero h1 { font-size: clamp(28px, 6vw, 56px); line-height: 1.07; margin: 0 0 12px; }
    .hero p.sub { color: var(--muted); font-size: clamp(14px, 2.4vw, 18px); margin: 0 0 26px; }
    .buttons { display: flex; gap: 12px; flex-wrap: wrap; justify-content: center; }
    .btn {
      display:inline-flex; align-items:center; gap:10px; padding: 14px 18px; border-radius: 14px; font-weight: 700; border: 1px solid rgba(255,255,255,0.12);
      background: rgba(18,24,33,0.7);
    }
    .btn:hover { border-color: rgba(255,255,255,0.3); transform: translateY(-1px); transition: 120ms; }
    .btn.primary { background: linear-gradient(90deg, var(--accent), var(--accent-2)); color: #0b0f14; border: none; }
    .badges { margin-top: 26px; display:flex; gap:10px; flex-wrap: wrap; justify-content: center; color:#cbd5e1; font-size: 14px; }
    .section {
      padding: 54px 22px; max-width: 1200px; margin: 0 auto;
    }
    .card {
      background: linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.02));
      border: 1px solid rgba(255,255,255,0.06);
      border-radius: 18px; padding: 20px;
    }
    .grid {
      display:grid; gap: 18px;
      grid-template-columns: repeat(1, minmax(0,1fr));
    }
    @media(min-width: 720px){ .grid { grid-template-columns: repeat(2, minmax(0,1fr)); } }
    @media(min-width: 1024px){ .grid { grid-template-columns: repeat(3, minmax(0,1fr)); } }
    .service h3 { margin: 0 0 8px; }
    .service p { margin: 0; color: #cbd5e1; font-size: 14px; }
    .ba-wrap {
      display:grid; grid-template-columns: 1fr 1fr; gap: 18px; align-items:center;
    }
    .ba-wrap img { width:100%; border-radius:16px; border:1px solid rgba(255,255,255,0.06); }
    .footer { padding: 36px 22px; color:#9ca3af; border-top:1px solid rgba(255,255,255,0.06); }
    .whatsapp { display:inline-flex; align-items:center; gap:10px; }
  </style>
</head>
<body>
  <header class="header">
    <div class="brand">
      <img src="assets/logo.svg" class="logo" alt="Detailing LA logo">
      <strong>Detailing LA</strong>
    </div>
    <nav class="nav">
      <a href="#services">Услуги</a>
      <a href="#portfolio">Работы</a>
      <a href="#contact" class="cta">Записаться</a>
    </nav>
  </header>

  <main>
    <section class="hero" aria-label="Главный экран">
      <video id="bgvideo" class="bgvideo" autoplay muted loop playsinline poster="assets/poster.jpg">
        <!-- Replace this src with your real video file at assets/hero.mp4 -->
        <source src="assets/hero.mp4" type="video/mp4">
        <source src="assets/hero.webm" type="video/webm">
        <!-- If no video, a poster image will be shown -->
      </video>
      <div class="gradient-overlay"></div>

      <div class="hero-content">
        <div>
          <h1>Детейлинг, тонировка, оклейка плёнкой в Лос-Анджелесе</h1>
          <p class="sub">Премиум-качество, гарантия результата. Сделаем так, чтобы ваша машина выглядела лучше новой.</p>
          <div class="buttons">
            <a class="btn primary" href="https://wa.me/15555555555" target="_blank" rel="noopener">Записаться в WhatsApp</a>
            <a class="btn" href="#portfolio">Смотреть работы</a>
          </div>
          <div class="badges">
            <span>PPF / Керамика</span>
            <span>Mat / Gloss / Satin</span>
            <span>3M / SunTek / Avery</span>
          </div>
        </div>
      </div>
    </section>

    <section id="services" class="section">
      <h2>Услуги</h2>
      <div class="grid">
        <div class="card service">
          <h3>Тонировка стёкол</h3>
          <p>Карты 5%–50% VLT, керамическая плёнка, безшовная задняя. Гарантия без пузырей.</p>
        </div>
        <div class="card service">
          <h3>Полировка кузова</h3>
          <p>One-Step / Two-Step / Heavy Cut. Удаление голограмм, восстановление глянца.</p>
        </div>
        <div class="card service">
          <h3>Оклейка плёнкой</h3>
          <p>Mat / Gloss / Color Flip / Carbon. Полная оклейка и частичные элементы.</p>
        </div>
        <div class="card service">
          <h3>Защитная PPF</h3>
          <p>Плёнка на зону риска: бампер, капот, зеркала, арки. Шаблоны под модель.</p>
        </div>
        <div class="card service">
          <h3>Керамическое покрытие</h3>
          <p>Долговременная защита лакокрасочного покрытия, гидрофоб, лёгкая мойка.</p>
        </div>
        <div class="card service">
          <h3>Детейлинг салона</h3>
          <p>Химчистка, пар, кожа/пластик/текстиль. Удаление запахов и бактерий.</p>
        </div>
      </div>
    </section>

    <section id="portfolio" class="section">
      <h2>До / После</h2>
      <div class="ba-wrap">
        <img src="assets/sample-before.jpg" alt="До — замените на свою фотографию">
        <img src="assets/sample-after.jpg" alt="После — замените на свою фотографию">
      </div>
    </section>

    <section id="contact" class="section card">
      <h2>Контакты</h2>
      <p>Лос-Анджелес • Пн–Сб 10:00–19:00</p>
      <p class="whatsapp">
        <strong>WhatsApp:</strong>
        <a href="https://wa.me/15555555555" target="_blank" rel="noopener">+1 (555) 555-5555</a>
      </p>
      <p><strong>Адрес:</strong> Добавьте ваш адрес и Google Maps ссылку</p>
      <p><strong>Instagram/TikTok:</strong> добавьте ссылки на соцсети</p>
    </section>
  </main>

  <footer class="footer">
    © <span id="year"></span> Detailing LA — Детейлинг • Тонировка • Оклейка • PPF
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>

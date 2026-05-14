<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Clanker</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0D0D0D;
    --card: #161616;
    --border: #272727;
    --orange: #FF6B1A;
    --orange2: #FF9240;
    --orange-dim: rgba(255,107,26,.12);
    --text: #E8E8E8;
    --muted: #888;
    --white: #fff;
  }
  *,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{background:var(--bg);color:var(--text);font-family:'Inter',sans-serif;font-size:16px;line-height:1.7;overflow-x:hidden}

  nav{position:fixed;top:0;left:0;right:0;z-index:99;display:flex;align-items:center;justify-content:space-between;padding:1rem 3rem;background:rgba(13,13,13,.85);backdrop-filter:blur(16px);border-bottom:1px solid var(--border)}
  .logo{font-family:'Syne',sans-serif;font-size:1.5rem;font-weight:800;color:var(--white);letter-spacing:-.03em}
  .logo span{color:var(--orange)}
  .nav-links{display:flex;gap:2rem}
  .nav-links a{font-size:.82rem;color:var(--muted);text-decoration:none;letter-spacing:.04em;transition:color .2s}
  .nav-links a:hover{color:var(--orange)}
  @media(max-width:600px){.nav-links{display:none}nav{padding:1rem 1.5rem}}

  .hero{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:8rem 2rem 4rem;position:relative;overflow:hidden}
  .hero-bg{position:absolute;inset:0;z-index:0;background:radial-gradient(ellipse 70% 60% at 50% 40%, rgba(255,107,26,.13) 0%, transparent 70%)}
  .hero-grid{position:absolute;inset:0;z-index:0;background-image:linear-gradient(rgba(255,107,26,.05) 1px,transparent 1px),linear-gradient(90deg,rgba(255,107,26,.05) 1px,transparent 1px);background-size:48px 48px;mask-image:radial-gradient(ellipse at center,black 30%,transparent 72%)}
  .hero > *{position:relative;z-index:1}
  .hero-chip{display:inline-flex;align-items:center;gap:.5rem;font-size:.72rem;letter-spacing:.15em;text-transform:uppercase;color:var(--orange);border:1px solid rgba(255,107,26,.3);padding:.35rem 1rem;border-radius:999px;margin-bottom:2rem;opacity:0;animation:up .6s ease forwards .1s}
  .hero-chip::before{content:'';width:7px;height:7px;border-radius:50%;background:var(--orange);animation:pulse 2s infinite}
  @keyframes pulse{0%,100%{opacity:1}50%{opacity:.3}}
  h1{font-family:'Syne',sans-serif;font-size:clamp(3.5rem,11vw,7.5rem);font-weight:800;color:var(--white);line-height:.92;letter-spacing:-.04em;margin-bottom:1.5rem;opacity:0;animation:up .7s ease forwards .25s}
  .orange-text{color:var(--orange)}
  .hero-sub{max-width:580px;color:var(--muted);font-size:1rem;line-height:1.8;margin-bottom:2.5rem;opacity:0;animation:up .7s ease forwards .4s}
  .btn-group{display:flex;gap:1rem;flex-wrap:wrap;justify-content:center;opacity:0;animation:up .7s ease forwards .55s}
  .btn{display:inline-flex;align-items:center;gap:.5rem;padding:.75rem 1.8rem;border-radius:8px;font-size:.88rem;font-weight:500;cursor:pointer;text-decoration:none;transition:all .2s}
  .btn-primary{background:var(--orange);color:#fff;border:1px solid var(--orange)}
  .btn-primary:hover{background:var(--orange2);border-color:var(--orange2)}
  .btn-outline{background:transparent;color:var(--text);border:1px solid var(--border)}
  .btn-outline:hover{border-color:var(--orange);color:var(--orange)}
  .btn svg{width:16px;height:16px}
  @keyframes up{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:none}}

  section{position:relative}
  .wrap{max-width:1060px;margin:0 auto;padding:5.5rem 2rem}
  .sec-label{font-size:.68rem;letter-spacing:.18em;text-transform:uppercase;color:var(--orange);margin-bottom:.8rem;display:flex;align-items:center;gap:.6rem}
  .sec-label::before{content:'';width:20px;height:1px;background:var(--orange)}
  .sec-title{font-family:'Syne',sans-serif;font-size:clamp(1.8rem,4vw,2.8rem);font-weight:800;color:var(--white);letter-spacing:-.03em;line-height:1.1;margin-bottom:1rem}
  .sec-sub{color:var(--muted);max-width:520px;font-size:.95rem;margin-bottom:3rem}
  .divider{height:1px;background:linear-gradient(90deg,transparent,var(--border),transparent);margin:0 2rem}

  .about-layout{display:grid;grid-template-columns:1fr 1fr;gap:3rem;align-items:center}
  .about-img{border-radius:16px;overflow:hidden;border:1px solid var(--border);background:#111;display:flex;align-items:center;justify-content:center}
  .placeholder{width:100%;height:280px;background:#111;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:1rem}
  .placeholder-icon{width:64px;height:64px;border-radius:50%;background:var(--orange-dim);border:1px solid rgba(255,107,26,.25);display:flex;align-items:center;justify-content:center}
  .placeholder-icon svg{width:28px;height:28px;stroke:var(--orange);fill:none;stroke-width:1.5}
  .placeholder-text{font-size:.8rem;color:var(--muted);letter-spacing:.05em}
  .about-tags{display:flex;flex-wrap:wrap;gap:.5rem;margin-top:1.5rem}
  .tag{font-size:.72rem;padding:.3rem .85rem;border-radius:999px;border:1px solid var(--border);color:var(--muted)}
  .tag.accent{border-color:rgba(255,107,26,.35);color:var(--orange);background:var(--orange-dim)}
  @media(max-width:700px){.about-layout{grid-template-columns:1fr}}

  footer{border-top:1px solid var(--border);padding:2rem 3rem;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:1rem}
  .footer-logo{font-family:'Syne',sans-serif;font-weight:800;color:var(--white)}
  .footer-logo span{color:var(--orange)}
  .footer-info{font-size:.75rem;color:var(--muted)}
  @media(max-width:600px){footer{flex-direction:column;text-align:center}}

  .reveal{opacity:0;transform:translateY(28px);transition:opacity .65s ease,transform .65s ease}
  .reveal.on{opacity:1;transform:none}
</style>
</head>
<body>

<nav>
  <div class="logo">Clan<span>ker</span></div>
  <div class="nav-links">
    <a href="#quienes">Quiénes somos</a>
    <a href="#objetivos">Objetivos</a>
    <a href="#estructura">Estructura</a>
    <a href="#tecnologias">Tecnologías</a>
    <a href="#tienda">Tienda</a>
  </div>
</nav>

<div class="hero">
  <div class="hero-bg"></div>
  <div class="hero-grid"></div>
  <div class="hero-chip">Proyecto de desarrollo — CFGS ASIX 2025–2026</div>
  <h1>Clan<span class="orange-text">ker</span></h1>
  <p class="hero-sub">Infraestructura tecnológica completa para una empresa de comercio electrónico. Red local, servidor Linux y tienda online funcional.</p>
</div>

<section id="quienes">
  <div class="wrap">
    <div class="sec-label reveal">01 — Quiénes somos</div>
    <div class="about-layout">
      <div>
        <h2 class="sec-title reveal">Una empresa de tecnología <span class="orange-text">simulada</span></h2>

        <p style="color:var(--muted);font-size:.95rem;line-height:1.8;margin-bottom:1rem" class="reveal">
          Clanker es un proyecto educativo del CFGS de Administración de Sistemas Informáticos que simula la creación de una empresa de comercio electrónico real.
        </p>

        <div class="about-tags reveal">
          <span class="tag accent">Comercio electrónico</span>
          <span class="tag accent">Ubuntu Server</span>
          <span class="tag accent">WooCommerce</span>
        </div>
      </div>

      <div class="reveal">
        <div class="about-img">

          <!-- <img src="logo.png" alt="Clanker logo"> -->

          <img src="Logo.png" alt="Clanker" onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">

          <div class="placeholder" style="display:none">
            <div class="placeholder-icon">
              <svg viewBox="0 0 24 24">
                <rect x="2" y="3" width="20" height="14" rx="2"/>
              </svg>
            </div>

            <span class="placeholder-text">
              Pon tu logo en:
              <code style="color:var(--orange)">src="logo-clanker.png"</code>
            </span>

          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="tienda">
  <div class="wrap">
    <div class="sec-label reveal">05 — Tienda online</div>

    <h2 class="sec-title reveal">
      Visita nuestra <span class="orange-text">tienda</span>
    </h2>

    <div class="link-section reveal">
      <div class="link-left">

        <h3>Clanker Shop</h3>

        <p>
          Accede a la tienda online de Clanker, desarrollada con WooCommerce sobre WordPress.
        </p>

        <div class="link-url" id="url-display">
          <span id="url-text">
            Haz clic en "Ir a la tienda" para configurar la URL
          </span>
        </div>
      </div>

      <div class="link-right">
        <button class="link-big-btn" id="shop-btn" onclick="openShop()">
          Ir a la tienda
        </button>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="footer-logo">Clan<span>ker</span></div>

  <div class="footer-info">
    Izan Casasola · SMX2A · Institut Puig Castellar · Santa Coloma de Gramenet · 2025–2026
  </div>
</footer>

<script>
  const obs = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) e.target.classList.add('on');
    });
  }, { threshold: 0.08 });

  document.querySelectorAll('.reveal').forEach(el => obs.observe(el));

  let shopUrl = '';

  function openShop() {
    shopUrl = "https://clankershop.infinityfree.me/wp";
    window.open(shopUrl, '_blank');
  }
</script>

</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kodex Creatives — Creative & Marketing Agency</title>
  <meta name="description" content="Kodex Creatives — Branding, content, and short-form ads that convert." />
  <style>
    :root{
      --bg:#070A12; --card:#0D1223; --text:#EAF0FF; --muted:#AAB6D6;
      --gold:#D6B25E; --line:rgba(214,178,94,.25);
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
      color:var(--text); background:
        radial-gradient(900px 500px at 15% 10%, rgba(214,178,94,.18), transparent 60%),
        radial-gradient(900px 500px at 90% 30%, rgba(120,140,255,.16), transparent 60%),
        var(--bg);
    }
    a{color:inherit; text-decoration:none}
    .wrap{max-width:1100px; margin:0 auto; padding:24px}
    header{
      position:sticky; top:0; backdrop-filter: blur(10px);
      background:rgba(7,10,18,.6); border-bottom:1px solid rgba(255,255,255,.06);
      z-index:10;
    }
    .nav{display:flex; align-items:center; justify-content:space-between; gap:14px}
    .brand{display:flex; align-items:center; gap:10px; font-weight:800; letter-spacing:.3px}
    .logo{
      width:34px; height:34px; border-radius:10px;
      background:linear-gradient(135deg, rgba(214,178,94,.95), rgba(255,255,255,.12));
      box-shadow:0 10px 30px rgba(214,178,94,.18);
    }
    .links{display:flex; gap:14px; font-size:14px; color:var(--muted)}
    .btn{
      display:inline-flex; align-items:center; justify-content:center; gap:8px;
      padding:10px 14px; border-radius:12px; border:1px solid var(--line);
      background:linear-gradient(180deg, rgba(214,178,94,.18), rgba(214,178,94,.06));
      color:var(--text); font-weight:800;
    }
    .btn.secondary{background:rgba(255,255,255,.02); border-color:rgba(255,255,255,.12); font-weight:700}
    .btn:hover{transform:translateY(-1px)}
    .hero{padding:54px 0 18px}
    .kicker{color:var(--gold); font-weight:900; letter-spacing:.18em; font-size:12px}
    h1{margin:12px 0 10px; font-size:44px; line-height:1.05}
    p{margin:0; color:var(--muted); font-size:16px; line-height:1.6}
    .grid{display:grid; gap:14px}
    .heroGrid{grid-template-columns: 1.2fr .8fr; align-items:stretch; margin-top:22px}
    .card{
      background:rgba(13,18,35,.72); border:1px solid rgba(255,255,255,.08);
      border-radius:18px; padding:18px; box-shadow:0 24px 80px rgba(0,0,0,.35);
    }
    .stats{display:grid; grid-template-columns:repeat(3,1fr); gap:12px; margin-top:14px}
    .stat{padding:14px; border-radius:14px; border:1px solid rgba(255,255,255,.08); background:rgba(255,255,255,.03)}
    .stat b{display:block; font-size:18px}
    .stat span{color:var(--muted); font-size:12px}
    section{padding:28px 0}
    h2{margin:0 0 10px; font-size:26px}
    .services{grid-template-columns:repeat(3,1fr)}
    .svc h3{margin:0 0 6px; font-size:16px}
    .svc p{font-size:14px}
    .pill{display:inline-block; margin-top:10px; font-size:12px; color:var(--gold);
      border:1px solid var(--line); padding:6px 10px; border-radius:999px; background:rgba(214,178,94,.08)}
    .footer{padding:18px 0 40px; color:var(--muted); font-size:13px; border-top:1px solid rgba(255,255,255,.06)}
    @media (max-width:900px){
      h1{font-size:36px}
      .heroGrid{grid-template-columns:1fr}
      .services{grid-template-columns:1fr}
      .stats{grid-template-columns:1fr}
      .links{display:none}
    }
  </style>
</head>
<body>
  <header>
    <div class="wrap nav">
      <a class="brand" href="#top"><span class="logo"></span> Kodex Creatives</a>
      <nav class="links">
        <a href="#services">Services</a>
        <a href="#process">Process</a>
        <a href="#contact">Contact</a>
      </nav>
      <a class="btn" href="#contact">Get a Quote →</a>
    </div>
  </header>

  <main id="top" class="wrap">
    <div class="hero">
      <div class="kicker">CREATIVE • CONTENT • PERFORMANCE</div>
      <h1>Premium creatives that make brands sell more.</h1>
      <p>
        Kodex Creatives helps businesses grow with high-end branding, scroll-stopping content,
        and short-form ads built for conversion.
      </p>

      <div class="grid heroGrid">
        <div class="card">
          <h2 style="margin:0 0 8px;">What we offer</h2>
          <p>Branding, social media content, and high-converting video creatives for TikTok & Instagram.</p>
          <div class="stats">
            <div class="stat"><b>Branding</b><span>Logo • identity • guidelines</span></div>
            <div class="stat"><b>Content</b><span>Reels • posters • captions</span></div>
            <div class="stat"><b>Ads</b><span>Video creatives • funnels</span></div>
          </div>
        </div>

        <div class="card" id="contact">
          <h2 style="margin:0 0 8px;">Contact</h2>
          <p style="margin-bottom:12px;">Tap a button below to reach us instantly.</p>

          <!-- CHANGE THESE TWO LINKS -->
          <a class="btn" href="https://wa.me/2547XXXXXXXX?text=Hello%20Kodex%20Creatives%2C%20I%20need%20your%20services." target="_blank">WhatsApp Us</a>
          <a class="btn secondary" href="mailto:kodexcreatives@gmail.com?subject=Kodex%20Creatives%20Inquiry">Email Us</a>

          <p style="margin-top:12px; font-size:13px; color:var(--muted);">
            Office: Kenya • Serving clients worldwide
          </p>
        </div>
      </div>
    </div>

    <section id="services">
      <h2>Services</h2>
      <div class="grid services">
        <div class="card svc">
          <h3>Brand Identity</h3>
          <p>Logos, brand colors, typography, and premium visual systems.</p>
          <span class="pill">For new & growing brands</span>
        </div>
        <div class="card svc">
          <h3>Social Media Content</h3>
          <p>Reels, posters, captions, and weekly content planning.</p>
          <span class="pill">For growth & trust</span>
        </div>
        <div class="card svc">
          <h3>Short-Form Ads</h3>
          <p>High-converting TikTok/IG ad creatives designed to generate leads & sales.</p>
          <span class="pill">For sales & leads</span>
        </div>
      </div>
    </section>

    <section id="process">
      <h2>How we work</h2>
      <div class="grid services">
        <div class="card">
          <h3>1) Strategy</h3>
          <p>We define your offer, target audience, and winning content angles.</p>
        </div>
        <div class="card">
          <h3>2) Production</h3>
          <p>We create premium designs + scroll-stopping video creatives.</p>
        </div>
        <div class="card">
          <h3>3) Improve</h3>
          <p>We refine what works and scale the winners.</p>
        </div>
      </div>
    </section>

    <div class="footer">
      © <span id="y"></span> Kodex Creatives. All rights reserved.
    </div>
  </main>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>

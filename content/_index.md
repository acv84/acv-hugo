<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Senior Layout Artist & Filmmaker</title>
  <meta name="description" content="Senior Layout Artist & Filmmaker — Bringing cinematic visions to life through precise visual storytelling." />
  <style>
    :root{
      --bg:#0b0c0f;
      --panel:#0f1117;
      --text:#e9e9ee;
      --muted:#b3b6c2;
      --line:rgba(255,255,255,.10);
      --link:#e9e9ee;
      --shadow: 0 18px 55px rgba(0,0,0,.45);
      --radius:18px;
      --max: 980px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background: radial-gradient(1200px 800px at 20% 0%, rgba(255,255,255,.06), transparent 55%),
                  radial-gradient(900px 650px at 85% 10%, rgba(255,255,255,.05), transparent 60%),
                  var(--bg);
      color:var(--text);
      font: 16px/1.55 ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      letter-spacing:.2px;
    }
    a{
      color:var(--link);
      text-decoration:none;
      border-bottom:1px solid rgba(233,233,238,.35);
    }
    a:hover{border-bottom-color:rgba(233,233,238,.85)}
    .wrap{
      max-width:var(--max);
      margin:0 auto;
      padding:72px 20px;
    }
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03));
      border:1px solid var(--line);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:42px;
    }
    header{
      display:flex;
      flex-direction:column;
      gap:14px;
      padding-bottom:26px;
      border-bottom:1px solid var(--line);
    }
    h1{
      margin:0;
      font-size: clamp(30px, 4.5vw, 48px);
      line-height:1.08;
      letter-spacing:-.6px;
      font-weight:650;
    }
    .lead{
      margin:0;
      font-size:18px;
      color:var(--muted);
      max-width:62ch;
    }
    .sublead{
      margin:0;
      color:var(--muted);
      max-width:70ch;
    }
    main{padding-top:26px}
    h2{
      margin:28px 0 12px;
      font-size:14px;
      letter-spacing:.18em;
      text-transform:uppercase;
      color:rgba(233,233,238,.78);
      font-weight:650;
    }
    p{margin:0 0 12px}
    .studios{
      display:flex;
      flex-wrap:wrap;
      gap:10px 14px;
      margin:10px 0 12px;
      color:var(--muted);
    }
    .studios span{color:rgba(233,233,238,.9)}
    .pill{
      display:inline-flex;
      align-items:center;
      padding:8px 12px;
      border:1px solid var(--line);
      border-radius:999px;
      background:rgba(0,0,0,.14);
    }
    .grid{
      display:grid;
      grid-template-columns: 1fr;
      gap:14px;
      margin-top:10px;
    }
    .item{
      border:1px solid var(--line);
      border-radius:16px;
      background:rgba(0,0,0,.18);
      padding:16px 16px 14px;
    }
    .item h3{
      margin:0 0 6px;
      font-size:16px;
      font-weight:650;
    }
    .item p{margin:0; color:var(--muted)}
    .project{
      border:1px solid var(--line);
      border-radius:16px;
      background:rgba(0,0,0,.18);
      padding:18px 18px 16px;
      margin-top:10px;
    }
    .project h3{
      margin:0 0 6px;
      font-size:18px;
      font-weight:650;
    }
    .project .meta{
      margin:0 0 10px;
      color:rgba(233,233,238,.78);
      font-size:14px;
      letter-spacing:.04em;
    }
    .cta{
      display:flex;
      flex-wrap:wrap;
      gap:12px;
      margin-top:18px;
    }
    .btn{
      display:inline-flex;
      align-items:center;
      justify-content:center;
      padding:11px 14px;
      border-radius:12px;
      border:1px solid var(--line);
      background:rgba(255,255,255,.06);
      color:var(--text);
      font-weight:600;
      letter-spacing:.2px;
    }
    .btn:hover{background:rgba(255,255,255,.10)}
    .btn.primary{
      background:rgba(233,233,238,.92);
      color:#0b0c0f;
      border-color:transparent;
    }
    .btn.primary:hover{background:rgba(233,233,238,1)}
    footer{
      padding-top:18px;
      margin-top:26px;
      border-top:1px solid var(--line);
      color:rgba(233,233,238,.55);
      font-size:13px;
    }
    @media (min-width: 860px){
      .grid{grid-template-columns: 1fr 1fr 1fr}
    }
  </style>
</head>

<body>
  <div class="wrap">
    <article class="card">
      <header>
        <h1>Senior Layout Artist &amp; Filmmaker</h1>
        <p class="lead">Bringing cinematic visions to life through precise visual storytelling</p>
        <p class="sublead">Specialized in Layout, Previs &amp; Post-Production for world-class VFX studios</p>
      </header>

      <main>
        <h2>Trusted by Industry Leaders</h2>
        <p>I’ve contributed to groundbreaking visual effects at some of the most prestigious studios in the industry:</p>

        <div class="studios" aria-label="Studios">
          <a class="pill" href="https://www.ilm.com/" target="_blank" rel="noopener noreferrer">Industrial Light &amp; Magic (ILM)</a>
          <span aria-hidden="true">|</span>
          <a class="pill" href="https://www.framestore.com/" target="_blank" rel="noopener noreferrer">Framestore</a>
          <span aria-hidden="true">|</span>
          <a class="pill" href="https://www.dneg.com/" target="_blank" rel="noopener noreferrer">DNEG</a>
          <span aria-hidden="true">|</span>
          <a class="pill" href="https://goodbyekansasstudios.com/" target="_blank" rel="noopener noreferrer">Goodbye Kansas</a>
        </div>

        <p>From London to Spain, collaborating on blockbuster productions and cutting-edge visual storytelling</p>

        <h2>What I Do</h2>
        <section class="grid">
          <div class="item">
            <h3>Layout Artist</h3>
            <p>Creating the fundamental framework for VFX sequences – precise camera work, composition, and timing that serves as the blueprint for spectacular visual effects.</p>
          </div>

          <div class="item">
            <h3>Previs Specialist</h3>
            <p>Translating director’s vision into preliminary visual sequences, helping teams visualize complex scenes before production.</p>
          </div>

          <div class="item">
            <h3>Filmmaker</h3>
            <p>Directing and producing independent projects with a focus on intimate storytelling and technical excellence.</p>
          </div>
        </section>

        <h2>Featured Project: «El Último Giro»</h2>
        <section class="project">
          <p class="meta">Documentary Film | Director &amp; Producer</p>
          <p>An intimate portrait of Sabina Asenjo, Spain’s legendary discus thrower who still holds the national record. The film explores her journey, challenges, and reflections on retirement from professional sports.</p>
          <p>A passion project where I handled direction, cinematography, editing, and post-production.</p>
        </section>

        <h2>Ready to Collaborate?</h2>
        <p>Whether you need precise layout work for your next VFX sequence or want to discuss a creative project, I’m here to help bring your vision to life.</p>

        <div class="cta">
          <a class="btn primary" href="https://adriancastroviejo.com/filmography" target="_blank" rel="noopener noreferrer">VIEW MY WORK</a>
          <a class="btn" href="https://adriancastroviejo.com/contact" target="_blank" rel="noopener noreferrer">GET IN TOUCH</a>
        </div>

        <footer>
        </footer>
      </main>
    </article>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Workshop | A Vida Que Eu Quero Viver</title>
  <meta name="description" content="Workshop gratuito de 3 noites (23, 24 e 25 de outubro, às 19h, ao vivo no YouTube) para soltar pesos do passado, liberar emoções que aprisionam e reescrever a sua história com leveza. Inscreva-se entrando no grupo de WhatsApp.">
  <meta name="theme-color" content="#6D5BD0">
  <!-- Open Graph -->
  <meta property="og:title" content="Workshop | A Vida Que Eu Quero Viver" />
  <meta property="og:description" content="3 noites para soltar o passado e escolher leveza. 23–25/10 às 19h, ao vivo no YouTube. Entre no grupo de WhatsApp e garanta sua vaga." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=A+Vida+Que+Eu+Quero+Viver" />
  <meta property="og:url" content="https://seudominio.com/workshop" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 100 100%27%3E%3Ccircle cx=%2750%27 cy=%2750%27 r=%2748%27 fill=%27%236D5BD0%27/%3E%3Ctext x=%2750%27 y=%2760%27 font-size=%2750%27 text-anchor=%27middle%27 fill=%27white%27%3E❤%3C/text%3E%3C/svg%3E" />
  <style>
    :root{
      --bg:#0f1020;
      --bg-soft:#151735;
      --brand:#6D5BD0;
      --brand-2:#8F83E6;
      --text:#E9E9F3;
      --muted:#BFC2D9;
      --ok:#27C498;
      --warn:#FFC86B;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius:16px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans";
      background: radial-gradient(1200px 800px at 70% -10%, #222455 0%, transparent 60%) , var(--bg);
      color:var(--text);
      line-height:1.5;
      hyphens:none; -webkit-hyphens:none;
    }
    h1, .cta, .chip, .supertitle {
      hyphens: none;
      -webkit-hyphens: none;
      word-break: keep-all;
      overflow-wrap: normal;
    }
    .wrap{max-width:1080px;margin:0 auto;padding:24px}
    .hero{display:grid; gap:24px; align-items:center; grid-template-columns: 1.2fr .8fr; padding: clamp(24px,5vw,56px) 0;}
    .supertitle{
      display:block;
      font-weight:900;
      font-size: clamp(1.4rem, 4vw, 2.4rem);
      letter-spacing:.4px;
      line-height:1.1;
      margin-bottom: 6px;
      color:#ffffff;
      text-transform: uppercase;
    }
    h1{font-size: clamp(2rem, 5vw, 3.2rem); margin:10px 0 8px; line-height:1.1}
    .sub{color:var(--muted); font-size: clamp(1rem, 2.2vw, 1.15rem); margin-bottom:18px}
    .cta{display:inline-flex; align-items:center; justify-content:center; gap:10px;
      background:linear-gradient(90deg,var(--brand-2),var(--brand));
      color:#fff; font-weight:800; letter-spacing:.2px;
      padding:16px 22px; border-radius:12px; text-decoration:none; box-shadow:var(--shadow);
      transition: transform .08s ease;}
    .cta:hover{transform: translateY(-1px)}
    .meta{display:flex; gap:14px; flex-wrap:wrap; margin:10px 0 24px}
    .chip{background:rgba(255,255,255,.06); color:var(--muted); border:1px solid rgba(255,255,255,.08); padding:8px 12px; border-radius:999px; font-size:.92rem}
    .card{background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,.02)); border:1px solid rgba(255,255,255,.08); border-radius: var(--radius); padding:24px; box-shadow:var(--shadow)}
    .grid{display:grid; gap:18px}
    .nights{grid-template-columns: repeat(3,1fr)}
    .night h3{margin:0 0 8px}
    .night ul{margin:10px 0 0 18px}
    .why{grid-template-columns: repeat(2,1fr)}
    .notice{display:flex; align-items:center; gap:10px; color:#111; background:linear-gradient(90deg,#D1F7EC,#F6F0FF); border-radius:12px; padding:12px 14px; font-weight:600;}
    .sticky-bar{position:sticky; bottom:12px; z-index:100; display:flex; justify-content:center;}
    .sticky-inner{backdrop-filter: blur(10px); background: rgba(21, 23, 53, .75); border:1px solid rgba(255,255,255,.1); padding:10px; border-radius:14px; box-shadow:var(--shadow); display:flex; gap:12px; align-items:center;}
    .countdown{font-variant-numeric: tabular-nums; color:var(--warn); font-weight:700}
    footer{color:var(--muted); font-size:.9rem; padding:40px 0}
    .illus{aspect-ratio: 4/3; border-radius: var(--radius); background: radial-gradient(500px 400px at 30% 20%, rgba(111,92,210,.35), transparent 60%), linear-gradient(180deg, rgba(255,255,255,.05), rgba(255,255,255,.02)); border:1px solid rgba(255,255,255,.08); display:flex; align-items:center; justify-content:center; color:#cfc9ff; font-weight:700; letter-spacing:.5px;}
    .illus small{display:block; color:#bdb7ee; font-weight:600}
    @media (max-width: 900px){.hero{grid-template-columns:1fr}.nights{grid-template-columns:1fr}.why{grid-template-columns:1fr}}
  </style>
  <script>
    document.addEventListener('DOMContentLoaded', ()=>{
      const out = document.querySelectorAll('.countdown');
      function tick(){
        const target = new Date('2025-10-23T19:00:00-03:00').getTime();
        const now = Date.now();
        let ms = target - now;
        if(ms < 0){ out.forEach(el=>el.textContent="começa hoje • 19h"); return; }
        const d = Math.floor(ms/86400000); ms-=d*86400000;
        const h = Math.floor(ms/3600000); ms-=h*3600000;
        const m = Math.floor(ms/60000);
        const txt = `${d}d ${String(h).padStart(2,'0')}h ${String(m).padStart(2,'0')}m`;
        out.forEach(el=>el.textContent=txt);
      }
      tick(); setInterval(tick, 30000);
    });
  </script>
</head>
<body>
  <header class="wrap hero" role="banner">
    <div>
      <div class="supertitle">WORKSHOP GRATUITO • AO VIVO NO YOUTUBE</div>
      <h1>A Vida Que Eu Quero Viver</h1>
      <p class="sub">3 noites para soltar os barulhos da mente, liberar emoções que aprisionam e reescrever sua história com leveza.</p>
      <div class="meta">
        <span class="chip">📅 23, 24 e 25 de outubro</span>
        <span class="chip">🕖 19h (ao vivo)</span>
        <span class="chip">🎥 YouTube</span>
        <span class="chip">⏳ começa em: <span class="countdown">calculando…</span></span>
      </div>
      <a class="cta" href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t" target="_blank" rel="noopener">💬 Entrar no grupo de WhatsApp</a>
      <p class="sub" style="margin-top:10px">❗ a confirmação e os links das aulas serão enviados apenas no grupo.</p>
    </div>
    <div class="illus card">WORKSHOP • 3 NOITES <small>consciência • liberação • novo começo</small></div>
  </header>

  <main class="wrap">
    <!-- ... resto das seções iguais ... -->
    <section class="card" style="text-align:center; margin-top:22px">
      <h2>garanta sua vaga agora</h2>
      <p class="sub">as informações e links serão enviados somente dentro do grupo.</p>
      <a class="cta" href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t" target="_blank" rel="noopener">💬 entrar no grupo de whatsapp</a>
      <p class="sub" style="margin-top:10px">📅 23, 24 e 25/10 • 🕖 19h • 🎥 YouTube</p>
    </section>

    <div class="sticky-bar">
      <div class="sticky-inner">
        <span>⏳ começa em: <span class="countdown">calculando…</span></span>
        <a class="cta" href="https://chat.whatsapp.com/CeXf6hjhBziAzvXl9HGFFp?mode=ems_copy_t" target="_blank" rel="noopener" style="padding:10px 14px;font-weight:700">garantir vaga</a>
      </div>
    </div>
  </main>

  <footer class="wrap">
    <div style="opacity:.9">© <span id="y"></span> Mentoria O Seu Lugar • Todos os direitos reservados</div>
    <script>document.getElementById('y').textContent = new Date().getFullYear();</script>
  </footer>
</body>
</html>


<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>LT TECNOLOGÍ COMPUTER — Enlaces Gamer</title>
  <meta name="description" content="LT Tecnología Computer - Portal de enlaces gamer, accesorios, ofertas y contacto.">
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#050505;
      --card:#0d0d0d;
      --neon:#e11b1b;
      --accent:#ff3b3b;
      --muted:#9a9a9a;
      --glass:rgba(255,255,255,0.03);
      --radius:14px;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:Inter,system-ui,sans-serif;
      background: radial-gradient(1200px 500px at 10% 10%,rgba(225,27,27,0.06),transparent 10%),
                  linear-gradient(180deg,rgba(10,10,10,1),rgba(3,3,3,1));
      color:#eee;
      overflow-x:hidden;
    }
    .bg-grid{
      position:fixed;inset:0;z-index:0;pointer-events:none;
      background-image:linear-gradient(transparent 90%,rgba(255,0,0,0.02) 100%),
                       linear-gradient(90deg,transparent 90%,rgba(255,0,0,0.02) 100%);
      background-size:260px 260px;
      opacity:0.35;filter:blur(18px);animation:floatGrid 20s linear infinite;
    }
    @keyframes floatGrid{
      from{background-position:0 0,0 0}
      to{background-position:400px 400px,-400px -400px}
    }
    .wrap{position:relative;z-index:3;max-width:1100px;margin:48px auto;padding:36px}
    header{text-align:center;margin-bottom:28px}
    .logo img{width:150px;height:auto;filter:drop-shadow(0 8px 18px rgba(225,27,27,0.15));border-radius:8px}
    .brand{font-family:'Orbitron',sans-serif;color:var(--neon);
      text-shadow:0 0 12px rgba(225,27,27,0.12);font-size:28px;margin-top:8px}
    .subtitle{color:var(--muted);font-size:13px;margin-top:6px}
    .links-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:18px}
    .card{
      background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));
      border-radius:var(--radius);
      padding:18px;
      box-shadow:0 6px 20px rgba(0,0,0,0.6);
      border:1px solid rgba(255,255,255,0.03);
      transition:transform .3s,box-shadow .3s;
      display:flex;gap:12px;align-items:center;justify-content:space-between;
    }
    .card:hover{
      transform:translateY(-6px);
      box-shadow:0 14px 34px rgba(0,0,0,0.7),0 0 40px rgba(225,27,27,0.06);
    }
    .icon{
      width:62px;height:62px;display:flex;align-items:center;justify-content:center;
      font-size:28px;border-radius:10px;background:rgba(225,27,27,0.08);
    }
    .meta .title{font-family:'Orbitron';font-size:15px;color:#fff}
    .meta .desc{font-size:12px;color:var(--muted)}
    .btn{
      background:transparent;border:1px solid rgba(255,255,255,0.06);
      padding:10px 14px;border-radius:10px;color:#fff;text-decoration:none;
      font-weight:600;transition:all .22s;backdrop-filter:blur(6px);
    }
    .btn:hover{
      transform:translateY(-4px) scale(1.02);
      box-shadow:0 8px 30px rgba(225,27,27,0.12);
      border-color:rgba(255,255,255,0.12);
    }
    .cta-bar{margin-top:26px;display:flex;gap:12px;align-items:center;justify-content:space-between;flex-wrap:wrap}
    .search{flex:1;display:flex;gap:8px}
    .search input{
      flex:1;padding:12px 14px;border-radius:12px;
      border:1px solid rgba(255,255,255,0.03);
      background:rgba(255,255,255,0.02);color:#fff
    }
    .search button{
      padding:12px 18px;border-radius:12px;border:none;
      background:linear-gradient(90deg,var(--neon),var(--accent));
      color:#fff;font-weight:700;cursor:pointer
    }
    footer{
      margin-top:42px;padding:22px;border-radius:12px;
      background:rgba(255,255,255,0.02);
      display:flex;gap:18px;align-items:center;
      justify-content:space-between;flex-wrap:wrap
    }
    .socials a{
      margin-right:12px;text-decoration:none;
      color:var(--muted);font-weight:600;font-size:13px
    }
    .contact-panel{
      margin-top:22px;padding:18px;border-radius:12px;
      background:rgba(20,20,20,0.6);border:1px solid rgba(255,255,255,0.03)
    }
    .contact-panel form{display:flex;flex-direction:column;gap:10px}
    .contact-panel input,.contact-panel textarea{
      padding:12px 14px;border-radius:10px;
      border:1px solid rgba(255,255,255,0.03);
      background:transparent;color:#fff;font-size:14px
    }
    .contact-panel textarea{min-height:120px;resize:vertical}
    .success{color:#8fe58f;font-weight:700;margin-top:8px}
    @media(max-width:900px){.links-grid{grid-template-columns:repeat(2,1fr)}}
    @media(max-width:600px){
      .links-grid{grid-template-columns:1fr}
      .wrap{padding:20px}
      .brand{font-size:20px}
    }
  </style>
</head>
<body>
  <div class="bg-grid"></div>
  <div class="wrap">
    <header>
      <div class="logo">
        <img src="assets/logo.png" alt="LT Tecnologí - Logo"
             onerror="this.src='https://dummyimage.com/150x150/000/ff3b3b&text=LT'">
      </div>
      <div class="brand">LT TECNOLOGÍ COMPUTER</div>
      <div class="subtitle">
        Enlaces oficiales, tiendas y accesorios gamer. Compra con seguridad.
      </div>
    </header>

  <div class="cta-bar">
      <div class="search">
   <input id="searchInput" placeholder="Buscar tienda o accesorio... (ej: Steam, Razer, Amazon)">
        <button id="searchBtn">Buscar</button>
  </div>
   <a class="btn" href="#contact">Contacto</a>
  </div>

   <section class="links-grid" id="linksGrid">
   <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">Steam</div><div class="desc">Tienda de juegos para PC</div></div><a class="btn" href="https://store.steampowered.com" target="_blank">Ir</a></article>
      <article class="card"><div class="icon">🕹️</div><div class="meta"><div class="title">Epic Games</div><div class="desc">Juegos gratis y descuentos</div></div><a class="btn" href="https://www.epicgames.com/store" target="_blank">Ir</a></article>
   <article class="card"><div class="icon">🛒</div><div class="meta"><div class="title">Amazon</div><div class="desc">Hardware y periféricos</div></div><a class="btn" href="https://www.amazon.com/s?k=gaming" target="_blank">Ir</a></article>
      <article class="card"><div class="icon">🇦🇷</div><div class="meta"><div class="title">MercadoLibre</div><div class="desc">Productos locales</div></div><a class="btn" href="https://www.mercadolibre.com" target="_blank">Ir</a></article>
   <article class="card"><div class="icon">⚡</div><div class="meta"><div class="title">Razer</div><div class="desc">Accesorios RGB</div></div><a class="btn" href="https://www.razer.com" target="_blank">Ir</a></article>
      <article class="card"><div class="icon">🖱️</div><div class="meta"><div class="title">Redragon</div><div class="desc">Teclados y mouse gamer</div></div><a class="btn" href="https://www.redragonzone.com" target="_blank">Ir</a></article>
  <article class="card"><div class="icon">💻🖥️</div><div class="meta"><div class="title">Compra Gamer</div><div class="desc">Teclados y mouse gamer</div></div><a class="btn" href="https://compragamer.com/" target="_blank">Ir</a></article>
  <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">Logitech G</div><div class="desc">Tienda gamer</div></div><a class="btn" href="https://www.logitechg.com/" target="_blank">Ir</a></article>
 <article class="card"><div class="icon">⚡</div><div class="meta"><div class="title">Playstation store</div><div class="desc">Juegos digitales, suscripciones y accesorios.</div></div><a class="btn" href="https://store.playstation.com/" target="_blank">Ir</a></article>
      <article class="card"><div class="icon">⚡</div><div class="meta"><div class="title">Xbox store</div><div class="desc">Juegos, hardware y accesorios para Xbox y PC..</div></div><a class="btn" href="https://www.xbox.com/en-US/microsoft-store" target="_blank">Ir</a></article>
      <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">FullH4rd</div><div class="desc">Tienda gamer argentina con hardware, notebooks y accesorios.</div></div><a class="btn" href="https://www.fullh4rd.com.ar/" target="_blank">Ir</a></article>
      <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">Maximus</div><div class="desc">Vende productos para gaming y tecnología.</div></div><a class="btn" href="https://www.maximus.com.ar/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">Venex</div><div class="desc">Equipos gamer, hardware, consolas, periféricos.</div></div><a class="btn" href="https://www.venex.com.ar/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">HyperX</div><div class="desc">Headsets, teclados y memorias diseñadas para.</div></div><a class="btn" href="https://www.hyperx.com/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">NZXT</div><div class="desc">🖥️ Gabinetes, refrigeración y componentes para PCs gamer personalizadas.</div></div><a class="btn" href="https://www.nzxt.com/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">Corsair</div><div class="desc">Periféricos, componentes RGB y accesorios premium para gaming.</div></div><a class="btn" href="https://www.corsair.com/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">Thermaltake</div><div class="desc">🔥 Componentes, fuentes, refrigeración líquida y sillas gamer.</div></div><a class="btn" href="https://www.thermaltake.com/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">Cooler Master</div><div class="desc">🧊 Hardware, periféricos y accesorios para gamers exigentes.</div></div><a class="btn" href="https://www.coolermaster.com/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">ASUS ROG</div><div class="desc">💻 Línea gamer de ASUS con notebooks, componentes y accesorios RGB.</div></div><a class="btn" href="https://rog.asus.com/" target="_blank">Ir</a></article>
       <article class="card"><div class="icon">🎮</div><div class="meta"><div class="title">MSI Gaming</div><div class="desc">🔥 Laptops, PCs, placas de video y monitores para jugadores exigentes.</div></div><a class="btn" href="https://www.msi.com/" target="_blank">Ir</a></article>
        </section>
        </section>

  <section id="contact" class="contact-panel">
      <h3 style="font-family:Orbitron;color:var(--neon)">Contacto</h3>
      <p class="muted">Envíanos una consulta o propuesta comercial.</p>
      <form id="contactForm">
        <input type="text" name="name" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Correo electrónico" required>
        <textarea name="message" placeholder="Escribe tu mensaje..." required></textarea>
        <button type="submit" class="btn" style="background:linear-gradient(90deg,var(--neon),var(--accent));">Enviar Mensaje</button>
        <div id="msg" class="success" style="display:none;">¡Gracias! Tu mensaje fue enviado.</div>
      </form>
    </section>

  <footer>
      <div>
        <strong>LT Tecnologí</strong><br>
        <span class="muted">Tienda y enlace oficial — Soporte y acuerdos comerciales</span>
      </div>
      <div class="socials">
        <a href="https://facebook.com" target="_blank">Facebook</a>
        <a href="https://instagram.com" target="_blank">Instagram</a>
        <a href="https://twitter.com" target="_blank">Twitter</a>
        <a href="https://youtube.com" target="_blank">YouTube</a>
      </div>
    </footer>
  </div>

  <script>
    // --- Buscador de enlaces ---
    const searchInput=document.getElementById('searchInput');
    const searchBtn=document.getElementById('searchBtn');
    const cards=[...document.querySelectorAll('.card')];

    function filterCards(q){
      q=q.toLowerCase();
      cards.forEach(c=>{
        const t=c.querySelector('.title').textContent.toLowerCase();
        const d=c.querySelector('.desc').textContent.toLowerCase();
        c.style.display=(t.includes(q)||d.includes(q))?'':'none';
      });
    }
    searchBtn.onclick=()=>filterCards(searchInput.value);
    searchInput.addEventListener('keypress',e=>{
      if(e.key==='Enter'){e.preventDefault();filterCards(searchInput.value);}
    });

    // --- Simular envío de formulario ---
    document.getElementById('contactForm').addEventListener('submit',e=>{
      e.preventDefault();
      document.getElementById('msg').style.display='block';
      e.target.reset();
      setTimeout(()=>{document.getElementById('msg').style.display='none';},4000);
    });
  </script>
</body>
</html>

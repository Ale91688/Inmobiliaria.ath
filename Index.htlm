<!DOCTYPE html>
<html lang="es"><head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="description" content="ATH Bienes Raíces: departamentos, casas, terrenos y cabañas en Córdoba y las sierras. Tasación gratuita. Escribinos por WhatsApp.">
<meta property="og:title" content="ATH Bienes Raíces | Comprá y vendé en Córdoba">
<meta property="og:description" content="Departamentos, casas, terrenos y cabañas en Córdoba y las sierras.">
<meta name="theme-color" content="#000000">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;800&amp;display=swap">
<title>ATH Bienes Raíces | Comprá y vendé en Córdoba</title>
<style>
/* ===== Colores tomados del logo ===== */
:root{
  --bg:#000; --panel:#0b1218; --line:#1b2a36;
  --teal:#1fb28f; --blue:#2467c4; --navy:#123a6b;
  --text:#f2f6f8; --muted:#9fb0bb;
  --grad:linear-gradient(135deg,var(--teal),var(--blue));
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth;scroll-padding-top:70px}
body{background:var(--bg);color:var(--text);font-family:"Plus Jakarta Sans","Segoe UI",system-ui,sans-serif;line-height:1.6}
a{color:inherit;text-decoration:none}
:focus-visible{outline:2px solid var(--teal);outline-offset:3px}
.wrap{max-width:1080px;margin:0 auto;padding:0 22px}
section{padding:84px 0}
h1,h2,h3{line-height:1.15;font-weight:800;letter-spacing:-.02em}
h2{font-size:clamp(1.7rem,4vw,2.4rem);margin-bottom:14px}
p.lead{color:var(--muted);max-width:60ch}

/* Navegación */
nav{position:sticky;top:0;z-index:10;background:rgba(0,0,0,.85);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
nav .wrap{display:flex;align-items:center;justify-content:space-between;height:62px}
.logo{font-weight:800;font-size:1.15rem}
.logo svg{display:block;margin:0 auto}
nav .logo svg{margin:0}
nav a.mini{font-size:.9rem;padding:8px 16px;border-radius:99px;border:1px solid var(--teal);color:var(--teal)}

/* Botones */
.btn{display:inline-block;padding:15px 30px;border-radius:99px;background:var(--grad);color:#fff;font-weight:700;border:0;cursor:pointer;font:inherit;font-weight:700;transition:transform .2s,box-shadow .2s}
.btn:hover{transform:translateY(-2px);box-shadow:0 10px 30px rgba(31,178,143,.3)}

/* Hero: techo en A con los colores del logo */
.hero{padding:96px 0 110px;position:relative;overflow:hidden}
.hero::before{content:"";position:absolute;right:-8%;top:8%;width:min(520px,80vw);aspect-ratio:1;background:var(--grad);opacity:.16;clip-path:polygon(50% 0,100% 100%,80% 100%,50% 30%,20% 100%,0 100%);pointer-events:none}
.hero h1{font-size:clamp(2.3rem,7vw,4.4rem);max-width:15ch;margin-bottom:20px;animation:in .9s ease both}
.hero p{font-size:1.15rem;color:var(--muted);max-width:46ch;margin-bottom:32px;animation:in .9s .15s ease both}
.hero .btn{animation:in .9s .3s ease both}
.hero small{display:block;margin-top:26px;color:var(--muted)}
@keyframes in{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:none}}

/* Beneficios */
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:38px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:28px}
.card svg{width:34px;height:34px;stroke:var(--teal);fill:none;stroke-width:1.8;margin-bottom:16px}
.card h3{font-size:1.15rem;margin-bottom:8px}
.card p{color:var(--muted);font-size:.97rem}


/* Propiedades */
.filters{display:flex;flex-wrap:wrap;gap:10px;margin:26px 0 8px}
.filters button{background:none;border:1px solid var(--line);color:var(--muted);padding:9px 18px;border-radius:99px;font:inherit;cursor:pointer;transition:all .2s}
.filters button[aria-pressed="true"]{background:var(--grad);border-color:transparent;color:#fff;font-weight:700}
.prop{background:var(--panel);border:1px solid var(--line);border-radius:16px;overflow:hidden;display:flex;flex-direction:column}
.prop .ph{aspect-ratio:4/3;background:linear-gradient(135deg,var(--navy),#0d2a2a);display:grid;place-items:center;color:var(--teal);font-weight:700}
.prop .ph img{width:100%;height:100%;object-fit:contain;display:block;background:#000;cursor:zoom-in}
.prop .in{padding:20px;display:flex;flex-direction:column;gap:6px;flex:1}
.prop .tag{font-size:.82rem;color:var(--teal);font-weight:700}
.prop h3{font-size:1.1rem}
.prop .zona,.prop .det{color:var(--muted);font-size:.93rem}
.prop .precio{font-weight:800;font-size:1.1rem;margin-top:auto;padding-top:10px}
.prop .btn{padding:11px 20px;text-align:center;margin-top:10px;font-size:.95rem}



/* Menú y botón flotante de WhatsApp */
.menu{display:flex;gap:22px;font-size:.92rem;color:var(--muted)}
.menu a:hover{color:var(--teal)}
.btn.ghost{background:none;border:1px solid var(--teal);color:var(--teal);margin-left:10px}
.wa{position:fixed;right:18px;bottom:calc(18px + env(safe-area-inset-bottom,0px));z-index:20;width:58px;height:58px;border-radius:50%;background:var(--grad);display:grid;place-items:center;box-shadow:0 8px 24px rgba(0,0,0,.5)}
.wa svg{width:30px;height:30px;fill:#fff}
.flinks{display:flex;justify-content:center;gap:20px;flex-wrap:wrap;margin-top:16px;font-size:.92rem}
.flinks a{color:var(--muted)}.flinks a:hover{color:var(--teal)}
@media(max-width:800px){.menu{display:none}.btn.ghost{margin:12px 0 0}}


/* Carrusel de fotos */
.prop .ph{position:relative;background:#000}
.ph .pv,.ph .nx{position:absolute;top:50%;transform:translateY(-50%);width:36px;height:36px;border-radius:50%;border:0;background:rgba(0,0,0,.6);color:#fff;font-size:1.4rem;line-height:1;cursor:pointer}
.ph .pv{left:10px}.ph .nx{right:10px}
.ph .ct{position:absolute;right:10px;bottom:10px;background:rgba(0,0,0,.65);color:#fff;font-size:.8rem;padding:3px 10px;border-radius:99px}


/* Visor de fotos */
#lb{position:fixed;inset:0;z-index:60;background:rgba(0,0,0,.95);display:flex;align-items:center;justify-content:center}
#lb[hidden]{display:none}
#lb img{max-width:92vw;max-height:88vh;object-fit:contain}
#lb button{position:absolute;background:rgba(255,255,255,.12);color:#fff;border:0;border-radius:50%;width:44px;height:44px;font-size:1.6rem;cursor:pointer}
#lb .lbp{left:12px}#lb .lbn{right:12px}#lb .lbx{top:calc(14px + env(safe-area-inset-top,0px));right:14px}

/* Panel admin */
#adm{position:fixed;inset:0;z-index:50;background:rgba(0,0,0,.88);overflow:auto;padding:24px 16px}
#adm[hidden],#adm [hidden]{display:none}
.adm-box{max-width:640px;margin:0 auto;background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:26px}
.adm-box h3{margin-bottom:14px}
.adm-box form{max-width:none;margin-top:0}
.adm-row{display:flex;justify-content:space-between;gap:10px;align-items:center;padding:10px 0;border-bottom:1px solid var(--line);font-size:.95rem}
.adm-row button,.adm-x{background:none;border:1px solid var(--line);color:var(--text);border-radius:8px;padding:6px 12px;cursor:pointer;font:inherit}
.adm-x{margin-bottom:12px}
#adm-msg{color:var(--teal);margin-top:12px;font-size:.92rem}
.adm-link{background:none;border:0;color:var(--muted);font:inherit;font-size:.8rem;cursor:pointer;margin-top:14px;text-decoration:underline}

/* Sobre nosotros */
.about{display:grid;grid-template-columns:1.2fr 1fr;gap:44px;align-items:center}
.badge{border:1px solid var(--line);border-radius:20px;padding:34px;text-align:center;background:radial-gradient(circle at 50% 0,rgba(36,103,196,.25),transparent 70%)}
.badge b{display:block;font-size:2.6rem;background:var(--grad);-webkit-background-clip:text;background-clip:text;color:transparent}
.badge span{color:var(--muted);font-size:.95rem}

/* Testimonios */
.quote{border-left:3px solid var(--teal);background:var(--panel);border-radius:0 14px 14px 0;padding:24px}
.quote p{margin-bottom:12px}
.quote cite{color:var(--muted);font-style:normal;font-size:.9rem}

/* Formulario */
form{max-width:560px;margin-top:30px;display:grid;gap:14px}
input,select,textarea{width:100%;background:var(--panel);border:1px solid var(--line);border-radius:12px;color:var(--text);padding:14px 16px;font:inherit}
input:focus,select:focus,textarea:focus{border-color:var(--teal);outline:none}
label{font-size:.9rem;color:var(--muted);display:grid;gap:6px}

/* Footer */
footer{border-top:1px solid var(--line);padding:44px 0 60px;text-align:center}
.social{display:flex;justify-content:center;gap:14px;margin:20px 0}
.social a{display:flex;align-items:center;gap:8px;padding:10px 20px;border-radius:99px;border:1px solid var(--line);transition:border-color .2s,color .2s}
.social a:hover{border-color:var(--teal);color:var(--teal)}
.social svg{width:20px;height:20px;fill:currentColor}
footer p{color:var(--muted);font-size:.9rem}

/* Aparición al hacer scroll (suave) */
.rv{opacity:0;transform:translateY(24px);transition:opacity .7s ease,transform .7s ease}
.rv.on{opacity:1;transform:none}

@media(max-width:800px){
  section{padding:60px 0}
  .grid3,.about{grid-template-columns:1fr}
}
@media(prefers-reduced-motion:reduce){
  *{animation:none!important;transition:none!important}
  .rv{opacity:1;transform:none}
}
</style>
</head>
<body>
<!-- Logo ATH (recreado en vectores) -->
<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <defs>
    <linearGradient id="lg" x1="0" y1="0.5" x2="1" y2="0.5"><stop offset="0" stop-color="#2f8fb0"></stop><stop offset="1" stop-color="#93d95a"></stop></linearGradient>
  </defs>
  <symbol id="ath" viewBox="0 0 200 200">
    <circle cx="100" cy="100" r="97" fill="none" stroke="#3a3f45" stroke-width="3"></circle>
    <circle cx="100" cy="100" r="91" fill="#143a7a"></circle>
    <circle cx="100" cy="100" r="82" fill="url(#lg)" stroke="#fff" stroke-width="1.5"></circle>
    <path d="M46 84 L100 40 L154 84" fill="none" stroke="#fff" stroke-width="9" stroke-linejoin="miter"></path>
    <path d="M58 92 L100 58 L142 92" fill="none" stroke="#fff" stroke-width="3"></path>
    <g fill="#fff" font-family="Segoe UI,Arial,sans-serif" text-anchor="middle">
      <text x="72" y="118" font-size="38" font-weight="300">A</text>
      <text x="100" y="128" font-size="38" font-weight="300">T</text>
      <text x="128" y="118" font-size="38" font-weight="300">H</text>
      <text x="100" y="146" font-size="12.5" font-weight="700">BIENES RAÍCES</text>
      <text x="100" y="158" font-size="7.5">CPCPI 5337</text>
    </g>
  </symbol>
</svg>

<nav>
  <div class="wrap">
    <a href="#inicio" class="logo" aria-label="ATH Bienes Raíces"><svg width="46" height="46"><use href="#ath"></use></svg></a>
    <div class="menu"><a href="#propiedades">Propiedades</a><a href="#nosotros">Nosotros</a><a href="#testimonios">Clientes</a><a href="#contacto">Contacto</a></div>
    <a class="mini" href="https://wa.link/gnlrln" target="_blank" rel="noopener">WhatsApp</a>
  </div>
</nav>

<!-- 1. HERO -->
<header class="hero" id="inicio">
  <div class="wrap">
    <h1>Comprá o vendé tu propiedad en Córdoba</h1>
    <p>Te acompañamos en todo el proceso: desde tasar tu propiedad hasta encontrar tu departamento, casa, terreno o cabaña en las sierras.</p>
    <a class="btn" href="https://wa.link/gnlrln" target="_blank" rel="noopener">Escribinos por WhatsApp</a><a class="btn ghost" href="#propiedades">Ver propiedades</a>
    <small>Matrícula CPCPI 5337</small>
  </div>
</header>

<!-- 2. BENEFICIOS -->
<section id="beneficios">
  <div class="wrap">
    <h2 class="rv">Por qué elegirnos</h2>
    <p class="lead rv">Un servicio cercano, con precios reales de mercado y propiedades pensadas para vivir o invertir.</p>
    <div class="grid3">
      <div class="card rv">
        <svg viewBox="0 0 24 24"><path d="M3 20h18M6 20V9l6-5 6 5v11M10 20v-5h4v5"></path></svg>
        <h3>Tasación gratuita</h3>
        <p>Tasamos tu propiedad y te damos el valor real de mercado.</p>
      </div>
      <div class="card rv">
        <svg viewBox="0 0 24 24"><path d="M3 17l6-6 4 4 8-8M15 7h6v6"></path></svg>
        <h3>Inversión con rentabilidad</h3>
        <p>Cabañas y terrenos en las sierras para generar ingresos todo el año.</p>
      </div>
      <div class="card rv">
        <svg viewBox="0 0 24 24"><path d="M21 12a8 8 0 0 1-12 7l-5 1 1-4.5A8 8 0 1 1 21 12z"></path></svg>
        <h3>Atención directa</h3>
        <p>Hablás con nosotros por WhatsApp, sin vueltas ni intermediarios.</p>
      </div>
    </div>
  </div>
</section>

<!-- PROPIEDADES: se cargan desde la lista PROPIEDADES en el script -->
<section id="propiedades">
  <div class="wrap">
    <h2 class="rv">Propiedades disponibles</h2>
    <p class="lead rv">Departamentos, casas, cabañas y terrenos en Córdoba y las sierras.</p>
    <div class="filters" id="filters" role="group" aria-label="Filtrar por tipo"></div>
    <div class="grid3" id="lista"></div>
  </div>
</section>

<!-- 3. SOBRE NOSOTROS -->
<section id="nosotros">
  <div class="wrap about">
    <div class="rv">
      <h2>Sobre nosotros</h2>
      <p class="lead">ATH Bienes Raíces es una inmobiliaria de Córdoba especializada en departamentos, casas, terrenos y cabañas estilo alpino en las Sierras de Córdoba. Cada propiedad tiene una historia, y trabajamos para que empiece la próxima con vos.</p>
    </div>
    <div class="badge rv">
      <b>CPCPI 5337</b>
      <span>Profesionales matriculados en Córdoba</span>
    </div>
  </div>
</section>

<!-- 4. TESTIMONIOS (reemplazá por los de tus clientes reales) -->
<section id="testimonios">
  <div class="wrap">
    <h2 class="rv">Lo que dicen nuestros clientes</h2>
    <div class="grid3">
      <blockquote class="quote rv"><p>“Nos tasaron la casa rápido y con un precio justo. Vendimos en pocas semanas.”</p><cite>Cliente vendedor, Córdoba</cite></blockquote>
      <blockquote class="quote rv"><p>“Nos ayudaron a elegir un terreno en las sierras. Todo claro y sin sorpresas.”</p><cite>Cliente comprador</cite></blockquote>
      <blockquote class="quote rv"><p>“Respondieron siempre por WhatsApp, muy atentos en todo el proceso.”</p><cite>Cliente inversor</cite></blockquote>
    </div>
  </div>
</section>

<!-- 5. CONTACTO -->
<section id="contacto">
  <div class="wrap">
    <h2 class="rv">Contanos qué buscás</h2>
    <p class="lead rv">Completá el formulario y te respondemos por WhatsApp.</p>
    <form id="form" class="rv" __gcruniqueid="1">
      <label>Nombre<input name="nombre" required="" autocomplete="name" __gcruniqueid="2"></label>
      <label>Teléfono<input name="tel" type="tel" required="" autocomplete="tel" __gcruniqueid="3"></label>
      <label>Quiero
        <select name="tipo" __gcruniqueid="4">
          <option>Comprar</option><option>Vender</option><option>Tasar mi propiedad</option><option>Invertir</option>
        </select>
      </label>
      <label>Mensaje<textarea name="msg" rows="4" __gcruniqueid="5"></textarea></label>
      <button class="btn" type="submit">Enviar por WhatsApp</button>
    </form>
  </div>
</section>

<!-- 6. FOOTER CON REDES -->
<footer>
  <div class="wrap">
    <div class="logo"><svg width="110" height="110" role="img" aria-label="ATH Bienes Raíces"><use href="#ath"></use></svg></div>
    <div class="flinks"><a href="#propiedades">Propiedades</a><a href="#nosotros">Nosotros</a><a href="#contacto">Contacto</a></div>
    <div class="social">
      <a href="https://www.instagram.com/inmobiliaria.ath" target="_blank" rel="noopener" aria-label="Instagram">
        <svg viewBox="0 0 24 24"><path d="M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5zm0 2a3 3 0 0 0-3 3v10a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3H7zm5 3.5A4.5 4.5 0 1 1 7.5 12 4.5 4.5 0 0 1 12 7.5zm0 2A2.5 2.5 0 1 0 14.5 12 2.5 2.5 0 0 0 12 9.5zM17.3 5.7a1 1 0 1 1-1 1 1 1 0 0 1 1-1z"></path></svg>
        inmobiliaria.ath
      </a>
      <a href="https://www.tiktok.com/@ath_inmobiliaria" target="_blank" rel="noopener" aria-label="TikTok">
        <svg viewBox="0 0 24 24"><path d="M16.6 2h-3.2v13.2a2.9 2.9 0 1 1-2-2.8V9.1a6.1 6.1 0 1 0 5.2 6.1V8.6a7.2 7.2 0 0 0 4.2 1.3V6.7A4.2 4.2 0 0 1 16.6 2z"></path></svg>
        @ath_inmobiliaria
      </a>
    </div>
    <p>Córdoba, Argentina · 351 642 0785 · CPCPI 5337</p>
    <button class="adm-link" id="adm-open" type="button">Acceso administrador</button>
  </div>
</footer>

<!-- Botón flotante de WhatsApp -->
<a class="wa" href="https://wa.link/gnlrln" target="_blank" rel="noopener" aria-label="Escribinos por WhatsApp">
  <svg viewBox="0 0 24 24"><path d="M12 2a10 10 0 0 0-8.6 15L2 22l5.2-1.4A10 10 0 1 0 12 2zm5.2 14.2c-.2.6-1.3 1.2-1.8 1.2-.5.1-1 .2-3.3-.7-2.8-1.2-4.6-4-4.7-4.2-.1-.2-1.1-1.5-1.1-2.8s.7-2 1-2.3c.2-.3.5-.3.7-.3h.5c.2 0 .4 0 .6.5l.8 2c.1.2.1.4 0 .6l-.4.6c-.2.2-.3.4-.1.7.2.3.8 1.3 1.7 2.1 1.2 1 2.1 1.3 2.4 1.5.3.1.5.1.7-.1l.9-1.1c.2-.3.4-.2.7-.1l1.9.9c.3.1.5.2.5.4.1.2.1.8-.1 1.4z"></path></svg>
</a>

<div id="lb" hidden role="dialog" aria-label="Fotos"><button class="lbx" aria-label="Cerrar">×</button><button class="lbp" aria-label="Anterior">‹</button><img id="lbi" alt=""><button class="lbn" aria-label="Siguiente">›</button></div>

<div id="adm" role="dialog" aria-label="Panel de administración" hidden="">
  <div class="adm-box">
    <button class="adm-x" id="adm-close" type="button">Cerrar</button>
    <div id="adm-login">
      <h3>Acceso administrador</h3>
      <form id="f-login" __gcruniqueid="6"><label>Clave<input type="password" id="clave" required="" __gcruniqueid="7"></label><button class="btn" type="submit">Entrar</button></form>
    </div>
    <div id="adm-panel" hidden="">
      <h3>Propiedades cargadas</h3>
      <div id="adm-list"></div>
      <h3 style="margin-top:26px" id="adm-tit">Agregar propiedad</h3>
      <form id="f-prop" __gcruniqueid="8">
        <label>Tipo<select name="tipo" __gcruniqueid="9"><option>Departamento</option><option>Casa</option><option>Cabaña</option><option>Terreno</option></select></label>
        <label>Título<input name="titulo" required="" __gcruniqueid="10"></label>
        <label>Zona<input name="zona" required="" __gcruniqueid="11"></label>
        <label>Detalle (ambientes, m², etc.)<input name="detalle" __gcruniqueid="12"></label>
        <label>Precio<input name="precio" placeholder="USD 85.000 o Consultar" __gcruniqueid="13"></label>
        <label>Fotos (mínimo 5, máximo 10)<input type="file" name="foto" accept="image/*" multiple=""></label>
        <button class="btn" type="submit" id="adm-add">Agregar a la lista</button>
      </form>
      <button class="btn" type="button" id="adm-save" style="margin-top:18px;width:100%">Guardar y publicar cambios</button>
      <p id="adm-msg"></p>
    </div>
  </div>
</div>
<script id="data" type="application/json">[{"tipo": "Departamento", "titulo": "Departamento en Córdoba capital", "zona": "Córdoba capital", "detalle": "Completar ambientes y m²", "precio": "Consultar", "fotos": []}, {"tipo": "Casa", "titulo": "Casa en  Venta 2 dormitorios Barrio Norte Villa Allende", "zona": "Barrio Norte Villa Allende", "detalle": "2 dormitorios 2 baños 107 m2 cubiertos cochera semi cubierta. Total  180 m2 súper.", "precio": "117.000 usd", "fotos": []}, {"tipo": "Cabaña", "titulo": "Construcción de Cabañas  Alpinas", "zona": "Sierras de Córdoba", "detalle": "Ideal vivir o alquilar 47 m2  estandar y modelo premium 2 dormitorios y 2 baños 2  uno en suite, sauna seco opcional", "precio": "19.500 usd", "fotos": []}, {"tipo": "Terreno", "titulo": "Terreno en las sierras", "zona": "Sierras de Córdoba", "detalle": "Completar superficie", "precio": "Consultar", "fotos": []}]</script>
<script>
let PROPIEDADES=JSON.parse(document.getElementById('data').textContent).map(p=>({...p,fotos:p.fotos||(p.foto?[p.foto]:[])}));
const WA='https://wa.me/543516420785?text=';
const lista=document.getElementById('lista'), filters=document.getElementById('filters');
function pintar(f){
  lista.innerHTML=PROPIEDADES.map((p,n)=>({p,n})).filter(({p})=>f==='Todas'||p.tipo===f).map(({p,n})=>`
    <article class="prop">
      <div class="ph" data-n="${n}" data-i="0">${p.fotos.length?`<img src="${p.fotos[0]}" alt="${p.titulo}" loading="lazy">${p.fotos.length>1?`<button class="pv" aria-label="Foto anterior">‹</button><button class="nx" aria-label="Foto siguiente">›</button><span class="ct">1/${p.fotos.length}</span>`:''}`:p.tipo}</div>
      <div class="in">
        <span class="tag">${p.tipo}</span>
        <h3>${p.titulo}</h3>
        <span class="zona">${p.zona}</span>
        <span class="det">${p.detalle}</span>
        <span class="precio">${p.precio}</span>
        <a class="btn" target="_blank" rel="noopener" href="${WA+encodeURIComponent('Hola, me interesa: '+p.titulo)}">Consultar</a>
      </div>
    </article>`).join('');
}
/* Visor: tocá una foto para verla completa */
let lbN=0,lbI=0;const lb=document.getElementById('lb');
const lbShow=()=>document.getElementById('lbi').src=PROPIEDADES[lbN].fotos[lbI];
lista.addEventListener('click',e=>{const im=e.target.closest('.ph img');if(!im)return;const ph=im.parentNode;lbN=+ph.dataset.n;lbI=+ph.dataset.i;lbShow();lb.hidden=false});
lb.addEventListener('click',e=>{const L=PROPIEDADES[lbN].fotos.length;
  if(e.target.closest('.lbp')){lbI=(lbI+L-1)%L;lbShow()}
  else if(e.target.closest('.lbn')){lbI=(lbI+1)%L;lbShow()}
  else if(e.target.id!=='lbi')lb.hidden=true});
document.addEventListener('keydown',e=>{if(e.key==='Escape')lb.hidden=true});
/* Pasar fotos de cada propiedad */
lista.addEventListener('click',e=>{const b=e.target.closest('.pv,.nx');if(!b)return;
  const ph=b.parentNode,p=PROPIEDADES[+ph.dataset.n],L=p.fotos.length;
  const i=(+ph.dataset.i+(b.classList.contains('nx')?1:L-1))%L;
  ph.dataset.i=i;ph.querySelector('img').src=p.fotos[i];ph.querySelector('.ct').textContent=(i+1)+'/'+L});
['Todas',...new Set(PROPIEDADES.map(p=>p.tipo))].forEach((t,i)=>{
  const b=document.createElement('button');b.textContent=t;b.setAttribute('aria-pressed',i===0);
  b.onclick=()=>{filters.querySelectorAll('button').forEach(x=>x.setAttribute('aria-pressed',x===b));pintar(t)};
  filters.appendChild(b);
});
pintar('Todas');

/* Aparición suave al hacer scroll */
const io = new IntersectionObserver((es)=>es.forEach(e=>{
  if(e.isIntersecting){e.target.classList.add('on');io.unobserve(e.target)}
}),{threshold:.15});
document.querySelectorAll('.rv').forEach(el=>io.observe(el));

/* El formulario abre WhatsApp con el mensaje armado */
document.getElementById('form').addEventListener('submit',e=>{
  e.preventDefault();
  const f=new FormData(e.target);
  const t=`Hola, soy ${f.get('nombre')}. Quiero: ${f.get('tipo')}. Mi teléfono: ${f.get('tel')}. ${f.get('msg')||''}`;
  window.open('https://wa.me/543516420785?text='+encodeURIComponent(t),'_blank');
});

/* ====== PANEL ADMIN ====== */
const HASH="c257b0dd62e576d65051ba91d58c3a7c4f45f42e04c75f3055cf401ddddde791"; /* SHA-256 de la clave */
const $=id=>document.getElementById(id); let ed=-1, fotoTmp=null;
const msg=t=>$('adm-msg').textContent=t;
const sha=async t=>[...new Uint8Array(await crypto.subtle.digest('SHA-256',new TextEncoder().encode(t)))].map(x=>x.toString(16).padStart(2,'0')).join('');
const redim=f=>new Promise(r=>{const i=new Image();i.onload=()=>{const k=Math.min(1,800/Math.max(i.width,i.height)),c=document.createElement('canvas');c.width=i.width*k;c.height=i.height*k;c.getContext('2d').drawImage(i,0,0,c.width,c.height);r(c.toDataURL('image/jpeg',.68))};i.src=URL.createObjectURL(f)});
function listar(){
  $('adm-list').innerHTML=PROPIEDADES.map((p,n)=>`<div class="adm-row"><span>${p.tipo} · ${p.titulo} (${p.fotos.length} fotos)</span><span><button data-e="${n}">Editar</button> <button data-d="${n}">Quitar</button></span></div>`).join('')||'<p>No hay propiedades.</p>';
}
$('adm-open').onclick=()=>$('adm').hidden=false;
$('adm-close').onclick=()=>$('adm').hidden=true;
$('f-login').onsubmit=async e=>{e.preventDefault();
  if(await sha($('clave').value)===HASH){$('adm-login').hidden=true;$('adm-panel').hidden=false;listar()}else{$('clave').value='';$('clave').placeholder='Clave incorrecta'}};
$('adm-list').onclick=e=>{const d=e.target.dataset;
  if(d.d!==undefined&&confirm('¿Quitar esta propiedad?')){PROPIEDADES.splice(+d.d,1);listar();pintar('Todas');msg('Quitada. Falta publicar los cambios.')}
  if(d.e!==undefined){ed=+d.e;const p=PROPIEDADES[ed],f=$('f-prop');['tipo','titulo','zona','detalle','precio'].forEach(k=>f[k].value=p[k]);$('adm-tit').textContent='Editar propiedad';$('adm-add').textContent='Guardar edición'}};
$('f-prop').onsubmit=async e=>{e.preventDefault();const f=e.target,p={};
  ['tipo','titulo','zona','detalle','precio'].forEach(k=>p[k]=f[k].value.trim());
  p.precio=p.precio||'Consultar';
  const files=[...f.foto.files];
  if((ed<0||files.length)&&(files.length<5||files.length>10)){msg('Elegí entre 5 y 10 fotos (elegiste '+files.length+').');return}
  msg('Procesando fotos…');
  p.fotos=files.length?await Promise.all(files.map(redim)):PROPIEDADES[ed].fotos;
  if(ed>=0)PROPIEDADES[ed]=p;else PROPIEDADES.push(p);
  ed=-1;f.reset();$('adm-tit').textContent='Agregar propiedad';$('adm-add').textContent='Agregar a la lista';
  listar();pintar('Todas');msg('Lista actualizada. Falta publicar los cambios.')};
$('adm-save').onclick=async()=>{
  const art=await (window.claude&&claude.use('artifact'));
  if(!art){msg('Este panel solo publica desde la cuenta dueña de la página.');return}
  const c=document.documentElement.cloneNode(true);
  [...c.attributes].forEach(a=>{if(a.name!=='lang')c.removeAttribute(a.name)}); /* saca atributos que agrega el navegador */
  c.querySelector('#lista').innerHTML='';c.querySelector('#filters').innerHTML='';
  c.querySelector('#adm').setAttribute('hidden','');c.querySelector('#lb').setAttribute('hidden','');c.querySelector('#lbi').removeAttribute('src');
  c.querySelector('#adm-list').innerHTML='';c.querySelector('#adm-msg').textContent='';
  c.querySelector('#adm-panel').setAttribute('hidden','');c.querySelector('#adm-login').removeAttribute('hidden');
  c.querySelectorAll('.rv.on').forEach(x=>x.classList.remove('on'));
  c.querySelector('#data').textContent=JSON.stringify(PROPIEDADES).replace(/</g,'\\u003c');
  msg('Publicando…');
  try{await art.publish('<!DOCTYPE html>\n'+c.outerHTML)}catch(err){msg('No se pudo publicar: '+(err.code||err.message)+'. Tenés que ser la persona dueña de la página.')}};
</script>


</body></html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Optimización Creativa · Ingeniería de Sistemas</title>
  <meta name="description" content="Sitio creativo sobre rendimiento, estabilidad y optimización en Ingeniería de Sistemas (sin mencionar límites)." />
  <style>
    :root{
      --bg:#070a12;
      --surface:#0b1222;
      --panel:#0f1830;
      --text:#e6eefc;
      --muted:#a4b0cf;
      --neon1:#22d3ee;  /* cyan */
      --neon2:#a78bfa;  /* violet */
      --neon3:#34d399;  /* green */
      --warn:#fbbf24;   /* amber */
      --danger:#fb7185; /* rose */
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,sans-serif;
      background: var(--bg);
      color:var(--text);
      overflow-x:hidden;
    }

    /* ===== Partículas de fondo (canvas) ===== */
    #stars{position:fixed;inset:0;z-index:-1;background:radial-gradient(1200px 600px at 80% -10%, #16213e55 0%, transparent 65%),
                                           radial-gradient(900px 400px at -10% 10%, #0ea5b81a 0%, transparent 65%),
                                           radial-gradient(900px 400px at 110% 50%, #8b5cf61a 0%, transparent 65%);}    

    /* ===== Header / Nav ===== */
    header{
      position:sticky; top:0; z-index:50; backdrop-filter: blur(10px);
      background:linear-gradient(180deg, rgba(7,10,18,.9), rgba(7,10,18,.5));
      border-bottom:1px solid #1e293b;
    }
    nav{max-width:1200px;margin:auto;display:flex;align-items:center;justify-content:space-between;padding:16px 20px}
    .brand{display:flex;gap:.7rem;align-items:center;font-weight:800;letter-spacing:.3px}
    .dot{width:12px;height:12px;border-radius:50%;background:var(--neon1);box-shadow:0 0 16px var(--neon1),0 0 32px var(--neon2)}
    .grad{background:linear-gradient(90deg,var(--neon1),var(--neon2));-webkit-background-clip:text;background-clip:text;color:transparent}
    .links a{color:var(--muted);text-decoration:none;margin:0 10px;font-size:.95rem;position:relative}
    .links a:after{content:"";position:absolute;left:0;bottom:-6px;height:2px;width:0;background:linear-gradient(90deg,var(--neon1),var(--neon2));box-shadow:0 0 12px var(--neon1);transition:.3s}
    .links a:hover{color:#fff}
    .links a:hover:after{width:100%}

    .container{max-width:1200px;margin:0 auto;padding:28px 20px}

    /* ===== Hero ===== */
    .hero{display:grid;grid-template-columns:1.2fr .8fr;gap:28px;align-items:center}
    .panel{background:linear-gradient(180deg, #0b1229, #0b1229ee);border:1px solid #1f2a48;border-radius:18px;padding:20px;box-shadow:0 10px 40px #0006}
    .pill{display:inline-flex;gap:.45rem;align-items:center;padding:6px 10px;border:1px solid #334155;border-radius:999px;color:#cbd5e1;font-size:.8rem;margin-bottom:12px}
    h1{font-size:clamp(1.7rem, 2.8vw, 2.6rem);line-height:1.15;margin:.2rem 0}
    p.lead{color:#d1d5db;max-width:62ch}

    /* ===== Tarjetas KPI ===== */
    .kpi{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:12px}
    .card{background:linear-gradient(180deg, #0b1229, #0b1229e6);border:1px solid #1f2a48;border-radius:16px;padding:16px;transition:transform .25s ease, box-shadow .25s ease}
    .card:hover{transform:translateY(-6px);box-shadow:0 20px 50px #0008}
    .muted{color:var(--muted)}

    /* ===== Botones ===== */
    .btn{appearance:none;border:none;background:linear-gradient(90deg,var(--neon1),var(--neon2));color:#0b1120;font-weight:800;padding:11px 14px;border-radius:12px;cursor:pointer;letter-spacing:.3px;box-shadow:0 0 20px #22d3ee33;transition:filter .2s, transform .2s}
    .btn:hover{filter:saturate(1.2) brightness(1.1);transform:translateY(-2px)}

    /* ===== Grilla Demos ===== */
    .grid{display:grid;grid-template-columns:repeat(12,1fr);gap:16px}
    .col-6{grid-column:span 6}
    .col-4{grid-column:span 4}
    .col-8{grid-column:span 8}

    /* ===== Chip / Tags ===== */
    .tag{display:inline-block;background:#0a0f22;border:1px dashed #233059;color:#93c5fd;padding:4px 8px;border-radius:999px;font-size:.75rem;margin:2px}

    /* ===== Tabla ===== */
    .table{width:100%;border-collapse:collapse}
    .table th,.table td{border-bottom:1px solid #1f2a48;padding:10px;text-align:left}
    .table th{color:#cbd5e1;font-weight:600}

    /* ===== Canvas mini-chart ===== */
    .chart-wrap{position:relative;height:180px;background:linear-gradient(180deg,#0a1123,#0c1631);border:1px solid #1f2a48;border-radius:14px;overflow:hidden}
    .chart-wrap canvas{width:100%;height:100%}

    /* ===== Icon Cards (flip) ===== */
    .flipgrid{display:grid;grid-template-columns:repeat(4,1fr);gap:12px}
    .flip{perspective:1000px}
    .flip > div{position:relative;transform-style:preserve-3d;transition:transform .6s}
    .flip:hover > div{transform:rotateY(180deg)}
    .face{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;padding:18px;border-radius:14px;background:linear-gradient(180deg,#0b1229,#0b1229ee);border:1px solid #1f2a48}
    .back{transform:rotateY(180deg)}
    .emoji{font-size:2rem;filter:drop-shadow(0 0 10px #22d3ee60)}

    /* ===== Footer ===== */
    .foot{margin-top:30px;font-size:.9rem;color:#94a3b8}

    @media (max-width: 980px){
      .hero{grid-template-columns:1fr}
      .col-6,.col-4,.col-8{grid-column:span 12}
      .flipgrid{grid-template-columns:repeat(2,1fr)}
    }
  </style>
</head>
<body>
  <!-- Fondo animado -->
  <canvas id="stars"></canvas>

  <header>
    <nav>
      <div class="brand"><span class="dot"></span> <span class="grad">Optimización × Ing. de Sistemas</span></div>
      <div class="links">
        <a href="#vision">Visión</a>
        <a href="#aplicaciones">Aplicaciones</a>
        <a href="#demos">Demos</a>
        <a href="#showcase">Showcase</a>
      </div>
    </nav>
  </header>

  <main class="container">
    <!-- HERO -->
    <section class="hero panel" id="vision">
      <div>
        <span class="pill">Rendimiento • Estabilidad • Precisión</span>
        <h1>De <span class="grad">la teoría</span> al <span class="grad">despliegue</span>: cómo diseñamos sistemas que se acercan a su desempeño ideal.</h1>
        <p class="lead">En sistemas reales buscamos que los procesos <strong>se estabilicen</strong>, que el rendimiento <strong>se acerque a un valor objetivo</strong> y que el error <strong>tienda a desaparecer</strong> con mejores decisiones de diseño. Aquí lo contamos con visuales.
        </p>
        <div class="kpi">
          <div class="card"><strong>Estabilidad</strong><span class="muted small">¿Tu algoritmo converge o oscila?</span></div>
          <div class="card"><strong>Rendimiento pico</strong><span class="muted small">¿Dónde está el tope útil bajo carga?</span></div>
          <div class="card"><strong>Precisión</strong><span class="muted small">¿Qué tan pequeño puede ser el error?</span></div>
        </div>
      </div>
      <div class="card">
        <h2>Idea central</h2>
        <p class="muted small">Cuando aumentamos la carga, iteramos un algoritmo o refinamos un cálculo, observamos <em>tendencias</em>: el desempeño se acerca a un valor estable, o el error se reduce hacia cero. Eso guía decisiones de arquitectura y optimización.</p>
        <div>
          <span class="tag">análisis de algoritmos</span>
          <span class="tag">procesamiento de señales</span>
          <span class="tag">sistemas distribuidos</span>
          <span class="tag">computación numérica</span>
        </div>
      </div>
    </section>

    <!-- TABLA/APLICACIONES -->
    <section id="aplicaciones" class="panel" style="margin-top:16px">
      <h2>Aplicaciones rápidas en Ingeniería de Sistemas</h2>
      <table class="table">
        <thead>
          <tr><th>Área</th><th>Idea</th><th>¿Para qué sirve?</th></tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Análisis de algoritmos</strong></td>
            <td>Comportamiento extremo cuando crece la entrada</td>
            <td>Comparar rendimientos y elegir estructuras eficientes</td>
          </tr>
          <tr>
            <td><strong>Optimización y ML</strong></td>
            <td>Gradientes y búsqueda de mínimos estables</td>
            <td>Entrenar modelos, ajustar hiperparámetros, evaluar convergencia</td>
          </tr>
          <tr>
            <td><strong>Procesamiento digital de señales</strong></td>
            <td>Series, filtros y estabilidad de respuestas</td>
            <td>Evitar aliasing, controlar ruido y resonancias</td>
          </tr>
          <tr>
            <td><strong>Sistemas y colas</strong></td>
            <td>Tendencia de throughput y tiempos de espera</td>
            <td>Detectar saturación y escalar servicios</td>
          </tr>
          <tr>
            <td><strong>Computación numérica</strong></td>
            <td>Refinar paso para reducir error</td>
            <td>Resultados fiables en simulaciones y gráficos</td>
          </tr>
          <tr>
            <td><strong>Control en tiempo discreto</strong></td>
            <td>Estados que se estabilizan con realimentación</td>
            <td>Diseños robustos frente a perturbaciones</td>
          </tr>
        </tbody>
      </table>
    </section>

    <!-- DEMOS INTERACTIVAS -->
    <section id="demos" class="grid" style="margin-top:16px">
      <!-- Demo 1: Rendimiento que se acerca a objetivo -->
      <div class="col-6 card">
        <h2>Demo — Rendimiento acercándose al objetivo</h2>
        <p class="small muted">Simulamos un sistema que mejora por iteraciones y se aproxima a su desempeño ideal.</p>
        <div class="chart-wrap"><canvas id="chart1"></canvas></div>
        <div style="display:flex;gap:10px;align-items:center;margin-top:10px">
          <button class="btn" id="run1">Iterar</button>
          <button class="btn" id="reset1" style="background:linear-gradient(90deg,#fb7185,#fbbf24)">Reiniciar</button>
          <span class="muted small">Objetivo: <strong id="goalTxt">90</strong>%</span>
        </div>
      </div>

      <!-- Demo 2: Cola/Throughput bajo carga -->
      <div class="col-6 card">
        <h2>Demo — Carga vs. rendimiento útil</h2>
        <p class="small muted">Aumenta usuarios concurrentes y observa cómo el rendimiento se acerca a un tope práctico.</p>
        <input id="users" type="range" min="10" max="2000" value="150" style="width:100%" />
        <div class="chart-wrap" style="margin-top:10px"><canvas id="chart2"></canvas></div>
        <div style="display:flex;gap:10px;align-items:center;margin-top:10px">
          <span class="muted small">Usuarios: <strong id="usersVal">150</strong></span>
          <span class="muted small">Rendimiento estimado: <strong id="tpVal">—</strong> req/s</span>
        </div>
      </div>
    </section>

    <!-- ICONOS / SHOWCASE -->
    <section id="showcase" class="panel" style="margin-top:16px">
      <h2>Showcase — ¿Dónde lo vemos en la práctica?</h2>
      <div class="flipgrid" style="margin-top:10px">
        <div class="flip">
          <div>
            <div class="face front"><span class="emoji">🤖</span></div>
            <div class="face back"><span class="muted">ML: descenso de gradiente estabiliza el entrenamiento.</span></div>
          </div>
        </div>
        <div class="flip">
          <div>
            <div class="face front"><span class="emoji">🛰️</span></div>
            <div class="face back"><span class="muted">Señales: filtros que no explotan ante ruido.</span></div>
          </div>
        </div>
        <div class="flip">
          <div>
            <div class="face front"><span class="emoji">🕸️</span></div>
            <div class="face back"><span class="muted">Redes: throughput cerca del tope de hardware.</span></div>
          </div>
        </div>
        <div class="flip">
          <div>
            <div class="face front"><span class="emoji">🧮</span></div>
            <div class="face back"><span class="muted">Cómputo numérico: error que se reduce al refinar.</span></div>
          </div>
        </div>
      </div>
      <p class="foot">Tip: explica <em>qué variable</em> se acerca a <em>qué valor objetivo</em> y <em>cómo</em> ayuda a decidir arquitectura, escalado y pruebas.</p>
    </section>
  </main>

  <footer class="container" style="opacity:.9">
    <div class="panel">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <span class="small">Proyecto creativo — Ingeniería de Sistemas • Autor: Jorge Stiven Nova Herrera</span>
        <button class="btn" id="toTop" aria-label="volver al inicio">⬆ Volver arriba</button>
      </div>
    </div>
  </footer>

  <script>
    /* ===== Fondo de partículas tipo "neón" ===== */
    (function(){
      const c = document.getElementById('stars');
      const ctx = c.getContext('2d');
      let w,h,particles=[];
      const N = 160; // cantidad de partículas
      function resize(){ w = c.width = window.innerWidth; h = c.height = window.innerHeight; }
      window.addEventListener('resize', resize); resize();
      function spawn(){
        particles = Array.from({length:N}, _=>({
          x: Math.random()*w,
          y: Math.random()*h,
          vx: (Math.random()-.5)*0.4,
          vy: (Math.random()-.5)*0.4,
          r: Math.random()*1.7+0.3,
          c: Math.random()<.5? 'rgba(34,211,238,.8)' : 'rgba(167,139,250,.8)'
        }));
      }
      spawn();
      function step(){
        ctx.clearRect(0,0,w,h);
        for(const p of particles){
          p.x+=p.vx; p.y+=p.vy;
          if(p.x<0||p.x>w) p.vx*=-1;
          if(p.y<0||p.y>h) p.vy*=-1;
          ctx.beginPath();
          ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
          ctx.shadowColor = p.c; ctx.shadowBlur = 8; ctx.fillStyle = p.c; ctx.fill();
        }
        requestAnimationFrame(step);
      }
      step();
    })();

    // Utilidad
    const $ = s => document.querySelector(s);

    /* ===== Demo 1: sistema que se acerca a un objetivo ===== */
    (function(){
      const canvas = $('#chart1');
      const ctx = canvas.getContext('2d');
      let W, H; const PAD=12; function fit(){ canvas.width = canvas.clientWidth; canvas.height = canvas.clientHeight; W=canvas.width; H=canvas.height; }
      window.addEventListener('resize', fit); fit();

      let data = []; const goal = 90; let y = 10; // valor inicial
      const friction = 0.14; // qué tan rápido nos acercamos
      const noise = 2.2;      // pequeñas variaciones
      const maxPts = 120;

      function push(val){ data.push(val); if(data.length>maxPts) data.shift(); }
      function step(){
        const err = (goal - y);
        y += err*friction + (Math.random()*2-1)*noise;
        y = Math.max(0, Math.min(100, y));
        push(y);
        draw();
      }
      function draw(){
        ctx.clearRect(0,0,W,H);
        // Ejes simples
        ctx.strokeStyle = '#22324f'; ctx.lineWidth = 1; ctx.beginPath();
        for(let i=0;i<6;i++){ const yy = PAD + (H-2*PAD)*i/5; ctx.moveTo(PAD,yy); ctx.lineTo(W-PAD,yy);}
        ctx.stroke();
        // Objetivo
        const yg = PAD + (H-2*PAD) * (1 - goal/100);
        ctx.strokeStyle = '#22d3ee88'; ctx.setLineDash([6,6]); ctx.beginPath(); ctx.moveTo(PAD, yg); ctx.lineTo(W-PAD, yg); ctx.stroke(); ctx.setLineDash([]);
        // Línea de datos
        if(data.length>1){
          ctx.beginPath();
          for(let i=0;i<data.length;i++){
            const x = PAD + (W-2*PAD)*(i/(maxPts-1));
            const v = data[i];
            const ypix = PAD + (H-2*PAD) * (1 - v/100);
            if(i===0) ctx.moveTo(x, ypix); else ctx.lineTo(x, ypix);
          }
          ctx.strokeStyle = '#a78bfa'; ctx.lineWidth = 2.2; ctx.shadowColor = '#a78bfa'; ctx.shadowBlur = 8; ctx.stroke(); ctx.shadowBlur=0;
        }
      }
      let timer=null; function run(){ if(timer) return; timer = setInterval(step, 80); }
      function reset(){ data=[]; y = 10; draw(); clearInterval(timer); timer=null; }
      $('#run1').addEventListener('click', run);
      $('#reset1').addEventListener('click', reset);
      document.getElementById('goalTxt').textContent = goal;
      reset();
    })();

    /* ===== Demo 2: throughput vs. usuarios ===== */
    (function(){
      const canvas = $('#chart2');
      const ctx = canvas.getContext('2d');
      let W, H; const PAD=12; function fit(){ canvas.width = canvas.clientWidth; canvas.height = canvas.clientHeight; W=canvas.width; H=canvas.height; }
      window.addEventListener('resize', fit); fit();

      const users = $('#users'); const usersVal = $('#usersVal'); const tpVal = $('#tpVal');
      function model(u){
        // Modelo logístico sencillo para rendimiento práctico (req/s)
        const cap = 1200; // tope práctico de hardware
        const k = 0.0065; // pendiente
        return cap/(1+Math.exp(-k*(u-600))) - 60; // corrige offset
      }
      function draw(u){
        usersVal.textContent = u;
        const tp = Math.max(0, Math.round(model(u)));
        tpVal.textContent = tp;
        ctx.clearRect(0,0,W,H);
        // Fondo cuadriculado
        ctx.strokeStyle = '#22324f'; ctx.beginPath(); for(let i=0;i<6;i++){ const yy = PAD+(H-2*PAD)*i/5; ctx.moveTo(PAD,yy); ctx.lineTo(W-PAD,yy);} ctx.stroke();
        // Curva completa
        ctx.beginPath();
        for(let i=0;i<=50;i++){
          const ux = 10 + (1990)*i/50;
          const x = PAD + (W-2*PAD) * ((ux-10)/(1990));
          const yv = Math.max(0, Math.min(1200, model(ux)));
          const y = PAD + (H-2*PAD) * (1 - yv/1200);
          if(i===0) ctx.moveTo(x,y); else ctx.lineTo(x,y);
        }
        ctx.strokeStyle = '#22d3ee'; ctx.lineWidth = 2; ctx.shadowColor = '#22d3ee'; ctx.shadowBlur = 10; ctx.stroke(); ctx.shadowBlur=0;
        // Punto actual
        const x = PAD + (W-2*PAD) * ((u-10)/(1990));
        const yv = Math.max(0, Math.min(1200, model(u)));
        const y = PAD + (H-2*PAD) * (1 - yv/1200);
        ctx.beginPath(); ctx.arc(x,y,5,0,Math.PI*2); ctx.fillStyle = '#a78bfa'; ctx.shadowColor = '#a78bfa'; ctx.shadowBlur = 12; ctx.fill(); ctx.shadowBlur=0;
      }
      users.addEventListener('input', e=> draw(parseInt(e.target.value,10)));
      draw(parseInt(users.value,10));
    })();

    // Botón volver arriba
    document.getElementById('toTop').addEventListener('click', ()=> window.scrollTo({top:0,behavior:'smooth'}));
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Tecnología para Humanistas</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,380;0,9..144,600;0,9..144,680;1,9..144,420&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --paper: #ECE6D6;
    --ink: #221F19;
    --ink-soft: #55503F;
    --teal: #2E5C4F;
    --rust: #A63D2A;
    --line: #B7A98C;
  }
  *{box-sizing:border-box;}
  html,body{margin:0;padding:0;background:#d8d2c0;}
  body{
    display:flex;
    justify-content:center;
    padding:32px 12px;
    font-family:'Fraunces', serif;
    color:var(--ink);
  }
  .sheet{
    width:1080px;
    max-width:100%;
    aspect-ratio:1080/1350;
    background:var(--paper);
    position:relative;
    overflow:hidden;
    box-shadow:0 30px 60px rgba(0,0,0,0.25);
    display:flex;
    flex-direction:column;
  }

  /* ---------- HERO ---------- */
  .hero{
    position:relative;
    height:56%;
    background:var(--ink);
    overflow:hidden;
    flex-shrink:0;
  }
  .hero svg{
    position:absolute;
    inset:0;
    width:100%;
    height:100%;
  }
  .hero-title{
    position:absolute;
    left:56px;
    bottom:34px;
    right:56px;
    z-index:3;
  }
  .hero-title .eyebrow{
    font-family:'IBM Plex Mono', monospace;
    font-size:12px;
    letter-spacing:0.08em;
    color:#D8D2C0;
    margin-bottom:10px;
  }
  .hero-title h1{
    margin:0;
    font-family:'Fraunces', serif;
    font-weight:600;
    font-size:74px;
    line-height:0.96;
    color:var(--paper);
    letter-spacing:-0.01em;
  }
  .hero-title h1 em{
    font-style:italic;
    font-weight:420;
    color:#8CBBAA;
  }

  /* ---------- BODY ---------- */
  .body{
    flex:1;
    padding:30px 56px 0 56px;
    position:relative;
  }
  .hook{
    font-style:italic;
    font-weight:420;
    font-size:25px;
    line-height:1.35;
    max-width:640px;
    margin:0 0 24px 0;
    border-left:3px solid var(--rust);
    padding-left:18px;
  }

  .tags{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    margin-bottom:26px;
  }
  .tag{
    font-family:'IBM Plex Mono', monospace;
    font-size:13px;
    letter-spacing:0.02em;
    color:var(--ink);
    border:1px solid var(--ink);
    padding:6px 14px;
    border-radius:999px;
  }

  .facts{
    display:flex;
    flex-wrap:wrap;
    gap:22px 34px;
    font-family:'IBM Plex Mono', monospace;
    font-size:14px;
    color:var(--ink-soft);
    padding-top:20px;
    border-top:1px solid var(--line);
  }
  .facts div{white-space:nowrap;}
  .facts b{color:var(--ink); font-weight:600;}

  /* ---------- FOOTER ---------- */
  .footer{
    background:var(--ink);
    color:var(--paper);
    padding:24px 56px 30px 56px;
    margin-top:auto;
  }
  .footer .badge{
    display:inline-block;
    font-family:'IBM Plex Mono', monospace;
    font-size:12px;
    letter-spacing:0.05em;
    color:var(--paper);
    background:var(--rust);
    padding:4px 10px;
    margin-bottom:16px;
  }
  .footer-grid{
    display:flex;
    justify-content:space-between;
    align-items:flex-end;
    gap:20px;
  }
  .footer-left .line{
    font-family:'IBM Plex Mono', monospace;
    font-size:15px;
    line-height:1.9;
    color:#D8D2C0;
  }
  .footer-left .line b{color:var(--paper); font-weight:600;}
  .price{ text-align:right; }
  .price .amount{
    font-family:'Fraunces', serif;
    font-weight:600;
    font-size:46px;
    line-height:1;
    color:var(--paper);
  }
  .price .amount span{
    font-size:20px;
    vertical-align:middle;
    font-weight:420;
  }
  .price .cta{
    margin-top:8px;
    font-family:'IBM Plex Mono', monospace;
    font-size:13px;
    color:#8CBBAA;
  }
</style>
</head>
<body>
  <div class="sheet">

    <div class="hero">
      <svg viewBox="0 0 1080 756" preserveAspectRatio="xMidYMax slice" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <clipPath id="headClip">
            <path d="M470 640
                     C 380 640 330 560 330 470
                     C 330 380 350 330 330 290
                     C 312 254 320 200 360 168
                     C 400 136 470 128 520 150
                     C 560 168 590 150 630 160
                     C 690 176 730 230 730 300
                     C 730 340 715 360 725 390
                     C 738 428 740 470 720 505
                     C 705 530 705 560 680 585
                     C 650 616 590 640 520 640
                     Z"/>
          </clipPath>
        </defs>

        <!-- faint full-bleed binary field -->
        <g font-family="IBM Plex Mono" font-size="15" fill="#3A3529">
          <text x="0" y="40">01 10 00 11 01 10 01 11 00 10 01 11 01 10 00 11 01 10 01 11 00 10</text>
          <text x="0" y="80">10 01 11 00 01 10 01 11 01 00 11 10 01 00 11 01 10 00 11 01 10 01</text>
          <text x="0" y="120">00 11 01 10 01 11 00 10 01 11 01 10 00 11 01 10 01 11 00 10 01 11</text>
          <text x="0" y="160">11 00 10 01 11 01 10 00 11 01 10 01 11 00 10 01 11 01 10 00 11 01</text>
          <text x="0" y="200">01 10 00 11 01 10 01 11 00 10 01 11 01 10 00 11 01 10 01 11 00 10</text>
          <text x="0" y="240">10 01 11 00 01 10 01 11 01 00 11 10 01 00 11 01 10 00 11 01 10 01</text>
          <text x="0" y="700">00 11 01 10 01 11 00 10 01 11 01 10 00 11 01 10 01 11 00 10 01 11</text>
          <text x="0" y="740">11 00 10 01 11 01 10 00 11 01 10 01 11 00 10 01 11 01 10 00 11 01</text>
        </g>

        <!-- circuit traces emanating -->
        <g stroke="#4A6E62" stroke-width="2" fill="none" opacity="0.9">
          <path d="M730 300 H 860 V 220 H 950"/>
          <path d="M725 390 H 830 V 460 H 940"/>
          <path d="M700 560 H 780 V 630 H 900"/>
          <path d="M360 200 H 250 V 130 H 140"/>
          <path d="M330 380 H 210 V 420 H 90"/>
          <path d="M400 600 H 300 V 670 H 170"/>
        </g>
        <g fill="#4A6E62">
          <circle cx="950" cy="220" r="6"/>
          <circle cx="940" cy="460" r="6"/>
          <circle cx="900" cy="630" r="6"/>
          <circle cx="140" cy="130" r="6"/>
          <circle cx="90" cy="420" r="6"/>
          <circle cx="170" cy="670" r="6"/>
        </g>

        <!-- head silhouette filled with binary -->
        <g clip-path="url(#headClip)">
          <rect x="0" y="0" width="1080" height="756" fill="#1A2E27"/>
          <g font-family="IBM Plex Mono" font-size="16" fill="#8CBBAA">
            <text x="300" y="180">0110 1001 0011 1010 0110 1001 0011</text>
            <text x="280" y="215">1010 0110 1001 0011 1010 0110 1001</text>
            <text x="290" y="250">0011 1010 0110 1001 0011 1010 0110</text>
            <text x="300" y="285">1001 0011 1010 0110 1001 0011 1010</text>
            <text x="280" y="320">0110 1001 0011 1010 0110 1001 0011</text>
            <text x="290" y="355">1010 0110 1001 0011 1010 0110 1001</text>
            <text x="300" y="390">0011 1010 0110 1001 0011 1010 0110</text>
            <text x="280" y="425">1001 0011 1010 0110 1001 0011 1010</text>
            <text x="290" y="460">0110 1001 0011 1010 0110 1001 0011</text>
            <text x="300" y="495">1010 0110 1001 0011 1010 0110 1001</text>
            <text x="280" y="530">0011 1010 0110 1001 0011 1010 0110</text>
            <text x="290" y="565">1001 0011 1010 0110 1001 0011 1010</text>
            <text x="300" y="600">0110 1001 0011 1010 0110 1001 0011</text>
          </g>
          <!-- warm glow where the "mind" is, representing human thought -->
          <circle cx="480" cy="330" r="90" fill="#A63D2A" opacity="0.55"/>
          <circle cx="480" cy="330" r="46" fill="#ECE6D6" opacity="0.9"/>
        </g>
        <path d="M470 640
                 C 380 640 330 560 330 470
                 C 330 380 350 330 330 290
                 C 312 254 320 200 360 168
                 C 400 136 470 128 520 150
                 C 560 168 590 150 630 160
                 C 690 176 730 230 730 300
                 C 730 340 715 360 725 390
                 C 738 428 740 470 720 505
                 C 705 530 705 560 680 585
                 C 650 616 590 640 520 640
                 Z" fill="none" stroke="#ECE6D6" stroke-width="2.5"/>

        <!-- fade to ink at bottom for text legibility -->
        <rect x="0" y="560" width="1080" height="196" fill="url(#fade)"/>
        <defs>
          <linearGradient id="fade" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0" stop-color="#221F19" stop-opacity="0"/>
            <stop offset="1" stop-color="#221F19" stop-opacity="1"/>
          </linearGradient>
        </defs>
      </svg>

      <div class="hero-title">
        <div class="eyebrow">curso virtual · primera edición</div>
        <h1>Tecnología para<br><em>humanistas</em></h1>
      </div>
    </div>

    <div class="body">
      <p class="hook">Entiende qué pasa detrás de la pantalla — sin necesidad de volverte programador.</p>

      <div class="tags">
        <span class="tag">Comunicadores</span>
        <span class="tag">Psicólogos</span>
        <span class="tag">Artistas y creativos</span>
        <span class="tag">Humanistas de todo tipo</span>
      </div>

      <div class="facts">
        <div>💻 <b>Virtual</b></div>
        <div>🕒 <b>10 sesiones</b> · 90 min</div>
        <div>🧠 <b>Sin conocimientos previos</b></div>
        <div>🧪 <b>Laboratorio interactivo</b></div>
      </div>
    </div>

    <div class="footer">
      <span class="badge">precio especial de lanzamiento</span>
      <div class="footer-grid">
        <div class="footer-left">
          <div class="line">Inicio: <b>[FECHA DE INICIO]</b> · <b>[HORARIO]</b></div>
          <div class="line">Inscripciones: <b>[LINK / CONTACTO]</b></div>
        </div>
        <div class="price">
          <div class="amount"><span>Bs</span> 150</div>
          <div class="cta">inscríbete ahora →</div>
        </div>
      </div>
    </div>

  </div>
</body>
</html>

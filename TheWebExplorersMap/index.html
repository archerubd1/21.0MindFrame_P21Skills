<!DOCTYPE html>
<html lang="en" data-theme="light" style=""><head>
<meta charset="utf-8">
<meta content="width=device-width, initial-scale=1.0" name="viewport">
<title>Slide 1 — The Web Explorer’s Map</title>
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&amp;display=swap" rel="stylesheet">
<style>
    /* Fixed 1280x720 slide canvas */
    html, body { height: 100%; }
    body{
      margin:0;
      background:#111827;
      font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      display:flex;
      align-items:center;
      justify-content:center;
    }

    .slide{
      width:1280px;
      height:720px;
      position:relative;
      display:flex;
      flex-direction:column;
      overflow:hidden;
      border-radius:24px;
      box-shadow: 0 24px 70px rgba(0,0,0,.35);
      background:#F6D3C0; /* fallback */
    }

    /* IMPORTANT: No CSS gradients (export-safe).
       Use layered soft color blocks to mimic peach + light blue blend. */
    .bg{
      position:absolute;
      inset:0;
      z-index:0;
      background:#FFE1CF;
    }
    .bg .peach{
      position:absolute;
      left:-120px;
      top:-120px;
      width:760px;
      height:760px;
      background:#FFDAB9;
      border-radius:60px;
      opacity:.95;
      transform: rotate(10deg);
      box-shadow: 0 30px 80px rgba(31,41,55,.12);
    }
    .bg .blue{
      position:absolute;
      right:-160px;
      bottom:-160px;
      width:900px;
      height:900px;
      background:#ADD8E6;
      border-radius:80px;
      opacity:.85;
      transform: rotate(-8deg);
      box-shadow: 0 30px 80px rgba(31,41,55,.12);
    }
    .bg .mist{
      position:absolute;
      left:260px;
      top:120px;
      width:760px;
      height:520px;
      background:#FFFFFF;
      border-radius:48px;
      opacity:.35;
      box-shadow: 0 22px 60px rgba(31,41,55,.10);
    }

    header{
      position:absolute;
      top:0;
      left:0;
      right:0;
      height:64px;
      z-index:3;
      background:rgba(255,255,255,.85);
      backdrop-filter: blur(6px);
      display:flex;
      align-items:center;
      padding:0 28px;
      box-shadow: 0 8px 18px rgba(31,41,55,.10);
    }
    header .brand{
      display:flex;
      align-items:center;
      gap:12px;
      color:#0f172a;
      font-weight:700;
      letter-spacing:.2px;
    }
    header .badge{
      width:38px;
      height:38px;
      border-radius:12px;
      background:#0ea5e9;
      display:flex;
      align-items:center;
      justify-content:center;
      box-shadow: 0 10px 20px rgba(14,165,233,.25);
      flex:0 0 auto;
    }
    header .badge i{ color:white; font-size:16px; }

    footer{
      position:absolute;
      bottom:0;
      left:0;
      right:0;
      height:48px;
      z-index:3;
      background:rgba(255,255,255,.9);
      backdrop-filter: blur(6px);
      display:flex;
      align-items:center;
      justify-content:center;
      padding:0 18px;
      box-shadow: 0 -10px 24px rgba(31,41,55,.10);
    }
    footer p{
      margin:0;
      color:#334155;
      font-size:14px;
      font-weight:600;
      text-align:center;
      white-space:nowrap;
      overflow:hidden;
      text-overflow:ellipsis;
      max-width: 1200px;
    }

    /* Navigation bar must be above footer and never overlap */
    .nav{
      position:absolute;
      left:0;
      right:0;
      bottom:48px; /* exactly above footer */
      height:62px;
      z-index:3;
      display:flex;
      align-items:center;
      justify-content:space-between;
      padding:0 22px;
      background:rgba(255,255,255,.70);
      backdrop-filter: blur(6px);
      box-shadow: 0 -8px 18px rgba(31,41,55,.08);
    }

    .nav a{
      display:flex;
      align-items:center;
      gap:12px;
      padding:12px 16px;
      border-radius:16px;
      text-decoration:none;
      color:#0f172a;
      font-weight:800;
      letter-spacing:.2px;
      background:#ffffff;
      box-shadow: 0 10px 24px rgba(31,41,55,.10);
      transition: transform .16s ease, box-shadow .16s ease, opacity .16s ease;
      max-width: 380px;
    }
    .nav a:hover{
      transform: translateY(-2px);
      box-shadow: 0 14px 30px rgba(31,41,55,.14);
      opacity:.98;
    }
    .nav a[aria-disabled="true"]{
      opacity:.55;
      pointer-events:none;
    }
    .nav .hint{
      font-size:12px;
      font-weight:700;
      color:#64748b;
      margin-left:10px;
    }
    .nav .topic{
      display:flex;
      flex-direction:column;
      line-height:1.1;
    }
    .nav .topic p{
      margin:0;
      font-size:14px;
      color:#64748b;
      font-weight:800;
    }
    .nav .topic strong{
      font-size:16px;
      color:#0f172a;
      font-weight:900;
    }

    main{
      position:relative;
      z-index:2;
      display:flex;
      flex:1;
      flex-direction:column;
      padding:84px 64px 130px; /* top for header, bottom for nav+footer */
      gap:18px;
    }

    .hero{
      flex:1;
      display:flex;
      align-items:center;
      justify-content:center;
    }

    .hero-card{
      width:min(980px, 100%);
      border-radius:24px;
      background: rgba(255,255,255,.78);
      box-shadow: 0 26px 70px rgba(31,41,55,.14);
      padding:56px 56px 46px;
      display:flex;
      gap:34px;
      align-items:center;
    }

    .left-visual{
      width:250px;
      height:250px;
      border-radius:24px;
      background:#0ea5e9;
      box-shadow: 0 22px 46px rgba(14,165,233,.22);
      position:relative;
      flex:0 0 auto;
      overflow:hidden;
    }
    .left-visual .panel{
      position:absolute;
      inset:14px;
      border-radius:20px;
      background:#ffffff;
      box-shadow: inset 0 0 0 2px rgba(15,23,42,.06);
      display:flex;
      flex-direction:column;
      padding:14px;
      gap:10px;
    }
    .chip-row{
      display:flex;
      gap:10px;
    }
    .chip{
      height:14px;
      border-radius:999px;
      background:#e2e8f0;
      flex:1;
    }
    .chip.blue{ background:#cfefff; }
    .chip.peach{ background:#ffe6d6; }

    .mini-card{
      flex:1;
      border-radius:16px;
      background:#f8fafc;
      box-shadow: 0 10px 20px rgba(31,41,55,.08);
      padding:12px;
      display:flex;
      flex-direction:column;
      justify-content:center;
      gap:8px;
    }
    .mini-card .row{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:10px;
    }
    .dot{
      width:10px;
      height:10px;
      border-radius:999px;
      background:#22c55e;
      box-shadow: 0 6px 16px rgba(34,197,94,.18);
      flex:0 0 auto;
    }
    .line{
      height:10px;
      border-radius:999px;
      background:#e2e8f0;
      flex:1;
    }

    h1{
      margin:0;
      font-size:56px;
      line-height:1.05;
      color:#0f172a;
      font-weight:900;
      letter-spacing:-.6px;
    }
    .subtitle{
      margin:16px 0 0;
      font-size:24px;
      line-height:1.35;
      color:#334155;
      font-weight:600;
    }

    .tag-row{
      margin-top:22px;
      display:flex;
      gap:10px;
      flex-wrap:wrap;
    }
    .tag{
      display:inline-flex;
      align-items:center;
      gap:10px;
      padding:10px 14px;
      border-radius:999px;
      background:#ffffff;
      box-shadow: 0 10px 22px rgba(31,41,55,.10);
      color:#0f172a;
      font-weight:800;
      font-size:14px;
      white-space:nowrap;
    }
    .tag i{ color:#0ea5e9; }

    /* Responsiveness: scale down to fit smaller screens while keeping 1280x720 internal layout */
    .scale-wrap{
      width:1280px;
      height:720px;
      transform-origin: top left;
    }
    @media (max-width: 1320px), (max-height: 760px){
      body{ padding: 12px; }
      .scale-wrap{
        transform: scale(min(calc((100vw - 24px) / 1280), calc((100vh - 24px) / 720)));
      }
    }
  </style>
</head>
<body style="">
<div class="scale-wrap">
<section aria-label="The Web Explorer’s Map — Slide 1" class="slide" role="application">
<!-- Background layers (no gradients) -->
<div aria-hidden="true" class="bg">
<div class="peach"></div>
<div class="blue"></div>
<div class="mist"></div>
</div>
<!-- Header (mandatory) -->
<header>
<div class="brand">
<div aria-hidden="true" class="badge">
<i class="fa-solid fa-compass"></i>
</div>
<p style="margin:0; font-size:16px;">
            EduuAspire21.0 Skills | 21st Century Skills | Digital Literacy
          </p>
</div>
</header>
<!-- Main content -->
<main>
<div class="hero">
<div class="hero-card">
<div aria-hidden="true" class="left-visual">
<div class="panel">
<div class="chip-row">
<div class="chip blue"></div>
<div class="chip peach"></div>
<div class="chip"></div>
</div>
<div class="mini-card">
<div class="row">
<div class="dot"></div>
<div class="line"></div>
</div>
<div class="row">
<div class="dot" style="background:#0ea5e9; box-shadow: 0 6px 16px rgba(14,165,233,.18);"></div>
<div class="line" style="width:70%;"></div>
</div>
<div class="row">
<div class="dot" style="background:#f97316; box-shadow: 0 6px 16px rgba(249,115,22,.18);"></div>
<div class="line" style="width:55%;"></div>
</div>
</div>
<div class="chip-row">
<div class="chip"></div>
<div class="chip blue"></div>
</div>
</div>
</div>
<div style="flex:1; min-width: 0;">
<h1>The Web Explorer’s Map</h1>
<p class="subtitle">Learn Smart &amp; Safe Internet Navigation</p>
<div class="tag-row">
<span class="tag"><i aria-hidden="true" class="fa-solid fa-shield-halved"></i><span>Safe Browsing</span></span>
<span class="tag"><i aria-hidden="true" class="fa-solid fa-magnifying-glass"></i><span>Smart Search</span></span>
<span class="tag"><i aria-hidden="true" class="fa-solid fa-link"></i><span>Spot Fake Links</span></span>
</div>
</div>
</div>
</div>
</main>
<!-- Navigation (topic-based; positioned above footer; no overlap) -->
<nav aria-label="Slide navigation" class="nav">
<a aria-disabled="true" href="index.html" title="You are on the first slide">
<i aria-hidden="true" class="fa-solid fa-arrow-left"></i>
<div class="topic">
<p><br></p>
<strong>Start</strong>
</div>
</a>
<div class="hint">

</div>
<a href="f2.html" title="Go to Objective">
<div class="topic" style="text-align:right;">

<strong>Objective</strong>
</div>
<i aria-hidden="true" class="fa-solid fa-arrow-right"></i>
</a>
</nav>
<!-- Footer (mandatory) -->
<footer>
<p>Licenced &amp; Powered By Astrl Mind Technologies copyright 2026-2033</p>
</footer>
</section>
</div>
<script>
    // Keyboard navigation: ArrowLeft / ArrowRight
    // Disabled while typing in inputs/textareas/contenteditable
    (function () {
      const prevLink = document.querySelector('nav.nav a[aria-disabled="true"]') || document.querySelector('nav.nav a[href]');
      const nextLink = document.querySelector('nav.nav a[href="f2.html"]');

      function isTypingTarget(el) {
        if (!el) return false;
        const tag = (el.tagName || '').toLowerCase();
        return tag === 'input' || tag === 'textarea' || el.isContentEditable === true;
      }

      document.addEventListener('keydown', function (e) {
        if (isTypingTarget(document.activeElement)) return;

        if (e.key === 'ArrowRight') {
          if (nextLink) window.location.href = nextLink.getAttribute('href');
        }
        if (e.key === 'ArrowLeft') {
          // On slide 1, keep user here (no previous)
          // If you later enable wrap-around, change this section.
          e.preventDefault();
        }
      });
    })();
  </script>

</body></html>
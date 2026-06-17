# 402gabriel.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- ===================== SEO META ===================== -->
<title>SafeFleet Compliance | DOT Compliance Management for Trucking Fleets</title>
<meta name="description" content="SafeFleet Compliance helps trucking companies and drivers stay DOT compliant — hours-of-service monitoring, driver qualification files, drug & alcohol programs, CSA score management, and audit-ready record keeping.">
<meta name="keywords" content="DOT compliance, FMCSA compliance, trucking compliance, hours of service, ELD monitoring, CSA score, DOT audit, driver qualification files, drug and alcohol testing program">
<meta name="robots" content="index, follow">
<link rel="canonical" href="https://www.safefleetcompliance.com/">
<meta name="theme-color" content="#1E3A8A">

<!-- Open Graph / social preview -->
<meta property="og:type" content="website">
<meta property="og:title" content="SafeFleet Compliance | DOT Compliance Management for Trucking Fleets">
<meta property="og:description" content="Hours-of-service monitoring, driver qualification files, drug & alcohol programs, and audit prep — built for trucking fleets that can't afford downtime.">
<meta property="og:site_name" content="SafeFleet Compliance">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="SafeFleet Compliance | DOT Compliance Management for Trucking Fleets">
<meta name="twitter:description" content="Hours-of-service monitoring, driver qualification files, drug & alcohol programs, and audit prep for trucking fleets.">

<!-- Favicon (inline, no external asset) -->
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%231E3A8A'/%3E%3Cpath d='M32 12 50 19v13c0 13-8.5 20.5-18 24-9.5-3.5-18-11-18-24V19z' fill='%23F97316'/%3E%3Cpath d='M24 32l6 6 12-14' stroke='%23ffffff' stroke-width='4' fill='none' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wght@600;700;800;900&family=Inter:wght@400;500;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap" rel="stylesheet">

<style>
/* =========================================================
   TOKENS
========================================================= */
:root{
  --blue:#1E3A8A;
  --blue-700:#16306f;
  --blue-900:#0F1F3D;
  --blue-tint:#F1F5FB;
  --blue-tint-2:#E7EDFA;
  --border:#DCE3F0;
  --white:#FFFFFF;
  --orange:#F97316;
  --orange-dark:#D9590C;
  --orange-tint:#FFF1E6;
  --ink:#0F1F3D;
  --muted:#566181;
  --muted-on-blue:#C7D2EE;
  --radius:14px;
  --shadow-sm:0 1px 2px rgba(15,31,61,.06);
  --shadow-md:0 12px 28px -8px rgba(15,31,61,.18);
  --shadow-lg:0 24px 60px -16px rgba(15,31,61,.28);
  --maxw:1200px;
  --header-h:76px;
  --ease:cubic-bezier(.22,.61,.36,1);
}

*,*::before,*::after{box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{
  margin:0;
  font-family:'Inter',system-ui,-apple-system,sans-serif;
  color:var(--ink);
  background:var(--white);
  line-height:1.6;
  -webkit-font-smoothing:antialiased;
}
h1,h2,h3{
  font-family:'Archivo',system-ui,sans-serif;
  color:var(--blue-900);
  line-height:1.12;
  margin:0;
  letter-spacing:-0.01em;
}
p{margin:0;}
img,svg{display:block;max-width:100%;}
a{color:inherit;text-decoration:none;}
ul{margin:0;padding:0;list-style:none;}
button{font-family:inherit;}

:focus-visible{outline:2.5px solid var(--orange);outline-offset:3px;border-radius:4px;}

.container{
  max-width:var(--maxw);
  margin:0 auto;
  padding:0 24px;
}

.eyebrow{
  display:inline-flex;
  align-items:center;
  gap:8px;
  font-family:'IBM Plex Mono',monospace;
  font-weight:600;
  font-size:0.78rem;
  letter-spacing:.12em;
  text-transform:uppercase;
  color:var(--orange-dark);
  margin:0 0 14px;
}
.eyebrow svg{width:14px;height:14px;flex-shrink:0;}
.on-blue .eyebrow{color:#FFC299;}

.section-lede{
  font-size:1.05rem;
  color:var(--muted);
  max-width:62ch;
  margin-top:14px;
}

h2{font-size:clamp(1.7rem,3.6vw,2.5rem);}
h3{font-size:1.2rem;font-weight:700;}

.section{padding:88px 0;scroll-margin-top:var(--header-h);}
.alt-bg{background:var(--blue-tint);}

/* skip link */
.skip-link{
  position:absolute;left:-9999px;top:0;
  background:var(--blue);color:#fff;padding:10px 18px;border-radius:8px;z-index:200;
}
.skip-link:focus{left:16px;top:16px;}

/* =========================================================
   BUTTONS
========================================================= */
.btn{
  display:inline-flex;
  align-items:center;
  justify-content:center;
  gap:8px;
  font-weight:700;
  font-size:0.96rem;
  padding:14px 26px;
  border-radius:10px;
  border:2px solid transparent;
  cursor:pointer;
  transition:transform .18s var(--ease), box-shadow .18s var(--ease), background .18s var(--ease), color .18s var(--ease);
  white-space:nowrap;
}
.btn-primary{background:var(--orange);color:#fff;box-shadow:0 8px 20px -6px rgba(249,115,22,.55);}
.btn-primary:hover{background:var(--orange-dark);transform:translateY(-2px);}
.btn-outline{background:transparent;border-color:var(--blue);color:var(--blue);}
.btn-outline:hover{background:var(--blue);color:#fff;transform:translateY(-2px);}
.on-blue .btn-outline{border-color:#fff;color:#fff;}
.on-blue .btn-outline:hover{background:#fff;color:var(--blue);}
.btn-lg{padding:16px 30px;font-size:1.02rem;}
.btn-sm{padding:10px 18px;font-size:0.88rem;}

/* =========================================================
   HEADER
========================================================= */
.site-header{
  position:fixed;top:0;left:0;right:0;z-index:100;
  height:var(--header-h);
  display:flex;align-items:center;
  background:rgba(255,255,255,.92);
  backdrop-filter:saturate(180%) blur(10px);
  border-bottom:1px solid transparent;
  transition:box-shadow .25s var(--ease), border-color .25s var(--ease);
}
.site-header.is-scrolled{
  box-shadow:0 4px 18px rgba(15,31,61,.08);
  border-color:var(--border);
}
.header-inner{
  display:flex;align-items:center;justify-content:space-between;
  width:100%;
}
.brand{display:flex;align-items:center;gap:10px;}
.brand-mark{width:38px;height:38px;flex-shrink:0;}
.brand-text{font-family:'Archivo',sans-serif;font-weight:800;font-size:1.18rem;color:var(--blue-900);display:flex;flex-direction:column;line-height:1.05;}
.brand-sub{font-family:'IBM Plex Mono',monospace;font-weight:600;font-size:.62rem;letter-spacing:.16em;color:var(--orange-dark);}

.main-nav ul{display:flex;gap:32px;}
.main-nav a{
  font-weight:600;font-size:.95rem;color:var(--blue-900);
  position:relative;padding:6px 2px;
}
.main-nav a::after{
  content:"";position:absolute;left:0;right:100%;bottom:-2px;height:2px;background:var(--orange);
  transition:right .22s var(--ease);
}
.main-nav a:hover::after,.main-nav a.is-active::after{right:0;}

.header-actions{display:flex;align-items:center;gap:14px;}
.nav-toggle{
  display:flex;flex-direction:column;justify-content:center;gap:5px;
  width:42px;height:42px;border-radius:8px;border:1px solid var(--border);
  background:#fff;cursor:pointer;
}
.nav-toggle span{display:block;width:20px;height:2px;background:var(--blue-900);margin:0 auto;transition:transform .25s var(--ease),opacity .25s var(--ease);}
.nav-toggle[aria-expanded="true"] span:nth-child(1){transform:translateY(7px) rotate(45deg);}
.nav-toggle[aria-expanded="true"] span:nth-child(2){opacity:0;}
.nav-toggle[aria-expanded="true"] span:nth-child(3){transform:translateY(-7px) rotate(-45deg);}

@media (max-width:899px){
  .main-nav{
    position:fixed;top:var(--header-h);left:0;right:0;
    background:#fff;border-bottom:1px solid var(--border);
    max-height:0;overflow:hidden;
    transition:max-height .3s var(--ease);
    box-shadow:0 14px 24px -10px rgba(15,31,61,.12);
  }
  .main-nav.is-open{max-height:340px;}
  .main-nav ul{flex-direction:column;gap:0;padding:8px 24px 18px;}
  .main-nav li{border-top:1px solid var(--border);}
  .main-nav li:first-child{border-top:none;}
  .main-nav a{display:block;padding:14px 2px;}
  .main-nav a::after{display:none;}
  .header-actions .btn-sm{display:none;}
}
@media (min-width:900px){
  .nav-toggle{display:none;}
}

/* =========================================================
   HERO
========================================================= */
.hero{
  padding:calc(var(--header-h) + 64px) 0 80px;
  position:relative;
  overflow:hidden;
  background:
    repeating-linear-gradient(100deg, rgba(30,58,138,.05) 0 2px, transparent 2px 46px),
    linear-gradient(180deg,#FFFFFF 0%, var(--blue-tint) 100%);
}
.hero-inner{
  display:grid;
  gap:48px;
  align-items:center;
}
.hero h1{font-size:clamp(2.1rem,4.6vw,3.4rem);}
.hero-sub{font-size:1.08rem;color:var(--muted);max-width:48ch;margin-top:20px;}
.hero-ctas{display:flex;flex-wrap:wrap;gap:14px;margin-top:30px;}

.trust-stats{
  display:flex;flex-wrap:wrap;gap:30px;
  margin-top:42px;padding-top:26px;
  border-top:1px solid var(--border);
}
.trust-stats li{display:flex;flex-direction:column;}
.stat-num,.stat-num-text{
  font-family:'IBM Plex Mono',monospace;font-weight:700;
  font-size:1.55rem;color:var(--blue-900);
}
.stat-label{font-size:.82rem;color:var(--muted);margin-top:2px;}

/* dashboard mock card */
.hero-visual{position:relative;}
.dash-card{
  background:linear-gradient(160deg,var(--blue) 0%, var(--blue-700) 100%);
  border-radius:18px;
  padding:26px 26px 22px;
  box-shadow:var(--shadow-lg);
  color:#fff;
  max-width:420px;
  margin:0 auto;
  position:relative;
}
.dash-card::before{
  content:"";position:absolute;inset:0;border-radius:18px;
  background:radial-gradient(circle at 85% -10%, rgba(249,115,22,.25), transparent 55%);
  pointer-events:none;
}
.dash-card-header{
  display:flex;align-items:center;gap:10px;
  font-family:'IBM Plex Mono',monospace;font-size:.78rem;font-weight:600;
  letter-spacing:.06em;color:var(--muted-on-blue);text-transform:uppercase;
  margin-bottom:18px;
}
.dash-dot{width:8px;height:8px;border-radius:50%;background:var(--orange);}

.dash-gauge{display:flex;align-items:center;gap:18px;padding-bottom:18px;border-bottom:1px solid rgba(255,255,255,.16);margin-bottom:18px;}
.dash-gauge svg{width:92px;height:92px;flex-shrink:0;}
.gauge-score{font-family:'Archivo',sans-serif;font-size:1.8rem;font-weight:800;fill:#fff;}
.gauge-track{fill:none;stroke:rgba(255,255,255,.18);stroke-width:9;}
.gauge-fill{fill:none;stroke:var(--orange);stroke-width:9;stroke-linecap:round;
  stroke-dasharray:301.6; stroke-dashoffset:301.6;
  transform:rotate(-90deg);transform-origin:50% 50%;
  animation:gaugeFill 1.4s .3s var(--ease) forwards;
}
@keyframes gaugeFill{to{stroke-dashoffset:66.4;}}
.gauge-text-label{font-size:.92rem;font-weight:700;}
.gauge-text-sub{font-size:.78rem;color:var(--muted-on-blue);margin-top:3px;}

.dash-checklist li{
  display:flex;align-items:center;justify-content:space-between;
  font-size:.92rem;font-weight:500;padding:9px 0;
  border-bottom:1px dashed rgba(255,255,255,.14);
}
.dash-checklist li:last-child{border-bottom:none;}
.dash-check-label{display:flex;align-items:center;gap:9px;}
.dash-check-label svg{width:16px;height:16px;color:var(--orange);}
.dash-status{font-family:'IBM Plex Mono',monospace;font-size:.74rem;color:#BFE6C8;letter-spacing:.03em;}

.dash-sync{
  display:flex;align-items:center;gap:7px;
  margin-top:16px;font-size:.76rem;color:var(--muted-on-blue);
  font-family:'IBM Plex Mono',monospace;
}
.live-dot{width:6px;height:6px;border-radius:50%;background:#5AD46B;animation:pulse 1.8s ease-in-out infinite;}
@keyframes pulse{0%,100%{opacity:1;}50%{opacity:.35;}}

@media (min-width:860px){
  .hero-inner{grid-template-columns:1.05fr 0.95fr;}
}

/* =========================================================
   ROUTE RAIL (signature element)
========================================================= */
.rail-layout{display:grid;grid-template-columns:1fr;gap:0;}
.rail{display:none;}
@media (min-width:1024px){
  .rail-layout{grid-template-columns:64px 1fr;column-gap:8px;}
  .rail{
    display:block;position:relative;
    border-left:3px dashed var(--orange);
    margin-top:6px;height:100%;
    opacity:.55;
  }
  .rail-node{
    position:absolute;top:-2px;left:-13px;
    width:26px;height:26px;border-radius:50%;
    background:var(--blue);color:#fff;
    display:flex;align-items:center;justify-content:center;
    font-family:'IBM Plex Mono',monospace;font-size:.62rem;font-weight:700;
    box-shadow:0 0 0 4px #fff;
  }
  .rail-end .rail-node{background:var(--orange);}
}
@media (prefers-reduced-motion:reduce){
  .rail{opacity:.55;}
}

/* =========================================================
   SERVICES
========================================================= */
.card-grid{
  display:grid;gap:20px;margin-top:38px;
  grid-template-columns:1fr;
}
@media (min-width:640px){.card-grid{grid-template-columns:repeat(2,1fr);}}
@media (min-width:1024px){.card-grid{grid-template-columns:repeat(3,1fr);}}

.card{
  background:#fff;border:1px solid var(--border);border-radius:var(--radius);
  padding:26px 24px;box-shadow:var(--shadow-sm);
  transition:transform .25s var(--ease), box-shadow .25s var(--ease), border-color .25s var(--ease);
}
.card:hover{transform:translateY(-4px);box-shadow:var(--shadow-md);border-color:#C9D6F2;}
.card-icon{
  width:46px;height:46px;border-radius:10px;
  background:var(--blue-tint-2);color:var(--blue);
  display:flex;align-items:center;justify-content:center;
  margin-bottom:16px;
}
.card-icon svg{width:24px;height:24px;}
.card h3{margin-bottom:8px;}
.card p{color:var(--muted);font-size:.95rem;}

/* =========================================================
   BENEFITS (stat rows)
========================================================= */
.stat-grid{
  display:grid;gap:18px;margin-top:38px;
  grid-template-columns:1fr;
}
@media (min-width:640px){.stat-grid{grid-template-columns:repeat(2,1fr);}}
@media (min-width:1024px){.stat-grid{grid-template-columns:repeat(4,1fr);}}
.stat-box{
  background:#fff;border:1px solid var(--border);border-radius:var(--radius);
  padding:26px 22px;
}
.stat-box .stat-num{
  font-size:2.3rem;color:var(--blue);display:block;
}
.stat-box p{margin-top:8px;color:var(--muted);font-size:.92rem;}

/* =========================================================
   MID-PAGE CTA BANNER
========================================================= */
.cta-banner{
  background:var(--ink);
  color:#fff;
  border-radius:18px;
  padding:48px clamp(20px,5vw,52px);
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  text-align:center;
  gap:24px;
  margin:0 24px;
  max-width:calc(var(--maxw) - 0px);
  margin-inline:auto;
}
.cta-banner h3{
  color:#fff;
  font-size:1.4rem;
  max-width:30ch;
  margin-inline:auto;
}
.cta-banner p{
  color:var(--muted-on-blue);
  margin-top:6px;
  max-width:40ch;
  margin-inline:auto;
}
.cta-banner .eyebrow{
  margin-inline:auto;
}

/* =========================================================
   ABOUT
========================================================= */
.about-grid{
  display:grid;gap:42px;margin-top:36px;
  grid-template-columns:1fr;
}
@media (min-width:960px){.about-grid{grid-template-columns:1.1fr .9fr;}}

.numbers-list{display:grid;grid-template-columns:repeat(2,1fr);gap:20px;margin-top:26px;}
.numbers-list .stat-num{font-size:1.7rem;color:var(--blue);}
.numbers-list p{color:var(--muted);font-size:.85rem;margin-top:4px;}

.pill-row{display:flex;flex-wrap:wrap;gap:10px;margin-top:22px;}
.pill{
  font-family:'IBM Plex Mono',monospace;font-size:.76rem;font-weight:600;
  padding:8px 14px;border-radius:100px;
  background:var(--orange-tint);color:var(--orange-dark);
  border:1px solid #FBD9B8;
}

.about-card{
  background:var(--blue-tint);border-radius:var(--radius);
  padding:30px;border:1px solid var(--border);
}
.about-card h3{margin-bottom:14px;}
.about-card ul{display:flex;flex-direction:column;gap:14px;}
.about-card li{display:flex;gap:12px;font-size:.94rem;color:var(--muted);}
.about-card li svg{width:18px;height:18px;flex-shrink:0;color:var(--orange);margin-top:2px;}

/* =========================================================
   CONTACT
========================================================= */
.contact{
  background:linear-gradient(165deg,var(--blue) 0%, var(--blue-700) 100%);
  color:#fff;
  position:relative;
  overflow:hidden;
}
.contact::before{
  content:"";position:absolute;inset:0;
  background:repeating-linear-gradient(110deg, rgba(255,255,255,.035) 0 2px, transparent 2px 50px);
  pointer-events:none;
}
.contact h2{color:#fff;}
.contact .section-lede{color:var(--muted-on-blue);}

.contact-grid{
  display:grid;gap:34px;margin-top:42px;
  grid-template-columns:1fr;
  position:relative;
}
@media (min-width:960px){.contact-grid{grid-template-columns:1.3fr .9fr;}}

.contact-form{
  background:#fff;border-radius:18px;padding:clamp(22px,4vw,34px);
  box-shadow:var(--shadow-lg);color:var(--ink);
}
.form-row{display:grid;gap:16px;margin-bottom:16px;grid-template-columns:1fr;}
@media (min-width:560px){.form-row.two-col{grid-template-columns:1fr 1fr;}}
.field label{display:block;font-size:.85rem;font-weight:600;margin-bottom:6px;color:var(--blue-900);}
.field input,.field select,.field textarea{
  width:100%;padding:12px 14px;border-radius:9px;border:1.5px solid var(--border);
  font-family:inherit;font-size:.95rem;color:var(--ink);background:#fbfcfe;
  transition:border-color .2s, box-shadow .2s;
}
.field input:focus,.field select:focus,.field textarea:focus{
  border-color:var(--blue);box-shadow:0 0 0 3px rgba(30,58,138,.12);outline:none;
}
.field textarea{resize:vertical;min-height:110px;}
.field.has-error input,.field.has-error select,.field.has-error textarea{border-color:#DC2626;}
.error-msg{display:none;color:#DC2626;font-size:.8rem;margin-top:5px;}
.field.has-error .error-msg{display:block;}
.form-footnote{font-size:.78rem;color:var(--muted);margin-top:14px;}
.contact-form .btn-primary{width:100%;margin-top:6px;}

.success-panel{display:none;text-align:center;padding:30px 10px;}
.success-panel.is-visible{display:block;}
.contact-form.is-submitted .form-fields{display:none;}
.success-icon{
  width:56px;height:56px;border-radius:50%;background:var(--blue-tint);
  display:flex;align-items:center;justify-content:center;margin:0 auto 16px;color:var(--blue);
}
.success-icon svg{width:28px;height:28px;}

.contact-info{display:flex;flex-direction:column;gap:26px;}
.info-block{display:flex;gap:14px;}
.info-icon{
  width:42px;height:42px;border-radius:10px;background:rgba(255,255,255,.12);
  display:flex;align-items:center;justify-content:center;flex-shrink:0;color:var(--orange);
}
.info-icon svg{width:20px;height:20px;}
.info-block h3{color:#fff;font-size:1rem;margin-bottom:4px;}
.info-block p,.info-block a{color:var(--muted-on-blue);font-size:.92rem;}
.info-block a:hover{color:#fff;text-decoration:underline;}

/* =========================================================
   FOOTER
========================================================= */
.site-footer{background:var(--blue-900);color:var(--muted-on-blue);}
.footer-top{padding:64px 0 40px;display:grid;gap:40px;grid-template-columns:1fr;}
@media (min-width:760px){.footer-top{grid-template-columns:1.4fr 1fr 1fr 1fr;}}
.footer-brand .brand-text{color:#fff;}
.footer-brand p{margin-top:14px;font-size:.9rem;max-width:34ch;color:var(--muted-on-blue);}
.footer-col h3{color:#fff;font-size:.82rem;letter-spacing:.08em;text-transform:uppercase;font-family:'IBM Plex Mono',monospace;margin-bottom:16px;}
.footer-col ul{display:flex;flex-direction:column;gap:11px;}
.footer-col a{font-size:.92rem;}
.footer-col a:hover{color:#fff;}
.social-row{display:flex;gap:10px;margin-top:18px;}
.social-row a{
  width:36px;height:36px;border-radius:9px;background:rgba(255,255,255,.07);
  display:flex;align-items:center;justify-content:center;
}
.social-row a:hover{background:var(--orange);color:#fff;}
.social-row svg{width:17px;height:17px;}

.footer-bottom{
  border-top:1px solid rgba(255,255,255,.1);
  padding:24px 0 30px;
  font-size:.8rem;color:#8FA0C9;
  display:flex;flex-wrap:wrap;gap:10px 24px;justify-content:space-between;
}
.footer-bottom .disclaimer{max-width:64ch;}
.footer-bottom .credit{width:100%;font-family:'IBM Plex Mono',monospace;font-size:.74rem;color:#6E81AC;border-top:1px solid rgba(255,255,255,.08);padding-top:14px;margin-top:4px;}

/* =========================================================
   REVEAL ANIMATIONS
========================================================= */
.reveal{opacity:0;transform:translateY(18px);transition:opacity .6s var(--ease), transform .6s var(--ease);}
.reveal.is-visible{opacity:1;transform:none;}
@media (prefers-reduced-motion:reduce){
  .reveal{opacity:1;transform:none;transition:none;}
  .gauge-fill{animation:none;stroke-dashoffset:66.4;}
  .live-dot{animation:none;}
  html{scroll-behavior:auto;}
}
</style>
</head>
<body>

<a href="#main" class="skip-link">Skip to main content</a>

<!-- ===================== HEADER ===================== -->
<header class="site-header" id="siteHeader">
  <div class="container header-inner">
    <a href="#top" class="brand" aria-label="SafeFleet Compliance home">
      <svg class="brand-mark" viewBox="0 0 64 64" aria-hidden="true">
        <rect width="64" height="64" rx="14" fill="#1E3A8A"/>
        <path d="M32 11 51 18.5v13.6c0 13.6-9 21.3-19 25-10-3.7-19-11.4-19-25V18.5z" fill="#F97316"/>
        <path d="M23 32l6.5 6.5L41.5 25" stroke="#FFFFFF" stroke-width="4.2" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
      <span class="brand-text">SafeFleet<span class="brand-sub">COMPLIANCE</span></span>
    </a>

    <nav class="main-nav" id="mainNav" aria-label="Primary">
      <ul>
        <li><a href="#services">Services</a></li>
        <li><a href="#benefits">Benefits</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <div class="header-actions">
      <a href="#contact" class="btn btn-primary btn-sm">Get a Compliance Review</a>
      <button class="nav-toggle" id="navToggle" aria-expanded="false" aria-controls="mainNav" aria-label="Toggle navigation menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </div>
</header>

<main id="main">

  <!-- ===================== HERO ===================== -->
  <section class="hero" id="top" aria-label="Introduction">
    <div class="container hero-inner">
      <div class="hero-copy">
        <p class="eyebrow">
          <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
          FMCSA &amp; DOT Compliance Partners
        </p>
        <h1>Keep your trucks rolling. Keep your DOT file clean.</h1>
        <p class="hero-sub">SafeFleet Compliance manages hours-of-service tracking, driver qualification files, drug &amp; alcohol programs, and audit prep for trucking companies — so your fleet stays on the road instead of in a regulatory hearing.</p>
        <div class="hero-ctas">
          <a href="#contact" class="btn btn-primary btn-lg">Request a Compliance Review</a>
          <a href="#services" class="btn btn-outline btn-lg">See What We Manage</a>
        </div>
        <ul class="trust-stats">
          <li><span class="stat-num" data-count-to="500" data-suffix="+">0</span><span class="stat-label">Fleets served</span></li>
          <li><span class="stat-num" data-count-to="98" data-suffix="%">0</span><span class="stat-label">Audit pass rate</span></li>
          <li><span class="stat-num-text">24/7</span><span class="stat-label">HOS &amp; ELD monitoring</span></li>
        </ul>
      </div>

      <div class="hero-visual" aria-hidden="true">
        <div class="dash-card">
          <div class="dash-card-header"><span class="dash-dot"></span> Fleet Compliance Snapshot</div>

          <div class="dash-gauge">
            <svg viewBox="0 0 100 100">
              <circle class="gauge-track" cx="50" cy="50" r="48"></circle>
              <circle class="gauge-fill" cx="50" cy="50" r="48"></circle>
              <text x="50" y="57" text-anchor="middle" class="gauge-score">22</text>
            </svg>
            <div>
              <p class="gauge-text-label">BASIC Score: Strong</p>
              <p class="gauge-text-sub">Lower is better · updated weekly</p>
            </div>
          </div>

          <ul class="dash-checklist">
            <li>
              <span class="dash-check-label"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/></svg>Hours of Service</span>
              <span class="dash-status">COMPLIANT</span>
            </li>
            <li>
              <span class="dash-check-label"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/></svg>Vehicle Inspections</span>
              <span class="dash-status">UP TO DATE</span>
            </li>
            <li>
              <span class="dash-check-label"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/></svg>Drug &amp; Alcohol Program</span>
              <span class="dash-status">ACTIVE</span>
            </li>
            <li>
              <span class="dash-check-label"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/></svg>Driver Qualification Files</span>
              <span class="dash-status">100% COMPLETE</span>
            </li>
          </ul>

          <p class="dash-sync"><span class="live-dot"></span> Synced 2 minutes ago</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================== SERVICES ===================== -->
  <section class="section services" id="services" aria-labelledby="services-heading">
    <div class="container rail-layout">
      <div class="rail" aria-hidden="true"><span class="rail-node">MM·1</span></div>
      <div class="reveal">
        <p class="eyebrow">
          <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
          What We Manage
        </p>
        <h2 id="services-heading">Compliance, covered end to end</h2>
        <p class="section-lede">From driver files to roadside inspections, every requirement FMCSA can ask about gets tracked, documented, and kept current — before it becomes a violation.</p>

        <div class="card-grid">
          <article class="card">
            <div class="card-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M9 3h6a1 1 0 0 1 1 1v1H8V4a1 1 0 0 1 1-1Z" stroke="currentColor" stroke-width="1.8"/><rect x="5" y="5" width="14" height="16" rx="2" stroke="currentColor" stroke-width="1.8"/><path d="M8.5 11.5h7M8.5 15h7M8.5 18h4" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/></svg></div>
            <h3>DOT Audit Preparation</h3>
            <p>Mock audits, full document review, and corrective action plans built before the FMCSA comes knocking — not after.</p>
          </article>

          <article class="card">
            <div class="card-icon"><svg viewBox="0 0 24 24" fill="none"><circle cx="12" cy="13" r="8" stroke="currentColor" stroke-width="1.8"/><path d="M12 13l3.5-3.5M9 4h6" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/></svg></div>
            <h3>Hours of Service Monitoring</h3>
            <p>Daily ELD data review, automated HOS violation alerts, and RODS audits so drivers never run out of legal hours mid-route.</p>
          </article>

          <article class="card">
            <div class="card-icon"><svg viewBox="0 0 24 24" fill="none"><circle cx="12" cy="8" r="3.2" stroke="currentColor" stroke-width="1.8"/><path d="M5 20c0-3.3 3.1-6 7-6s7 2.7 7 6" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/><path d="M16.5 4.5l1.2 1.2 2.3-2.3" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
            <h3>Driver Qualification Files</h3>
            <p>Applications, MVR pulls, medical certifications, and road test records — built and kept current for every driver on payroll.</p>
          </article>

          <article class="card">
            <div class="card-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M10 3h4M12 3v6l5 9a2 2 0 0 1-1.7 3H8.7A2 2 0 0 1 7 18l5-9" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
            <h3>Drug &amp; Alcohol Testing Program</h3>
            <p>Clearinghouse queries, random testing pool management, and MIS reporting handled on schedule, every quarter.</p>
          </article>

          <article class="card">
            <div class="card-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M3 17h2l1.5-5h11L19 17h2M7.5 12l1-4h7l1 4" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/><circle cx="7.5" cy="17.5" r="1.6" stroke="currentColor" stroke-width="1.8"/><circle cx="16.5" cy="17.5" r="1.6" stroke="currentColor" stroke-width="1.8"/></svg></div>
            <h3>Vehicle Maintenance &amp; Inspection</h3>
            <p>DVIRs, annual inspections, and repair records organized and ready to hand over at any roadside stop.</p>
          </article>

          <article class="card">
            <div class="card-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M4 19V9M10 19V5M16 19v-7M4 19h16" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
            <h3>CSA Score Management</h3>
            <p>Ongoing BASIC score monitoring, inaccurate violation disputes, and trend tracking across your whole fleet.</p>
          </article>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================== BENEFITS ===================== -->
  <section class="section benefits alt-bg" id="benefits" aria-labelledby="benefits-heading">
    <div class="container rail-layout">
      <div class="rail" aria-hidden="true"><span class="rail-node">MM·2</span></div>
      <div class="reveal">
        <p class="eyebrow">
          <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
          The SafeFleet Difference
        </p>
        <h2 id="benefits-heading">Why fleets trust SafeFleet</h2>
        <p class="section-lede">Most carriers find out their paperwork has a gap during a roadside stop or a federal audit. Fleets working with SafeFleet find out on a Tuesday afternoon, from an alert — with time to fix it.</p>

        <div class="stat-grid">
          <div class="stat-box">
            <span class="stat-num" data-count-to="63" data-suffix="%">0</span>
            <p>Fewer roadside violations within the first year</p>
          </div>
          <div class="stat-box">
            <span class="stat-num" data-count-to="11" data-suffix=" hrs">0</span>
            <p>Average paperwork time saved per safety manager, weekly</p>
          </div>
          <div class="stat-box">
            <span class="stat-num" data-count-to="100" data-suffix="%">0</span>
            <p>Of driver and vehicle files audit-ready, every single day</p>
          </div>
          <div class="stat-box">
            <span class="stat-num-text">&lt;24 hrs</span>
            <p>Average response time on a flagged compliance alert</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================== MID-PAGE CTA ===================== -->
  <div class="container" style="margin:0 auto 8px;">
    <div class="cta-banner reveal">
      <div>
        <p class="eyebrow" style="margin-bottom:8px;margin-inline:auto;">Free Assessment</p>
        <h3>Not sure where your fleet stands today?</h3>
        <p>Get a free CSA score review and find out before FMCSA does.</p>
      </div>
      <a href="#contact" class="btn btn-primary btn-lg">Get My Free Review</a>
    </div>
  </div>

  <!-- ===================== ABOUT ===================== -->
  <section class="section about" id="about" aria-labelledby="about-heading">
    <div class="container rail-layout">
      <div class="rail rail-end" aria-hidden="true"><span class="rail-node">MM·3</span></div>
      <div class="reveal">
        <p class="eyebrow">
          <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
          About SafeFleet
        </p>
        <h2 id="about-heading">Built by people who've sat across the table from an auditor</h2>

        <div class="about-grid">
          <div>
            <p class="section-lede" style="margin-top:0;">SafeFleet Compliance was founded in 2014 by former safety directors who had spent years inside trucking companies, watching well-run fleets get put out of service over a missing signature, not an unsafe truck. We built the company we wished we'd had: one that treats a DQ file the way a CFO treats a balance sheet — checked, current, and never a surprise.</p>
            <p class="section-lede">Today our team manages compliance programs for carriers ranging from owner-operators to fleets running several hundred trucks, across nearly every state the FMCSA regulates.</p>

            <div class="numbers-list">
              <div>
                <span class="stat-num">2014</span>
                <p>Founded</p>
              </div>
              <div>
                <span class="stat-num">38</span>
                <p>States with active clients</p>
              </div>
              <div>
                <span class="stat-num">500+</span>
                <p>Fleets currently managed</p>
              </div>
              <div>
                <span class="stat-num">1,200+</span>
                <p>Driver qualification files maintained</p>
              </div>
            </div>

            <div class="pill-row">
              <span class="pill">FMCSA Parts 382 &amp; 383</span>
              <span class="pill">CSA BASICs</span>
              <span class="pill">ELD Mandate · 49 CFR 395</span>
              <span class="pill">Clearinghouse Queries</span>
              <span class="pill">DOT Audit Defense</span>
            </div>
          </div>

          <div class="about-card">
            <h3>How we work with your team</h3>
            <ul>
              <li><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg><span>A dedicated compliance specialist learns your fleet, not a rotating call center.</span></li>
              <li><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg><span>Monthly compliance reports your ops team and your insurer can both read.</span></li>
              <li><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg><span>Direct integration with most major ELD providers — no double data entry.</span></li>
              <li><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg><span>Audit support on call, including the day an FMCSA letter actually shows up.</span></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================== CONTACT ===================== -->
  <section class="section contact on-blue" id="contact" aria-labelledby="contact-heading">
    <div class="container" style="position:relative;">
      <p class="eyebrow">
        <svg viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
        Get Started
      </p>
      <h2 id="contact-heading">Ready to get audit-ready?</h2>
      <p class="section-lede">Tell us about your fleet. A compliance specialist will follow up within one business day with a clear next step — no sales script, just an honest read on where you stand.</p>

      <div class="contact-grid">
        <form class="contact-form" id="contactForm" novalidate>
          <div class="form-fields">
            <div class="form-row two-col">
              <div class="field" id="field-name">
                <label for="fullName">Full name</label>
                <input type="text" id="fullName" name="fullName" autocomplete="name" required>
                <p class="error-msg">Please enter your name.</p>
              </div>
              <div class="field" id="field-company">
                <label for="company">Company name</label>
                <input type="text" id="company" name="company" autocomplete="organization" required>
                <p class="error-msg">Please enter your company name.</p>
              </div>
            </div>

            <div class="form-row two-col">
              <div class="field" id="field-email">
                <label for="email">Email address</label>
                <input type="email" id="email" name="email" autocomplete="email" required>
                <p class="error-msg">Please enter a valid email address.</p>
              </div>
              <div class="field" id="field-phone">
                <label for="phone">Phone number</label>
                <input type="tel" id="phone" name="phone" autocomplete="tel" required>
                <p class="error-msg">Please enter a phone number.</p>
              </div>
            </div>

            <div class="form-row">
              <div class="field" id="field-fleet">
                <label for="fleetSize">Fleet size</label>
                <select id="fleetSize" name="fleetSize" required>
                  <option value="" selected disabled>Select fleet size</option>
                  <option>1–10 trucks</option>
                  <option>11–50 trucks</option>
                  <option>51–200 trucks</option>
                  <option>200+ trucks</option>
                </select>
                <p class="error-msg">Please select a fleet size.</p>
              </div>
            </div>

            <div class="form-row">
              <div class="field" id="field-message">
                <label for="message">What's prompting the call? <span style="font-weight:400;color:var(--muted);">(optional)</span></label>
                <textarea id="message" name="message" placeholder="Upcoming audit, ELD switch, a recent violation, building a program from scratch..."></textarea>
              </div>
            </div>

            <button type="submit" class="btn btn-primary btn-lg">Request Compliance Review</button>
            <p class="form-footnote">By submitting, you agree to be contacted by SafeFleet Compliance about your request. No spam, no third parties.</p>
          </div>

          <div class="success-panel" id="successPanel" role="status" tabindex="-1">
            <div class="success-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M5 12l4.5 4.5L19 7" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
            <h3 style="margin-bottom:8px;">Request received</h3>
            <p style="color:var(--muted);">A compliance specialist will reach out within one business day. Keep an eye on your inbox.</p>
          </div>
        </form>

        <aside class="contact-info" aria-label="Contact details">
          <div class="info-block">
            <div class="info-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M5 4h3l2 5-2.5 1.5a11 11 0 0 0 5 5L14 13l5 2v3a2 2 0 0 1-2 2C10.5 20 4 13.5 4 6a2 2 0 0 1 1-2Z" stroke="currentColor" stroke-width="1.7" stroke-linejoin="round"/></svg></div>
            <div>
              <h3>Call us</h3>
              <p><a href="tel:+18885550142">(888) 555-0142</a></p>
            </div>
          </div>
          <div class="info-block">
            <div class="info-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M4 6h16v12H4z" stroke="currentColor" stroke-width="1.7"/><path d="M4 7l8 6 8-6" stroke="currentColor" stroke-width="1.7" stroke-linejoin="round"/></svg></div>
            <div>
              <h3>Email us</h3>
              <p><a href="mailto:compliance@safefleetcompliance.com">compliance@safefleetcompliance.com</a></p>
            </div>
          </div>
          <div class="info-block">
            <div class="info-icon"><svg viewBox="0 0 24 24" fill="none"><path d="M12 21s7-6.3 7-11.5A7 7 0 0 0 5 9.5C5 14.7 12 21 12 21Z" stroke="currentColor" stroke-width="1.7"/><circle cx="12" cy="9.5" r="2.4" stroke="currentColor" stroke-width="1.7"/></svg></div>
            <div>
              <h3>Office</h3>
              <p>4400 Logistics Pkwy, Suite 220<br>Dallas, TX 75201</p>
            </div>
          </div>
          <div class="info-block">
            <div class="info-icon"><svg viewBox="0 0 24 24" fill="none"><circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="1.7"/><path d="M12 7v5l3.5 2" stroke="currentColor" stroke-width="1.7" stroke-linecap="round"/></svg></div>
            <div>
              <h3>Hours</h3>
              <p>Mon–Fri, 7am–7pm CT<br>Emergency audit support, 24/7</p>
            </div>
          </div>
        </aside>
      </div>
    </div>
  </section>

</main>

<!-- ===================== FOOTER ===================== -->
<footer class="site-footer">
  <div class="container footer-top">
    <div class="footer-brand">
      <a href="#top" class="brand" aria-label="SafeFleet Compliance home">
        <svg class="brand-mark" viewBox="0 0 64 64" aria-hidden="true">
          <rect width="64" height="64" rx="14" fill="#1E3A8A"/>
          <path d="M32 11 51 18.5v13.6c0 13.6-9 21.3-19 25-10-3.7-19-11.4-19-25V18.5z" fill="#F97316"/>
          <path d="M23 32l6.5 6.5L41.5 25" stroke="#FFFFFF" stroke-width="4.2" fill="none" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <span class="brand-text">SafeFleet<span class="brand-sub">COMPLIANCE</span></span>
      </a>
      <p>DOT and FMCSA compliance management for trucking companies and drivers who'd rather be hauling freight than chasing paperwork.</p>
      <div class="social-row">
        <a href="#" aria-label="SafeFleet Compliance on LinkedIn"><svg viewBox="0 0 24 24" fill="none"><rect x="3" y="3" width="18" height="18" rx="3" stroke="currentColor" stroke-width="1.6"/><path d="M8 10v6M8 7.5v.01M12 16v-4a2 2 0 0 1 4 0v4M12 16v-6" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg></a>
        <a href="#" aria-label="SafeFleet Compliance on X"><svg viewBox="0 0 24 24" fill="none"><path d="M4 4l16 16M20 4 4 20" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg></a>
        <a href="#" aria-label="SafeFleet Compliance on Facebook"><svg viewBox="0 0 24 24" fill="none"><path d="M14 9h2.5V6.2H14c-1.9 0-3 1.2-3 3v2H9v2.6h2V21h2.7v-7.2H16l.4-2.6h-2.7V9.6c0-.5.2-.6.6-.6Z" stroke="currentColor" stroke-width="1.3" stroke-linejoin="round"/></svg></a>
      </div>
    </div>

    <div class="footer-col">
      <h3>Company</h3>
      <ul>
        <li><a href="#services">Services</a></li>
        <li><a href="#benefits">Benefits</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>

    <div class="footer-col">
      <h3>Services</h3>
      <ul>
        <li><a href="#services">DOT Audit Prep</a></li>
        <li><a href="#services">Hours of Service</a></li>
        <li><a href="#services">Driver Qualification Files</a></li>
        <li><a href="#services">Drug &amp; Alcohol Program</a></li>
      </ul>
    </div>

    <div class="footer-col">
      <h3>Resources</h3>
      <ul>
        <li><a href="#">FMCSA Resources</a></li>
        <li><a href="#">Privacy Policy</a></li>
        <li><a href="#">Terms of Service</a></li>
      </ul>
    </div>
  </div>

  <div class="container footer-bottom">
    <p>© 2026 SafeFleet Compliance. All rights reserved.</p>
    <p class="disclaimer">SafeFleet Compliance is an independent compliance management service. We are not affiliated with, and do not represent, the Federal Motor Carrier Safety Administration (FMCSA) or the U.S. Department of Transportation (DOT).</p>
    <p class="credit">Concept Website Created by Gabriel Morales</p>
  </div>
</footer>

<script>
(function(){
  "use strict";

  var reducedMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;

  /* ---------- Header scroll shadow ---------- */
  var header = document.getElementById('siteHeader');
  function onScroll(){
    if(window.scrollY > 8){ header.classList.add('is-scrolled'); }
    else { header.classList.remove('is-scrolled'); }
  }
  document.addEventListener('scroll', onScroll, {passive:true});
  onScroll();

  /* ---------- Mobile nav toggle ---------- */
  var navToggle = document.getElementById('navToggle');
  var mainNav = document.getElementById('mainNav');
  navToggle.addEventListener('click', function(){
    var open = mainNav.classList.toggle('is-open');
    navToggle.setAttribute('aria-expanded', open ? 'true' : 'false');
  });
  mainNav.querySelectorAll('a').forEach(function(link){
    link.addEventListener('click', function(){
      mainNav.classList.remove('is-open');
      navToggle.setAttribute('aria-expanded','false');
    });
  });

  /* ---------- Active nav link on scroll ---------- */
  var sections = document.querySelectorAll('main section[id]');
  var navLinks = document.querySelectorAll('.main-nav a[href^="#"]');
  if('IntersectionObserver' in window){
    var navObserver = new IntersectionObserver(function(entries){
      entries.forEach(function(entry){
        if(entry.isIntersecting){
          var id = entry.target.getAttribute('id');
          navLinks.forEach(function(link){
            link.classList.toggle('is-active', link.getAttribute('href') === '#' + id);
          });
        }
      });
    }, {rootMargin:'-45% 0px -50% 0px'});
    sections.forEach(function(sec){ navObserver.observe(sec); });
  }

  /* ---------- Reveal-on-scroll ---------- */
  var revealEls = document.querySelectorAll('.reveal');
  if('IntersectionObserver' in window && !reducedMotion){
    var revealObserver = new IntersectionObserver(function(entries, obs){
      entries.forEach(function(entry){
        if(entry.isIntersecting){
          entry.target.classList.add('is-visible');
          obs.unobserve(entry.target);
        }
      });
    }, {threshold:0.12});
    revealEls.forEach(function(el){ revealObserver.observe(el); });
  } else {
    revealEls.forEach(function(el){ el.classList.add('is-visible'); });
  }

  /* ---------- Count-up stats ---------- */
  var counters = document.querySelectorAll('[data-count-to]');
  function animateCount(el){
    var target = parseFloat(el.getAttribute('data-count-to'));
    var suffix = el.getAttribute('data-suffix') || '';
    if(reducedMotion){
      el.textContent = target + suffix;
      return;
    }
    var duration = 1100;
    var start = null;
    function step(ts){
      if(start === null) start = ts;
      var progress = Math.min((ts - start) / duration, 1);
      var eased = 1 - Math.pow(1 - progress, 3);
      var value = Math.round(eased * target);
      el.textContent = value + suffix;
      if(progress < 1){ requestAnimationFrame(step); }
    }
    requestAnimationFrame(step);
  }
  if('IntersectionObserver' in window){
    var countObserver = new IntersectionObserver(function(entries, obs){
      entries.forEach(function(entry){
        if(entry.isIntersecting){
          animateCount(entry.target);
          obs.unobserve(entry.target);
        }
      });
    }, {threshold:0.4});
    counters.forEach(function(el){ countObserver.observe(el); });
  } else {
    counters.forEach(function(el){
      el.textContent = el.getAttribute('data-count-to') + (el.getAttribute('data-suffix')||'');
    });
  }

  /* ---------- Contact form validation + fake submit ---------- */
  var form = document.getElementById('contactForm');
  var successPanel = document.getElementById('successPanel');

  function setError(fieldId, hasError){
    var field = document.getElementById(fieldId);
    if(field){ field.classList.toggle('has-error', hasError); }
  }

  function isValidEmail(value){
    return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(value);
  }

  form.addEventListener('submit', function(e){
    e.preventDefault();
    var name = document.getElementById('fullName');
    var company = document.getElementById('company');
    var email = document.getElementById('email');
    var phone = document.getElementById('phone');
    var fleetSize = document.getElementById('fleetSize');

    var valid = true;

    var nameOk = name.value.trim().length > 1;
    setError('field-name', !nameOk); if(!nameOk) valid = false;

    var companyOk = company.value.trim().length > 1;
    setError('field-company', !companyOk); if(!companyOk) valid = false;

    var emailOk = isValidEmail(email.value.trim());
    setError('field-email', !emailOk); if(!emailOk) valid = false;

    var phoneOk = phone.value.trim().length >= 7;
    setError('field-phone', !phoneOk); if(!phoneOk) valid = false;

    var fleetOk = fleetSize.value.trim().length > 0;
    setError('field-fleet', !fleetOk); if(!fleetOk) valid = false;

    if(!valid){
      var firstError = form.querySelector('.has-error input, .has-error select');
      if(firstError) firstError.focus();
      return;
    }

    form.classList.add('is-submitted');
    successPanel.classList.add('is-visible');
    successPanel.focus();
  });

})();
</script>

</body>
</html>

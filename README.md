[index.html](https://github.com/user-attachments/files/22480464/index.html)
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Teddy Mutua — Portfolio</title>
<meta name="description" content="Teddy Mutua — Communications, content creation, graphic design, photography. Projects, case studies and contact." />
<meta property="og:title" content="Teddy Mutua — Portfolio" />
<meta property="og:description" content="Communications, content creation, graphic design, photography." />
<meta name="theme-color" content="#0f172a" />
<style>
/* Simple, modern responsive CSS — single-file for GitHub Pages */
:root{--bg:#0b1220;--card:#0f172a;--muted:#94a3b8;--accent:#7c3aed;--glass:rgba(255,255,255,0.04)}
*{box-sizing:border-box}
html,body{height:100%}
body{margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial;line-height:1.5;background:linear-gradient(180deg,#020617 0%, #07102a 100%);color:#e6eef8}
.container{max-width:1000px;margin:48px auto;padding:24px}
header{display:flex;align-items:center;justify-content:space-between;gap:16px}
.brand{display:flex;align-items:center;gap:12px}
.logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#06b6d4);display:flex;align-items:center;justify-content:center;font-weight:700}
h1{font-size:clamp(22px,4vw,34px);margin:0}
p.lead{color:var(--muted);margin:6px 0 0}
nav a{color:var(--muted);text-decoration:none;margin-left:12px}
main{margin-top:28px}
.grid{display:grid;grid-template-columns:1fr 320px;gap:20px}
@media (max-width:880px){.grid{grid-template-columns:1fr} .sidebar{order:2}}
.card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6);}
.about h2{margin:0 0 10px}
.skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
.tag{padding:6px 10px;border-radius:999px;background:var(--glass);color:var(--muted);font-size:13px}
.projects-list{display:flex;flex-direction:column;gap:12px}
.project{padding:12px;border-radius:10px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.02)}
.project h3{margin:0 0 6px}
.project p{margin:0;color:var(--muted);font-size:14px}
.project .meta{margin-top:8px;font-size:13px;color:var(--muted)}
.btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:white;text-decoration:none;font-weight:600}
.sidebar .card + .card{margin-top:16px}
footer{margin-top:36px;text-align:center;color:var(--muted);font-size:13px}
.grid-gap{height:14px}
/* simple modal */
.modal{position:fixed;inset:0;background:rgba(2,6,23,0.6);display:flex;align-items:center;justify-content:center;padding:20px;visibility:hidden;opacity:0;transition:opacity .18s ease, visibility .18s}
.modal.open{visibility:visible;opacity:1}
.modal .panel{background:linear-gradient(180deg,#071024,#081022);padding:18px;border-radius:12px;max-width:720px;width:100%}
label{display:block;margin-top:10px;font-size:13px;color:var(--muted)}
input,textarea{width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:inherit}
.muted{color:var(--muted);font-size:13px}
</style>
</head>
<body>
<div class="container">
<header>
<div class="brand">
<div class="logo">TM</div>
<div>
<h1>Teddy Mutua</h1>
<p class="lead">Communications • Content creation • Graphic design • Photography</p>
</div>
</div>
<nav>
<a href="#projects">Projects</a>
<a href="#about">About</a>
<a href="#contact" class="btn">Contact</a>
</nav>
</header>


<main>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OtakuTiers</title>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800;900&family=JetBrains+Mono:wght@400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --bg:#0e1117;--bg2:#161b25;--bg3:#1c2333;--bg4:#222c3c;
  --border:rgba(255,255,255,0.07);--border2:rgba(255,255,255,0.13);
  --gold:#f0a500;--gold2:#ffd166;--accent:#4fc3f7;
  --text:#e8eaf0;--text2:#8892a4;--text3:#4a5568;
  --font:'Outfit',sans-serif;--mono:'JetBrains Mono',monospace;
  --red:#e05c5c;--green:#4caf82;
}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:var(--font);min-height:100vh;overflow-x:hidden}
::-webkit-scrollbar{width:5px}::-webkit-scrollbar-track{background:var(--bg)}::-webkit-scrollbar-thumb{background:var(--bg4);border-radius:3px}

/* NAV */
.nav{position:fixed;top:0;left:0;right:0;z-index:1000;height:52px;background:rgba(14,17,23,0.97);backdrop-filter:blur(12px);border-bottom:1px solid var(--border);display:flex;align-items:center;padding:0 16px;gap:0}
.nav-logo{display:flex;align-items:center;gap:8px;text-decoration:none;margin-right:20px;flex-shrink:0}
.nav-logo-text{font-size:16px;font-weight:900;color:var(--text);letter-spacing:1px}
.nav-logo-text span{color:var(--gold)}
.nav-links{display:flex;align-items:center;gap:2px;flex:1;overflow-x:auto;scrollbar-width:none}
.nav-links::-webkit-scrollbar{display:none}
.nav-link{flex-shrink:0;background:none;border:none;border-bottom:2px solid transparent;color:var(--text2);font-family:var(--font);font-size:13px;font-weight:600;padding:6px 13px;cursor:pointer;transition:all .15s;white-space:nowrap}
.nav-link:hover{color:var(--text)}
.nav-link.active{color:var(--text);border-bottom-color:var(--gold)}
.nav-admin{margin-left:auto;flex-shrink:0;background:rgba(240,165,0,.1);border:1px solid rgba(240,165,0,.25);color:var(--gold);border-radius:6px;padding:5px 12px;font-family:var(--font);font-size:12px;font-weight:700;cursor:pointer;transition:all .15s;letter-spacing:.3px}
.nav-admin:hover{background:rgba(240,165,0,.2)}

/* PAGES */
.page{display:none;padding-top:52px;min-height:100vh}
.page.active{display:block}

/* HERO */
.hero{position:relative;height:220px;display:flex;align-items:flex-end;justify-content:center;padding-bottom:28px;overflow:hidden}
.hero-bg{position:absolute;inset:0;background:linear-gradient(180deg,rgba(14,17,23,0) 0%,rgba(14,17,23,.6) 55%,rgba(14,17,23,1) 100%),radial-gradient(ellipse at 50% 20%,rgba(240,165,0,.1),transparent 65%)}
.hero-grid{position:absolute;inset:0;background-image:linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);background-size:36px 36px}
.hero-glow{position:absolute;top:0;left:50%;transform:translateX(-50%);width:280px;height:100px;background:radial-gradient(ellipse,rgba(240,165,0,.15),transparent 70%)}
.hero-content{position:relative;z-index:2;text-align:center}
.hero-content h1{font-size:clamp(2rem,7vw,3.6rem);font-weight:900;letter-spacing:4px;text-transform:uppercase;line-height:1;text-shadow:0 0 40px rgba(240,165,0,.3)}
.hero-content h1 .g{color:var(--gold);text-shadow:0 0 30px rgba(240,165,0,.5)}
.hero-content p{font-size:12px;color:var(--text3);margin-top:6px;letter-spacing:2px;text-transform:uppercase}

/* GM BAR */
.gm-bar{background:var(--bg2);border-bottom:1px solid var(--border);position:sticky;top:52px;z-index:99}
.gm-bar-inner{display:flex;overflow-x:auto;max-width:1100px;margin:0 auto;padding:0 12px;scrollbar-width:none;gap:2px;align-items:center}
.gm-bar-inner::-webkit-scrollbar{display:none}
.gm-tab{flex-shrink:0;background:none;border:none;border-bottom:2px solid transparent;color:var(--text2);font-family:var(--font);font-size:12px;font-weight:700;padding:11px 14px;cursor:pointer;transition:all .15s;white-space:nowrap;text-transform:uppercase;letter-spacing:.5px;display:flex;align-items:center;gap:5px}
.gm-tab:hover{color:var(--text)}
.gm-tab.active{color:var(--gold);border-bottom-color:var(--gold)}

/* MAIN */
.main{max-width:1100px;margin:0 auto;padding:20px 16px}

/* TIER ROWS */
.tinfo{display:flex;align-items:center;justify-content:space-between;margin-bottom:16px;flex-wrap:wrap;gap:10px}
.tinfo-l h2{font-size:1.2rem;font-weight:800;letter-spacing:.5px}
.tinfo-l h2 .g{color:var(--gold)}
.search-box{display:flex;align-items:center;gap:7px;background:var(--bg2);border:1px solid var(--border);border-radius:7px;padding:7px 12px}
.search-box input{background:none;border:none;color:var(--text);font-family:var(--font);font-size:12px;outline:none;width:150px}
.search-box input::placeholder{color:var(--text3)}
.notice{font-size:12px;color:var(--text2);margin-bottom:14px;padding:9px 14px;background:var(--bg2);border:1px solid var(--border);border-radius:7px;display:flex;align-items:center;gap:8px}
.notice-dot{width:7px;height:7px;border-radius:50%;background:var(--gold);flex-shrink:0;animation:pulse 2s infinite}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.4}}

.tier-row{display:flex;border-radius:7px;overflow:hidden;margin-bottom:4px;border:1px solid rgba(255,255,255,.04);min-height:58px}
.tier-lbl{width:50px;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:1.4rem;letter-spacing:1px}
.tl-S{background:#c89b3c;color:#1a0d00}
.tl-A{background:#4a9e5c;color:#001200}
.tl-B{background:#4472b8;color:#000d1a}
.tl-C{background:#7b52ab;color:#0d0018}
.tl-D{background:#5a6270;color:#0a0c10}
.tl-F{background:#3a3f4a;color:#8892a4}
.tl-HM{background:linear-gradient(135deg,#7a5c10,#c89b3c);color:#fff;font-size:.8rem;font-weight:800;text-align:center;line-height:1.2;padding:2px}
.tier-cells{flex:1;background:var(--bg2);display:flex;flex-wrap:wrap;align-items:center;gap:6px;padding:8px 12px}

/* PLAYER CARD */
.pcard{display:flex;align-items:center;gap:7px;background:var(--bg3);border:1px solid var(--border);border-radius:7px;padding:5px 10px;cursor:pointer;transition:all .15s}
.pcard:hover{border-color:var(--border2);background:var(--bg4);transform:translateY(-1px)}
.pcard-face{width:26px;height:26px;border-radius:4px;overflow:hidden;background:var(--bg4);flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:9px;font-weight:800;color:var(--gold);font-family:var(--mono)}
.pcard-face img{width:100%;height:100%;object-fit:cover;image-rendering:pixelated}
.pcard-name{font-size:12px;font-weight:700;color:var(--text);line-height:1}
.pcard-rank{font-size:9px;font-weight:700;padding:1px 5px;border-radius:3px;letter-spacing:.3px;margin-top:2px;display:inline-block}
.empty-t{color:var(--text3);font-size:11px;font-style:italic}

/* RANK BADGE COLORS */
.rb-beginner{background:rgba(100,116,139,.2);color:#94a3b8;border:1px solid rgba(100,116,139,.3)}
.rb-newbie{background:rgba(76,175,130,.15);color:#6dbf84;border:1px solid rgba(76,175,130,.3)}
.rb-ace{background:rgba(68,114,184,.15);color:#7ba7e0;border:1px solid rgba(68,114,184,.3)}
.rb-specialist{background:rgba(123,82,171,.15);color:#b59dda;border:1px solid rgba(123,82,171,.3)}
.rb-master{background:rgba(240,165,0,.15);color:#f0a500;border:1px solid rgba(240,165,0,.35)}
.rb-grandmaster{background:linear-gradient(135deg,rgba(240,165,0,.25),rgba(224,92,92,.2));color:#ffd166;border:1px solid rgba(240,165,0,.45)}

/* TIER TAG COLORS */
.tt-S{background:#c89b3c;color:#1a0d00}
.tt-A{background:#4a9e5c;color:#001200}
.tt-B{background:#4472b8;color:#fff}
.tt-C{background:#7b52ab;color:#fff}
.tt-D{background:#5a6270;color:#fff}
.tt-F{background:#3a3f4a;color:#8892a4}
.tt-HM{background:linear-gradient(135deg,#7a5c10,#c89b3c);color:#fff}
.tt-NA{background:rgba(100,116,139,.15);color:#64748b;border:1px solid rgba(100,116,139,.2)}

/* PROFILE MODAL */
.overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.82);z-index:2000;align-items:center;justify-content:center;padding:16px;backdrop-filter:blur(6px)}
.overlay.active{display:flex}
.prof-modal{background:var(--bg2);border:1px solid var(--border2);border-radius:14px;width:100%;max-width:460px;overflow:hidden;position:relative}
.prof-top{background:var(--bg3);padding:18px 20px;display:flex;align-items:center;gap:14px;border-bottom:1px solid var(--border)}
.prof-face{width:60px;height:60px;border-radius:9px;overflow:hidden;border:2px solid var(--border2);background:var(--bg4);display:flex;align-items:center;justify-content:center;font-size:1.2rem;font-weight:800;color:var(--gold);font-family:var(--mono);flex-shrink:0}
.prof-face img{width:100%;height:100%;object-fit:cover;image-rendering:pixelated}
.prof-name{font-size:1.2rem;font-weight:800;letter-spacing:.5px;margin-bottom:5px}
.prof-rank-pill{display:inline-flex;align-items:center;gap:5px;padding:3px 11px;border-radius:20px;font-size:11px;font-weight:700;margin-bottom:4px}
.prof-region{float:right;margin-top:-4px;background:rgba(224,92,92,.12);color:#f87171;border:1px solid rgba(224,92,92,.25);border-radius:5px;padding:2px 9px;font-size:10px;font-weight:700}
.prof-pts{font-size:11px;color:var(--text2)}
.prof-body{padding:14px 20px}
.prof-modes-title{font-size:9px;font-weight:800;color:var(--text3);letter-spacing:2px;text-transform:uppercase;margin-bottom:12px;text-align:center}
.mode-grid{display:flex;flex-wrap:wrap;gap:10px;justify-content:center}
.mode-item{display:flex;flex-direction:column;align-items:center;gap:5px}
.mode-circle{width:52px;height:52px;border-radius:50%;background:var(--bg3);border:2px solid var(--border2);display:flex;align-items:center;justify-content:center;font-size:20px}
.mode-tt{font-size:9px;font-weight:800;padding:2px 6px;border-radius:3px;text-align:center}
.mode-nm{font-size:9px;color:var(--text2);text-align:center;max-width:52px;line-height:1.2}
.modal-x{position:absolute;top:12px;right:14px;background:none;border:none;color:var(--text2);font-size:17px;cursor:pointer}
.modal-x:hover{color:var(--text)}

/* LEADERBOARD */
.lb-wrap{background:var(--bg2);border:1px solid var(--border);border-radius:11px;overflow:hidden}
.lb-head{display:grid;grid-template-columns:44px 1fr 130px 70px;padding:9px 14px;border-bottom:1px solid var(--border);gap:6px}
.lb-head span{font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:1.5px}
.lb-row{display:grid;grid-template-columns:44px 1fr 130px 70px;padding:9px 14px;border-bottom:1px solid rgba(255,255,255,.025);align-items:center;gap:6px;cursor:pointer;transition:background .1s}
.lb-row:hover{background:rgba(255,255,255,.02)}
.lb-row:last-child{border-bottom:none}
.lb-pos{font-size:12px;font-weight:800;color:var(--text3);font-family:var(--mono)}
.lb-pos.r1{color:var(--gold)}
.lb-pos.r2{color:#94a3b8}
.lb-pos.r3{color:#c07a3c}
.lb-player{display:flex;align-items:center;gap:9px}
.lb-face{width:30px;height:30px;border-radius:5px;overflow:hidden;background:var(--bg4);flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:800;color:var(--gold);font-family:var(--mono)}
.lb-face img{width:100%;height:100%;object-fit:cover;image-rendering:pixelated}
.lb-pname{font-weight:700;font-size:13px;display:block}
.lb-mode-tags{display:flex;gap:3px;flex-wrap:wrap;margin-top:2px}
.lb-mtag{font-size:8px;font-weight:800;padding:1px 5px;border-radius:3px}
.lb-score{font-family:var(--mono);font-weight:800;font-size:13px;color:var(--gold)}

/* RANKS GRID */
.rg{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:12px;margin-top:16px}
.rcard{background:var(--bg2);border:1px solid var(--border);border-radius:11px;padding:18px;position:relative;overflow:hidden;transition:transform .15s,border-color .15s}
.rcard:hover{transform:translateY(-2px);border-color:var(--border2)}
.rcard::after{content:'';position:absolute;top:0;left:0;right:0;height:2px}
.rc-beginner::after{background:#64748b}
.rc-newbie::after{background:#4caf82}
.rc-ace::after{background:#4472b8}
.rc-specialist::after{background:#7b52ab}
.rc-master::after{background:var(--gold)}
.rc-grandmaster::after{background:linear-gradient(90deg,var(--gold),#e05c5c)}
.rcard-icon{font-size:1.8rem;margin-bottom:8px}
.rcard-name{font-size:1rem;font-weight:800;letter-spacing:.5px;margin-bottom:4px}
.rcard-range{font-size:10px;font-family:var(--mono);color:var(--text3);background:var(--bg3);display:inline-block;padding:3px 9px;border-radius:5px;margin-bottom:9px}
.rcard-desc{font-size:12px;color:var(--text2);line-height:1.6}

/* SUBMIT */
.sf{background:var(--bg2);border:1px solid var(--border);border-radius:12px;padding:22px;max-width:500px;margin:20px auto}
.sf-title{font-size:1.1rem;font-weight:800;letter-spacing:.5px;margin-bottom:4px}
.sf-sub{font-size:12px;color:var(--text2);margin-bottom:18px}
.sf-g{margin-bottom:12px}
.sf-lbl{display:block;font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:1.2px;margin-bottom:5px}
.sf-in,.sf-sel,.sf-ta{width:100%;background:var(--bg3);border:1px solid var(--border);border-radius:7px;padding:8px 11px;color:var(--text);font-family:var(--font);font-size:13px;outline:none;transition:border-color .15s}
.sf-in:focus,.sf-sel:focus,.sf-ta:focus{border-color:rgba(240,165,0,.4)}
.sf-sel option{background:var(--bg3)}
.sf-ta{resize:vertical;min-height:65px}
.sf-row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.sf-btn{width:100%;background:var(--gold);border:none;border-radius:8px;padding:11px;color:#1a0d00;font-family:var(--font);font-size:13px;font-weight:800;cursor:pointer;margin-top:4px;letter-spacing:.5px;transition:opacity .15s}
.sf-btn:hover{opacity:.85}

/* ABOUT */
.aw{max-width:660px;margin:0 auto;padding:20px 16px}
.acard{background:var(--bg2);border:1px solid var(--border);border-radius:11px;padding:18px;margin-bottom:12px}
.acard h2{font-size:.95rem;font-weight:800;letter-spacing:1px;color:var(--gold);margin-bottom:10px}
.acard p{font-size:12px;color:var(--text2);line-height:1.8;margin-bottom:6px}
.faq{border-bottom:1px solid var(--border);padding:11px 0;cursor:pointer}
.faq:last-child{border-bottom:none}
.faq-q{font-size:13px;font-weight:600;display:flex;justify-content:space-between;align-items:center;gap:8px}
.faq-a{font-size:12px;color:var(--text2);line-height:1.7;margin-top:7px;display:none}
.faq.open .faq-a{display:block}
.faq-arr{color:var(--gold);transition:transform .2s;flex-shrink:0}
.faq.open .faq-arr{transform:rotate(180deg)}

/* ADMIN */
.adm{padding:18px 16px;max-width:880px;margin:0 auto}
.adm-bar{display:flex;align-items:center;justify-content:space-between;margin-bottom:18px;padding:13px 16px;background:var(--bg2);border:1px solid var(--border);border-radius:9px}
.adm-title{font-weight:800;font-size:1rem;color:var(--gold);letter-spacing:2px}
.adm-logout{background:rgba(224,92,92,.12);border:1px solid rgba(224,92,92,.25);color:#f87171;border-radius:6px;padding:5px 12px;font-family:var(--font);font-size:11px;cursor:pointer}
.adm-stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(110px,1fr));gap:9px;margin-bottom:16px}
.ast{background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:12px;text-align:center}
.ast-n{font-size:1.6rem;font-weight:800;color:var(--gold);font-family:var(--mono)}
.ast-l{font-size:9px;color:var(--text3);text-transform:uppercase;letter-spacing:1px;margin-top:2px}
.a-tabs{display:flex;gap:4px;margin-bottom:14px;background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:4px}
.a-tab{flex:1;background:none;border:none;color:var(--text2);font-family:var(--font);font-size:11px;font-weight:700;padding:7px;border-radius:6px;cursor:pointer;transition:all .15s;text-transform:uppercase;letter-spacing:.5px}
.a-tab.active{background:var(--gold);color:#1a0d00}
.asec{display:none}
.asec.active{display:block}
.ac{background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:14px;margin-bottom:10px}
.ac h3{font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:2px;margin-bottom:12px}
.af{display:grid;gap:9px}
.ar{display:grid;grid-template-columns:1fr 1fr;gap:9px}
.al{font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:1px;margin-bottom:4px}
.ai,.as{width:100%;background:var(--bg3);border:1px solid var(--border);border-radius:6px;padding:7px 11px;color:var(--text);font-family:var(--font);font-size:12px;outline:none;transition:border-color .15s}
.ai:focus,.as:focus{border-color:rgba(240,165,0,.4)}
.as option{background:var(--bg3)}
.ab{background:var(--gold);border:none;border-radius:7px;padding:8px 18px;color:#1a0d00;font-family:var(--font);font-size:12px;font-weight:800;cursor:pointer;transition:opacity .15s}
.ab:hover{opacity:.85}
.at{width:100%;border-collapse:collapse}
.at th{font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:1.5px;padding:7px 9px;text-align:left;border-bottom:1px solid var(--border)}
.at td{padding:7px 9px;font-size:11px;border-bottom:1px solid rgba(255,255,255,.025)}
.at tr:hover td{background:rgba(255,255,255,.015)}
.aab{background:none;border:1px solid var(--border);border-radius:4px;padding:3px 8px;font-size:9px;cursor:pointer;font-family:var(--font);transition:all .15s;margin-right:3px}
.aab.e{color:var(--accent);border-color:rgba(79,195,247,.3)}
.aab.d{color:var(--red);border-color:rgba(224,92,92,.3)}

/* LOGIN MODAL */
.lm{background:var(--bg2);border:1px solid var(--border2);border-radius:13px;padding:26px;width:90%;max-width:340px;position:relative}
.lm h2{font-size:1.1rem;font-weight:800;margin-bottom:4px;letter-spacing:.5px}
.lm-sub{font-size:11px;color:var(--text2);margin-bottom:18px}
.pw-row{display:flex;gap:7px}
.pw-row input{flex:1;background:var(--bg3);border:1px solid var(--border);border-radius:7px;padding:8px 12px;color:var(--text);font-family:var(--mono);font-size:13px;outline:none;letter-spacing:3px;transition:border-color .15s}
.pw-row input:focus{border-color:rgba(240,165,0,.4)}
.pw-row button{background:var(--gold);border:none;border-radius:7px;padding:8px 14px;color:#1a0d00;font-weight:800;cursor:pointer;font-family:var(--font);font-size:12px}
.pw-err{color:var(--red);font-size:11px;margin-top:7px;display:none}

/* NOTIF */
.notif{position:fixed;top:62px;right:14px;background:var(--bg2);border-radius:7px;padding:9px 16px;font-size:12px;z-index:3000;display:none;box-shadow:0 4px 20px rgba(0,0,0,.5)}

@media(max-width:580px){
  .lb-head,.lb-row{grid-template-columns:36px 1fr 70px}
  .lb-head span:nth-child(3),.lb-row>*:nth-child(3){display:none}
  .sf-row,.ar{grid-template-columns:1fr}
}
</style>
</head>
<body>

<!-- NAV -->
<nav class="nav">
  <a class="nav-logo" href="#" onclick="goPage('home');return false">
    <span class="nav-logo-text">⚔️ Otaku<span>Tiers</span></span>
  </a>
  <div class="nav-links">
    <button class="nav-link active" onclick="goPage('home')">Home</button>
    <button class="nav-link" onclick="goPage('tiers')">Tiers</button>
    <button class="nav-link" onclick="goPage('lb')">Leaderboards</button>
    <button class="nav-link" onclick="goPage('ranks')">Ranks</button>
    <button class="nav-link" onclick="goPage('submit')">Submit</button>
    <button class="nav-link" onclick="goPage('about')">About</button>
  </div>
  <button class="nav-admin" onclick="openLogin()">⚙ Admin</button>
</nav>

<div class="notif" id="notif"></div>

<!-- HOME -->
<div class="page active" id="page-home">
  <div class="hero">
    <div class="hero-grid"></div><div class="hero-bg"></div><div class="hero-glow"></div>
    <div class="hero-content">
      <h1><span class="g">OTAKU</span> TIERS</h1>
      <p>The #1 Minecraft PvP Ranking Platform</p>
    </div>
  </div>
  <div class="main">
    <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:10px;margin-bottom:24px">
      <div class="hcard" onclick="goPage('tiers')" style="background:var(--bg2);border:1px solid var(--border

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
      <div class="hcard" onclick="goPage('tiers')" style="background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:16px;cursor:pointer;transition:border-color .15s" onmouseover="this.style.borderColor='var(--border2)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="font-size:1.5rem;margin-bottom:7px">📊</div>
        <div style="font-weight:800;font-size:13px;margin-bottom:3px">Tier Lists</div>
        <div style="font-size:11px;color:var(--text2)">Rankings across all 8 gamemodes</div>
      </div>
      <div onclick="goPage('lb')" style="background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:16px;cursor:pointer;transition:border-color .15s" onmouseover="this.style.borderColor='var(--border2)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="font-size:1.5rem;margin-bottom:7px">🏆</div>
        <div style="font-weight:800;font-size:13px;margin-bottom:3px">Leaderboards</div>
        <div style="font-size:11px;color:var(--text2)">Top players by total points</div>
      </div>
      <div onclick="goPage('ranks')" style="background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:16px;cursor:pointer;transition:border-color .15s" onmouseover="this.style.borderColor='var(--border2)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="font-size:1.5rem;margin-bottom:7px">🎖️</div>
        <div style="font-weight:800;font-size:13px;margin-bottom:3px">Rank System</div>
        <div style="font-size:11px;color:var(--text2)">Combat Beginner → Grandmaster</div>
      </div>
      <div onclick="goPage('submit')" style="background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:16px;cursor:pointer;transition:border-color .15s" onmouseover="this.style.borderColor='var(--border2)'" onmouseout="this.style.borderColor='var(--border)'">
        <div style="font-size:1.5rem;margin-bottom:7px">📝</div>
        <div style="font-weight:800;font-size:13px;margin-bottom:3px">Submit Player</div>
        <div style="font-size:11px;color:var(--text2)">Nominate a player for review</div>
      </div>
    </div>
    <div style="font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:2px;margin-bottom:9px">Gamemodes</div>
    <div id="homeGMs" style="display:flex;flex-wrap:wrap;gap:7px"></div>
  </div>
</div>

<!-- TIERS -->
<div class="page" id="page-tiers">
  <div class="gm-bar"><div class="gm-bar-inner" id="gmTabRow"></div></div>
  <div class="main">
    <div class="tinfo">
      <div class="tinfo-l">
        <div style="font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:2px;margin-bottom:4px" id="gmLbl"></div>
        <h2 id="gmH2">Tier List</h2>
      </div>
      <div class="search-box">
        <span style="color:var(--text3);font-size:12px">🔍</span>
        <input id="psrch" placeholder="Search players..." onkeyup="renderTiers()"/>
      </div>
    </div>
    <div class="notice"><div class="notice-dot"></div><span id="gmDesc"></span></div>
    <div id="tierContainer"></div>
  </div>
</div>

<!-- LEADERBOARD -->
<div class="page" id="page-lb">
  <div class="main">
    <div style="margin-bottom:16px">
      <div style="font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:2px;margin-bottom:5px">Global Rankings</div>
      <h2 style="font-size:1.2rem;font-weight:800;letter-spacing:.5px">Leaderboards</h2>
    </div>
    <div style="display:flex;gap:5px;flex-wrap:wrap;margin-bottom:14px" id="lbFilters">
      <button class="gm-tab active" onclick="setLBF('all',this)" style="border-radius:6px;border:1px solid var(--border);padding:6px 12px;font-size:11px">All</button>
    </div>
    <div class="lb-wrap">
      <div class="lb-head">
        <span>#</span><span>Player</span><span>Rank</span><span>Score</span>
      </div>
      <div id="lbRows"></div>
    </div>
  </div>
</div>

<!-- RANKS -->
<div class="page" id="page-ranks">
  <div class="main">
    <div style="margin-bottom:16px">
      <div style="font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:2px;margin-bottom:5px">Point-Based System</div>
      <h2 style="font-size:1.2rem;font-weight:800;letter-spacing:.5px">Player <span style="color:var(--gold)">Ranks</span></h2>
      <p style="font-size:11px;color:var(--text2);margin-top:5px">Ranks are assigned automatically by total points. Each tier placement earns points.</p>
    </div>
    <div style="background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:12px 14px;margin-bottom:16px;display:grid;grid-template-columns:repeat(auto-fill,minmax(120px,1fr));gap:8px" id="ptTable"></div>
    <div class="rg" id="ranksGrid"></div>
  </div>
</div>

<!-- SUBMIT -->
<div class="page" id="page-submit">
  <div class="main">
    <div class="sf">
      <div class="sf-title">Submit a Player</div>
      <div class="sf-sub">Know a skilled player not listed? Submit them for staff review.</div>
      <div class="sf-g"><label class="sf-lbl">Minecraft Username</label><input class="sf-in" id="sfU" placeholder="IGN..."/></div>
      <div class="sf-row">
        <div class="sf-g"><label class="sf-lbl">Gamemode</label><select class="sf-sel" id="sfGM"></select></div>
        <div class="sf-g"><label class="sf-lbl">Suggested Tier</label>
          <select class="sf-sel" id="sfT"><option>S</option><option>A</option><option>B</option><option>C</option><option>D</option></select>
        </div>
      </div>
      <div class="sf-g"><label class="sf-lbl">Evidence / Reason</label><textarea class="sf-ta" id="sfR" placeholder="Video links, tournament results..."></textarea></div>
      <div class="sf-g"><label class="sf-lbl">Your Discord (optional)</label><input class="sf-in" id="sfD" placeholder="user#0000"/></div>
      <button class="sf-btn" onclick="doSubmit()">SUBMIT FOR REVIEW</button>
    </div>
  </div>
</div>

<!-- ABOUT -->
<div class="page" id="page-about">
  <div class="aw">
    <div style="margin-bottom:16px">
      <div style="font-size:9px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:2px;margin-bottom:5px">About</div>
      <h2 style="font-size:1.2rem;font-weight:800;letter-spacing:.5px">About <span style="color:var(--gold)">OtakuTiers</span></h2>
    </div>
    <div class="acard">
      <h2>What is OtakuTiers?</h2>
      <p>OtakuTiers is the definitive Minecraft PvP ranking platform covering all major gamemodes — NethPot, Sword, UHC, DiaPot, Vanilla (Crystal PvP), SMP, Mace, and Axe.</p>
      <p>Rankings are maintained by experienced staff who review gameplay footage, tournament results, and community standing to produce accurate placements.</p>
    </div>
    <div class="acard">
      <h2>Point-Based Ranks</h2>
      <p>Ranks are automatically assigned based on total points. Tier placements in each mode earn points: S=20, A=15, B=10, C=7, D=4, HM=3, F=1. The sum determines your rank — Combat Beginner through Combat Grandmaster.</p>
    </div>
    <div class="acard">
      <h2>FAQ</h2>
      <div class="faq" onclick="this.classList.toggle('open')"><div class="faq-q">How often is the list updated? <span class="faq-arr">▼</span></div><div class="faq-a">Typically weekly. Major updates happen after tournaments and community events.</div></div>
      <div class="faq" onclick="this.classList.toggle('open')"><div class="faq-q">How do I get ranked? <span class="faq-arr">▼</span></div><div class="faq-a">Use the Submit page to nominate yourself. Staff will review and add you if you meet the criteria.</div></div>
      <div class="faq" onclick="this.classList.toggle('open')"><div class="faq-q">Can I dispute a placement? <span class="faq-arr">▼</span></div><div class="faq-a">Yes — join our Discord and open a dispute ticket with evidence of your skill.</div></div>
      <div class="faq" onclick="this.classList.toggle('open')"><div class="faq-q">What is Combat Grandmaster? <span class="faq-arr">▼</span></div><div class="faq-a">The highest rank on the platform — awarded to players with 161+ points. Absolute elite.</div></div>
    </div>
  </div>
</div>

<!-- ADMIN -->
<div class="page" id="page-admin">
  <div class="adm">
    <div class="adm-bar">
      <div class="adm-title">⚙ ADMIN PANEL</div>
      <button class="adm-logout" onclick="goPage('home')">Logout</button>
    </div>
    <div class="adm-stats" id="admStats"></div>
    <div class="a-tabs">
      <button class="a-tab active" onclick="aTab('add',this)">Add Player</button>
      <button class="a-tab" onclick="aTab('manage',this)">Manage Players</button>
      <button class="a-tab" onclick="aTab('subs',this)">Submissions</button>
    </div>

    <div class="asec active" id="asec-add">
      <div class="ac"><h3>Add New Player</h3>
        <div class="af">
          <div class="ar">
            <div><div class="al">Username</div><input class="ai" id="aU" placeholder="Minecraft IGN"/></div>
            <div><div class="al">Gamemode</div><select class="as" id="aGM"></select></div>
          </div>
          <div class="ar">
            <div><div class="al">Tier</div>
              <select class="as" id="aTr">
                <option value="S">S Tier</option><option value="A">A Tier</option><option value="B">B Tier</option>
                <option value="C">C Tier</option><option value="D">D Tier</option><option value="F">F Tier</option><option value="HM">HM</option>
              </select>
            </div>
            <div><div class="al">Points (auto-filled if blank)</div><input class="ai" id="aPts" type="number" placeholder="Leave blank = auto"/></div>
          </div>
          <div class="ar">
            <div><div class="al">Region</div><input class="ai" id="aReg" placeholder="NA / EU / AS / SA..."/></div>
            <div><div class="al">Face URL (optional)</div><input class="ai" id="aFaceUrl" placeholder="https://..."/></div>
          </div>
          <div><button class="ab" onclick="addPlayer()">Add Player</button></div>
        </div>
      </div>
    </div>

    <div class="asec" id="asec-manage">
      <div class="ac"><h3>All Players</h3>
        <div style="display:flex;gap:7px;margin-bottom:10px">
          <input class="ai" id="aSrch" placeholder="Search..." onkeyup="renderAT()" style="flex:1"/>
          <select class="as" id="aFGM" onchange="renderAT()" style="width:130px"><option value="">All Modes</option></select>
        </div>
        <div style="overflow-x:auto">
          <table class="at"><thead><tr><th>Player</th><th>Mode</th><th>Tier</th><th>Pts</th><th>Rank</th><th>Actions</th></tr></thead>
          <tbody id="aTBody"></tbody></table>
        </div>
      </div>
    </div>

    <div class="asec" id="asec-subs">
      <div class="ac"><h3>Pending Submissions</h3>
        <div style="overflow-x:auto">
          <table class="at"><thead><tr><th>Username</th><th>Gamemode</th><th>Suggested</th><th>Reason</th><th>Actions</th></tr></thead>
          <tbody id="aSubsBody"></tbody></table>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Login overlay -->
<div class="overlay" id="loginOv">
  <div class="lm">
    <button class="modal-x" onclick="closeLogin()">✕</button>
    <h2>Admin Login</h2>
    <div class="lm-sub">Enter the admin password to continue.</div>
    <div class="pw-row">
      <input type="password" id="pwIn" placeholder="Password" onkeydown="if(event.key==='Enter')checkPw()"/>
      <button onclick="checkPw()">Enter</button>
    </div>
    <div class="pw-err" id="pwErr">Wrong password.</div>
  </div>
</div>

<!-- Profile overlay -->
<div class="overlay" id="profOv">
  <div class="prof-modal">
    <button class="modal-x" onclick="document.getElementById('profOv').classList.remove('active')">✕</button>
    <div id="profContent"></div>
  </div>
</div>

<script>
const ADMIN_PW='MeowGopGop';

const GMS=[
  {id:'nethpot', name:'NethPot',    icon:'🧪', desc:'Nether Potion PvP — fast-paced, requires precise potion timing and aggression control.'},
  {id:'sword',   name:'Sword',      icon:'⚔️', desc:'Classic sword combat — combos, critical hits, and mechanical timing define the best.'},
  {id:'uhc',     name:'UHC',        icon:'❤️', desc:'Ultra Hardcore — no natural regeneration. The most demanding test of survival PvP.'},
  {id:'diapot',  name:'DiaPot',     icon:'💎', desc:'Diamond Potion PvP — heavy armor combined with fast potion mechanics.'},
  {id:'vanilla', name:'Vanilla',    icon:'✨', desc:'Crystal/Vanilla PvP — the highest technical skillcap PvP gamemode in Java Edition.'},
  {id:'smp',     name:'SMP',        icon:'🏔️', desc:'Survival Multiplayer PvP — gear-based combat with terrain and environmental play.'},
  {id:'mace',    name:'Mace',       icon:'🔨', desc:'Mace PvP (1.21+) — new weapon with unique fall-damage and knockback mechanics.'},
  {id:'axe',     name:'Axe',        icon:'🪓', desc:'Axe PvP — shield breaking, critical hits, and powerful burst damage.'},
];

const RANKS=[
  {key:'grandmaster',label:'Combat Grandmaster',min:161,max:Infinity,cls:'rb-grandmaster',card:'rc-grandmaster',icon:'👑',color:'#ffd166',desc:'The absolute pinnacle — 161+ pts. Feared by everyone, surpassed by none.'},
  {key:'master',     label:'Combat Master',     min:121,max:160,     cls:'rb-master',     card:'rc-master',     icon:'🏆',color:'#f0a500',desc:'Elite multi-mode players at 121–160 pts. Dominant in competition.'},
  {key:'specialist', label:'Combat Specialist', min:81, max:120,     cls:'rb-specialist', card:'rc-specialist', icon:'💠',color:'#b59dda',desc:'Highly skilled at 81–120 pts. Consistent tournament performers.'},
  {key:'ace',        label:'Combat Ace',        min:41, max:80,      cls:'rb-ace',        card:'rc-ace',        icon:'🔷',color:'#7ba7e0',desc:'Solid competitive players at 41–80 pts. Above average in most modes.'},
  {key:'newbie',     label:'Combat Newbie',     min:21, max:40,      cls:'rb-newbie',     card:'rc-newbie',     icon:'🌿',color:'#6dbf84',desc:'Developing competitors at 21–40 pts. Learning and improving.'},
  {key:'beginner',   label:'Combat Beginner',   min:0,  max:20,      cls:'rb-beginner',   card:'rc-beginner',  icon:'🌱',color:'#94a3b8',desc:'Starting their journey. 0–20 pts. Everyone begins somewhere.'},
];

const TIER_PTS={S:20,A:15,B:10,C:7,D:4,HM:3,F:1};
const TIER_COLORS={S:'#c89b3c',A:'#4a9e5c',B:'#4472b8',C:'#7b52ab',D:'#5a6270',F:'#3a3f4a',HM:'#c89b3c'};

function getRank(pts){return RANKS.find(r=>pts>=r.min&&pts<=r.max)||RANKS[RANKS.length-1]}

let players=[];
let submissions=[];
let nextId=1;
let curGM='nethpot';
let lbF='all';

// PAGE NAV
function goPage(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-'+id).classList.add('active');
  const order=['home','tiers','lb','ranks','submit','about'];
  document.querySelectorAll('.nav-link').forEach((b,i)=>{b.classList.toggle('active',order[i]===id)});
  window.scrollTo(0,0);
  if(id==='tiers')renderTiers();
  if(id==='lb')renderLB();
  if(id==='admin')renderAdmin();
}

// INIT GM SELECTS
function initGMs(){
  // Tab row
  const tr=document.getElementById('gmTabRow');
  tr.innerHTML=GMS.map(g=>`<button class="gm-tab${g.id===curGM?' active':''}" onclick="selGM('${g.id}',this)">${g.icon} ${g.name}</button>`).join('');
  // Home pills
  const hg=document.getElementById('homeGMs');
  if(hg)hg.innerHTML=GMS.map(g=>`<div onclick="selGM('${g.id}');goPage('tiers')" style="display:inline-flex;align-items:center;gap:5px;background:var(--bg2);border:1px solid var(--border);border-radius:6px;padding:6px 12px;cursor:pointer;font-size:11px;font-weight:700;transition:border-color .15s" onmouseover="this.style.borderColor='var(--border2)'" onmouseout="this.style.borderColor='var(--border)'">${g.icon} ${g.name}</div>`).join('');
  // Selects
  ['sfGM','aGM','aFGM'].forEach(sid=>{
    const el=document.getElementById(sid);if(!el)return;
    el.innerHTML=(sid==='aFGM'?'<option value="">All Modes</option>':'')+GMS.map(g=>`<option value="${g.id}">${g.name}</option>`).join('');
  });
}

function selGM(id,el){
  curGM=id;
  document.querySelectorAll('#gmTabRow .gm-tab').forEach((b,i)=>b.classList.toggle('active',GMS[i]?.id===id));
  document.getElementById('psrch').value='';
  renderTiers();
}

// TIER RENDER
const TIERS_O=['S','A','B','C','D','F','HM'];

function renderTiers(){
  const gm=GMS.find(g=>g.id===curGM)||GMS[0];
  document.getElementById('gmLbl').textContent=gm.name+' Tier List';
  document.getElementById('gmH2').innerHTML=`<span style="color:var(--gold)">${gm.icon}</span> ${gm.name} <span style="color:var(--gold)">Tier List</span>`;
  document.getElementById('gmDesc').textContent=gm.desc;
  const q=(document.getElementById('psrch')?.value||'').toLowerCase();
  const gmp=players.filter(p=>p.gm===curGM&&(!q||p.name.toLowerCase().includes(q)));
  document.getElementById('tierContainer').innerHTML=TIERS_O.map(tier=>{
    const tp=gmp.filter(p=>p.tier===tier);
    const lc='tl-'+tier;
    const chips=tp.length?tp.map(p=>{
      const rk=getRank(p.pts||0);
      return`<div class="pcard" onclick="openProf(${p.id})">
        <div class="pcard-face">${p.face?`<img src="${p.face}" onerror="this.style.display='none'">`:(p.name.substring(0,2).toUpperCase())}</div>
        <div>
          <div class="pcard-name">${p.name}</div>
          <div class="pcard-rank ${rk.cls}">${rk.label}</div>
        </div>
      </div>`;
    }).join(''):'<span class="empty-t">—</span>';
    return`<div class="tier-row"><div class="tier-lbl ${lc}">${tier}</div><div class="tier-cells">${chips}</div></div>`;
  }).join('');
}

// PROFILE
function openProf(id){
  const p=players.find(x=>x.id===id);if(!p)return;
  const rk=getRank(p.pts||0);
  const gm=GMS.find(g=>g.id===p.gm);
  const modeItems=GMS.map(g=>{
    const mp=players.find(x=>x.name===p.name&&x.gm===g.id);
    const t=mp?mp.tier:'NA';
    return`<div class="mode-item">
      <div class="mode-circle">${g.icon}</div>
      <div class="mode-tt tt-${t==='NA'?'NA':t}">${t}</div>
      <div class="mode-nm">${g.name}</div>
    </div>`;
  }).join('');
  document.getElementById('profContent').innerHTML=`
    <div class="prof-top">
      <div class="prof-face">${p.face?`<img src="${p.face}" onerror="this.style.display='none'">`:(p.name.substring(0,2).toUpperCase())}</div>
      <div style="flex:1">
        <div style="display:flex;align-items:flex-start;justify-content:space-between">
          <div class="prof-name">${p.name}</div>
          ${p.region?`<div class="prof-region">${p.region}</div>`:''}
        </div>
        <div class="prof-rank-pill ${rk.cls}">${rk.icon} ${rk.label}</div>
        <div class="prof-pts">${p.pts||0} points · ${gm?gm.icon+' '+gm.name:p.gm}</div>
      </div>
    </div>
    <div class="prof-body">
      <div class="prof-modes-title">Tiers</div>
      <div class="mode-grid">${modeItems}</div>
    </div>`;
  document.getElementById('profOv').classList.add('active');
}

// LEADERBOARD
function renderLB(){
  const data=lbF==='all'?players:players.filter(p=>p.gm===lbF);
  const map={};
  data.forEach(p=>{
    if(!map[p.name])map[p.name]={name:p.name,face:p.face,region:p.region,total:0,modes:{}};
    map[p.name].total+=(p.pts||0);
    map[p.name].modes[p.gm]=p.tier;
  });
  const sorted=Object.values(map).sort((a,b)=>b.total-a.total);
  const el=document.getElementById('lbRows');
  if(!sorted.length){el.innerHTML='<div style="padding:2rem;text-align:center;color:var(--text3);font-size:12px">No players yet. Add via Admin panel.</div>';return;}
  el.innerHTML=sorted.map((p,i)=>{
    const rk=getRank(p.total);
    const pc=i===0?'r1':i===1?'r2':i===2?'r3':'';
    const tags=GMS.map(g=>{const t=p.modes[g.id];return t?`<span class="lb-mtag tt-${t}">${t}</span>`:''}).join('');
    return`<div class="lb-row" onclick="">
      <div class="lb-pos ${pc}">${i===0?'👑':i===1?'🥈':i===2?'🥉':'#'+(i+1)}</div>
      <div class="lb-player">
        <div class="lb-face">${p.face?`<img src="${p.face}" onerror="this.style.display='none'">`:(p.name.substring(0,2).toUpperCase())}</div>
        <div>
          <span class="lb-pname">${p.name}</span>
          <div class="lb-mode-tags">${tags||''}</div>
        </div>
      </div>
      <div><span class="pcard-rank ${rk.cls}" style="font-size:9px">${rk.label}</span></div>
      <div class="lb-score">${p.total}</div>
    </div>`;
  }).join('');
}

function setLBF(gm,btn){
  lbF=gm;
  document.querySelectorAll('#lbFilters .gm-tab').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  renderLB();
}

function initLBFilters(){
  const row=document.getElementById('lbFilters');
  GMS.forEach(g=>{
    const b=document.createElement('button');
    b.className='gm-tab';
    b.style.cssText='border-radius:6px;border:1px solid var(--border);padding:6px 12px;font-size:11px';
    b.innerHTML=g.icon+' '+g.name;
    b.onclick=function(){setLBF(g.id,this)};
    row.appendChild(b);
  });
}

// RANKS PAGE
function renderRanks(){
  // Points table
  document.getElementById('ptTable').innerHTML=Object.entries(TIER_PTS).map(([t,p])=>`
    <div style="text-align:center">
      <div style="font-size:.9rem;font-weight:900;color:${TIER_COLORS[t]||'#94a3b8'};margin-bottom:3px">${t}</div>
      <div style="font-size:10px;color:var(--text2)">= ${p} pts</div>
    </div>`).join('');
  // Rank cards
  document.getElementById('ranksGrid').innerHTML=RANKS.map(r=>`
    <div class="rcard ${r.card}">
      <div class="rcard-icon">${r.icon}</div>
      <div class="rcard-name" style="color:${r.color}">${r.label}</div>
      <div class="rcard-range">${r.min===161?'161+ pts':`${r.min}–${r.max} pts`}</div>
      <div class="rcard-desc">${r.desc}</div>
    </div>`).join('');
}

// SUBMIT
function doSubmit(){
  const u=document.getElementById('sfU').value.trim();
  const gm=document.getElementById('sfGM').value;
  if(!u||!gm){notify('Fill in username and gamemode.',true);return;}
  const tier=document.getElementById('sfT').value;
  const reason=document.getElementById('sfR').value.trim();
  const dc=document.getElementById('sfD').value.trim();
  submissions.push({id:Date.now(),username:u,gm,tier,reason,discord:dc});
  notify('Submitted! Staff will review shortly.');
  document.getElementById('sfU').value='';
  document.getElementById('sfR').value='';
  document.getElementById('sfD').value='';
}

// ADMIN
function openLogin(){document.getElementById('loginOv').classList.add('active');setTimeout(()=>document.getElementById('pwIn').focus(),100)}
function closeLogin(){document.getElementById('loginOv').classList.remove('active');document.getElementById('pwIn').value='';document.getElementById('pwErr').style.display='none'}
function checkPw(){
  if(document.getElementById('pwIn').value===ADMIN_PW){closeLogin();goPage('admin');}
  else{document.getElementById('pwErr').style.display='block';document.getElementById('pwIn').value='';document.getElementById('pwIn').focus();}
}

function renderAdmin(){
  document.getElementById('admStats').innerHTML=`
    <div class="ast"><div class="ast-n">${players.length}</div><div class="ast-l">Players</div></div>
    <div class="ast"><div class="ast-n">${GMS.length}</div><div class="ast-l">Gamemodes</div></div>
    <div class="ast"><div class="ast-n">${submissions.length}</div><div class="ast-l">Submissions</div></div>
    <div class="ast"><div class="ast-n">${players.filter(p=>getRank(p.pts||0).key==='grandmaster').length}</div><div class="ast-l">Grandmasters</div></div>
  `;
  ['aGM','aFGM'].forEach(sid=>{
    const el=document.getElementById(sid);if(!el)return;
    el.innerHTML=(sid==='aFGM'?'<option value="">All Modes</option>':'')+GMS.map(g=>`<option value="${g.id}">${g.name}</option>`).join('');
  });
  renderAT();renderASubs();
}

function renderAT(){
  const q=(document.getElementById('aSrch')?.value||'').toLowerCase();
  const gf=document.getElementById('aFGM')?.value||'';
  const data=players.filter(p=>(!q||p.name.toLowerCase().includes(q))&&(!gf||p.gm===gf));
  const gmap=Object.fromEntries(GMS.map(g=>[g.id,g.name]));
  document.getElementById('aTBody').innerHTML=data.length?data.map(p=>{
    const rk=getRank(p.pts||0);
    return`<tr>
      <td style="font-weight:700">${p.name}</td>
      <td style="color:var(--text2);font-size:10px">${gmap[p.gm]||p.gm}</td>
      <td style="font-weight:800;color:${TIER_COLORS[p.tier]||'#94a3b8'}">${p.tier}</td>
      <td style="font-family:var(--mono);color:var(--gold)">${p.pts||0}</td>
      <td><span class="pcard-rank ${rk.cls}" style="font-size:9px">${rk.label}</span></td>
      <td>
        <button class="aab e" onclick="editP(${p.id})">Edit</button>
        <button class="aab d" onclick="delP(${p.id})">Delete</button>
      </td>
    </tr>`;
  }).join(''):'<tr><td colspan="6" style="text-align:center;padding:1.5rem;color:var(--text3)">No players yet</td></tr>';
}

function renderASubs(){
  const gmap=Object.fromEntries(GMS.map(g=>[g.id,g.name]));
  document.getElementById('aSubsBody').innerHTML=submissions.length?submissions.map(s=>`<tr>
    <td style="font-weight:700">${s.username}</td>
    <td style="color:var(--text2)">${gmap[s.gm]||s.gm}</td>
    <td style="font-weight:800;color:${TIER_COLORS[s.tier]||'#94a3b8'}">${s.tier}</td>
    <td style="font-size:10px;color:var(--text2);max-width:160px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap">${s.reason||'—'}</td>
    <td>
      <button class="aab e" onclick="approveSub(${s.id})">Approve</button>
      <button class="aab d" onclick="rejectSub(${s.id})">Reject</button>
    </td>
  </tr>`).join(''):'<tr><td colspan="5" style="text-align:center;padding:1.5rem;color:var(--text3)">No pending submissions</td></tr>';
}

function addPlayer(){
  const name=document.getElementById('aU').value.trim();
  const gm=document.getElementById('aGM').value;
  const tier=document.getElementById('aTr').value;
  const ptsVal=document.getElementById('aPts').value;
  const pts=ptsVal!==''?parseInt(ptsVal):(TIER_PTS[tier]||0);
  const region=document.getElementById('aReg').value.trim()||'NA';
  const face=document.getElementById('aFaceUrl').value.trim();
  if(!name||!gm){notify('Fill in username and gamemode.',true);return;}
  players.push({id:nextId++,name,gm,tier,pts,region,face});
  document.getElementById('aU').value='';document.getElementById('aPts').value='';
  document.getElementById('aReg').value='';document.getElementById('aFaceUrl').value='';
  renderAdmin();notify(`${name} added to ${tier} Tier!`);
}

function editP(id){
  const p=players.find(x=>x.id===id);if(!p)return;
  const t=prompt(`Tier for ${p.name}? (S/A/B/C/D/F/HM)`,p.tier);if(t===null)return;
  const pt=prompt(`Points for ${p.name}?`,p.pts||0);if(pt===null)return;
  p.tier=t.toUpperCase().trim();
  p.pts=parseInt(pt)||p.pts;
  renderAdmin();notify(`${p.name} updated!`);
}
function delP(id){
  if(!confirm('Delete this player?'))return;
  players=players.filter(x=>x.id!==id);
  renderAdmin();notify('Player deleted.');
}
function approveSub(id){
  const s=submissions.find(x=>x.id===id);if(!s)return;
  players.push({id:nextId++,name:s.username,gm:s.gm,tier:s.tier,pts:TIER_PTS[s.tier]||0,region:'NA',face:''});
  submissions=submissions.filter(x=>x.id!==id);
  renderAdmin();notify(`${s.username} approved!`);
}
function rejectSub(id){
  submissions=submissions.filter(x=>x.id!==id);
  renderAdmin();notify('Rejected.');
}

function aTab(id,el){
  document.querySelectorAll('.a-tab').forEach(t=>t.classList.remove('active'));
  document.querySelectorAll('.asec').forEach(s=>s.classList.remove('active'));
  el.classList.add('active');
  document.getElementById('asec-'+id).classList.add('active');
}

// NOTIF
function notify(msg,err=false){
  const n=document.getElementById('notif');
  n.textContent=msg;
  n.style.borderColor=err?'var(--red)':'var(--green)';
  n.style.color=err?'var(--red)':'var(--green)';
  n.style.border='1px solid '+(err?'var(--red)':'var(--green)');
  n.style.display='block';
  clearTimeout(n._t);n._t=setTimeout(()=>n.style.display='none',3000);
}

// Overlay close on bg click
document.getElementById('loginOv').addEventListener('click',function(e){if(e.target===this)closeLogin()});
document.getElementById('profOv').addEventListener('click',function(e){if(e.target===this)this.classList.remove('active')});

// INIT
initGMs();
initLBFilters();
renderRanks();
renderTiers();
renderLB();
</script>
</body>
</html>

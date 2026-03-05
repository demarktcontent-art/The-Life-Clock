<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Life Clock">
<title>CEO Life Clock</title>
<style>
/* ══════════════════════════════════════
   CEO LIFE CLOCK — Black, White & Gold
   Clean, bold, premium
══════════════════════════════════════ */
:root{
  --ac:#D4A843;          /* gold accent */
  --ac-l:#F5D070;        /* light gold */
  --ac-d:#7A5C1E;        /* dark gold */
  --bg:#0A0A0A;          /* near-black page */
  --sb:#111111;          /* sidebar — deep black */
  --c1:#1A1A1A;          /* card background */
  --c2:#222222;          /* slightly lighter */
  --c3:#2E2E2E;          /* borders / inputs */
  --tx:#F5F5F5;          /* primary text — bright white */
  --tx2:#AAAAAA;         /* secondary text */
  --tx3:#555555;         /* muted text */
  --gn:#D4A843;          /* gold = done (no green, stay on-theme) */
  --pr:#D4A843;          /* gold prayer */
  --or:#D4A843;          /* gold family */
  --rd:#FF4F4F;          /* red only for danger */
  --bdr:rgba(212,168,67,.18);
  --bdr2:rgba(212,168,67,.38);
}
*{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
html{scroll-behavior:smooth;}
body{background:#0A0A0A;background-color:#0A0A0A;color:var(--tx);font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;min-height:100vh;overflow-x:hidden;}

/* ══ SIDEBAR — fully opaque on ALL browsers including iOS Safari ══ */
.sidebar{
width:260px;
background:#111111;
background-color:#111111 !important;
-webkit-background-color:#111111;
border-right:1px solid var(–bdr);
position:fixed;top:0;left:0;bottom:0;
z-index:350;
display:flex;flex-direction:column;
overflow-y:auto;
-webkit-overflow-scrolling:touch;
transition:transform .3s ease;
isolation:isolate;
}
.sidebar::-webkit-scrollbar{width:3px;}
.sidebar::-webkit-scrollbar-thumb{background:var(–c3);}

.sb-head{padding:20px 16px 14px;border-bottom:1px solid var(–bdr);background:#111111 !important;}
.sb-badge{font-size:7px;letter-spacing:3px;text-transform:uppercase;color:var(–ac);display:block;margin-bottom:5px;font-weight:600;}
.sb-title{font-size:17px;font-weight:800;color:var(–ac-l);line-height:1.2;}
.sb-sub{font-size:9px;color:var(–tx3);margin-top:3px;}

/* Ring */
.sb-ring{padding:16px;display:flex;flex-direction:column;align-items:center;border-bottom:1px solid var(–bdr);background:#111111 !important;}
.ring-wrap{position:relative;width:94px;height:94px;margin-bottom:8px;}
.ring-svg{transform:rotate(-90deg);width:94px;height:94px;}
.r-bg{fill:none;stroke:var(–c3);stroke-width:8;}
.r-fg{fill:none;stroke:var(–ac);stroke-width:8;stroke-linecap:round;stroke-dasharray:264;stroke-dashoffset:264;transition:stroke-dashoffset .7s ease;filter:drop-shadow(0 0 8px rgba(212,168,67,.7));}
.ring-ctr{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center;}
.r-pct{font-size:23px;font-weight:800;color:var(–ac-l);line-height:1;}
.r-sub{font-size:7px;color:var(–tx3);letter-spacing:2px;margin-top:2px;}
.sb-info{font-size:12px;color:var(–tx2);text-align:center;font-weight:500;}
.sb-info b{color:var(–ac-l);font-weight:700;}

/* Days */
.sb-days{padding:12px 16px;border-bottom:1px solid var(–bdr);background:#111111 !important;}
.sec-lbl{font-size:7px;letter-spacing:2px;text-transform:uppercase;color:var(–tx3);margin-bottom:8px;display:block;font-weight:600;}
.day-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:4px;}
.d-btn{
aspect-ratio:1;border:1px solid var(–bdr);
background:var(–c1);color:var(–tx2);
font-size:12px;font-weight:700;cursor:pointer;
border-radius:5px;transition:all .2s;
display:flex;align-items:center;justify-content:center;position:relative;
}
.d-btn:active{opacity:.7;}
.d-btn.active{background:var(–ac-d);border-color:var(–ac);color:#fff;}
.d-dot{width:4px;height:4px;border-radius:50%;background:var(–gn);position:absolute;bottom:2px;right:2px;display:none;}
.d-btn.has-p .d-dot{display:block;}

/* Search */
.sb-search{padding:10px 16px;border-bottom:1px solid var(–bdr);background:#111111 !important;}
.search-wrap{display:flex;align-items:center;gap:7px;background:var(–c1);border:1px solid var(–bdr);border-radius:6px;padding:8px 11px;}
.search-wrap:focus-within{border-color:var(–ac);box-shadow:0 0 0 1px rgba(212,168,67,.15);}
.search-icon{font-size:12px;color:var(–tx3);flex-shrink:0;}
.search-inp{background:transparent;border:none;outline:none;color:var(–tx);font-size:12px;width:100%;}
.search-inp::placeholder{color:var(–tx3);}
.search-clear{font-size:12px;color:var(–tx3);cursor:pointer;display:none;}
.search-clear.show{display:block;}

/* Nav */
.sb-nav{flex:1;padding:4px 0;overflow-y:auto;background:#111111 !important;}
.n-item{display:flex;align-items:center;gap:9px;padding:8px 16px;cursor:pointer;border-left:2px solid transparent;text-decoration:none;transition:background .15s;}
.n-item:active,.n-item.act{background:rgba(212,168,67,.08);border-left-color:var(–ac);}
.n-icon{font-size:13px;width:15px;text-align:center;}
.n-info{flex:1;}
.n-name{font-size:11px;font-weight:600;color:var(–tx);display:block;line-height:1.3;}
.n-time{font-size:8px;color:var(–tx3);}
.n-bar{width:24px;height:3px;background:var(–c3);border-radius:2px;overflow:hidden;}
.n-fill{height:100%;background:var(–ac);transition:width .4s;width:0%;}

/* Sidebar actions */
.sb-actions{padding:10px 16px 14px;border-top:1px solid var(–bdr);background:#111111 !important;display:flex;flex-direction:column;gap:5px;}
.rem-tog{width:100%;padding:9px 12px;background:var(–c1);border:1px solid var(–bdr);border-radius:5px;display:flex;align-items:center;justify-content:space-between;cursor:pointer;}
.rem-lbl{font-size:10px;color:var(–tx2);font-weight:600;}
.rem-ind{width:28px;height:15px;background:var(–c3);border-radius:8px;position:relative;transition:background .2s;}
.rem-ind.on{background:var(–ac);}
.rem-dot{width:11px;height:11px;background:#fff;border-radius:50%;position:absolute;top:2px;left:2px;transition:left .2s;}
.rem-ind.on .rem-dot{left:15px;}
.sb-btn-row{display:flex;gap:5px;}
.sb-btn{flex:1;padding:8px 4px;background:var(–c1);border:1px solid var(–bdr);color:var(–tx2);font-size:9px;letter-spacing:.5px;text-transform:uppercase;cursor:pointer;border-radius:5px;font-weight:700;}
.sb-btn:active{background:var(–c2);border-color:var(–ac);color:var(–ac-l);}
.sb-btn.danger:active{border-color:var(–rd);color:var(–rd);}
.sb-btn.mentor-btn{color:var(–ac-l);border-color:var(–ac-d);background:rgba(212,168,67,.06);}

/* ══ MAIN ══ */
.main{margin-left:260px;min-height:100vh;padding-bottom:60px;}
.g-bar{height:3px;background:var(–c3);}
.g-fill{height:100%;background:linear-gradient(to right,var(–ac-d),var(–ac-l));transition:width .6s;width:0%;box-shadow:0 0 10px rgba(212,168,67,.4);}

.topbar{
position:sticky;top:0;z-index:100;
background:#1A1A1A;
background-color:#1A1A1A;
border-bottom:1px solid var(–bdr);
padding:11px 18px;
display:flex;align-items:center;justify-content:space-between;
box-shadow:0 2px 16px rgba(0,0,0,.6);
}
.tb-left{}
.tb-clk{font-size:19px;font-weight:800;color:var(–ac-l);letter-spacing:2px;font-variant-numeric:tabular-nums;line-height:1;}
.tb-dt{font-size:9px;color:var(–tx3);margin-top:2px;font-weight:500;}
.tb-r{display:flex;gap:16px;}
.tb-stat{text-align:center;}
.tb-n{font-size:17px;font-weight:800;color:var(–tx);line-height:1;display:block;}
.tb-n.gold{color:var(–ac-l);}
.tb-l2{font-size:7px;color:var(–tx3);letter-spacing:1px;text-transform:uppercase;margin-top:2px;display:block;}

.content{padding:0 16px;}

/* Banner */
.cur-banner{display:none;margin:10px 0 0;padding:10px 14px;background:rgba(212,168,67,.07);border:1px solid rgba(212,168,67,.22);border-radius:6px;align-items:center;gap:8px;}
.cur-banner.show{display:flex;}
.cb-pulse{width:7px;height:7px;border-radius:50%;background:var(–ac);animation:pulse 1.5s ease infinite;flex-shrink:0;}
.cb-tx{font-size:11px;color:var(–tx2);font-weight:500;}
.cb-tx b{color:var(–ac-l);}

/* Streak */
.streak-row{display:flex;gap:3px;margin:8px 0 3px;}
.s-pip{min-width:23px;height:23px;border-radius:4px;background:var(–c1);border:1px solid var(–bdr);display:flex;align-items:center;justify-content:center;font-size:9px;color:var(–tx3);font-weight:700;}
.s-pip.partial{background:rgba(212,168,67,.15);border-color:rgba(212,168,67,.4);color:var(–ac);}
.s-pip.full{background:var(–ac-d);border-color:var(–ac);color:var(–ac-l);}

.congrats{display:none;margin:10px 0;padding:14px 18px;background:rgba(212,168,67,.08);border:1px solid rgba(212,168,67,.3);border-radius:6px;text-align:center;}
.congrats.show{display:block;}
.congrats h2{font-size:18px;font-weight:800;color:var(–ac-l);margin-bottom:3px;}
.congrats p{font-size:11px;color:var(–tx2);}

/* Phase sections */
.phase-sec{margin-top:2px;}
.ph-hdr{display:flex;align-items:center;gap:10px;padding:16px 0 9px;position:sticky;top:46px;z-index:50;background:#0A0A0A;background-color:#0A0A0A;}
.ph-icon{font-size:19px;}
.ph-info{flex:1;}
.ph-title{font-size:14px;font-weight:800;color:var(–tx);line-height:1;}
.ph-time-lbl{font-size:9px;color:var(–tx3);margin-top:2px;}
.ph-cnt{font-size:9px;font-weight:700;color:var(–ac);background:rgba(212,168,67,.10);padding:3px 8px;border-radius:10px;border:1px solid rgba(212,168,67,.25);}
.ph-line{height:1px;background:linear-gradient(to right,rgba(212,168,67,.35),transparent);margin-bottom:5px;}

/* ══ HABIT CARD ══ */
/* ══ HABIT CARD ══ */
.hcard{
background:var(–c1);
border:1px solid var(–c3);
border-radius:8px;
margin-bottom:7px;
overflow:hidden;
transition:border-color .18s,background .18s;
}
.hcard[data-type=“prayer”]{border-left:3px solid var(–pr);}
.hcard[data-type=“work”]  {border-left:3px solid var(–ac);}
.hcard[data-type=“rest”]  {border-left:3px solid var(–gn);}
.hcard[data-type=“habit”] {border-left:3px solid rgba(212,168,67,.7);}
.hcard[data-type=“family”]{border-left:3px solid var(–or);}

/* DONE — gold tint, clearly readable */
.hcard.done{
background:rgba(212,168,67,.10);
border:1px solid rgba(212,168,67,.45);
border-left:3px solid var(–ac) !important;
}
.hcard.done .hc-name{
color:var(–ac-l) !important;
text-decoration:line-through;
text-decoration-color:rgba(212,168,67,.4);
}
.hcard.done .hc-hint{color:rgba(212,168,67,.6) !important;}
.hcard.done .hc-t{color:var(–ac-l) !important;}
.hcard.done .chk{
background:var(–ac);
border-color:var(–ac);
color:#000;
font-size:16px;
font-weight:800;
}

.hcard.now{
border-color:var(–ac) !important;
box-shadow:0 0 0 2px rgba(212,168,67,.15);
}
.hcard.search-match{border-color:var(–ac) !important;background:rgba(212,168,67,.07);}
.hcard.search-hidden{display:none;}

.hc-row{display:grid;grid-template-columns:54px 1fr 42px;min-height:52px;cursor:pointer;}
.hc-left{padding:9px 6px;border-right:1px solid var(–bdr);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:3px;}
.hc-t{font-size:11px;font-weight:800;color:var(–ac-l);text-align:center;line-height:1.2;}
.hc-num{font-size:8px;font-weight:500;color:var(–tx3);text-align:center;}
.hc-mid{padding:10px 12px;display:flex;flex-direction:column;justify-content:center;gap:3px;}
.hc-name{font-size:13px;font-weight:700;color:var(–tx);line-height:1.3;}
.hcard.done .hc-name{color:var(–gn);text-decoration:line-through;text-decoration-color:rgba(212,168,67,.4);}
.hc-hint{font-size:10px;color:#999999;line-height:1.45;}
.hcard.done .hc-hint{color:rgba(212,168,67,.6);}
.hc-work-tag{display:inline-block;font-size:8px;font-weight:700;color:var(–ac);background:rgba(212,168,67,.08);border:1px solid rgba(212,168,67,.22);padding:2px 7px;border-radius:3px;margin-top:3px;}
.hc-chk{border-left:1px solid var(–bdr);display:flex;align-items:center;justify-content:center;}
.chk{width:28px;height:28px;border-radius:50%;border:2px solid var(–bdr2);background:var(–c2);display:flex;align-items:center;justify-content:center;font-size:14px;color:transparent;transition:all .2s;}
.hcard.done .chk{background:var(–gn);border-color:var(–gn);color:#fff;}

/* Expand */
.hc-expand{max-height:0;overflow:hidden;transition:max-height .28s ease;border-top:0 solid var(–bdr);}
.hc-expand.open{max-height:400px;border-top:1px solid var(–bdr);}
.hc-exp-inner{padding:10px 12px 12px;}
.exp-lbl{font-size:8px;letter-spacing:2px;text-transform:uppercase;color:var(–ac);margin-bottom:7px;font-weight:800;}
.w-row{display:flex;align-items:center;gap:9px;padding:7px 8px;border-radius:5px;cursor:pointer;transition:background .15s;}
.w-row:active{background:rgba(212,168,67,.07);}
.w-row.done{background:rgba(212,168,67,.08);}
.w-cb{width:18px;height:18px;min-width:18px;min-height:18px;border:1.5px solid var(–bdr2);border-radius:3px;background:var(–c2);display:flex;align-items:center;justify-content:center;font-size:10px;color:transparent;flex-shrink:0;transition:all .18s;}
.w-row.done .w-cb{background:var(–ac);border-color:var(–ac);color:#000;font-weight:800;}
.w-lbl{font-size:11px;color:var(–tx2);line-height:1.4;flex:1;}
.w-row.done .w-lbl{color:var(–tx3);text-decoration:line-through;}

/* Report */
.report-panel{display:none;margin:10px 0;background:var(–c1);border:1px solid var(–bdr2);border-radius:8px;overflow:hidden;}
.report-panel.show{display:block;}
.rp-head{padding:14px 16px;border-bottom:1px solid var(–bdr);display:flex;justify-content:space-between;align-items:center;background:var(–c2);}
.rp-title{font-size:14px;font-weight:800;color:var(–ac-l);}
.rp-close{font-size:18px;color:var(–tx3);cursor:pointer;padding:2px 6px;}
.rp-body{padding:14px 16px;}
.rp-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:5px;margin-bottom:14px;}
.rp-day{background:var(–c2);border:1px solid var(–bdr);border-radius:5px;padding:7px 4px;text-align:center;}
.rp-dn{font-size:8px;color:var(–tx3);margin-bottom:3px;font-weight:600;}
.rp-pct{font-size:14px;font-weight:800;color:var(–tx3);}
.rp-pct.ok{color:var(–ac);}
.rp-pct.great{color:var(–gn);}
.rp-summary{font-size:11px;color:var(–tx2);line-height:1.65;background:var(–c2);padding:12px 14px;border-radius:5px;border-left:3px solid var(–ac);}

/* Mentor */
.mentor-overlay{position:fixed;inset:0;background:rgba(0,0,0,.78);z-index:2000;display:none;align-items:flex-end;justify-content:center;}
.mentor-overlay.show{display:flex;}
.mentor-box{background:var(–c1);border:1px solid var(–bdr2);border-radius:14px 14px 0 0;width:100%;max-width:600px;max-height:80vh;display:flex;flex-direction:column;overflow:hidden;}
.mentor-head{padding:14px 16px;border-bottom:1px solid var(–bdr);display:flex;align-items:center;gap:10px;flex-shrink:0;background:var(–c2);}
.mentor-avatar{width:38px;height:38px;border-radius:50%;background:linear-gradient(135deg,var(–ac-d),var(–ac));display:flex;align-items:center;justify-content:center;font-size:20px;flex-shrink:0;}
.mentor-info{flex:1;}
.mentor-name{font-size:14px;font-weight:800;color:var(–ac-l);}
.mentor-status{font-size:9px;color:var(–tx3);}
.mentor-close{font-size:22px;color:var(–tx3);cursor:pointer;padding:2px 8px;}
.mentor-msgs{flex:1;overflow-y:auto;padding:14px 16px;display:flex;flex-direction:column;gap:9px;background:#0A0A0A;background-color:#0A0A0A;-webkit-overflow-scrolling:touch;}
.msg{max-width:88%;padding:10px 13px;border-radius:9px;font-size:12px;line-height:1.6;}
.msg.bot{background:var(–c1);border:1px solid var(–bdr);color:var(–tx);align-self:flex-start;border-radius:4px 9px 9px 9px;}
.msg.user{background:rgba(212,168,67,.10);border:1px solid rgba(212,168,67,.25);color:var(–tx);align-self:flex-end;border-radius:9px 4px 9px 9px;}
.msg.typing{color:var(–tx3);font-style:italic;}
.mentor-inp{display:flex;gap:8px;padding:12px 16px;border-top:1px solid var(–bdr);flex-shrink:0;background:var(–c1);}
.mentor-input{flex:1;background:var(–c2);border:1px solid var(–bdr);border-radius:6px;padding:10px 13px;color:var(–tx);font-size:12px;outline:none;}
.mentor-input:focus{border-color:var(–ac);}
.mentor-send{background:var(–ac);border:none;border-radius:6px;padding:10px 16px;color:#000;font-size:12px;font-weight:800;cursor:pointer;}

/* Popup */
.overlay{position:fixed;inset:0;background:rgba(0,0,0,.8);z-index:1999;display:none;}
.overlay.show{display:block;}
.popup{position:fixed;top:50%;left:50%;transform:translate(-50%,-60%) scale(.9);background:var(–c1);border:1px solid var(–bdr2);border-radius:12px;padding:26px 22px;max-width:380px;width:90%;text-align:center;opacity:0;pointer-events:none;transition:all .28s;z-index:2001;}
.popup.show{transform:translate(-50%,-50%) scale(1);opacity:1;pointer-events:all;}
.pp-icon{font-size:34px;margin-bottom:9px;}
.pp-title{font-size:17px;font-weight:800;color:var(–ac-l);margin-bottom:4px;}
.pp-time{font-size:9px;color:var(–ac);letter-spacing:2px;margin-bottom:7px;font-weight:600;}
.pp-desc{font-size:11px;color:var(–tx2);line-height:1.6;margin-bottom:17px;}
.pp-btns{display:flex;gap:9px;justify-content:center;}
.pp-btn{padding:10px 18px;border-radius:6px;font-size:9px;letter-spacing:1px;text-transform:uppercase;cursor:pointer;border:1px solid;font-weight:800;}
.pp-ok{background:var(–ac);border-color:var(–ac);color:#000;}
.pp-skip{background:transparent;border-color:var(–bdr);color:var(–tx3);}

/* Toast */
.toast{position:fixed;top:60px;left:50%;transform:translateX(-50%) translateY(-20px);background:var(–c2);border:1px solid var(–gn);border-radius:20px;padding:10px 18px;font-size:12px;color:var(–gn);opacity:0;transition:all .26s;z-index:9999;white-space:nowrap;font-weight:700;box-shadow:0 4px 20px rgba(0,0,0,.5);}
.toast.show{transform:translateX(-50%) translateY(0);opacity:1;}
.toast.warn{border-color:var(–or);color:var(–or);}
.toast.info{border-color:var(–ac);color:var(–ac-l);}

/* Menu */
.menu-btn{display:none;position:fixed;top:0;left:0;z-index:400;background:#111111 !important;border:none;border-right:1px solid var(–bdr);border-bottom:1px solid var(–bdr);padding:13px 15px;color:var(–ac);cursor:pointer;font-size:19px;line-height:1;}
.bdrop{display:none;position:fixed;inset:0;background:rgba(0,0,0,.72);z-index:300;}
.bdrop.show{display:block;}

/* Scrollbar */
::-webkit-scrollbar{width:3px;height:3px;}
::-webkit-scrollbar-thumb{background:var(–c3);border-radius:2px;}

@media(max-width:680px){
.sidebar{transform:translateX(-100%);box-shadow:8px 0 32px rgba(0,0,0,.8);}
.sidebar.open{transform:translateX(0);}
.main{margin-left:0 !important;}
.menu-btn{display:flex;align-items:center;justify-content:center;}
.topbar{padding:10px 10px 10px 52px;}
.content{padding:0 10px;}
.tb-clk{font-size:15px;}
.ph-hdr{top:44px;background:#0A0A0A;background-color:#0A0A0A;}
.hc-row{grid-template-columns:50px 1fr 40px;}
.hc-name{font-size:12px;}
.hc-hint{font-size:10px;}
.mentor-box{max-height:88vh;}
}
@keyframes pulse{0%,100%{box-shadow:0 0 0 0 rgba(212,168,67,.5);}50%{box-shadow:0 0 0 7px rgba(212,168,67,0);}}
::-webkit-scrollbar{width:3px;height:3px;}
::-webkit-scrollbar-thumb{background:var(–c3);border-radius:2px;}
</style>

</head>
<body>
<button class="menu-btn" id="menuBtn">☰</button>
<div class="bdrop" id="bdrop"></div>

<!-- ══ SIDEBAR ══ -->

<div class="sidebar" id="sidebar">
  <div class="sb-head">
    <span class="sb-badge">Coach Kanchon · March 2026</span>
    <div class="sb-title">CEO Life Clock™</div>
    <div class="sb-sub">Focus Phase · I AM Disciplined</div>
  </div>
  <div class="sb-ring">
    <div class="ring-wrap">
      <svg class="ring-svg" viewBox="0 0 92 92">
        <circle class="r-bg" cx="46" cy="46" r="41"/>
        <circle class="r-fg" id="ringFg" cx="46" cy="46" r="41"/>
      </svg>
      <div class="ring-ctr">
        <span class="r-pct" id="ringPct">0%</span>
        <span class="r-sub">TODAY</span>
      </div>
    </div>
    <div class="sb-info"><b id="doneC">0</b> / <b id="totalC">42</b> habits</div>
  </div>
  <div class="sb-days">
    <span class="sec-lbl">Phase Block — Days 1–10</span>
    <div class="day-grid" id="dayGrid"></div>
  </div>
  <div class="sb-search">
    <div class="search-wrap">
      <span class="search-icon">🔍</span>
      <input class="search-inp" id="searchInp" type="text" placeholder="Search habit # or name…" inputmode="search">
      <span class="search-clear" id="searchClear">✕</span>
    </div>
  </div>
  <nav class="sb-nav" id="sbNav"></nav>
  <div class="sb-actions">
    <div class="rem-tog" id="remTog">
      <span class="rem-lbl">🔔 Block Reminders</span>
      <div class="rem-ind" id="remInd"><div class="rem-dot"></div></div>
    </div>
    <div class="sb-btn-row">
      <button class="sb-btn mentor-btn" id="mentorBtn">🧠 Mentor</button>
      <button class="sb-btn" id="reportBtn">📊 Report</button>
      <button class="sb-btn danger" id="rstBtn">↺ Reset</button>
    </div>
  </div>
</div>

<!-- ══ MAIN ══ -->

<div class="main">
  <div class="g-bar"><div class="g-fill" id="gFill"></div></div>
  <div class="topbar">
    <div class="tb-left">
      <div class="tb-clk" id="tbClk">--:--:--</div>
      <div class="tb-dt" id="tbDt">—</div>
    </div>
    <div class="tb-r">
      <div class="tb-stat"><span class="tb-n gold" id="tbDone">0</span><span class="tb-l2">Done</span></div>
      <div class="tb-stat"><span class="tb-n" id="tbLeft">42</span><span class="tb-l2">Left</span></div>
      <div class="tb-stat"><span class="tb-n gold" id="tbDay">D1</span><span class="tb-l2">Day</span></div>
    </div>
  </div>
  <div class="content">
    <div class="cur-banner" id="curBanner"><div class="cb-pulse"></div><div class="cb-tx">Now: <b id="cbTx">—</b></div></div>
    <div class="streak-row" id="streakRow"></div>
    <div class="congrats" id="congrats"><h2>🏆 Perfect Day!</h2><p>All 42 habits done. Mark them in your Life Clock paper tracker!</p></div>
    <div class="report-panel" id="reportPanel">
      <div class="rp-head"><span class="rp-title">📊 10-Day Progress Report</span><span class="rp-close" id="rpClose">✕</span></div>
      <div class="rp-body">
        <div class="rp-grid" id="rpGrid"></div>
        <div class="rp-summary" id="rpSummary">Loading…</div>
      </div>
    </div>
    <div id="mainCon"></div>
  </div>
</div>

<!-- ══ MENTOR ══ -->

<div class="mentor-overlay" id="mentorOverlay">
  <div class="mentor-box">
    <div class="mentor-head">
      <div class="mentor-avatar">🧠</div>
      <div class="mentor-info">
        <div class="mentor-name">Coach Kanchon AI</div>
        <div class="mentor-status">Your Life Clock Mentor · Always watching your progress</div>
      </div>
      <span class="mentor-close" id="mentorClose">✕</span>
    </div>
    <div class="mentor-msgs" id="mentorMsgs"></div>
    <div class="mentor-inp">
      <input class="mentor-input" id="mentorInput" type="text" placeholder="Ask your mentor anything…">
      <button class="mentor-send" id="mentorSend">Send</button>
    </div>
  </div>
</div>

<!-- ══ REMINDER POPUP ══ -->

<div class="overlay" id="overlay"></div>
<div class="popup" id="popup">
  <div class="pp-icon" id="ppIcon">⏰</div>
  <div class="pp-title" id="ppTitle">—</div>
  <div class="pp-time" id="ppTime">—</div>
  <div class="pp-desc" id="ppDesc">—</div>
  <div class="pp-btns">
    <button class="pp-btn pp-ok" id="ppOk">✓ Mark Done</button>
    <button class="pp-btn pp-skip" id="ppSkip">Snooze 5m</button>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
// ════════════════════════════════════════════════════
//  CEO LIFE CLOCK  — Full 42 Habits, Time-Organised
//  5 Prayers at correct windows
//  Work: 10 AM – 7 PM
//  Persistent memory via localStorage (survives refresh/close)
// ════════════════════════════════════════════════════
var BLOCKS=[
  {id:"s1",icon:"🌅",title:"Fajr + Morning Identity",time:"5:00 – 5:55 AM",type:"prayer",habits:[
    {n:36,id:"h36a",hid:"h36",tag:"5:00 AM",type:"prayer",name:"Fajr Prayer",hint:"Start with the Almighty. Full salah — 5:00–6:00 AM window.",work:[]},
    {n:37,id:"h37a",hid:"h37",tag:"5:20 AM",type:"prayer",name:"Remembrance (Dhikr)",hint:"Morning adhkar — 5 min after Fajr.",work:[]},
    {n:38,id:"h38a",hid:"h38",tag:"5:25 AM",type:"prayer",name:"Sacred Reading",hint:"One page of Quran every single day.",work:[]},
    {n:1, id:"h1", hid:"h1", tag:"5:35 AM",type:"habit",name:"Power Declaration",hint:'"I AM Disciplined" — say it out loud 3 times.',work:[]},
    {n:2, id:"h2", hid:"h2", tag:"5:38 AM",type:"habit",name:"Mind Movie",hint:"Visualise your best CEO self for 60 seconds.",work:[]},
    {n:3, id:"h3", hid:"h3", tag:"5:40 AM",type:"habit",name:"Power Pose",hint:"Stand tall, smile wide — 2 full minutes.",work:[]},
    {n:6, id:"h6", hid:"h6", tag:"5:43 AM",type:"habit",name:"Gratitude Drop",hint:"Write 3 things you are genuinely thankful for.",work:[]},
    {n:39,id:"h39a",hid:"h39",tag:"5:47 AM",type:"prayer",name:"Good Deed Intention",hint:"Plan today's unseen, unsaid good act now.",work:[]},
  ]},
  {id:"s2",icon:"💪",title:"Physical Power",time:"6:00 – 7:00 AM",type:"habit",habits:[
    {n:16,id:"h16",hid:"h16",tag:"6:00 AM",type:"habit",name:"Body Weight (kg)",hint:"Log your weight every morning — track the data.",work:[]},
    {n:10,id:"h10",hid:"h10",tag:"6:02 AM",type:"habit",name:"Hydrate",hint:"Drink 2 glasses now. Target 10+ glasses all day.",work:[]},
    {n:11,id:"h11",hid:"h11",tag:"6:05 AM",type:"habit",name:"Move — Exercise",hint:"30 min: Gym / HIIT / Yoga / Walk. Zero excuse.",work:[]},
    {n:14,id:"h14a",hid:"h14",tag:"6:35 AM",type:"habit",name:"Touch",hint:"Walk barefoot — 2 min grounding on earth.",work:[]},
    {n:34,id:"h34",hid:"h34",tag:"6:38 AM",type:"habit",name:"Nature Touch",hint:"Sunlight, fresh air — 5 minutes outside.",work:[]},
    {n:7, id:"h7", hid:"h7", tag:"6:43 AM",type:"habit",name:"Mental Hygiene",hint:"1-min pause & micro reset — exhale all pressure.",work:[]},
  ]},
  {id:"s3",icon:"🍳",title:"Breakfast + Emotional Reset",time:"7:00 – 8:00 AM",type:"rest",habits:[
    {n:13,id:"h13a",hid:"h13",tag:"7:00 AM",type:"rest",name:"Eat Healthy",hint:"Balanced carb + protein + fat. No screen while eating.",work:[]},
    {n:8, id:"h8a", hid:"h8", tag:"7:15 AM",type:"habit",name:"Mindful Moments",hint:"Fully present — taste your food, no multitasking.",work:[]},
    {n:4, id:"h4", hid:"h4", tag:"7:25 AM",type:"habit",name:"Emotional Alchemy",hint:"Feel → Flow → Free & Forever Fulfilling (F²F²).",work:[]},
    {n:5, id:"h5", hid:"h5", tag:"7:35 AM",type:"habit",name:"Empathy Practice",hint:"Recognise one person's feeling — team or customer.",work:[
      {id:"w5a",tx:"Read 1 customer review or complaint with empathy"},
      {id:"w5b",tx:"Acknowledge 1 team member's effort genuinely"},
    ]},
    {n:9, id:"h9", hid:"h9", tag:"7:45 AM",type:"habit",name:"Alignment Win (AW)",hint:"Do 1 hard thing aligned with your core values.",work:[
      {id:"w9a",tx:"Make the CEO decision you have been avoiding"},
    ]},
  ]},
  {id:"s4",icon:"📊",title:"CEO Command — Numbers + Big 3",time:"8:00 – 10:00 AM",type:"habit",habits:[
    {n:17,id:"h17",hid:"h17",tag:"8:00 AM",type:"habit",name:"Momentum Meter",hint:"Set your intention. 5-sec rule. No distraction.",work:[
      {id:"w17a",tx:"Set today's #1 focus intention — write it down"},
      {id:"w17b",tx:"Review yesterday: sales, ad ROAS, revenue"},
      {id:"w17c",tx:"Check team KPIs, orders, open issues"},
    ]},
    {n:20,id:"h20",hid:"h20",tag:"8:20 AM",type:"habit",name:"Three Big Moves",hint:"90-90-90: Push what truly moves the needle today.",work:[
      {id:"w20a",tx:"Big Move 1 — top revenue or growth action"},
      {id:"w20b",tx:"Big Move 2 — operations or product priority"},
      {id:"w20c",tx:"Big Move 3 — team, system, or brand task"},
    ]},
    {n:25,id:"h25",hid:"h25",tag:"9:00 AM",type:"habit",name:"Study Time",hint:"CK / BRAVE — invest in your knowledge daily.",work:[
      {id:"w25a",tx:"30 min: CK / BRAVE study session"},
    ]},
    {n:26,id:"h26a",hid:"h26",tag:"9:30 AM",type:"habit",name:"Read 10+ Minutes",hint:"Feed your brain — business, marketing, or growth.",work:[
      {id:"w26a",tx:"Read: business / ads / eCommerce book"},
    ]},
  ]},
  {id:"s5",icon:"🔥",title:"Deep Work Block 1",time:"10:00 – 11:30 AM",type:"work",habits:[
    {n:19,id:"h19a",hid:"h19",tag:"10:00 AM",type:"work",name:"90-Min Block — Growth Engine",hint:"Phone OFF. DND. No WhatsApp. Build, not just run.",work:[
      {id:"w19a",tx:"MON/WED: Meta/Google Ads — scale winners, cut losers"},
      {id:"w19b",tx:"TUE/THU: Products & suppliers — listings, sourcing"},
      {id:"w19c",tx:"FRI: Systems & SOPs — automation, hiring"},
      {id:"w19d",tx:"SAT: Brand & content strategy"},
    ]},
    {n:18,id:"h18",hid:"h18",tag:"11:00 AM",type:"work",name:"Content Create Daily",hint:"Post & impact — create and publish every day.",work:[
      {id:"w18a",tx:"Create 1 content piece — video, ad, or brand post"},
      {id:"w18b",tx:"Influencer outreach — DM 3 creators"},
      {id:"w18c",tx:"Review content performance & moderator feedback"},
    ]},
  ]},
  {id:"s6",icon:"⚡",title:"Deep Work Block 2",time:"11:30 AM – 1:00 PM",type:"work",habits:[
    {n:19,id:"h19b",hid:"h19",tag:"11:30 AM",type:"work",name:"90-Min Block — Operations",hint:"Customer, competitor, ads optimisation. Data only.",work:[
      {id:"w19e",tx:"Customer feedback — reviews, returns, support tickets"},
      {id:"w19f",tx:"Competitor analysis — pricing, listings, new ads"},
      {id:"w19g",tx:"Warranty & quality review — flag issues"},
      {id:"w19h",tx:"Ad campaigns — pause losers, scale winners"},
    ]},
    {n:27,id:"h27a",hid:"h27",tag:"12:30 PM",type:"habit",name:"Micro-Learn Daily",hint:"1 new skill, tactic, or platform insight today.",work:[
      {id:"w27a",tx:"Learn 1 new: Meta Ads / Daraz tactic / B2B tip"},
    ]},
  ]},
  {id:"s7",icon:"🕐",title:"Dhuhr + Lunch + Family",time:"1:00 – 2:30 PM",type:"prayer",habits:[
    {n:36,id:"h36b",hid:"h36",tag:"1:00 PM",type:"prayer",name:"Dhuhr Prayer",hint:"Sacred midday pause — full salah. 1:00–2:00 PM window.",work:[]},
    {n:13,id:"h13b",hid:"h13",tag:"1:20 PM",type:"rest",name:"Eat Healthy — Lunch",hint:"Balanced meal. Sit down. No screen at table.",work:[]},
    {n:30,id:"h30",hid:"h30",tag:"1:35 PM",type:"family",name:"Meaningful Talk",hint:"10 min undistracted connection — family or team.",work:[
      {id:"w30a",tx:"Team feedback call — what's working, what's blocked"},
    ]},
    {n:31,id:"h31",hid:"h31",tag:"1:50 PM",type:"family",name:"Play or Learn with Kids",hint:"Presence is the best parenting — 15 minutes.",work:[]},
    {n:15,id:"h15",hid:"h15",tag:"2:10 PM",type:"rest",name:"Power Nap",hint:"19 minutes exactly — set timer now. Non-negotiable.",work:[]},
  ]},
  {id:"s8",icon:"💰",title:"Wealth Block",time:"2:30 – 4:00 PM",type:"work",habits:[
    {n:21,id:"h21",hid:"h21",tag:"2:30 PM",type:"work",name:"Numbers Check — Scorecard",hint:"Know your numbers. No guessing in business.",work:[
      {id:"w21a",tx:"Sales vs Reach ₹50 daily target — actual count"},
      {id:"w21b",tx:"Ad spend vs ROAS — cut, hold, or scale decision"},
      {id:"w21c",tx:"Daraz & Packly dashboards — rankings, seller score"},
      {id:"w21d",tx:"Cashflow — incoming, outgoing, net position today"},
    ]},
    {n:22,id:"h22",hid:"h22",tag:"2:50 PM",type:"work",name:"Daily Sales / Income",hint:"Record today's sales. Track daily without fail.",work:[
      {id:"w22a",tx:"Log actual revenue in scorecard"},
      {id:"w22b",tx:"Note top-selling product today"},
    ]},
    {n:23,id:"h23",hid:"h23",tag:"3:05 PM",type:"work",name:"Savings + Expense Awareness",hint:"No mindless spending. Record every expense.",work:[
      {id:"w23a",tx:"Record all business expenses today"},
      {id:"w23b",tx:"Flag any unnecessary spending"},
      {id:"w23c",tx:"Budget check — within operational target?"},
    ]},
  ]},
  {id:"s8b",icon:"🕌",title:"Asr Prayer",time:"4:00 – 4:15 PM",type:"prayer",habits:[
    {n:36,id:"h36c",hid:"h36",tag:"4:00 PM",type:"prayer",name:"Asr Prayer",hint:"Pause everything. Pray. Reset your afternoon intention. 4:00–5:00 PM window.",work:[]},
  ]},
  {id:"s9",icon:"🚀",title:"Deep Work Block 3",time:"4:15 – 5:45 PM",type:"work",habits:[
    {n:19,id:"h19c",hid:"h19",tag:"4:15 PM",type:"work",name:"90-Min Block — Scale & B2B",hint:"Marketplace, B2B, influencers. Revenue multipliers.",work:[
      {id:"w19i",tx:"B2B strategy — pipeline, bulk deals, new partners"},
      {id:"w19j",tx:"Daraz seller update — listings, campaigns, score"},
      {id:"w19k",tx:"Packly dashboard — packaging, print, delivery"},
      {id:"w19l",tx:"Influencer outreach — DM 3 or follow up actives"},
    ]},
    {n:24,id:"h24",hid:"h24",tag:"5:15 PM",type:"work",name:"Act of Giving",hint:"Give time, money, or kindness to someone today.",work:[
      {id:"w24a",tx:"Send appreciation to 1 supplier or partner"},
    ]},
    {n:28,id:"h28",hid:"h28",tag:"5:25 PM",type:"habit",name:"Practice New Language",hint:"10 minutes daily — every skill rewires your destiny.",work:[]},
  ]},
  {id:"s10",icon:"📈",title:"Deep Work Block 4 — Finance + Team",time:"5:45 – 7:00 PM",type:"work",habits:[
    {n:33,id:"h33",hid:"h33",tag:"5:45 PM",type:"habit",name:"Organise — Desk, Inbox, Space",hint:"Your space either drains or defines you.",work:[
      {id:"w33a",tx:"Clear desk, organise inbox & high-energy corner"},
    ]},
    {n:29,id:"h29a",hid:"h29",tag:"5:55 PM",type:"work",name:"Love Bomb",hint:"Send love through a message, call, or kind act.",work:[
      {id:"w29a",tx:"Appreciation message to 1 team member"},
      {id:"w29b",tx:"Recognition or thanks to 1 supplier / partner"},
    ]},
    {n:41,id:"h41",hid:"h41",tag:"6:05 PM",type:"work",name:"Mentor / Partner Check-In",hint:"Accountability keeps the fire lit.",work:[
      {id:"w41a",tx:"Team feedback — working, blocked, needs CEO call"},
      {id:"w41b",tx:"Message or call mentor / accountability partner"},
    ]},
    {n:32,id:"h32",hid:"h32",tag:"6:30 PM",type:"habit",name:"Apologise or Forgive Fast",hint:"Release 1 grudge today — your soul will breathe.",work:[
      {id:"w32a",tx:"Release 1 business frustration or team conflict"},
    ]},
    {n:35,id:"h35a",hid:"h35",tag:"6:50 PM",type:"habit",name:"Digital Detox",hint:"Log off work apps. Disconnect to reconnect. Work ends at 7 PM.",work:[
      {id:"w35a",tx:"Close all work apps — work day ends at 7 PM"},
    ]},
  ]},
  {id:"s11",icon:"🌆",title:"Maghrib + Family Time",time:"6:00 – 7:30 PM",type:"family",habits:[
    {n:36,id:"h36d",hid:"h36",tag:"6:00 PM",type:"prayer",name:"Maghrib Prayer",hint:"Pray with family if possible — full salah. 6:00–7:00 PM window.",work:[]},
    {n:29,id:"h29b",hid:"h29",tag:"6:20 PM",type:"family",name:"Love Bomb — Family",hint:"Hug your family. Express genuine love.",work:[]},
    {n:13,id:"h13c",hid:"h13",tag:"6:30 PM",type:"family",name:"Eat Healthy — Dinner",hint:"Balanced dinner. No phone at table.",work:[]},
    {n:8, id:"h8b", hid:"h8", tag:"6:45 PM",type:"family",name:"Mindful Moments — Family",hint:"Taste your food, hear your family. 100% present.",work:[]},
    {n:14,id:"h14b",hid:"h14",tag:"7:05 PM",type:"family",name:"Touch — Human Connection",hint:"Hug, hold hands — human warmth matters.",work:[]},
    {n:39,id:"h39b",hid:"h39",tag:"7:15 PM",type:"prayer",name:"Good Deed — Execute",hint:"Do the unseen, unsaid good act you planned at Fajr.",work:[]},
  ]},
  {id:"s12",icon:"📚",title:"Relaxation + Growth",time:"7:30 – 8:00 PM",type:"rest",habits:[
    {n:40,id:"h40",hid:"h40",tag:"7:30 PM",type:"rest",name:"Layer Subtraction (EGO:6)",hint:"BE SOULFUL. Strip ego. Stay humble. Reflect.",work:[]},
    {n:26,id:"h26b",hid:"h26",tag:"7:40 PM",type:"rest",name:"Read 10+ Minutes — Evening",hint:"Wind down with a book. Screens off if possible.",work:[]},
    {n:27,id:"h27b",hid:"h27",tag:"7:55 PM",type:"habit",name:"Micro-Learn — Evening Review",hint:"Write 1 key insight you learned today.",work:[
      {id:"w27b",tx:"Write 1 lesson learned from today's CEO decisions"},
    ]},
  ]},
  {id:"s13",icon:"🌙",title:"Isha + Night Review + Sleep",time:"8:00 – 10:00 PM",type:"prayer",habits:[
    {n:36,id:"h36e",hid:"h36",tag:"8:00 PM",type:"prayer",name:"Isha Prayer",hint:"Full salah — close the day with the Almighty. 8:00–9:00 PM window.",work:[]},
    {n:37,id:"h37b",hid:"h37",tag:"8:20 PM",type:"prayer",name:"Evening Dhikr",hint:"Evening adhkar — reflection and gratitude.",work:[]},
    {n:38,id:"h38b",hid:"h38",tag:"8:30 PM",type:"prayer",name:"Sacred Reading — Night",hint:"5 min Quran before sleep — end with the Almighty.",work:[]},
    {n:42,id:"h42",hid:"h42",tag:"9:00 PM",type:"habit",name:"Happiness Score",hint:"Rate your day 1–10. Log in your Life Clock tracker.",work:[
      {id:"w42a",tx:"Did I hit my Big 3 today? What moved the needle?"},
      {id:"w42b",tx:"Write tomorrow's Top 3 Big Moves — Next-Day Blueprint"},
      {id:"w42c",tx:"Log Happiness Score 1–10 in paper tracker"},
    ]},
    {n:35,id:"h35b",hid:"h35",tag:"9:50 PM",type:"habit",name:"Digital Detox — Phone Out",hint:"Phone out of bedroom. Screen-free sleep.",work:[]},
    {n:12,id:"h12",hid:"h12",tag:"10:00 PM",type:"rest",name:"Sleep — 7 Hours",hint:"Lights out 10 PM. Wake 5 AM. Night = tomorrow's foundation.",work:[]},
  ]},
];

var UNIQUE_IDS=["h1","h2","h3","h4","h5","h6","h7","h8","h9","h10","h11","h12","h13","h14","h15","h16","h17","h18","h19","h20","h21","h22","h23","h24","h25","h26","h27","h28","h29","h30","h31","h32","h33","h34","h35","h36","h37","h38","h39","h40","h41","h42"];

// ════════════ PERSISTENT STORAGE ════════════
// Keys: lc7_h_d{day} = habit states, lc7_w_d{day} = work tasks
var day=1,remOn=false,hSt={},wSt={},lastRem=null,popHid=null,snoozeT=null;
var HPFX="lc7_h_d",WPFX="lc7_w_d";

function load(){
  try{hSt=JSON.parse(localStorage.getItem(HPFX+day)||"{}");wSt=JSON.parse(localStorage.getItem(WPFX+day))||{};}
  catch(e){hSt={};wSt={};}
  // ensure objects
  if(typeof hSt!=="object"||!hSt)hSt={};
  if(typeof wSt!=="object"||!wSt)wSt={};
}
function save(){
  try{localStorage.setItem(HPFX+day,JSON.stringify(hSt));localStorage.setItem(WPFX+day,JSON.stringify(wSt));}
  catch(e){showToast("⚠ Storage full","warn");}
}
function loadDay(d){
  try{return JSON.parse(localStorage.getItem(HPFX+d)||"{}");}
  catch(e){return {};}
}
function doneCount(){return UNIQUE_IDS.filter(function(id){return hSt[id];}).length;}
function dayPct(d){
  var h=loadDay(d);
  return Math.round(UNIQUE_IDS.filter(function(id){return h[id];}).length/42*100);
}

// ════════════ RENDER ════════════
function renderAll(){renderDays();renderNav();renderMain();renderStreak();updateProg();highlightNow();}

function renderDays(){
  var g=document.getElementById("dayGrid");g.innerHTML="";
  for(var d=1;d<=10;d++){
    var b=document.createElement("button");
    b.className="d-btn"+(d===day?" active":"");
    b.innerHTML=d+'<span class="d-dot"></span>';
    var p=dayPct(d);
    if(p>0)b.classList.add("has-p");
    (function(dd){b.onclick=function(){day=dd;load();renderAll();closeSidebar();};})(d);
    g.appendChild(b);
  }
}

function renderNav(){
  var nav=document.getElementById("sbNav");nav.innerHTML="";
  BLOCKS.forEach(function(blk){
    var uids=[];blk.habits.forEach(function(h){if(UNIQUE_IDS.indexOf(h.hid)>-1&&uids.indexOf(h.hid)<0)uids.push(h.hid);});
    var done=uids.filter(function(id){return hSt[id];}).length;
    var pct=uids.length?Math.round(done/uids.length*100):0;
    var a=document.createElement("a");
    a.className="n-item";a.href="#"+blk.id;
    a.innerHTML='<span class="n-icon">'+blk.icon+'</span><div class="n-info"><span class="n-name">'+blk.title+'</span><span class="n-time">'+blk.time+'</span></div><div class="n-bar"><div class="n-fill" style="width:'+pct+'%"></div></div>';
    a.onclick=function(){closeSidebar();};
    nav.appendChild(a);
  });
}

function renderMain(){
  var c=document.getElementById("mainCon");c.innerHTML="";
  BLOCKS.forEach(function(blk){
    var sec=document.createElement("div");sec.className="phase-sec";sec.id=blk.id;
    var uids=[];blk.habits.forEach(function(h){if(UNIQUE_IDS.indexOf(h.hid)>-1&&uids.indexOf(h.hid)<0)uids.push(h.hid);});
    var done=uids.filter(function(id){return hSt[id];}).length;
    sec.innerHTML='<div class="ph-hdr"><span class="ph-icon">'+blk.icon+'</span><div class="ph-info"><div class="ph-title">'+blk.title+'</div><div class="ph-time-lbl">'+blk.time+'</div></div><span class="ph-cnt" id="pc-'+blk.id+'">'+done+'/'+uids.length+'</span></div><div class="ph-line"></div>';

    blk.habits.forEach(function(h){
      var isDone=!!hSt[h.hid];
      var hasWork=h.work&&h.work.length>0;
      var card=document.createElement("div");
      card.className="hcard"+(isDone?" done":"");
      card.dataset.type=h.type;
      card.id="hc-"+h.id;
      card.dataset.hnum=h.n;
      card.dataset.hname=h.name.toLowerCase();

      var workHTML="";
      if(hasWork){
        var rows=h.work.map(function(w){
          var wd=!!wSt[w.id];
          return'<div class="w-row'+(wd?" done":"")+'" id="wr-'+w.id+'" data-wid="'+w.id+'" data-hid="'+h.hid+'"><div class="w-cb">'+(wd?"✓":"")+'</div><span class="w-lbl">'+w.tx+'</span></div>';
        }).join("");
        workHTML='<div class="hc-expand" id="he-'+h.id+'"><div class="hc-exp-inner"><div class="exp-lbl">⚡ CEO Work Tasks</div>'+rows+'</div></div>';
      }

      card.innerHTML=
        '<div class="hc-row" data-hid="'+h.hid+'" data-rid="'+h.id+'" data-hw="'+(hasWork?1:0)+'">'+
          '<div class="hc-left">'+
            '<span class="hc-t">'+h.tag+'</span>'+
            '<span class="hc-num">#'+h.n+'</span>'+
          '</div>'+
          '<div class="hc-mid">'+
            '<div class="hc-name">'+h.name+'</div>'+
            '<div class="hc-hint">'+h.hint+'</div>'+
            (hasWork?'<span class="hc-work-tag">+ work tasks</span>':'')+
          '</div>'+
          '<div class="hc-chk"><div class="chk">'+(isDone?"✓":"")+'</div></div>'+
        '</div>'+workHTML;

      sec.appendChild(card);
    });
    c.appendChild(sec);
  });

  document.getElementById("mainCon").addEventListener("click",function(e){
    var wr=e.target.closest(".w-row");
    if(wr&&wr.dataset.wid){e.stopPropagation();toggleWork(wr.dataset.wid,wr.dataset.hid,wr);return;}
    var row=e.target.closest(".hc-row");
    if(!row||!row.dataset.hid)return;
    if(e.target.closest(".hc-chk")){
      toggleHabit(row.dataset.hid);
    } else if(row.dataset.hw==="1"){
      var exp=document.getElementById("he-"+row.dataset.rid);
      if(exp)exp.classList.toggle("open");
    } else {
      toggleHabit(row.dataset.hid);
    }
  });
}

function renderStreak(){
  var row=document.getElementById("streakRow");row.innerHTML="";
  for(var d=1;d<=10;d++){
    var pip=document.createElement("div");pip.className="s-pip";pip.textContent=d;
    var p=dayPct(d);
    if(p>=100)pip.classList.add("full");
    else if(p>0)pip.classList.add("partial");
    row.appendChild(pip);
  }
}

function updateProg(){
  var done=doneCount(),total=42;
  var pct=Math.round(done/total*100);
  document.getElementById("ringPct").textContent=pct+"%";
  document.getElementById("doneC").textContent=done;
  document.getElementById("totalC").textContent=total;
  document.getElementById("tbDone").textContent=done;
  document.getElementById("tbLeft").textContent=total-done;
  document.getElementById("tbDay").textContent="D"+day;
  document.getElementById("gFill").style.width=pct+"%";
  // circumference 2*pi*41 ≈ 258
  document.getElementById("ringFg").style.strokeDashoffset=258-(pct/100)*258;
  document.getElementById("congrats").classList.toggle("show",done===total);
  BLOCKS.forEach(function(blk){
    var el=document.getElementById("pc-"+blk.id);
    if(!el)return;
    var uids=[];blk.habits.forEach(function(h){if(UNIQUE_IDS.indexOf(h.hid)>-1&&uids.indexOf(h.hid)<0)uids.push(h.hid);});
    var dn=uids.filter(function(id){return hSt[id];}).length;
    el.textContent=dn+"/"+uids.length;
  });
}

// ════════════ TOGGLE ════════════
function toggleHabit(hid){
  var was=!!hSt[hid];hSt[hid]=!was;save();
  BLOCKS.forEach(function(blk){blk.habits.forEach(function(h){
    if(h.hid===hid){
      var card=document.getElementById("hc-"+h.id);
      if(card){card.classList.toggle("done",!was);var c=card.querySelector(".chk");if(c)c.textContent=!was?"✓":"";}
    }
  });});
  updateProg();renderNav();renderStreak();
  if(!was){
    var nm="";BLOCKS.forEach(function(b){b.habits.forEach(function(h){if(h.hid===hid&&!nm)nm=h.name;});});
    showToast("✓ "+nm.substring(0,32));
  }
}

function toggleWork(wid,hid,el){
  var was=!!wSt[wid];wSt[wid]=!was;
  el.classList.toggle("done",!was);
  var cb=el.querySelector(".w-cb");if(cb)cb.textContent=!was?"✓":"";
  save();
  var allDone=true;
  BLOCKS.forEach(function(b){b.habits.forEach(function(h){
    if(h.hid===hid&&h.work&&h.work.length)h.work.forEach(function(w){if(!wSt[w.id])allDone=false;});
  });});
  if(allDone&&!hSt[hid])toggleHabit(hid);
}

// ════════════ SEARCH ════════════
function doSearch(q){
  q=q.trim().toLowerCase();
  document.getElementById("searchClear").classList.toggle("show",q.length>0);
  var all=document.querySelectorAll(".hcard");
  all.forEach(function(card){
    if(!q){card.classList.remove("search-match","search-hidden");return;}
    var num=card.dataset.hnum||"";
    var nm=card.dataset.hname||"";
    var match=num===q||nm.indexOf(q)>-1||("#"+num).indexOf(q)>-1;
    card.classList.toggle("search-match",match);
    card.classList.toggle("search-hidden",!match);
  });
}

// ════════════ CLOCK ════════════
function toMin(s){
  if(!s)return -1;
  var m=s.match(/(\d+):(\d+)\s*(AM|PM)/i);if(!m)return -1;
  var h=parseInt(m[1]),mn=parseInt(m[2]),ap=m[3].toUpperCase();
  if(ap==="PM"&&h!==12)h+=12;if(ap==="AM"&&h===12)h=0;
  return h*60+mn;
}
function nowMin(){var n=new Date();return n.getHours()*60+n.getMinutes();}

function highlightNow(){
  var now=nowMin();var cur=null;
  BLOCKS.forEach(function(blk){blk.habits.forEach(function(h){
    var card=document.getElementById("hc-"+h.id);
    var hm=toMin(h.tag);
    var act=hm>0&&now>=hm&&now<hm+25&&!hSt[h.hid];
    if(card)card.classList.toggle("now",act);
    if(act&&!cur)cur=h;
  });});
  var banner=document.getElementById("curBanner");
  if(cur){banner.classList.add("show");document.getElementById("cbTx").textContent="#"+cur.n+" "+cur.name;}
  else banner.classList.remove("show");
  if(remOn&&cur&&cur.id!==lastRem&&!hSt[cur.hid]){lastRem=cur.id;popHid=cur;showPopup(cur);}
}

function tick(){
  var n=new Date();function p(x){return x.toString().padStart(2,"0");}
  document.getElementById("tbClk").textContent=p(n.getHours())+":"+p(n.getMinutes())+":"+p(n.getSeconds());
  document.getElementById("tbDt").textContent="March 2026 — Day "+day;
}

// ════════════ REPORT ════════════
function showReport(){
  var panel=document.getElementById("reportPanel");
  panel.classList.add("show");
  var grid=document.getElementById("rpGrid");grid.innerHTML="";
  var total=0,days=0;
  for(var d=1;d<=10;d++){
    var p=dayPct(d);
    if(p>0){total+=p;days++;}
    var div=document.createElement("div");div.className="rp-day";
    var cls=p>=80?"great":p>=40?"ok":"";
    div.innerHTML='<div class="rp-dn">Day '+d+'</div><div class="rp-pct '+cls+'">'+p+'%</div>';
    grid.appendChild(div);
  }
  var avg=days?Math.round(total/days):0;
  var best=0,bestD=0;
  for(var d=1;d<=10;d++){var p2=dayPct(d);if(p2>best){best=p2;bestD=d;}}
  var sum=document.getElementById("rpSummary");
  var msg="";
  if(days===0)msg="No tracking data yet. Start Day 1 and come back!";
  else{
    msg="📅 Days tracked: "+days+"/10\n";
    msg+="📊 Average completion: "+avg+"%\n";
    if(bestD)msg+="🏆 Best day: Day "+bestD+" ("+best+"%)\n";
    if(avg>=80)msg+="\n🔥 Excellent! You are living the Life Clock. Keep this standard.";
    else if(avg>=50)msg+="\n⚡ Good progress. Push harder on the morning blocks — they set the tone.";
    else msg+="\n💡 Focus on consistency over perfection. Start with the 5 prayers and 3 identity habits.";
  }
  sum.style.whiteSpace="pre-line";sum.textContent=msg;
  setTimeout(function(){panel.scrollIntoView({behavior:"smooth"});},100);
}

// ════════════ MENTOR AGENT ════════════
var mentorHistory=[];
var MENTOR_KEY="lc7_mentor";

function loadMentorHistory(){
  try{mentorHistory=JSON.parse(localStorage.getItem(MENTOR_KEY)||"[]");}
  catch(e){mentorHistory=[];}
}
function saveMentorHistory(){
  try{localStorage.setItem(MENTOR_KEY,JSON.stringify(mentorHistory.slice(-40)));}
  catch(e){}
}

function openMentor(){
  loadMentorHistory();
  var overlay=document.getElementById("mentorOverlay");
  overlay.classList.add("show");
  var msgs=document.getElementById("mentorMsgs");msgs.innerHTML="";
  if(mentorHistory.length===0){
    // greeting with progress context
    var done=doneCount();
    var greeting="As-salamu alaykum! I'm your Coach Kanchon AI Mentor. 🧠\n\nToday (Day "+day+") you've completed "+done+"/42 habits ("+Math.round(done/42*100)+"%).\n\n";
    if(done===0)greeting+="You haven't started tracking today yet. Let's begin — tap any habit to mark it done.\n\nWhat's your biggest challenge right now?";
    else if(done<15)greeting+="You've made a start. Focus next on completing your physical power block and prayers. What's holding you back?";
    else if(done<30)greeting+="Good progress! You're halfway. Which block do you want to push harder on?";
    else greeting+="Strong day! You're "+done+" habits in. Let's make sure you close the day strong. Any blockers?";
    addMentorMsg("bot",greeting);
    mentorHistory.push({role:"bot",text:greeting});
    saveMentorHistory();
  } else {
    mentorHistory.forEach(function(m){addMentorMsg(m.role,m.text);});
  }
  setTimeout(function(){msgs.scrollTop=msgs.scrollHeight;},100);
}

function addMentorMsg(role,text){
  var msgs=document.getElementById("mentorMsgs");
  var div=document.createElement("div");
  div.className="msg "+role;
  div.textContent=text;
  msgs.appendChild(div);
  msgs.scrollTop=msgs.scrollHeight;
}

function sendMentor(){
  var inp=document.getElementById("mentorInput");
  var txt=inp.value.trim();if(!txt)return;
  inp.value="";
  addMentorMsg("user",txt);
  mentorHistory.push({role:"user",text:txt});

  // typing indicator
  var msgs=document.getElementById("mentorMsgs");
  var typing=document.createElement("div");
  typing.className="msg bot typing";typing.textContent="Coach is thinking…";
  msgs.appendChild(typing);msgs.scrollTop=msgs.scrollHeight;

  // build progress context
  var done=doneCount();
  var prayerDone=["h36","h37","h38"].filter(function(id){return hSt[id];}).length;
  var workDone=["h17","h18","h19","h20","h21","h22"].filter(function(id){return hSt[id];}).length;
  var phyDone=["h10","h11","h12","h13","h14","h15","h16"].filter(function(id){return hSt[id];}).length;
  var dayPcts=[];for(var d=1;d<=10;d++)dayPcts.push("D"+d+":"+dayPct(d)+"%");

  var systemPrompt="You are Coach Kanchon AI, a strict but caring life mentor for an eCommerce CEO using the Life Clock 42-habit framework. The 10-day focus phase goal is: 'I AM Disciplined' with a primary target of Reach ₹50 daily sales. Be concise, direct, motivating. Use the data to give specific actionable feedback. Don't be generic. Max 120 words per reply.\n\nUser's current data:\n- Today: Day "+day+", "+done+"/42 habits done ("+Math.round(done/42*100)+"%)\n- Prayers done today: "+prayerDone+"/3 (Fajr, Dhikr, Quran)\n- Work habits done: "+workDone+"/6\n- Physical habits done: "+phyDone+"/7\n- 10-day overview: "+dayPcts.join(", ");

  var messages=[{role:"user",content:systemPrompt+"\n\nUser says: "+txt}];

  fetch("https://api.anthropic.com/v1/messages",{
    method:"POST",
    headers:{"Content-Type":"application/json"},
    body:JSON.stringify({
      model:"claude-sonnet-4-20250514",
      max_tokens:200,
      messages:messages
    })
  }).then(function(r){return r.json();}).then(function(data){
    typing.remove();
    var reply="";
    if(data.content&&data.content[0]&&data.content[0].text){
      reply=data.content[0].text;
    } else if(data.error){
      reply="⚠ Mentor offline right now. Your data is saved. Keep tracking — I'll be back!";
    }
    addMentorMsg("bot",reply);
    mentorHistory.push({role:"bot",text:reply});
    saveMentorHistory();
  }).catch(function(){
    typing.remove();
    // fallback offline mentor
    var fallback=getOfflineMentorReply(txt,done,prayerDone);
    addMentorMsg("bot",fallback);
    mentorHistory.push({role:"bot",text:fallback});
    saveMentorHistory();
  });
}

function getOfflineMentorReply(q,done,prayers){
  q=q.toLowerCase();
  if(q.indexOf("prayer")>-1||q.indexOf("fajr")>-1)
    return "Prayer is the foundation. If you miss Fajr, the whole day tilts. Set your alarm now for 5:00 AM. No negotiation with Allah's time. ✅";
  if(q.indexOf("sales")>-1||q.indexOf("revenue")>-1||q.indexOf("ads")>-1)
    return "Check your ROAS daily. Your Big 3 Moves drive revenue — are they done? Scale what's working. Cut what isn't. Numbers don't lie. 📊";
  if(q.indexOf("lazy")>-1||q.indexOf("motivation")>-1||q.indexOf("tired")>-1)
    return "Say it now: I AM Disciplined. Motivation is a guest — discipline is the host. You have "+done+"/42 done. What's your next habit? Go. ⚡";
  if(q.indexOf("sleep")>-1)
    return "10 PM lights out. 5 AM wake up. That's 7 hours — your CEO superpower. Everything else follows from this. Protect your sleep like your revenue.";
  if(done>=35)
    return "Outstanding! "+done+"/42 habits — you're living the Life Clock. Finish strong. Log your Happiness Score tonight. 🏆";
  if(done<10)
    return "Only "+done+" habits done. Start with the 5 prayers — they anchor everything. Then identity block. Then physical. One by one. You've got this. 💪";
  return "You have "+done+"/42 habits done today. Focus on what's undone. The Life Clock doesn't wait. Every habit is a vote for the CEO you're becoming. 🧠";
}

// ════════════ REMINDERS ════════════
function toggleRem(){
  remOn=!remOn;
  document.getElementById("remInd").classList.toggle("on",remOn);
  showToast(remOn?"🔔 Reminders ON":"🔕 Reminders OFF","info");
  if(remOn&&"Notification"in window&&Notification.permission==="default")Notification.requestPermission();
}
function showPopup(h){
  var icons={prayer:"🕌",work:"💼",rest:"😴",habit:"⚡",family:"❤️"};
  document.getElementById("ppIcon").textContent=icons[h.type]||"⏰";
  document.getElementById("ppTitle").textContent="#"+h.n+" — "+h.name;
  document.getElementById("ppTime").textContent=h.tag;
  document.getElementById("ppDesc").textContent=h.hint;
  document.getElementById("popup").classList.add("show");
  document.getElementById("overlay").classList.add("show");
  if("Notification"in window&&Notification.permission==="granted")
    new Notification("⏰ Life Clock #"+h.n,{body:h.name+" · "+h.tag});
}
function markFromPopup(){if(popHid)toggleHabit(popHid.hid);closePopup();}
function closePopup(){
  document.getElementById("popup").classList.remove("show");
  document.getElementById("overlay").classList.remove("show");
  if(snoozeT)clearTimeout(snoozeT);
  if(remOn&&popHid)(function(hh){
    snoozeT=setTimeout(function(){if(remOn&&!hSt[hh.hid])showPopup(hh);},5*60*1000);
  })(popHid);
}

function showToast(msg,type){
  var t=document.getElementById("toast");t.textContent=msg;t.className="toast show"+(type?" "+type:"");
  clearTimeout(t._t);t._t=setTimeout(function(){t.classList.remove("show");},2800);
}
function resetDay(){if(!confirm("Reset Day "+day+"? This cannot be undone."))return;hSt={};wSt={};save();lastRem=null;renderAll();showToast("↺ Day "+day+" reset","warn");}
function closeSidebar(){document.getElementById("sidebar").classList.remove("open");document.getElementById("bdrop").classList.remove("show");}

// ════════════ EVENTS ════════════
document.getElementById("menuBtn").onclick=function(){document.getElementById("sidebar").classList.toggle("open");document.getElementById("bdrop").classList.toggle("show");};
document.getElementById("bdrop").onclick=closeSidebar;
document.getElementById("remTog").onclick=toggleRem;
document.getElementById("rstBtn").onclick=resetDay;
document.getElementById("ppOk").onclick=markFromPopup;
document.getElementById("ppSkip").onclick=closePopup;
document.getElementById("overlay").onclick=closePopup;
document.getElementById("reportBtn").onclick=function(){showReport();closeSidebar();};
document.getElementById("rpClose").onclick=function(){document.getElementById("reportPanel").classList.remove("show");};
document.getElementById("mentorBtn").onclick=function(){openMentor();closeSidebar();};
document.getElementById("mentorClose").onclick=function(){document.getElementById("mentorOverlay").classList.remove("show");};
document.getElementById("mentorSend").onclick=sendMentor;
document.getElementById("mentorInput").onkeydown=function(e){if(e.key==="Enter")sendMentor();};
document.getElementById("mentorOverlay").onclick=function(e){if(e.target===this)this.classList.remove("show");};
document.getElementById("searchInp").oninput=function(){doSearch(this.value);};
document.getElementById("searchClear").onclick=function(){document.getElementById("searchInp").value="";doSearch("");};

// ════════════ TRACK REMINDER (every 2 hrs) ════════════
function scheduleTrackReminder(){
  setInterval(function(){
    var done=doneCount();
    if(done<42&&remOn){
      showToast("🧠 Track your habits! "+done+"/42 done","info");
    }
  },2*60*60*1000); // every 2 hours
}

// ════════════ BOOT ════════════
load();renderAll();
setInterval(tick,1000);
setInterval(highlightNow,60000);
tick();
scheduleTrackReminder();
</script>

</body>
</html>

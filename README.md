<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080912">
<title>HACKER CENTER — Cyber Intelligence Forum</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@500;600;700;800;900&family=DM+Mono:wght@400;500&family=Manrope:wght@400;500;600;700;800&display=swap');
:root{--bg:#050505;--panel:#101321;--panel2:#151a2b;--line:#282b42;--text:#f3f1ff;--muted:#9696b1;--purple:#a56cff;--blue:#557cff;--cyan:#76d7ff;--gold:#f2c66d;--green:#7ce0b0;--red:#ff7f91;--shadow:0 18px 50px #0008}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:#050505;color:var(--text);font-family:Manrope,system-ui,sans-serif;min-height:100vh}button,input,textarea,select{font:inherit}button{cursor:pointer}a{color:inherit;text-decoration:none}.shell{max-width:1480px;margin:auto;padding:22px 26px 70px}.topline{height:3px;background:linear-gradient(90deg,var(--blue),var(--purple),#e0a9ff);border-radius:4px;margin-bottom:20px}.topbar{display:flex;align-items:center;justify-content:space-between;gap:20px;padding:10px 2px 22px}.brand{display:flex;align-items:center;gap:12px}.brand img{width:38px;height:38px;object-fit:contain}.brand-mark{width:40px;height:40px;border:1px solid #7860bc;border-radius:13px;display:grid;place-items:center;background:linear-gradient(145deg,#202d64,#36194f);font:900 20px 'Barlow Condensed';color:#d7c6ff;box-shadow:inset 0 1px #ffffff25,0 8px 24px #5037a633}.brand-name{font:800 23px 'Barlow Condensed';letter-spacing:1.4px}.brand-name span{color:#b58aff}.brand-sub{font:10px 'DM Mono';letter-spacing:2px;color:var(--muted);margin-top:2px}.top-actions{display:flex;align-items:center;gap:10px}.pill{border:1px solid var(--line);border-radius:999px;padding:9px 13px;background:#101321;color:#c9c5df;font:11px 'DM Mono';display:flex;align-items:center;gap:8px}.live-dot{width:7px;height:7px;border-radius:50%;background:#7ce0b0;box-shadow:0 0 12px #7ce0b0}.avatar-mini{width:31px;height:31px;border-radius:50%;background:linear-gradient(135deg,#4568d7,#a56cff);display:grid;place-items:center;font-weight:800;font-size:11px}.hero{position:relative;overflow:hidden;border:1px solid #48416e;border-radius:18px;padding:28px 30px 26px;background:linear-gradient(112deg,#151e42 0%,#211b42 52%,#25143a 100%);box-shadow:var(--shadow),inset 0 1px #ffffff20;min-height:175px}.hero:after{content:"";position:absolute;width:380px;height:280px;right:4%;top:-130px;border:1px solid #ffffff13;border-radius:50%;box-shadow:0 0 0 28px #ffffff08,0 0 0 58px #ffffff05;transform:rotate(-20deg)}.hero-kicker{font:11px 'DM Mono';letter-spacing:2.5px;color:#b7b4e4}.hero h1{font:900 clamp(36px,6vw,66px)/.92 'Barlow Condensed';letter-spacing:1px;margin:13px 0 10px;text-transform:uppercase}.hero h1 span{background:linear-gradient(90deg,#8bb5ff,#c49aff 70%,#f1c4ff);-webkit-background-clip:text;background-clip:text;color:transparent}.hero p{color:#c4c1dc;font-size:12px;max-width:570px;line-height:1.7;margin:0}.hero-art{position:absolute;right:5%;top:22px;width:135px;height:130px;display:grid;place-items:center;opacity:.92}.hero-art img{max-width:100%;max-height:100%;object-fit:contain;filter:drop-shadow(0 14px 20px #8b5cff55)}.hero-art .fallback{font:900 78px 'Barlow Condensed';color:#b58aff;transform:rotate(-9deg);text-shadow:5px 7px 0 #37276d}.balance-row{display:grid;grid-template-columns:minmax(0,1fr) auto;gap:14px;margin:16px 0}.balance{border:1px solid #35334f;border-radius:14px;background:linear-gradient(115deg,#111525,#15172a);padding:15px 18px;display:flex;align-items:center;justify-content:space-between;gap:15px}.balance-label{font:10px 'DM Mono';letter-spacing:1.7px;color:var(--muted)}.balance-value{font:700 22px 'DM Mono';margin-top:5px;letter-spacing:.5px}.balance-value small{font-size:12px;color:#b5a6e7}.balance-meta{font:10px 'DM Mono';color:var(--muted);margin-top:4px}.icon-btn{width:36px;height:36px;border:1px solid #383650;border-radius:10px;background:#1b1c31;color:#cfc7f5}.id-chip{border:1px dashed #51466f;border-radius:14px;padding:12px 16px;display:flex;flex-direction:column;justify-content:center;min-width:190px;background:#151326}.id-chip span{font:9px 'DM Mono';color:var(--muted);letter-spacing:1px}.id-chip strong{font:12px 'DM Mono';color:#d8c5ff;margin-top:6px}.ticker{height:35px;overflow:hidden;display:flex;align-items:center;background:linear-gradient(90deg,#49308b,#2b235f,#4b2c84);border:1px solid #7252ad;transform:skewX(-5deg);margin:14px 0 18px;box-shadow:0 8px 20px #27134b55}.ticker-track{white-space:nowrap;display:inline-block;animation:marquee 24s linear infinite;font:800 12px 'Barlow Condensed';letter-spacing:2.3px;color:#f4eaff}.ticker-track span{padding:0 34px}@keyframes marquee{to{transform:translateX(-50%)}}.banner-main{height:155px;border:1px solid #45416c;border-radius:14px;overflow:hidden;background:linear-gradient(100deg,#1a2750,#2c1d51 60%,#4b276c);position:relative;display:flex;align-items:center;padding:24px 28px;margin-bottom:12px}.banner-main img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;opacity:.82}.banner-main:after{content:"";position:absolute;inset:0;background:linear-gradient(90deg,#0d1128d9,#15112c70 60%,transparent)}.banner-copy{position:relative;z-index:1}.banner-copy small{font:10px 'DM Mono';letter-spacing:2px;color:#c5b6f1}.banner-copy h2{font:800 32px 'Barlow Condensed';margin:8px 0 4px}.banner-copy p{font-size:11px;color:#d1cbe7;margin:0}.banner-pair{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:20px}.banner-small{height:90px;border-radius:12px;border:1px solid #34334e;overflow:hidden;position:relative;background:linear-gradient(110deg,#171a32,#292044);display:flex;align-items:center;padding:15px 18px}.banner-small img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;opacity:.62}.banner-small:after{content:"";position:absolute;inset:0;background:linear-gradient(90deg,#101323dd,#18142c70)}.banner-small div{position:relative;z-index:1}.banner-small b{font:700 17px 'Barlow Condensed';letter-spacing:.5px}.banner-small span{display:block;color:#aaa6c5;font:9px 'DM Mono';margin-top:5px}.layout{display:grid;grid-template-columns:220px minmax(0,1fr);gap:18px;align-items:start}.sidebar{position:sticky;top:12px;border:1px solid var(--line);border-radius:15px;background:#0e1120;padding:12px;box-shadow:var(--shadow)}.nav-label{font:9px 'DM Mono';letter-spacing:2px;color:#74748e;padding:10px 10px 7px}.nav-btn{width:100%;border:0;background:transparent;color:#aaa9c4;padding:11px 10px;border-radius:9px;display:flex;align-items:center;gap:11px;text-align:left;font-size:11px;font-weight:700;transition:.2s}.nav-btn svg{width:17px;height:17px;stroke:currentColor;fill:none;stroke-width:1.8}.nav-btn:hover,.nav-btn.active{background:linear-gradient(100deg,#30245a,#1c2445);color:#eee8ff}.nav-btn.active{box-shadow:inset 2px 0 #ad82ff}.nav-count{margin-left:auto;font:9px 'DM Mono';color:#aaa1d2}.side-user{border-top:1px solid var(--line);margin-top:12px;padding:14px 8px 5px;display:flex;gap:9px;align-items:center}.side-user img{width:30px;height:30px;object-fit:contain}.side-user b{font-size:10px;display:block}.side-user small{font:9px 'DM Mono';color:var(--muted)}.content{min-width:0}.welcome{display:flex;align-items:center;justify-content:space-between;gap:14px;padding:15px 18px;border:1px solid #39365e;border-left:3px solid #a77cff;border-radius:12px;background:linear-gradient(100deg,#171c3b,#111525);margin-bottom:17px}.welcome h3{font-size:14px;margin:0 0 4px}.welcome h3 span{color:#c09cff}.welcome p{font-size:10px;color:#aaa8c1;margin:0}.welcome-meta{font:9px 'DM Mono';color:#aaa8c1;text-align:right}.section-head{display:flex;justify-content:space-between;align-items:end;gap:12px;margin:22px 0 12px}.section-head h2{font:800 24px 'Barlow Condensed';margin:0;letter-spacing:.5px}.section-head p{font-size:10px;color:var(--muted);margin:4px 0 0}.section-tag{font:9px 'DM Mono';color:#b99aff;border:1px solid #514070;padding:6px 9px;border-radius:7px}.notice-list{display:grid;gap:8px}.notice{display:flex;gap:12px;align-items:center;padding:12px 14px;border:1px solid #24283a;border-radius:10px;background:#10131d}.notice-icon{width:29px;height:29px;border-radius:8px;background:#292047;color:#c4a2ff;display:grid;place-items:center;flex-shrink:0}.notice-icon svg{width:15px;height:15px;stroke:currentColor;fill:none;stroke-width:1.8}.notice b{font-size:11px}.notice p{font-size:9px;color:#9998b0;margin:3px 0 0}.notice p em{color:#c09aff;font-style:normal}.category-grid{display:grid;grid-template-columns:1fr 1fr;gap:9px}.category{padding:14px;border:1px solid #282c40;background:linear-gradient(120deg,#111521,#10121b);border-radius:11px;display:flex;gap:12px;align-items:center;cursor:pointer;transition:.2s}.category:hover{border-color:#7156a4;transform:translateY(-2px)}.category-icon{width:36px;height:36px;border-radius:10px;background:#242044;color:#b999ff;display:grid;place-items:center;flex-shrink:0}.category-icon svg{width:19px;height:19px;stroke:currentColor;fill:none;stroke-width:1.7}.category b{font-size:11px}.category p{font-size:9px;color:#9695ad;margin:4px 0 0;line-height:1.4}.category small{display:block;color:#a88ce7;font:9px 'DM Mono';margin-top:5px}.page{display:none}.page.active{display:block}.toolbar{display:flex;gap:9px;align-items:center;margin:13px 0}.search{flex:1;min-width:0;background:#101321;border:1px solid #30334a;border-radius:9px;color:white;padding:11px 13px;font-size:11px;outline:none}.search:focus,input:focus,textarea:focus,select:focus{border-color:#8e6ad1!important;box-shadow:0 0 0 3px #9a70e51b}.action{border:1px solid #5b4b85;background:linear-gradient(110deg,#4a347e,#273b72);color:white;border-radius:9px;padding:10px 14px;font-size:10px;font-weight:800}.action.secondary{background:#171a2a;border-color:#34364d;color:#c9c4dc}.post-list{display:grid;gap:12px}.post-card{display:grid;grid-template-columns:156px minmax(0,1fr);border:1px solid #2b2e42;border-radius:13px;overflow:hidden;background:#10131e;box-shadow:0 8px 22px #0003}.post-author{padding:17px 13px;background:#151515;border-right:1px solid #292d43;display:flex;flex-direction:column;align-items:center;text-align:center}.post-avatar{width:52px;height:52px;border-radius:15px;background:linear-gradient(140deg,#4266d0,#8c56c8);display:grid;place-items:center;font:800 17px 'Barlow Condensed';color:white;overflow:hidden}.post-avatar img{width:100%;height:100%;object-fit:cover}.post-author strong{font-size:11px;margin-top:9px;overflow-wrap:anywhere;max-width:100%}.role-badge{display:inline-flex;align-items:center;gap:5px;margin-top:6px;padding:4px 7px;border-radius:5px;background:#32274a;color:#d0b6ff;font:8px 'DM Mono';letter-spacing:.5px}.role-badge.owner{background:#4a381e;color:#ffdc8b;box-shadow:0 0 16px #e7b64b30}.role-badge.moderator{background:#1d3b42;color:#8de3dc}.role-badge.admin{background:#34264c;color:#c7a4ff}.role-badge.member{background:#272c40;color:#b4bad4}.role-emblem{display:block;width:42px;height:42px;object-fit:contain;margin:9px auto 2px;filter:drop-shadow(0 0 8px #d7a94b66)}.post-bio{font-size:9px;line-height:1.5;color:#a5a5b4;text-align:center;margin:7px 0 0;overflow-wrap:anywhere}.post-stats{width:100%;margin-top:12px;border-top:1px solid #303349;padding-top:10px;display:grid;gap:5px;text-align:left;font:9px 'DM Mono';color:#9696ad}.post-stats span{display:flex;justify-content:space-between}.post-stats b{color:#ded9f2;font-weight:500}.post-main{padding:16px 18px;min-width:0}.post-meta{display:flex;justify-content:space-between;gap:10px;align-items:center;font:9px 'DM Mono';color:#8889a4}.post-main h3{font:700 19px 'Barlow Condensed';letter-spacing:.3px;margin:10px 0 7px}.post-body{font-size:11px;line-height:1.75;color:#c1bfd2;white-space:pre-wrap;overflow-wrap:anywhere}.post-attachment{margin-top:12px;border:1px solid #34364d;border-radius:9px;overflow:hidden;background:#0b0d17}.post-attachment img{display:block;max-width:100%;max-height:340px;object-fit:contain;margin:auto}.file-attachment{display:flex;align-items:center;gap:10px;padding:12px;color:#d6d0e8;font-size:10px}.file-attachment svg{width:21px;height:21px;stroke:#b89bff;fill:none}.post-foot{display:flex;justify-content:space-between;gap:10px;margin-top:13px;padding-top:10px;border-top:1px solid #292d40;color:#8d8da8;font:9px 'DM Mono'}.post-foot button{background:none;border:0;color:#b69aff;font:inherit}.form-card,.profile-card,.stat-card,.member-card{border:1px solid #2b2e43;border-radius:13px;background:#10131f;padding:17px}.form-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}.field{display:grid;gap:6px;margin-bottom:12px}.field label{font:9px 'DM Mono';letter-spacing:1px;color:#a5a3bd}.field input,.field textarea,.field select{width:100%;border:1px solid #34364d;border-radius:8px;background:#0b0e18;color:#f1edff;padding:11px;font-size:11px;outline:none}.field textarea{min-height:120px;resize:vertical;line-height:1.6}.field small{color:#777991;font-size:9px;line-height:1.5}.file-pick{border:1px dashed #65538e;padding:13px;border-radius:9px;background:#171529;color:#c9b8f0;font-size:10px}.profile-layout{display:grid;grid-template-columns:260px minmax(0,1fr);gap:13px}.profile-card{text-align:center}.profile-photo{width:90px;height:90px;border-radius:23px;margin:4px auto 12px;background:linear-gradient(145deg,#4d6de1,#9b5ac9);display:grid;place-items:center;font:900 30px 'Barlow Condensed';overflow:hidden}.profile-photo img{width:100%;height:100%;object-fit:cover}.profile-card h3{margin:0;font:800 23px 'Barlow Condensed'}.profile-card p{font-size:10px;color:#a6a4bc;line-height:1.6}.profile-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:6px;margin-top:16px}.profile-stats div{background:#191c2c;border-radius:8px;padding:9px 3px}.profile-stats b{display:block;font:700 15px 'DM Mono'}.profile-stats small{font-size:8px;color:#9997b1}.stats-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}.stat-card small{font:9px 'DM Mono';color:#9291ac}.stat-card b{display:block;font:800 25px 'Barlow Condensed';margin-top:7px}.member-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}.member-card{padding:10px;display:flex;align-items:center;gap:9px}.member-avatar{width:30px;height:30px;border-radius:9px;display:grid;place-items:center;background:#25264a;color:#c5b3ff;font-size:10px;font-weight:800}.member-card b{font-size:10px;display:block}.member-card small{font:8px 'DM Mono';color:#9694ae}.gold-text{color:#f5cf79!important;text-shadow:0 0 12px #d4a64b55}.empty{padding:35px;text-align:center;color:#8888a2;border:1px dashed #34364d;border-radius:12px;font-size:11px}.toast{position:fixed;right:20px;bottom:20px;background:#242044;border:1px solid #8065ba;color:#eee7ff;border-radius:10px;padding:12px 16px;font-size:11px;box-shadow:var(--shadow);opacity:0;transform:translateY(12px);transition:.25s;pointer-events:none;z-index:30}.toast.show{opacity:1;transform:translateY(0)}.modal-backdrop{position:fixed;inset:0;background:#03040bdc;display:none;place-items:center;padding:18px;z-index:20}.modal-backdrop.show{display:grid}.modal{width:min(600px,100%);max-height:90vh;overflow:auto;background:#111525;border:1px solid #514575;border-radius:15px;padding:20px;box-shadow:0 25px 90px #000b}.modal-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:15px}.modal-head h3{font:800 23px 'Barlow Condensed';margin:0}.close{background:#24263b;border:1px solid #3b3d54;border-radius:8px;color:white;width:30px;height:30px}.footer{text-align:center;margin-top:26px;padding-top:16px;border-top:1px solid #24273a;color:#6f718b;font:9px 'DM Mono';letter-spacing:1px}
@media(max-width:850px){.shell{padding:14px 13px 50px}.layout{grid-template-columns:1fr}.sidebar{position:static;display:flex;overflow:auto;gap:5px;padding:7px}.nav-label,.side-user{display:none}.nav-btn{width:auto;white-space:nowrap;padding:10px 12px}.nav-count{display:none}.post-card{grid-template-columns:112px minmax(0,1fr)}.post-author{padding:13px 8px}.profile-layout{grid-template-columns:1fr}.hero-art{right:3%;opacity:.5}.welcome-meta{display:none}}
@media(max-width:560px){.top-actions .pill:first-child{display:none}.hero{padding:23px 19px;min-height:160px}.hero-art{width:90px;height:95px;top:32px;right:9px}.hero p{max-width:75%}.balance-row{grid-template-columns:1fr}.id-chip{min-width:0;flex-direction:row;align-items:center;justify-content:space-between}.banner-main{height:125px;padding:17px}.banner-copy h2{font-size:26px}.banner-pair{gap:7px}.banner-small{height:78px;padding:10px}.banner-small b{font-size:14px}.category-grid,.form-grid{grid-template-columns:1fr}.post-card{grid-template-columns:104px minmax(0,1fr);border-radius:10px}.post-author{border-right:1px solid #292d43;border-bottom:0;flex-direction:column;text-align:center;gap:5px;padding:12px 7px;align-items:center}.post-avatar{width:43px;height:43px;border-radius:10px}.post-author strong{margin:3px 0 0;font-size:10px}.post-author .role-badge{margin:3px 0 0;font-size:7px;padding:4px 5px}.post-author .role-emblem{display:block;width:34px;height:34px;margin:6px auto 0}.post-bio{display:block;font-size:8px;line-height:1.35;margin-top:5px}.post-stats{display:grid;margin-top:9px;padding-top:8px;gap:5px;font-size:7px}.post-main{padding:12px 10px}.post-meta{font-size:8px;flex-wrap:wrap}.post-main h3{font-size:18px}.post-body{font-size:11px;line-height:1.7}.stats-grid{grid-template-columns:1fr 1fr}.member-grid{grid-template-columns:1fr 1fr}.welcome{padding:13px}.section-head h2{font-size:22px}}

/* HACKER CENTER — forum refinement */
:root{--bg:#050505}
body{background:#050505!important}
.shell{background:transparent}
.forum-entry{display:flex;align-items:center;justify-content:space-between;gap:18px;margin-top:24px;padding:20px 22px;border:1px solid #30303a;border-left:3px solid #8c69d6;border-radius:8px;background:#101014}
.forum-entry small{font:9px 'DM Mono';letter-spacing:2px;color:#a58be2}
.forum-entry h3{font:700 23px 'Barlow Condensed';margin:7px 0 4px;color:#f1eff8}
.forum-entry p{margin:0;color:#a5a3b2;font-size:11px;line-height:1.6;max-width:560px}
.detail-post .post-card{min-height:430px}
.post-card{background:#101014;border-color:#30303a;border-radius:9px;box-shadow:none}
.post-author{background:#17171c;border-right-color:#30303a}
.post-main{background:#101014}
.post-attachment{background:#080808;border-color:#333}
.post-attachment img{max-height:520px}
.nav-btn svg,.action svg,.notice-icon svg,.category-icon svg{width:18px;height:18px;stroke:currentColor;stroke-width:1.7;stroke-linecap:round;stroke-linejoin:round;fill:none}
@media(max-width:560px){
 .forum-entry{align-items:flex-start;flex-direction:column;padding:16px}
 .detail-post .post-card{min-height:0}
 .post-attachment img{max-height:380px}
}


/* Refined pictogram and forum controls */
.category-icon,.notice-icon{width:48px;height:48px;border-radius:13px;background:#191622;border:1px solid #373044;color:#c7a8ff;display:grid;place-items:center;flex:0 0 auto}
.category-icon svg,.notice-icon svg{width:29px;height:29px;stroke:currentColor;stroke-width:1.45;fill:none;stroke-linecap:round;stroke-linejoin:round}
.category{gap:15px}
.category-icon svg path,.category-icon svg circle{vector-effect:non-scaling-stroke}
.balance-toggle svg{width:19px;height:19px;stroke:currentColor;stroke-width:1.5;fill:none;stroke-linecap:round;stroke-linejoin:round}
.post-body-clamped{display:-webkit-box;-webkit-box-orient:vertical;-webkit-line-clamp:7;overflow:hidden}
.post-body-clamped.expanded{display:block;overflow:visible}
.read-more{margin-top:7px;padding:0;border:0;background:none;color:#c1a0ff;font:9px 'DM Mono';letter-spacing:1px;cursor:pointer}
.read-more span{font-size:13px;margin-left:5px}
.author-menu-wrap{width:100%;position:relative;display:flex;flex-direction:column;align-items:center}
.author-menu-trigger,.profile-more{position:absolute;top:-5px;right:-5px;width:27px;height:27px;border:1px solid #383340;border-radius:7px;background:#1b1a20;color:#bfb6d0;display:grid;place-items:center;cursor:pointer}
.author-menu-trigger svg,.profile-more svg{width:17px;height:17px;stroke:currentColor;fill:currentColor;stroke-width:1.4}
.author-menu{display:none;position:absolute;z-index:8;right:0;top:25px;padding:5px;border:1px solid #454052;border-radius:8px;background:#17161d;box-shadow:0 10px 30px #000b}
.author-menu.visible{display:block}
.author-menu button{white-space:nowrap;border:0;background:transparent;color:#e5ddf4;padding:8px 10px;font:9px 'DM Mono';cursor:pointer}
.author-menu button:hover{background:#2a2436}
.profile-actions{display:flex;align-items:center;gap:8px}
.profile-more{position:static;width:37px;height:37px}
.post-author .role-emblem{display:block;width:66px;height:66px;object-fit:contain;margin:8px auto 3px;padding:0;background:transparent;border:0;border-radius:0;filter:drop-shadow(0 3px 10px #0009)}
.post-body{white-space:pre-wrap;overflow-wrap:anywhere}
#page-threads{min-height:65vh}
#page-threads .post-list{gap:16px}
#page-detail .post-card{width:100%;min-height:540px}
@media(max-width:560px){
 .category-icon,.notice-icon{width:48px;height:48px}
 .category{align-items:center}
 .post-card{grid-template-columns:112px minmax(0,1fr)}
 .post-author{min-width:0}
 .post-main{min-width:0}
 .post-body{font-size:11px;line-height:1.7}
 .post-body-clamped{-webkit-line-clamp:8}
 .post-author .role-emblem{width:56px;height:56px;margin:5px auto 2px}
}


/* V3.1 — separated workspace, refined pictograms and profile controls */
.shell.is-subpage > .hero,
.shell.is-subpage > .balance-row,
.shell.is-subpage > .ticker,
.shell.is-subpage > .banner-main,
.shell.is-subpage > .banner-pair {display:none!important}
.shell.is-subpage .welcome{display:none!important}
.shell.is-subpage .layout{margin-top:18px}
.shell.is-subpage .content{min-height:calc(100vh - 150px)}
.shell.is-subpage #page-threads,
.shell.is-subpage #page-detail,
.shell.is-subpage #page-research,
.shell.is-subpage #page-market,
.shell.is-subpage #page-members,
.shell.is-subpage #page-profile,
.shell.is-subpage #page-compose,
.shell.is-subpage #page-settings{animation:pageEnter .22s ease both}
@keyframes pageEnter{from{opacity:0;transform:translateY(7px)}to{opacity:1;transform:translateY(0)}}

.category-icon,.notice-icon{
  width:50px;height:50px;min-width:50px;border-radius:14px;
  background:linear-gradient(145deg,#211c35,#171724);
  border:1px solid #403451;color:#cbb4ff;
  box-shadow:inset 0 1px #ffffff12,0 7px 18px #0003;
}
.category-icon svg,.notice-icon svg{
  width:27px;height:27px;stroke:currentColor;stroke-width:1.65;
  stroke-linecap:round;stroke-linejoin:round;fill:none;
}
.category:hover .category-icon{border-color:#8263b8;color:#e0ceff;transform:translateY(-1px)}
.category-icon{transition:transform .2s,border-color .2s,color .2s}
.balance-toggle{display:grid;place-items:center}
.balance-toggle svg{width:19px;height:19px;stroke:currentColor;stroke-width:1.65;fill:none}
.nav-btn svg{width:18px;height:18px;stroke-width:1.7}
.post-body-clamped{-webkit-line-clamp:7;line-height:1.75}
.read-more{display:inline-flex;align-items:center;gap:6px;margin-top:9px;padding:7px 0}
.read-more:hover{color:#e0ceff}
.author-menu-trigger,.profile-more{display:grid;place-items:center}
.author-menu-trigger svg,.profile-more svg{width:17px;height:17px;stroke:currentColor;fill:none;stroke-width:1.8;stroke-linecap:round}
.profile-actions{flex-direction:row}
.profile-more{order:0}
.profile-photo{border:1px solid #5a4b7c;box-shadow:inset 0 1px #ffffff22,0 12px 28px #0004}
.profile-photo img{display:block}
.role-emblem{object-fit:contain}
.role-badge{font-weight:600}
#topAvatar{overflow:hidden}
#topAvatar img{width:100%;height:100%;object-fit:cover}
.settings-preview{display:flex;align-items:center;gap:13px;padding:12px;border:1px solid #343149;border-radius:11px;background:#0c0e18;margin:0 0 14px}
.settings-preview-photo{width:54px;height:54px;border-radius:15px;overflow:hidden;display:grid;place-items:center;background:#292044;color:#e5d9ff;font:800 18px 'Barlow Condensed'}
.settings-preview-photo img{width:100%;height:100%;object-fit:cover}
.settings-preview-emblem{width:46px;height:46px;object-fit:contain;margin-left:auto}
.settings-preview small{display:block;color:#9693ad;font:9px 'DM Mono';margin-top:4px}
.profile-menu-note{font:9px 'DM Mono';color:#8f8ba6;margin-top:9px;line-height:1.6}
@media(max-width:560px){
 .shell.is-subpage .layout{margin-top:10px}
 .category-icon,.notice-icon{width:46px;height:46px;min-width:46px}
 .category-icon svg,.notice-icon svg{width:25px;height:25px}
 .post-body-clamped{-webkit-line-clamp:7}
 .settings-preview{gap:9px}
}


/* PATCH 2026.11 — clean role emblem + reliable profile editing */
.post-author .role-badge{display:none!important}
.post-author .role-emblem{width:64px;height:64px;object-fit:contain;display:block;margin:7px auto 3px;background:transparent!important}
.post-author .post-avatar{flex:0 0 auto}
@media(max-width:560px){
 .post-author .role-emblem{width:58px;height:58px;margin:5px auto 2px}
}
</style>
</head>
<body>
<div class="shell">
<div class="topline"></div>
<header class="topbar">
  <div class="brand"><img src="c4.png" alt="C4 mark" onerror="this.style.display='none'"><div class="brand-mark" id="brandFallback">HC</div><div><div class="brand-name">HACKER <span>CENTER</span></div><div class="brand-sub">THE HACKING FORUM</div></div></div>
  <div class="top-actions"><div class="pill"><i class="live-dot"></i> SYSTEM ONLINE</div><div class="avatar-mini" id="topAvatar">LZ</div></div>
</header>
<section class="hero">
  <div class="hero-kicker">INDEPENDENT FORUM COMMUNITY / EST. 2026</div>
  <h1>HACKER <span>CENTER</span></h1>
  <p>Research, share, and strengthen digital infrastructure. A focused space for security notes, responsible disclosure, threat intelligence, and defensive engineering.</p>
  <div class="hero-art"><img src="c4.png" alt="" onerror="this.style.display='none';this.nextElementSibling.style.display='block'"><div class="fallback" style="display:none">HC</div></div>
</section>
<div class="balance-row">
  <div class="balance"><div><div class="balance-label">WALLET / BTC BALANCE</div><div class="balance-value" id="balanceValue">0,002969 <small>BTC</small></div><div class="balance-meta">Read-only payment privat account</div></div><button class="icon-btn balance-toggle" id="toggleBalance" aria-label="Hide balance"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M2.5 12s3.4-6 9.5-6 9.5 6 9.5 6-3.4 6-9.5 6-9.5-6-9.5-6Z"/><circle cx="12" cy="12" r="2.7"/></svg></button></div>
  <div class="id-chip"><span>RANDOM MEMBER IDENTIFIER</span><strong id="randomId">HC-7A92-F04C</strong></div>
</div>
<div class="ticker"><div class="ticker-track"><span>◆ MARKET THE HACK'S FORUM</span><span>◆ RESPONSIBLE DISCLOSURE</span><span>◆ DEFEND • RESEARCH • SHARE</span><span>◆ MARKET THE HACK'S FORUM</span><span>◆ RESPONSIBLE DISCLOSURE</span><span>◆ DEFEND • RESEARCH • SHARE</span></div></div>
<div class="banner-main"><img src="22.png" alt="" onerror="this.style.display='none'"><div class="banner-copy"><small>HACKER CENTER / FIELD NOTES</small><h2>BUILD KNOWLEDGE. EXPOSURE.</h2><p>Practical security research, responsibly shared.</p></div></div>
<div class="banner-pair">
  <div class="banner-small"><img src="2.jpg" alt="" onerror="this.style.display='none'"><div><b>SECURITY RESEARCH</b><span>ANALYSIS · HARDENING · REPORTS</span></div></div>
  <div class="banner-small"><img src="3.jpg" alt="" onerror="this.style.display='none'"><div><b>COMMUNITY EXCHANGE</b><span>TOOLS · KNOWLEDGE · COLLABORATION</span></div></div>
</div>
<div class="layout">
<aside class="sidebar">
  <div class="nav-label">WORKSPACE</div>
  <button class="nav-btn active" data-page="home"><svg viewBox="0 0 24 24"><path d="m3 10 9-7 9 7v10a1 1 0 0 1-1 1h-5v-7H9v7H4a1 1 0 0 1-1-1z"/></svg>Dashboard</button>
  <button class="nav-btn" data-page="threads"><svg viewBox="0 0 24 24"><path d="M4 5h16v12H8l-4 4zM8 9h8M8 13h5"/></svg>General <span class="nav-count" id="threadCount">04</span></button>
  <button class="nav-btn" data-page="research"><svg viewBox="0 0 24 24"><path d="M4 5h16v14H4zM8 9h8M8 13h8M8 17h4"/></svg>Research Lab</button>
  <button class="nav-btn" data-page="market"><svg viewBox="0 0 24 24"><path d="M3 8h18l-2 12H5zM7 8l2-5h6l2 5M9 12v4M15 12v4"/></svg>Marketplace <span class="nav-count">SAFE</span></button>
  <button class="nav-btn" data-page="members"><svg viewBox="0 0 24 24"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2M9 11a4 4 0 1 0 0-8 4 4 0 0 0 0 8zM20 8v6M23 11h-6"/></svg>Members</button>
  <div class="nav-label">PERSONAL</div>
  <button class="nav-btn" data-page="profile"><svg viewBox="0 0 24 24"><circle cx="12" cy="8" r="4"/><path d="M4 21a8 8 0 0 1 16 0"/></svg>Profile</button>
  <button class="nav-btn" data-page="compose"><svg viewBox="0 0 24 24"><path d="M12 5v14M5 12h14"/></svg>New thread</button>
  <button class="nav-btn" data-page="settings"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="3"/><path d="m19.4 15 .1.1 1.4 1.1-1.4 2.4-1.7-.6a8 8 0 0 1-1.7 1l-.3 1.8h-2.8l-.3-1.8a8 8 0 0 1-1.7-1l-1.7.6-1.4-2.4L5.3 15a8 8 0 0 1 0-2l-1.4-1.1 1.4-2.4 1.7.6a8 8 0 0 1 1.7-1L9 7.3h2.8l.3 1.8a8 8 0 0 1 1.7 1l1.7-.6 1.4 2.4-1.4 1.1a8 8 0 0 1-.1 2z"/></svg>Settings</button>
  <div class="side-user"><img id="sideEmblem" src="o2.png" alt="" onerror="this.style.display='none'"><div><b id="sideName">L0ZXX</b><small id="sideRole">OWNER ACCOUNT</small></div></div>
</aside>
<main class="content">
  <div class="welcome"><div><h3>Welcome back, <span id="welcomeName">L0ZXX</span>!</h3><p>You are signed in to the Hacker Center community workspace.</p></div><div class="welcome-meta">MEMBER ID <b id="welcomeId">HC-7A92-F04C</b><br>SESSION · LOCAL DEMO</div></div>

  <section class="page active" id="page-home">
    <div class="section-head"><div><h2>Temporary Announcement</h2><p>Community standards and important updates</p></div><span class="section-tag">NOTICE BOARD</span></div>
    <div class="notice-list">
      <div class="notice"><div class="notice-icon"><svg viewBox="0 0 24 24"><path d="M3 11v2l13 5V6zM16 9a4 4 0 0 1 0 6M6 14l2 6h4l-2-5"/></svg></div><div><b>Share research responsibly</b><p>Never publish personal information, credentials, private records, or unredacted breach data.</p></div></div>
      <div class="notice"><div class="notice-icon"><svg viewBox="0 0 24 24"><path d="M12 3 3 7v5c0 5 4 8 9 9 5-1 9-4 9-9V7zM8 12l3 3 5-6"/></svg></div><div><b>Follow the disclosure policy</b><p>Use coordinated disclosure and contact the system owner through an authorized channel.</p></div></div>
      <div class="notice"><div class="notice-icon"><svg viewBox="0 0 24 24"><path d="M4 4h16v16H4zM8 8h8M8 12h8M8 16h5"/></svg></div><div><b>Keep uploads sanitized</b><p>Remove secrets, personal identifiers, tokens, and live exploit payloads before attaching files.</p></div></div>
    </div>
    <div class="section-head"><div><h2>Hacker Center — General</h2><p>Explore the community categories</p></div><span class="section-tag">OPEN CHANNELS</span></div>
    <div class="category-grid">
      <div class="category" data-go="research"><div class="category-icon"><svg viewBox="0 0 24 24"><ellipse cx="12" cy="5" rx="8" ry="3"/><path d="M4 5v14c0 1.7 3.6 3 8 3s8-1.3 8-3V5M4 12c0 1.7 3.6 3 8 3s8-1.3 8-3"/></svg></div><div><b>Security Research</b><p>Defensive analysis, vulnerability notes, and remediation.</p><small>BY COMMUNITY</small></div></div>
      <div class="category" data-go="threads"><div class="category-icon"><svg viewBox="0 0 24 24"><path d="M4 5h16v12H8l-4 4zM8 9h8M8 13h5"/></svg></div><div><b>General Discussion</b><p>Ask questions and exchange practical knowledge.</p><small>BY COMMUNITY</small></div></div>
      <div class="category" data-go="market"><div class="category-icon"><svg viewBox="0 0 24 24"><path d="M4 5h16v14H4zM8 9h8M8 13h5"/></svg></div><div><b>Tools & Resources</b><p>Share legal tools, learning resources, and templates.</p><small>CURATED EXCHANGE</small></div></div>
      <div class="category" data-go="members"><div class="category-icon"><svg viewBox="0 0 24 24"><circle cx="9" cy="8" r="4"/><path d="M2 21a7 7 0 0 1 14 0M17 4a4 4 0 0 1 0 8M18 15a6 6 0 0 1 4 6"/></svg></div><div><b>Community Members</b><p>Meet contributors, moderators, and admins.</p><small>1,200 DIRECTORY SLOTS</small></div></div>
    </div>
    <div class="forum-entry"><div><small>COMMUNITY FORUM</small><h3>Discussions live in General</h3><p>Open the full thread index to read posts with author profiles, role emblems, biographies, statistics, and attachments.</p></div><button class="action secondary" data-go="threads">Open General <span aria-hidden="true">↗</span></button></div>
  </section>

  <section class="page" id="page-threads">
    <div class="section-head"><div><h2>General / Threads</h2><p>Full discussion feed · author profile and attachments included</p></div><button class="action" data-go="compose">＋ New thread</button></div>
    <div class="toolbar"><input class="search" id="threadSearch" placeholder="Search title, author, or topic…"><select class="search" id="threadFilter" style="max-width:145px"><option value="all">All categories</option><option>Security Research</option><option>General</option><option>Tools & Resources</option></select></div>
    <div class="post-list" id="threadPosts"></div>
  </section>

  <section class="page" id="page-detail">
    <div class="section-head"><div><h2>Thread / Full view</h2><p>Complete post with author profile and attached material</p></div><button class="action secondary" data-go="threads">← Back to General</button></div>
    <div id="detailPost" class="detail-post"></div>
  </section>
  <section class="page" id="page-research">
    <div class="section-head"><div><h2>Research Lab</h2><p>Defensive knowledge base and responsible disclosure notes</p></div><span class="section-tag">DEFENSIVE ONLY</span></div>
    <div class="category-grid">
      <div class="category"><div class="category-icon"><svg viewBox="0 0 48 48" aria-hidden="true"><path d="M24 5.5 39 14v20L24 42.5 9 34V14L24 5.5Z"/><path d="m24 11 9.5 5.4v15.2L24 37l-9.5-5.4V16.4L24 11Z"/><path d="m18.5 20 5.5-3.1 5.5 3.1v8l-5.5 3.1-5.5-3.1v-8Z"/></svg></div><div><b>Asset Inventory</b><p>Document systems you own or are authorized to assess.</p></div></div>
      <div class="category"><div class="category-icon"><svg viewBox="0 0 48 48" aria-hidden="true"><path d="M24 5 38 10.5V22c0 9.2-5.5 16.2-14 21-8.5-4.8-14-11.8-14-21V10.5L24 5Z"/><path d="m17.5 23.5 4.3 4.3 9-10"/><path d="M17 13.5h14"/></svg></div><div><b>Hardening Notes</b><p>Configuration baselines, patching, and access control.</p></div></div>
      <div class="category"><div class="category-icon"><svg viewBox="0 0 48 48" aria-hidden="true"><circle cx="24" cy="24" r="15"/><circle cx="24" cy="24" r="8"/><path d="M24 3v8M24 37v8M3 24h8M37 24h8"/><path d="m20 24 2.7 2.7 5.8-6"/></svg></div><div><b>Incident Response</b><p>Containment, recovery, and lessons learned.</p></div></div>
      <div class="category"><div class="category-icon"><svg viewBox="0 0 48 48" aria-hidden="true"><path d="M8 8.5h32v25H22l-9 7v-7H8v-25Z"/><path d="M15.5 16.5h17M15.5 22.5h12"/><path d="m27.5 29 3 3 6-7"/></svg></div><div><b>Disclosure Reports</b><p>Sanitized findings with clear remediation guidance.</p></div></div>
    </div>
    <div class="section-head"><div><h2>Research discussions</h2><p>Posts tagged Security Research</p></div></div><div class="post-list" id="researchPosts"></div>
  </section>

  <section class="page" id="page-market">
    <div class="section-head"><div><h2>Marketplace / Resource Exchange</h2><p>Legal tools, templates, training, and defensive resources — no stolen data or personal records.</p></div><span class="section-tag">SAFE EXCHANGE</span></div>
    <div class="notice"><div class="notice-icon"><svg viewBox="0 0 48 48" aria-hidden="true"><circle cx="24" cy="24" r="15"/><circle cx="24" cy="24" r="8"/><path d="M24 3v8M24 37v8M3 24h8M37 24h8"/><path d="m20 24 2.7 2.7 5.8-6"/></svg></div><div><b>Marketplace policy</b><p>Only list resources you own or have permission to distribute. No credentials, breached databases, doxxing material, malware, or unauthorized access.</p></div></div>
    <div class="toolbar"><input class="search" id="marketSearch" placeholder="Search tools and resources…"><button class="action" data-go="compose">＋ Share resource</button></div>
    <div class="post-list" id="marketPosts"></div>
  </section>

  <section class="page" id="page-members">
    <div class="section-head"><div><h2>Member Directory</h2><p>Community roster · sample directory with 1,200 generated display identities</p></div><span class="section-tag">1,200 MEMBERS</span></div>
    <div class="toolbar"><input class="search" id="memberSearch" placeholder="Find a member…"><select class="search" id="memberRole" style="max-width:140px"><option value="all">All roles</option><option>OWNER</option><option>MODERATOR</option><option>ADMIN</option><option>MEMBER</option></select></div>
    <div class="stats-grid" style="margin-bottom:13px"><div class="stat-card"><small>TOTAL MEMBERS</small><b>1,200</b></div><div class="stat-card"><small>ONLINE NOW</small><b>84</b></div><div class="stat-card"><small>STAFF TEAM</small><b>16</b></div></div>
    <div class="member-grid" id="memberGrid"></div>
  </section>

  <section class="page" id="page-profile">
    <div class="section-head"><div><h2>Member Profile</h2><p>Public profile preview and account statistics</p></div><div class="profile-actions"><button class="profile-more" type="button" aria-label="Open profile settings menu" title="Profile settings" id="profileMore"><svg viewBox="0 0 24 24"><circle cx="5" cy="12" r="1.5"/><circle cx="12" cy="12" r="1.5"/><circle cx="19" cy="12" r="1.5"/></svg></button><button class="action" data-go="settings">Edit profile</button></div></div>
    <div class="profile-layout">
      <div class="profile-card"><div class="profile-photo" id="profilePhoto">LZ</div><h3 id="profileName">L0ZXX</h3><div id="profileRoleBadge" class="role-badge owner">OWNER</div><img id="profileEmblem" class="role-emblem" src="o2.png" alt="Role emblem" onerror="this.style.display='none'"><p id="profileBio">Security enthusiast · defensive research · responsible disclosure.</p><div class="profile-stats"><div><b id="myPosts">0</b><small>POSTS</small></div><div><b>18</b><small>THREADS</small></div><div><b>2026</b><small>JOINED</small></div></div></div>
      <div class="form-card"><div class="section-head" style="margin-top:0"><div><h2>Account statistics</h2><p>Local prototype metrics</p></div></div><div class="stats-grid"><div class="stat-card"><small>MEMBER ID</small><b style="font-size:15px" id="profileId">HC-7A92-F04C</b></div><div class="stat-card"><small>REPUTATION</small><b>98%</b></div><div class="stat-card"><small>STATUS</small><b style="color:var(--green)">ACTIVE</b></div></div><div class="field" style="margin-top:17px"><label>ABOUT THIS PROFILE</label><p id="profileBioLong" style="font-size:11px;color:#b9b7ce;line-height:1.8">Security enthusiast · defensive research · responsible disclosure.</p></div><button class="action" data-go="settings">Manage profile →</button></div>
    </div>
  </section>

  <section class="page" id="page-compose">
    <div class="section-head"><div><h2>Create a thread</h2><p>Publish a discussion, sanitized report, or community resource</p></div><span class="section-tag">NEW POST</span></div>
    <div class="form-card">
      <form id="postForm">
        <div class="field"><label for="postTitle">THREAD TITLE</label><input id="postTitle" maxlength="120" required placeholder="Write a clear, descriptive title…"></div>
        <div class="form-grid"><div class="field"><label for="postCategory">CATEGORY</label><select id="postCategory"><option>General</option><option>Security Research</option><option>Tools & Resources</option></select></div><div class="field"><label for="postType">POST TYPE</label><select id="postType"><option>Discussion</option><option>Research Note</option><option>Resource Listing</option><option>Responsible Disclosure</option></select></div></div>
        <div class="field"><label for="postBody">DESCRIPTION / BODY</label><textarea id="postBody" required placeholder="Explain the context, findings, defensive impact, and recommended mitigation…"></textarea><small>Do not include personal data, passwords, access tokens, private records, or instructions for unauthorized access.</small></div>
        <div class="form-grid"><div class="field"><label for="postImage">ATTACH IMAGE</label><input class="file-pick" id="postImage" type="file" accept="image/*"><small>Image preview is stored locally in this browser.</small></div><div class="field"><label for="postFile">ATTACH FILE</label><input class="file-pick" id="postFile" type="file"><small>Only attach sanitized files you have permission to share.</small></div></div>
        <div class="notice" style="margin-bottom:13px"><div class="notice-icon">✓</div><div><b>Publishing checklist</b><p>Confirm that this post contains no doxxing, exposed credentials, stolen datasets, or private personal information.</p></div></div>
        <label style="display:flex;gap:9px;align-items:flex-start;font-size:10px;color:#bdb9d1;margin:10px 0 16px"><input type="checkbox" id="safeConfirm" required style="accent-color:#a77cff;margin-top:1px"> I confirm this content is authorized, sanitized, and safe to share.</label>
        <button class="action" type="submit">Publish thread →</button> <button class="action secondary" type="reset">Clear form</button>
      </form>
    </div>
  </section>

  <section class="page" id="page-settings">
    <div class="section-head"><div><h2>Profile & Settings</h2><p>Customize your local demo identity and role preview</p></div><span class="section-tag">LOCAL SETTINGS</span></div>
    <div class="form-card">
      <form id="profileForm">
        <div class="settings-preview">
          <div class="settings-preview-photo" id="settingsPhotoPreview">LZ</div>
          <div><strong id="settingsNamePreview">L0ZXX</strong><small id="settingsRolePreview">OWNER · PROFILE PREVIEW</small></div>
          <img class="settings-preview-emblem" id="settingsEmblemPreview" src="o2.png" alt="Selected role emblem">
        </div>
        <div class="form-grid"><div class="field"><label for="editName">DISPLAY NAME</label><input id="editName" maxlength="22" required value="L0ZXX"></div><div class="field"><label for="editRole">ROLE BADGE</label><select id="editRole"><option>OWNER</option><option>MODERATOR</option><option>ADMIN</option><option>MEMBER</option></select><small>Role switching is a visual prototype only; it does not grant real privileges.</small></div></div>
        <div class="field"><label for="editBio">BIO</label><textarea id="editBio" maxlength="240">Security enthusiast · defensive research · responsible disclosure.</textarea></div>
        <div class="field"><label for="editAvatar">PROFILE IMAGE</label><input class="file-pick" id="editAvatar" type="file" accept="image/*"><small>Choose a square image for best results.</small></div>
        <button class="action" type="submit">Save profile settings</button>
      </form>
    </div>
    <div class="section-head"><div><h2>Role emblem mapping</h2><p>Place the corresponding PNG files beside this HTML file.</p></div></div>
    <div class="category-grid">
      <div class="category"><img src="o2.png" style="width:34px;height:34px;object-fit:contain" onerror="this.style.display='none'"><div><b class="gold-text">OWNER</b><p>o2.png · gold accent</p></div></div>
      <div class="category"><img src="m2.png" style="width:34px;height:34px;object-fit:contain" onerror="this.style.display='none'"><div><b>MODERATOR</b><p>m2.png · teal accent</p></div></div>
      <div class="category"><img src="a2.png" style="width:34px;height:34px;object-fit:contain" onerror="this.style.display='none'"><div><b>ADMIN</b><p>a2.png · violet accent</p></div></div>
      <div class="category"><img src="mb2.png" style="width:34px;height:34px;object-fit:contain" onerror="this.style.display='none'"><div><b>MEMBER</b><p>mb2.png · neutral accent</p></div></div>
    </div>
  </section>
  <footer class="footer">HACKER CENTER · CYBER INTELLIGENCE NETWORK · LOCAL FRONT-END DEMO</footer>
</main>
</div>
</div>
<div class="toast" id="toast"></div>
<div class="modal-backdrop" id="postModal"><div class="modal"><div class="modal-head"><h3>Thread preview</h3><button class="close" id="closeModal">×</button></div><div id="modalContent"></div></div></div>
<script>
const $=s=>document.querySelector(s), $$=s=>[...document.querySelectorAll(s)];
const roleFiles={OWNER:'o2.png',MODERATOR:'m2.png',ADMIN:'a2.png',MEMBER:'mb2.png'};
const defaultProfile={name:'L0ZXX',role:'OWNER',bio:'Security enthusiast · defensive research · responsible disclosure.',avatar:''};
function readStored(key,fallback){
 try{const raw=localStorage.getItem(key);return raw?JSON.parse(raw):fallback}
 catch(err){console.warn('Stored data could not be read:',key,err);return fallback}
}
let profile={...defaultProfile,...(readStored('hc_profile',{})||{})};
let posts=readStored('hc_posts',null);
if(!posts) posts=[
{id:'HC-0001',title:'Baseline checklist for securing a small Linux server',body:'A practical starting point for a hardened host: keep packages patched, disable unused services, require key-based SSH authentication, apply least-privilege access, and centralize logs. Test every change in a staging environment before rolling it out.',category:'Security Research',type:'Research Note',author:'NIKA',role:'ADMIN',bio:'Infrastructure defender · Linux hardening.',date:'10 Nov 2026 · 09:40',image:'',file:''},
{id:'HC-0002',title:'Responsible disclosure report template',body:'A clear report should include a concise summary, affected asset (only when authorized to disclose), reproducible high-level observations, impact assessment, evidence with sensitive values redacted, and a practical remediation path. Coordinate publication with the system owner.',category:'Tools & Resources',type:'Resource Listing',author:'MR•403',role:'MODERATOR',bio:'Application security and disclosure.',date:'09 Nov 2026 · 18:15',image:'',file:''},
{id:'HC-0003',title:'What belongs in a sanitized incident timeline?',body:'Record timestamps with timezone, detection source, affected internal service names where safe, containment actions, and recovery milestones. Avoid copying customer records, credentials, or raw private logs into public threads.',category:'General',type:'Discussion',author:'GHOSTH4X',role:'MEMBER',bio:'Learning incident response.',date:'08 Nov 2026 · 12:02',image:'',file:''}
];
const save=()=>{
 try{
  localStorage.setItem('hc_profile',JSON.stringify(profile));
  localStorage.setItem('hc_posts',JSON.stringify(posts));
  return true;
 }catch(err){
  console.error('Local save failed:',err);
  toast('Penyimpanan browser penuh. Gunakan foto profil yang lebih kecil.');
  return false;
 }
};
const initials=n=>n.slice(0,2).toUpperCase();
const safe=s=>String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const toast=msg=>{const t=$('#toast');t.textContent=msg;t.classList.add('show');setTimeout(()=>t.classList.remove('show'),2400)};
function showPage(name){$('.shell').classList.toggle('is-subpage',name!=='home');$$('.page').forEach(p=>p.classList.toggle('active',p.id==='page-'+name));$$('.nav-btn').forEach(b=>b.classList.toggle('active',b.dataset.page===name));if(name==='threads')renderPosts('threadPosts');if(name==='research')renderPosts('researchPosts',p=>p.category==='Security Research');if(name==='market')renderPosts('marketPosts',p=>p.category==='Tools & Resources');if(name==='members')renderMembers();if(name==='profile')renderProfile();if(name==='settings')fillSettings();window.scrollTo({top:0,behavior:'smooth'})}
$$('[data-page]').forEach(b=>b.addEventListener('click',()=>showPage(b.dataset.page)));
$$('[data-go]').forEach(b=>b.addEventListener('click',()=>showPage(b.dataset.go)));$('#profileMore')?.addEventListener('click',()=>showPage('settings'));
function roleClass(role){return role.toLowerCase()}
function authorBlock(p){const role=p.role||'MEMBER';return `<aside class="post-author"><div class="author-menu-wrap">${p.author===profile.name?`<button class="author-menu-trigger" type="button" aria-label="Profile options" data-profile-menu="${safe(p.id)}"><svg viewBox="0 0 24 24" aria-hidden="true"><circle cx="5" cy="12" r="1.4"/><circle cx="12" cy="12" r="1.4"/><circle cx="19" cy="12" r="1.4"/></svg></button><div class="author-menu" id="authorMenu-${safe(p.id)}"><button type="button" data-edit-profile>EDIT PROFILE</button></div>`:''}<div class="post-avatar">${p.avatar?`<img src="${p.avatar}" alt="">`:safe(initials(p.author||'HC'))}</div></div><img class="role-emblem" src="${roleFiles[role]||roleFiles.MEMBER}" alt="${safe(role)} emblem" data-role-emblem onerror="this.style.display='none'"><strong class="${role==='OWNER'?'gold-text':''}">${safe(p.author||'MEMBER')}</strong><p class="post-bio">${safe(p.bio||'Community contributor · defensive research.')}</p><div class="post-stats"><span>Posts <b>${posts.filter(x=>x.author===p.author).length}</b></span><span>Threads <b>${posts.filter(x=>x.author===p.author).length+3}</b></span><span>Joined <b>2026</b></span><span>Reputation <b>98%</b></span></div></aside>`}
function postCard(p){return `<article class="post-card">${authorBlock(p)}<div class="post-main"><div class="post-meta"><span>${safe(p.category)} / ${safe(p.type||'Discussion')}</span><span>${safe(p.date||'Recently')}</span></div><h3>${safe(p.title)}</h3><div class="post-body post-body-clamped" data-post-body>${safe(p.body)}</div>${p.body.length>520?`<button class="read-more" type="button" data-read-more>READ FULL POST <span>↘</span></button>`:'' }${p.image?`<div class="post-attachment"><img src="${p.image}" alt="Post attachment"></div>`:''}${p.file?`<div class="post-attachment file-attachment"><svg viewBox="0 0 24 24"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8zM14 2v6h6M8 13h8M8 17h6"/></svg><span>${safe(p.file)}</span></div>`:''}<div class="post-foot"><span>THREAD ID: ${safe(p.id)}</span><button data-open="${safe(p.id)}">View discussion ↗</button></div></div></article>`}
function renderPosts(target,filter=null,limit=Infinity,query=''){let list=posts.filter(p=>(!filter||filter(p))&&(`${p.title} ${p.body} ${p.author}`).toLowerCase().includes(query.toLowerCase()));if(target==='threadPosts'&&$('#threadFilter')&&$('#threadFilter').value!=='all')list=list.filter(p=>p.category===$('#threadFilter').value);$('#'+target).innerHTML=list.length?list.slice(0,limit).map(postCard).join(''):'<div class="empty">No threads found. Start a useful discussion.</div>';$$('[data-open]').forEach(b=>b.addEventListener('click',()=>openPost(b.dataset.open)));$$('[data-profile-menu]').forEach(b=>b.addEventListener('click',()=>{const m=$('#authorMenu-'+CSS.escape(b.dataset.profileMenu));if(m)m.classList.toggle('visible')}));$$('[data-edit-profile]').forEach(b=>b.addEventListener('click',()=>showPage('settings')));$$('[data-read-more]').forEach(b=>b.addEventListener('click',()=>{const body=b.previousElementSibling;body.classList.toggle('expanded');b.innerHTML=body.classList.contains('expanded')?'SHOW LESS <span>↗</span>':'READ FULL POST <span>↘</span>'}))}
function openPost(id){const p=posts.find(x=>x.id===id);if(!p)return;$('#detailPost').innerHTML=postCard(p);showPage('detail')}
$('#closeModal').onclick=()=>$('#postModal').classList.remove('show');$('#postModal').addEventListener('click',e=>{if(e.target.id==='postModal')e.currentTarget.classList.remove('show')});
function renderMembers(){const names=['L0ZXX','MR•403','ANONs9c','GHOSTH4X','NIKA','R3DLINE','VOID_77','KRYPT0','S1LENT','HEXWAVE','BYTE•404','ROOTLESS','CYBERNOVA','DARKNODE','PIXELSEC','RAVEN_X'];const roles=['OWNER','MODERATOR','ADMIN','MEMBER'];let data=Array.from({length:1200},(_,i)=>({name:names[i]||`${['NX','V0ID','R3D','HEX','S4F'][i%5]}_${(i*7919+403).toString(16).toUpperCase().slice(0,4)}`,role:i===0?'OWNER':i<5?'MODERATOR':i<16?'ADMIN':'MEMBER'}));data[0]={name:profile.name,role:profile.role};let q=($('#memberSearch').value||'').toLowerCase(),r=$('#memberRole').value;data=data.filter(x=>x.name.toLowerCase().includes(q)&&(r==='all'||x.role===r));$('#memberGrid').innerHTML=data.slice(0,72).map(x=>`<div class="member-card"><div class="member-avatar">${safe(initials(x.name))}</div><div><b class="${x.role==='OWNER'?'gold-text':''}">${safe(x.name)}</b><small>${x.role}</small></div></div>`).join('')||'<div class="empty">No members found.</div>'}
function renderProfile(){const n=profile.name;$('#profileName').textContent=n;$('#profileRoleBadge').textContent=profile.role;$('#profileRoleBadge').className='role-badge '+roleClass(profile.role);$('#profileEmblem').src=roleFiles[profile.role];$('#profileBio').textContent=profile.bio;$('#profileBioLong').textContent=profile.bio;$('#profilePhoto').innerHTML=profile.avatar?`<img src="${profile.avatar}">`:safe(initials(n));$('#myPosts').textContent=posts.filter(p=>p.author===n).length;$('#profileId').textContent=$('#randomId').textContent}
function updateSettingsPreview(){
 const photo=$('#settingsPhotoPreview');
 photo.innerHTML=profile.avatar?`<img src="${profile.avatar}" alt="Profile preview">`:safe(initials(profile.name));
 $('#settingsNamePreview').textContent=profile.name;
 $('#settingsRolePreview').textContent=profile.role+' · PROFILE PREVIEW';
 $('#settingsEmblemPreview').src=roleFiles[profile.role]||roleFiles.MEMBER;
}
function fillSettings(){
 $('#editName').value=profile.name;$('#editRole').value=profile.role;$('#editBio').value=profile.bio;
 updateSettingsPreview();
}
function updateHeader(){
 const n=profile.name;
 $('#welcomeName').textContent=n;$('#sideName').textContent=n;
 $('#sideRole').textContent=profile.role+' ACCOUNT';
 $('#sideEmblem').src=roleFiles[profile.role]||roleFiles.MEMBER;
 $('#topAvatar').innerHTML=profile.avatar?`<img src="${profile.avatar}" alt="Profile">`:safe(initials(n));
 $('#threadCount').textContent=String(posts.length).padStart(2,'0');
 $('#welcomeId').textContent=$('#randomId').textContent;
}
$('#editName').addEventListener('input',()=>{$('#settingsNamePreview').textContent=$('#editName').value||'MEMBER';$('#settingsPhotoPreview').innerHTML=profile.avatar?`<img src="${profile.avatar}" alt="Profile preview">`:safe(initials($('#editName').value||'ME'))});
$('#editRole').addEventListener('change',()=>{$('#settingsRolePreview').textContent=$('#editRole').value+' · PROFILE PREVIEW';$('#settingsEmblemPreview').src=roleFiles[$('#editRole').value]||roleFiles.MEMBER});
function compressProfileImage(file,done){
 const reader=new FileReader();
 reader.onload=()=>{
  const img=new Image();
  img.onload=()=>{
   const max=640,scale=Math.min(1,max/Math.max(img.width,img.height));
   const canvas=document.createElement('canvas');
   canvas.width=Math.max(1,Math.round(img.width*scale));
   canvas.height=Math.max(1,Math.round(img.height*scale));
   const ctx=canvas.getContext('2d');
   ctx.drawImage(img,0,0,canvas.width,canvas.height);
   done(canvas.toDataURL('image/jpeg',0.78));
  };
  img.onerror=()=>{toast('Foto profil tidak dapat dibaca.');};
  img.src=reader.result;
 };
 reader.onerror=()=>toast('Gagal membaca foto profil.');
 reader.readAsDataURL(file);
}
$('#editAvatar').addEventListener('change',e=>{
 const file=e.target.files[0];if(!file)return;
 if(!file.type.startsWith('image/')){toast('Pilih file gambar yang valid.');e.target.value='';return}
 if(file.size>8*1024*1024){toast('Ukuran foto maksimal 8 MB.');e.target.value='';return}
 compressProfileImage(file,data=>{$('#settingsPhotoPreview').innerHTML=`<img src="${data}" alt="Profile preview">`;$('#settingsPhotoPreview').dataset.pendingAvatar=data;});
});
$('#profileForm').addEventListener('submit',e=>{
 e.preventDefault();
 const submit=e.submitter||$('#profileForm button[type="submit"]');
 if(submit){submit.disabled=true;submit.textContent='Saving…'}
 const previousName=profile.name;
 const nextName=$('#editName').value.trim();
 if(!nextName){toast('Display name wajib diisi.');if(submit){submit.disabled=false;submit.textContent='Save profile settings'}return}
 profile.name=nextName;
 profile.role=$('#editRole').value;
 profile.bio=$('#editBio').value.trim();
 const pending=$('#settingsPhotoPreview').dataset.pendingAvatar;
 const finishProfile=()=>{
  posts=posts.map(p=>p.author===previousName?{...p,author:profile.name,role:profile.role,bio:profile.bio,avatar:profile.avatar}:p);
  const saved=save();
  updateHeader();renderProfile();renderPosts('threadPosts');
  renderPosts('researchPosts',p=>p.category==='Security Research');
  renderPosts('marketPosts',p=>p.category==='Tools & Resources');
  if(submit){submit.disabled=false;submit.textContent='Save profile settings'}
  if(saved)toast('Profil berhasil diperbarui.');
 };
 if(pending){profile.avatar=pending;delete $('#settingsPhotoPreview').dataset.pendingAvatar;finishProfile()}
 else finishProfile();
});
$('#postForm').addEventListener('submit',e=>{e.preventDefault();const title=$('#postTitle').value.trim(),body=$('#postBody').value.trim();if(!title||!body)return;const imageFile=$('#postImage').files[0],fileFile=$('#postFile').files[0];if(imageFile&&imageFile.size>3*1024*1024){toast('Image too large. Use an image under 3 MB.');return}if(fileFile&&fileFile.size>5*1024*1024){toast('File too large. Use a file under 5 MB.');return}const addPost=image=>{const p={id:'HC-'+Math.random().toString(36).slice(2,8).toUpperCase(),title,body,category:$('#postCategory').value,type:$('#postType').value,author:profile.name,role:profile.role,bio:profile.bio,avatar:profile.avatar,date:new Date().toLocaleString('en-GB',{day:'2-digit',month:'short',year:'numeric',hour:'2-digit',minute:'2-digit'}),image:image||'',file:fileFile?fileFile.name:''};posts.unshift(p);save();e.target.reset();updateHeader();renderPosts('threadPosts');toast('Thread published to this browser.');showPage('threads')};if(imageFile){const reader=new FileReader();reader.onload=()=>addPost(reader.result);reader.readAsDataURL(imageFile)}else addPost('')});
$('#threadSearch').addEventListener('input',()=>renderPosts('threadPosts',null,Infinity,$('#threadSearch').value));$('#threadFilter').addEventListener('change',()=>renderPosts('threadPosts'));$('#marketSearch').addEventListener('input',()=>renderPosts('marketPosts',p=>p.category==='Tools & Resources',Infinity,$('#marketSearch').value));$('#memberSearch').addEventListener('input',renderMembers);$('#memberRole').addEventListener('change',renderMembers);
let hidden=false;$('#toggleBalance').onclick=()=>{
 hidden=!hidden;
 $('#balanceValue').innerHTML=hidden?'•••••••• <small>BTC</small>':'0,002969 <small>BTC</small>';
 $('#toggleBalance').setAttribute('aria-label',hidden?'Show balance':'Hide balance');
 $('#toggleBalance').innerHTML=hidden
 ?'<svg viewBox="0 0 24 24" aria-hidden="true"><path d="m3 3 18 18M10.6 6.2A10.8 10.8 0 0 1 12 6c6.1 0 9.5 6 9.5 6a16 16 0 0 1-3.1 3.7M6.2 6.2C3.8 7.7 2.5 12 2.5 12s3.4 6 9.5 6c1.2 0 2.3-.2 3.3-.6"/><path d="M9.9 9.9a3 3 0 0 0 4.2 4.2"/></svg>'
 :'<svg viewBox="0 0 24 24" aria-hidden="true"><path d="M2.5 12s3.4-6 9.5-6 9.5 6 9.5 6-3.4 6-9.5 6-9.5-6-9.5-6Z"/><circle cx="12" cy="12" r="2.7"/></svg>';
};
$('#randomId').textContent='HC-'+Math.random().toString(16).slice(2,6).toUpperCase()+'-'+Math.random().toString(16).slice(2,6).toUpperCase();
updateHeader();renderPosts('threadPosts');renderProfile();updateSettingsPreview();

// Convert near-white matte pixels in the supplied emblem PNGs to alpha transparency.
// This keeps the source files named o2.png, mb2.png, m2.png and a2.png unchanged.
function cleanEmblemImage(img){
 if(!img || img.dataset.cleaned==='1' || !img.complete || !img.naturalWidth)return;
 try{
  const canvas=document.createElement('canvas');
  canvas.width=img.naturalWidth;canvas.height=img.naturalHeight;
  const ctx=canvas.getContext('2d',{willReadFrequently:true});
  ctx.drawImage(img,0,0);
  const frame=ctx.getImageData(0,0,canvas.width,canvas.height),d=frame.data;
  for(let i=0;i<d.length;i+=4){
   const min=Math.min(d[i],d[i+1],d[i+2]),max=Math.max(d[i],d[i+1],d[i+2]);
   if(min>218 && max-min<34){
    const alpha=Math.max(0,Math.min(255,Math.round((255-min)*6.8)));
    d[i+3]=Math.min(d[i+3],alpha);
   }
  }
  ctx.putImageData(frame,0,0);
  img.dataset.originalSrc=img.dataset.originalSrc||img.src;
  img.src=canvas.toDataURL('image/png');
  img.dataset.cleaned='1';
 }catch(err){
  // If the browser blocks canvas access to local files, leave the original image visible.
  img.dataset.cleanFailed='1';
  console.warn('Emblem transparency cleanup unavailable:',err);
 }
}
function cleanAllEmblems(){
 document.querySelectorAll('[data-role-emblem],#profileEmblem,#settingsEmblemPreview,#sideEmblem,.category img[src$="o2.png"],.category img[src$="mb2.png"],.category img[src$="m2.png"],.category img[src$="a2.png"]').forEach(img=>{
  if(img.complete)cleanEmblemImage(img);else img.addEventListener('load',()=>cleanEmblemImage(img),{once:true});
 });
}
const emblemObserver=new MutationObserver(()=>cleanAllEmblems());
emblemObserver.observe(document.body,{subtree:true,childList:true});
cleanAllEmblems();

// Delegated controls also work in the dedicated full-thread view.
document.addEventListener('click',e=>{
 const more=e.target.closest('[data-read-more]');
 if(more){const body=more.previousElementSibling;body.classList.toggle('expanded');more.innerHTML=body.classList.contains('expanded')?'SHOW LESS <span>↗</span>':'READ FULL POST <span>↘</span>';return}
 const menu=e.target.closest('[data-profile-menu]');
 if(menu){const panel=document.getElementById('authorMenu-'+menu.dataset.profileMenu);if(panel)panel.classList.toggle('visible');return}
 if(e.target.closest('[data-edit-profile]')){showPage('settings');return}
 if(!e.target.closest('.author-menu-wrap'))document.querySelectorAll('.author-menu.visible').forEach(x=>x.classList.remove('visible'));
});

</script>
</body>
</html>

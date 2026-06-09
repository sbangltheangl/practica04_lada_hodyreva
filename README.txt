*{box-sizing:border-box}
:root{--bg:#080d18;--card:#121c2e;--text:#f5f7fb;--muted:#a6b0c3;--accent:#6c63ff;--accent2:#22d3ee;--border:rgba(255,255,255,.12);--radius:18px;--shadow:0 24px 70px rgba(0,0,0,.35)}
body{margin:0;font-family:Arial,Helvetica,sans-serif;color:var(--text);background:radial-gradient(circle at 20% 10%,rgba(108,99,255,.28),transparent 28%),radial-gradient(circle at 90% 5%,rgba(34,211,238,.18),transparent 26%),var(--bg);line-height:1.6}
a{color:inherit;text-decoration:none}.container{width:min(1120px,calc(100% - 32px));margin:0 auto}
.site-header{position:sticky;top:0;z-index:10;background:rgba(8,13,24,.88);border-bottom:1px solid var(--border);backdrop-filter:blur(14px)}
.header-inner{min-height:76px;display:flex;justify-content:space-between;align-items:center;gap:24px}
.logo{font-size:28px;font-weight:800;letter-spacing:-.04em}.logo::after{content:".";color:var(--accent2)}
.nav{display:flex;gap:12px;flex-wrap:wrap}.nav a{padding:10px 14px;border-radius:999px;color:var(--muted)}.nav a:hover,.nav a.active{color:var(--text);background:rgba(255,255,255,.08)}
.hero{padding:86px 0 54px}.hero-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:32px;align-items:center}
.eyebrow{color:var(--accent2);text-transform:uppercase;letter-spacing:.16em;font-weight:700;font-size:13px}
h1{margin:0 0 18px;font-size:clamp(38px,7vw,74px);line-height:1;letter-spacing:-.06em}h2{margin:0 0 18px;font-size:28px;letter-spacing:-.03em}h3{margin:0 0 10px}
.hero-text,.lead{max-width:720px;color:var(--muted);font-size:20px}.hero-actions{display:flex;gap:14px;flex-wrap:wrap;margin-top:30px}
.btn{display:inline-flex;justify-content:center;align-items:center;min-height:48px;padding:12px 22px;border-radius:999px;border:1px solid var(--border);font-weight:700;cursor:pointer}
.btn.primary{color:#07101f;background:linear-gradient(135deg,var(--accent2),var(--accent));border:none}.btn.secondary{background:rgba(255,255,255,.06)}
.hero-card,.card,.product-card{background:linear-gradient(180deg,rgba(255,255,255,.06),rgba(255,255,255,.025));border:1px solid var(--border);border-radius:var(--radius);box-shadow:var(--shadow)}
.hero-card{padding:28px;display:grid;gap:16px}.stat{padding:22px;border-radius:16px;background:rgba(255,255,255,.05)}.stat strong{display:block;font-size:42px}.stat span,.card p,.product-card p,.product-card li,.muted{color:var(--muted)}
.section{padding:54px 0}.features,.product-grid,.contact-grid{display:grid;gap:20px}.features{grid-template-columns:repeat(3,1fr)}.product-grid{grid-template-columns:repeat(2,1fr);margin-top:28px}.contact-grid{grid-template-columns:1fr 1fr;margin-top:28px;align-items:start}
.card,.product-card{padding:28px}.split{display:grid;grid-template-columns:.8fr 1.2fr;gap:30px;align-items:start;padding-top:20px}
.check-list{margin:0;padding:0;list-style:none;display:grid;gap:12px}.check-list li{padding:16px 18px;background:var(--card);border:1px solid var(--border);border-radius:14px}.check-list li::before{content:"✓";color:var(--accent2);font-weight:800;margin-right:10px}
.product-icon{width:62px;height:62px;margin-bottom:18px;display:grid;place-items:center;border-radius:18px;background:linear-gradient(135deg,rgba(34,211,238,.25),rgba(108,99,255,.35));font-weight:800}.product-card ul{padding-left:18px}
.form-row{margin-bottom:16px}label{display:block;margin-bottom:7px;font-weight:700}
input,select,textarea{width:100%;padding:14px 15px;border:1px solid var(--border);border-radius:12px;background:rgba(8,13,24,.75);color:var(--text);font:inherit}
input:focus,select:focus,textarea:focus{outline:3px solid rgba(34,211,238,.22);border-color:var(--accent2)}
.map-placeholder{min-height:220px;margin-top:22px;display:grid;place-items:center;border-radius:16px;border:1px dashed rgba(255,255,255,.28);color:var(--muted);background:linear-gradient(135deg,rgba(108,99,255,.20),rgba(34,211,238,.10)),#101827}
.site-footer{padding:34px 0;color:var(--muted);border-top:1px solid var(--border);text-align:center}
@media (max-width:820px){.header-inner,.hero-grid,.split,.contact-grid{grid-template-columns:1fr}.header-inner{display:grid;justify-items:start;padding:18px 0}.features,.product-grid{grid-template-columns:1fr}.hero{padding-top:48px}}
@media (max-width:520px){.nav{width:100%}.nav a{flex:1;text-align:center}.btn{width:100%}}

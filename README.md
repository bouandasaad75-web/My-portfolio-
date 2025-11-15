:root{
  --bg: #ffffff;
  --text: #0f1724;
  --muted: #6b7280;
  --accent: #0ea5a4; /* يمكن تغييره */
  --card: #f8fafc;
  --radius: 12px;
  --container: 1100px;
  font-family: 'Inter', system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
}

*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0;
  background:var(--bg);
  color:var(--text);
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  line-height:1.45;
}

.container{max-width:var(--container);margin:0 auto;padding:28px}

.site-header{border-bottom:1px solid #eef2f6;background:rgba(255,255,255,0.8);backdrop-filter:saturate(120%) blur(6px);position:sticky;top:0;z-index:30}
.header-inner{display:flex;align-items:center;justify-content:space-between;padding:10px 0}
.brand{font-weight:700;color:var(--text);text-decoration:none}
.nav{display:flex;gap:18px}
.nav a{color:var(--text);text-decoration:none;font-weight:500}
.nav-toggle{display:none;background:none;border:0;font-size:

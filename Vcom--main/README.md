<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Vcom — README</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <style>
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; line-height:1.5; max-width:720px; margin:36px auto; color:#111; }
    header { margin-bottom:18px; }
    h1 { font-size:28px; margin:0 0 6px 0; }
    p.lead { margin:0 0 12px 0; color:#333; }
    ul { margin:8px 0 16px 20px; }
    code { background:#f3f3f3; padding:2px 6px; border-radius:4px; font-family:monospace; }
    .meta { font-size:13px; color:#555; }
    .box { padding:12px; background:#fafafa; border:1px solid #eee; border-radius:8px; }
  </style>
</head>
<body>
  <header>
    <h1>Vcom</h1>
    <p class="lead">A small, modular full-stack demo app — clean APIs, simple frontend, Docker-ready.</p>
  </header>

  <section class="box">
    <strong>Features</strong>
    <ul>
      <li>User auth (JWT)</li>
      <li>CRUD for core resources</li>
      <li>Docker support</li>
    </ul>

    <strong>Quick start</strong>
    <ul>
      <li>Clone: <code>git clone https://github.com/Vinaymadhu45/Vcom.git</code></li>
      <li>Backend: <code>cd backend && ./mvnw spring-boot:run</code> (or your start command)</li>
      <li>Frontend: <code>cd frontend && npm install && npm start</code></li>
    </ul>

    <p class="meta">Env: add DB connection and <code>JWT_SECRET</code> in each service's .env.</p>
  </section>

  <footer style="margin-top:14px; font-size:13px; color:#444">
    License: MIT · Contact: <a href="mailto:your-email@example.com">your-email@example.com</a>
  </footer>
</body>
</html>

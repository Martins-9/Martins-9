<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Currículo / Perfil — Enzo Martins dos Santos</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#f5f6f8;
      --card:#0f1723;
      --muted:#6b7280;
      --white:#ffffff;
      --radius:12px;
      --shadow: 0 6px 20px rgba(2,6,23,0.12);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:"Inter",system-ui,-apple-system,"Segoe UI",Roboto,Arial;
      background: linear-gradient(180deg,#fafbfc 0%, #f1f3f5 100%);
      color:#111827;
      padding:28px;
    }
    .container{ max-width:980px; margin:0 auto; }
    header{
      display:flex;
      gap:20px;
      align-items:flex-start;
      margin-bottom:24px;
    }
    .avatar{
      width:92px; height:92px;
      border-radius:12px;
      background:linear-gradient(135deg,#111827,#0f1723);
      display:flex; align-items:center; justify-content:center;
      color:var(--white);
      font-weight:700; font-size:28px;
      box-shadow:var(--shadow);
      flex-shrink:0;
    }
    .profile-info{ flex:1; }
    .profile-info h1{
      margin:0 0 6px 0;
      font-size:22px;
    }
    .role{
      display:inline-block;
      background:#111827;
      color:var(--white);
      padding:6px 10px;
      border-radius:8px;
      font-size:13px;
      font-weight:600;
      margin-top:4px;
    }
    p.bio{
      margin:10px 0 12px 0;
      color:var(--muted);
      line-height:1.5;
      font-size:14px;
    }
    .tech-icons{
      display:flex;
      gap:8px;
      flex-wrap:wrap;
      margin-top:12px;
    }
    .icon{
      width:40px; height:40px;
      border-radius:8px;
      background:rgba(255,255,255,0.7);
      display:flex; align-items:center; justify-content:center;
      font-weight:700;
      color:#111827;
      font-size:13px;
      box-shadow:0 4px 12px rgba(2,6,23,0.06);
    }
    .card{
      background:var(--card);
      color:var(--white);
      padding:18px;
      border-radius:12px;
      box-shadow:var(--shadow);
      margin-bottom:18px;
    }
    .card h3{ margin:0 0 10px 0; font-size:16px; }
    ul.links{
      list-style:none;
      padding:0;
      margin:0;
    }
    ul.links li{
      margin-bottom:8px;
      font-size:14px;
    }
    ul.links a{
      color:#60a5fa;
      text-decoration:none;
    }
    footer{
      margin-top:20px;
      color:var(--muted);
      font-size:13px;
      text-align:center;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">EM</div>
      <div class="profile-info">
        <h1>Enzo Martins dos Santos</h1>
        <span class="role">Estudante de Programação</span>
        <p class="bio">
          Tenho 15 anos e estou estudando para me tornar profissional na área de programação, buscando aprender mais e 
          adquirir experiência prática. Atualmente, iniciei meus estudos em Python e pretendo expandir meus conhecimentos para outras linguagens e tecnologias.
        </p>
        <div class="tech-icons">
          <div class="icon">HTML</div>
          <div class="icon">CSS</div>
          <div class="icon">PY</div>
          <div class="icon">JS</div>
        </div>
      </div>
    </header>

    <!-- Card de links -->
    <div class="card">
      <h3>Links</h3>
      <ul class="links">
        <li>● GitHub: <a href="https://github.com/Martins-9" target="_blank">github.com/martins9</a></li>
        <li>● LinkedIn: <a href="#" target="_blank">[Adicionar quando criar]</a></li>
      </ul>
    </div>

    <!-- Card de contato -->
    <div class="card">
      <h3>Contato</h3>
      <p>Email: <strong>enzom9260@gmail.com</strong></p>
      <p>Local: <span>Santo André - São Paulo</span></p>
    </div>

    <footer>
      © 2025 — Portfólio de Enzo Martins dos Santos
    </footer>
  </div>
</body>
</html>


---

# Jj-universe
Sla
<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Universe JJ - Semi Anarquia</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600;800&display=swap" rel="stylesheet">  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Orbitron', sans-serif;
      color: white;
      overflow-x: hidden;
      background: #000;
    }

    /* FUNDO ANIMADO */
    .background {
      position: fixed;
      inset: 0;
      background: linear-gradient(270deg, #0f0f1a, #1a0033, #000);
      background-size: 600% 600%;
      animation: bgMove 12s ease infinite;
      z-index: -2;
    }

    @keyframes bgMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* TEXTO PHONK */
    .phonk-text {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: clamp(40px, 10vw, 90px);
      font-weight: 800;
      color: #ff0055;
      text-shadow:
        0 0 10px #ff0055,
        0 0 30px #ff0055,
        0 0 60px #8000ff;
      animation: glitch 2s infinite;
      opacity: 0.25;
      pointer-events: none;
      z-index: -1;
      text-align: center;
    }

    @keyframes glitch {
      0% { transform: translate(-50%, -50%) skew(0deg); }
      25% { transform: translate(-49%, -51%) skew(2deg); }
      50% { transform: translate(-51%, -49%) skew(-2deg); }
      75% { transform: translate(-50%, -50%) skew(1deg); }
      100% { transform: translate(-50%, -50%) skew(0deg); }
    }

    header {
      text-align: center;
      padding: 70px 20px 40px;
    }

    header h1 {
      font-size: 52px;
      color: #7f9cff;
      text-shadow: 0 0 15px #7f9cff;
    }

    header p {
      margin-top: 10px;
      color: #ccc;
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    .card {
      background: rgba(20, 20, 40, 0.88);
      border-radius: 16px;
      padding: 30px;
      margin-bottom: 30px;
      box-shadow: 0 0 25px rgba(0,0,0,0.8);
    }

    .card h2 {
      color: #ff6b6b;
      margin-bottom: 15px;
    }

    .card ul {
      padding-left: 20px;
    }

    .card li {
      margin-bottom: 10px;
    }

    .discord {
      text-align: center;
    }

    .discord a {
      display: inline-block;
      margin-top: 20px;
      padding: 16px 30px;
      background: linear-gradient(45deg, #5865F2, #8a5cff);
      color: white;
      text-decoration: none;
      border-radius: 12px;
      font-size: 18px;
      box-shadow: 0 0 20px #5865F2;
      transition: transform .2s, box-shadow .2s;
    }

    .discord a:hover {
      transform: scale(1.05);
      box-shadow: 0 0 30px #8a5cff;
    }

    footer {
      text-align: center;
      padding: 25px;
      color: #aaa;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      header h1 { font-size: 38px; }
      .card { padding: 22px; }
    }
  </style></head>
<body>  <div class="background"></div>
  <div class="phonk-text">SEMI ANARCHY</div>  <header>
    <h1>Universe JJ</h1>
    <p>Servidor Minecraft • Semi-Anarquia</p>
  </header>  <section>
    <div class="card">
      <h2>📜 Regras do Servidor</h2>
      <ul>
        <li>❌ Cheats (Xray, KillAura, Fly, AutoClick)</li>
        <li>❌ Clientes hack ou mods ilegais</li>
        <li>❌ Dupe, bugs ou exploits</li>
        <li>❌ Lag proposital</li>
        <li>❌ Racismo ou discurso de ódio</li>
        <li>✅ PvP, grief e raid liberados fora do spawn</li>
      </ul>
    </div><div class="card discord">
  <h2>💬 Discord Oficial</h2>
  <p>Entre na comunidade do Universe JJ</p>
  <a href="https://discord.gg/Gx52UMZ4p" target="_blank">Entrar no Discord</a>
</div>

  </section>  <footer>
    © 2026 • Universe JJ • Todos

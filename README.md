<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>sucloudflare0x00 — Bug Bounty & Security Research</title>

  <meta name="description"
       content="Histórico público de sucloudflare0x00 em bug bounty, VDPs, CTFs, segurança web, API testing e pesquisa de vulnerabilidades.">

  <meta name="author" content="sucloudflare0x00">

  <meta name="robots" content="index, follow">

  <link rel="canonical" href="https://github.com/sucloudflare">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #0b0f14;
      color: #e6edf3;
      line-height: 1.6;
    }

    .container {
      width: min(1100px, 92%);
      margin: auto;
    }

    header {
      padding: 80px 0 50px;
      text-align: center;
      border-bottom: 1px solid #30363d;
    }

    .username {
      color: #58a6ff;
      font-size: 18px;
      margin-bottom: 12px;
    }

    h1 {
      font-size: clamp(34px, 6vw, 64px);
      margin-bottom: 15px;
    }

    .subtitle {
      color: #8b949e;
      font-size: 18px;
    }

    section {
      padding: 55px 0;
      border-bottom: 1px solid #21262d;
    }

    h2 {
      font-size: 30px;
      margin-bottom: 20px;
    }

    h3 {
      margin-bottom: 12px;
      color: #58a6ff;
    }

    p {
      color: #c9d1d9;
      margin-bottom: 15px;
    }

    .stats {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 18px;
      margin-top: 30px;
    }

    .stat {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 12px;
      padding: 25px;
      text-align: center;
    }

    .num {
      display: block;
      font-size: 38px;
      font-weight: bold;
      color: #58a6ff;
    }

    .lbl {
      display: block;
      color: #8b949e;
      margin-top: 5px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 12px;
      padding: 25px;
    }

    .handle {
      color: #58a6ff;
      font-family: monospace;
    }

    ul {
      margin: 15px 0 0 20px;
      color: #c9d1d9;
    }

    li {
      margin: 7px 0;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 20px;
    }

    code {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 6px;
      padding: 6px 10px;
      color: #79c0ff;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 25px;
      background: #161b22;
    }

    th,
    td {
      border: 1px solid #30363d;
      padding: 14px;
      text-align: left;
    }

    th {
      color: #58a6ff;
    }

    td {
      color: #c9d1d9;
    }

    .links {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 25px;
    }

    .links a {
      display: inline-block;
      padding: 12px 18px;
      border: 1px solid #30363d;
      border-radius: 8px;
      color: #58a6ff;
      text-decoration: none;
      background: #161b22;
    }

    .links a:hover {
      border-color: #58a6ff;
    }

    blockquote {
      margin-top: 30px;
      padding: 20px;
      border-left: 4px solid #58a6ff;
      background: #161b22;
      color: #c9d1d9;
      font-style: italic;
    }

    .source {
      font-size: 13px;
      color: #8b949e;
      margin-top: 12px;
    }

    footer {
      padding: 35px 0;
      text-align: center;
      color: #8b949e;
      font-family: monospace;
    }

    .verified {
      color: #3fb950;
    }

    @media (max-width: 600px) {
      header {
        padding: 55px 0 35px;
      }

      section {
        padding: 40px 0;
      }

      th,
      td {
        padding: 9px;
        font-size: 14px;
      }
    }
  </style>

</head>

<body>

  <header>
    <div class="container">

      <div class="username">@sucloudflare0x00</div>

      <h1>Bug Bounty &amp; Security Research</h1>

      <p class="subtitle">
        Histórico público de pesquisa em segurança, Bug Bounty, VDPs e CTFs.
      </p>

    </div>
  </header>

  <main>

    <section>
      <div class="container">

        <h2>Sobre</h2>

        <p>
          Nos últimos meses venho dedicando tempo à pesquisa de segurança,
          identificação e reporte de possíveis vulnerabilidades em programas
          públicos e privados, além de participar de CTFs e VDPs.
        </p>

        <p>
          Este projeto reúne informações públicas relacionadas à trajetória
          de <strong>sucloudflare0x00</strong> em segurança da informação.
        </p>

        <p>
          Os números apresentados nesta página correspondem aos registros
          públicos disponíveis nas respectivas plataformas e podem ser
          atualizados conforme novas submissões sejam analisadas.
        </p>

      </div>
    </section>


    <section>
      <div class="container">

        <h2>Números registrados</h2>

        <div class="stats">

          <div class="stat">
            <span class="num">7</span>
            <span class="lbl">Vulnerabilidades reportadas</span>
          </div>

          <div class="stat">
            <span class="num">70%</span>
            <span class="lbl">Accuracy</span>
          </div>

          <div class="stat">
            <span class="num">1</span>
            <span class="lbl">Validada e resolvida</span>
          </div>

          <div class="stat">
            <span class="num">5</span>
            <span class="lbl">Badges / achievements</span>
          </div>

        </div>

      </div>
    </section>


    <section>
      <div class="container">

        <h2>Plataformas</h2>

        <div class="cards">

          <div class="card">

            <h3>📍 Bugcrowd</h3>

            <p class="handle">@sucloudflare0x00</p>

            <ul>
              <li>7 vulnerabilidades reportadas</li>
              <li>70% de accuracy</li>
              <li>Submission Shogun — Level 2</li>
              <li>Bounty Bee — Level 2</li>
              <li>Foco em Web Application e API Testing</li>
            </ul>

            <div class="links">
              <a href="https://bugcrowd.com/"
                 target="_blank"
                 rel="noopener noreferrer">
                Perfil Bugcrowd
              </a>
            </div>

          </div>


          <div class="card">

            <h3>📍 HackerOne</h3>

            <p class="handle">@sucloudflare0x00</p>

            <ul>
              <li>Vulnerabilidade registrada como validada e resolvida no Gogo VDP</li>
              <li>Badge: Insecticide</li>
              <li>Badge: TrailBlazer</li>
              <li>Badge: Good Samaritan</li>
              <li>Atuação em pesquisa de vulnerabilidades</li>
            </ul>

            <div class="links">
              <a href="https://hackerone.com/sucloudflare0x00"
                 target="_blank"
                 rel="noopener noreferrer">
                Perfil HackerOne
              </a>
            </div>

          </div>

        </div>

      </div>
    </section>


    <section>
      <div class="container">

        <h2>Áreas de atuação</h2>

        <table>

          <thead>
            <tr>
              <th>Área</th>
              <th>Classes / Stack</th>
            </tr>
          </thead>

          <tbody>

            <tr>
              <td><strong>Segurança Web</strong></td>
              <td>
                <code>IDOR</code>
                <code>CORS</code>
                <code>XSS</code>
                <code>SSRF</code>
                <code>Race Conditions</code>
              </td>
            </tr>

            <tr>
              <td><strong>API Testing</strong></td>
              <td>
                <code>Authentication</code>
                <code>Authorization</code>
                <code>Broken Access Control</code>
                <code>Business Logic</code>
              </td>
            </tr>

            <tr>
              <td><strong>Smart Contracts</strong></td>
              <td>
                <code>Solidity</code>
                <code>Foundry</code>
                <code>DeFi</code>
              </td>
            </tr>

          </tbody>

        </table>

      </div>
    </section>


    <section>
      <div class="container">

        <h2>Projetos e pesquisa</h2>

        <p>
          O perfil público associado ao username
          <strong>sucloudflare</strong> reúne projetos relacionados a
          desenvolvimento, automação, reconhecimento e segurança.
        </p>

        <div class="links">

          <a href="https://github.com/sucloudflare"
             target="_blank"
             rel="noopener noreferrer">
            GitHub — sucloudflare
          </a>

          <a href="https://hackerone.com/sucloudflare0x00"
             target="_blank"
             rel="noopener noreferrer">
            HackerOne
          </a>

        </div>

      </div>
    </section>


    <section>
      <div class="container">

        <h2>Histórico público</h2>

        <p>
          Esta página não substitui os registros originais das plataformas.
          Ela funciona como uma apresentação consolidada das informações
          públicas relacionadas ao perfil.
        </p>

        <p>
          Para confirmação dos números, badges e resultados de submissões,
          consulte diretamente os perfis das respectivas plataformas.
        </p>

        <blockquote>
          Bora continuar caçando bugs. 🐛
        </blockquote>

      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <span>$ exit</span>
      <br>
      <span>sucloudflare0x00 · bug bounty hunter</span>
    </div>
  </footer>

</body>
</html>

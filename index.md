<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Pritam System Log</title>

<style>
  :root {
    --bg: #000;
    --panel: #050505;
    --text: #f5f5f5;
    --muted: #9a9a9a;
    --border: #2a2a2a;
  }

  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    background: var(--bg);
    color: var(--text);
    font-family: "Fira Code", Consolas, monospace;
    line-height: 1.7;
    padding: 20px;
  }

  h1 {
    text-align: center;
    letter-spacing: 0.25em;
    font-size: 1.6rem;
    margin-bottom: 30px;
  }

  .container {
    max-width: 900px;
    margin: auto;
    background: var(--panel);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 28px;
  }

  .divider {
    color: var(--muted);
  }

  .section {
    margin: 28px 0;
  }

  .section-title {
    font-size: 0.85rem;
    letter-spacing: 0.3em;
    margin-bottom: 8px;
    color: var(--muted);
  }

  .log-line {
    margin: 4px 0;
  }

  .muted {
    color: var(--muted);
  }

  .ok {
    font-weight: bold;
  }

  .cursor {
    display: inline-block;
    width: 10px;
    height: 1em;
    background: #fff;
    margin-left: 6px;
    animation: blink 1.1s infinite;
    vertical-align: bottom;
  }

  @keyframes blink {
    50% { opacity: 0; }
  }

  @media (max-width: 480px) {
    body {
      padding: 12px;
    }

    .container {
      padding: 20px;
    }

    h1 {
      font-size: 1.2rem;
      letter-spacing: 0.18em;
    }
  }
</style>
</head>

<body>

<h1>PRITAM · SYSTEM LOG</h1>

<div class="container">

  <div class="section">
    <div class="divider">────────────────────────────────────────</div>
    <div class="log-line">INITIALIZING pritammaharjan.dev v1.0.0</div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line">[BOOT] Loading system… <span class="ok">OK</span></div>
    <div class="log-line">[BOOT] Environment detected… Sydney, Australia</div>
    <div class="log-line">[BOOT] Contact channel… primgdev@gmail.com</div>
  </div>

  <div class="section">
    <div class="section-title">MODULE: IDENTITY</div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line">name: "Pritam Maharjan"</div>
    <div class="log-line">role: "Software Engineer (Web)"</div>
    <div class="log-line">status: "always learning"</div>
  </div>

  <div class="section">
    <div class="section-title">MODULE: PURPOSE</div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line muted">
      > Crafting clean, predictable, human-centered web experiences.
    </div>
    <div class="log-line muted">
      > Building interfaces that feel simple and behave consistently.
    </div>
    <div class="log-line muted">
      > Writing code that explains itself.
    </div>
  </div>

  <div class="section">
    <div class="section-title">MODULE: STACK</div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line">frontend → UI logic, components, state</div>
    <div class="log-line">backend → APIs, CMS, performance</div>
    <div class="log-line">tools → Git, Postman, Bitbucket</div>
  </div>

  <div class="section">
    <div class="section-title">MODULE: EXPERIENCE</div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line">• Cypha Interactive — Junior .NET Developer</div>
    <div class="log-line">• GO Tech International — Software Engineer</div>
    <div class="log-line">• PIEX Education — Developer Intern</div>
  </div>

  <div class="section">
    <div class="section-title">FINALIZE RENDER</div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line">[OK] System initialized</div>
    <div class="log-line">[OK] All modules operational</div>
    <div class="log-line">
      [OK] Ready to build<span class="cursor"></span>
    </div>
  </div>

</div>

</body>
</html>

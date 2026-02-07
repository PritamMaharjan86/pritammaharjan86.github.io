<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Pritam System Log</title>

<style>
  :root {
    --bg: #0b0f14;
    --panel: #0f1623;
    --primary: #00ffc8;
    --secondary: #82aaff;
    --success: #00ff7f;
    --text: #d6deeb;
    --muted: #7f8fa6;
  }

  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    background: radial-gradient(circle at top, #0f172a, #020617);
    color: var(--text);
    font-family: "Fira Code", Consolas, monospace;
    line-height: 1.7;
    padding: 20px;
  }

  .container {
    max-width: 900px;
    margin: auto;
    background: rgba(15, 22, 35, 0.75);
    border: 1px solid rgba(0, 255, 200, 0.15);
    border-radius: 14px;
    padding: 28px;
    box-shadow:
      0 0 40px rgba(0, 255, 200, 0.08),
      inset 0 0 20px rgba(0, 0, 0, 0.4);
  }

  h1 {
    text-align: center;
    color: var(--success);
    letter-spacing: 0.15em;
    margin-bottom: 30px;
    text-shadow: 0 0 12px rgba(0, 255, 127, 0.4);
  }

  .section {
    margin: 28px 0;
  }

  .divider {
    color: var(--primary);
    opacity: 0.8;
  }

  .section-title {
    color: var(--primary);
    letter-spacing: 0.2em;
    font-size: 0.9rem;
    margin-bottom: 10px;
  }

  .highlight {
    color: var(--secondary);
  }

  .ok {
    color: var(--success);
    font-weight: bold;
  }

  .muted {
    color: var(--muted);
  }

  .log-line {
    margin: 4px 0;
  }

  .cursor {
    display: inline-block;
    width: 10px;
    background: var(--success);
    margin-left: 4px;
    animation: blink 1.1s infinite;
  }

  @keyframes blink {
    50% { opacity: 0; }
  }
</style>
</head>

<body>

<h1>PRITAM · SYSTEM LOG</h1>

<div class="container">

  <div class="section">
    <div class="divider">────────────────────────────────────────</div>
    <div class="log-line">
      INITIALIZING <span class="highlight">pritammaharjan.dev</span> v1.0.0
    </div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line">[BOOT] Loading system… <span class="ok">OK</span></div>
    <div class="log-line">[BOOT] Environment detected… Sydney, Australia</div>
    <div class="log-line">
      [BOOT] Contact channel… <span class="highlight">primgdev@gmail.com</span>
    </div>
  </div>

  <div class="section">
    <div class="section-title">MODULE: IDENTITY</div>
    <div class="divider">────────────────────────────────────────</div>

    <div class="log-line">name: <span class="highlight">"Pritam Maharjan"</span></div>
    <div class="log-line">role: "Software Engineer (Web)"</div>
    <div class="log-line">status: <span class="ok">"always learning"</span></div>
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

    <div class="log-line"><span class="ok">[OK]</span> System initialized</div>
    <div class="log-line"><span class="ok">[OK]</span> Modules operational</div>
    <div class="log-line">
      <span class="ok">[OK]</span> Ready to build<span class="cursor"></span>
    </div>
  </div>

</div>

</body>
</html>

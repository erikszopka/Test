<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Lebenslauf Max Mustermann – Frontend Entwickler">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Max Mustermann – Lebenslauf</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 2rem auto;
      line-height: 1.5;
      color: #333;
    }
    header, section {
      margin-bottom: 2rem;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
      color: #5D2E8C;
    }
    .contact span {
      display: inline-block;
      margin-right: 1rem;
    }
    h2 {
      font-size: 1.5rem;
      border-bottom: 2px solid #5D2E8C;
      padding-bottom: 0.3rem;
    }
    .job, .education, .project {
      margin-bottom: 1rem;
    }
    .job h3, .education h3, .project h3 {
      margin: 0;
      font-size: 1.2rem;
    }
    .job .meta, .education .meta, .project .meta {
      font-size: 0.9rem;
      color: #666;
    }
    ul.skills {
      list-style: none;
      padding: 0;
    }
    ul.skills li {
      display: inline-block;
      margin-right: 1rem;
      background: #EAE2F8;
      padding: 0.3rem 0.6rem;
      border-radius: 0.3rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Max Mustermann</h1>
  <div class="contact">
    <span>📍 Musterstadt, Deutschland</span>
    <span>✉️ mail@example.com</span>
    <span>📞 +49 170 1234567</span>
    <span>🔗 <a href="#">GitHub</a></span>
    <span>🔗 <a href="#">LinkedIn</a></span>
  </div>
</header>

<section id="profil">
  <h2>Profil</h2>
  <p>Erfahrener Frontend‑Entwickler mit Schwerpunkt auf **React**, **Vue.js** und moderner Softwarearchitektur. Leidenschaft für effiziente und nutzerfreundliche Weblösungen.</p>
</section>

<section id="erfahrung">
  <h2>Berufserfahrung</h2>

  <article class="job">
    <h3>Senior Frontend Engineer – Beispiel GmbH</h3>
    <p class="meta">2020 – heute</p>
    <ul>
      <li>Entwicklung skalierbarer Webapplikationen mit React, TypeScript und Tailwind CSS.</li>
      <li>Aufbau modularer UI‑Komponenten mittels OneDesign System.</li>
      <li>Mentoring von Junior-Entwicklern & Durchführung von Code‑Reviews.</li>
    </ul>
  </article>

  <article class="job">
    <h3>Frontend Developer – Muster AG</h3>
    <p class="meta">2017 – 2020</p>
    <ul>
      <li>Umsetzung responsiver SPAs mit React/Vue und Integration von REST‑APIs.</li>
      <li>Performance‑Optimierung (z. B. LCP, TBT) und Aufbau von CI/CD‑Pipelines.</li>
      <li>Einführung automatisierter Tests (Jest, Cypress).</li>
    </ul>
  </article>
</section>

<section id="faehigkeiten">
  <h2>Technische Fähigkeiten</h2>
  <ul class="skills">
    <li>HTML5</li><li>CSS3</li><li>JavaScript</li><li>React</li><li>Vue.js</li>
    <li>Tailwind CSS</li><li>TypeScript</li><li>Jest</li><li>Cypress</li><li>Git</li>
  </ul>
</section>

<section id="ausbildung">
  <h2>Ausbildung</h2>
  <article class="education">
    <h3>B.Sc. Informatik – Universität Musterstadt</h3>
    <p class="meta">2013 – 2016</p>
  </article>
</section>

<section id="projekte">
  <h2>Projekte</h2>
  <article class="project">
    <h3>Dashboard‑Plattform</h3>
    <p class="meta">React ● WebSocket ● D3.js</p>
    <ul>
      <li>Interaktive Visualisierung von Nutzerdaten, Performance-Steigerung um 30 %.</li>
    </ul>
  </article>
  <article class="project">
    <h3>Open‑Source: Markdown‑Resume Generator</h3>
    <p class="meta">Markdown ● Open Source</p>
    <ul>
      <li>Beitrag zur Erstellung ATS‑freundlicher Lebenslaufsysteme.:contentReference[oaicite:0]{index=0}</li>
    </ul>
  </article>
</section>

<section id="zusatz">
  <h2>Sprachen & Interessen</h2>
  <p><strong>Deutsch:</strong> Muttersprache | <strong>Englisch:</strong> Fließend</p>
  <p>Interessen: UI/UX‑Design, Agile Methoden, Tech‑Meetups</p>
</section>

</body>
</html>

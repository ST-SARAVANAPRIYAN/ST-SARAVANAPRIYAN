<!--
  Ultimate Neon-Tech Mixed README
  Author:  SARAVANA PRIYAN S T
  Repo name MUST be: ST-SARAVANAPRIYAN
  This README includes inline SVG animations, animated GIFs, dynamic stats cards and hooks for auto-updating sections.
-->

<!-- ==========================
     Animated Neon Header (inline SVG)
     GitHub renders basic inline SVGs in README.
   ========================== -->
<div align="center">
  <svg width="100%" height="160" viewBox="0 0 1200 160" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" role="img" aria-labelledby="title-desc">
    <title id="title">SARAVANA PRIYAN S T - Banner</title>
    <desc id="desc">Neon animated banner with glowing gradient and pulsing orbit</desc>

    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0%" stop-color="#00F5A0">
          <animate attributeName="stop-color" dur="6s"
            values="#00F5A0;#00B4FF;#9D00FF;#FF007A;#00F5A0" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#FF007A">
          <animate attributeName="stop-color" dur="6s"
            values="#FF007A;#00F5A0;#00B4FF;#9D00FF;#FF007A" repeatCount="indefinite"/>
        </stop>
      </linearGradient>

      <filter id="glow">
        <feGaussianBlur stdDeviation="6.5" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Background -->
    <rect width="1200" height="160" fill="#020617"/>

    <!-- Neon title -->
    <text x="50%" y="48%" text-anchor="middle" font-family="Segoe UI, Roboto, Inter, Arial" font-size="34" font-weight="800"
          fill="url(#g1)" style="filter:url(#glow);">
      SARAVANA PRIYAN S T
    </text>

    <!-- Tagline -->
    <text x="50%" y="73%" text-anchor="middle" font-family="Segoe UI, Roboto, Inter, Arial" font-size="16" fill="#bcdfff" opacity="0.9">
      AI &amp; Data Science Enthusiast | Tech Explorer
    </text>

    <!-- Orbiting neon dots -->
    <g transform="translate(1000,40)">
      <circle r="6" fill="#00F5A0" opacity="0.95">
        <animate attributeName="cx" values="0;40;0" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0.9;0.45;0.9" dur="4s" repeatCount="indefinite"/>
      </circle>
      <circle r="4" fill="#FF007A" cx="-20" cy="40" opacity="0.9">
        <animate attributeName="cy" values="40;10;40" dur="3.2s" repeatCount="indefinite"/>
      </circle>
    </g>

  </svg>
</div>

---

<div align="center">

<!-- Typing-effect style (SVG based) -->
<svg width="680" height="70" viewBox="0 0 680 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="typing">
  <style>
    .t { font: 600 20px/1 "Segoe UI", Roboto, Arial; fill: #bfefff; }
  </style>
  <text x="12" y="28" class="t">Hi, I'm <tspan font-weight="800">SARAVANA PRIYAN S T</tspan> —</text>
  <text x="12" y="54" class="t">
    <tspan> </tspan>
    <tspan>
      <animate attributeName="textLength" from="0" to="420" dur="3.6s" fill="freeze" />
    </tspan>
    <tspan id="typed" font-style="italic">AI &amp; Data Science • Realtime tinkering • Open-source</tspan>
  </text>
</svg>

</div>

---

## 🔭 About me
I build and explore ML tooling and data systems, love clean code, and enjoy making nifty automation & analysis tools.

---

## 📊 Live GitHub Stats & Highlights

<p align="center">
  <!-- GitHub Stats from github-readme-stats (replace theme if you prefer) -->
  <img src="https://github-readme-stats.vercel.app/api?username=ST-SARAVANAPRIYAN&show_icons=true&theme=radical&count_private=true" alt="GitHub stats" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ST-SARAVANAPRIYAN&layout=compact&theme=radical" alt="Top languages" />
</p>

<p align="center">
  <!-- Streak & Commits -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ST-SARAVANAPRIYAN&theme=highcontrast" alt="streak" />
</p>

---

## 🚀 Featured Projects
<table>
  <tr>
    <td align="center" width="48%">
      <a href="https://github.com/ST-SARAVANAPRIYAN/COLLEGE-EVENT-MANAGEMENT-SYSTEM">
        <img alt="CEMS Demo" src="https://c.tenor.com/6e2U2E2G3UcAAAAC/loading-spinner.gif" width="220"/><br/>
        <b>College Event Management System</b>
      </a>
      <p>Event management portal built for college activities (Java / Servlet / DB)</p>
    </td>
    <td align="center" width="48%">
      <a href="https://github.com/ST-SARAVANAPRIYAN/insurance_assistant">
        <img alt="Insurance Assistant" src="https://c.tenor.com/4fQp8D4k5cMAAAAC/drawing-speed.gif" width="220"/><br/>
        <b>Insurance Assistant</b>
      </a>
      <p>Assistant for insurance workflows — automation & data analysis (Python)</p>
    </td>
  </tr>
</table>

---

## 🛠 Tech stack & skills
<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/PYTHON-3776AB?logo=python&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/JAVA-007396?logo=java&logoColor=white" />
  <img alt="C" src="https://img.shields.io/badge/C-00599C?logo=c&logoColor=white" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
</p>

---

## ✨ Auto-updating sections (powered by GitHub Actions)
- **Daily Tech Quote**: curated list of tech quotes rotates daily (see below).  
- **Last Commit**: shows last repo commit timestamp (auto-updated).  
- **Visitor Counter**: public badge shows profile views.

> **Daily Quote (tech)**  
> <blockquote>
> <em id="daily-quote">"Talk is cheap. Show me the code." — Linus Torvalds</em>
> </blockquote>

> **Last commit** — <em id="last-commit">Automatically updated by workflow</em>  
> **Profile views** —  
> <img src="https://visitor-badge.glitch.me/badge?page_id=ST-SARAVANAPRIYAN.ST-SARAVANAPRIYAN" alt="visitor badge" />

---

## 🔁 Contribution animation
<p align="center">
  <img alt="contribution-snake" src="https://raw.githubusercontent.com/Platane/snk/master/static/snake-dark.svg" width="600" />
</p>

---

## 📫 Contact
<p align="center">
  <a href="https://www.linkedin.com/in/saravana-priyan-s-t"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin" /></a>
  &nbsp;
  <a href="mailto:saravanapriyanst@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-red?logo=gmail&logoColor=white" /></a>
</p>

---

## 🔧 How this README auto-updates (files included)
- `.github/workflows/daily-update.yml` — GitHub Action that runs daily and on push.
- `scripts/update_readme.py` — picks a tech quote, reads README, replaces the `<em id="daily-quote">...</em>` and `<em id="last-commit">...</em>` parts and commits the change.

You can preview and tweak the `QUOTES` list in `scripts/update_readme.py` if you want to customize quotes.

---

## ✍️ Manual edits & tips
- Replace any GIF URLs with your custom project demos (hosted or public GIFs).  
- To change color theme, edit the inline SVG gradient stops.  
- If you prefer a different visitor counter, replace the badge URL with your preferred service.

---

*Enjoy the neon vibes. If you want I can also:*
- produce a tiny logo SVG for your avatar theme,
- add a "Currently coding" live card using GitHub Actions to show current branch,
- or build a more advanced dynamic stats card (requires a small token or service).

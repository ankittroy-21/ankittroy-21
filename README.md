<div align="center">

<!-- ══════════════════════════════════════════════════
     HERO BANNER — inline SVG (no external host needed)
     ══════════════════════════════════════════════════ -->

<svg width="860" height="160" viewBox="0 0 860 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0d1117"/>
      <stop offset="50%"  stop-color="#0f2027"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FF87"/>
      <stop offset="100%" stop-color="#60efff"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="860" height="160" rx="16" fill="url(#bg)"/>

  <!-- Top accent line -->
  <rect x="0" y="0" width="860" height="3" rx="2" fill="url(#accent)"/>

  <!-- Grid dots -->
  <g fill="#1a2a3a" opacity="0.6">
    <circle cx="30"  cy="30"  r="1.5"/><circle cx="80"  cy="30"  r="1.5"/><circle cx="130" cy="30"  r="1.5"/>
    <circle cx="180" cy="30"  r="1.5"/><circle cx="230" cy="30"  r="1.5"/><circle cx="280" cy="30"  r="1.5"/>
    <circle cx="30"  cy="80"  r="1.5"/><circle cx="80"  cy="80"  r="1.5"/><circle cx="130" cy="80"  r="1.5"/>
    <circle cx="30"  cy="130" r="1.5"/><circle cx="80"  cy="130" r="1.5"/><circle cx="130" cy="130" r="1.5"/>
    <circle cx="730" cy="30"  r="1.5"/><circle cx="780" cy="30"  r="1.5"/><circle cx="830" cy="30"  r="1.5"/>
    <circle cx="730" cy="80"  r="1.5"/><circle cx="780" cy="80"  r="1.5"/><circle cx="830" cy="80"  r="1.5"/>
    <circle cx="730" cy="130" r="1.5"/><circle cx="780" cy="130" r="1.5"/><circle cx="830" cy="130" r="1.5"/>
  </g>

  <!-- Avatar circle frame -->
  <circle cx="100" cy="80" r="48" fill="none" stroke="url(#accent)" stroke-width="2" opacity="0.8" filter="url(#glow)"/>
  <clipPath id="avatar"><circle cx="100" cy="80" r="44"/></clipPath>
  <image href="https://avatars.githubusercontent.com/u/82595330?v=4" x="56" y="36" width="88" height="88" clip-path="url(#avatar)"/>

  <!-- Name -->
  <text x="178" y="62" font-family="'Segoe UI', monospace" font-size="30" font-weight="700" fill="url(#accent)" filter="url(#glow)">ANKIT ROY</text>

  <!-- Subtitle line -->
  <rect x="178" y="70" width="480" height="1.5" fill="url(#accent)" opacity="0.4"/>

  <!-- Role tags -->
  <text x="178" y="92" font-family="monospace" font-size="13" fill="#8b949e">
    <tspan fill="#00FF87">▶</tspan>  Software Developer  ·  Backend Architect  ·  AI &amp; Automation
  </text>

  <!-- Status pill -->
  <rect x="178" y="108" width="130" height="22" rx="11" fill="#00FF87" opacity="0.12"/>
  <circle cx="194" cy="119" r="4" fill="#00FF87">
    <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="204" y="124" font-family="monospace" font-size="11" fill="#00FF87">ONLINE · SHIPPING</text>

  <!-- Location pill -->
  <rect x="320" y="108" width="95" height="22" rx="11" fill="#60efff" opacity="0.12"/>
  <text x="334" y="124" font-family="monospace" font-size="11" fill="#60efff">🇮🇳 India</text>

  <!-- Bottom accent line -->
  <rect x="0" y="157" width="860" height="3" rx="2" fill="url(#accent)"/>
</svg>

<!-- Typing animation -->
<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=2800&pause=900&color=00FF87&center=true&vCenter=true&multiline=true&width=700&height=72&lines=Building+tools+that+talk+to+each+other+%E2%80%94+so+you+don%27t+have+to;VSCode+Extension+Author+%7C+Hackathon+Veteran+%7C+Open+Source+Contributor;Automating+the+boring+stuff+since+2021+%F0%9F%9A%80)](https://github.com/ankittroy-21)

<!-- Social badges -->

[![GitHub followers](https://img.shields.io/github/followers/ankittroy-21?label=Followers&style=flat-square&color=00FF87&labelColor=0d1117&logo=github)](https://github.com/ankittroy-21?tab=followers)
[![Profile Views](https://komarev.com/ghpvc/?username=ankittroy-21&color=00FF87&style=flat-square&label=Profile+Views)](https://github.com/ankittroy-21)
[![VSCode Extension](https://img.shields.io/visual-studio-marketplace/i/ankittroy-21.gitphone?label=Gitphone+Installs&style=flat-square&color=60efff&labelColor=0d1117&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=ankittroy-21.gitphone)
[![PyPI](https://img.shields.io/pypi/dm/kuberef?label=kuberef+Downloads&style=flat-square&color=ff9f43&labelColor=0d1117&logo=pypi)](https://pypi.org/project/kuberef/)

</div>

---

## 🧠 About Me

```yaml
# ankittroy-21 :: developer.yml
name:         Ankit Roy
handle:       "@ankittroy-21"
location:     India 🇮🇳
role:         Software Developer · Backend · AI · Automation

currently:
  building:   "Gitphone — GitHub remote control via Telegram + VS Code"
  learning:   ["LLM pipelines", "FastAPI at scale", "Kubernetes internals"]
  obsessed:   "Making devtools talk to messaging apps"

philosophy:
  - "If it can be automated → it WILL be automated"
  - "The best commit is the one you didn't write yourself"
  - "Open source today, industry standard tomorrow"
  - "Ship fast. Break nothing. Automate the rest."

fun_fact:     "I build tools to avoid doing things manually… including this README"
```

---

## 🛠 Tech Stack

<div align="center">

**Languages**

[![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://python.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://java.com)

**Frameworks & Runtimes**

[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![Uvicorn](https://img.shields.io/badge/Uvicorn-4B0082?style=for-the-badge&logo=python&logoColor=white)](https://www.uvicorn.org)

**Data & Cloud**

[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)
[![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com)

**Dev Tools & APIs**

[![VS Code API](https://img.shields.io/badge/VS_Code_API-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/api)
[![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://core.telegram.org/bots/api)
[![PyGitHub](https://img.shields.io/badge/PyGitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://pygithub.readthedocs.io)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org)

</div>

---

## 🚀 Featured Projects

### ⚡ Personal Tools

<table>
<tr>
<td width="50%" valign="top">

#### 🔭 [Gitphone](https://github.com/ankittroy-21/Gitphone)
> **The Developer's Remote Control for GitHub**

Stage code in VS Code, commit & deploy from Telegram. Maintain your streak even when you're away from your desk. Published on the VS Code Marketplace.

`Python` `FastAPI` `Supabase` `TypeScript` `VS Code API` `Telegram Bot API`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/Gitphone?style=flat-square&color=00FF87&labelColor=0d1117)](https://github.com/ankittroy-21/Gitphone/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/Gitphone?style=flat-square&color=60efff&labelColor=0d1117)](https://github.com/ankittroy-21/Gitphone/network)
[![Marketplace](https://img.shields.io/badge/VSCode-Marketplace-007ACC?style=flat-square&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=ankittroy-21.gitphone)

</td>
<td width="50%" valign="top">

#### 📐 [Latex-Generator](https://github.com/ankittroy-21/Latex-Generator)
> **Math should be beautiful**

Programmatically generate LaTeX diagrams and formatted mathematical content from code. Because beautiful documentation shouldn't require manual typesetting.

`Python` `LaTeX` `Automation`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/Latex-Generator?style=flat-square&color=00FF87&labelColor=0d1117)](https://github.com/ankittroy-21/Latex-Generator/stargazers)
[![Size](https://img.shields.io/github/repo-size/ankittroy-21/Latex-Generator?style=flat-square&color=ff9f43&labelColor=0d1117)](https://github.com/ankittroy-21/Latex-Generator)
[![Status](https://img.shields.io/badge/Status-Shipped-00FF87?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/Latex-Generator)

</td>
</tr>
</table>

---

### 🏆 Hackathon Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🗳 [BallotIQ](https://github.com/ankittroy-21/BallotIQ)
> **AI-Powered Election Education Platform**

Learn how elections work in every country — interactive AI assistant + curated learning modules + quizzes. Built at a hackathon, deployed on Google Cloud Run.

`TypeScript` `Next.js` `AI` `Google Cloud`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/BallotIQ?style=flat-square&color=9B59B6&labelColor=0d1117)](https://github.com/ankittroy-21/BallotIQ/stargazers)
[![Live](https://img.shields.io/badge/Live-Demo-9B59B6?style=flat-square&logo=google-cloud)](https://ballotiq-61721852903.us-central1.run.app/)
[![Badge](https://img.shields.io/badge/🏆-Hackathon-gold?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/BallotIQ)

</td>
<td width="50%" valign="top">

#### 🅿️ [parkfinder](https://github.com/ankittroy-21/parkfinder)
> **Smart Parking — Production Grade**

Find real-time parking spots at scale. Built with a scalable architecture designed for production from day one. A hackathon project that went beyond prototype.

`TypeScript` `Node.js` `Scalability`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/parkfinder?style=flat-square&color=9B59B6&labelColor=0d1117)](https://github.com/ankittroy-21/parkfinder/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/parkfinder?style=flat-square&color=9B59B6&labelColor=0d1117)](https://github.com/ankittroy-21/parkfinder/network)
[![Badge](https://img.shields.io/badge/🏆-Hackathon-gold?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/parkfinder)

</td>
</tr>
</table>

---

### 🌐 Open Source Contributions

<table>
<tr>
<td width="33%" valign="top">

#### 🌍 [CO2Track](https://github.com/ankittroy-21/CO2Track)
Real-time carbon footprint tracker — because the planet needs good code too.

`JavaScript` `Vercel`

[![Live](https://img.shields.io/badge/Live-co2track-2ECC71?style=flat-square)](https://co-2-track.vercel.app)
[![Stars](https://img.shields.io/github/stars/ankittroy-21/CO2Track?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/CO2Track)

</td>
<td width="33%" valign="top">

#### ♾ [Algo-Infinity-Verse](https://github.com/ankittroy-21/Algo-Infinity-Verse)
DSA learning universe — algorithms visualized & explained interactively.

`HTML` `CSS` `JavaScript`

[![Live](https://img.shields.io/badge/Live-Demo-2ECC71?style=flat-square)](https://algo-infinity-verse.vercel.app)
[![Stars](https://img.shields.io/github/stars/ankittroy-21/Algo-Infinity-Verse?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/Algo-Infinity-Verse)

</td>
<td width="33%" valign="top">

#### ☕ [Learnovate](https://github.com/ankittroy-21/Learnovate)
Java + DSA learning repo from the Learnovate bootcamp — structured, open, and growing.

`Java` `DSA`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/Learnovate?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/Learnovate)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/Learnovate?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/Learnovate/network)

</td>
</tr>
<tr>
<td width="33%" valign="top">

#### 🎓 [LecturePulse](https://github.com/ankittroy-21/LecturePulse)
Real-time lecture engagement platform. Deployed and live.

`JavaScript` `Node.js`

[![Live](https://img.shields.io/badge/Live-lecturepulse-2ECC71?style=flat-square)](https://lecturepulse.vercel.app)

</td>
<td width="33%" valign="top">

#### ☸️ [kuberef](https://github.com/ankittroy-21/kuberef)
Kubernetes reference PyPI package — for devs who live in the terminal.

`Python` `PyPI` `Kubernetes`

[![PyPI](https://img.shields.io/pypi/v/kuberef?style=flat-square&color=3775A9&labelColor=0d1117&logo=pypi)](https://pypi.org/project/kuberef/)

</td>
<td width="33%" valign="top">

#### 🤝 More on GitHub
Explore all my repositories — experiments, utilities, and works in progress.

[![Repos](https://img.shields.io/badge/View_All_Repos-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ankittroy-21?tab=repositories)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=ankittroy-21&show_icons=true&theme=merko&hide_border=true&bg_color=0d1117&title_color=00FF87&icon_color=60efff&text_color=c9d1d9&border_radius=12&include_all_commits=true&count_private=true">
  <img src="https://github-readme-stats.vercel.app/api?username=ankittroy-21&show_icons=true&hide_border=true&bg_color=ffffff&title_color=0d6efd&icon_color=0d6efd&text_color=333333&border_radius=12" height="170"/>
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=ankittroy-21&layout=compact&theme=merko&hide_border=true&bg_color=0d1117&title_color=00FF87&text_color=c9d1d9&border_radius=12&langs_count=8">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ankittroy-21&layout=compact&hide_border=true&bg_color=ffffff&title_color=0d6efd&text_color=333333&border_radius=12" height="170"/>
</picture>

<br/><br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=ankittroy-21&theme=merko&hide_border=true&background=0D1117&stroke=00FF87&ring=00FF87&fire=ff9f43&currStreakLabel=00FF87&sideLabels=c9d1d9&dates=c9d1d9&border_radius=12)](https://git.io/streak-stats)

</div>

---

## 📈 Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ankittroy-21&bg_color=0d1117&color=00FF87&line=60efff&point=00FF87&area=true&area_color=00FF87&hide_border=true&radius=8)](https://github.com/ankittroy-21)

</div>

---

## 🏅 Achievements & Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=ankittroy-21&theme=matrix&no-frame=true&no-bg=true&margin-w=6&margin-h=6&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 🌐 Connect

<div align="center">

<svg width="700" height="80" viewBox="0 0 700 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="card-bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f2027"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
  </defs>
  <rect width="700" height="80" rx="12" fill="url(#card-bg)" stroke="#00FF87" stroke-width="0.5" stroke-opacity="0.4"/>
  <text x="350" y="28" font-family="monospace" font-size="12" fill="#8b949e" text-anchor="middle">// find me on the internet</text>
  <text x="350" y="55" font-family="'Segoe UI', monospace" font-size="15" fill="#00FF87" text-anchor="middle" filter="url(#glow)">github.com/ankittroy-21</text>
  <text x="350" y="72" font-family="monospace" font-size="11" fill="#60efff" text-anchor="middle">marketplace.visualstudio.com → search: Gitphone</text>
</svg>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-@ankittroy--21-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ankittroy-21)
[![VSCode Marketplace](https://img.shields.io/badge/VSCode_Marketplace-Gitphone-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://marketplace.visualstudio.com/items?itemName=ankittroy-21.gitphone)
[![PyPI](https://img.shields.io/badge/PyPI-kuberef-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/kuberef/)

</div>

---

<div align="center">

<svg width="680" height="54" viewBox="0 0 680 54" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footer-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FF87" stop-opacity="0"/>
      <stop offset="50%"  stop-color="#00FF87" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#60efff" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="680" height="54" rx="10" fill="#0d1117"/>
  <rect x="0" y="0" width="680" height="1" fill="url(#footer-grad)"/>
  <text x="340" y="22" font-family="monospace" font-size="12" fill="#8b949e" text-anchor="middle">ankittroy-21@github:~$</text>
  <text x="340" y="42" font-family="monospace" font-size="13" fill="#00FF87" text-anchor="middle">echo "I don't sleep. I ship." &amp;&amp; git push origin main</text>
  <rect x="0" y="53" width="680" height="1" fill="url(#footer-grad)"/>
</svg>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ankittroy-21&color=00FF87&style=flat-square&label=Visitors)
&nbsp;·&nbsp;
**Made with 🔥 by [Ankit Roy](https://github.com/ankittroy-21)**

</div>

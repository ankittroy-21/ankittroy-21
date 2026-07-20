<div align="center">

<!-- ══════════════════════════════════════════════════
     HERO BANNER — inline SVG
     ══════════════════════════════════════════════════ -->

<svg width="860" height="130" viewBox="0 0 860 130" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#060d16"/>
      <stop offset="50%"  stop-color="#0b1929"/>
      <stop offset="100%" stop-color="#060d16"/>
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FF87"/>
      <stop offset="100%" stop-color="#60efff"/>
    </linearGradient>
    <linearGradient id="name-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00FF87"/>
      <stop offset="60%"  stop-color="#60efff"/>
      <stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="soft-glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Avatar clip -->
    <clipPath id="avatar-clip"><circle cx="65" cy="65" r="46"/></clipPath>
  </defs>

  <!-- Background -->
  <rect width="860" height="130" rx="18" fill="url(#bg)"/>

  <!-- Subtle circuit-board grid -->
  <g stroke="#1a2e45" stroke-width="0.4" opacity="0.5">
    <line x1="0" y1="40"  x2="150" y2="40"/><line x1="0" y1="90" x2="140" y2="90"/>
    <line x1="50"  y1="0" x2="50"  y2="130"/><line x1="100" y1="0" x2="100" y2="30"/>
    <line x1="100" y1="50" x2="100" y2="80"/><line x1="100" y1="100" x2="100" y2="130"/>
    <line x1="150" y1="0" x2="150" y2="130"/>
    <!-- right side -->
    <line x1="710" y1="40"  x2="860" y2="40"/><line x1="680" y1="90" x2="860" y2="90"/>
    <line x1="810" y1="0" x2="810" y2="130"/><line x1="760" y1="0" x2="760" y2="130"/>
    <line x1="710" y1="0" x2="710" y2="130"/>
  </g>

  <!-- Top accent bar -->
  <rect x="0" y="0" width="860" height="3" rx="2" fill="url(#accent)"/>

  <!-- Glow ring behind avatar -->
  <circle cx="65" cy="65" r="52" fill="none" stroke="#00FF87" stroke-width="1.5" opacity="0.25"/>
  <circle cx="65" cy="65" r="48" fill="none" stroke="url(#accent)" stroke-width="2.5" opacity="0.9" filter="url(#glow)"/>

  <!-- Profile picture (GitHub avatar) -->
  <image href="avatar.png"
         x="19" y="19" width="92" height="92"
         clip-path="url(#avatar-clip)"
         preserveAspectRatio="xMidYMid slice"/>

  <!-- Name -->
  <text x="155" y="76" font-family="'Segoe UI', 'Inter', monospace" font-size="36" font-weight="800"
        fill="url(#name-grad)" filter="url(#glow)" letter-spacing="1">ANKIT ROY</text>

  <!-- Bottom accent bar -->
  <rect x="0" y="127" width="860" height="3" rx="2" fill="url(#accent)"/>
</svg>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=2800&pause=900&color=00FF87&center=true&vCenter=true&multiline=true&width=720&height=72&lines=Building+tools+that+talk+to+each+other+—+so+you+don%27t+have+to;VSCode+Publisher+%7C+Hackathon+Veteran+%7C+PyPI+Author+%7C+Open+Source;Automating+the+boring+stuff+since+2021+🚀)](https://github.com/ankittroy-21)

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
  building:   "Next big thing — stay tuned"
  learning:   ["LLM pipelines", "FastAPI at scale", "Kubernetes internals", "RAG systems"]
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
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

**Frameworks & Runtimes**

[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org)
[![Uvicorn](https://img.shields.io/badge/Uvicorn-4B0082?style=for-the-badge&logo=python&logoColor=white)](https://www.uvicorn.org)

**AI & ML**

[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://langchain.com)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
[![Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![Groq](https://img.shields.io/badge/Groq-F54E00?style=for-the-badge&logo=groq&logoColor=white)](https://groq.com)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co)

**Data & Cloud**

[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io)
[![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)

**APIs, Dev Tools & Integrations**

[![VS Code API](https://img.shields.io/badge/VS_Code_API-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/api)
[![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://core.telegram.org/bots/api)
[![WhatsApp API](https://img.shields.io/badge/WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://developers.facebook.com/docs/whatsapp)
[![Spotify API](https://img.shields.io/badge/Spotify_API-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://developer.spotify.com)
[![PyGitHub](https://img.shields.io/badge/PyGitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://pygithub.readthedocs.io)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://postman.com)

</div>

---

## 🚀 Featured Projects

### 🏆 Hackathon Projects

<table>
<tr>
<td width="50%" valign="top">

#### 📱 [Gitphone](https://github.com/ankittroy-21/Gitphone)
> **Developer's Remote Control for GitHub**

Stage code in VS Code, commit & push from Telegram. Your GitHub workflow — wherever you are. Built at a hackathon, shipped to VS Code Marketplace.

`Python` `FastAPI` `Supabase` `TypeScript` `VS Code API` `Telegram Bot API`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/Gitphone?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/Gitphone/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/Gitphone?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/Gitphone/network)
[![Marketplace](https://img.shields.io/badge/VSCode-Marketplace-007ACC?style=flat-square&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=ankittroy-21.gitphone)
[![Badge](https://img.shields.io/badge/🏆-Hackathon-f59e0b?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/Gitphone)

</td>
<td width="50%" valign="top">

#### 🤖 [Triage Agent](https://github.com/ankittroy-21/hackerrank-orchestrate-may26)
> **AI-Powered Medical Triage Assistant**

An AI agent that performs smart medical triage — classifying patient symptoms, prioritizing severity, and routing to the right care. Built under hackathon pressure.

`Python` `LangChain` `Groq` `FastAPI` `AI Agents`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/hackerrank-orchestrate-may26?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/hackerrank-orchestrate-may26/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/hackerrank-orchestrate-may26?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/hackerrank-orchestrate-may26/network)
[![Badge](https://img.shields.io/badge/🏆-Hackathon-f59e0b?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/hackerrank-orchestrate-may26)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💼 [OpportuAI](https://github.com/ankittroy-21/opportuai)
> **AI Job Opportunity Hunter**

Scans the web for job listings, matches them to your skills using LLMs, and surfaces the best opportunities. Automates the most boring part of job hunting.

`Python` `AI` `LLMs` `Automation`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/opportuai?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/opportuai/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/opportuai?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/opportuai/network)
[![Badge](https://img.shields.io/badge/🏆-Hackathon-f59e0b?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/opportuai)

</td>
<td width="50%" valign="top">

#### 💬 [WhatsApp Health Assistant](https://github.com/ankittroy-21/whatsapp-health-assistant)
> **Your Doctor on WhatsApp**

An AI-powered health assistant that lives inside WhatsApp. Ask symptoms, get preliminary guidance, and know when to see a real doctor — all via chat.

`Python` `WhatsApp API` `Gemini AI` `FastAPI`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/whatsapp-health-assistant?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/whatsapp-health-assistant/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/whatsapp-health-assistant?style=flat-square&color=f59e0b&labelColor=0d1117)](https://github.com/ankittroy-21/whatsapp-health-assistant/network)
[![Badge](https://img.shields.io/badge/🏆-Hackathon-f59e0b?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/whatsapp-health-assistant)

</td>
</tr>
</table>

---

### ⚡ Personal Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🎵 [Spotigram](https://github.com/ankittroy-21/spotigram)
> **Spotify × Telegram = Spotigram**

Control Spotify playback, browse your playlists, and share tracks — all from Telegram. Because the best music player is the one already open.

`Python` `Spotify API` `Telegram Bot API` `FastAPI`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/spotigram?style=flat-square&color=00FF87&labelColor=0d1117)](https://github.com/ankittroy-21/spotigram/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/spotigram?style=flat-square&color=00FF87&labelColor=0d1117)](https://github.com/ankittroy-21/spotigram/network)
[![Status](https://img.shields.io/badge/Status-Personal-00FF87?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/spotigram)

</td>
<td width="50%" valign="top">

#### 🗣 [Vaani](https://github.com/ankittroy-21/vaani)
> **Voice → Action. Everywhere.**

A cross-platform voice assistant that understands intent and executes tasks. Beyond simple commands — Vaani reasons, responds, and acts.

`Python` `Speech Recognition` `NLP` `AI`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/vaani?style=flat-square&color=00FF87&labelColor=0d1117)](https://github.com/ankittroy-21/vaani/stargazers)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/vaani?style=flat-square&color=00FF87&labelColor=0d1117)](https://github.com/ankittroy-21/vaani/network)
[![Status](https://img.shields.io/badge/Status-Personal-00FF87?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/vaani)

</td>
</tr>
</table>

---

### 🎓 Internship Project

<table>
<tr>
<td width="50%" valign="top">

#### 📐 [Latex-Generator](https://github.com/ankittroy-21/Latex-Generator)
> **Math Should Be Beautiful**

Built during an internship — programmatically generate LaTeX diagrams and mathematical content from code. Because beautiful documentation shouldn't require manual typesetting.

`Python` `LaTeX` `Automation`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/Latex-Generator?style=flat-square&color=e879f9&labelColor=0d1117)](https://github.com/ankittroy-21/Latex-Generator/stargazers)
[![Size](https://img.shields.io/github/repo-size/ankittroy-21/Latex-Generator?style=flat-square&color=e879f9&labelColor=0d1117)](https://github.com/ankittroy-21/Latex-Generator)
[![Badge](https://img.shields.io/badge/🎓-Internship-e879f9?style=flat-square&labelColor=0d1117)](https://github.com/ankittroy-21/Latex-Generator)

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

---

### 🌐 Open Source Contributions

<table>
<tr>
<td width="33%" valign="top">

#### 🗳 [BallotIQ](https://github.com/ankittroy-21/BallotIQ)
AI-powered election education platform — learn how elections work in every country with interactive modules + quizzes.

`TypeScript` `Next.js` `AI` `Google Cloud`

[![Live](https://img.shields.io/badge/Live-Demo-2ECC71?style=flat-square&logo=google-cloud)](https://ballotiq-61721852903.us-central1.run.app/)
[![Stars](https://img.shields.io/github/stars/ankittroy-21/BallotIQ?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/BallotIQ)

</td>
<td width="33%" valign="top">

#### 🅿️ [parkfinder](https://github.com/ankittroy-21/parkfinder)
Smart parking finder — production-grade, scalable, and built for real traffic.

`TypeScript` `Node.js` `Scalability`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/parkfinder?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/parkfinder)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/parkfinder?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/parkfinder/network)

</td>
<td width="33%" valign="top">

#### 🌍 [CO2Track](https://github.com/ankittroy-21/CO2Track)
Real-time carbon footprint tracker — because the planet deserves good code too.

`JavaScript` `Vercel`

[![Live](https://img.shields.io/badge/Live-co2track-2ECC71?style=flat-square)](https://co-2-track.vercel.app)
[![Stars](https://img.shields.io/github/stars/ankittroy-21/CO2Track?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/CO2Track)

</td>
</tr>
<tr>
<td width="33%" valign="top">

#### ♾ [Algo-Infinity-Verse](https://github.com/ankittroy-21/Algo-Infinity-Verse)
DSA learning universe — algorithms visualized & explained interactively.

`HTML` `CSS` `JavaScript`

[![Live](https://img.shields.io/badge/Live-Demo-2ECC71?style=flat-square)](https://algo-infinity-verse.vercel.app)
[![Stars](https://img.shields.io/github/stars/ankittroy-21/Algo-Infinity-Verse?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/Algo-Infinity-Verse)

</td>
<td width="33%" valign="top">

#### ☕ [Learnovate](https://github.com/ankittroy-21/Learnovate)
Java + DSA learning repo from the Learnovate bootcamp — 7 stars, structured, open, and growing.

`Java` `DSA`

[![Stars](https://img.shields.io/github/stars/ankittroy-21/Learnovate?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/Learnovate)
[![Forks](https://img.shields.io/github/forks/ankittroy-21/Learnovate?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/Learnovate/network)

</td>
<td width="33%" valign="top">

#### 🎓 [LecturePulse](https://github.com/ankittroy-21/LecturePulse)
Real-time lecture engagement platform — keeping students locked in, live.

`JavaScript` `Node.js`

[![Live](https://img.shields.io/badge/Live-lecturepulse-2ECC71?style=flat-square)](https://lecturepulse.vercel.app)
[![Stars](https://img.shields.io/github/stars/ankittroy-21/LecturePulse?style=flat-square&color=2ECC71&labelColor=0d1117)](https://github.com/ankittroy-21/LecturePulse)

</td>
</tr>
<tr>
<td width="33%" valign="top">

#### ☸️ [kuberef](https://github.com/ankittroy-21/kuberef)
Kubernetes reference PyPI package — for devs who live in the terminal. Stop googling `kubectl` syntax.

`Python` `PyPI` `Kubernetes` `CLI`

[![PyPI](https://img.shields.io/pypi/v/kuberef?style=flat-square&color=2ECC71&labelColor=0d1117&logo=pypi)](https://pypi.org/project/kuberef/)
[![Downloads](https://img.shields.io/pypi/dm/kuberef?style=flat-square&color=ff9f43&labelColor=0d1117&logo=pypi)](https://pypi.org/project/kuberef/)

</td>
<td width="33%" valign="top">

</td>
<td width="33%" valign="top">

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

[![GitHub](https://img.shields.io/badge/GitHub-@ankittroy--21-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ankittroy-21)
[![Telegram](https://img.shields.io/badge/Telegram-@itz__oxi-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/itz_oxi)

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
  <rect width="680" height="54" rx="10" fill="#060d16"/>
  <rect x="0" y="0" width="680" height="1" fill="url(#footer-grad)"/>
  <text x="340" y="22" font-family="monospace" font-size="12" fill="#8b949e" text-anchor="middle">ankittroy-21@github:~$</text>
  <text x="340" y="42" font-family="monospace" font-size="13" fill="#00FF87" text-anchor="middle">echo "I don't sleep. I ship." &amp;&amp; git push origin main</text>
  <rect x="0" y="53" width="680" height="1" fill="url(#footer-grad)"/>
</svg>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ankittroy-21&color=00FF87&style=flat-square&label=Visitors)

</div>

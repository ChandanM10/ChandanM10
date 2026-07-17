<!-- ═══════════════════════════════════════════════════════════════════════════
     🚀 CHANDAN MAHATO — SELF-CONTAINED ANIMATED GITHUB PROFILE README
     Everything inlined. No external image files needed.
     ═══════════════════════════════════════════════════════════════════════════ -->

<!-- ═══ 3D ANIMATED GITHUB-STYLE HERO (inline SVG) ═══ -->
<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/212747919-84b68444-0d81-46db-a338-7ec50e9dd4cd.gif" width="100%" alt="Header Animation"/>

<br/>

<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="340" viewBox="0 0 1000 340" font-family="'Fira Code', monospace">
  <defs>
    <linearGradient id="ghBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a0e1a"/>
      <stop offset="50%" stop-color="#1e1b4b"/>
      <stop offset="100%" stop-color="#0a0e1a"/>
    </linearGradient>
    <linearGradient id="ghNameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="50%" stop-color="#38bdf8"/>
      <stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
    <radialGradient id="ghGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#22d3ee" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#0f172a" stop-opacity="0"/>
    </radialGradient>
    <filter id="ghBlur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2"/>
    </filter>
  </defs>

  <rect width="1000" height="340" fill="url(#ghBg)"/>

  <!-- Center glow halo -->
  <ellipse cx="500" cy="170" rx="350" ry="140" fill="url(#ghGlow)"/>

  <!-- ═══ Outer rotating ring (counter-clockwise) ═══ -->
  <g transform="translate(500, 170)">
    <circle r="120" fill="none" stroke="#22d3ee" stroke-width="1" stroke-dasharray="3 6" opacity="0.5">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="30s" repeatCount="indefinite"/>
    </circle>
    <circle r="100" fill="none" stroke="#a78bfa" stroke-width="0.8" stroke-dasharray="1 4" opacity="0.6">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="22s" repeatCount="indefinite"/>
    </circle>

    <!-- 6 orbital dots -->
    <g>
      <circle cx="120" cy="0" r="4" fill="#22d3ee"/>
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="12s" repeatCount="indefinite"/>
    </g>
    <g>
      <circle cx="0" cy="-110" r="3" fill="#38bdf8"/>
      <animateTransform attributeName="transform" type="rotate" from="45" to="405" dur="14s" repeatCount="indefinite"/>
    </g>
    <g>
      <circle cx="-100" cy="0" r="3.5" fill="#a78bfa"/>
      <animateTransform attributeName="transform" type="rotate" from="90" to="450" dur="16s" repeatCount="indefinite"/>
    </g>
    <g>
      <circle cx="0" cy="95" r="3" fill="#22d3ee"/>
      <animateTransform attributeName="transform" type="rotate" from="135" to="495" dur="13s" repeatCount="indefinite"/>
    </g>
    <g>
      <circle cx="85" cy="85" r="2.5" fill="#7dd3fc"/>
      <animateTransform attributeName="transform" type="rotate" from="180" to="540" dur="15s" repeatCount="indefinite"/>
    </g>
    <g>
      <circle cx="-85" cy="-85" r="2.5" fill="#a78bfa"/>
      <animateTransform attributeName="transform" type="rotate" from="225" to="585" dur="17s" repeatCount="indefinite"/>
    </g>

    <!-- ═══ 3D GitHub-style Octocat mark (stylized, hand-drawn) ═══ -->
    <!-- Outer hex shape (3D bevel effect) -->
    <polygon points="0,-70 60,-35 60,35 0,70 -60,35 -60,-35"
             fill="#0f172a" stroke="url(#ghNameGrad)" stroke-width="2"/>
    <polygon points="0,-70 60,-35 0,0 -60,-35"
             fill="#1e1b4b" opacity="0.8"/>
    <!-- Inner GitHub-like cat silhouette (simplified) -->
    <g fill="url(#ghNameGrad)">
      <!-- Head -->
      <ellipse cx="0" cy="-5" rx="22" ry="20"/>
      <!-- Ears -->
      <polygon points="-22,-18 -28,-32 -14,-25"/>
      <polygon points="22,-18 28,-32 14,-25"/>
      <!-- Eyes -->
      <ellipse cx="-8" cy="-8" rx="2.5" ry="3" fill="#0a0e1a"/>
      <ellipse cx="8" cy="-8" rx="2.5" ry="3" fill="#0a0e1a"/>
      <!-- Nose -->
      <polygon points="0,2 -3,5 3,5" fill="#0a0e1a"/>
      <!-- Body/tail curve -->
      <path d="M-15,15 Q-20,25 -15,30 Q0,33 15,30 Q20,25 15,15 Z" fill="url(#ghNameGrad)"/>
      <!-- Tail -->
      <path d="M15,20 Q30,18 32,5" fill="none" stroke="url(#ghNameGrad)" stroke-width="3" stroke-linecap="round"/>
    </g>

    <!-- Pulsing center glow -->
    <circle r="65" fill="#22d3ee" opacity="0.15">
      <animate attributeName="r" values="60;75;60" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.1;0.25;0.1" dur="3s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- ═══ Floating particles (anti-gravity) ═══ -->
  <circle cx="100" cy="280" r="2.5" fill="#22d3ee">
    <animate attributeName="cy" values="280;40;280" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="290" r="2" fill="#a78bfa">
    <animate attributeName="cy" values="290;50;290" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="850" cy="285" r="2.5" fill="#38bdf8">
    <animate attributeName="cy" values="285;45;285" dur="6.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="6.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="920" cy="295" r="2" fill="#22d3ee">
    <animate attributeName="cy" values="295;55;295" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;0" dur="8s" repeatCount="indefinite"/>
  </circle>

  <!-- ═══ Name overlay ═══ -->
  <text x="500" y="290" font-size="34" font-weight="bold"
        fill="url(#ghNameGrad)" text-anchor="middle" letter-spacing="3">
    CHANDAN MAHATO
    <animate attributeName="opacity" values="0.85;1;0.85" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="500" y="318" font-size="12" fill="#94a3b8" text-anchor="middle" letter-spacing="6">
    AI · ML · DATA SCIENCE · DEVELOPER
  </text>
</svg>

</div>

<br/>

<!-- ═══ TYPING DISPLAY (dynamic service — universally accepted) ═══ -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=2800&pause=800&color=22D3EE&center=true&vCenter=true&random=false&width=940&lines=Hi+There+%F0%9F%91%8B+I'm+Chandan+Mahato;AI+%26;+ML+Engineer+%7C+Developer;Building+Data-Driven+Systems;JARVIS+Creator+%F0%9F%A4%96;Turning+Data+Into+Decisions">
    <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=2800&pause=800&color=22D3EE&center=true&vCenter=true&random=false&width=940&lines=Hi+There+%F0%9F%91%8B+I'm+Chandan+Mahato;AI+%26;+ML+Engineer+%7C+Developer;Building+Data-Driven+Systems;JARVIS+Creator+%F0%9F%A4%96;Turning+Data+Into+Decisions" />
  </picture>
</p>

<br/>

<!-- ═══ 3D ANTI-GRAVITY INLINE HERO BANNER ═══ -->
<div align="center">

<svg width="100%" height="280" viewBox="0 0 1000 280" xmlns="http://www.w3.org/2000/svg" style="border-radius:20px; box-shadow:0 15px 40px rgba(0,0,0,0.4); border:2px solid #22d3ee;">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f172a"/>
      <stop offset="50%" stop-color="#1e1b4b"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="50%" stop-color="#38bdf8"/>
      <stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.6"/>
      <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.4"/>
    </filter>
  </defs>

  <rect width="1000" height="280" fill="url(#bgGrad)"/>

  <path d="M0,140 Q250,80 500,140 T1000,140" stroke="#22d3ee" stroke-width="1.5" fill="none" opacity="0.4">
    <animate attributeName="d" dur="6s" repeatCount="indefinite"
      values="M0,140 Q250,80 500,140 T1000,140;
              M0,140 Q250,200 500,140 T1000,140;
              M0,140 Q250,80 500,140 T1000,140"/>
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="4s" repeatCount="indefinite"/>
  </path>
  <path d="M0,180 Q250,120 500,180 T1000,180" stroke="#a78bfa" stroke-width="1.2" fill="none" opacity="0.3">
    <animate attributeName="d" dur="8s" repeatCount="indefinite"
      values="M0,180 Q250,220 500,180 T1000,180;
              M0,180 Q250,120 500,180 T1000,180;
              M0,180 Q250,220 500,180 T1000,180"/>
  </path>

  <circle cx="100" cy="50" r="3" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="220" r="2.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="220;200;220" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="780" cy="60" r="3" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="60;35;60" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="900" cy="200" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="200;180;200" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="40" r="2" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;20;40" dur="5.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="5.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="240" r="2.5" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="240;215;240" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="4.5s" repeatCount="indefinite"/>
  </circle>

  <text x="500" y="115" font-family="Fira Code, monospace" font-size="48" font-weight="bold"
        fill="url(#textGrad)" text-anchor="middle" filter="url(#depth3d)">
    CHANDAN MAHATO
    <animate attributeName="opacity" values="0.85;1;0.85" dur="3s" repeatCount="indefinite"/>
  </text>

  <text x="500" y="165" font-family="Fira Code, monospace" font-size="18"
        fill="#94a3b8" text-anchor="middle" letter-spacing="3">
    <tspan>
      AI · ML ENGINEER · DEVELOPER
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2.5s" repeatCount="indefinite"/>
    </tspan>
  </text>

  <text x="500" y="210" font-family="Fira Code, monospace" font-size="14"
        fill="#22d3ee" text-anchor="middle" opacity="0.9">
    ⚡ Turning data into decisions that matter
  </text>

  <line x1="200" y1="245" x2="800" y2="245" stroke="#22d3ee" stroke-width="1" opacity="0.3">
    <animate attributeName="x1" values="200;400;200" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="800;600;800" dur="4s" repeatCount="indefinite"/>
  </line>
</svg>

</div>

<br/>

<div align="center">

<svg width="100%" height="40" viewBox="0 0 1000 40" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20" stroke="#22d3ee" stroke-width="2" fill="none" opacity="0.6">
    <animate attributeName="d" dur="4s" repeatCount="indefinite"
      values="M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20;
              M0,20 Q125,35 250,20 T500,20 T750,20 T1000,20;
              M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20"/>
  </path>
  <circle r="4" fill="#22d3ee">
    <animateMotion dur="4s" repeatCount="indefinite"
      path="M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20"/>
  </circle>
</svg>

</div>

---

<!-- ═══ HERO INTRO BLOCK ═══ -->
<div align="center">

<h2>🚀 Data Enthusiast | Developer | <span style="color:#22d3ee;">AI/ML Engineer</span></h2>

<p>
  <b>Building</b> predictive systems · data pipelines · real-world AI solutions<br/>
  <b style="color:#22d3ee;">Turning data into decisions that matter.</b>
</p>

</div>

---

## 👋 About Me

### 🎯 What I Do

<table>
<tr>
<td width="60">🔭</td>
<td><b>Currently Working On:</b> JARVIS — an AI-powered voice operating system with memory, automation & real-time command execution 🤖</td>
</tr>
<tr>
<td width="60">🤝</td>
<td><b>Looking For:</b> Data Scientist · ML Engineer · AI Developer roles</td>
</tr>
<tr>
<td width="60">🌱</td>
<td><b>Currently Learning:</b> Advanced Deep Learning · LLMs · Multi-modal AI</td>
</tr>
<tr>
<td width="60">💬</td>
<td><b>Ask Me About:</b> Python · Data Science · Machine Learning · SQL · AI Automation</td>
</tr>
<tr>
<td width="60">⚡</td>
<td><b>Fun Fact:</b> I built my own JARVIS — yes, the Iron Man one, but smarter 😎</td>
</tr>
<tr>
<td width="60">💻</td>
<td><b>All Projects:</b> Available on GitHub — explore below ⬇️</td>
</tr>
<tr>
<td width="60">📫</td>
<td><b>Contact:</b> itssinghchandan10@gmail.com</td>
</tr>
<tr>
<td width="60">🌐</td>
<td><b>Portfolio:</b> <a href="https://chandan-mahato-portfolio-website.vercel.app/">chandan-mahato-portfolio-website.vercel.app</a></td>
</tr>
</table>

---

<!-- ═══ SOCIAL LINKS (inline SVG badges) ═══ -->
<div align="center" style="margin:25px 0;">

<a href="https://github.com/ChandanM10"><svg xmlns="http://www.w3.org/2000/svg" width="110" height="32" viewBox="0 0 110 32"><rect width="110" height="32" rx="6" fill="#0f172a" stroke="#ffffff" stroke-width="1.5"/><circle cx="16" cy="16" r="4" fill="#ffffff"/><text x="30" y="21" font-family="monospace" font-size="13" font-weight="bold" fill="#ffffff">GitHub</text></svg></a>
&nbsp;
<a href="https://linkedin.com/in/chandan-mahato-6a484b279"><svg xmlns="http://www.w3.org/2000/svg" width="110" height="32" viewBox="0 0 110 32"><rect width="110" height="32" rx="6" fill="#0f172a" stroke="#0A66C2" stroke-width="1.5"/><circle cx="16" cy="16" r="4" fill="#0A66C2"/><text x="30" y="21" font-family="monospace" font-size="13" font-weight="bold" fill="#0A66C2">LinkedIn</text></svg></a>
&nbsp;
<a href="mailto:chandanmahato7975@gmail.com"><svg xmlns="http://www.w3.org/2000/svg" width="110" height="32" viewBox="0 0 110 32"><rect width="110" height="32" rx="6" fill="#0f172a" stroke="#EA4335" stroke-width="1.5"/><circle cx="16" cy="16" r="4" fill="#EA4335"/><text x="30" y="21" font-family="monospace" font-size="13" font-weight="bold" fill="#EA4335">Email</text></svg></a>
&nbsp;
<a href="https://chandan-mahato-portfolio-website.vercel.app/"><svg xmlns="http://www.w3.org/2000/svg" width="111" height="32" viewBox="0 0 111 32"><rect width="111" height="32" rx="6" fill="#0f172a" stroke="#22d3ee" stroke-width="1.5"/><circle cx="16" cy="16" r="4" fill="#22d3ee"/><text x="30" y="21" font-family="monospace" font-size="13" font-weight="bold" fill="#22d3ee">Portfolio</text></svg></a>

</div>

---

## 📊 Quick Stats

<table width="100%" cellspacing="10">
<tr>

<td align="center" style="background:#0f172a; padding:20px; border-radius:16px; border:1.5px solid rgba(34,211,238,0.4);">
<h2 style="color:#22d3ee; margin:0;">1+</h2>
<p style="color:#94a3b8; font-size:0.9em;">Years Experience</p>
</td>

<td align="center" style="background:#0f172a; padding:20px; border-radius:16px; border:1.5px solid rgba(167,139,250,0.4);">
<h2 style="color:#a78bfa; margin:0;">10+</h2>
<p style="color:#94a3b8; font-size:0.9em;">Projects Shipped</p>
</td>

<td align="center" style="background:#0f172a; padding:20px; border-radius:16px; border:1.5px solid rgba(56,189,248,0.4);">
<h2 style="color:#38bdf8; margin:0;">15+</h2>
<p style="color:#94a3b8; font-size:0.9em;">Tools Mastered</p>
</td>

<td align="center" style="background:#0f172a; padding:20px; border-radius:16px; border:1.5px solid rgba(34,211,238,0.4);">
<h2 style="color:#22d3ee; margin:0;">∞</h2>
<p style="color:#94a3b8; font-size:0.9em;">AI · Analytics · Automation</p>
</td>

</tr>
</table>

---

## 🧠 Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,tensorflow,sklearn,pandas,mysql,aws,docker,flask,git,github,vscode,linux" alt="Tech Stack"/>
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white" alt="XGBoost"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
</div>

---

## 🚀 Featured Projects

<table width="100%" cellspacing="15">

<!-- ROW 1 — JARVIS + ClipBoat.ai -->
<tr>

<td width="50%" valign="top" style="background:#0f172a; padding:18px; border-radius:18px; border:1.5px solid rgba(34,211,238,0.35);">
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">

<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%"   stop-color="#0a0e1a"/>
    <stop offset="50%"  stop-color="#0f172a"/>
    <stop offset="100%" stop-color="#1e1b4b"/>
  </linearGradient>
  <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   stop-color="#22d3ee"/>
    <stop offset="100%" stop-color="#a78bfa"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.5"/>
    <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.3"/>
  </filter>
</defs>

  <rect width="800" height="320" fill="url(#bg)" rx="14"/>
  
  <circle cx="100" cy="50" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="80;60;80" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="40" r="1.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;25;40" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="280" r="1.5" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="280;260;280" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="290" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="290;270;290" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>


  <!-- Title -->
  <text x="400" y="40" font-family="'Fira Code',monospace" font-size="20" font-weight="bold"
        fill="url(#accent)" text-anchor="middle" filter="url(#depth3d)" letter-spacing="2">
    JARVIS · AI VOICE OS
  </text>
  <text x="400" y="62" font-family="'Fira Code',monospace" font-size="11" fill="#94a3b8"
        text-anchor="middle" letter-spacing="3">VOICE · MEMORY · AUTOMATION</text>

  <!-- Arc reactor core -->
  <g transform="translate(400, 180)">
    <!-- Outer rotating ring -->
    <circle r="80" fill="none" stroke="#22d3ee" stroke-width="1" opacity="0.4">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="20s" repeatCount="indefinite"/>
    </circle>
    <circle r="65" fill="none" stroke="#a78bfa" stroke-width="1.5" stroke-dasharray="4 8" opacity="0.6">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="15s" repeatCount="indefinite"/>
    </circle>
    <!-- Inner ring with tick marks -->
    <circle r="50" fill="none" stroke="#22d3ee" stroke-width="0.8" opacity="0.7"/>
    <circle r="40" fill="#0f172a" stroke="#38bdf8" stroke-width="1.2"/>
    <!-- 8 triangular coil segments -->
    <g filter="url(#glow)">
      <polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(0)"/><polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(45)"/><polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(90)"/><polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(135)"/><polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(180)"/><polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(225)"/><polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(270)"/><polygon points="0,-35 6,-25 -6,-25" fill="#22d3ee" transform="rotate(315)"/>
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="8s" repeatCount="indefinite"/>
    </g>
    <!-- Center glowing core -->
    <circle r="22" fill="url(#accent)" filter="url(#glow)">
      <animate attributeName="r" values="20;26;20" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
    </circle>
    <text y="6" font-family="'Fira Code',monospace" font-size="11" font-weight="bold"
          fill="#0a0e1a" text-anchor="middle">J.A.R.V.I.S</text>
  </g>

  <!-- Sound wave bars at bottom -->
  <g transform="translate(280, 290)">
    <rect x="0" y="0" width="6" height="20" fill="#22d3ee" rx="2"><animate attributeName="height" values="20;6;20" dur="0.8s" begin="0.0s" repeatCount="indefinite"/><animate attributeName="y" values="0;3;0" dur="0.8s" begin="0.0s" repeatCount="indefinite"/></rect><rect x="22" y="0" width="6" height="35" fill="#22d3ee" rx="2"><animate attributeName="height" values="35;11;35" dur="0.8s" begin="0.08s" repeatCount="indefinite"/><animate attributeName="y" values="0;5;0" dur="0.8s" begin="0.08s" repeatCount="indefinite"/></rect><rect x="44" y="0" width="6" height="28" fill="#22d3ee" rx="2"><animate attributeName="height" values="28;9;28" dur="0.8s" begin="0.16s" repeatCount="indefinite"/><animate attributeName="y" values="0;4;0" dur="0.8s" begin="0.16s" repeatCount="indefinite"/></rect><rect x="66" y="0" width="6" height="40" fill="#22d3ee" rx="2"><animate attributeName="height" values="40;13;40" dur="0.8s" begin="0.24s" repeatCount="indefinite"/><animate attributeName="y" values="0;6;0" dur="0.8s" begin="0.24s" repeatCount="indefinite"/></rect><rect x="88" y="0" width="6" height="25" fill="#22d3ee" rx="2"><animate attributeName="height" values="25;8;25" dur="0.8s" begin="0.32s" repeatCount="indefinite"/><animate attributeName="y" values="0;4;0" dur="0.8s" begin="0.32s" repeatCount="indefinite"/></rect><rect x="110" y="0" width="6" height="38" fill="#22d3ee" rx="2"><animate attributeName="height" values="38;12;38" dur="0.8s" begin="0.4s" repeatCount="indefinite"/><animate attributeName="y" values="0;6;0" dur="0.8s" begin="0.4s" repeatCount="indefinite"/></rect><rect x="132" y="0" width="6" height="30" fill="#22d3ee" rx="2"><animate attributeName="height" values="30;10;30" dur="0.8s" begin="0.48s" repeatCount="indefinite"/><animate attributeName="y" values="0;5;0" dur="0.8s" begin="0.48s" repeatCount="indefinite"/></rect><rect x="154" y="0" width="6" height="22" fill="#22d3ee" rx="2"><animate attributeName="height" values="22;7;22" dur="0.8s" begin="0.56s" repeatCount="indefinite"/><animate attributeName="y" values="0;3;0" dur="0.8s" begin="0.56s" repeatCount="indefinite"/></rect><rect x="176" y="0" width="6" height="36" fill="#22d3ee" rx="2"><animate attributeName="height" values="36;12;36" dur="0.8s" begin="0.64s" repeatCount="indefinite"/><animate attributeName="y" values="0;6;0" dur="0.8s" begin="0.64s" repeatCount="indefinite"/></rect><rect x="198" y="0" width="6" height="28" fill="#22d3ee" rx="2"><animate attributeName="height" values="28;9;28" dur="0.8s" begin="0.72s" repeatCount="indefinite"/><animate attributeName="y" values="0;4;0" dur="0.8s" begin="0.72s" repeatCount="indefinite"/></rect>
  </g>
</svg>

</div>
<h3 align="center">🤖 JARVIS_IS_LISTENING</h3>
<p align="center"><i>AI-Powered Voice Operating System</i></p>
<p align="center">Built my own AI-powered <b>JARVIS operating system</b> capable of voice interaction, intelligent assistance, task automation, memory handling, and real-time command execution.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/AI-Voice_Assistant-22d3ee?style=flat-square"/>
  <img src="https://img.shields.io/badge/Automation-FF6F00?style=flat-square"/>
</p>
<p align="center"><a href="https://github.com/ChandanM10?tab=repositories"><b>→ View Project</b></a></p>
</td>

<td width="50%" valign="top" style="background:#0f172a; padding:18px; border-radius:18px; border:1.5px solid rgba(167,139,250,0.35);">
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">

<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%"   stop-color="#0a0e1a"/>
    <stop offset="50%"  stop-color="#0f172a"/>
    <stop offset="100%" stop-color="#1e1b4b"/>
  </linearGradient>
  <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   stop-color="#22d3ee"/>
    <stop offset="100%" stop-color="#a78bfa"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.5"/>
    <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.3"/>
  </filter>
</defs>

  <rect width="800" height="320" fill="url(#bg)" rx="14"/>
  
  <circle cx="100" cy="50" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="80;60;80" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="40" r="1.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;25;40" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="280" r="1.5" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="280;260;280" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="290" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="290;270;290" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>


  <text x="400" y="40" font-family="'Fira Code',monospace" font-size="20" font-weight="bold"
        fill="url(#accent)" text-anchor="middle" filter="url(#depth3d)" letter-spacing="2">
    ClipBoat · AI
  </text>
  <text x="400" y="62" font-family="'Fira Code',monospace" font-size="11" fill="#94a3b8"
        text-anchor="middle" letter-spacing="3">CLIP · CAPTION · SCHEDULE</text>

  <!-- Long-form video (left side) -->
  <g transform="translate(80, 120)">
    <rect width="180" height="110" rx="8" fill="#1e1b4b" stroke="#a78bfa" stroke-width="1.5"/>
    <text x="90" y="50" font-family="'Fira Code',monospace" font-size="12" fill="#a78bfa" text-anchor="middle">▶ LONG VIDEO</text>
    <text x="90" y="75" font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8" text-anchor="middle">45:00 min</text>
    <!-- Progress bar -->
    <rect x="20" y="90" width="140" height="4" rx="2" fill="#22d3ee" opacity="0.3"/>
    <rect x="20" y="90" width="80" height="4" rx="2" fill="#22d3ee">
      <animate attributeName="width" values="40;120;40" dur="6s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- Arrow + clip scissors in middle -->
  <g transform="translate(290, 175)">
    <text font-family="'Fira Code',monospace" font-size="36" fill="#22d3ee" text-anchor="middle" filter="url(#glow)">✂</text>
    <text y="40" font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8" text-anchor="middle">AI CLIP</text>
    <line x1="-30" y1="20" x2="30" y2="20" stroke="#22d3ee" stroke-width="1.5" stroke-dasharray="3 3">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="0.6s" repeatCount="indefinite"/>
    </line>
  </g>

  <!-- Short clips (right side) — 3 stacked mini videos -->
  <g transform="translate(360, 110)">
    <g>
      <rect width="180" height="32" rx="6" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
      <text x="15" y="22" font-family="'Fira Code',monospace" font-size="11" fill="#22d3ee">CLIP 1 · 0:30</text>
      <circle cx="165" cy="16" r="4" fill="#27c93f"/>
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite"/>
    </g>
    <g transform="translate(0, 42)">
      <rect width="180" height="32" rx="6" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
      <text x="15" y="22" font-family="'Fira Code',monospace" font-size="11" fill="#22d3ee">CLIP 2 · 0:45</text>
      <circle cx="165" cy="16" r="4" fill="#27c93f"/>
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" begin="0.4s" repeatCount="indefinite"/>
    </g>
    <g transform="translate(0, 84)">
      <rect width="180" height="32" rx="6" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
      <text x="15" y="22" font-family="'Fira Code',monospace" font-size="11" fill="#22d3ee">CLIP 3 · 0:25</text>
      <circle cx="165" cy="16" r="4" fill="#27c93f"/>
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" begin="0.8s" repeatCount="indefinite"/>
    </g>
  </g>

  <!-- Social platform badges -->
  <g transform="translate(560, 120)">
    <rect width="40" height="40" rx="8" fill="none" stroke="#E1306C" stroke-width="1.5"/>
    <text x="20" y="28" font-family="'Fira Code',monospace" font-size="20" fill="#E1306C" text-anchor="middle">⬢</text>
    <text x="20" y="58" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">INSTA</text>
  </g>
  <g transform="translate(560, 180)">
    <rect width="40" height="40" rx="8" fill="none" stroke="#1877F2" stroke-width="1.5"/>
    <text x="20" y="28" font-family="'Fira Code',monospace" font-size="20" fill="#1877F2" text-anchor="middle">f</text>
    <text x="20" y="58" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">FB</text>
  </g>

  <!-- Schedule clock bottom -->
  <g transform="translate(400, 280)">
    <circle r="18" fill="none" stroke="#22d3ee" stroke-width="1.5"/>
    <line x1="0" y1="0" x2="0" y2="-12" stroke="#22d3ee" stroke-width="1.5">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="4s" repeatCount="indefinite"/>
    </line>
    <line x1="0" y1="0" x2="9" y2="0" stroke="#a78bfa" stroke-width="1"/>
    <text y="40" font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8" text-anchor="middle">AUTO-SCHEDULED</text>
  </g>
</svg>

</div>
<h3 align="center">🎬 ClipBoat.ai</h3>
<p align="center"><i>AI Social Media Auto-Clipping</i></p>
<p align="center">Automatically <b>clips, captions, and schedules</b> content for Instagram & Facebook from long-form videos using official <b>Meta APIs</b>. End-to-end content pipeline.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Meta_APIs-Instagram-FF6F00?style=flat-square&logo=instagram&logoColor=white"/>
  <img src="https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white"/>
  <img src="https://img.shields.io/badge/AI-Auto_Clip-a78bfa?style=flat-square"/>
</p>
<p align="center"><a href="https://github.com/ChandanM10?tab=repositories"><b>→ View Project</b></a></p>
</td>

</tr>

<!-- ROW 2 — Hand Gesture + Fraud Detection -->
<tr>

<td width="50%" valign="top" style="background:#0f172a; padding:18px; border-radius:18px; border:1.5px solid rgba(56,189,248,0.35);">
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">

<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%"   stop-color="#0a0e1a"/>
    <stop offset="50%"  stop-color="#0f172a"/>
    <stop offset="100%" stop-color="#1e1b4b"/>
  </linearGradient>
  <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   stop-color="#22d3ee"/>
    <stop offset="100%" stop-color="#a78bfa"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.5"/>
    <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.3"/>
  </filter>
</defs>

  <rect width="800" height="320" fill="url(#bg)" rx="14"/>
  
  <circle cx="100" cy="50" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="80;60;80" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="40" r="1.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;25;40" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="280" r="1.5" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="280;260;280" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="290" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="290;270;290" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>


  <text x="400" y="40" font-family="'Fira Code',monospace" font-size="20" font-weight="bold"
        fill="url(#accent)" text-anchor="middle" filter="url(#depth3d)" letter-spacing="2">
    HAND GESTURE CONTROLLER
  </text>
  <text x="400" y="62" font-family="'Fira Code',monospace" font-size="11" fill="#94a3b8"
        text-anchor="middle" letter-spacing="3">WEBCAM · MEDIAPIPE · PYTHON</text>

  <!-- Webcam frame -->
  <g transform="translate(80, 100)">
    <rect width="240" height="180" rx="10" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1.5"/>
    <!-- Camera dot -->
    <circle cx="220" cy="20" r="4" fill="#ff5f56">
      <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <text x="12" y="20" font-family="'Fira Code',monospace" font-size="10" fill="#22d3ee">● LIVE CAM</text>

    <!-- Simplified hand outline with tracking dots -->
    <g transform="translate(120, 90)" stroke="#22d3ee" stroke-width="1.2" fill="none">
      <!-- Palm -->
      <ellipse cx="0" cy="20" rx="28" ry="35" opacity="0.5"/>
      <!-- 5 fingers (lines from palm to tip) -->
      <line x1="-22" y1="-5" x2="-30" y2="-40"/>
      <line x1="-10" y1="-12" x2="-12" y2="-55"/>
      <line x1="0"   y1="-15" x2="0"   y2="-60"/>
      <line x1="10"  y1="-12" x2="14"  y2="-55"/>
      <line x1="22"  y1="-5" x2="30"  y2="-35"/>
      <!-- Tracking key points (21 landmarks) -->
      <g fill="#22d3ee" stroke="none" filter="url(#glow)">
        <circle cx="-22" cy="-5" r="3"/>
        <circle cx="-30" cy="-40" r="3"/>
        <circle cx="-10" cy="-12" r="3"/>
        <circle cx="-12" cy="-55" r="3"/>
        <circle cx="0" cy="-15" r="3"/>
        <circle cx="0" cy="-60" r="3"/>
        <circle cx="10" cy="-12" r="3"/>
        <circle cx="14" cy="-55" r="3"/>
        <circle cx="22" cy="-5" r="3"/>
        <circle cx="30" cy="-35" r="3"/>
        <circle cx="0" cy="20" r="4" fill="#a78bfa"/>
      </g>
      <!-- Connection lines (animated dashes) -->
      <g stroke="#a78bfa" stroke-width="0.6" stroke-dasharray="2 2" opacity="0.6">
        <line x1="-22" y1="-5" x2="-10" y2="-12"/>
        <line x1="-10" y1="-12" x2="0" y2="-15"/>
        <line x1="0" y1="-15" x2="10" y2="-12"/>
        <line x1="10" y1="-12" x2="22" y2="-5"/>
        <animate attributeName="stroke-dashoffset" from="0" to="-8" dur="0.5s" repeatCount="indefinite"/>
      </g>
      <!-- Pulse on tracking -->
      <animateTransform attributeName="transform" type="translate" values="120,90; 120,85; 120,90" dur="3s" repeatCount="indefinite" additive="sum"/>
    </g>
  </g>

  <!-- Arrow pointing to action -->
  <g transform="translate(360, 175)">
    <line x1="0" y1="0" x2="40" y2="0" stroke="#22d3ee" stroke-width="2" stroke-dasharray="3 3">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="0.8s" repeatCount="indefinite"/>
    </line>
    <polygon points="40,-6 50,0 40,6" fill="#22d3ee" filter="url(#glow)"/>
  </g>

  <!-- Action outputs (right side) -->
  <g transform="translate(450, 110)">
    <rect width="280" height="40" rx="6" fill="#1e1b4b" stroke="#27c93f" stroke-width="1"/>
    <text x="20" y="26" font-family="'Fira Code',monospace" font-size="13" fill="#27c93f">→ VOLUME UP</text>

    <g transform="translate(0, 50)">
      <rect width="280" height="40" rx="6" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
      <text x="20" y="26" font-family="'Fira Code',monospace" font-size="13" fill="#22d3ee">→ SCROLL DOWN</text>
    </g>

    <g transform="translate(0, 100)">
      <rect width="280" height="40" rx="6" fill="#1e1b4b" stroke="#a78bfa" stroke-width="1"/>
      <text x="20" y="26" font-family="'Fira Code',monospace" font-size="13" fill="#a78bfa">→ ZOOM IN</text>
    </g>
  </g>

  <!-- Bottom caption -->
  <text x="400" y="298" font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8" text-anchor="middle">
    21 hand landmarks tracked in real-time · no sensors required
  </text>
</svg>

</div>
<h3 align="center">✋ AI Virtual Hand Gesture Controller</h3>
<p align="center"><i>Control Your System With Bare Hands</i></p>
<p align="center">A fully interactive Python app where your <b>bare hand controls system actions</b>, a virtual robotic interface, or simulates movements — with only your <b>webcam</b>.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/MediaPipe-FF6F00?style=flat-square"/>
</p>
<p align="center"><a href="https://github.com/ChandanM10?tab=repositories"><b>→ View Project</b></a></p>
</td>

<td width="50%" valign="top" style="background:#0f172a; padding:18px; border-radius:18px; border:1.5px solid rgba(34,211,238,0.35);">
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">

<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%"   stop-color="#0a0e1a"/>
    <stop offset="50%"  stop-color="#0f172a"/>
    <stop offset="100%" stop-color="#1e1b4b"/>
  </linearGradient>
  <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   stop-color="#22d3ee"/>
    <stop offset="100%" stop-color="#a78bfa"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.5"/>
    <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.3"/>
  </filter>
</defs>

  <rect width="800" height="320" fill="url(#bg)" rx="14"/>
  
  <circle cx="100" cy="50" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="80;60;80" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="40" r="1.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;25;40" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="280" r="1.5" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="280;260;280" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="290" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="290;270;290" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>


  <text x="400" y="40" font-family="'Fira Code',monospace" font-size="20" font-weight="bold"
        fill="url(#accent)" text-anchor="middle" filter="url(#depth3d)" letter-spacing="2">
    FRAUD DETECTION SYSTEM
  </text>
  <text x="400" y="62" font-family="'Fira Code',monospace" font-size="11" fill="#94a3b8"
        text-anchor="middle" letter-spacing="3">REAL-TIME · TENSORFLOW · ANOMALY AI</text>

  <!-- Transaction stream (left) -->
  <g transform="translate(60, 100)">
    <text font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8">TRANSACTIONS</text>
    <g transform="translate(0, 10)"><rect width="200" height="22" rx="4" fill="#1e1b4b" stroke="#27c93f" stroke-width="0.8" opacity="0.8"/><text x="10" y="15" font-family="monospace" font-size="10" fill="#27c93f">TXN#1000</text><text x="120" y="15" font-family="monospace" font-size="10" fill="#94a3b8">$50.00</text><circle cx="185" cy="11" r="4" fill="#27c93f"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" begin="0.0s" repeatCount="indefinite"/></circle></g><g transform="translate(0, 38)"><rect width="200" height="22" rx="4" fill="#1e1b4b" stroke="#27c93f" stroke-width="0.8" opacity="0.8"/><text x="10" y="15" font-family="monospace" font-size="10" fill="#27c93f">TXN#1001</text><text x="120" y="15" font-family="monospace" font-size="10" fill="#94a3b8">$120.50</text><circle cx="185" cy="11" r="4" fill="#27c93f"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" begin="0.3s" repeatCount="indefinite"/></circle></g><g transform="translate(0, 66)"><rect width="200" height="22" rx="4" fill="#1e1b4b" stroke="#ff5f56" stroke-width="0.8" opacity="0.8"/><text x="10" y="15" font-family="monospace" font-size="10" fill="#ff5f56">TXN#1002</text><text x="120" y="15" font-family="monospace" font-size="10" fill="#94a3b8">$9999.00</text><circle cx="185" cy="11" r="4" fill="#ff5f56"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" begin="0.6s" repeatCount="indefinite"/></circle></g><g transform="translate(0, 94)"><rect width="200" height="22" rx="4" fill="#1e1b4b" stroke="#27c93f" stroke-width="0.8" opacity="0.8"/><text x="10" y="15" font-family="monospace" font-size="10" fill="#27c93f">TXN#1003</text><text x="120" y="15" font-family="monospace" font-size="10" fill="#94a3b8">$30.25</text><circle cx="185" cy="11" r="4" fill="#27c93f"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" begin="0.8999999999999999s" repeatCount="indefinite"/></circle></g><g transform="translate(0, 122)"><rect width="200" height="22" rx="4" fill="#1e1b4b" stroke="#ff5f56" stroke-width="0.8" opacity="0.8"/><text x="10" y="15" font-family="monospace" font-size="10" fill="#ff5f56">TXN#1004</text><text x="120" y="15" font-family="monospace" font-size="10" fill="#94a3b8">$5000.00</text><circle cx="185" cy="11" r="4" fill="#ff5f56"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" begin="1.2s" repeatCount="indefinite"/></circle></g>
  </g>

  <!-- Shield in center -->
  <g transform="translate(400, 180)">
    <!-- Animated pulse ring around shield -->
    <circle r="60" fill="none" stroke="#22d3ee" stroke-width="1" opacity="0.4">
      <animate attributeName="r" values="55;75;55" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;0;0.6" dur="3s" repeatCount="indefinite"/>
    </circle>
    <!-- Shield shape -->
    <path d="M0,-50 L40,-35 L40,10 Q40,40 0,55 Q-40,40 -40,10 L-40,-35 Z"
          fill="#0f172a" stroke="url(#accent)" stroke-width="2" filter="url(#depth3d)"/>
    <!-- Checkmark inside shield -->
    <path d="M-15,0 L-5,15 L20,-15" fill="none" stroke="#27c93f" stroke-width="3" stroke-linecap="round" stroke-linejoin="round">
      <animate attributeName="stroke-dasharray" from="0 60" to="60 0" dur="1.5s" repeatCount="indefinite"/>
    </path>
    <!-- Glow -->
    <circle r="5" fill="#22d3ee" filter="url(#glow)" opacity="0.8">
      <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Result labels (right) -->
  <g transform="translate(520, 120)">
    <rect width="220" height="40" rx="6" fill="#1e1b4b" stroke="#27c93f" stroke-width="1"/>
    <text x="20" y="26" font-family="'Fira Code',monospace" font-size="13" fill="#27c93f">✓ LEGITIMATE · 98.2%</text>

    <g transform="translate(0, 55)">
      <rect width="220" height="40" rx="6" fill="#1e1b4b" stroke="#ff5f56" stroke-width="1">
        <animate attributeName="opacity" values="0.7;1;0.7" dur="1s" repeatCount="indefinite"/>
      </rect>
      <text x="20" y="26" font-family="'Fira Code',monospace" font-size="13" fill="#ff5f56">⚠ FRAUD DETECTED</text>
    </g>

    <g transform="translate(0, 110)">
      <rect width="220" height="40" rx="6" fill="#1e1b4b" stroke="#27c93f" stroke-width="1"/>
      <text x="20" y="26" font-family="'Fira Code',monospace" font-size="13" fill="#27c93f">✓ LEGITIMATE · 99.1%</text>
    </g>
  </g>

  <text x="400" y="298" font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8" text-anchor="middle">
    Deep learning model scoring 5,000+ transactions/sec
  </text>
</svg>

</div>
<h3 align="center">🛡️ Fraud Detection System</h3>
<p align="center"><i>Real-time Transaction Fraud AI</i></p>
<p align="center">A deep learning-powered fraud detection system that analyzes transaction patterns in real-time and flags anomalies with high precision using TensorFlow.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
</p>
<p align="center"><a href="https://github.com/ChandanM10?tab=repositories"><b>→ View Project</b></a></p>
</td>

</tr>

<!-- ROW 3 — Employee Churn + MediaDownloader -->
<tr>

<td width="50%" valign="top" style="background:#0f172a; padding:18px; border-radius:18px; border:1.5px solid rgba(167,139,250,0.35);">
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">

<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%"   stop-color="#0a0e1a"/>
    <stop offset="50%"  stop-color="#0f172a"/>
    <stop offset="100%" stop-color="#1e1b4b"/>
  </linearGradient>
  <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   stop-color="#22d3ee"/>
    <stop offset="100%" stop-color="#a78bfa"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.5"/>
    <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.3"/>
  </filter>
</defs>

  <rect width="800" height="320" fill="url(#bg)" rx="14"/>
  
  <circle cx="100" cy="50" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="80;60;80" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="40" r="1.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;25;40" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="280" r="1.5" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="280;260;280" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="290" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="290;270;290" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>


  <text x="400" y="40" font-family="'Fira Code',monospace" font-size="20" font-weight="bold"
        fill="url(#accent)" text-anchor="middle" filter="url(#depth3d)" letter-spacing="2">
    EMPLOYEE CHURN PREDICTION
  </text>
  <text x="400" y="62" font-family="'Fira Code',monospace" font-size="11" fill="#94a3b8"
        text-anchor="middle" letter-spacing="3">XGBOOST · HR ANALYTICS · ML</text>

  <!-- Employee grid (left) -->
  <g transform="translate(60, 100)">
    <text font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8">EMPLOYEES · 24</text>
    <!-- 6x4 grid of employee icons -->
<g transform="translate(0, 15)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="0.0s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(30, 15)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="0.1s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(60, 15)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="0.2s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(90, 15)"><circle r="8" fill="#ff5f56" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="0.30000000000000004s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">!</text></g><g transform="translate(120, 15)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="0.4s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(150, 15)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="0.5s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(0, 45)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="0.6000000000000001s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(30, 45)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="0.7000000000000001s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(60, 45)"><circle r="8" fill="#ff5f56" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="0.8s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">!</text></g><g transform="translate(90, 45)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="0.9s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(120, 45)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="1.0s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(150, 45)"><circle r="8" fill="#ff5f56" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="1.1s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">!</text></g><g transform="translate(0, 75)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="1.2000000000000002s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(30, 75)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="1.3s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(60, 75)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="1.4000000000000001s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(90, 75)"><circle r="8" fill="#ff5f56" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="1.5s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">!</text></g><g transform="translate(120, 75)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="1.6s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(150, 75)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="1.7000000000000002s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(0, 105)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="1.8s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(30, 105)"><circle r="8" fill="#ff5f56" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="1.9000000000000001s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">!</text></g><g transform="translate(60, 105)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="2.0s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(90, 105)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.0s" begin="2.1s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g><g transform="translate(120, 105)"><circle r="8" fill="#ff5f56" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.5s" begin="2.2s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">!</text></g><g transform="translate(150, 105)"><circle r="8" fill="#27c93f" opacity="0.8"><animate attributeName="opacity" values="0.4;1;0.4" dur="3.0s" begin="2.3000000000000003s" repeatCount="indefinite"/></circle><text y="3" font-family="monospace" font-size="9" fill="#0a0e1a" text-anchor="middle" font-weight="bold">✓</text></g>  </g>

  <!-- Arrow indicating attrition -->
  <g transform="translate(310, 175)">
    <line x1="0" y1="0" x2="60" y2="0" stroke="#ff5f56" stroke-width="2.5" stroke-dasharray="4 3">
      <animate attributeName="stroke-dashoffset" from="0" to="-14" dur="0.8s" repeatCount="indefinite"/>
    </line>
    <polygon points="60,-7 73,0 60,7" fill="#ff5f56" filter="url(#glow)"/>
    <text y="-15" font-family="'Fira Code',monospace" font-size="10" fill="#ff5f56" text-anchor="middle">CHURN RISK</text>
  </g>

  <!-- Prediction chart (right) -->
  <g transform="translate(420, 100)">
    <text font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8">PREDICTION CONFIDENCE</text>
    <!-- Bar chart -->
<g transform="translate(0, 30)"><rect width="40" height="120" rx="3" fill="#1e1b4b"/><rect width="40" height="102" y="18" rx="3" fill="#ff5f56"><animate attributeName="height" from="0" to="102" dur="1s" begin="0.0s" fill="freeze"/><animate attributeName="y" from="120" to="18" dur="1s" begin="0.0s" fill="freeze"/></rect><text x="20" y="135" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">EMP #1034</text><text x="20" y="-5" font-family="monospace" font-size="9" fill="#ff5f56" text-anchor="middle">85%</text></g><g transform="translate(65, 30)"><rect width="40" height="120" rx="3" fill="#1e1b4b"/><rect width="40" height="74" y="46" rx="3" fill="#ffbd2e"><animate attributeName="height" from="0" to="74" dur="1s" begin="0.2s" fill="freeze"/><animate attributeName="y" from="120" to="46" dur="1s" begin="0.2s" fill="freeze"/></rect><text x="20" y="135" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">EMP #2156</text><text x="20" y="-5" font-family="monospace" font-size="9" fill="#ffbd2e" text-anchor="middle">62%</text></g><g transform="translate(130, 30)"><rect width="40" height="120" rx="3" fill="#1e1b4b"/><rect width="40" height="33" y="87" rx="3" fill="#27c93f"><animate attributeName="height" from="0" to="33" dur="1s" begin="0.4s" fill="freeze"/><animate attributeName="y" from="120" to="87" dur="1s" begin="0.4s" fill="freeze"/></rect><text x="20" y="135" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">EMP #3091</text><text x="20" y="-5" font-family="monospace" font-size="9" fill="#27c93f" text-anchor="middle">28%</text></g><g transform="translate(195, 30)"><rect width="40" height="120" rx="3" fill="#1e1b4b"/><rect width="40" height="109" y="11" rx="3" fill="#ff5f56"><animate attributeName="height" from="0" to="109" dur="1s" begin="0.6000000000000001s" fill="freeze"/><animate attributeName="y" from="120" to="11" dur="1s" begin="0.6000000000000001s" fill="freeze"/></rect><text x="20" y="135" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">EMP #4203</text><text x="20" y="-5" font-family="monospace" font-size="9" fill="#ff5f56" text-anchor="middle">91%</text></g><g transform="translate(260, 30)"><rect width="40" height="120" rx="3" fill="#1e1b4b"/><rect width="40" height="18" y="102" rx="3" fill="#27c93f"><animate attributeName="height" from="0" to="18" dur="1s" begin="0.8s" fill="freeze"/><animate attributeName="y" from="120" to="102" dur="1s" begin="0.8s" fill="freeze"/></rect><text x="20" y="135" font-family="monospace" font-size="8" fill="#94a3b8" text-anchor="middle">EMP #5187</text><text x="20" y="-5" font-family="monospace" font-size="9" fill="#27c93f" text-anchor="middle">15%</text></g>  </g>

  <text x="400" y="298" font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8" text-anchor="middle">
    XGBoost model · 92% accuracy · identifies retention drivers
  </text>
</svg>

</div>
<h3 align="center">👥 Employee Churn Prediction</h3>
<p align="center"><i>Predict Who's Likely To Leave</i></p>
<p align="center">ML model predicting employee attrition using HR analytics — identifies at-risk employees and key retention drivers with XGBoost explainability.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/XGBoost-FF6600?style=flat-square"/>
</p>
<p align="center"><a href="https://github.com/ChandanM10?tab=repositories"><b>→ View Project</b></a></p>
</td>

<td width="50%" valign="top" style="background:#0f172a; padding:18px; border-radius:18px; border:1.5px solid rgba(56,189,248,0.35);">
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">

<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%"   stop-color="#0a0e1a"/>
    <stop offset="50%"  stop-color="#0f172a"/>
    <stop offset="100%" stop-color="#1e1b4b"/>
  </linearGradient>
  <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   stop-color="#22d3ee"/>
    <stop offset="100%" stop-color="#a78bfa"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.5"/>
    <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.3"/>
  </filter>
</defs>

  <rect width="800" height="320" fill="url(#bg)" rx="14"/>
  
  <circle cx="100" cy="50" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="80;60;80" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="40" r="1.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;25;40" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="280" r="1.5" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="280;260;280" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="290" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="290;270;290" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>


  <text x="400" y="40" font-family="'Fira Code',monospace" font-size="20" font-weight="bold"
        fill="url(#accent)" text-anchor="middle" filter="url(#depth3d)" letter-spacing="2">
    MediaDownloader
  </text>
  <text x="400" y="62" font-family="'Fira Code',monospace" font-size="11" fill="#94a3b8"
        text-anchor="middle" letter-spacing="3">FAST · LIGHTWEIGHT · MULTI-PLATFORM</text>

  <!-- Source platforms (left) -->
  <g transform="translate(60, 110)">
    <text font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8">SOURCES</text>
    <g transform="translate(0, 20)">
      <rect width="60" height="60" rx="10" fill="#1e1b4b" stroke="#ff5f56" stroke-width="1.5"/>
      <text x="30" y="40" font-family="'Fira Code',monospace" font-size="24" fill="#ff5f56" text-anchor="middle">▶</text>
      <text x="30" y="78" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">YT</text>
    </g>
    <g transform="translate(80, 20)">
      <rect width="60" height="60" rx="10" fill="#1e1b4b" stroke="#E1306C" stroke-width="1.5"/>
      <text x="30" y="40" font-family="'Fira Code',monospace" font-size="20" fill="#E1306C" text-anchor="middle">⬢</text>
      <text x="30" y="78" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">IG</text>
    </g>
    <g transform="translate(0, 110)">
      <rect width="60" height="60" rx="10" fill="#1e1b4b" stroke="#1DA1F2" stroke-width="1.5"/>
      <text x="30" y="40" font-family="'Fira Code',monospace" font-size="20" fill="#1DA1F2" text-anchor="middle">𝕏</text>
      <text x="30" y="78" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">X</text>
    </g>
    <g transform="translate(80, 110)">
      <rect width="60" height="60" rx="10" fill="#1e1b4b" stroke="#1877F2" stroke-width="1.5"/>
      <text x="30" y="40" font-family="'Fira Code',monospace" font-size="20" fill="#1877F2" text-anchor="middle">f</text>
      <text x="30" y="78" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">FB</text>
    </g>
  </g>

  <!-- Big download arrow center -->
  <g transform="translate(400, 180)" filter="url(#glow)">
    <!-- Animated download arrow -->
    <g>
      <path d="M-30,-40 L-30,0 L-50,0 L0,50 L50,0 L30,0 L30,-40 Z"
            fill="url(#accent)" stroke="#22d3ee" stroke-width="2"/>
      <animateTransform attributeName="transform" type="translate"
        values="0,-8; 0,8; 0,-8" dur="1.5s" repeatCount="indefinite"/>
    </g>
    <text y="80" font-family="'Fira Code',monospace" font-size="11" fill="#22d3ee" text-anchor="middle" font-weight="bold">DOWNLOAD</text>
  </g>

  <!-- Output files (right) -->
  <g transform="translate(560, 110)">
    <text font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8">OUTPUTS</text>
    <g transform="translate(0, 20)">
      <rect width="180" height="36" rx="6" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
      <text x="15" y="22" font-family="'Fira Code',monospace" font-size="11" fill="#22d3ee">📹 video.mp4</text>
      <text x="165" y="22" font-family="'Fira Code',monospace" font-size="9" fill="#27c93f" text-anchor="end">100%</text>
    </g>
    <g transform="translate(0, 65)">
      <rect width="180" height="36" rx="6" fill="#1e1b4b" stroke="#a78bfa" stroke-width="1"/>
      <text x="15" y="22" font-family="'Fira Code',monospace" font-size="11" fill="#a78bfa">🎵 audio.mp3</text>
      <text x="165" y="22" font-family="'Fira Code',monospace" font-size="9" fill="#27c93f" text-anchor="end">100%</text>
    </g>
    <g transform="translate(0, 110)">
      <rect width="180" height="36" rx="6" fill="#1e1b4b" stroke="#38bdf8" stroke-width="1"/>
      <text x="15" y="22" font-family="'Fira Code',monospace" font-size="11" fill="#38bdf8">🖼 thumbnail.jpg</text>
      <rect x="120" y="14" width="40" height="8" rx="4" fill="#1e1b4b"/>
      <rect x="120" y="14" width="32" height="8" rx="4" fill="#38bdf8">
        <animate attributeName="width" values="0;40;0" dur="2s" repeatCount="indefinite"/>
      </rect>
    </g>
  </g>

  <text x="400" y="298" font-family="'Fira Code',monospace" font-size="10" fill="#94a3b8" text-anchor="middle">
    Web platform · supports 4+ social platforms · MP4/MP3/JPG
  </text>
</svg>

</div>
<h3 align="center">⬇️ MediaDownloader</h3>
<p align="center"><i>Web Platform For Social Media Downloads</i></p>
<p align="center">A clean web platform for <b>downloading media from social platforms</b> — fast, lightweight, and built for an end-to-end user experience.</p>
<p align="center">
  <img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Web-Platform-38bdf8?style=flat-square"/>
  <img src="https://img.shields.io/badge/Media-Downloader-22d3ee?style=flat-square"/>
</p>
<p align="center"><a href="https://github.com/ChandanM10?tab=repositories"><b>→ View Project</b></a></p>
</td>

</tr>

<!-- ROW 4 — Nepal Gov Connect (full width) -->
<tr>
<td colspan="2" valign="top" style="background:#0f172a; padding:18px; border-radius:18px; border:1.5px solid rgba(34,211,238,0.35);">
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="800" height="320" viewBox="0 0 800 320">

<defs>
  <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%"   stop-color="#0a0e1a"/>
    <stop offset="50%"  stop-color="#0f172a"/>
    <stop offset="100%" stop-color="#1e1b4b"/>
  </linearGradient>
  <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%"   stop-color="#22d3ee"/>
    <stop offset="100%" stop-color="#a78bfa"/>
  </linearGradient>
  <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="depth3d" x="-20%" y="-20%" width="140%" height="140%">
    <feDropShadow dx="3" dy="3" stdDeviation="2" flood-color="#22d3ee" flood-opacity="0.5"/>
    <feDropShadow dx="-2" dy="-2" stdDeviation="1" flood-color="#a78bfa" flood-opacity="0.3"/>
  </filter>
</defs>

  <rect width="800" height="320" fill="url(#bg)" rx="14"/>
  
  <circle cx="100" cy="50" r="2" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="50;30;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="80;60;80" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="40" r="1.5" fill="#38bdf8" filter="url(#glow)">
    <animate attributeName="cy" values="40;25;40" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;1;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="280" r="1.5" fill="#22d3ee" filter="url(#glow)">
    <animate attributeName="cy" values="280;260;280" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="650" cy="290" r="2" fill="#a78bfa" filter="url(#glow)">
    <animate attributeName="cy" values="290;270;290" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/>
  </circle>


  <text x="400" y="40" font-family="'Fira Code',monospace" font-size="20" font-weight="bold"
        fill="url(#accent)" text-anchor="middle" filter="url(#depth3d)" letter-spacing="2">
    🇳🇵 NEPAL GOV CONNECT
  </text>
  <text x="400" y="62" font-family="'Fira Code',monospace" font-size="11" fill="#94a3b8"
        text-anchor="middle" letter-spacing="3">CITIZEN ↔ GOVERNMENT · TRANSPARENCY</text>

  <!-- Citizen (left) reporting -->
  <g transform="translate(100, 130)">
    <circle r="32" fill="#1e1b4b" stroke="#22d3ee" stroke-width="2"/>
    <text y="6" font-family="'Fira Code',monospace" font-size="22" text-anchor="middle" fill="#22d3ee">👤</text>
    <text y="55" font-family="'Fira Code',monospace" font-size="11" fill="#22d3ee" text-anchor="middle">CITIZEN</text>

    <!-- Chat bubble with report -->
    <g transform="translate(50, -10)">
      <rect width="160" height="50" rx="8" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
      <polygon points="0,20 -10,30 0,40" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
      <text x="80" y="22" font-family="'Fira Code',monospace" font-size="10" fill="#22d3ee" text-anchor="middle">📝 REPORT ISSUE</text>
      <text x="80" y="38" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">Pothole on Road #5</text>
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
    </g>
  </g>

  <!-- Animated arrows (bidirectional) -->
  <g transform="translate(330, 175)">
    <line x1="0" y1="-8" x2="60" y2="-8" stroke="#22d3ee" stroke-width="2" stroke-dasharray="3 3">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="0.8s" repeatCount="indefinite"/>
    </line>
    <polygon points="60,-14 70,-8 60,-2" fill="#22d3ee" filter="url(#glow)"/>

    <line x1="70" y1="8" x2="10" y2="8" stroke="#a78bfa" stroke-width="2" stroke-dasharray="3 3">
      <animate attributeName="stroke-dashoffset" from="0" to="-12" dur="0.8s" begin="0.4s" repeatCount="indefinite"/>
    </line>
    <polygon points="10,2 0,8 10,14" fill="#a78bfa" filter="url(#glow)"/>
  </g>

  <!-- Government (right) responding -->
  <g transform="translate(700, 130)">
    <circle r="32" fill="#1e1b4b" stroke="#a78bfa" stroke-width="2"/>
    <text y="8" font-family="'Fira Code',monospace" font-size="22" text-anchor="middle" fill="#a78bfa">🏛</text>
    <text y="55" font-family="'Fira Code',monospace" font-size="11" fill="#a78bfa" text-anchor="middle">GOVERNMENT</text>

    <g transform="translate(-210, -10)">
      <rect width="160" height="50" rx="8" fill="#1e1b4b" stroke="#a78bfa" stroke-width="1"/>
      <polygon points="160,20 170,30 160,40" fill="#1e1b4b" stroke="#a78bfa" stroke-width="1"/>
      <text x="80" y="22" font-family="'Fira Code',monospace" font-size="10" fill="#a78bfa" text-anchor="middle">✓ ACTION TAKEN</text>
      <text x="80" y="38" font-family="'Fira Code',monospace" font-size="9" fill="#94a3b8" text-anchor="middle">Repair scheduled · 2 days</text>
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" begin="1s" repeatCount="indefinite"/>
    </g>
  </g>

  <!-- Stats row at bottom -->
  <g transform="translate(80, 260)">
    <rect width="180" height="40" rx="6" fill="#1e1b4b" stroke="#22d3ee" stroke-width="1"/>
    <text x="90" y="26" font-family="'Fira Code',monospace" font-size="12" fill="#22d3ee" text-anchor="middle">📊 1,240 REPORTS</text>
  </g>
  <g transform="translate(310, 260)">
    <rect width="180" height="40" rx="6" fill="#1e1b4b" stroke="#27c93f" stroke-width="1"/>
    <text x="90" y="26" font-family="'Fira Code',monospace" font-size="12" fill="#27c93f" text-anchor="middle">✓ 980 RESOLVED</text>
  </g>
  <g transform="translate(540, 260)">
    <rect width="180" height="40" rx="6" fill="#1e1b4b" stroke="#a78bfa" stroke-width="1"/>
    <text x="90" y="26" font-family="'Fira Code',monospace" font-size="12" fill="#a78bfa" text-anchor="middle">⚡ 79% EFFICIENCY</text>
  </g>
</svg>

</div>
<h3 align="center">🇳🇵 Nepal Gov Connect</h3>
<p align="center"><i>Citizen–Government Digital Bridge</i></p>
<p align="center">A platform allowing <b>citizens to report public issues and complaints</b>, enabling government authorities to <b>monitor, respond, and take action efficiently</b>. Aims to improve transparency, accountability, and public service delivery across Nepal.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Full_Stack-Web_App-22d3ee?style=flat-square"/>
  <img src="https://img.shields.io/badge/Citizen_Reporting-Live-a78bfa?style=flat-square"/>
  <img src="https://img.shields.io/badge/Civic_Tech-Nepal-FF6F00?style=flat-square"/>
</p>
<p align="center"><a href="https://github.com/ChandanM10?tab=repositories"><b>→ View Project</b></a></p>
</td>
</tr>

</table>

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=ChandanM10&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0f172a&title_color=22d3ee&icon_color=a78bfa&text_color=94a3b8" alt="Chandan's GitHub Stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChandanM10&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=22d3ee&text_color=94a3b8" alt="Top Languages"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ChandanM10&theme=tokyonight&hide_border=true&background=0f172a&ring=22d3ee&fire=a78bfa&currStreakLabel=22d3ee" alt="GitHub Streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChandanM10&theme=tokyo-night&hide_border=true&bg_color=0f172a&color=22d3ee&line=a78bfa&point=38bdf8" alt="Activity Graph" width="90%"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=ChandanM10&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="Trophies"/>

</div>

---

## 🐍 Snake Contribution Animation

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ChandanM10/ChandanM10/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ChandanM10/ChandanM10/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/ChandanM10/ChandanM10/output/github-snake-dark.svg" width="100%"/>
</picture>

</div>

---

<div align="center">

<svg width="100%" height="40" viewBox="0 0 1000 40" xmlns="http://www.w3.org/2000/svg">
  <path d="M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20" stroke="#22d3ee" stroke-width="2" fill="none" opacity="0.6">
    <animate attributeName="d" dur="4s" repeatCount="indefinite"
      values="M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20;
              M0,20 Q125,35 250,20 T500,20 T750,20 T1000,20;
              M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20"/>
  </path>
  <circle r="4" fill="#22d3ee">
    <animateMotion dur="4s" repeatCount="indefinite"
      path="M0,20 Q125,5 250,20 T500,20 T750,20 T1000,20"/>
  </circle>
</svg>

</div>

---

## 📬 Let's Connect

<div align="center">

<h3>💼 Open to <span style="color:#22d3ee;">AI / ML / Data Science</span> opportunities</h3>

<p>
  Whether it's building intelligent systems, automating workflows, or extracting insights from data —<br/>
  I'm always excited to collaborate on <b>real-world AI projects</b>.
</p>

<table>
<tr>
<td align="center" width="200">
<a href="https://linkedin.com/in/chandan-mahato-6a484b279">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/><br/>
<sub>Chandan Mahato</sub>
</a>
</td>
<td align="center" width="200">
<a href="https://chandan-mahato-portfolio-website.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-22D3EE?style=for-the-badge&logo=vercel&logoColor=black"/><br/>
<sub>Live Website</sub>
</a>
</td>
<td align="center" width="200">
<a href="mailto:itssinghchandan10@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/><br/>
<sub>itssinghchandan10@gmail.com</sub>
</a>
</td>
<td align="center" width="200">
<a href="https://github.com/ChandanM10">
<img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white"/><br/>
<sub>@ChandanM10</sub>
</a>
</td>
</tr>
</table>

</div>

<br/>

<div align="center">

<svg width="80%" height="80" viewBox="0 0 800 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22d3ee"/>
      <stop offset="50%" stop-color="#38bdf8"/>
      <stop offset="100%" stop-color="#a78bfa"/>
    </linearGradient>
  </defs>
  <text x="400" y="40" font-family="Fira Code, monospace" font-size="20" font-weight="bold"
        fill="url(#footerGrad)" text-anchor="middle">
    ⚡ Thanks for visiting — let's build something intelligent together ⚡
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  <text x="400" y="65" font-family="Fira Code, monospace" font-size="12"
        fill="#94a3b8" text-anchor="middle" opacity="0.7">
    © Chandan Mahato · AI · ML · Data Science · 2026
  </text>
</svg>

</div>



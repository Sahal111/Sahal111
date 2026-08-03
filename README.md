<!-- ============================================================
     SAHAL111 · GITHUB PROFILE README
     Author  : Sahal (X_ proff)
     Version : 3.0 — Ultra Premium Edition
     ============================================================ -->

<!-- ██████████████████████████████████████████████████████████ -->
<!--                    HERO — ANIMATED SVG BANNER              -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 280" width="100%">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0f172a"/>
      <stop offset="50%"  stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <!-- Neon glow filter -->
    <filter id="neonGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Strong glow for signature -->
    <filter id="strongGlow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <!-- Grid pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1e293b" stroke-width="0.5"/>
    </pattern>
    <!-- Particle animation gradient -->
    <radialGradient id="particleGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#38bdf8" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#6366f1" stop-opacity="0"/>
    </radialGradient>
    <!-- Cyan text gradient -->
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#38bdf8"/>
      <stop offset="50%"  stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#14b8a6"/>
    </linearGradient>
    <!-- Cyan line gradient -->
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#38bdf8" stop-opacity="0"/>
      <stop offset="30%"  stop-color="#38bdf8"/>
      <stop offset="70%"  stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#6366f1" stop-opacity="0"/>
    </linearGradient>
    <!-- Orbit gradient -->
    <linearGradient id="orbitGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#38bdf8" stop-opacity="0"/>
      <stop offset="50%"  stop-color="#38bdf8"/>
      <stop offset="100%" stop-color="#38bdf8" stop-opacity="0"/>
    </linearGradient>
  </defs>

  <!-- Base background -->
  <rect width="900" height="280" fill="url(#bgGrad)" rx="16"/>

  <!-- Grid overlay -->
  <rect width="900" height="280" fill="url(#grid)" rx="16" opacity="0.4"/>

  <!-- Floating particles -->
  <g opacity="0.6">
    <circle cx="60"  cy="40"  r="2" fill="#38bdf8">
      <animate attributeName="cy" values="40;20;40"   dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="150" cy="80"  r="1.5" fill="#6366f1">
      <animate attributeName="cy" values="80;55;80"   dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="820" cy="50"  r="2" fill="#14b8a6">
      <animate attributeName="cy" values="50;30;50"   dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="200" r="1.5" fill="#38bdf8">
      <animate attributeName="cy" values="200;180;200" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="20"  r="1" fill="#6366f1">
      <animate attributeName="cy" values="20;5;20"    dur="4.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="250" r="2" fill="#2563eb">
      <animate attributeName="cy" values="250;230;250" dur="5.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="860" cy="230" r="1.5" fill="#14b8a6">
      <animate attributeName="cy" values="230;210;230" dur="4.2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Orbit rings (decorative) -->
  <g transform="translate(820,60)" opacity="0.15">
    <ellipse cx="0" cy="0" rx="55" ry="20" fill="none" stroke="#38bdf8" stroke-width="0.8">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="8s" repeatCount="indefinite"/>
    </ellipse>
    <ellipse cx="0" cy="0" rx="35" ry="13" fill="none" stroke="#6366f1" stroke-width="0.6">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="5s" repeatCount="indefinite"/>
    </ellipse>
    <circle cx="0" cy="0" r="5" fill="#38bdf8" opacity="0.6"/>
  </g>

  <!-- Corner decorations -->
  <g filter="url(#neonGlow)">
    <path d="M 0 40 L 0 16 Q 0 0 16 0 L 40 0" fill="none" stroke="#38bdf8" stroke-width="1.5" rx="16" opacity="0.7"/>
    <path d="M 900 40 L 900 16 Q 900 0 884 0 L 860 0" fill="none" stroke="#38bdf8" stroke-width="1.5" opacity="0.7"/>
    <path d="M 0 240 L 0 264 Q 0 280 16 280 L 40 280" fill="none" stroke="#6366f1" stroke-width="1.5" opacity="0.7"/>
    <path d="M 900 240 L 900 264 Q 900 280 884 280 L 860 280" fill="none" stroke="#6366f1" stroke-width="1.5" opacity="0.7"/>
  </g>

  <!-- Name — main hero text -->
  <text x="450" y="95" text-anchor="middle" font-family="'Courier New', monospace" font-size="52"
        font-weight="900" fill="url(#textGrad)" filter="url(#neonGlow)" letter-spacing="6">
    SAHAL
    <animate attributeName="opacity" values="0;1" dur="1s" begin="0s" fill="freeze"/>
  </text>

  <!-- Subtitle -->
  <text x="450" y="130" text-anchor="middle" font-family="'Courier New', monospace" font-size="13"
        fill="#94a3b8" letter-spacing="8">
    FULLSTACK DEVELOPER  ·  ML ENGINEER  ·  INDONESIA 🇮🇩
    <animate attributeName="opacity" values="0;1" dur="1s" begin="0.3s" fill="freeze"/>
  </text>

  <!-- Divider line -->
  <line x1="150" y1="148" x2="750" y2="148" stroke="url(#lineGrad)" stroke-width="1">
    <animate attributeName="x1" values="450;150" dur="1s" begin="0.5s" fill="freeze"/>
    <animate attributeName="x2" values="450;750" dur="1s" begin="0.5s" fill="freeze"/>
  </line>

  <!-- Role tags -->
  <g font-family="'Courier New', monospace" font-size="11" fill="#38bdf8" filter="url(#neonGlow)">
    <text x="450" y="172" text-anchor="middle">
      <tspan fill="#6366f1">[ </tspan>React<tspan fill="#6366f1"> ] </tspan>
      <tspan fill="#6366f1">[ </tspan>Laravel<tspan fill="#6366f1"> ] </tspan>
      <tspan fill="#6366f1">[ </tspan>Python<tspan fill="#6366f1"> ] </tspan>
      <tspan fill="#6366f1">[ </tspan>ML<tspan fill="#6366f1"> ] </tspan>
      <tspan fill="#6366f1">[ </tspan>TypeScript<tspan fill="#6366f1"> ]</tspan>
      <animate attributeName="opacity" values="0;1" dur="0.5s" begin="1s" fill="freeze"/>
    </text>
  </g>

  <!-- Blinking cursor line -->
  <rect x="445" y="185" width="10" height="2" fill="#38bdf8">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>

  <!-- Status dot -->
  <circle cx="390" cy="215" r="5" fill="#22c55e" filter="url(#neonGlow)">
    <animate attributeName="r" values="5;7;5" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.6;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="402" y="219" font-family="'Courier New', monospace" font-size="11" fill="#94a3b8">
    Available for opportunities
  </text>

  <!-- Bottom tagline -->
  <text x="450" y="255" text-anchor="middle" font-family="'Courier New', monospace" font-size="10"
        fill="#334155" letter-spacing="3">
    BUILDING THE FUTURE · ONE COMMIT AT A TIME
  </text>
</svg>

</div>

<!-- ██████████████████████████████████████████████████████████ -->
<!--               QUICK BADGES & CTA ROW                      -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=Sahal111&style=for-the-badge&color=00ff41&labelColor=0d1117&label=PROFILE+VIEWS)](https://github.com/Sahal111)
[![GitHub Followers](https://img.shields.io/github/followers/Sahal111?style=for-the-badge&color=38bdf8&labelColor=0d1117&label=FOLLOWERS)](https://github.com/Sahal111?tab=followers)
[![GitHub Stars](https://img.shields.io/github/stars/Sahal111?style=for-the-badge&color=6366f1&labelColor=0d1117&label=TOTAL+STARS)](https://github.com/Sahal111)
[![Status](https://img.shields.io/badge/STATUS-OPEN_FOR_COLLAB-00ff41?style=for-the-badge&labelColor=0d1117)](https://github.com/Sahal111)

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                  TERMINAL SIMULATION                       -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 480" width="90%">
  <defs>
    <linearGradient id="termBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#090c10"/>
    </linearGradient>
    <filter id="termGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1e293b"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
  </defs>

  <!-- Window frame -->
  <rect width="820" height="480" fill="url(#termBg)" rx="12" stroke="#1e293b" stroke-width="1"/>

  <!-- Title bar -->
  <rect width="820" height="36" fill="url(#headerGrad)" rx="12"/>
  <rect y="24" width="820" height="12" fill="url(#headerGrad)"/>

  <!-- Traffic lights -->
  <circle cx="20" cy="18" r="6" fill="#ff5f57"/>
  <circle cx="38" cy="18" r="6" fill="#ffbd2e"/>
  <circle cx="56" cy="18" r="6" fill="#28c840"/>

  <!-- Terminal title -->
  <text x="410" y="23" text-anchor="middle" font-family="'SF Mono', 'Courier New', monospace"
        font-size="12" fill="#64748b">sahal@portfolio ~ zsh</text>

  <!-- Scanline overlay effect -->
  <rect width="820" height="480" fill="none" rx="12"
        style="background: repeating-linear-gradient(0deg,rgba(0,0,0,0.03) 0px,rgba(0,0,0,0.03) 1px,transparent 1px,transparent 2px)"/>

  <!-- Terminal content -->
  <g font-family="'SF Mono', 'Courier New', monospace" font-size="13" filter="url(#termGlow)">

    <!-- Line 1: prompt + whoami -->
    <text x="20" y="68" fill="#6366f1">sahal</text>
    <text x="64" y="68" fill="#94a3b8">@</text>
    <text x="76" y="68" fill="#38bdf8">portfolio</text>
    <text x="154" y="68" fill="#64748b"> ~ </text>
    <text x="175" y="68" fill="#22c55e">❯</text>
    <text x="190" y="68" fill="#e2e8f0"> whoami</text>

    <!-- whoami output -->
    <text x="20" y="92" fill="#94a3b8">╭─────────────────────────────────────────────────────────────────╮</text>
    <text x="20" y="110" fill="#94a3b8">│</text>
    <text x="34" y="110" fill="#38bdf8">  👤 Name   :</text>
    <text x="166" y="110" fill="#e2e8f0"> Sahal (X_ proff)</text>
    <text x="20" y="128" fill="#94a3b8">│</text>
    <text x="34" y="128" fill="#38bdf8">  🌏 Origin :</text>
    <text x="166" y="128" fill="#e2e8f0"> Indonesia 🇮🇩</text>
    <text x="20" y="146" fill="#94a3b8">│</text>
    <text x="34" y="146" fill="#38bdf8">  💼 Role   :</text>
    <text x="166" y="146" fill="#e2e8f0"> Fullstack Developer + ML Engineer</text>
    <text x="20" y="164" fill="#94a3b8">│</text>
    <text x="34" y="164" fill="#38bdf8">  🎓 Edu    :</text>
    <text x="166" y="164" fill="#e2e8f0"> Computer Science</text>
    <text x="20" y="182" fill="#94a3b8">│</text>
    <text x="34" y="182" fill="#38bdf8">  ⚡ Status :</text>
    <text x="166" y="182" fill="#22c55e"> ● Open for collab &amp; freelance</text>
    <text x="20" y="200" fill="#94a3b8">╰─────────────────────────────────────────────────────────────────╯</text>

    <!-- Line 2: prompt + skills -->
    <text x="20" y="226" fill="#6366f1">sahal</text>
    <text x="64" y="226" fill="#94a3b8">@</text>
    <text x="76" y="226" fill="#38bdf8">portfolio</text>
    <text x="154" y="226" fill="#64748b"> ~ </text>
    <text x="175" y="226" fill="#22c55e">❯</text>
    <text x="190" y="226" fill="#e2e8f0"> cat skills.json</text>

    <!-- skills output -->
    <text x="20" y="248" fill="#94a3b8">{</text>
    <text x="34" y="264" fill="#6366f1">"languages"</text>
    <text x="124" y="264" fill="#94a3b8">:</text>
    <text x="136" y="264" fill="#22c55e"> ["PHP", "Python", "JavaScript", "TypeScript"],</text>
    <text x="34" y="280" fill="#6366f1">"frontend"</text>
    <text x="118" y="280" fill="#94a3b8">:</text>
    <text x="130" y="280" fill="#22c55e"> ["React", "TailwindCSS", "HTML5", "CSS3"],</text>
    <text x="34" y="296" fill="#6366f1">"backend"</text>
    <text x="116" y="296" fill="#94a3b8">:</text>
    <text x="128" y="296" fill="#22c55e"> ["Laravel", "Node.js", "REST API"],</text>
    <text x="34" y="312" fill="#6366f1">"ml_ai"</text>
    <text x="100" y="312" fill="#94a3b8">:</text>
    <text x="112" y="312" fill="#22c55e"> ["scikit-learn", "Pandas", "Jupyter", "NumPy"],</text>
    <text x="34" y="328" fill="#6366f1">"tools"</text>
    <text x="100" y="328" fill="#94a3b8">:</text>
    <text x="112" y="328" fill="#22c55e"> ["Git", "Docker", "VS Code", "Postman", "Figma"]</text>
    <text x="20" y="344" fill="#94a3b8">}</text>

    <!-- Line 3: prompt + status -->
    <text x="20" y="368" fill="#6366f1">sahal</text>
    <text x="64" y="368" fill="#94a3b8">@</text>
    <text x="76" y="368" fill="#38bdf8">portfolio</text>
    <text x="154" y="368" fill="#64748b"> ~ </text>
    <text x="175" y="368" fill="#22c55e">❯</text>
    <text x="190" y="368" fill="#e2e8f0"> ./status --now</text>

    <!-- status output -->
    <text x="20" y="390" fill="#38bdf8">🚀</text>
    <text x="38" y="390" fill="#e2e8f0"> Building School ERP (Laravel + React)</text>
    <text x="20" y="406" fill="#6366f1">🧠</text>
    <text x="38" y="406" fill="#e2e8f0"> Exploring Deep Learning &amp; AI Engineering</text>
    <text x="20" y="422" fill="#14b8a6">📦</text>
    <text x="38" y="422" fill="#e2e8f0"> 270+ commits in 2026  ·  14 public repos</text>

    <!-- blinking cursor -->
    <text x="20" y="450" fill="#6366f1">sahal</text>
    <text x="64" y="450" fill="#94a3b8">@</text>
    <text x="76" y="450" fill="#38bdf8">portfolio</text>
    <text x="154" y="450" fill="#64748b"> ~ </text>
    <text x="175" y="450" fill="#22c55e">❯</text>
    <rect x="192" y="437" width="8" height="14" fill="#38bdf8">
      <animate attributeName="opacity" values="1;0;1" dur="1.2s" repeatCount="indefinite"/>
    </rect>
  </g>
</svg>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--             COMMAND PALETTE — RAYCAST STYLE                -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" width="80%">
  <defs>
    <linearGradient id="palBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#111827"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <linearGradient id="activeRow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1e3a5f" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#1e1b4b" stop-opacity="0.3"/>
    </linearGradient>
  </defs>

  <!-- Outer glow ring -->
  <rect x="2" y="2" width="696" height="316" rx="14" fill="none"
        stroke="url(#textGrad)" stroke-width="0.8" opacity="0.4"/>

  <!-- Window -->
  <rect width="700" height="320" rx="14" fill="url(#palBg)" stroke="#1e293b" stroke-width="1"/>

  <!-- Search input bar -->
  <rect x="16" y="16" width="668" height="44" rx="8" fill="#1e293b" stroke="#334155" stroke-width="1"/>
  <!-- Search icon -->
  <text x="36" y="44" font-size="16" fill="#64748b">⌘</text>
  <!-- Input text -->
  <text x="58" y="44" font-family="'SF Mono','Courier New',monospace" font-size="14" fill="#e2e8f0">&gt; </text>
  <text x="76" y="44" font-family="'SF Mono','Courier New',monospace" font-size="14" fill="#94a3b8">Type a command...</text>
  <!-- Keyboard hint -->
  <text x="630" y="44" font-family="'SF Mono','Courier New',monospace" font-size="11" fill="#475569">ESC</text>
  <rect x="622" y="30" width="34" height="18" rx="4" fill="none" stroke="#475569" stroke-width="1"/>

  <!-- Divider -->
  <line x1="16" y1="68" x2="684" y2="68" stroke="#1e293b" stroke-width="1"/>

  <!-- Category label -->
  <text x="24" y="88" font-family="'SF Mono','Courier New',monospace" font-size="10"
        fill="#475569" letter-spacing="2">QUICK ACTIONS</text>

  <!-- Command item 1 — ACTIVE -->
  <rect x="12" y="96" width="676" height="44" rx="6" fill="url(#activeRow)"/>
  <rect x="12" y="96" width="3" height="44" rx="2" fill="#38bdf8"/>
  <text x="30" y="113" font-size="16">👤</text>
  <text x="52" y="113" font-family="'SF Mono','Courier New',monospace" font-size="13" fill="#e2e8f0">about</text>
  <text x="52" y="130" font-family="'SF Mono','Courier New',monospace" font-size="11" fill="#64748b">View profile, skills and background</text>
  <text x="600" y="122" font-family="'SF Mono','Courier New',monospace" font-size="10" fill="#38bdf8">ENTER ↵</text>

  <!-- Command item 2 -->
  <rect x="12" y="148" width="676" height="44" rx="6" fill="#0f172a"/>
  <text x="30" y="165" font-size="16">🗂</text>
  <text x="52" y="165" font-family="'SF Mono','Courier New',monospace" font-size="13" fill="#94a3b8">projects</text>
  <text x="52" y="182" font-family="'SF Mono','Courier New',monospace" font-size="11" fill="#475569">Browse pinned repos and featured work</text>

  <!-- Command item 3 -->
  <rect x="12" y="200" width="676" height="44" rx="6" fill="#0f172a"/>
  <text x="30" y="217" font-size="16">📬</text>
  <text x="52" y="217" font-family="'SF Mono','Courier New',monospace" font-size="13" fill="#94a3b8">contact</text>
  <text x="52" y="234" font-family="'SF Mono','Courier New',monospace" font-size="11" fill="#475569">Email · LinkedIn · Instagram</text>

  <!-- Command item 4 -->
  <rect x="12" y="252" width="676" height="44" rx="6" fill="#0f172a"/>
  <text x="30" y="269" font-size="16">📊</text>
  <text x="52" y="269" font-family="'SF Mono','Courier New',monospace" font-size="13" fill="#94a3b8">stats</text>
  <text x="52" y="286" font-family="'SF Mono','Courier New',monospace" font-size="11" fill="#475569">GitHub analytics, streaks and trophies</text>

  <!-- Bottom bar -->
  <line x1="16" y1="302" x2="684" y2="302" stroke="#1e293b" stroke-width="1"/>
  <text x="24" y="316" font-family="'SF Mono','Courier New',monospace" font-size="10" fill="#334155">
    ↑↓ navigate  ·  ↵ select  ·  ⌘K to open
  </text>
  <text x="580" y="316" font-family="'SF Mono','Courier New',monospace" font-size="10" fill="#334155">
    v3.0-sahal
  </text>
</svg>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                      ABOUT ME                             -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <defs>
    <linearGradient id="divGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0f172a" stop-opacity="0"/>
      <stop offset="20%" stop-color="#38bdf8"/>
      <stop offset="50%" stop-color="#6366f1"/>
      <stop offset="80%" stop-color="#14b8a6"/>
      <stop offset="100%" stop-color="#0f172a" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#38bdf8" opacity="0.8"/>
  <text x="410" y="22" text-anchor="middle" font-family="monospace" font-size="9"
        fill="#0f172a" font-weight="bold">✦</text>
</svg>

</div>

<br/>

## 🧬 `> about --me`

<table>
<tr>
<td width="55%" valign="top">

```typescript
const sahal: Developer = {
  name:      "Sahal (X_ proff)",
  location:  "Indonesia 🇮🇩",
  role:      "Fullstack Developer",
  education: "Computer Science",

  philosophy: [
    "Code is craft, not just function",
    "Clean architecture over clever hacks",
    "Ship fast · Iterate · Improve",
  ],

  currentlyBuilding: "School ERP System",
  currentlyLearning: ["Deep Learning", "AI Engineering"],

  funFact: "I debug with console.log()  
            and I'm not ashamed 😄",

  coffee: ☕ × ∞,
  openForWork: true,
};
```

</td>
<td width="45%" valign="top">

<br/>

**🔥 Currently Focused On**

> 🚀 School ERP — Laravel + React + MySQL  
> 🧠 Deep Learning & AI Engineering  
> ⚡ Building clean, scalable fullstack apps  
> 📐 System Design & Clean Architecture  
> 🌐 Open Source contribution

<br/>

**🎯 2026 Goals**

> ✅ 300+ GitHub contributions  
> 🔲 Launch SaaS product  
> 🔲 Contribute to major OSS  
> 🔲 Land Software Engineer role  
> 🔲 Publish tech blog posts

</td>
</tr>
</table>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--           TECH STACK — SKILLICONS.DEV                     -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#6366f1" opacity="0.8"/>
</svg>

</div>

## ⚡ `> cat tech_stack.json`

<div align="center">

**`[ LANGUAGES ]`**

[![Languages](https://skillicons.dev/icons?i=php,python,js,ts,html,css&theme=dark&perline=8)](https://skillicons.dev)

**`[ FRONTEND ]`**

[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,sass,bootstrap&theme=dark&perline=8)](https://skillicons.dev)

**`[ BACKEND ]`**

[![Backend](https://skillicons.dev/icons?i=laravel,nodejs,express,php&theme=dark&perline=8)](https://skillicons.dev)

**`[ DATABASE ]`**

[![Database](https://skillicons.dev/icons?i=mysql,postgresql,sqlite,redis&theme=dark&perline=8)](https://skillicons.dev)

**`[ AI / ML ]`**

[![AI](https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark&perline=8)](https://skillicons.dev)

**`[ DEVOPS & TOOLS ]`**

[![DevOps](https://skillicons.dev/icons?i=git,github,docker,linux,nginx,vscode,postman,figma&theme=dark&perline=8)](https://skillicons.dev)

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--              TIMELINE — INTERACTIVE SVG                    -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#14b8a6" opacity="0.8"/>
</svg>

</div>

## 🛤️ `> git log --timeline --pretty=journey`

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 520" width="90%">
  <defs>
    <linearGradient id="tlBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#090c10"/>
    </linearGradient>
    <linearGradient id="tlLine" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"   stop-color="#38bdf8"/>
      <stop offset="40%"  stop-color="#6366f1"/>
      <stop offset="70%"  stop-color="#14b8a6"/>
      <stop offset="100%" stop-color="#22c55e"/>
    </linearGradient>
    <filter id="tlGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <linearGradient id="card1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1e3a5f"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="card2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#2d1b69"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="card3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#134e4a"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="card4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#14532d"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="card5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c2d12"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
  </defs>

  <rect width="820" height="520" fill="url(#tlBg)" rx="12" stroke="#1e293b" stroke-width="1"/>

  <!-- Center spine -->
  <line x1="410" y1="20" x2="410" y2="500" stroke="url(#tlLine)" stroke-width="2"/>

  <!-- ── 2023 ── -->
  <circle cx="410" cy="55" r="12" fill="#38bdf8" filter="url(#tlGlow)">
    <animate attributeName="r" values="12;15;12" dur="3s" repeatCount="indefinite"/>
  </circle>
  <text x="410" y="60" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#0d1117">23</text>
  <!-- Left card -->
  <rect x="40" y="30" width="340" height="70" rx="8" fill="url(#card1)" stroke="#38bdf8" stroke-width="0.5" stroke-opacity="0.5"/>
  <text x="56" y="52" font-family="'SF Mono',monospace" font-size="13" font-weight="bold" fill="#38bdf8">2023 — The Beginning</text>
  <text x="56" y="70" font-family="'SF Mono',monospace" font-size="11" fill="#94a3b8">Started programming journey</text>
  <text x="56" y="86" font-family="'SF Mono',monospace" font-size="11" fill="#64748b">HTML · CSS · JavaScript basics</text>
  <!-- connector -->
  <line x1="380" y1="55" x2="398" y2="55" stroke="#38bdf8" stroke-width="1" stroke-dasharray="4,2"/>

  <!-- ── 2024 ── -->
  <circle cx="410" cy="155" r="12" fill="#6366f1" filter="url(#tlGlow)">
    <animate attributeName="r" values="12;15;12" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <text x="410" y="160" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#fff">24</text>
  <!-- Right card -->
  <rect x="440" y="128" width="340" height="70" rx="8" fill="url(#card2)" stroke="#6366f1" stroke-width="0.5" stroke-opacity="0.5"/>
  <text x="456" y="150" font-family="'SF Mono',monospace" font-size="13" font-weight="bold" fill="#6366f1">2024 — Backend Rising</text>
  <text x="456" y="168" font-family="'SF Mono',monospace" font-size="11" fill="#94a3b8">Mastered PHP + Laravel framework</text>
  <text x="456" y="184" font-family="'SF Mono',monospace" font-size="11" fill="#64748b">MySQL · REST API · MVC pattern</text>
  <!-- connector -->
  <line x1="422" y1="155" x2="440" y2="155" stroke="#6366f1" stroke-width="1" stroke-dasharray="4,2"/>

  <!-- ── 2025 ── -->
  <circle cx="410" cy="255" r="12" fill="#14b8a6" filter="url(#tlGlow)">
    <animate attributeName="r" values="12;15;12" dur="4s" repeatCount="indefinite"/>
  </circle>
  <text x="410" y="260" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#0d1117">25</text>
  <!-- Left card -->
  <rect x="40" y="228" width="340" height="70" rx="8" fill="url(#card3)" stroke="#14b8a6" stroke-width="0.5" stroke-opacity="0.5"/>
  <text x="56" y="250" font-family="'SF Mono',monospace" font-size="13" font-weight="bold" fill="#14b8a6">2025 — Fullstack Era</text>
  <text x="56" y="268" font-family="'SF Mono',monospace" font-size="11" fill="#94a3b8">React + TypeScript + Laravel</text>
  <text x="56" y="284" font-family="'SF Mono',monospace" font-size="11" fill="#64748b">ML with Python · scikit-learn</text>
  <line x1="380" y1="255" x2="398" y2="255" stroke="#14b8a6" stroke-width="1" stroke-dasharray="4,2"/>

  <!-- ── 2026 ── -->
  <circle cx="410" cy="355" r="14" fill="#22c55e" filter="url(#tlGlow)">
    <animate attributeName="r" values="14;18;14" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#22c55e;#16a34a;#22c55e" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="410" y="361" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#0d1117">26</text>
  <!-- Right card — CURRENT -->
  <rect x="440" y="325" width="340" height="72" rx="8" fill="url(#card4)" stroke="#22c55e" stroke-width="1"/>
  <text x="456" y="348" font-family="'SF Mono',monospace" font-size="13" font-weight="bold" fill="#22c55e">2026 — NOW ● LIVE</text>
  <text x="456" y="366" font-family="'SF Mono',monospace" font-size="11" fill="#94a3b8">Software Engineer · AI Explorer</text>
  <text x="456" y="382" font-family="'SF Mono',monospace" font-size="11" fill="#64748b">Building ERP · 270+ contributions</text>
  <line x1="422" y1="355" x2="440" y2="355" stroke="#22c55e" stroke-width="1" stroke-dasharray="4,2"/>

  <!-- ── FUTURE ── -->
  <circle cx="410" cy="455" r="12" fill="none" stroke="#f97316" stroke-width="2" stroke-dasharray="4,2" filter="url(#tlGlow)">
    <animate attributeName="stroke-dashoffset" values="0;16" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="410" y="460" text-anchor="middle" font-family="monospace" font-size="9" fill="#f97316">∞</text>
  <!-- Left card -->
  <rect x="40" y="428" width="340" height="55" rx="8" fill="url(#card5)" stroke="#f97316" stroke-width="0.5" stroke-opacity="0.5" stroke-dasharray="4,2"/>
  <text x="56" y="450" font-family="'SF Mono',monospace" font-size="13" font-weight="bold" fill="#f97316">Future — AI Engineer</text>
  <text x="56" y="468" font-family="'SF Mono',monospace" font-size="11" fill="#64748b">Deep Learning · LLM · Production AI</text>
  <line x1="380" y1="455" x2="398" y2="455" stroke="#f97316" stroke-width="1" stroke-dasharray="4,2"/>
</svg>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                  GITHUB ANALYTICS                         -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#2563eb" opacity="0.8"/>
</svg>

</div>

## 📊 `> gh api /analytics --format=premium`

<div align="center">

<!-- GitHub Stats + Top Languages -->
<img src="https://github-readme-stats.vercel.app/api?username=Sahal111&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=6366f1&text_color=94a3b8&ring_color=38bdf8&count_private=true&include_all_commits=true" height="165" alt="GitHub Stats"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sahal111&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8&langs_count=8" height="165" alt="Top Languages"/>

<br/><br/>

<!-- Streak Stats -->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sahal111&theme=terminal&hide_border=true&background=0d1117&ring=38bdf8&fire=6366f1&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=475569&sideNums=e2e8f0&currStreakNum=ffffff" alt="GitHub Streak" width="70%"/>

<br/><br/>

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sahal111&bg_color=0d1117&color=38bdf8&line=6366f1&point=ffffff&area=true&hide_border=true&custom_title=Sahal111%27s%20Contribution%20Graph&area_color=38bdf8" width="95%" alt="Activity Graph"/>

<br/><br/>

<!-- Trophies -->
<img src="https://github-profile-trophy.vercel.app/?username=Sahal111&theme=matrix&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" width="95%" alt="Trophies"/>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--             CONTRIBUTION SNAKE ANIMATION                  -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#14b8a6" opacity="0.8"/>
</svg>

## 🐍 `> ./snake.py --eat-contributions`

<!--
  SNAKE ANIMATION SETUP:
  ─────────────────────────────────────────────────────────────
  1. In your Sahal111/Sahal111 repo, go to Settings → Actions → Workflows
  2. Create file: .github/workflows/snake.yml
  3. Paste this content:

  name: Generate Snake
  on:
    schedule: [{ cron: "0 */12 * * *" }]
    workflow_dispatch:
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: actions/checkout@v3
        - uses: Platane/snk@v3
          with:
            github_user_name: Sahal111
            outputs: |
              dist/github-snake.svg?palette=github-dark
              dist/github-snake-dark.svg?palette=github-dark&color_snake=38bdf8
        - uses: crazy-max/ghaction-github-pages@v3
          with: { target_branch: output, build_dir: dist }
          env: { GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} }
  ─────────────────────────────────────────────────────────────
  After setup, uncomment the img below and delete this comment:
-->

<img src="https://raw.githubusercontent.com/Sahal111/Sahal111/output/github-snake-dark.svg" alt="Snake animation" width="95%"/>

<!-- Fallback static badge while snake is being set up -->
[![Contribution Snake](https://img.shields.io/badge/🐍_Contribution_Snake-Setting_Up-38bdf8?style=for-the-badge&labelColor=0d1117)](https://github.com/Sahal111/Sahal111/actions)

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                 FEATURED PROJECTS                         -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#38bdf8" opacity="0.8"/>
</svg>

</div>

## 📌 `> git ls-remote --featured-projects`

<div align="center">

<!-- Row 1 -->
<a href="https://github.com/Sahal111/sneakershead">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=sneakershead&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=6366f1&text_color=94a3b8" alt="sneakershead"/>
</a>
&nbsp;
<a href="https://github.com/Sahal111/UTS_ML_Sahal">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=UTS_ML_Sahal&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=6366f1&text_color=94a3b8" alt="UTS ML Sahal"/>
</a>

<br/><br/>

<!-- Row 2 -->
<a href="https://github.com/Sahal111/Challenge_Frontend_React">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=Challenge_Frontend_React&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=6366f1&text_color=94a3b8" alt="Frontend React Challenge"/>
</a>
&nbsp;
<a href="https://github.com/Sahal111/RPL_Group1">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=RPL_Group1&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=6366f1&text_color=94a3b8" alt="RPL Group1"/>
</a>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--            LIVE WIDGETS — SPOTIFY / CODING                -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#6366f1" opacity="0.8"/>
</svg>

</div>

## 🎧 `> ./live_status.sh --now-playing`

<div align="center">

<table>
<tr>
<td align="center" width="50%">

<!-- ─────────────────────────────────────────────
  🎵 SPOTIFY — NOW PLAYING
  ─────────────────────────────────────────────
  SETUP STEPS:
  1. Go to https://github.com/novatorem/novatorem
  2. Deploy to Vercel, connect your Spotify account
  3. Replace YOUR_VERCEL_APP below with your URL
  ─────────────────────────────────────────────
  Once set up, uncomment this block:

  [![Spotify](https://YOUR_VERCEL_APP.vercel.app/api/spotify)](https://open.spotify.com/user/YOUR_SPOTIFY_ID)
  ─────────────────────────────────────────────
-->

[![Spotify](https://img.shields.io/badge/🎵_NOW_PLAYING-Connect_Spotify-1DB954?style=for-the-badge&labelColor=0d1117&logo=spotify)](https://github.com/novatorem/novatorem)

**🎵 Now Playing**  
> *Setup Spotify widget via [novatorem](https://github.com/novatorem/novatorem)*

</td>
<td align="center" width="50%">

<!-- ─────────────────────────────────────────────
  ⏱ WAKATIME — CODING STATS
  ─────────────────────────────────────────────
  SETUP STEPS:
  1. Sign up at https://wakatime.com
  2. Install WakaTime plugin in VS Code
  3. Add WAKATIME_API_KEY to repo secrets
  4. Replace YOUR_WAKATIME_USERNAME below
  ─────────────────────────────────────────────
  Once set up, uncomment this block:

  [![Wakatime](https://wakatime.com/badge/user/YOUR_WAKATIME_ID.svg)](https://wakatime.com/@Sahal111)
  ![Wakatime](https://github-readme-stats.vercel.app/api/wakatime?username=Sahal111&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8)
  ─────────────────────────────────────────────
-->

[![WakaTime](https://img.shields.io/badge/⏱_CODING_STATS-Setup_WakaTime-38bdf8?style=for-the-badge&labelColor=0d1117&logo=wakatime)](https://wakatime.com)

**⏱ Coding Stats**  
> *Setup WakaTime at [wakatime.com](https://wakatime.com)*

</td>
</tr>
</table>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                   ACHIEVEMENT SECTION                     -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#f59e0b" opacity="0.8"/>
</svg>

</div>

## 🏆 `> gh achievement list --unlocked`

<div align="center">

<table>
<tr>

<td align="center" width="25%">

```
╔═══════════╗
║  🌟 270+  ║
║ Commits   ║
║  in 2026  ║
╚═══════════╝
```
**Commit Warrior**

</td>

<td align="center" width="25%">

```
╔═══════════╗
║  📦  14   ║
║  Public   ║
║   Repos   ║
╚═══════════╝
```
**Open Builder**

</td>

<td align="center" width="25%">

```
╔═══════════╗
║  ⚡ Full  ║
║  Stack    ║
║ Certified ║
╚═══════════╝
```
**Fullstack Dev**

</td>

<td align="center" width="25%">

```
╔═══════════╗
║  🧠  ML   ║
║ Explorer  ║
║  Python   ║
╚═══════════╝
```
**AI Learner**

</td>

</tr>
</table>

<!-- Trophy widget -->
<img src="https://github-profile-trophy.vercel.app/?username=Sahal111&theme=matrix&no-frame=true&no-bg=true&row=1&column=4&margin-w=12" alt="Trophies"/>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                 CURRENT FOCUS CARDS                       -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#22c55e" opacity="0.8"/>
</svg>

</div>

## 🎯 `> ./focus --current`

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 180" width="90%">
  <defs>
    <linearGradient id="focusBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#090c10"/>
    </linearGradient>
    <linearGradient id="fc1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e3a5f"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="fc2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#2d1b69"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="fc3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#134e4a"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="fc4" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#3b0764"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="fc5" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#14532d"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
  </defs>

  <rect width="820" height="180" fill="url(#focusBg)" rx="12" stroke="#1e293b" stroke-width="1"/>

  <!-- Card 1 -->
  <rect x="16" y="16" width="148" height="148" rx="10" fill="url(#fc1)" stroke="#38bdf8" stroke-width="0.5"/>
  <text x="90" y="65" text-anchor="middle" font-size="28">🚀</text>
  <text x="90" y="92" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#38bdf8">School ERP</text>
  <text x="90" y="110" text-anchor="middle" font-family="monospace" font-size="10" fill="#64748b">Laravel + React</text>
  <text x="90" y="128" text-anchor="middle" font-family="monospace" font-size="10" fill="#475569">Building</text>
  <circle cx="90" cy="148" r="5" fill="#22c55e">
    <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
  </circle>

  <!-- Card 2 -->
  <rect x="172" y="16" width="148" height="148" rx="10" fill="url(#fc2)" stroke="#6366f1" stroke-width="0.5"/>
  <text x="246" y="65" text-anchor="middle" font-size="28">🧠</text>
  <text x="246" y="92" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#6366f1">Deep Learning</text>
  <text x="246" y="110" text-anchor="middle" font-family="monospace" font-size="10" fill="#64748b">Python + PyTorch</text>
  <text x="246" y="128" text-anchor="middle" font-family="monospace" font-size="10" fill="#475569">Learning</text>
  <circle cx="246" cy="148" r="5" fill="#6366f1">
    <animate attributeName="opacity" values="1;0.3;1" dur="2.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Card 3 -->
  <rect x="328" y="16" width="148" height="148" rx="10" fill="url(#fc3)" stroke="#14b8a6" stroke-width="0.5"/>
  <text x="402" y="65" text-anchor="middle" font-size="28">⚡</text>
  <text x="402" y="92" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#14b8a6">React + Vite</text>
  <text x="402" y="110" text-anchor="middle" font-family="monospace" font-size="10" fill="#64748b">TypeScript · TW</text>
  <text x="402" y="128" text-anchor="middle" font-family="monospace" font-size="10" fill="#475569">Practicing</text>
  <circle cx="402" cy="148" r="5" fill="#14b8a6">
    <animate attributeName="opacity" values="1;0.3;1" dur="3s" repeatCount="indefinite"/>
  </circle>

  <!-- Card 4 -->
  <rect x="484" y="16" width="148" height="148" rx="10" fill="url(#fc4)" stroke="#a855f7" stroke-width="0.5"/>
  <text x="558" y="65" text-anchor="middle" font-size="28">📐</text>
  <text x="558" y="92" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#a855f7">Clean Arch</text>
  <text x="558" y="110" text-anchor="middle" font-family="monospace" font-size="10" fill="#64748b">SOLID · DDD</text>
  <text x="558" y="128" text-anchor="middle" font-family="monospace" font-size="10" fill="#475569">Studying</text>
  <circle cx="558" cy="148" r="5" fill="#a855f7">
    <animate attributeName="opacity" values="1;0.3;1" dur="2.2s" repeatCount="indefinite"/>
  </circle>

  <!-- Card 5 -->
  <rect x="640" y="16" width="164" height="148" rx="10" fill="url(#fc5)" stroke="#22c55e" stroke-width="0.5"/>
  <text x="722" y="65" text-anchor="middle" font-size="28">🌐</text>
  <text x="722" y="92" text-anchor="middle" font-family="monospace" font-size="11" font-weight="bold" fill="#22c55e">Open Source</text>
  <text x="722" y="110" text-anchor="middle" font-family="monospace" font-size="10" fill="#64748b">Contributing</text>
  <text x="722" y="128" text-anchor="middle" font-family="monospace" font-size="10" fill="#475569">Exploring</text>
  <circle cx="722" cy="148" r="5" fill="#22c55e">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.8s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                    FUN FACTS                              -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#f59e0b" opacity="0.8"/>
</svg>

</div>

## 🎲 `> cat fun_facts.txt | shuf | head -6`

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│  ⚡  I can center a div in CSS — on the first try (sometimes)   │
│  🐛  My debugging style: console.log > debugger                 │
│  ☕  Correlation between coffee intake and commit quality: 1.0  │
│  🌙  Peak coding hours: 10PM – 2AM (don't ask why)             │
│  🎮  I name my variables after anime characters sometimes        │
│  🇮🇩  Indonesian dev who dreams in English & codes in PHP       │
└─────────────────────────────────────────────────────────────────┘
```

<!-- Random Dev Quote -->
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&quote=The%20best%20code%20is%20no%20code%20at%20all.%20Every%20new%20line%20of%20code%20you%20willingly%20bring%20into%20the%20world%20is%20code%20that%20has%20to%20be%20debugged&author=Jeff%20Atwood" alt="Dev Quote" width="80%"/>

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--                   CONNECT / SOCIALS                       -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 36" width="90%">
  <line x1="0" y1="18" x2="820" y2="18" stroke="url(#divGrad1)" stroke-width="1"/>
  <polygon points="410,4 418,18 410,32 402,18" fill="#38bdf8" opacity="0.8"/>
</svg>

</div>

## 🌐 `> curl -s https://api.sahal.dev/contact | jq`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-@Sahal111-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/Sahal111)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sahal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117)](https://linkedin.com/in/sahal111)
[![Instagram](https://img.shields.io/badge/Instagram-@X__proff-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117)](https://instagram.com/sahal111)
[![Email](https://img.shields.io/badge/Email-Drop_a_Mail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117)](mailto:sahal@gmail.com)

<br/>

<!-- Typing CTA -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=15&duration=3000&pause=1000&color=38BDF8&background=0D111700&center=true&vCenter=true&multiline=false&width=600&lines=Let's+build+something+amazing+together+🚀;Open+for+freelance+%26+collaboration+💼;Drop+me+a+message+anytime+✉️)](https://github.com/Sahal111)

</div>

<br/>

<!-- ██████████████████████████████████████████████████████████ -->
<!--     GITHUB ACTIONS SETUP — AUTO-UPDATE WORKFLOWS          -->
<!-- ██████████████████████████████████████████████████████████ -->

<!--
═══════════════════════════════════════════════════════════════════
  ⚙️  GITHUB ACTIONS AUTO-UPDATE WORKFLOWS
═══════════════════════════════════════════════════════════════════

  Create these workflow files in .github/workflows/ to enable
  auto-updating content on your profile README:

  ── 1. CONTRIBUTION SNAKE ─────────────────────────────────────
  File: .github/workflows/snake.yml
  ┌──────────────────────────────────────────────────────────────┐
  │ name: Generate Snake                                         │
  │ on:                                                          │
  │   schedule: [{ cron: "0 */12 * * *" }]                      │
  │   workflow_dispatch:                                         │
  │ jobs:                                                        │
  │   generate:                                                  │
  │     runs-on: ubuntu-latest                                   │
  │     steps:                                                   │
  │       - uses: actions/checkout@v3                            │
  │       - uses: Platane/snk@v3                                 │
  │         with:                                                │
  │           github_user_name: Sahal111                        │
  │           outputs: |                                         │
  │             dist/github-snake-dark.svg?palette=github-dark   │
  │               &color_snake=38bdf8                           │
  │       - uses: crazy-max/ghaction-github-pages@v3            │
  │         with: { target_branch: output, build_dir: dist }     │
  │         env: { GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }} }  │
  └──────────────────────────────────────────────────────────────┘

  ── 2. SPOTIFY NOW PLAYING ─────────────────────────────────────
  Deploy https://github.com/novatorem/novatorem to Vercel,
  then add this to your profile repo Actions to auto-refresh:
  File: .github/workflows/spotify.yml
  ┌──────────────────────────────────────────────────────────────┐
  │ name: Update Spotify                                         │
  │ on:                                                          │
  │   schedule: [{ cron: "*/30 * * * *" }]                      │
  │ jobs:                                                        │
  │   update:                                                    │
  │     runs-on: ubuntu-latest                                   │
  │     steps:                                                   │
  │       - uses: actions/checkout@v3                            │
  │       - name: Refresh Spotify token                          │
  │         run: curl -X POST ${{ secrets.SPOTIFY_REFRESH_URL }} │
  └──────────────────────────────────────────────────────────────┘

  ── 3. WAKATIME STATS ──────────────────────────────────────────
  File: .github/workflows/waka.yml
  ┌──────────────────────────────────────────────────────────────┐
  │ name: Waka Readme                                            │
  │ on:                                                          │
  │   schedule: [{ cron: "30 18 * * *" }]                       │
  │   workflow_dispatch:                                         │
  │ jobs:                                                        │
  │   update-readme:                                             │
  │     name: Update Readme with Wakatime Stats                  │
  │     runs-on: ubuntu-latest                                   │
  │     steps:                                                   │
  │       - uses: anmol098/waka-readme-stats@master              │
  │         with:                                                │
  │           WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}  │
  │           GH_TOKEN: ${{ secrets.GH_TOKEN }}                  │
  │           SHOW_LINES_OF_CODE: "True"                         │
  │           SHOW_PROFILE_VIEWS: "False"                        │
  └──────────────────────────────────────────────────────────────┘

  ── 4. OPTIONAL WIDGETS ────────────────────────────────────────
  • Holopin Badges  → https://holopin.io/@Sahal111
    (Sign up at holopin.io to earn badges from open source work)
  
  • LeetCode Stats  → https://leetcard.jacoblin.cool/Sahal111
    (Create account at leetcode.com/Sahal111)
  
  • Codewars        → https://www.codewars.com/users/Sahal111/badges/large
    (Create account at codewars.com)
  
  • Discord Status  → https://lanyard.cnrad.dev/api/YOUR_DISCORD_ID
    (Use Lanyard: discord.gg/lanyard, then add your user ID)
═══════════════════════════════════════════════════════════════════
-->

<!-- ██████████████████████████████████████████████████████████ -->
<!--         NEON FOOTER — WAVE + DIGITAL SIGNATURE            -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200" width="100%">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#090c10" stop-opacity="0"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <filter id="neonText" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <linearGradient id="waveFill1" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#1e293b" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#0f172a" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="waveFill2" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#38bdf8" stop-opacity="0.08"/>
      <stop offset="100%" stop-color="#0f172a" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="waveFill3" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#6366f1" stop-opacity="0.06"/>
      <stop offset="100%" stop-color="#0f172a" stop-opacity="0"/>
    </linearGradient>
    <linearGradient id="sigGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#38bdf8"/>
      <stop offset="50%"  stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#14b8a6"/>
    </linearGradient>
  </defs>

  <!-- Base -->
  <rect width="900" height="200" fill="url(#footerBg)"/>

  <!-- Wave layer 3 (back) -->
  <path d="M0,120 C150,80 300,160 450,120 C600,80 750,160 900,120 L900,200 L0,200 Z"
        fill="url(#waveFill1)">
    <animate attributeName="d"
      values="M0,120 C150,80 300,160 450,120 C600,80 750,160 900,120 L900,200 L0,200 Z;
              M0,100 C150,140 300,60 450,100 C600,140 750,60 900,100 L900,200 L0,200 Z;
              M0,120 C150,80 300,160 450,120 C600,80 750,160 900,120 L900,200 L0,200 Z"
      dur="8s" repeatCount="indefinite"/>
  </path>

  <!-- Wave layer 2 (mid) -->
  <path d="M0,140 C225,100 450,180 675,140 C787,120 843,155 900,140 L900,200 L0,200 Z"
        fill="url(#waveFill2)">
    <animate attributeName="d"
      values="M0,140 C225,100 450,180 675,140 C787,120 843,155 900,140 L900,200 L0,200 Z;
              M0,160 C225,120 450,160 675,120 C787,100 843,135 900,120 L900,200 L0,200 Z;
              M0,140 C225,100 450,180 675,140 C787,120 843,155 900,140 L900,200 L0,200 Z"
      dur="6s" repeatCount="indefinite"/>
  </path>

  <!-- Wave layer 1 (front) -->
  <path d="M0,160 C300,130 600,180 900,155 L900,200 L0,200 Z"
        fill="url(#waveFill3)">
    <animate attributeName="d"
      values="M0,160 C300,130 600,180 900,155 L900,200 L0,200 Z;
              M0,150 C300,175 600,140 900,165 L900,200 L0,200 Z;
              M0,160 C300,130 600,180 900,155 L900,200 L0,200 Z"
      dur="5s" repeatCount="indefinite"/>
  </path>

  <!-- Neon glowing line at top of footer -->
  <line x1="0" y1="2" x2="900" y2="2" stroke="url(#sigGrad)" stroke-width="1.5" opacity="0.6"/>

  <!-- Digital Signature — neon style -->
  <text x="450" y="60" text-anchor="middle"
        font-family="'Courier New', Courier, monospace"
        font-size="36" font-weight="900"
        fill="url(#sigGrad)" filter="url(#neonText)"
        letter-spacing="4">
    SAHAL
    <animate attributeName="opacity" values="0.9;1;0.85;1;0.9" dur="3s" repeatCount="indefinite"/>
  </text>

  <!-- Underline glow -->
  <line x1="310" y1="68" x2="590" y2="68" stroke="url(#sigGrad)" stroke-width="1.5" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0.9;0.5" dur="2s" repeatCount="indefinite"/>
  </line>

  <!-- Subtitle -->
  <text x="450" y="92" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="11"
        fill="#38bdf8" letter-spacing="6" opacity="0.7">
    X_ PROFF · FULLSTACK DEVELOPER
  </text>

  <!-- Decorative particles near footer -->
  <circle cx="120" cy="40" r="2" fill="#38bdf8" opacity="0.5">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="780" cy="35" r="1.5" fill="#6366f1" opacity="0.5">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="450" cy="20" r="1" fill="#14b8a6" opacity="0.6">
    <animate attributeName="cy" values="20;10;20" dur="4s" repeatCount="indefinite"/>
  </circle>

  <!-- Made with line -->
  <text x="450" y="125" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="11"
        fill="#334155" letter-spacing="1">
    Made with ❤️ + ☕ + console.log() · Indonesia 🇮🇩
  </text>

  <!-- Bottom copyright line -->
  <text x="450" y="155" text-anchor="middle"
        font-family="'Courier New', monospace" font-size="10"
        fill="#1e293b">
    © 2026 Sahal · All bugs are features in disguise 🐛
  </text>

  <!-- Corner brackets neon -->
  <path d="M 20 185 L 20 195 L 30 195" fill="none" stroke="#38bdf8" stroke-width="1" opacity="0.4"/>
  <path d="M 880 185 L 880 195 L 870 195" fill="none" stroke="#38bdf8" stroke-width="1" opacity="0.4"/>
</svg>

</div>

<!-- ██████████████████████████████████████████████████████████ -->
<!--         TYPING ANIMATION — HERO (BELOW FOOTER)            -->
<!-- ██████████████████████████████████████████████████████████ -->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=13&duration=2500&pause=800&color=38BDF8&background=0D111700&center=true&vCenter=true&multiline=false&width=700&lines=root%40Sahal111%3A~%24+echo+%22Thanks+for+visiting!%22;root%40Sahal111%3A~%24+git+push+origin+awesome-future;root%40Sahal111%3A~%24+sudo+make+me+a+sandwich;root%40Sahal111%3A~%24+npm+run+build+--+--success;Don%27t+forget+to+%E2%AD%90+star+repos+you+like!)](https://github.com/Sahal111)

</div>

---

<div align="center">

<!-- Final visitor count -->
![Visitor Count](https://komarev.com/ghpvc/?username=Sahal111&style=flat-square&color=38bdf8&label=Total+Profile+Views)
&nbsp; · &nbsp;
![Last Updated](https://img.shields.io/badge/Last_Updated-2026-38bdf8?style=flat-square&labelColor=0d1117)
&nbsp; · &nbsp;
![Open Source Love](https://img.shields.io/badge/Open_Source-❤️-6366f1?style=flat-square&labelColor=0d1117)

</div>

<!-- END OF README ─────────────────────────────────────────── -->

<!--
╔══════════════════════════════════════════════════════════════════════════════╗
║          SAHAL111 · GITHUB PROFILE README · ULTRA PREMIUM EDITION           ║
║          Built with: SVG · CSS Animation · GitHub APIs · Markdown           ║
║          Author: Sahal · Indonesia 🇮🇩 · github.com/Sahal111               ║
╚══════════════════════════════════════════════════════════════════════════════╝

  SETUP NOTES FOR APIS:
  ─────────────────────
  ① Spotify Now Playing  → Deploy: github.com/novatorem/novatorem
     Replace YOUR_VERCEL_URL with your deployed URL
  ② Wakatime Stats       → Connect at wakatime.com, add secret WAKATIME_API_KEY
  ③ Snake Animation      → Enable GitHub Actions workflow (included below)
  ④ GitHub Actions       → Create .github/workflows/update.yml for auto-updates
  ⑤ Discord Status       → Optional: lanyard.rest (add your Discord user ID)
  ⑥ Holopin Badges       → Earn at holopin.io
  ⑦ Leetcode             → Use leetcard.jacoblin.com with your username
  ⑧ Codewars             → www.codewars.com/users/Sahal111
-->

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   ANIMATED WAVE HEADER                  -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="120" viewBox="0 0 1440 120" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0f172a"/>
      <stop offset="30%"  stop-color="#0d1117"/>
      <stop offset="70%"  stop-color="#0d2818"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="1440" height="120" fill="url(#headerGrad)"/>
  <!-- Animated neon grid lines -->
  <line x1="0" y1="60" x2="1440" y2="60" stroke="#00ff41" stroke-width="0.3" stroke-dasharray="4 8" opacity="0.3"/>
  <line x1="0" y1="30" x2="1440" y2="30" stroke="#0ff" stroke-width="0.2" stroke-dasharray="2 12" opacity="0.2"/>
  <line x1="0" y1="90" x2="1440" y2="90" stroke="#0ff" stroke-width="0.2" stroke-dasharray="2 12" opacity="0.2"/>
  <!-- Matrix rain dots -->
  <circle cx="100"  cy="20"  r="1.5" fill="#00ff41" opacity="0.8" filter="url(#glow)">
    <animate attributeName="opacity" values="0.8;0.1;0.8" dur="2.1s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="20;100;20"   dur="4.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="280"  cy="50"  r="1.5" fill="#00ff41" opacity="0.6" filter="url(#glow)">
    <animate attributeName="opacity" values="0.6;0.05;0.6" dur="1.7s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="50;110;50"    dur="3.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="460"  cy="10"  r="1"   fill="#00ff41" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0.1;0.7" dur="2.8s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="10;90;10"    dur="5.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="640"  cy="70"  r="1.5" fill="#38bdf8" opacity="0.5" filter="url(#glow)">
    <animate attributeName="opacity" values="0.5;0.05;0.5" dur="2.3s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="70;110;70"    dur="4.6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="820"  cy="35"  r="1"   fill="#38bdf8" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="1.9s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="35;100;35"    dur="3.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1000" cy="55"  r="1.5" fill="#6366f1" opacity="0.5" filter="url(#glow)">
    <animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.5s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="55;115;55"    dur="5.0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1180" cy="25"  r="1"   fill="#00ff41" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0.05;0.7" dur="2.0s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="25;95;25"     dur="4.0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1360" cy="65"  r="1.5" fill="#38bdf8" opacity="0.4" filter="url(#glow)">
    <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.1s" repeatCount="indefinite"/>
    <animate attributeName="cy"      values="65;110;65"    dur="6.2s" repeatCount="indefinite"/>
  </circle>
  <!-- Glowing wave -->
  <path d="M0,80 C180,40 360,100 540,60 C720,20 900,80 1080,50 C1260,20 1380,70 1440,55 L1440,120 L0,120 Z"
        fill="url(#headerGrad)" opacity="0.5"/>
  <!-- Terminal cursor blink in header -->
  <rect x="670" y="52" width="8" height="16" fill="#00ff41" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0;0.9" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════ -->
<!--               CUSTOM SVG HERO BANNER                    -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <!-- Backgrounds -->
    <linearGradient id="bgMain" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0d1117"/>
      <stop offset="50%"  stop-color="#0f172a"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <!-- Neon cyan glow -->
    <linearGradient id="cyanGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#38bdf8"/>
      <stop offset="50%"  stop-color="#00ff41"/>
      <stop offset="100%" stop-color="#38bdf8"/>
    </linearGradient>
    <!-- Purple accent -->
    <linearGradient id="purpGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#2563eb"/>
    </linearGradient>
    <!-- Glow filter -->
    <filter id="neonGlow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softGlow" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Scanline pattern -->
    <pattern id="scanlines" x="0" y="0" width="1" height="4" patternUnits="userSpaceOnUse">
      <rect x="0" y="0" width="860" height="1" fill="rgba(0,255,65,0.03)"/>
    </pattern>
    <!-- Circuit pattern -->
    <pattern id="circuit" x="0" y="0" width="60" height="60" patternUnits="userSpaceOnUse">
      <path d="M10,30 L30,30 L30,10 M30,30 L50,30 M20,10 L20,20 M40,50 L40,40" 
            stroke="#38bdf8" stroke-width="0.4" fill="none" opacity="0.15"/>
      <circle cx="30" cy="30" r="2" fill="#38bdf8" opacity="0.1"/>
      <circle cx="10" cy="30" r="1.5" fill="#00ff41" opacity="0.08"/>
      <circle cx="50" cy="30" r="1.5" fill="#00ff41" opacity="0.08"/>
      <circle cx="20" cy="10" r="1"   fill="#6366f1" opacity="0.1"/>
      <circle cx="40" cy="50" r="1"   fill="#6366f1" opacity="0.1"/>
    </pattern>
    <!-- Clip path for rounded corners -->
    <clipPath id="bannerClip">
      <rect x="0" y="0" width="860" height="280" rx="16" ry="16"/>
    </clipPath>
  </defs>

  <g clip-path="url(#bannerClip)">
    <!-- Base bg -->
    <rect width="860" height="280" fill="url(#bgMain)"/>
    <!-- Circuit overlay -->
    <rect width="860" height="280" fill="url(#circuit)"/>
    <!-- Scanlines overlay -->
    <rect width="860" height="280" fill="url(#scanlines)"/>

    <!-- Glowing orb top-right -->
    <circle cx="780" cy="50" r="80" fill="#38bdf8" opacity="0.04" filter="url(#neonGlow)"/>
    <circle cx="780" cy="50" r="50" fill="#6366f1" opacity="0.05" filter="url(#neonGlow)"/>
    <!-- Glowing orb bottom-left -->
    <circle cx="80"  cy="230" r="70" fill="#00ff41" opacity="0.03" filter="url(#neonGlow)"/>
    <circle cx="80"  cy="230" r="40" fill="#38bdf8" opacity="0.04" filter="url(#neonGlow)"/>

    <!-- Border glow -->
    <rect x="1" y="1" width="858" height="278" rx="15" ry="15"
          fill="none" stroke="url(#cyanGrad)" stroke-width="0.8" opacity="0.6" filter="url(#softGlow)"/>

    <!-- Corner accents -->
    <path d="M0,40 L0,0 L40,0"   fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
    <path d="M820,0 L860,0 L860,40"  fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
    <path d="M0,240 L0,280 L40,280"  fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
    <path d="M820,280 L860,280 L860,240" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>

    <!-- Corner dots -->
    <circle cx="0"   cy="0"   r="4" fill="#00ff41" opacity="0.9" filter="url(#softGlow)">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="860" cy="0"   r="4" fill="#38bdf8" opacity="0.9" filter="url(#softGlow)">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="0"   cy="280" r="4" fill="#6366f1" opacity="0.9" filter="url(#softGlow)">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="1.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="860" cy="280" r="4" fill="#00ff41" opacity="0.9" filter="url(#softGlow)">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.2s" repeatCount="indefinite"/>
    </circle>

    <!-- Status bar top -->
    <rect x="0" y="0" width="860" height="28" fill="rgba(0,0,0,0.4)"/>
    <circle cx="22"  cy="14" r="5" fill="#ff5f57">
      <animate attributeName="opacity" values="1;0.6;1" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="40"  cy="14" r="5" fill="#febc2e">
      <animate attributeName="opacity" values="1;0.6;1" dur="3.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="58"  cy="14" r="5" fill="#28c840">
      <animate attributeName="opacity" values="1;0.6;1" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <text x="430" y="18" fill="#38bdf8" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" opacity="0.7">
      ~/portfolio/sahal — bash — 120×30
    </text>
    <!-- Pulsing dot (live indicator) -->
    <circle cx="820" cy="14" r="3.5" fill="#00ff41" opacity="0.9">
      <animate attributeName="r"       values="3.5;5;3.5"   dur="1.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <text x="808" y="18" fill="#00ff41" font-size="8" font-family="'Courier New',monospace" text-anchor="end" opacity="0.7">LIVE</text>

    <!-- Main title area -->
    <!-- Name: SAHAL -->
    <text x="430" y="100" fill="url(#cyanGrad)" font-size="64" font-family="'Courier New',monospace"
          font-weight="900" text-anchor="middle" letter-spacing="12" filter="url(#neonGlow)" opacity="0.95">
      SAHAL
    </text>
    <!-- Subtle echo / shadow -->
    <text x="432" y="102" fill="#38bdf8" font-size="64" font-family="'Courier New',monospace"
          font-weight="900" text-anchor="middle" letter-spacing="12" opacity="0.08">
      SAHAL
    </text>

    <!-- Tag line -->
    <text x="430" y="130" fill="#94a3b8" font-size="12" font-family="'Courier New',monospace"
          text-anchor="middle" letter-spacing="6">
      FULL-STACK DEVELOPER · INDONESIA
    </text>

    <!-- Animated underline -->
    <line x1="230" y1="140" x2="630" y2="140" stroke="url(#cyanGrad)" stroke-width="1" opacity="0.5">
      <animate attributeName="x1"      values="230;330;230" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="x2"      values="630;530;630" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5"   dur="3s" repeatCount="indefinite"/>
    </line>

    <!-- Role badges -->
    <rect x="200" y="155" width="120" height="22" rx="11" fill="rgba(56,189,248,0.1)" stroke="#38bdf8" stroke-width="0.8"/>
    <text x="260" y="170" fill="#38bdf8" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" letter-spacing="1">React · Laravel</text>

    <rect x="340" y="155" width="100" height="22" rx="11" fill="rgba(99,102,241,0.1)" stroke="#6366f1" stroke-width="0.8"/>
    <text x="390" y="170" fill="#6366f1" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" letter-spacing="1">Python · ML</text>

    <rect x="460" y="155" width="120" height="22" rx="11" fill="rgba(0,255,65,0.08)" stroke="#00ff41" stroke-width="0.8"/>
    <text x="520" y="170" fill="#00ff41" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" letter-spacing="1">Open Source 🔥</text>

    <!-- Stats bar -->
    <text x="430" y="215" fill="#475569" font-size="9" font-family="'Courier New',monospace" text-anchor="middle">
      ── SYSTEM STATUS ─────────────────────────────────────────────
    </text>

    <!-- Stat items -->
    <text x="170" y="240" fill="#64748b" font-size="9" font-family="'Courier New',monospace" text-anchor="middle">REPOS</text>
    <text x="170" y="255" fill="#00ff41" font-size="14" font-family="'Courier New',monospace" text-anchor="middle" font-weight="bold" filter="url(#softGlow)">14+</text>

    <line x1="245" y1="232" x2="245" y2="260" stroke="#1e293b" stroke-width="1"/>

    <text x="315" y="240" fill="#64748b" font-size="9" font-family="'Courier New',monospace" text-anchor="middle">COMMITS</text>
    <text x="315" y="255" fill="#38bdf8" font-size="14" font-family="'Courier New',monospace" text-anchor="middle" font-weight="bold" filter="url(#softGlow)">270+</text>

    <line x1="390" y1="232" x2="390" y2="260" stroke="#1e293b" stroke-width="1"/>

    <text x="430" y="240" fill="#64748b" font-size="9" font-family="'Courier New',monospace" text-anchor="middle">STARS</text>
    <text x="430" y="255" fill="#6366f1" font-size="14" font-family="'Courier New',monospace" text-anchor="middle" font-weight="bold" filter="url(#softGlow)">14</text>

    <line x1="475" y1="232" x2="475" y2="260" stroke="#1e293b" stroke-width="1"/>

    <text x="545" y="240" fill="#64748b" font-size="9" font-family="'Courier New',monospace" text-anchor="middle">LOCATION</text>
    <text x="545" y="255" fill="#f59e0b" font-size="11" font-family="'Courier New',monospace" text-anchor="middle" font-weight="bold">🇮🇩 INDONESIA</text>

    <line x1="620" y1="232" x2="620" y2="260" stroke="#1e293b" stroke-width="1"/>

    <text x="690" y="240" fill="#64748b" font-size="9" font-family="'Courier New',monospace" text-anchor="middle">STATUS</text>
    <text x="690" y="255" fill="#00ff41" font-size="11" font-family="'Courier New',monospace" text-anchor="middle" font-weight="bold">● AVAILABLE</text>

    <!-- Bottom separator -->
    <line x1="40" y1="270" x2="820" y2="270" stroke="#1e293b" stroke-width="0.8" opacity="0.8"/>
    <text x="430" y="278" fill="#334155" font-size="8" font-family="'Courier New',monospace" text-anchor="middle">
      github.com/Sahal111 · X_proff · Building cool stuff since 2023
    </text>
  </g>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   TYPING ANIMATION                      -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=2800&pause=700&color=00FF41&background=0D111700&center=true&vCenter=true&multiline=false&width=700&lines=root%40Sahal111%3A~%24+whoami;Full-Stack+Developer+%F0%9F%9A%80;React+%7C+Laravel+%7C+Python+%7C+ML;Building+the+Future+from+Indonesia+%F0%9F%87%AE%F0%9F%87%A9;Open+Source+Enthusiast+%E2%9D%A4%EF%B8%8F;Always+learning%2C+always+building+%E2%9A%A1)](https://git.io/typing-svg)

</div>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                 VISITOR + SOCIAL BADGES                 -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=Sahal111&style=for-the-badge&color=00ff41&labelColor=0d1117&label=PROFILE+VIEWS)](https://github.com/Sahal111)
[![GitHub followers](https://img.shields.io/github/followers/Sahal111?style=for-the-badge&color=38bdf8&labelColor=0d1117&label=FOLLOWERS)](https://github.com/Sahal111?tab=followers)
[![GitHub stars](https://img.shields.io/github/stars/Sahal111?style=for-the-badge&color=6366f1&labelColor=0d1117&label=TOTAL+STARS)](https://github.com/Sahal111)
[![Status](https://img.shields.io/badge/STATUS-OPEN_FOR_COLLAB-00ff41?style=for-the-badge&labelColor=0d1117)](https://github.com/Sahal111)

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--            TERMINAL SIMULATION (whoami, etc.)           -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="780" height="480" viewBox="0 0 780 480" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="termBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"  stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#060d0d"/>
    </linearGradient>
    <filter id="termGlow">
      <feGaussianBlur stdDeviation="1.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="termClip">
      <rect x="0" y="0" width="780" height="480" rx="12" ry="12"/>
    </clipPath>
  </defs>

  <g clip-path="url(#termClip)">
    <!-- Terminal background -->
    <rect width="780" height="480" fill="url(#termBg)"/>

    <!-- Title bar -->
    <rect x="0" y="0" width="780" height="36" fill="#161b22"/>
    <rect x="0" y="36" width="780" height="1" fill="#21262d"/>

    <!-- Traffic lights -->
    <circle cx="22" cy="18" r="6" fill="#ff5f57"/>
    <circle cx="42" cy="18" r="6" fill="#febc2e"/>
    <circle cx="62" cy="18" r="6" fill="#28c840"/>

    <!-- Terminal title -->
    <text x="390" y="23" fill="#8b949e" font-size="12" font-family="'SF Mono','Courier New',monospace" text-anchor="middle">
      bash — sahal111@matrix: ~/portfolio
    </text>

    <!-- Tab indicator -->
    <rect x="300" y="32" width="180" height="4" fill="#00ff41" rx="2">
      <animate attributeName="opacity" values="1;0.5;1" dur="3s" repeatCount="indefinite"/>
    </rect>

    <!-- ── LINE 1: prompt + whoami ── -->
    <text x="24" y="72" font-family="'Courier New',monospace" font-size="13" fill="#00ff41" filter="url(#termGlow)">
      <tspan fill="#6366f1">┌──(</tspan><tspan fill="#38bdf8">sahal111</tspan><tspan fill="#6366f1">㉿</tspan><tspan fill="#00ff41">matrix</tspan><tspan fill="#6366f1">)-[</tspan><tspan fill="#f59e0b">~/portfolio</tspan><tspan fill="#6366f1">]</tspan>
    </text>
    <text x="24" y="90" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">
      └─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> whoami</tspan>
    </text>
    <text x="24" y="110" font-family="'Courier New',monospace" font-size="13" fill="#94a3b8">
      ► <tspan fill="#38bdf8">Sahal</tspan> — Full-Stack Developer &amp; ML Enthusiast from Indonesia 🇮🇩
    </text>
    <text x="24" y="128" font-family="'Courier New',monospace" font-size="12" fill="#64748b">
      <tspan fill="#00ff41">  ✓</tspan> Laravel · React · Python · MySQL · TailwindCSS
    </text>
    <text x="24" y="146" font-family="'Courier New',monospace" font-size="12" fill="#64748b">
      <tspan fill="#00ff41">  ✓</tspan> 270+ commits · 14 repos · Open for collaboration
    </text>

    <!-- Separator -->
    <line x1="24" y1="158" x2="756" y2="158" stroke="#21262d" stroke-width="0.8"/>

    <!-- ── LINE 2: skills ── -->
    <text x="24" y="178" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">
      └─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> cat skills.json</tspan>
    </text>
    <text x="24" y="196" font-family="'Courier New',monospace" font-size="11" fill="#64748b">{</text>
    <text x="40" y="212" font-family="'Courier New',monospace" font-size="11">
      <tspan fill="#6366f1">"frontend"</tspan><tspan fill="#94a3b8">: [</tspan>
      <tspan fill="#f59e0b">"React"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"Next.js"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"TailwindCSS"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"TypeScript"</tspan><tspan fill="#94a3b8">],</tspan>
    </text>
    <text x="40" y="228" font-family="'Courier New',monospace" font-size="11">
      <tspan fill="#6366f1">"backend"</tspan><tspan fill="#94a3b8">: [</tspan>
      <tspan fill="#f59e0b">"Laravel"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"PHP"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"Node.js"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"Python"</tspan><tspan fill="#94a3b8">],</tspan>
    </text>
    <text x="40" y="244" font-family="'Courier New',monospace" font-size="11">
      <tspan fill="#6366f1">"database"</tspan><tspan fill="#94a3b8">: [</tspan>
      <tspan fill="#f59e0b">"MySQL"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"PostgreSQL"</tspan><tspan fill="#94a3b8">],</tspan>
    </text>
    <text x="40" y="260" font-family="'Courier New',monospace" font-size="11">
      <tspan fill="#6366f1">"ai_ml"</tspan><tspan fill="#94a3b8">: [</tspan>
      <tspan fill="#f59e0b">"scikit-learn"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"Pandas"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"Jupyter"</tspan><tspan fill="#94a3b8">],</tspan>
    </text>
    <text x="40" y="276" font-family="'Courier New',monospace" font-size="11">
      <tspan fill="#6366f1">"tools"</tspan><tspan fill="#94a3b8">: [</tspan>
      <tspan fill="#f59e0b">"Git"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"VS Code"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"Figma"</tspan><tspan fill="#94a3b8">, </tspan>
      <tspan fill="#f59e0b">"Postman"</tspan><tspan fill="#94a3b8">]</tspan>
    </text>
    <text x="24" y="292" font-family="'Courier New',monospace" font-size="11" fill="#64748b">}</text>

    <!-- Separator -->
    <line x1="24" y1="302" x2="756" y2="302" stroke="#21262d" stroke-width="0.8"/>

    <!-- ── LINE 3: projects ── -->
    <text x="24" y="320" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">
      └─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> ls projects/ --color</tspan>
    </text>
    <text x="24" y="338" font-family="'Courier New',monospace" font-size="12">
      <tspan fill="#38bdf8">sneakershead/</tspan><tspan fill="#475569">     </tspan>
      <tspan fill="#38bdf8">UTS_ML_Sahal/</tspan><tspan fill="#475569">     </tspan>
      <tspan fill="#38bdf8">RPL_Group1/</tspan>
    </text>
    <text x="24" y="356" font-family="'Courier New',monospace" font-size="12">
      <tspan fill="#f59e0b">Challenge_Frontend/</tspan><tspan fill="#475569">  </tspan>
      <tspan fill="#6366f1">[WIP]</tspan><tspan fill="#38bdf8"> school-erp/</tspan><tspan fill="#475569">   </tspan>
      <tspan fill="#6366f1">[WIP]</tspan><tspan fill="#38bdf8"> ai-project/</tspan>
    </text>

    <!-- Separator -->
    <line x1="24" y1="368" x2="756" y2="368" stroke="#21262d" stroke-width="0.8"/>

    <!-- ── LINE 4: status ── -->
    <text x="24" y="386" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">
      └─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> status --verbose</tspan>
    </text>
    <text x="24" y="404" font-family="'Courier New',monospace" font-size="12" fill="#94a3b8">
      <tspan fill="#00ff41">  [ON]</tspan>  Currently building: <tspan fill="#38bdf8">School ERP System</tspan>
    </text>
    <text x="24" y="420" font-family="'Courier New',monospace" font-size="12" fill="#94a3b8">
      <tspan fill="#00ff41">  [ON]</tspan>  Learning: <tspan fill="#6366f1">AI/ML · Clean Architecture · Docker</tspan>
    </text>
    <text x="24" y="436" font-family="'Courier New',monospace" font-size="12" fill="#94a3b8">
      <tspan fill="#00ff41">  [ON]</tspan>  Open to: <tspan fill="#f59e0b">Collaboration · Freelance · Internship</tspan>
    </text>

    <!-- Blinking cursor -->
    <text x="24" y="460" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">
      └─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> _</tspan>
    </text>
    <rect x="60" y="448" width="8" height="14" fill="#00ff41" filter="url(#termGlow)">
      <animate attributeName="opacity" values="1;0;1" dur="1.1s" repeatCount="indefinite"/>
    </rect>
  </g>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              COMMAND PALETTE (Raycast style)            -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="580" height="260" viewBox="0 0 580 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="palBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"  stop-color="#161b22"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <filter id="palGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="palClip">
      <rect x="0" y="0" width="580" height="260" rx="14" ry="14"/>
    </clipPath>
  </defs>

  <g clip-path="url(#palClip)">
    <rect width="580" height="260" fill="url(#palBg)"/>
    <!-- Outer glow border -->
    <rect x="1" y="1" width="578" height="258" rx="13" ry="13"
          fill="none" stroke="#38bdf8" stroke-width="0.8" opacity="0.5" filter="url(#palGlow)"/>

    <!-- Search bar -->
    <rect x="16" y="16" width="548" height="42" rx="8" fill="#21262d"/>
    <rect x="16" y="16" width="548" height="42" rx="8" fill="none" stroke="#38bdf8" stroke-width="1" opacity="0.4"/>
    <!-- Command prefix -->
    <text x="36" y="43" font-family="'Courier New',monospace" font-size="16" fill="#6366f1" font-weight="bold">⌘</text>
    <text x="58" y="43" font-family="'Courier New',monospace" font-size="14" fill="#94a3b8">&gt; Type a command...</text>
    <!-- Placeholder cursor -->
    <rect x="228" y="26" width="2" height="20" fill="#38bdf8">
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
    </rect>
    <!-- Keyboard shortcut hint -->
    <rect x="508" y="26" width="40" height="22" rx="4" fill="#161b22" stroke="#334155" stroke-width="1"/>
    <text x="528" y="41" font-family="'Courier New',monospace" font-size="10" fill="#475569" text-anchor="middle">ESC</text>

    <!-- Separator -->
    <line x1="16" y1="68" x2="564" y2="68" stroke="#21262d" stroke-width="1"/>

    <!-- Section label -->
    <text x="28" y="86" font-family="'SF Pro','Helvetica',monospace" font-size="10" fill="#475569" letter-spacing="2">QUICK COMMANDS</text>

    <!-- Command item 1: about -->
    <rect x="16" y="92" width="548" height="38" rx="6" fill="#38bdf8" opacity="0.05"/>
    <rect x="16" y="92" width="3" height="38" rx="1" fill="#38bdf8"/>
    <text x="34" y="107" font-family="'Courier New',monospace" font-size="12" fill="#00ff41">▶</text>
    <text x="50" y="107" font-family="'Courier New',monospace" font-size="13" fill="#e2e8f0">about</text>
    <text x="50" y="122" font-family="'Courier New',monospace" font-size="10" fill="#475569">Open Sahal's profile and background</text>
    <rect x="520" y="100" width="36" height="20" rx="4" fill="#161b22" stroke="#334155" stroke-width="1"/>
    <text x="538" y="114" font-family="'Courier New',monospace" font-size="9" fill="#38bdf8" text-anchor="middle">↵</text>

    <!-- Command item 2: projects -->
    <rect x="16" y="136" width="548" height="38" rx="6" fill="transparent"/>
    <text x="34" y="151" font-family="'Courier New',monospace" font-size="12" fill="#6366f1">▶</text>
    <text x="50" y="151" font-family="'Courier New',monospace" font-size="13" fill="#94a3b8">projects</text>
    <text x="50" y="166" font-family="'Courier New',monospace" font-size="10" fill="#475569">Browse all featured repositories</text>
    <rect x="518" y="143" width="42" height="20" rx="4" fill="#161b22" stroke="#21262d" stroke-width="1"/>
    <text x="539" y="157" font-family="'Courier New',monospace" font-size="9" fill="#475569" text-anchor="middle">⌘ P</text>

    <!-- Command item 3: contact -->
    <rect x="16" y="180" width="548" height="38" rx="6" fill="transparent"/>
    <text x="34" y="195" font-family="'Courier New',monospace" font-size="12" fill="#f59e0b">▶</text>
    <text x="50" y="195" font-family="'Courier New',monospace" font-size="13" fill="#94a3b8">contact</text>
    <text x="50" y="210" font-family="'Courier New',monospace" font-size="10" fill="#475569">Reach out for collaboration</text>
    <rect x="518" y="187" width="42" height="20" rx="4" fill="#161b22" stroke="#21262d" stroke-width="1"/>
    <text x="539" y="201" font-family="'Courier New',monospace" font-size="9" fill="#475569" text-anchor="middle">⌘ K</text>

    <!-- Footer hint -->
    <line x1="16" y1="226" x2="564" y2="226" stroke="#21262d" stroke-width="1"/>
    <text x="28" y="246" font-family="'Courier New',monospace" font-size="9" fill="#334155">↑↓ navigate</text>
    <text x="120" y="246" font-family="'Courier New',monospace" font-size="9" fill="#334155">↵ select</text>
    <text x="196" y="246" font-family="'Courier New',monospace" font-size="9" fill="#334155">ESC close</text>
    <text x="480" y="246" font-family="'Courier New',monospace" font-size="9" fill="#38bdf8" text-anchor="end" filter="url(#palGlow)">Sahal Command Palette ⚡</text>
  </g>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    SVG DIVIDER                          -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">
<svg width="100%" height="3" viewBox="0 0 800 3" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="divGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0d1117" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#38bdf8"/>
      <stop offset="50%"  stop-color="#00ff41"/>
      <stop offset="80%"  stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="800" height="1" y="1" fill="url(#divGrad)"/>
</svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    ABOUT ME                             -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Technologist.png" width="28"/> &nbsp;About Me
</h2>

<table align="center" width="90%">
<tr>
<td width="55%" valign="top">

```yaml
# sahal.config.yml
─────────────────────────────────────
name:        "Sahal (X_proff)"
alias:       "Sahal111"
location:    "Indonesia 🇮🇩"
role:        "Full-Stack Developer"
─────────────────────────────────────
languages:
  primary:   ["PHP", "JavaScript"]
  secondary: ["Python", "TypeScript"]
  learning:  ["Go", "Rust"]

frameworks:
  love:      ["Laravel", "React"]
  exploring: ["Next.js", "FastAPI"]

focus_2025:
  - School ERP System (Laravel + React)
  - Machine Learning with Python
  - Clean Architecture & TDD
  - Open Source Contributions
─────────────────────────────────────
availability: "Open for collaboration ✅"
coffee:       "☕ Required before 10am"
```

</td>
<td width="45%" valign="top">

<br/>

🚀 &nbsp;**Passionate** about building elegant solutions with clean code

🧠 &nbsp;**Currently** deep diving into AI/ML and fullstack architecture

⚡ &nbsp;**Believer** in writing code that is readable, testable, scalable

🎓 &nbsp;**CS Student** hustling every day to level up

🌏 &nbsp;**Building** from Indonesia for the world

🔥 &nbsp;**Fun fact:** I debug faster with lo-fi music on 🎵

💡 &nbsp;**Philosophy:** `"Code is poetry, ship it with intention"`

<br/>

**Let's Connect:**

[![GitHub](https://img.shields.io/badge/GitHub-Sahal111-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Sahal111)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-sahal111-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sahal111)
[![Instagram](https://img.shields.io/badge/Instagram-X__proff-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/sahal111)
[![Email](https://img.shields.io/badge/Gmail-contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sahal@gmail.com)

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                  CURRENT FOCUS CARDS                    -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="780" height="130" viewBox="0 0 780 130" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="card1bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"  stop-color="#0d2818"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="card2bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"  stop-color="#1a0d2e"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="card3bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"  stop-color="#0d1a2e"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="card4bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"  stop-color="#2e1a0d"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <filter id="cardGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Card 1: Building -->
  <rect x="0"   y="15" width="182" height="100" rx="10" fill="url(#card1bg)"/>
  <rect x="0"   y="15" width="182" height="100" rx="10" fill="none" stroke="#00ff41" stroke-width="0.8" opacity="0.6"/>
  <rect x="0"   y="15" width="3"   height="100" rx="2" fill="#00ff41" filter="url(#cardGlow)"/>
  <text x="20" y="45" font-family="'Courier New',monospace" font-size="20">🚀</text>
  <text x="48" y="45" font-family="'Courier New',monospace" font-size="10" fill="#00ff41" font-weight="bold" letter-spacing="1">BUILDING</text>
  <text x="20" y="65" font-family="'Courier New',monospace" font-size="11" fill="#e2e8f0">School ERP</text>
  <text x="20" y="82" font-family="'Courier New',monospace" font-size="10" fill="#64748b">Laravel + React</text>
  <!-- Progress bar -->
  <rect x="20"  y="95" width="144" height="4" rx="2" fill="#21262d"/>
  <rect x="20"  y="95" width="90"  height="4" rx="2" fill="#00ff41" opacity="0.8">
    <animate attributeName="width" from="0" to="90" dur="2s" fill="freeze"/>
  </rect>
  <text x="168" y="100" font-family="'Courier New',monospace" font-size="8" fill="#00ff41" text-anchor="end">62%</text>

  <!-- Card 2: Learning -->
  <rect x="198" y="15" width="182" height="100" rx="10" fill="url(#card2bg)"/>
  <rect x="198" y="15" width="182" height="100" rx="10" fill="none" stroke="#6366f1" stroke-width="0.8" opacity="0.6"/>
  <rect x="198" y="15" width="3"   height="100" rx="2" fill="#6366f1" filter="url(#cardGlow)"/>
  <text x="218" y="45" font-family="'Courier New',monospace" font-size="20">🧠</text>
  <text x="246" y="45" font-family="'Courier New',monospace" font-size="10" fill="#6366f1" font-weight="bold" letter-spacing="1">LEARNING</text>
  <text x="218" y="65" font-family="'Courier New',monospace" font-size="11" fill="#e2e8f0">AI / ML</text>
  <text x="218" y="82" font-family="'Courier New',monospace" font-size="10" fill="#64748b">Python · scikit-learn</text>
  <rect x="218" y="95" width="144" height="4" rx="2" fill="#21262d"/>
  <rect x="218" y="95" width="72"  height="4" rx="2" fill="#6366f1" opacity="0.8">
    <animate attributeName="width" from="0" to="72" dur="2.5s" fill="freeze"/>
  </rect>
  <text x="366" y="100" font-family="'Courier New',monospace" font-size="8" fill="#6366f1" text-anchor="end">50%</text>

  <!-- Card 3: Exploring -->
  <rect x="396" y="15" width="182" height="100" rx="10" fill="url(#card3bg)"/>
  <rect x="396" y="15" width="182" height="100" rx="10" fill="none" stroke="#38bdf8" stroke-width="0.8" opacity="0.6"/>
  <rect x="396" y="15" width="3"   height="100" rx="2" fill="#38bdf8" filter="url(#cardGlow)"/>
  <text x="416" y="45" font-family="'Courier New',monospace" font-size="20">⚡</text>
  <text x="444" y="45" font-family="'Courier New',monospace" font-size="10" fill="#38bdf8" font-weight="bold" letter-spacing="1">EXPLORING</text>
  <text x="416" y="65" font-family="'Courier New',monospace" font-size="11" fill="#e2e8f0">Clean Architecture</text>
  <text x="416" y="82" font-family="'Courier New',monospace" font-size="10" fill="#64748b">TDD · SOLID · DDD</text>
  <rect x="416" y="95" width="144" height="4" rx="2" fill="#21262d"/>
  <rect x="416" y="95" width="108" height="4" rx="2" fill="#38bdf8" opacity="0.8">
    <animate attributeName="width" from="0" to="108" dur="3s" fill="freeze"/>
  </rect>
  <text x="564" y="100" font-family="'Courier New',monospace" font-size="8" fill="#38bdf8" text-anchor="end">75%</text>

  <!-- Card 4: Goal -->
  <rect x="594" y="15" width="182" height="100" rx="10" fill="url(#card4bg)"/>
  <rect x="594" y="15" width="182" height="100" rx="10" fill="none" stroke="#f59e0b" stroke-width="0.8" opacity="0.6"/>
  <rect x="594" y="15" width="3"   height="100" rx="2" fill="#f59e0b" filter="url(#cardGlow)"/>
  <text x="614" y="45" font-family="'Courier New',monospace" font-size="20">🎯</text>
  <text x="642" y="45" font-family="'Courier New',monospace" font-size="10" fill="#f59e0b" font-weight="bold" letter-spacing="1">GOAL 2026</text>
  <text x="614" y="65" font-family="'Courier New',monospace" font-size="11" fill="#e2e8f0">Software Engineer</text>
  <text x="614" y="82" font-family="'Courier New',monospace" font-size="10" fill="#64748b">Full Stack · AI Track</text>
  <rect x="614" y="95" width="144" height="4" rx="2" fill="#21262d"/>
  <rect x="614" y="95" width="36"  height="4" rx="2" fill="#f59e0b" opacity="0.8">
    <animate attributeName="width" from="0" to="36" dur="1.5s" fill="freeze"/>
  </rect>
  <text x="762" y="100" font-family="'Courier New',monospace" font-size="8" fill="#f59e0b" text-anchor="end">25%</text>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    SVG DIVIDER                          -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">
<svg width="100%" height="3" viewBox="0 0 800 3" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="divGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0d1117" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#6366f1"/>
      <stop offset="50%"  stop-color="#38bdf8"/>
      <stop offset="80%"  stop-color="#00ff41"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="800" height="1" y="1" fill="url(#divGrad2)"/>
</svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    TECH STACK                           -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" width="28"/> &nbsp;Tech Stack
</h2>

<div align="center">

<!-- Languages -->
<p>
<img src="https://skillicons.dev/icons?i=php,js,ts,python,html,css&theme=dark" alt="Languages"/>
</p>

<sub><kbd>Languages</kbd></sub>

<!-- Frontend -->
<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,figma&theme=dark" alt="Frontend"/>
</p>

<sub><kbd>Frontend</kbd></sub>

<!-- Backend -->
<p>
<img src="https://skillicons.dev/icons?i=laravel,nodejs,express,fastapi&theme=dark" alt="Backend"/>
</p>

<sub><kbd>Backend</kbd></sub>

<!-- Database -->
<p>
<img src="https://skillicons.dev/icons?i=mysql,postgres,sqlite,redis&theme=dark" alt="Database"/>
</p>

<sub><kbd>Database</kbd></sub>

<!-- DevOps & Cloud -->
<p>
<img src="https://skillicons.dev/icons?i=docker,git,github,vercel,linux&theme=dark" alt="DevOps"/>
</p>

<sub><kbd>DevOps & Tools</kbd></sub>

<!-- AI & Data -->
<p>
<img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,sklearn&theme=dark" alt="AI/ML"/>
</p>

<sub><kbd>AI / ML</kbd></sub>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--            INTERACTIVE TIMELINE (SVG)                   -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="28"/> &nbsp;Journey Timeline
</h2>

<div align="center">

<svg width="700" height="520" viewBox="0 0 700 520" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="tlLine" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"   stop-color="#00ff41"/>
      <stop offset="40%"  stop-color="#38bdf8"/>
      <stop offset="70%"  stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#f59e0b" stop-opacity="0.5"/>
    </linearGradient>
    <filter id="tlGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="dotGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="700" height="520" fill="#0d1117"/>

  <!-- Title -->
  <text x="350" y="35" font-family="'Courier New',monospace" font-size="13" fill="#475569"
        text-anchor="middle" letter-spacing="4">── DEVELOPER JOURNEY ──</text>

  <!-- Timeline vertical line -->
  <line x1="350" y1="55" x2="350" y2="485" stroke="url(#tlLine)" stroke-width="2"
        stroke-dasharray="6 4" filter="url(#tlGlow)"/>

  <!-- ─── 2023: Start ─── -->
  <!-- Left card -->
  <rect x="40" y="62" width="280" height="76" rx="8" fill="#161b22"/>
  <rect x="40" y="62" width="280" height="76" rx="8" fill="none" stroke="#00ff41" stroke-width="0.8" opacity="0.6"/>
  <rect x="40" y="62" width="4"   height="76" rx="2" fill="#00ff41"/>
  <text x="60" y="84"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" font-weight="bold">2023</text>
  <text x="60" y="100" font-family="'Courier New',monospace" font-size="13" fill="#e2e8f0" font-weight="bold">Started Programming</text>
  <text x="60" y="116" font-family="'Courier New',monospace" font-size="10" fill="#64748b">HTML · CSS · JavaScript</text>
  <text x="60" y="130" font-family="'Courier New',monospace" font-size="10" fill="#64748b">First web projects 🎉</text>
  <!-- Connector line -->
  <line x1="320" y1="100" x2="340" y2="100" stroke="#00ff41" stroke-width="1.5" opacity="0.7"/>
  <!-- Timeline dot -->
  <circle cx="350" cy="100" r="8"  fill="#0d1117" stroke="#00ff41" stroke-width="2"/>
  <circle cx="350" cy="100" r="4"  fill="#00ff41" filter="url(#dotGlow)">
    <animate attributeName="r" values="4;6;4" dur="2s" repeatCount="indefinite"/>
  </circle>

  <!-- ─── 2024 Early: Laravel ─── -->
  <!-- Right card -->
  <rect x="380" y="152" width="280" height="76" rx="8" fill="#161b22"/>
  <rect x="380" y="152" width="280" height="76" rx="8" fill="none" stroke="#38bdf8" stroke-width="0.8" opacity="0.6"/>
  <rect x="676" y="152" width="4"   height="76" rx="2" fill="#38bdf8"/>
  <text x="400" y="174" font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" font-weight="bold">2024 — Q1</text>
  <text x="400" y="190" font-family="'Courier New',monospace" font-size="13" fill="#e2e8f0" font-weight="bold">Laravel & PHP Backend</text>
  <text x="400" y="206" font-family="'Courier New',monospace" font-size="10" fill="#64748b">MVC · REST API · Auth</text>
  <text x="400" y="220" font-family="'Courier New',monospace" font-size="10" fill="#64748b">First real project 🛠️</text>
  <!-- Connector -->
  <line x1="360" y1="190" x2="380" y2="190" stroke="#38bdf8" stroke-width="1.5" opacity="0.7"/>
  <!-- Dot -->
  <circle cx="350" cy="190" r="8"  fill="#0d1117" stroke="#38bdf8" stroke-width="2"/>
  <circle cx="350" cy="190" r="4"  fill="#38bdf8" filter="url(#dotGlow)">
    <animate attributeName="r" values="4;6;4" dur="2.4s" repeatCount="indefinite"/>
  </circle>

  <!-- ─── 2024 Mid: React ─── -->
  <!-- Left card -->
  <rect x="40" y="242" width="280" height="76" rx="8" fill="#161b22"/>
  <rect x="40" y="242" width="280" height="76" rx="8" fill="none" stroke="#6366f1" stroke-width="0.8" opacity="0.6"/>
  <rect x="40" y="242" width="4"   height="76" rx="2" fill="#6366f1"/>
  <text x="60" y="264" font-family="'Courier New',monospace" font-size="11" fill="#6366f1" font-weight="bold">2024 — Q3</text>
  <text x="60" y="280" font-family="'Courier New',monospace" font-size="13" fill="#e2e8f0" font-weight="bold">React Frontend + ML</text>
  <text x="60" y="296" font-family="'Courier New',monospace" font-size="10" fill="#64748b">React · Python · Pandas</text>
  <text x="60" y="310" font-family="'Courier New',monospace" font-size="10" fill="#64748b">UTS ML project submitted 📊</text>
  <!-- Connector -->
  <line x1="320" y1="280" x2="340" y2="280" stroke="#6366f1" stroke-width="1.5" opacity="0.7"/>
  <!-- Dot -->
  <circle cx="350" cy="280" r="8"  fill="#0d1117" stroke="#6366f1" stroke-width="2"/>
  <circle cx="350" cy="280" r="4"  fill="#6366f1" filter="url(#dotGlow)">
    <animate attributeName="r" values="4;6;4" dur="1.8s" repeatCount="indefinite"/>
  </circle>

  <!-- ─── 2025: Fullstack ─── -->
  <!-- Right card -->
  <rect x="380" y="332" width="280" height="76" rx="8" fill="#161b22"/>
  <rect x="380" y="332" width="280" height="76" rx="8" fill="none" stroke="#f59e0b" stroke-width="0.8" opacity="0.6"/>
  <rect x="676" y="332" width="4"   height="76" rx="2" fill="#f59e0b"/>
  <text x="400" y="354" font-family="'Courier New',monospace" font-size="11" fill="#f59e0b" font-weight="bold">2025 — NOW</text>
  <text x="400" y="370" font-family="'Courier New',monospace" font-size="13" fill="#e2e8f0" font-weight="bold">Fullstack + Architecture</text>
  <text x="400" y="386" font-family="'Courier New',monospace" font-size="10" fill="#64748b">Laravel + React + Docker</text>
  <text x="400" y="402" font-family="'Courier New',monospace" font-size="10" fill="#64748b">Clean Code · Open Source 🔥</text>
  <!-- Connector -->
  <line x1="360" y1="370" x2="380" y2="370" stroke="#f59e0b" stroke-width="1.5" opacity="0.7"/>
  <!-- Dot (pulsing - current) -->
  <circle cx="350" cy="370" r="10" fill="#0d1117" stroke="#f59e0b" stroke-width="2"/>
  <circle cx="350" cy="370" r="5"  fill="#f59e0b" filter="url(#dotGlow)">
    <animate attributeName="r"       values="5;8;5"   dur="1.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.4;1" dur="1.2s" repeatCount="indefinite"/>
  </circle>

  <!-- ─── Future ─── -->
  <!-- Left card — semi-transparent / future -->
  <rect x="40" y="422" width="280" height="76" rx="8" fill="#161b22" opacity="0.5"/>
  <rect x="40" y="422" width="280" height="76" rx="8" fill="none" stroke="#94a3b8" stroke-width="0.6" stroke-dasharray="4 3" opacity="0.4"/>
  <text x="60" y="444" font-family="'Courier New',monospace" font-size="11" fill="#475569" font-weight="bold">2026 — FUTURE</text>
  <text x="60" y="460" font-family="'Courier New',monospace" font-size="13" fill="#64748b" font-weight="bold">Software / AI Engineer</text>
  <text x="60" y="476" font-family="'Courier New',monospace" font-size="10" fill="#334155">Building for the world 🌍</text>
  <text x="60" y="490" font-family="'Courier New',monospace" font-size="10" fill="#334155">Launching products · AI 🤖</text>
  <!-- Connector -->
  <line x1="320" y1="460" x2="340" y2="460" stroke="#475569" stroke-width="1" stroke-dasharray="3 3" opacity="0.4"/>
  <!-- Dot -->
  <circle cx="350" cy="460" r="8" fill="#0d1117" stroke="#475569" stroke-width="1.5" stroke-dasharray="3 3" opacity="0.5"/>
  <circle cx="350" cy="460" r="3" fill="#475569" opacity="0.5"/>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              FEATURED PROJECTS                          -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="28"/> &nbsp;Featured Projects
</h2>

<div align="center">

<!-- Row 1 -->
<a href="https://github.com/Sahal111/sneakershead">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=sneakershead&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=38bdf8&text_color=94a3b8&border_radius=10" />
</a>
<a href="https://github.com/Sahal111/UTS_ML_Sahal">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=UTS_ML_Sahal&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=6366f1&text_color=94a3b8&border_radius=10" />
</a>

<!-- Row 2 -->
<a href="https://github.com/Sahal111/Challenge_Frontend_React">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=Challenge_Frontend_React&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=6366f1&icon_color=00ff41&text_color=94a3b8&border_radius=10" />
</a>
<a href="https://github.com/Sahal111/RPL_Group1">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Sahal111&repo=RPL_Group1&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=f59e0b&icon_color=38bdf8&text_color=94a3b8&border_radius=10" />
</a>

</div>

<!-- Custom Project Cards for WIP projects -->
<div align="center">

<svg width="760" height="100" viewBox="0 0 760 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="wipGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"  stop-color="#0d1a2e"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="wipGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"  stop-color="#1a0d2e"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
  </defs>

  <!-- WIP Project 1: School ERP -->
  <rect x="0"   y="5" width="368" height="88" rx="10" fill="url(#wipGrad1)"/>
  <rect x="0"   y="5" width="368" height="88" rx="10" fill="none" stroke="#38bdf8" stroke-width="0.8" opacity="0.5" stroke-dasharray="5 3"/>
  <text x="20" y="30"  font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" font-weight="bold">📚 School ERP System</text>
  <rect x="260" y="18" width="36" height="16" rx="8" fill="#0d2818" stroke="#00ff41" stroke-width="0.7"/>
  <text x="278" y="29" font-family="'Courier New',monospace" font-size="8" fill="#00ff41" text-anchor="middle">WIP</text>
  <text x="20" y="50"  font-family="'Courier New',monospace" font-size="10" fill="#64748b">Comprehensive school management system</text>
  <text x="20" y="65"  font-family="'Courier New',monospace" font-size="10" fill="#64748b">Stack: Laravel · React · MySQL · Filament</text>
  <rect x="20" y="78" width="80"  height="8" rx="4" fill="#21262d"/>
  <rect x="20" y="78" width="50"  height="8" rx="4" fill="#38bdf8" opacity="0.7">
    <animate attributeName="width" from="0" to="50" dur="2s" fill="freeze"/>
  </rect>
  <text x="108" y="86" font-family="'Courier New',monospace" font-size="8" fill="#38bdf8">62% done</text>

  <!-- WIP Project 2: AI Assistant -->
  <rect x="392" y="5" width="368" height="88" rx="10" fill="url(#wipGrad2)"/>
  <rect x="392" y="5" width="368" height="88" rx="10" fill="none" stroke="#6366f1" stroke-width="0.8" opacity="0.5" stroke-dasharray="5 3"/>
  <text x="412" y="30"  font-family="'Courier New',monospace" font-size="11" fill="#6366f1" font-weight="bold">🤖 AI Chat Assistant</text>
  <rect x="648" y="18" width="36" height="16" rx="8" fill="#1a0d2e" stroke="#6366f1" stroke-width="0.7"/>
  <text x="666" y="29" font-family="'Courier New',monospace" font-size="8" fill="#6366f1" text-anchor="middle">WIP</text>
  <text x="412" y="50"  font-family="'Courier New',monospace" font-size="10" fill="#64748b">Intelligent assistant with custom LLM</text>
  <text x="412" y="65"  font-family="'Courier New',monospace" font-size="10" fill="#64748b">Stack: Python · FastAPI · React · OpenAI</text>
  <rect x="412" y="78" width="80"  height="8" rx="4" fill="#21262d"/>
  <rect x="412" y="78" width="20"  height="8" rx="4" fill="#6366f1" opacity="0.7">
    <animate attributeName="width" from="0" to="20" dur="1.5s" fill="freeze"/>
  </rect>
  <text x="500" y="86" font-family="'Courier New',monospace" font-size="8" fill="#6366f1">25% done</text>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--               GITHUB ANALYTICS                         -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="28"/> &nbsp;GitHub Analytics
</h2>

<div align="center">

<!-- Stats + Languages -->
<img src="https://github-readme-stats.vercel.app/api?username=Sahal111&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&icon_color=38bdf8&text_color=94a3b8&ring_color=00ff41&border_radius=10&custom_title=Sahal111%27s+GitHub+Stats&include_all_commits=true&count_private=true" height="170" />
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sahal111&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8&border_radius=10&langs_count=8" height="170" />

</div>

<br/>

<!-- Streak -->
<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Sahal111&theme=terminal&hide_border=true&background=0d1117&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&sideLabels=00cc33&dates=009922&sideNums=00ff41&currStreakNum=ffffff&border_radius=10" />

</div>

<br/>

<!-- Activity Graph -->
<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Sahal111&bg_color=0d1117&color=00ff41&line=38bdf8&point=ffffff&area=true&hide_border=true&custom_title=Sahal111%27s+Contribution+Graph&radius=10" width="92%"/>

</div>

<br/>

<!-- Trophy -->
<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Sahal111&theme=matrix&no-frame=true&no-bg=true&row=1&column=6" />

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--           CONTRIBUTION SNAKE ANIMATION                  -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<!-- 
  ⚙️ SNAKE ANIMATION SETUP:
  Create this GitHub Actions workflow → .github/workflows/snake.yml
  ─────────────────────────────────────────────────────────────────
  name: Generate Snake Animation
  on:
    schedule:
      - cron: "0 */12 * * *"
    workflow_dispatch:
  jobs:
    generate:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: Sahal111
            outputs: |
              dist/snake.svg
              dist/snake-dark.svg?palette=github-dark
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ─────────────────────────────────────────────────────────────────
  After running, use this URL (replace YOUR_USERNAME):
-->

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/Sahal111/Sahal111/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sahal111/Sahal111/output/snake.svg"/>
  <img alt="Snake animation" src="https://raw.githubusercontent.com/Sahal111/Sahal111/output/snake.svg"/>
</picture>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--          NOW PLAYING + CODING STATUS                    -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Headphone.png" width="28"/> &nbsp;Live Status
</h2>

<div align="center">

<!--
  ♫ SPOTIFY NOW PLAYING SETUP:
  ─────────────────────────────────────────────────────────────────
  1. Fork → github.com/novatorem/novatorem
  2. Deploy to Vercel with your Spotify credentials
  3. Add SPOTIFY_CLIENT_ID, SPOTIFY_CLIENT_SECRET, SPOTIFY_REFRESH_TOKEN to Vercel env
  4. Replace YOUR_VERCEL_APP with your deployment URL below
  ─────────────────────────────────────────────────────────────────
  <img src="https://YOUR_VERCEL_APP.vercel.app/api/spotify" width="380"/>
  ─────────────────────────────────────────────────────────────────
  For now, using the badge placeholder:
-->

[![Spotify](https://img.shields.io/badge/Spotify-Lo--fi%20Beats%20🎵-1DB954?style=for-the-badge&logo=spotify&logoColor=white&labelColor=0d1117)](https://open.spotify.com)

<!--
  ⚡ WAKATIME SETUP:
  ─────────────────────────────────────────────────────────────────
  1. Sign up at wakatime.com
  2. Install WakaTime plugin in VS Code
  3. Add WAKATIME_API_KEY to GitHub Secrets
  4. Create .github/workflows/waka-readme.yml
  ─────────────────────────────────────────────────────────────────
  Then uncomment:
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=Sahal111&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00ff41&text_color=94a3b8&border_radius=10&layout=compact"/>
-->

</div>

<br/>

<!-- Currently Coding Status Card (SVG) -->
<div align="center">

<svg width="560" height="80" viewBox="0 0 560 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="codingBg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"  stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <filter id="codingGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="codingClip">
      <rect x="0" y="0" width="560" height="80" rx="10" ry="10"/>
    </clipPath>
  </defs>

  <g clip-path="url(#codingClip)">
    <rect width="560" height="80" fill="url(#codingBg)"/>
    <rect width="560" height="80" fill="none" stroke="#00ff41" stroke-width="0.8" opacity="0.4"/>

    <!-- Pulsing live dot -->
    <circle cx="24" cy="40" r="6" fill="#00ff41" filter="url(#codingGlow)">
      <animate attributeName="r"       values="6;9;6"   dur="1.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="24" cy="40" r="3" fill="#00ff41"/>

    <text x="44" y="34" font-family="'Courier New',monospace" font-size="10" fill="#475569">CURRENTLY CODING</text>
    <text x="44" y="54" font-family="'Courier New',monospace" font-size="14" fill="#e2e8f0" font-weight="bold">School ERP System</text>

    <!-- Separator -->
    <line x1="240" y1="15" x2="240" y2="65" stroke="#21262d" stroke-width="1"/>

    <text x="260" y="30" font-family="'Courier New',monospace" font-size="10" fill="#475569">EDITOR</text>
    <text x="260" y="46" font-family="'Courier New',monospace" font-size="12" fill="#38bdf8">VS Code</text>

    <line x1="370" y1="15" x2="370" y2="65" stroke="#21262d" stroke-width="1"/>

    <text x="390" y="30" font-family="'Courier New',monospace" font-size="10" fill="#475569">LANGUAGE</text>
    <text x="390" y="46" font-family="'Courier New',monospace" font-size="12" fill="#f59e0b">PHP · JS</text>

    <line x1="480" y1="15" x2="480" y2="65" stroke="#21262d" stroke-width="1"/>

    <text x="498" y="30" font-family="'Courier New',monospace" font-size="10" fill="#475569">OS</text>
    <text x="498" y="46" font-family="'Courier New',monospace" font-size="12" fill="#6366f1">Linux 🐧</text>
  </g>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    SVG DIVIDER                          -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">
<svg width="100%" height="3" viewBox="0 0 800 3" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="divGrad3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#0d1117" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#f59e0b"/>
      <stop offset="50%"  stop-color="#00ff41"/>
      <stop offset="80%"  stop-color="#38bdf8"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="800" height="1" y="1" fill="url(#divGrad3)"/>
</svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--               ACHIEVEMENT SECTION                       -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Trophy.png" width="28"/> &nbsp;Achievements
</h2>

<div align="center">

<svg width="780" height="180" viewBox="0 0 780 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="achGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="780" height="180" fill="#0d1117"/>

  <!-- Achievement 1: Code Warrior -->
  <rect x="10"  y="20" width="140" height="140" rx="12" fill="#161b22"/>
  <rect x="10"  y="20" width="140" height="140" rx="12" fill="none" stroke="#f59e0b" stroke-width="1" opacity="0.7"/>
  <text x="80"  y="72"  font-size="30" text-anchor="middle">⚔️</text>
  <text x="80"  y="100" font-family="'Courier New',monospace" font-size="10" fill="#f59e0b" text-anchor="middle" font-weight="bold">CODE WARRIOR</text>
  <text x="80"  y="116" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">270+ Commits</text>
  <text x="80"  y="132" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">Consistent Pusher</text>
  <circle cx="148" cy="28" r="10" fill="#161b22" stroke="#f59e0b" stroke-width="1"/>
  <text x="148" y="32"  font-family="'Courier New',monospace" font-size="8" fill="#f59e0b" text-anchor="middle">🔥</text>

  <!-- Achievement 2: Open Source -->
  <rect x="166" y="20" width="140" height="140" rx="12" fill="#161b22"/>
  <rect x="166" y="20" width="140" height="140" rx="12" fill="none" stroke="#00ff41" stroke-width="1" opacity="0.7"/>
  <text x="236" y="72"  font-size="30" text-anchor="middle">🌱</text>
  <text x="236" y="100" font-family="'Courier New',monospace" font-size="10" fill="#00ff41" text-anchor="middle" font-weight="bold">OPEN SOURCE</text>
  <text x="236" y="116" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">14 Public Repos</text>
  <text x="236" y="132" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">Community Builder</text>

  <!-- Achievement 3: Full Stack -->
  <rect x="322" y="20" width="140" height="140" rx="12" fill="#161b22"/>
  <rect x="322" y="20" width="140" height="140" rx="12" fill="none" stroke="#38bdf8" stroke-width="1" opacity="0.7"/>
  <text x="392" y="72"  font-size="30" text-anchor="middle">🚀</text>
  <text x="392" y="100" font-family="'Courier New',monospace" font-size="10" fill="#38bdf8" text-anchor="middle" font-weight="bold">FULL-STACK</text>
  <text x="392" y="116" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">React + Laravel</text>
  <text x="392" y="132" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">End-to-End Dev</text>

  <!-- Achievement 4: ML Explorer -->
  <rect x="478" y="20" width="140" height="140" rx="12" fill="#161b22"/>
  <rect x="478" y="20" width="140" height="140" rx="12" fill="none" stroke="#6366f1" stroke-width="1" opacity="0.7"/>
  <text x="548" y="72"  font-size="30" text-anchor="middle">🧠</text>
  <text x="548" y="100" font-family="'Courier New',monospace" font-size="10" fill="#6366f1" text-anchor="middle" font-weight="bold">ML EXPLORER</text>
  <text x="548" y="116" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">Python · Jupyter</text>
  <text x="548" y="132" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">Scikit · Pandas</text>

  <!-- Achievement 5: Rapid Learner -->
  <rect x="634" y="20" width="140" height="140" rx="12" fill="#161b22"/>
  <rect x="634" y="20" width="140" height="140" rx="12" fill="none" stroke="#14b8a6" stroke-width="1" opacity="0.7"/>
  <text x="704" y="72"  font-size="30" text-anchor="middle">⚡</text>
  <text x="704" y="100" font-family="'Courier New',monospace" font-size="10" fill="#14b8a6" text-anchor="middle" font-weight="bold">SPEED CODER</text>
  <text x="704" y="116" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">Multi-Tech Stack</text>
  <text x="704" y="132" font-family="'Courier New',monospace" font-size="9"  fill="#64748b" text-anchor="middle">2yr Journey</text>
</svg>

</div>

<br/>

<!-- GitHub Trophy -->
<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=Sahal111&theme=matrix&no-frame=true&no-bg=true&row=2&column=4&margin-w=10&margin-h=10"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--               EXTERNAL WIDGETS                          -->
<!-- ═══════════════════════════════════════════════════════ -->

<!--
  📊 LEETCODE WIDGET (activate if you have LeetCode account):
  ─────────────────────────────────────────────────────────────────
  <div align="center">
  <img src="https://leetcard.jacoblin.com/Sahal111?theme=dark&font=Roboto+Mono&ext=contest&width=450&border=0&radius=10&bg=0d1117"/>
  </div>

  ⚔️ CODEWARS BADGE (activate after creating account at codewars.com/users/Sahal111):
  ─────────────────────────────────────────────────────────────────
  <div align="center">
  <img src="https://www.codewars.com/users/Sahal111/badges/large"/>
  </div>

  🏅 HOLOPIN BADGES (activate after earning badges at holopin.io):
  ─────────────────────────────────────────────────────────────────
  <a href="https://holopin.io/@sahal111">
    <img src="https://holopin.me/sahal111"/>
  </a>
-->

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   FUN FACTS                             -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Activities/Game%20Die.png" width="28"/> &nbsp;Fun Facts
</h2>

<div align="center">

<svg width="720" height="200" viewBox="0 0 720 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <clipPath id="funClip">
      <rect x="0" y="0" width="720" height="200" rx="12" ry="12"/>
    </clipPath>
  </defs>

  <g clip-path="url(#funClip)">
    <rect width="720" height="200" fill="#0d1117"/>
    <rect width="720" height="200" fill="none" stroke="#334155" stroke-width="0.8"/>

    <!-- Row 1 -->
    <rect x="10" y="15" width="210" height="75" rx="8" fill="#161b22"/>
    <text x="30" y="42" font-family="monospace" font-size="20">☕</text>
    <text x="58" y="42" font-family="'Courier New',monospace" font-size="11" fill="#f59e0b" font-weight="bold">Coffee First</text>
    <text x="30" y="60" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">Can't compile without</text>
    <text x="30" y="75" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">at least 2 cups/day ☕</text>

    <rect x="235" y="15" width="210" height="75" rx="8" fill="#161b22"/>
    <text x="255" y="42" font-family="monospace" font-size="20">🎵</text>
    <text x="283" y="42" font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" font-weight="bold">Lo-fi Dev</text>
    <text x="255" y="60" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">Productivity x10 with</text>
    <text x="255" y="75" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">Lo-fi hip hop beats 🎧</text>

    <rect x="460" y="15" width="250" height="75" rx="8" fill="#161b22"/>
    <text x="480" y="42" font-family="monospace" font-size="20">🐛</text>
    <text x="508" y="42" font-family="'Courier New',monospace" font-size="11" fill="#6366f1" font-weight="bold">Bug Whisperer</text>
    <text x="480" y="60" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">99% bugs are fixed by</text>
    <text x="480" y="75" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">console.log() 🎉</text>

    <!-- Row 2 -->
    <rect x="10" y="105" width="210" height="75" rx="8" fill="#161b22"/>
    <text x="30" y="132" font-family="monospace" font-size="20">🌙</text>
    <text x="58" y="132" font-family="'Courier New',monospace" font-size="11" fill="#00ff41" font-weight="bold">Night Coder</text>
    <text x="30" y="150" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">Best ideas come at</text>
    <text x="30" y="165" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">2am, not kidding 🌙</text>

    <rect x="235" y="105" width="210" height="75" rx="8" fill="#161b22"/>
    <text x="255" y="132" font-family="monospace" font-size="20">🇮🇩</text>
    <text x="283" y="132" font-family="'Courier New',monospace" font-size="11" fill="#f59e0b" font-weight="bold">Proud Indonesian</text>
    <text x="255" y="150" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">Building tech from</text>
    <text x="255" y="165" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">Southeast Asia 🌏</text>

    <rect x="460" y="105" width="250" height="75" rx="8" fill="#161b22"/>
    <text x="480" y="132" font-family="monospace" font-size="20">🎯</text>
    <text x="508" y="132" font-family="'Courier New',monospace" font-size="11" fill="#14b8a6" font-weight="bold">Goal Setter</text>
    <text x="480" y="150" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">Every year: better code,</text>
    <text x="480" y="165" font-family="'Courier New',monospace" font-size="9"  fill="#64748b">bigger impact 💪</text>
  </g>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              RANDOM DEV QUOTE                           -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&border=true&quote=Code+is+like+humor.+When+you+have+to+explain+it%2C+it%27s+bad.&author=Cory+House" width="680" />

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--             SOCIAL & CONNECT SECTION                    -->
<!-- ═══════════════════════════════════════════════════════ -->

<h2 align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Globe%20Showing%20Asia-Australia.png" width="28"/> &nbsp;Connect With Me
</h2>

<div align="center">

<a href="https://github.com/Sahal111">
  <img src="https://img.shields.io/badge/GitHub-Sahal111-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/sahal111">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://instagram.com/sahal111">
  <img src="https://img.shields.io/badge/Instagram-@X__proff-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="mailto:sahal@gmail.com">
  <img src="https://img.shields.io/badge/Email-Say_Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"/>
</a>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              MATRIX RAIN BACKGROUND FOOTER              -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="160" viewBox="0 0 1440 160" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%"  stop-color="#0d1117" stop-opacity="0"/>
      <stop offset="30%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#060d0d"/>
    </linearGradient>
    <filter id="matrixGlow">
      <feGaussianBlur stdDeviation="1" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="1440" height="160" fill="#0d1117"/>

  <!-- Matrix rain characters (decorative) -->
  <!-- Column 1 -->
  <text x="40"  y="20"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.7" filter="url(#matrixGlow)">1</text>
  <text x="40"  y="35"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.5">0</text>
  <text x="40"  y="50"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.3">1</text>
  <text x="40"  y="65"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.15">1</text>
  <!-- Column 2 -->
  <text x="90"  y="10"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.8" filter="url(#matrixGlow)">0</text>
  <text x="90"  y="25"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.6">1</text>
  <text x="90"  y="40"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.35">0</text>
  <!-- Column 3 -->
  <text x="140" y="30"  font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" opacity="0.6" filter="url(#matrixGlow)">S</text>
  <text x="140" y="45"  font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" opacity="0.4">A</text>
  <text x="140" y="60"  font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" opacity="0.2">H</text>
  <!-- Column 4 -->
  <text x="190" y="15"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.7" filter="url(#matrixGlow)">1</text>
  <text x="190" y="30"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.5">1</text>
  <text x="190" y="45"  font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.3">1</text>
  <!-- Column 5 -->
  <text x="240" y="25"  font-family="'Courier New',monospace" font-size="11" fill="#6366f1" opacity="0.7" filter="url(#matrixGlow)">λ</text>
  <text x="240" y="40"  font-family="'Courier New',monospace" font-size="11" fill="#6366f1" opacity="0.4">∞</text>
  <!-- Repeat pattern across -->
  <text x="1260" y="20" font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.7" filter="url(#matrixGlow)">0</text>
  <text x="1260" y="35" font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.5">1</text>
  <text x="1310" y="10" font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.8" filter="url(#matrixGlow)">1</text>
  <text x="1310" y="25" font-family="'Courier New',monospace" font-size="11" fill="#00ff41" opacity="0.6">0</text>
  <text x="1360" y="30" font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" opacity="0.6" filter="url(#matrixGlow)">A</text>
  <text x="1360" y="45" font-family="'Courier New',monospace" font-size="11" fill="#38bdf8" opacity="0.4">L</text>
  <text x="1400" y="15" font-family="'Courier New',monospace" font-size="11" fill="#6366f1" opacity="0.7" filter="url(#matrixGlow)">λ</text>

  <!-- Gradient overlay -->
  <rect width="1440" height="160" fill="url(#footerBg)"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════ -->
<!--              ANIMATED WAVE + NEON FOOTER                -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="180" viewBox="0 0 1440 180" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="waveGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00ff41" stop-opacity="0.8"/>
      <stop offset="30%"  stop-color="#38bdf8" stop-opacity="0.9"/>
      <stop offset="60%"  stop-color="#6366f1" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#14b8a6" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#00ff41" stop-opacity="0.8"/>
    </linearGradient>
    <linearGradient id="waveGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#6366f1" stop-opacity="0.5"/>
      <stop offset="50%"  stop-color="#00ff41" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#38bdf8" stop-opacity="0.5"/>
    </linearGradient>
    <filter id="waveGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="1440" height="180" fill="#060d0d"/>

  <!-- Wave layer 3 (back) -->
  <path d="M0,100 C200,60 400,130 600,90 C800,50 1000,110 1200,80 C1300,65 1380,90 1440,75 L1440,180 L0,180 Z"
        fill="#6366f1" opacity="0.07"/>

  <!-- Wave layer 2 (mid) -->
  <path d="M0,110 C240,70 480,140 720,100 C960,60 1200,120 1440,90 L1440,180 L0,180 Z"
        fill="#38bdf8" opacity="0.06"/>

  <!-- Wave layer 1 (front animated) - neon line -->
  <path d="M0,120 C180,80 360,150 540,110 C720,70 900,130 1080,100 C1260,70 1380,110 1440,95 L1440,100 C1380,115 1260,75 1080,105 C900,135 720,75 540,115 C360,155 180,85 0,125 Z"
        fill="url(#waveGrad1)" opacity="0.15" filter="url(#waveGlow)">
    <animateTransform attributeName="transform" type="translate" values="0,0; -30,5; 0,0" dur="6s" repeatCount="indefinite"/>
  </path>

  <!-- Neon wave line -->
  <path d="M0,120 C180,80 360,150 540,110 C720,70 900,130 1080,100 C1260,70 1380,110 1440,95"
        fill="none" stroke="url(#waveGrad1)" stroke-width="1.5" filter="url(#waveGlow)">
    <animateTransform attributeName="transform" type="translate" values="0,0; -20,3; 0,0" dur="6s" repeatCount="indefinite"/>
  </path>

  <!-- Second wave line -->
  <path d="M0,130 C200,95 400,155 600,120 C800,85 1000,140 1200,115 C1320,100 1400,125 1440,115"
        fill="none" stroke="url(#waveGrad2)" stroke-width="1" opacity="0.6">
    <animateTransform attributeName="transform" type="translate" values="0,0; 15,-4; 0,0" dur="8s" repeatCount="indefinite"/>
  </path>

  <!-- Digital signature (neon style) -->
  <!-- Glow effect for signature -->
  <text x="720" y="75" font-family="'Courier New',monospace" font-size="28" fill="#00ff41"
        text-anchor="middle" opacity="0.05" font-weight="bold">Sahal111</text>
  <text x="720" y="75" font-family="'Courier New',monospace" font-size="24" fill="#00ff41"
        text-anchor="middle" font-weight="bold" filter="url(#waveGlow)" opacity="0.9">
    ⌨️ Sahal · X_proff ⌨️
  </text>

  <!-- Neon signature underline -->
  <line x1="550" y1="85" x2="890" y2="85" stroke="url(#waveGrad1)" stroke-width="1" opacity="0.6" filter="url(#waveGlow)"/>

  <!-- Tagline -->
  <text x="720" y="110" font-family="'Courier New',monospace" font-size="12" fill="#475569"
        text-anchor="middle" letter-spacing="3">
    // Made with ❤️ + ☕ + console.log() from Indonesia 🇮🇩
  </text>

  <!-- Social quick links -->
  <text x="400" y="148" font-family="'Courier New',monospace" font-size="10" fill="#334155" text-anchor="middle">github.com/Sahal111</text>
  <line x1="450" y1="143" x2="450" y2="153" stroke="#21262d" stroke-width="1"/>
  <text x="540" y="148" font-family="'Courier New',monospace" font-size="10" fill="#334155" text-anchor="middle">@X_proff</text>
  <line x1="590" y1="143" x2="590" y2="153" stroke="#21262d" stroke-width="1"/>
  <text x="680" y="148" font-family="'Courier New',monospace" font-size="10" fill="#334155" text-anchor="middle">Indonesia 🇮🇩</text>
  <line x1="740" y1="143" x2="740" y2="153" stroke="#21262d" stroke-width="1"/>
  <text x="820" y="148" font-family="'Courier New',monospace" font-size="10" fill="#334155" text-anchor="middle">Open for collab ✅</text>
  <line x1="900" y1="143" x2="900" y2="153" stroke="#21262d" stroke-width="1"/>
  <text x="980" y="148" font-family="'Courier New',monospace" font-size="10" fill="#334155" text-anchor="middle">Building cool stuff 🚀</text>

  <!-- Bottom line -->
  <line x1="0" y1="165" x2="1440" y2="165" stroke="#0d1117" stroke-width="1"/>
  <text x="720" y="175" font-family="'Courier New',monospace" font-size="9" fill="#1e293b" text-anchor="middle">
    © 2025 Sahal111 · github.com/Sahal111 · Built with Markdown + SVG + ❤️
  </text>
</svg>

</div>

<!--
╔══════════════════════════════════════════════════════════════════════════╗
║                    GITHUB ACTIONS WORKFLOWS SETUP                        ║
╠══════════════════════════════════════════════════════════════════════════╣
║                                                                          ║
║  1. SNAKE ANIMATION → .github/workflows/snake.yml                       ║
║  ─────────────────────────────────────────────────────────────────────   ║
║  name: Generate Snake                                                    ║
║  on:                                                                     ║
║    schedule: [{cron: "0 */12 * * *"}]                                   ║
║    workflow_dispatch:                                                     ║
║  jobs:                                                                   ║
║    generate:                                                             ║
║      runs-on: ubuntu-latest                                              ║
║      steps:                                                              ║
║        - uses: Platane/snk@v3                                            ║
║          with:                                                           ║
║            github_user_name: Sahal111                                   ║
║            outputs: |                                                    ║
║              dist/snake.svg                                              ║
║              dist/snake-dark.svg?palette=github-dark                    ║
║          env:                                                            ║
║            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}                    ║
║        - uses: crazy-max/ghaction-github-pages@v3                       ║
║          with:                                                           ║
║            target_branch: output                                         ║
║            build_dir: dist                                               ║
║          env:                                                            ║
║            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}                    ║
║                                                                          ║
║  2. WAKATIME STATS → .github/workflows/waka.yml                         ║
║  ─────────────────────────────────────────────────────────────────────   ║
║  name: Waka Readme                                                       ║
║  on:                                                                     ║
║    schedule: [{cron: "0 0 * * *"}]                                      ║
║    workflow_dispatch:                                                     ║
║  jobs:                                                                   ║
║    update-readme:                                                        ║
║      runs-on: ubuntu-latest                                              ║
║      steps:                                                              ║
║        - uses: athul/waka-readme@master                                  ║
║          with:                                                           ║
║            WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}            ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
-->

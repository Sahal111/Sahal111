<!-- ╔══════════════════════════════════════════════════════════════════════════════╗
     ║                  SAHAL111 · GITHUB PROFILE README                            ║
     ║       Built with: SVG · CSS Animation · Cyberpunk/Matrix Theme               ║
     ║              Author: Sahal · Indonesia 🇮🇩 · github.com/Sahal111              ║
     ╚══════════════════════════════════════════════════════════════════════════════╝ -->

<!-- ═══════════════════════════════════════════════════════ -->
<!-- ANIMATED WAVE HEADER                                    -->
<!-- ═══════════════════════════════════════════════════════ -->
<div align="center">
  <svg width="100%" height="120" viewBox="0 0 1440 120" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
    <defs>
      <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#0f172a"/>
        <stop offset="30%" stop-color="#0d1117"/>
        <stop offset="70%" stop-color="#0d2818"/>
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
    <circle cx="100" cy="20" r="1.5" fill="#00ff41" opacity="0.8" filter="url(#glow)">
      <animate attributeName="opacity" values="0.8;0.1;0.8" dur="2.1s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="20;100;20" dur="4.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="280" cy="50" r="1.5" fill="#00ff41" opacity="0.6" filter="url(#glow)">
      <animate attributeName="opacity" values="0.6;0.05;0.6" dur="1.7s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="50;110;50" dur="3.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="460" cy="10" r="1" fill="#00ff41" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.1;0.7" dur="2.8s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="10;90;10" dur="5.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="640" cy="70" r="1.5" fill="#38bdf8" opacity="0.5" filter="url(#glow)">
      <animate attributeName="opacity" values="0.5;0.05;0.5" dur="2.3s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="70;110;70" dur="4.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="820" cy="35" r="1" fill="#38bdf8" opacity="0.6">
      <animate attributeName="opacity" values="0.6;0.1;0.6" dur="1.9s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="35;100;35" dur="3.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1000" cy="55" r="1.5" fill="#6366f1" opacity="0.5" filter="url(#glow)">
      <animate attributeName="opacity" values="0.5;0.1;0.5" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="55;115;55" dur="5.0s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1180" cy="25" r="1" fill="#00ff41" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.05;0.7" dur="2.0s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="25;95;25" dur="4.0s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1360" cy="65" r="1.5" fill="#38bdf8" opacity="0.4" filter="url(#glow)">
      <animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.1s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="65;110;65" dur="6.2s" repeatCount="indefinite"/>
    </circle>
    <!-- Glowing wave -->
    <path d="M0,80 C180,40 360,100 540,60 C720,20 900,80 1080,50 C1260,20 1380,70 1440,55 L1440,120 L0,120 Z" fill="url(#headerGrad)" opacity="0.5"/>
    <!-- Terminal cursor blink in header -->
    <rect x="670" y="52" width="8" height="16" fill="#00ff41" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0;0.9" dur="1s" repeatCount="indefinite"/>
    </rect>
  </svg>
</div>

<!-- ═══════════════════════════════════════════════════════ -->
<!-- CUSTOM SVG HERO BANNER                                  -->
<!-- ═══════════════════════════════════════════════════════ -->
<div align="center">
  <svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <defs>
      <linearGradient id="bgMain" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#0d1117"/>
        <stop offset="50%" stop-color="#0f172a"/>
        <stop offset="100%" stop-color="#0d1117"/>
      </linearGradient>
      <linearGradient id="cyanGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#38bdf8"/>
        <stop offset="50%" stop-color="#00ff41"/>
        <stop offset="100%" stop-color="#38bdf8"/>
      </linearGradient>
      <filter id="neonGlow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <filter id="softGlow" x="-10%" y="-10%" width="120%" height="120%">
        <feGaussianBlur stdDeviation="2" result="blur"/>
        <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <pattern id="scanlines" x="0" y="0" width="1" height="4" patternUnits="userSpaceOnUse">
        <rect x="0" y="0" width="860" height="1" fill="rgba(0,255,65,0.03)"/>
      </pattern>
      <pattern id="circuit" x="0" y="0" width="60" height="60" patternUnits="userSpaceOnUse">
        <path d="M10,30 L30,30 L30,10 M30,30 L50,30 M20,10 L20,20 M40,50 L40,40" stroke="#38bdf8" stroke-width="0.4" fill="none" opacity="0.15"/>
        <circle cx="30" cy="30" r="2" fill="#38bdf8" opacity="0.1"/>
        <circle cx="10" cy="30" r="1.5" fill="#00ff41" opacity="0.08"/>
      </pattern>
      <clipPath id="bannerClip">
        <rect x="0" y="0" width="860" height="280" rx="16" ry="16"/>
      </clipPath>
    </defs>
    <g clip-path="url(#bannerClip)">
      <rect width="860" height="280" fill="url(#bgMain)"/>
      <rect width="860" height="280" fill="url(#circuit)"/>
      <rect width="860" height="280" fill="url(#scanlines)"/>
      <circle cx="780" cy="50" r="80" fill="#38bdf8" opacity="0.04" filter="url(#neonGlow)"/>
      <circle cx="80" cy="230" r="70" fill="#00ff41" opacity="0.03" filter="url(#neonGlow)"/>
      <rect x="1" y="1" width="858" height="278" rx="15" ry="15" fill="none" stroke="url(#cyanGrad)" stroke-width="0.8" opacity="0.6" filter="url(#softGlow)"/>
      <path d="M0,40 L0,0 L40,0" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
      <path d="M820,0 L860,0 L860,40" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
      <path d="M0,240 L0,280 L40,280" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
      <path d="M820,280 L860,280 L860,240" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.8"/>
      <circle cx="0" cy="0" r="4" fill="#00ff41" opacity="0.9" filter="url(#softGlow)"><animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" repeatCount="indefinite"/></circle>
      <circle cx="860" cy="0" r="4" fill="#38bdf8" opacity="0.9" filter="url(#softGlow)"><animate attributeName="opacity" values="0.9;0.3;0.9" dur="2.5s" repeatCount="indefinite"/></circle>
      <rect x="0" y="0" width="860" height="28" fill="rgba(0,0,0,0.4)"/>
      <circle cx="22" cy="14" r="5" fill="#ff5f57"/>
      <circle cx="40" cy="14" r="5" fill="#febc2e"/>
      <circle cx="58" cy="14" r="5" fill="#28c840"/>
      <text x="430" y="18" fill="#38bdf8" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" opacity="0.7">~/portfolio/sahal — bash — 120×30</text>
      <circle cx="820" cy="14" r="3.5" fill="#00ff41" opacity="0.9"><animate attributeName="opacity" values="0.9;0.3;0.9" dur="1.5s" repeatCount="indefinite"/></circle>
      <text x="808" y="18" fill="#00ff41" font-size="8" font-family="'Courier New',monospace" text-anchor="end" opacity="0.7">LIVE</text>
      <text x="430" y="100" fill="url(#cyanGrad)" font-size="64" font-family="'Courier New',monospace" font-weight="900" text-anchor="middle" letter-spacing="12" filter="url(#neonGlow)" opacity="0.95">SAHAL</text>
      <text x="430" y="130" fill="#94a3b8" font-size="12" font-family="'Courier New',monospace" text-anchor="middle" letter-spacing="6">FULL-STACK DEVELOPER · INDONESIA</text>
      <line x1="230" y1="140" x2="630" y2="140" stroke="url(#cyanGrad)" stroke-width="1" opacity="0.5"><animate attributeName="x1" values="230;330;230" dur="3s" repeatCount="indefinite"/><animate attributeName="x2" values="630;530;630" dur="3s" repeatCount="indefinite"/><animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/></line>
      <rect x="200" y="155" width="120" height="22" rx="11" fill="rgba(56,189,248,0.1)" stroke="#38bdf8" stroke-width="0.8"/>
      <text x="260" y="170" fill="#38bdf8" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" letter-spacing="1">React · Laravel</text>
      <rect x="340" y="155" width="100" height="22" rx="11" fill="rgba(99,102,241,0.1)" stroke="#6366f1" stroke-width="0.8"/>
      <text x="390" y="170" fill="#6366f1" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" letter-spacing="1">Python · ML</text>
      <rect x="460" y="155" width="120" height="22" rx="11" fill="rgba(0,255,65,0.08)" stroke="#00ff41" stroke-width="0.8"/>
      <text x="520" y="170" fill="#00ff41" font-size="9" font-family="'Courier New',monospace" text-anchor="middle" letter-spacing="1">Open Source 🔥</text>
      <text x="430" y="215" fill="#475569" font-size="9" font-family="'Courier New',monospace" text-anchor="middle">── SYSTEM STATUS ─────────────────────────────────────────────</text>
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
      <line x1="40" y1="270" x2="820" y2="270" stroke="#1e293b" stroke-width="0.8" opacity="0.8"/>
      <text x="430" y="278" fill="#334155" font-size="8" font-family="'Courier New',monospace" text-anchor="middle">github.com/Sahal111 · X_proff · Building cool stuff since 2023</text>
    </g>
  </svg>
</div>
<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!-- TERMINAL SIMULATION (whoami, etc.)                      -->
<!-- ═══════════════════════════════════════════════════════ -->
<div align="center">
  <svg width="780" height="480" viewBox="0 0 780 480" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="termBg" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#0d1117"/><stop offset="100%" stop-color="#060d0d"/>
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
      <rect width="780" height="480" fill="url(#termBg)"/>
      <rect x="0" y="0" width="780" height="36" fill="#161b22"/>
      <rect x="0" y="36" width="780" height="1" fill="#21262d"/>
      <circle cx="22" cy="18" r="6" fill="#ff5f57"/><circle cx="42" cy="18" r="6" fill="#febc2e"/><circle cx="62" cy="18" r="6" fill="#28c840"/>
      <text x="390" y="23" fill="#8b949e" font-size="12" font-family="'SF Mono','Courier New',monospace" text-anchor="middle">bash — sahal111@matrix: ~/portfolio</text>
      
      <!-- LINE 1: whoami -->
      <text x="24" y="72" font-family="'Courier New',monospace" font-size="13" fill="#00ff41" filter="url(#termGlow)">
        <tspan fill="#6366f1">┌──(</tspan><tspan fill="#38bdf8">sahal111</tspan><tspan fill="#6366f1">㉿</tspan><tspan fill="#00ff41">matrix</tspan><tspan fill="#6366f1">)-[</tspan><tspan fill="#f59e0b">~/portfolio</tspan><tspan fill="#6366f1">]</tspan>
      </text>
      <text x="24" y="90" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">└─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> whoami</tspan></text>
      <text x="24" y="110" font-family="'Courier New',monospace" font-size="13" fill="#94a3b8">► <tspan fill="#38bdf8">Sahal</tspan> — Full-Stack Developer &amp; ML Enthusiast from Indonesia 🇮🇩</text>
      <text x="24" y="128" font-family="'Courier New',monospace" font-size="12" fill="#64748b"><tspan fill="#00ff41">  ✓</tspan> Laravel · React · Python · MySQL · TailwindCSS</text>
      <text x="24" y="146" font-family="'Courier New',monospace" font-size="12" fill="#64748b"><tspan fill="#00ff41">  ✓</tspan> 270+ commits · 14 repos · Open for collaboration</text>
      <line x1="24" y1="158" x2="756" y2="158" stroke="#21262d" stroke-width="0.8"/>

      <!-- LINE 2: skills.json -->
      <text x="24" y="178" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">└─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> cat skills.json</tspan></text>
      <text x="24" y="196" font-family="'Courier New',monospace" font-size="11" fill="#64748b">{</text>
      <text x="40" y="212" font-family="'Courier New',monospace" font-size="11"><tspan fill="#6366f1">"frontend"</tspan><tspan fill="#94a3b8">: [</tspan><tspan fill="#f59e0b">"React"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"Next.js"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"TailwindCSS"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"TypeScript"</tspan><tspan fill="#94a3b8">],</tspan></text>
      <text x="40" y="228" font-family="'Courier New',monospace" font-size="11"><tspan fill="#6366f1">"backend"</tspan><tspan fill="#94a3b8">: [</tspan><tspan fill="#f59e0b">"Laravel"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"PHP"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"Node.js"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"Python"</tspan><tspan fill="#94a3b8">],</tspan></text>
      <text x="40" y="244" font-family="'Courier New',monospace" font-size="11"><tspan fill="#6366f1">"database"</tspan><tspan fill="#94a3b8">: [</tspan><tspan fill="#f59e0b">"MySQL"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"PostgreSQL"</tspan><tspan fill="#94a3b8">],</tspan></text>
      <text x="40" y="260" font-family="'Courier New',monospace" font-size="11"><tspan fill="#6366f1">"ai_ml"</tspan><tspan fill="#94a3b8">: [</tspan><tspan fill="#f59e0b">"scikit-learn"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"Pandas"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"Jupyter"</tspan><tspan fill="#94a3b8">],</tspan></text>
      <text x="40" y="276" font-family="'Courier New',monospace" font-size="11"><tspan fill="#6366f1">"tools"</tspan><tspan fill="#94a3b8">: [</tspan><tspan fill="#f59e0b">"Git"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"VS Code"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"Figma"</tspan><tspan fill="#94a3b8">, </tspan><tspan fill="#f59e0b">"Postman"</tspan><tspan fill="#94a3b8">]</tspan></text>
      <text x="24" y="292" font-family="'Courier New',monospace" font-size="11" fill="#64748b">}</text>
      <line x1="24" y1="302" x2="756" y2="302" stroke="#21262d" stroke-width="0.8"/>

      <!-- LINE 3: projects -->
      <text x="24" y="320" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">└─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> ls projects/ --color</tspan></text>
      <text x="24" y="338" font-family="'Courier New',monospace" font-size="12"><tspan fill="#38bdf8">sneakershead/</tspan><tspan fill="#475569">     </tspan><tspan fill="#38bdf8">UTS_ML_Sahal/</tspan><tspan fill="#475569">     </tspan><tspan fill="#38bdf8">RPL_Group1/</tspan></text>
      <text x="24" y="356" font-family="'Courier New',monospace" font-size="12"><tspan fill="#f59e0b">Challenge_Frontend/</tspan><tspan fill="#475569">  </tspan><tspan fill="#6366f1">[WIP]</tspan><tspan fill="#38bdf8"> school-erp/</tspan><tspan fill="#475569">   </tspan><tspan fill="#6366f1">[WIP]</tspan><tspan fill="#38bdf8"> ai-project/</tspan></text>
      <line x1="24" y1="368" x2="756" y2="368" stroke="#21262d" stroke-width="0.8"/>

      <!-- LINE 4: status -->
      <text x="24" y="386" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">└─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> status --verbose</tspan></text>
      <text x="24" y="404" font-family="'Courier New',monospace" font-size="12" fill="#94a3b8"><tspan fill="#00ff41">  [ON]</tspan>  Currently building: <tspan fill="#38bdf8">School ERP System</tspan></text>
      <text x="24" y="420" font-family="'Courier New',monospace" font-size="12" fill="#94a3b8"><tspan fill="#00ff41">  [ON]</tspan>  Learning: <tspan fill="#6366f1">AI/ML · Clean Architecture</tspan></text>
      <text x="24" y="436" font-family="'Courier New',monospace" font-size="12" fill="#94a3b8"><tspan fill="#00ff41">  [ON]</tspan>  Open to: <tspan fill="#f59e0b">Collaboration · Freelance</tspan></text>
      <text x="24" y="460" font-family="'Courier New',monospace" font-size="13" fill="#6366f1">└─<tspan fill="#00ff41">$</tspan><tspan fill="#e2e8f0"> _</tspan></text>
      <rect x="60" y="448" width="8" height="14" fill="#00ff41" filter="url(#termGlow)"><animate attributeName="opacity" values="1;0;1" dur="1.1s" repeatCount="indefinite"/></rect>
    </g>
  </svg>
</div>
<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!-- COMMAND PALETTE (Raycast style)                         -->
<!-- ═══════════════════════════════════════════════════════ -->
<div align="center">
  <svg width="580" height="260" viewBox="0 0 580 260" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="palBg" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#161b22"/><stop offset="100%" stop-color="#0d1117"/>
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
      <rect x="1" y="1" width="578" height="258" rx="13" ry="13" fill="none" stroke="#38bdf8" stroke-width="0.8" opacity="0.5" filter="url(#palGlow)"/>
      <rect x="16" y="16" width="548" height="42" rx="8" fill="#21262d"/>
      <rect x="16" y="16" width="548" height="42" rx="8" fill="none" stroke="#38bdf8" stroke-width="1" opacity="0.4"/>
      <text x="36" y="43" font-family="'Courier New',monospace" font-size="16" fill="#6366f1" font-weight="bold">⌘</text>
      <text x="58" y="43" font-family="'Courier New',monospace" font-size="14" fill="#94a3b8">&gt; Type a command...</text>
      <rect x="228" y="26" width="2" height="20" fill="#38bdf8"><animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/></rect>
      <rect x="508" y="26" width="40" height="22" rx="4" fill="#161b22" stroke="#334155" stroke-width="1"/>
      <text x="528" y="41" font-family="'Courier New',monospace" font-size="10" fill="#475569" text-anchor="middle">ESC</text>
      <line x1="16" y1="68" x2="564" y2="68" stroke="#21262d" stroke-width="1"/>
      <text x="28" y="86" font-family="'SF Pro','Helvetica',monospace" font-size="10" fill="#475569" letter-spacing="2">QUICK COMMANDS</text>
      
      <!-- Option 1 -->
      <rect x="16" y="92" width="548" height="38" rx="6" fill="#38bdf8" opacity="0.05"/>
      <rect x="16" y="92" width="3" height="38" rx="1" fill="#38bdf8"/>
      <text x="34" y="107" font-family="'Courier New',monospace" font-size="12" fill="#00ff41">▶</text>
      <text x="50" y="107" font-family="'Courier New',monospace" font-size="13" fill="#e2e8f0">about</text>
      <text x="50" y="122" font-family="'Courier New',monospace" font-size="10" fill="#475569">Open Sahal's profile and background</text>
      <rect x="520" y="100" width="36" height="20" rx="4" fill="#161b22" stroke="#334155" stroke-width="1"/>
      <text x="538" y="114" font-family="'Courier New',monospace" font-size="9" fill="#38bdf8" text-anchor="middle">↵</text>

      <!-- Option 2 -->
      <rect x="16" y="136" width="548" height="38" rx="6" fill="transparent"/>
      <text x="34" y="151" font-family="'Courier New',monospace" font-size="12" fill="#6366f1">▶</text>
      <text x="50" y="151" font-family="'Courier New',monospace" font-size="13" fill="#94a3b8">projects</text>
      <text x="50" y="166" font-family="'Courier New',monospace" font-size="10" fill="#475569">Browse all featured repositories</text>
      <rect x="518" y="143" width="42" height="20" rx="4" fill="#161b22" stroke="#21262d" stroke-width="1"/>
      <text x="539" y="157" font-family="'Courier New',monospace" font-size="9" fill="#475569" text-anchor="middle">⌘ P</text>

      <!-- Option 3 -->
      <rect x="16" y="180" width="548" height="38" rx="6" fill="transparent"/>
      <text x="34" y="195" font-family="'Courier New',monospace" font-size="12" fill="#f59e0b">▶</text>
      <text x="50" y="195" font-family="'Courier New',monospace" font-size="13" fill="#94a3b8">contact</text>
      <text x="50" y="210" font-family="'Courier New',monospace" font-size="10" fill="#475569">Reach out for collaboration</text>
      <rect x="518" y="187" width="42" height="20" rx="4" fill="#161b22" stroke="#21262d" stroke-width="1"/>
      <text x="539" y="201" font-family="'Courier New',monospace" font-size="9" fill="#475569" text-anchor="middle">⌘ K</text>

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
<!-- SVG DIVIDER                                             -->
<!-- ═══════════════════════════════════════════════════════ -->
<div align="center">
  <svg width="100%" height="3" viewBox="0 0 800 3" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
    <defs>
      <linearGradient id="divGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#0d1117" stop-opacity="0"/>
        <stop offset="20%" stop-color="#38bdf8"/>
        <stop offset="50%" stop-color="#00ff41"/>
        <stop offset="80%" stop-color="#6366f1"/>
        <stop offset="100%" stop-color="#0d1117" stop-opacity="0"/>
      </linearGradient>
    </defs>
    <rect width="800" height="1" y="1" fill="url(#divGrad)"/>
  </svg>
</div>
<br/>

<!-- ═══════════════════════════════════════════════════════ -->
<!-- ABOUT ME                                                -->
<!-- ═══════════════════════════════════════════════════════ -->
<h2 align="center">
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/People/Technologist.png" width="28"/>
  About Me
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

focus_2026:
  - School ERP System (Laravel + React)
  - Machine Learning with Python
  - Clean Architecture & TDD
  - Open Source Contributions
─────────────────────────────────────
availability: "Open for collaboration ✅"
coffee:       "☕ Required before 10am"

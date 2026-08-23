<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 920 560" width="920" height="560" font-family="Segoe UI, Verdana, sans-serif">

  <defs>
    <linearGradient id="water" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"  stop-color="#cfe6f5"/>
      <stop offset="16%" stop-color="#a9cfe8"/>
      <stop offset="55%" stop-color="#4f6fa0"/>
      <stop offset="100%" stop-color="#31456b"/>
    </linearGradient>
    <linearGradient id="sand" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#e9d3ab"/>
      <stop offset="100%" stop-color="#d3b787"/>
    </linearGradient>
    <clipPath id="tankClip">
      <rect x="8" y="70" width="904" height="410" rx="16"/>
    </clipPath>
  </defs>

  <!-- plaque -->
  <text x="460" y="34" text-anchor="middle" font-size="13" letter-spacing="4" fill="#7a8aa8">WELCOME TO MY TINY CORNER OF GITHUB</text>
  <text x="460" y="62" text-anchor="middle" font-size="34" font-style="italic" font-weight="700" fill="#3d4f78">gaurang&#8217;s tank &#8942; &#9825;</text>

  <!-- tank frame -->
  <rect x="4" y="66" width="912" height="418" rx="20" fill="#ffffff"/>
  <g clip-path="url(#tankClip)">
    <rect x="8" y="70" width="904" height="410" fill="url(#water)"/>

    <!-- light rays -->
    <g opacity="0.28">
      <rect x="100" y="70" width="46" height="410" fill="#ffffff" transform="skewX(-12)">
        <animate attributeName="opacity" values="0.15;0.4;0.15" dur="7s" repeatCount="indefinite"/>
      </rect>
      <rect x="420" y="70" width="46" height="410" fill="#ffffff" transform="skewX(-12)">
        <animate attributeName="opacity" values="0.4;0.15;0.4" dur="6s" repeatCount="indefinite"/>
      </rect>
      <rect x="700" y="70" width="46" height="410" fill="#ffffff" transform="skewX(-12)">
        <animate attributeName="opacity" values="0.2;0.4;0.2" dur="8s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- jellyfish -->
    <g transform="translate(150,140)">
      <ellipse cx="0" cy="0" rx="17" ry="13" fill="#f2e3f5" opacity="0.85"/>
      <path d="M -11,10 Q -8,22 -11,30 M -3,12 Q 0,24 -3,32 M 5,12 Q 8,24 5,32 M 11,10 Q 14,22 11,30"
            stroke="#e0c6ea" stroke-width="2" fill="none" opacity="0.6"/>
      <animateTransform attributeName="transform" type="translate" additive="sum"
        values="0,0; 10,-18; 0,0" dur="6s" repeatCount="indefinite"/>
    </g>
    <g transform="translate(600,170) scale(0.8)">
      <ellipse cx="0" cy="0" rx="17" ry="13" fill="#f2e3f5" opacity="0.8"/>
      <path d="M -11,10 Q -8,22 -11,30 M -3,12 Q 0,24 -3,32 M 5,12 Q 8,24 5,32 M 11,10 Q 14,22 11,30"
            stroke="#e0c6ea" stroke-width="2" fill="none" opacity="0.6"/>
      <animateTransform attributeName="transform" type="translate" additive="sum"
        values="0,0; -8,-16; 0,0" dur="5.2s" begin="1.4s" repeatCount="indefinite"/>
    </g>

    <!-- thought bubble -->
    <g transform="translate(28,300)">
      <rect x="0" y="0" width="168" height="58" rx="14" fill="#ffffff" opacity="0.9"/>
      <circle cx="20" cy="64" r="6" fill="#ffffff" opacity="0.9"/>
      <text x="14" y="20" font-size="15" font-style="italic" font-weight="700" fill="#3d4f78">currently &#9729;</text>
      <text x="14" y="36" font-size="10.5" fill="#48587e">learning something new,</text>
      <text x="14" y="48" font-size="10.5" fill="#48587e">one commit at a time.</text>
      <animateTransform attributeName="transform" type="translate" additive="sum"
        values="28,300; 28,290; 28,300" dur="5s" repeatCount="indefinite"/>
    </g>

    <!-- ===== FISH ===== -->
    <!-- fish 1: ReUseIt, left -> right, facing right -->
    <g transform="translate(-140,150)">
      <g>
        <ellipse cx="0" cy="0" rx="26" ry="15" fill="#e07f98"/>
        <path d="M -24,0 L -40,-11 L -40,11 Z" fill="#e07f98">
          <animateTransform attributeName="transform" type="rotate" values="0 -24 0; 12 -24 0; 0 -24 0" dur="0.6s" repeatCount="indefinite"/>
        </path>
        <path d="M -6,-9 Q 4,-18 14,-9 Z" fill="#ffffff" opacity="0.55"/>
        <circle cx="12" cy="-3" r="2.4" fill="#2f3a4f"/>
        <rect x="-30" y="18" width="86" height="16" rx="8" fill="rgba(40,55,90,0.6)"/>
        <text x="13" y="30" text-anchor="middle" font-size="10.5" font-weight="700" fill="#ffffff">&#9851; ReUseIt</text>
      </g>
      <animateTransform attributeName="transform" type="translate" values="-140,150; 1020,150" dur="17s" repeatCount="indefinite"/>
    </g>

    <!-- fish 2: Smart Waste Segregation, right -> left, mirrored -->
    <g transform="translate(1020,225) scale(-1,1)">
      <g>
        <ellipse cx="0" cy="0" rx="26" ry="15" fill="#7fae8c"/>
        <path d="M -24,0 L -40,-11 L -40,11 Z" fill="#7fae8c">
          <animateTransform attributeName="transform" type="rotate" values="0 -24 0; 12 -24 0; 0 -24 0" dur="0.6s" repeatCount="indefinite"/>
        </path>
        <path d="M -6,-9 Q 4,-18 14,-9 Z" fill="#ffffff" opacity="0.55"/>
        <circle cx="12" cy="-3" r="2.4" fill="#2f3a4f"/>
        <g transform="scale(-1,1)">
          <rect x="-70" y="18" width="140" height="16" rx="8" fill="rgba(40,55,90,0.6)"/>
          <text x="0" y="30" text-anchor="middle" font-size="10.5" font-weight="700" fill="#ffffff">&#128465; Smart Waste Segregation</text>
        </g>
      </g>
      <animateTransform attributeName="transform" type="translate" values="1020,225; -140,225" dur="21s" repeatCount="indefinite" additive="sum"/>
    </g>

    <!-- fish 3: App Experiments, left -> right -->
    <g transform="translate(-140,300)">
      <g>
        <ellipse cx="0" cy="0" rx="24" ry="14" fill="#f2b866"/>
        <path d="M -22,0 L -37,-10 L -37,10 Z" fill="#f2b866">
          <animateTransform attributeName="transform" type="rotate" values="0 -22 0; 12 -22 0; 0 -22 0" dur="0.55s" repeatCount="indefinite"/>
        </path>
        <path d="M -5,-8 Q 4,-16 12,-8 Z" fill="#ffffff" opacity="0.55"/>
        <circle cx="11" cy="-3" r="2.2" fill="#2f3a4f"/>
        <rect x="-26" y="16" width="100" height="16" rx="8" fill="rgba(40,55,90,0.6)"/>
        <text x="24" y="28" text-anchor="middle" font-size="10.5" font-weight="700" fill="#ffffff">&#128241; App Experiments</text>
      </g>
      <animateTransform attributeName="transform" type="translate" values="-140,300; 1020,300" dur="14.5s" begin="2s" repeatCount="indefinite"/>
    </g>

    <!-- fish 4: little idea, right -> left, small -->
    <g transform="translate(1020,370) scale(-0.7,0.7)">
      <g>
        <ellipse cx="0" cy="0" rx="24" ry="14" fill="#a58ce0"/>
        <path d="M -22,0 L -37,-10 L -37,10 Z" fill="#a58ce0">
          <animateTransform attributeName="transform" type="rotate" values="0 -22 0; 14 -22 0; 0 -22 0" dur="0.5s" repeatCount="indefinite"/>
        </path>
        <circle cx="11" cy="-3" r="2.4" fill="#2f3a4f"/>
        <g transform="scale(-1,1)">
          <rect x="-58" y="16" width="80" height="18" rx="9" fill="rgba(40,55,90,0.6)"/>
          <text x="-18" y="29" text-anchor="middle" font-size="11" font-weight="700" fill="#ffffff">&#128031; idea</text>
        </g>
      </g>
      <animateTransform attributeName="transform" type="translate" values="1020,370; -140,370" dur="12s" begin="4s" repeatCount="indefinite" additive="sum"/>
    </g>

    <!-- ===== BUBBLES ===== -->
    <g fill="#ffffff">
      <circle cx="60"  cy="480" r="3" opacity="0"><animate attributeName="cy" values="480;70" dur="6s" begin="0.2s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="6s" begin="0.2s" repeatCount="indefinite"/></circle>
      <circle cx="120" cy="480" r="4.5" opacity="0"><animate attributeName="cy" values="480;70" dur="7.5s" begin="1.6s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="7.5s" begin="1.6s" repeatCount="indefinite"/></circle>
      <circle cx="260" cy="480" r="2.5" opacity="0"><animate attributeName="cy" values="480;70" dur="5.2s" begin="0.9s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="5.2s" begin="0.9s" repeatCount="indefinite"/></circle>
      <circle cx="410" cy="480" r="4" opacity="0"><animate attributeName="cy" values="480;70" dur="6.8s" begin="2.3s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="6.8s" begin="2.3s" repeatCount="indefinite"/></circle>
      <circle cx="540" cy="480" r="3" opacity="0"><animate attributeName="cy" values="480;70" dur="5.8s" begin="0.4s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="5.8s" begin="0.4s" repeatCount="indefinite"/></circle>
      <circle cx="650" cy="480" r="5" opacity="0"><animate attributeName="cy" values="480;70" dur="8s" begin="3.1s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="8s" begin="3.1s" repeatCount="indefinite"/></circle>
      <circle cx="770" cy="480" r="3.5" opacity="0"><animate attributeName="cy" values="480;70" dur="6.3s" begin="1.1s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="6.3s" begin="1.1s" repeatCount="indefinite"/></circle>
      <circle cx="850" cy="480" r="2.5" opacity="0"><animate attributeName="cy" values="480;70" dur="4.6s" begin="2.8s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="4.6s" begin="2.8s" repeatCount="indefinite"/></circle>
      <circle cx="330" cy="480" r="3" opacity="0"><animate attributeName="cy" values="480;70" dur="5.5s" begin="0.1s" repeatCount="indefinite"/><animate attributeName="opacity" values="0;0.9;0" dur="5.5s" begin="0.1s" repeatCount="indefinite"/></circle>
    </g>

    <!-- sand -->
    <rect x="8" y="440" width="904" height="40" fill="url(#sand)"/>

    <!-- pebbles -->
    <ellipse cx="90"  cy="452" rx="14" ry="7" fill="#c9b48b"/>
    <ellipse cx="640" cy="450" rx="18" ry="9" fill="#c9b48b"/>
    <ellipse cx="380" cy="454" rx="10" ry="5" fill="#c9b48b"/>

    <!-- seaweed -->
    <g stroke="none">
      <path d="M 55,443 Q 40,400 55,350" stroke="#5f8f70" stroke-width="10" fill="none" stroke-linecap="round">
        <animateTransform attributeName="transform" type="rotate" values="-7 55 443; 8 55 443; -7 55 443" dur="4.2s" repeatCount="indefinite"/>
      </path>
      <path d="M 80,443 Q 68,410 80,375" stroke="#7fae8c" stroke-width="8" fill="none" stroke-linecap="round">
        <animateTransform attributeName="transform" type="rotate" values="6 80 443; -8 80 443; 6 80 443" dur="3.7s" repeatCount="indefinite"/>
      </path>
      <path d="M 300,443 Q 288,412 300,385" stroke="#7fae8c" stroke-width="8" fill="none" stroke-linecap="round">
        <animateTransform attributeName="transform" type="rotate" values="-6 300 443; 8 300 443; -6 300 443" dur="4.6s" begin="0.5s" repeatCount="indefinite"/>
      </path>
      <path d="M 480,443 Q 462,392 480,335" stroke="#5f8f70" stroke-width="10" fill="none" stroke-linecap="round">
        <animateTransform attributeName="transform" type="rotate" values="7 480 443; -8 480 443; 7 480 443" dur="4s" repeatCount="indefinite"/>
      </path>
      <path d="M 505,443 Q 493,405 505,370" stroke="#7fae8c" stroke-width="8" fill="none" stroke-linecap="round">
        <animateTransform attributeName="transform" type="rotate" values="-8 505 443; 6 505 443; -8 505 443" dur="3.9s" begin="0.9s" repeatCount="indefinite"/>
      </path>
    </g>

    <!-- treasure chest -->
    <g transform="translate(800,410)">
      <rect x="-32" y="16" width="64" height="24" rx="6" fill="#8a5a2b" stroke="#5f3c1a" stroke-width="2"/>
      <g>
        <path d="M -32,16 Q -32,-6 0,-6 Q 32,-6 32,16 Z" fill="#a86a34" stroke="#5f3c1a" stroke-width="2"/>
        <animateTransform attributeName="transform" type="rotate" values="0 0 16; 0 0 16; -32 0 16; -32 0 16; 0 0 16" keyTimes="0;0.55;0.68;0.85;1" dur="3.6s" repeatCount="indefinite"/>
      </g>
      <text x="0" y="58" text-anchor="middle" font-size="11" fill="#eef6fb">next project &#9203;</text>
    </g>
  </g>

  <!-- toolbox row -->
  <g font-size="12.5" font-weight="700" fill="#4a5b80">
    <g transform="translate(105,520)">
      <rect x="-46" y="-18" width="92" height="30" rx="15" fill="#fdf8ef"/>
      <text text-anchor="middle" y="2">&#128013; Python</text>
    </g>
    <g transform="translate(225,520)">
      <rect x="-40" y="-18" width="80" height="30" rx="15" fill="#fdf8ef"/>
      <text text-anchor="middle" y="2">&#9749; Java</text>
    </g>
    <g transform="translate(335,520)">
      <rect x="-40" y="-18" width="80" height="30" rx="15" fill="#fdf8ef"/>
      <text text-anchor="middle" y="2">&#127760; Web</text>
    </g>
    <g transform="translate(455,520)">
      <rect x="-52" y="-18" width="104" height="30" rx="15" fill="#fdf8ef"/>
      <text text-anchor="middle" y="2">&#129504; AI / ML</text>
    </g>
    <g transform="translate(578,520)">
      <rect x="-42" y="-18" width="84" height="30" rx="15" fill="#fdf8ef"/>
      <text text-anchor="middle" y="2">&#128202; Data</text>
    </g>
    <g transform="translate(690,520)">
      <rect x="-40" y="-18" width="80" height="30" rx="15" fill="#fdf8ef"/>
      <text text-anchor="middle" y="2">&#128241; Apps</text>
    </g>
    <g transform="translate(800,520)">
      <rect x="-44" y="-18" width="88" height="30" rx="15" fill="#fdf8ef"/>
      <text text-anchor="middle" y="2">&#127912; Design</text>
    </g>
  </g>

  <text x="460" y="552" text-anchor="middle" font-size="11.5" font-style="italic" fill="#6b7aa0">one idea &#8226; one commit &#8226; one day at a time &#9825;</text>
</svg>

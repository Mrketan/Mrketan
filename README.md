<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <clipPath id="canvasClip-light">
      <rect x="0" y="0" width="1180" height="610" rx="24"/>
    </clipPath>
    <clipPath id="leftClip-light">
      <rect x="0" y="0" width="448" height="610" rx="24"/>
    </clipPath>

    <linearGradient id="accentGrad-light" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#2563EB"/>
      <stop offset="50%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#10B981"/>
      <animate attributeName="x1" values="0%;100%;0%" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="100%;200%;100%" dur="6s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="asciiGrad-light" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#2563EB"/>
      <stop offset="100%" stop-color="#06B6D4">
        <animate attributeName="stop-color" values="#06B6D4;#2563EB;#06B6D4" dur="5s" repeatCount="indefinite"/>
      </stop>
      <animate attributeName="x1" values="0%;30%;0%" dur="7s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="borderGrad-light" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.7"/>
      <stop offset="50%" stop-color="#06B6D4" stop-opacity="0.7"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0.7"/>
      <animateTransform attributeName="gradientTransform" type="rotate" from="0 590 305" to="360 590 305" dur="10s" repeatCount="indefinite"/>
    </linearGradient>

    <radialGradient id="blob1-light" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.22"/>
      <stop offset="100%" stop-color="#2563EB" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="blob2-light" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.22"/>
      <stop offset="100%" stop-color="#06B6D4" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="blob3-light" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#10B981" stop-opacity="0.22"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
    </radialGradient>

    <filter id="softBlur-light" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="18"/>
    </filter>
    <filter id="glow-light" x="-80%" y="-80%" width="260%" height="260%">
      <feGaussianBlur stdDeviation="3.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="noise-light">
      <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="2" stitchTiles="stitch" result="noise"/>
      <feColorMatrix in="noise" type="matrix" values="0 0 0 0 1  0 0 0 0 1  0 0 0 0 1  0 0 0 0.5 0"/>
    </filter>
  </defs>

  <g clip-path="url(#canvasClip-light)">
    <rect width="1180" height="610" fill="#FFFFFF"/>

    <circle cx="120" cy="90" r="220" fill="url(#blob1-light)" filter="url(#softBlur-light)">
      <animateTransform attributeName="transform" type="translate" values="0,0; 40,25; 0,0" dur="14s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1020" cy="120" r="240" fill="url(#blob2-light)" filter="url(#softBlur-light)">
      <animateTransform attributeName="transform" type="translate" values="0,0; -30,30; 0,0" dur="16s" repeatCount="indefinite"/>
    </circle>
    <circle cx="920" cy="550" r="220" fill="url(#blob3-light)" filter="url(#softBlur-light)">
      <animateTransform attributeName="transform" type="translate" values="0,0; 25,-25; 0,0" dur="13s" repeatCount="indefinite"/>
    </circle>

    <rect width="1180" height="610" filter="url(#noise-light)" opacity="0.02"/>

    <!-- particles -->
    <circle cx="60" cy="80" r="1" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="3s" begin="0.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-18; 0,0" dur="5s" begin="0.0s" repeatCount="indefinite"/>
    </circle><circle cx="157" cy="217" r="2" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="4s" begin="0.4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-19; 0,0" dur="6s" begin="0.3s" repeatCount="indefinite"/>
    </circle><circle cx="254" cy="354" r="3" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="5s" begin="0.8s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-20; 0,0" dur="7s" begin="0.6s" repeatCount="indefinite"/>
    </circle><circle cx="351" cy="491" r="1" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="6s" begin="1.2000000000000002s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-21; 0,0" dur="8s" begin="0.8999999999999999s" repeatCount="indefinite"/>
    </circle><circle cx="448" cy="118" r="2" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="3s" begin="1.6s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-22; 0,0" dur="9s" begin="1.2s" repeatCount="indefinite"/>
    </circle><circle cx="545" cy="255" r="3" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="4s" begin="2.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-23; 0,0" dur="5s" begin="1.5s" repeatCount="indefinite"/>
    </circle><circle cx="642" cy="392" r="1" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="5s" begin="2.4000000000000004s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-24; 0,0" dur="6s" begin="1.7999999999999998s" repeatCount="indefinite"/>
    </circle><circle cx="739" cy="529" r="2" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="6s" begin="2.8000000000000003s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-25; 0,0" dur="7s" begin="2.1s" repeatCount="indefinite"/>
    </circle><circle cx="836" cy="156" r="3" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="3s" begin="3.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-26; 0,0" dur="8s" begin="2.4s" repeatCount="indefinite"/>
    </circle><circle cx="933" cy="293" r="1" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="4s" begin="3.6s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-27; 0,0" dur="9s" begin="2.6999999999999997s" repeatCount="indefinite"/>
    </circle><circle cx="1030" cy="430" r="2" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="5s" begin="4.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-28; 0,0" dur="5s" begin="3.0s" repeatCount="indefinite"/>
    </circle><circle cx="1127" cy="567" r="3" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="6s" begin="4.4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-29; 0,0" dur="6s" begin="3.3s" repeatCount="indefinite"/>
    </circle><circle cx="84" cy="194" r="1" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="3s" begin="4.800000000000001s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-30; 0,0" dur="7s" begin="3.5999999999999996s" repeatCount="indefinite"/>
    </circle><circle cx="181" cy="331" r="2" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="4s" begin="5.2s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-31; 0,0" dur="8s" begin="3.9s" repeatCount="indefinite"/>
    </circle><circle cx="278" cy="468" r="3" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="5s" begin="5.6000000000000005s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-32; 0,0" dur="9s" begin="4.2s" repeatCount="indefinite"/>
    </circle><circle cx="375" cy="95" r="1" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="6s" begin="6.0s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-33; 0,0" dur="5s" begin="4.5s" repeatCount="indefinite"/>
    </circle><circle cx="472" cy="232" r="2" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="3s" begin="6.4s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-34; 0,0" dur="6s" begin="4.8s" repeatCount="indefinite"/>
    </circle><circle cx="569" cy="369" r="3" fill="#06B6D4" opacity="0.5">
      <animate attributeName="opacity" values="0;0.7;0" dur="4s" begin="6.800000000000001s" repeatCount="indefinite"/>
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-35; 0,0" dur="7s" begin="5.1s" repeatCount="indefinite"/>
    </circle>

    <!-- divider -->
    <line x1="448" y1="30" x2="448" y2="580" stroke="url(#accentGrad-light)" stroke-opacity="0.25" stroke-width="1"/>

    <!-- LEFT PANEL -->
    <g clip-path="url(#leftClip-light)">
      <rect x="0" y="0" width="448" height="610" fill="#F8FAFC" fill-opacity="0.85"/>

      <text x="40" y="58" font-family="'JetBrains Mono',monospace" font-size="12" fill="#475569" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.1s" dur="0.4s" fill="freeze"/>
        &gt; whoami
      </text>

      <g>
        
      <text x="40" y="96" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.5s" dur="0.4s" fill="freeze"/>              ......
      </text>
      <text x="40" y="111" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.59s" dur="0.4s" fill="freeze"/>          ...::::::::...
      </text>
      <text x="40" y="126" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.68s" dur="0.4s" fill="freeze"/>        ..::----------::..
      </text>
      <text x="40" y="141" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.77s" dur="0.4s" fill="freeze"/>       .::--====++====--::.
      </text>
      <text x="40" y="156" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.86s" dur="0.4s" fill="freeze"/>      .::--=+++****+++=--::.
      </text>
      <text x="40" y="171" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.95s" dur="0.4s" fill="freeze"/>     ..:--=++**####**++=--:..
      </text>
      <text x="40" y="186" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="1.04s" dur="0.4s" fill="freeze"/>     ..:--=++*##%%##*++=--:..
      </text>
      <text x="40" y="201" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="1.13s" dur="0.4s" fill="freeze"/>     ..:--=++**####**++=--:..
      </text>
      <text x="40" y="216" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="1.22s" dur="0.4s" fill="freeze"/>      .::--=+++****+++=--::.
      </text>
      <text x="40" y="231" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="1.31s" dur="0.4s" fill="freeze"/>       .::--====++====--::.
      </text>
      <text x="40" y="246" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="1.4s" dur="0.4s" fill="freeze"/>        ..::----------::..
      </text>
      <text x="40" y="261" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="1.49s" dur="0.4s" fill="freeze"/>          ...::::::::...
      </text>
      <text x="40" y="276" font-family="'JetBrains Mono','Consolas',monospace" font-size="11" letter-spacing="1" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="1.58s" dur="0.4s" fill="freeze"/>              ......
      </text>
      </g>

      <rect x="40" y="297" width="8" height="12" fill="url(#asciiGrad-light)" opacity="0">
        <animate attributeName="opacity" begin="1.97s" dur="1s" values="1;0;1" repeatCount="indefinite"/>
      </rect>

      <text x="40" y="331" font-family="'JetBrains Mono',monospace" font-size="14" font-weight="700" fill="url(#accentGrad-light)" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="2.27" dur="0.5s" fill="freeze"/>
        Ketan_Patil.dev
      </text>

      <!-- scanline -->
      <rect x="0" y="0" width="448" height="3" fill="#06B6D4" opacity="0.12">
        <animateTransform attributeName="transform" type="translate" values="0,0; 0,610; 0,0" dur="6s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- RIGHT PANEL -->
    <g>
      <!-- terminal window chrome -->
      <rect x="488" y="36" width="652" height="40" rx="10" fill="#0F172A" fill-opacity="0.04" stroke="#0F172A" stroke-opacity="0.08"/>
      <circle cx="512" cy="56" r="5.5" fill="#EF4444" opacity="0.85"/>
      <circle cx="532" cy="56" r="5.5" fill="#F59E0B" opacity="0.85"/>
      <circle cx="552" cy="56" r="5.5" fill="#10B981" opacity="0.85"/>
      <text x="814.0" y="60" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="12" fill="#475569">ketan@dev:~</text>

      <text x="544" y="140" font-family="'Inter',sans-serif" font-size="20" fill="#475569" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.2s" dur="0.5s" fill="freeze"/>
        Hi
      </text>
      <text x="544" y="180" font-family="'Inter',sans-serif" font-size="38" font-weight="800" fill="#0F172A" opacity="0">
        <animate attributeName="opacity" from="0" to="1" begin="0.5s" dur="0.6s" fill="freeze"/>
        I'm <tspan fill="url(#accentGrad-light)">Ketan Patil</tspan>
      </text>

      <rect x="544" y="186" width="1" height="24" fill="none"/>
      
      <g opacity="0">
        <animate attributeName="opacity" begin="0s" dur="15.0s" repeatCount="indefinite"
          keyTimes="0.0000;0.1700;1.0000" values="1;1;0"/>
        <clipPath id="clipRolelight0">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="0s" dur="15.0s" repeatCount="indefinite"
              keyTimes="0.0000;0.0600;0.1700;1.0000" values="0;300.0;300.0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#clipRolelight0)">
          <text x="544" y="205" font-family="'JetBrains Mono','Consolas',monospace" font-size="21" font-weight="600" fill="url(#accentGrad-light)">Full Stack Web Developer</text>
        </g>
      </g>
      <g opacity="0">
        <animate attributeName="opacity" begin="0s" dur="15.0s" repeatCount="indefinite"
          keyTimes="0.0000;0.2000;0.3700;1.0000" values="0;1;1;0"/>
        <clipPath id="clipRolelight1">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="0s" dur="15.0s" repeatCount="indefinite"
              keyTimes="0.0000;0.2000;0.2600;0.3700;1.0000" values="0;0;375.0;375.0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#clipRolelight1)">
          <text x="544" y="205" font-family="'JetBrains Mono','Consolas',monospace" font-size="21" font-weight="600" fill="url(#accentGrad-light)">PHP &amp; CodeIgniter 4 Specialist</text>
        </g>
      </g>
      <g opacity="0">
        <animate attributeName="opacity" begin="0s" dur="15.0s" repeatCount="indefinite"
          keyTimes="0.0000;0.4000;0.5700;1.0000" values="0;1;1;0"/>
        <clipPath id="clipRolelight2">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="0s" dur="15.0s" repeatCount="indefinite"
              keyTimes="0.0000;0.4000;0.4600;0.5700;1.0000" values="0;0;225.0;225.0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#clipRolelight2)">
          <text x="544" y="205" font-family="'JetBrains Mono','Consolas',monospace" font-size="21" font-weight="600" fill="url(#accentGrad-light)">React.js Developer</text>
        </g>
      </g>
      <g opacity="0">
        <animate attributeName="opacity" begin="0s" dur="15.0s" repeatCount="indefinite"
          keyTimes="0.0000;0.6000;0.7700;1.0000" values="0;1;1;0"/>
        <clipPath id="clipRolelight3">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="0s" dur="15.0s" repeatCount="indefinite"
              keyTimes="0.0000;0.6000;0.6600;0.7700;1.0000" values="0;0;137.5;137.5;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#clipRolelight3)">
          <text x="544" y="205" font-family="'JetBrains Mono','Consolas',monospace" font-size="21" font-weight="600" fill="url(#accentGrad-light)">UI Engineer</text>
        </g>
      </g>
      <g opacity="0">
        <animate attributeName="opacity" begin="0s" dur="15.0s" repeatCount="indefinite"
          keyTimes="0.0000;0.8000;0.9700;1.0000" values="0;1;1;0"/>
        <clipPath id="clipRolelight4">
          <rect x="0" y="0" width="0" height="34">
            <animate attributeName="width" begin="0s" dur="15.0s" repeatCount="indefinite"
              keyTimes="0.0000;0.8000;0.8600;0.9700;1.0000" values="0;0;275.0;275.0;0"/>
          </rect>
        </clipPath>
        <g clip-path="url(#clipRolelight4)">
          <text x="544" y="205" font-family="'JetBrains Mono','Consolas',monospace" font-size="21" font-weight="600" fill="url(#accentGrad-light)">Open Source Enthusiast</text>
        </g>
      </g>
      
      <rect x="544" y="186" width="3" height="24" fill="url(#accentGrad-light)">
        <animate attributeName="x" begin="0s" dur="15.0s" repeatCount="indefinite"
          keyTimes="0.0000;0.0600;0.1700;0.2000;0.2600;0.3700;0.4000;0.4600;0.5700;0.6000;0.6600;0.7700;0.8000;0.8600;0.9700;1.0000" values="544;844.0;844.0;544;919.0;919.0;544;769.0;769.0;544;681.5;681.5;544;819.0;819.0;819.0"/>
        <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/>
      </rect>

      
      <g opacity="0" transform="translate(-10,0)">
        <animate attributeName="opacity" begin="3.6s" dur="0.5s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" begin="3.6s" dur="0.5s" fill="freeze" from="-10,0" to="0,0"/>
        <rect x="544" y="244" width="34" height="18" rx="5" fill="url(#accentGrad-light)" opacity="0.16"/>
        <text x="561" y="257" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="8.5" font-weight="700" fill="url(#accentGrad-light)">LOC</text>
        <text x="590" y="258" font-family="'Inter',sans-serif" font-size="13" fill="#475569">Location: <tspan fill="#0F172A" font-weight="600">Pune, Maharashtra, India</tspan></text>
      </g>
      <g opacity="0" transform="translate(-10,0)">
        <animate attributeName="opacity" begin="3.76s" dur="0.5s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" begin="3.76s" dur="0.5s" fill="freeze" from="-10,0" to="0,0"/>
        <rect x="544" y="273" width="34" height="18" rx="5" fill="url(#accentGrad-light)" opacity="0.16"/>
        <text x="561" y="286" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="8.5" font-weight="700" fill="url(#accentGrad-light)">EDU</text>
        <text x="590" y="287" font-family="'Inter',sans-serif" font-size="13" fill="#475569">Education: <tspan fill="#0F172A" font-weight="600">B.E. Computer Science</tspan></text>
      </g>
      <g opacity="0" transform="translate(-10,0)">
        <animate attributeName="opacity" begin="3.92s" dur="0.5s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" begin="3.92s" dur="0.5s" fill="freeze" from="-10,0" to="0,0"/>
        <rect x="544" y="302" width="34" height="18" rx="5" fill="url(#accentGrad-light)" opacity="0.16"/>
        <text x="561" y="315" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="8.5" font-weight="700" fill="url(#accentGrad-light)">JOB</text>
        <text x="590" y="316" font-family="'Inter',sans-serif" font-size="13" fill="#475569">Current Focus: <tspan fill="#0F172A" font-weight="600">Sr. Web Developer @ The Brand Bugzz</tspan></text>
      </g>
      <g opacity="0" transform="translate(-10,0)">
        <animate attributeName="opacity" begin="4.08s" dur="0.5s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" begin="4.08s" dur="0.5s" fill="freeze" from="-10,0" to="0,0"/>
        <rect x="544" y="331" width="34" height="18" rx="5" fill="url(#accentGrad-light)" opacity="0.16"/>
        <text x="561" y="344" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="8.5" font-weight="700" fill="url(#accentGrad-light)">PRJ</text>
        <text x="590" y="345" font-family="'Inter',sans-serif" font-size="13" fill="#475569">Featured Projects: <tspan fill="#0F172A" font-weight="600">Erupaiya · TPM · HRMS · LMS</tspan></text>
      </g>
      <g opacity="0" transform="translate(-10,0)">
        <animate attributeName="opacity" begin="4.24s" dur="0.5s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" begin="4.24s" dur="0.5s" fill="freeze" from="-10,0" to="0,0"/>
        <rect x="544" y="360" width="34" height="18" rx="5" fill="url(#accentGrad-light)" opacity="0.16"/>
        <text x="561" y="373" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="8.5" font-weight="700" fill="url(#accentGrad-light)">WEB</text>
        <text x="590" y="374" font-family="'Inter',sans-serif" font-size="13" fill="#475569">Portfolio: <tspan fill="#0F172A" font-weight="600">ketanpatil-phi.vercel.app</tspan></text>
      </g>
      <g opacity="0" transform="translate(-10,0)">
        <animate attributeName="opacity" begin="4.4s" dur="0.5s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" begin="4.4s" dur="0.5s" fill="freeze" from="-10,0" to="0,0"/>
        <rect x="544" y="389" width="34" height="18" rx="5" fill="url(#accentGrad-light)" opacity="0.16"/>
        <text x="561" y="402" text-anchor="middle" font-family="'JetBrains Mono',monospace" font-size="8.5" font-weight="700" fill="url(#accentGrad-light)">MAIL</text>
        <text x="590" y="403" font-family="'Inter',sans-serif" font-size="13" fill="#475569">Email: <tspan fill="#0F172A" font-weight="600">patilketan1303@gmail.com</tspan></text>
      </g>

      
      <g opacity="0" transform="scale(0.85)" style="transform-origin:512.1px 471.0px">
        <animate attributeName="opacity" begin="5.0s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.0s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="488" y="458" width="48.2" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="2.0s" repeatCount="indefinite"/>
        </rect>
        <text x="512.1" y="475.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">PHP</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:605.3000000000001px 471.0px">
        <animate attributeName="opacity" begin="5.08s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.08s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="544.2" y="458" width="122.2" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="2.35s" repeatCount="indefinite"/>
        </rect>
        <text x="605.3000000000001" y="475.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">CodeIgniter 4</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:717.0000000000001px 471.0px">
        <animate attributeName="opacity" begin="5.16s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.16s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="674.4000000000001" y="458" width="85.2" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="2.7s" repeatCount="indefinite"/>
        </rect>
        <text x="717.0000000000001" y="475.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">React.js</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:817.6000000000001px 471.0px">
        <animate attributeName="opacity" begin="5.24s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.24s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="767.6000000000001" y="458" width="100.0" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="3.05s" repeatCount="indefinite"/>
        </rect>
        <text x="817.6000000000001" y="475.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">TypeScript</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:925.6000000000001px 471.0px">
        <animate attributeName="opacity" begin="5.32s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.32s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="875.6000000000001" y="458" width="100.0" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="3.4s" repeatCount="indefinite"/>
        </rect>
        <text x="925.6000000000001" y="475.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">JavaScript</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:1015.1000000000001px 471.0px">
        <animate attributeName="opacity" begin="5.4s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.4s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="983.6000000000001" y="458" width="63.0" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="3.75s" repeatCount="indefinite"/>
        </rect>
        <text x="1015.1000000000001" y="475.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">MySQL</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:1093.5000000000002px 471.0px">
        <animate attributeName="opacity" begin="5.48s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.48s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="1054.6000000000001" y="458" width="77.8" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="4.1s" repeatCount="indefinite"/>
        </rect>
        <text x="1093.5000000000002" y="475.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">Node.js</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:519.5px 505.0px">
        <animate attributeName="opacity" begin="5.56s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.56s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="488" y="492" width="63.0" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="4.45s" repeatCount="indefinite"/>
        </rect>
        <text x="519.5" y="509.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">Redis</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:616.4px 505.0px">
        <animate attributeName="opacity" begin="5.64s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.64s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="559.0" y="492" width="114.8" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="4.8s" repeatCount="indefinite"/>
        </rect>
        <text x="616.4" y="509.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">Tailwind CSS</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:728.0999999999999px 505.0px">
        <animate attributeName="opacity" begin="5.72s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.72s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="681.8" y="492" width="92.6" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="5.15s" repeatCount="indefinite"/>
        </rect>
        <text x="728.0999999999999" y="509.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">WordPress</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:806.5px 505.0px">
        <animate attributeName="opacity" begin="5.8s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.8s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="782.4" y="492" width="48.2" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="5.5s" repeatCount="indefinite"/>
        </rect>
        <text x="806.5" y="509.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">Git</text>
      </g>
      <g opacity="0" transform="scale(0.85)" style="transform-origin:884.9px 505.0px">
        <animate attributeName="opacity" begin="5.88s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="scale" begin="5.88s" dur="0.4s" fill="freeze" from="0.85" to="1" additive="sum"/>
        <rect x="838.6" y="492" width="92.6" height="26" rx="15" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.5" stroke-width="1">
          <animate attributeName="stroke-opacity" values="0.35;0.8;0.35" dur="3s" begin="5.85s" repeatCount="indefinite"/>
        </rect>
        <text x="884.9" y="509.0" text-anchor="middle" font-family="'Inter',sans-serif" font-size="11.5" font-weight="600" fill="#0F172A">REST APIs</text>
      </g>

      
      <a xlink:href="https://github.com/Mrketan" target="_blank">
      <g opacity="0" transform="translate(505,552)">
        <animate attributeName="opacity" begin="5.8s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" values="0,0; 0,-4; 0,0" dur="3.4s" begin="1.2s" repeatCount="indefinite"/>
        <circle r="17" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.45" stroke-width="1.2">
          <animate attributeName="stroke-opacity" values="0.3;0.85;0.3" dur="2.6s" begin="1.2s" repeatCount="indefinite"/>
        </circle>
        <g transform="scale(0.62)" fill="#0F172A">
          <path d="M0 -12c-6.6 0-12 5.4-12 12 0 5.3 3.4 9.8 8.2 11.4.6.1.8-.3.8-.6v-2.2c-3.3.7-4-1.6-4-1.6-.5-1.4-1.3-1.8-1.3-1.8-1.1-.7.1-.7.1-.7 1.2.1 1.8 1.2 1.8 1.2 1.1 1.8 2.8 1.3 3.5 1 .1-.8.4-1.3.7-1.6-2.6-.3-5.4-1.3-5.4-5.8 0-1.3.5-2.3 1.2-3.1-.1-.3-.5-1.5.1-3.2 0 0 1-.3 3.3 1.2 1-.3 2-.4 3-.4s2 .1 3 .4c2.3-1.5 3.3-1.2 3.3-1.2.6 1.7.2 2.9.1 3.2.8.8 1.2 1.9 1.2 3.1 0 4.5-2.8 5.5-5.4 5.8.4.4.8 1.1.8 2.2v3.3c0 .3.2.7.8.6C8.6 21.8 12 17.3 12 12c0-6.6-5.4-12-12-12z"/>
        </g>
      </g>
      </a>
      <a xlink:href="https://www.linkedin.com/in/ketan-patil-webdeveloper/" target="_blank">
      <g opacity="0" transform="translate(557,552)">
        <animate attributeName="opacity" begin="5.92s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" values="0,0; 0,-4; 0,0" dur="3.4s" begin="1.6s" repeatCount="indefinite"/>
        <circle r="17" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.45" stroke-width="1.2">
          <animate attributeName="stroke-opacity" values="0.3;0.85;0.3" dur="2.6s" begin="1.6s" repeatCount="indefinite"/>
        </circle>
        <g transform="scale(0.62)" fill="#0F172A">
          <path d="M-10-10h5v20h-5zM-7.5-14a3 3 0 100-6 3 3 0 000 6zM-2-10h4.8v2.7h.1c.7-1.3 2.4-2.7 4.9-2.7 5.2 0 6.2 3.4 6.2 7.9V10H8.5V-1.3c0-2.7 0-6.1-3.7-6.1-3.7 0-4.3 2.9-4.3 5.9V10H-2z"/>
        </g>
      </g>
      </a>
      <a xlink:href="https://ketanpatil-phi.vercel.app/" target="_blank">
      <g opacity="0" transform="translate(609,552)">
        <animate attributeName="opacity" begin="6.04s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" values="0,0; 0,-4; 0,0" dur="3.4s" begin="2.0s" repeatCount="indefinite"/>
        <circle r="17" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.45" stroke-width="1.2">
          <animate attributeName="stroke-opacity" values="0.3;0.85;0.3" dur="2.6s" begin="2.0s" repeatCount="indefinite"/>
        </circle>
        <g transform="scale(0.62)" fill="#0F172A">
          <path d="M0-12a12 12 0 100 24 12 12 0 000-24zm0 2.4c1.5 1.7 2.6 3.8 3.1 6.1H-3.1c.5-2.3 1.6-4.4 3.1-6.1zM-9.2-3.5h4.6c-.4 2.1-.4 4.4 0 6.5h-4.6a9.6 9.6 0 010-6.5zm0 8.9h4.6c.5 2.3 1.6 4.4 3.1 6.1a9.7 9.7 0 01-7.7-6.1zm10.6 6.1c1.5-1.7 2.6-3.8 3.1-6.1H8c-1.2 2.8-3.6 5-6.6 6.1zM8.6 3H4c.2-1.1.3-2.2.3-3.3 0-1.1-.1-2.2-.3-3.2h4.6a9.6 9.6 0 010 6.5zM6.6-5.4H3.4a15.4 15.4 0 00-3.1-6.1c2.9 1.1 5.4 3.3 6.3 6.1zm-7.9-6.1a15.4 15.4 0 00-3.1 6.1h-3.2c1-2.8 3.4-5 6.3-6.1z"/>
        </g>
      </g>
      </a>
      <a xlink:href="mailto:patilketan1303@gmail.com" target="_blank">
      <g opacity="0" transform="translate(661,552)">
        <animate attributeName="opacity" begin="6.16s" dur="0.4s" fill="freeze" from="0" to="1"/>
        <animateTransform attributeName="transform" type="translate" additive="sum" values="0,0; 0,-4; 0,0" dur="3.4s" begin="2.4s" repeatCount="indefinite"/>
        <circle r="17" fill="#0F172A" fill-opacity="0.04" stroke="url(#accentGrad-light)" stroke-opacity="0.45" stroke-width="1.2">
          <animate attributeName="stroke-opacity" values="0.3;0.85;0.3" dur="2.6s" begin="2.4s" repeatCount="indefinite"/>
        </circle>
        <g transform="scale(0.62)" fill="#0F172A">
          <path d="M-12-8h24v16h-24zM-12-8l12 9-12 -9zm24 0L0 1l12-9"/>
        </g>
      </g>
      </a>
    </g>
  </g>

  <!-- outer glowing shimmer border -->
  <rect x="1.5" y="1.5" width="1177" height="607" rx="24" fill="none" stroke="url(#borderGrad-light)" stroke-width="2"/>
  <rect x="1.5" y="1.5" width="1177" height="607" rx="24" fill="none" stroke="#0F172A" stroke-opacity="0.08" stroke-width="1"/>
</svg>

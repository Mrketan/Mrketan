<linearGradient id="accentGrad-dark" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#7C3AED"/>
  <stop offset="50%" stop-color="#22D3EE"/>
  <stop offset="100%" stop-color="#10B981"/>
  <animate attributeName="x1" values="0%;100%;0%" dur="6s" repeatCount="indefinite"/>
  <animate attributeName="x2" values="100%;200%;100%" dur="6s" repeatCount="indefinite"/>
</linearGradient>

<linearGradient id="asciiGrad-dark" x1="0%" y1="0%" x2="100%" y2="100%">
  <stop offset="0%" stop-color="#22D3EE"/>
  <stop offset="100%" stop-color="#7C3AED">
    <animate attributeName="stop-color" values="#7C3AED;#22D3EE;#7C3AED" dur="5s" repeatCount="indefinite"/>
  </stop>
  <animate attributeName="x1" values="0%;30%;0%" dur="7s" repeatCount="indefinite"/>
</linearGradient>

<linearGradient id="borderGrad-dark" x1="0%" y1="0%" x2="100%" y2="100%">
  <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.7"/>
  <stop offset="50%" stop-color="#22D3EE" stop-opacity="0.7"/>
  <stop offset="100%" stop-color="#10B981" stop-opacity="0.7"/>
  <animateTransform attributeName="gradientTransform" type="rotate" from="0 590 305" to="360 590 305" dur="10s" repeatCount="indefinite"/>
</linearGradient>

<radialGradient id="blob1-dark" cx="50%" cy="50%" r="50%">
  <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.55"/>
  <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
</radialGradient>
<radialGradient id="blob2-dark" cx="50%" cy="50%" r="50%">
  <stop offset="0%" stop-color="#22D3EE" stop-opacity="0.55"/>
  <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
</radialGradient>
<radialGradient id="blob3-dark" cx="50%" cy="50%" r="50%">
  <stop offset="0%" stop-color="#10B981" stop-opacity="0.55"/>
  <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
</radialGradient>

<filter id="softBlur-dark" x="-50%" y="-50%" width="200%" height="200%">
  <feGaussianBlur stdDeviation="18"/>
</filter>
<filter id="glow-dark" x="-80%" y="-80%" width="260%" height="260%">
  <feGaussianBlur stdDeviation="3.2" result="blur"/>
  <feMerge>
    <feMergeNode in="blur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>
<filter id="noise-dark">
  <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="2" stitchTiles="stitch" result="noise"/>
  <feColorMatrix in="noise" type="matrix" values="0 0 0 0 1  0 0 0 0 1  0 0 0 0 1  0 0 0 0.5 0"/>
</filter>

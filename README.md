<svg viewBox="0 0 800 900" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#3178C6" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#3178C6" stop-opacity="0"/>
    </radialGradient>
    <filter id="blur" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="9"/>
    </filter>

    <path id="orbit1" d="M 190,345 A 210,85 0 1,1 610,345 A 210,85 0 1,1 190,345 Z"/>
    <path id="orbit2" d="M 190,345 A 210,85 0 1,1 610,345 A 210,85 0 1,1 190,345 Z"/>
    <path id="orbit3" d="M 190,345 A 210,85 0 1,1 610,345 A 210,85 0 1,1 190,345 Z"/>
  </defs>

  <rect x="0" y="0" width="800" height="900" rx="28" fill="#0d1117" stroke="#30363d" stroke-width="1.5"/>

  <text x="400" y="56" text-anchor="middle" font-family="Segoe UI, Verdana, sans-serif"
        font-size="24" font-weight="600" fill="#e6edf3" letter-spacing="0.5">Franklin&#8217;s Stack</text>
  <text x="400" y="80" text-anchor="middle" font-family="Segoe UI, Verdana, sans-serif"
        font-size="12" fill="#6e7681" letter-spacing="1.5">TYPESCRIPT AT THE CORE</text>

  <circle cx="400" cy="345" r="62" fill="url(#glow)" filter="url(#blur)">
    <animate attributeName="opacity" values="0.55;0.85;0.55" dur="6s" repeatCount="indefinite"/>
  </circle>

  <!-- orbit 1 tilt 0deg frontend -->
  <g transform="rotate(0 400 345)">
    <use href="#orbit1" xlink:href="#orbit1" fill="none" stroke="#61DAFB" stroke-opacity="0.16" stroke-width="1"/>
    <circle r="5.5" fill="#61DAFB">
      <animateMotion dur="18s" begin="0s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit1" xlink:href="#orbit1"/>
      </animateMotion>
    </circle>
    <circle r="5.5" fill="#61DAFB" opacity="0.85">
      <animateMotion dur="18s" begin="-6s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit1" xlink:href="#orbit1"/>
      </animateMotion>
    </circle>
    <circle r="5.5" fill="#61DAFB" opacity="0.7">
      <animateMotion dur="18s" begin="-12s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit1" xlink:href="#orbit1"/>
      </animateMotion>
    </circle>
  </g>

  <!-- orbit 2 tilt 60deg backend -->
  <g transform="rotate(60 400 345)">
    <use href="#orbit2" xlink:href="#orbit2" fill="none" stroke="#7c86e0" stroke-opacity="0.16" stroke-width="1"/>
    <circle r="5.5" fill="#7c86e0">
      <animateMotion dur="23s" begin="0s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit2" xlink:href="#orbit2"/>
      </animateMotion>
    </circle>
    <circle r="5.5" fill="#7c86e0" opacity="0.85">
      <animateMotion dur="23s" begin="-7.7s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit2" xlink:href="#orbit2"/>
      </animateMotion>
    </circle>
    <circle r="5.5" fill="#7c86e0" opacity="0.7">
      <animateMotion dur="23s" begin="-15.4s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit2" xlink:href="#orbit2"/>
      </animateMotion>
    </circle>
  </g>

  <!-- orbit 3 tilt 120deg data -->
  <g transform="rotate(120 400 345)">
    <use href="#orbit3" xlink:href="#orbit3" fill="none" stroke="#52b788" stroke-opacity="0.14" stroke-width="1"/>
    <circle r="5.5" fill="#52b788">
      <animateMotion dur="28s" begin="0s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit3" xlink:href="#orbit3"/>
      </animateMotion>
    </circle>
    <circle r="5.5" fill="#52b788" opacity="0.85">
      <animateMotion dur="28s" begin="-9.3s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit3" xlink:href="#orbit3"/>
      </animateMotion>
    </circle>
    <circle r="5.5" fill="#52b788" opacity="0.7">
      <animateMotion dur="28s" begin="-18.6s" repeatCount="indefinite" rotate="0">
        <mpath href="#orbit3" xlink:href="#orbit3"/>
      </animateMotion>
    </circle>
  </g>

  <!-- nucleus: TS only -->
  <circle cx="400" cy="345" r="34" fill="#3178C6" stroke="#0d1117" stroke-width="3"/>
  <text x="400" y="352" text-anchor="middle" font-family="Segoe UI, sans-serif" font-size="17" font-weight="700" fill="#ffffff">TS</text>

  <!-- legend, static -->
  <line x1="90" y1="600" x2="710" y2="600" stroke="#21262d" stroke-width="1"/>

  <text x="90" y="635" font-family="Segoe UI, sans-serif" font-size="11" fill="#6e7681" letter-spacing="1">FRONTEND</text>
  <circle cx="94" cy="656" r="4" fill="#61DAFB"/><text x="106" y="660" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">Next.js</text>
  <circle cx="94" cy="680" r="4" fill="#61DAFB"/><text x="106" y="684" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">React</text>
  <circle cx="94" cy="704" r="4" fill="#61DAFB"/><text x="106" y="708" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">React Native</text>

  <text x="330" y="635" font-family="Segoe UI, sans-serif" font-size="11" fill="#6e7681" letter-spacing="1">BACKEND</text>
  <circle cx="334" cy="656" r="4" fill="#7c86e0"/><text x="346" y="660" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">Node.js</text>
  <circle cx="334" cy="680" r="4" fill="#7c86e0"/><text x="346" y="684" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">NestJS</text>
  <circle cx="334" cy="704" r="4" fill="#7c86e0"/><text x="346" y="708" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">Express.js</text>

  <text x="570" y="635" font-family="Segoe UI, sans-serif" font-size="11" fill="#6e7681" letter-spacing="1">DATA</text>
  <circle cx="574" cy="656" r="4" fill="#52b788"/><text x="586" y="660" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">PostgreSQL</text>
  <circle cx="574" cy="680" r="4" fill="#52b788"/><text x="586" y="684" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">MongoDB</text>
  <circle cx="574" cy="704" r="4" fill="#52b788"/><text x="586" y="708" font-family="Segoe UI, sans-serif" font-size="13" fill="#c9d1d9">Prisma</text>

  <text x="400" y="770" text-anchor="middle" font-family="Segoe UI, sans-serif" font-size="11" fill="#484f58">
    Full Stack JavaScript / TypeScript Developer
  </text>
</svg>

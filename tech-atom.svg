<svg viewBox="0 0 800 900" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#3178C6" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#3178C6" stop-opacity="0"/>
    </radialGradient>
    <filter id="blur" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="9"/>
    </filter>

    <style>
      /* ellipse offset from center, sampled every 30deg (rx=210, ry=85) */
      @keyframes orbitMove {
        0%    { transform: translate(210px, 0px); }
        8.33% { transform: translate(181.9px, 42.5px); }
        16.67%{ transform: translate(105px, 73.6px); }
        25%   { transform: translate(0px, 85px); }
        33.33%{ transform: translate(-105px, 73.6px); }
        41.67%{ transform: translate(-181.9px, 42.5px); }
        50%   { transform: translate(-210px, 0px); }
        58.33%{ transform: translate(-181.9px, -42.5px); }
        66.67%{ transform: translate(-105px, -73.6px); }
        75%   { transform: translate(0px, -85px); }
        83.33%{ transform: translate(105px, -73.6px); }
        91.67%{ transform: translate(181.9px, -42.5px); }
        100%  { transform: translate(210px, 0px); }
      }
      @keyframes glowPulse {
        0%, 100% { opacity: 0.55; }
        50%      { opacity: 0.85; }
      }
      .electron { animation-name: orbitMove; animation-timing-function: linear; animation-iteration-count: infinite; }
      .glow { animation: glowPulse 6s ease-in-out infinite; }
    </style>
  </defs>

  <rect x="0" y="0" width="800" height="900" rx="28" fill="#0d1117" stroke="#30363d" stroke-width="1.5"/>

  <text x="400" y="56" text-anchor="middle" font-family="Segoe UI, Verdana, sans-serif"
        font-size="24" font-weight="600" fill="#e6edf3" letter-spacing="0.5">Franklin&#8217;s Stack</text>
  <text x="400" y="80" text-anchor="middle" font-family="Segoe UI, Verdana, sans-serif"
        font-size="12" fill="#6e7681" letter-spacing="1.5">TYPESCRIPT AT THE CORE</text>

  <circle class="glow" cx="400" cy="345" r="62" fill="url(#glow)" filter="url(#blur)"/>

  <!-- orbit 1 tilt 0deg frontend -->
  <g transform="rotate(0 400 345)">
    <ellipse cx="400" cy="345" rx="210" ry="85" fill="none" stroke="#61DAFB" stroke-opacity="0.16" stroke-width="1"/>
    <g transform="translate(400,345)">
      <circle class="electron" r="5.5" fill="#61DAFB" style="animation-duration:18s; animation-delay:0s"/>
      <circle class="electron" r="5.5" fill="#61DAFB" opacity="0.85" style="animation-duration:18s; animation-delay:-6s"/>
      <circle class="electron" r="5.5" fill="#61DAFB" opacity="0.7" style="animation-duration:18s; animation-delay:-12s"/>
    </g>
  </g>

  <!-- orbit 2 tilt 60deg backend -->
  <g transform="rotate(60 400 345)">
    <ellipse cx="400" cy="345" rx="210" ry="85" fill="none" stroke="#7c86e0" stroke-opacity="0.16" stroke-width="1"/>
    <g transform="translate(400,345)">
      <circle class="electron" r="5.5" fill="#7c86e0" style="animation-duration:23s; animation-delay:0s"/>
      <circle class="electron" r="5.5" fill="#7c86e0" opacity="0.85" style="animation-duration:23s; animation-delay:-7.7s"/>
      <circle class="electron" r="5.5" fill="#7c86e0" opacity="0.7" style="animation-duration:23s; animation-delay:-15.4s"/>
    </g>
  </g>

  <!-- orbit 3 tilt 120deg data -->
  <g transform="rotate(120 400 345)">
    <ellipse cx="400" cy="345" rx="210" ry="85" fill="none" stroke="#52b788" stroke-opacity="0.14" stroke-width="1"/>
    <g transform="translate(400,345)">
      <circle class="electron" r="5.5" fill="#52b788" style="animation-duration:28s; animation-delay:0s"/>
      <circle class="electron" r="5.5" fill="#52b788" opacity="0.85" style="animation-duration:28s; animation-delay:-9.3s"/>
      <circle class="electron" r="5.5" fill="#52b788" opacity="0.7" style="animation-duration:28s; animation-delay:-18.6s"/>
    </g>
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

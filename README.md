# Franklin Rodriguez

<p align="center">

<svg width="900" height="480" viewBox="0 0 900 480" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bgGlow" cx="50%" cy="42%" r="70%">
      <stop offset="0%" stop-color="#0d1b2e" />
      <stop offset="100%" stop-color="#0A0A0A" />
    </radialGradient>
    <radialGradient id="nucleusGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#3AA0FF" />
      <stop offset="55%" stop-color="#007BFF" />
      <stop offset="100%" stop-color="#0056b3" />
    </radialGradient>
    <filter id="softGlow" x="-100%" y="-100%" width="300%" height="300%">
      <feGaussianBlur stdDeviation="6" result="blur" />
      <feMerge><feMergeNode in="blur" /><feMergeNode in="SourceGraphic" /></feMerge>
    </filter>
    <filter id="dotGlow" x="-150%" y="-150%" width="400%" height="400%">
      <feGaussianBlur stdDeviation="2.2" result="blur" />
      <feMerge><feMergeNode in="blur" /><feMergeNode in="SourceGraphic" /></feMerge>
    </filter>
    <path id="orbitPath" d="M -215,0 A 215,78 0 1,1 215,0 A 215,78 0 1,1 -215,0" />
  </defs>
  <rect x="0" y="0" width="900" height="480" rx="18" fill="url(#bgGlow)" />
  <rect x="1" y="1" width="898" height="478" rx="17" fill="none" stroke="#1a2a3d" stroke-width="1.5" />
  <g transform="translate(450,195)">
    <g transform="rotate(0)"><ellipse cx="0" cy="0" rx="215" ry="78" fill="none" stroke="#007BFF" stroke-opacity="0.30" stroke-width="1.4" /></g>
    <g transform="rotate(60)"><ellipse cx="0" cy="0" rx="215" ry="78" fill="none" stroke="#007BFF" stroke-opacity="0.30" stroke-width="1.4" /></g>
    <g transform="rotate(120)"><ellipse cx="0" cy="0" rx="215" ry="78" fill="none" stroke="#007BFF" stroke-opacity="0.30" stroke-width="1.4" /></g>
    <g transform="rotate(0)">
      <circle r="10" fill="#111111" stroke="#ffffff" stroke-width="1.4" filter="url(#dotGlow)">
        <title>Next.js</title>
        <animateMotion dur="9s" repeatCount="indefinite" rotate="0"><mpath href="#orbitPath" /></animateMotion>
      </circle>
      <circle r="9" fill="#6cc3ff" filter="url(#dotGlow)">
        <title>Express.js</title>
        <animateMotion dur="9s" repeatCount="indefinite" rotate="0" begin="-3s"><mpath href="#orbitPath" /></animateMotion>
      </circle>
      <circle r="9" fill="#47A248" filter="url(#dotGlow)">
        <title>MongoDB</title>
        <animateMotion dur="9s" repeatCount="indefinite" rotate="0" begin="-6s"><mpath href="#orbitPath" /></animateMotion>
      </circle>
    </g>
    <g transform="rotate(60)">
      <circle r="10" fill="#61DAFB" filter="url(#dotGlow)">
        <title>React</title>
        <animateMotion dur="10.5s" repeatCount="indefinite" rotate="0"><mpath href="#orbitPath" /></animateMotion>
      </circle>
      <circle r="9" fill="#7ee787" filter="url(#dotGlow)">
        <title>Node.js</title>
        <animateMotion dur="10.5s" repeatCount="indefinite" rotate="0" begin="-3.5s"><mpath href="#orbitPath" /></animateMotion>
      </circle>
      <circle r="9" fill="#3ECF8E" filter="url(#dotGlow)">
        <title>Supabase</title>
        <animateMotion dur="10.5s" repeatCount="indefinite" rotate="0" begin="-7s"><mpath href="#orbitPath" /></animateMotion>
      </circle>
    </g>
    <g transform="rotate(120)">
      <circle r="10" fill="#0078D4" filter="url(#dotGlow)">
        <title>Azure</title>
        <animateMotion dur="12s" repeatCount="indefinite" rotate="0"><mpath href="#orbitPath" /></animateMotion>
      </circle>
      <circle r="9" fill="#5b9bd5" filter="url(#dotGlow)">
        <title>PostgreSQL</title>
        <animateMotion dur="12s" repeatCount="indefinite" rotate="0" begin="-6s"><mpath href="#orbitPath" /></animateMotion>
      </circle>
    </g>
    <circle r="46" fill="url(#nucleusGlow)" filter="url(#softGlow)">
      <animate attributeName="r" values="44;48;44" dur="3s" repeatCount="indefinite" />
    </circle>
    <text x="0" y="8" text-anchor="middle" font-family="Consolas, 'Space Grotesk', monospace" font-size="26" font-weight="700" fill="#ffffff">TS</text>
  </g>
  <g font-family="Consolas, 'Space Grotesk', monospace" font-size="13" fill="#c8d3e0">
    <g transform="translate(450,412)">
      <g transform="translate(-360,0)"><circle cx="0" cy="-4" r="6" fill="#111111" stroke="#ffffff" stroke-width="1.2" /><text x="12" y="0">Next.js</text></g>
      <g transform="translate(-255,0)"><circle cx="0" cy="-4" r="6" fill="#6cc3ff" /><text x="12" y="0">Express.js</text></g>
      <g transform="translate(-135,0)"><circle cx="0" cy="-4" r="6" fill="#47A248" /><text x="12" y="0">MongoDB</text></g>
      <g transform="translate(-15,0)"><circle cx="0" cy="-4" r="6" fill="#61DAFB" /><text x="12" y="0">React</text></g>
      <g transform="translate(75,0)"><circle cx="0" cy="-4" r="6" fill="#7ee787" /><text x="12" y="0">Node.js</text></g>
      <g transform="translate(180,0)"><circle cx="0" cy="-4" r="6" fill="#007BFF" /><text x="12" y="0">TypeScript (core)</text></g>
    </g>
    <g transform="translate(450,440)">
      <g transform="translate(-160,0)"><circle cx="0" cy="-4" r="6" fill="#3ECF8E" /><text x="12" y="0">Supabase</text></g>
      <g transform="translate(-45,0)"><circle cx="0" cy="-4" r="6" fill="#0078D4" /><text x="12" y="0">Azure</text></g>
      <g transform="translate(50,0)"><circle cx="0" cy="-4" r="6" fill="#5b9bd5" /><text x="12" y="0">PostgreSQL</text></g>
    </g>
  </g>
</svg>

</p>

**Full Stack Developer | Next.js, TypeScript & Node.js**

## About Me

Full Stack Developer focused on building modern web applications with Next.js, React, TypeScript, Node.js, and PostgreSQL.

My main interests are backend development, scalable systems, and creating software that solves real business problems. I enjoy working across the full development lifecycle, from designing user interfaces to building APIs and managing data.

I am currently expanding my knowledge in NestJS, Docker, backend architecture, and advanced Next.js patterns.

## Tech Stack

### Frontend
- Next.js
- React
- TypeScript

### Backend
- Node.js
- Express.js
- REST APIs
- JWT Authentication

### Database
- PostgreSQL
- MongoDB
- Prisma ORM
- Supabase

### Cloud & Tools
- Azure
- Git
- GitHub
- Vercel
- Render

## Featured Projects

### Trux
A logistics platform focused on fleet auditing, operational management, and real-time tracking.

### Semtex
An autonomous AI copilot for SME financial management. It securely parses accounting files, provides natural language insights, and streamlines reporting.

### Riwlogic
Projects focused on algorithms, workflow optimization, and process automation.

## Currently Learning
- NestJS
- Docker
- Backend Architecture
- Advanced Next.js Patterns
- Data Structures & Algorithms

## Let's Connect
- LinkedIn: [linkedin.com/in/franklirodriguez](https://www.linkedin.com/in/franklirodriguez/)
- Portfolio: [portfolio-sandyrho-3rf5robkj9.vercel.app](https://portfolio-sandyrho-3rf5robkj9.vercel.app/)
- Email: FranklinRodriguezDev@gmail.com

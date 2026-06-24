<p align="center">
	<!-- <img src="_zulan.png"> -->
	<!-- <img src="https://capsule-render.vercel.app/api?type=waving&color=100:ffffff,100:1a1a2e&height=160&section=header&text=Zulan&fontSize=42&fontColor=ffffff&fontAlignY=55&desc=%20Developer%20&descSize=14&descAlignY=75&descColor=888888" /> -->
</p>

<svg width="1200" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="space" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#050816"/>
      <stop offset="50%" stop-color="#0f172a"/>
      <stop offset="100%" stop-color="#020617"/>
    </linearGradient>

    <!-- Glow -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Star -->
    <circle id="star" r="1.5" fill="white"/>
  </defs>

  <!-- Background -->
  <rect width="1200" height="320" fill="url(#space)"/>

  <!-- Animated Stars -->
  <g opacity="0.9">
    <use href="#star" x="80" y="40">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/>
    </use>
    <use href="#star" x="240" y="90">
      <animate attributeName="opacity" values="1;0.1;1" dur="2.5s" repeatCount="indefinite"/>
    </use>
    <use href="#star" x="420" y="50">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="4s" repeatCount="indefinite"/>
    </use>
    <use href="#star" x="610" y="110">
      <animate attributeName="opacity" values="1;0.2;1" dur="2.2s" repeatCount="indefinite"/>
    </use>
    <use href="#star" x="820" y="70">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="5s" repeatCount="indefinite"/>
    </use>
    <use href="#star" x="1040" y="40">
      <animate attributeName="opacity" values="1;0.1;1" dur="3.5s" repeatCount="indefinite"/>
    </use>

    <!-- Moving stars -->
    <circle cx="0" cy="40" r="2" fill="#7dd3fc">
      <animate attributeName="cx" from="-20" to="1220" dur="15s" repeatCount="indefinite"/>
    </circle>

    <circle cx="0" cy="250" r="1.5" fill="#c084fc">
      <animate attributeName="cx" from="-20" to="1220" dur="22s" repeatCount="indefinite"/>
    </circle>

    <circle cx="1200" cy="180" r="2" fill="#60a5fa">
      <animate attributeName="cx" from="1220" to="-20" dur="18s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Nebula Glow -->
  <circle cx="200" cy="100" r="120" fill="#4f46e5" opacity="0.12">
    <animate attributeName="r" values="110;130;110" dur="8s" repeatCount="indefinite"/>
  </circle>

  <circle cx="950" cy="220" r="140" fill="#7c3aed" opacity="0.1">
    <animate attributeName="r" values="130;150;130" dur="10s" repeatCount="indefinite"/>
  </circle>

  <!-- Title -->
  <text
    x="600"
    y="130"
    text-anchor="middle"
    fill="#ffffff"
    font-family="Segoe UI, Arial, sans-serif"
    font-size="72"
    font-weight="700"
    filter="url(#glow)">
    Zulan
  </text>

  <!-- Typing Text Area -->
  <g transform="translate(600,210)">
    <text
      x="0"
      y="0"
      text-anchor="middle"
      fill="#7dd3fc"
      font-family="Consolas, Monaco, monospace"
      font-size="32">

      <!-- .NET Developer -->
      <tspan opacity="0">
        .NET Developer
        <animate attributeName="opacity"
                 values="0;1;1;0"
                 keyTimes="0;0.05;0.28;0.33"
                 dur="12s"
                 repeatCount="indefinite"/>
      </tspan>

      <!-- Game Developer -->
      <tspan opacity="0">
        Game Developer
        <animate attributeName="opacity"
                 values="0;0;1;1;0"
                 keyTimes="0;0.33;0.38;0.61;0.66"
                 dur="12s"
                 repeatCount="indefinite"/>
      </tspan>

      <!-- Full-Stack Developer -->
      <tspan opacity="0">
        Full-Stack Developer
        <animate attributeName="opacity"
                 values="0;0;1;1;0"
                 keyTimes="0;0.66;0.71;0.94;1"
                 dur="12s"
                 repeatCount="indefinite"/>
      </tspan>
    </text>

    <!-- Blinking Cursor -->
    <rect x="155" y="-28" width="4" height="36" fill="#7dd3fc">
      <animate attributeName="opacity"
               values="1;0;1"
               dur="0.8s"
               repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- Shooting Star -->
  <g opacity="0.8">
    <line x1="0" y1="0" x2="80" y2="0" stroke="white" stroke-width="2">
      <animateTransform
        attributeName="transform"
        type="translate"
        from="-100 40"
        to="1300 280"
        dur="8s"
        repeatCount="indefinite"/>
    </line>
  </g>
</svg>

## Tech Stack

### Languages
<p align="left">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### Frameworks/Engines
<p align="left">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white" />
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Django_REST_FRAMEWORK-2D5C40?style=for-the-badge&logo=django&logoColor=white" />
</p>

<!--
**rZulan/rZulan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

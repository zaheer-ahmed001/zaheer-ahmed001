<div align="center">

<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <title>Zaheer Ahmed Khan - DevOps Engineer GitHub Banner</title>
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#060d1f"/>
      <stop offset="100%" stop-color="#0b1730"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#38bdf8"/>
      <stop offset="40%" stop-color="#818cf8"/>
      <stop offset="100%" stop-color="#06b6d4"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#38bdf8" stop-opacity="0"/>
      <stop offset="50%" stop-color="#818cf8"/>
      <stop offset="100%" stop-color="#06b6d4" stop-opacity="0"/>
    </linearGradient>
    <filter id="nameGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="redShift">
      <feOffset dx="-4" dy="0" result="shifted"/>
      <feFlood flood-color="#ff003c" flood-opacity="0.7" result="color"/>
      <feComposite in="color" in2="shifted" operator="in" result="colorShifted"/>
      <feMerge><feMergeNode in="colorShifted"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="blueShift">
      <feOffset dx="4" dy="0" result="shifted"/>
      <feFlood flood-color="#00f7ff" flood-opacity="0.7" result="color"/>
      <feComposite in="color" in2="shifted" operator="in" result="colorShifted"/>
      <feMerge><feMergeNode in="colorShifted"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="dotGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="clip1">
      <rect x="0" y="55" width="800" height="18"/>
    </clipPath>
    <clipPath id="clip2">
      <rect x="0" y="80" width="800" height="12"/>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" fill="url(#bg)" rx="12"/>

  <!-- Grid lines horizontal -->
  <line x1="0" y1="50" x2="800" y2="50" stroke="#1e3a5f" stroke-width="0.5" opacity="0.5"/>
  <line x1="0" y1="100" x2="800" y2="100" stroke="#1e3a5f" stroke-width="0.5" opacity="0.3"/>
  <line x1="0" y1="150" x2="800" y2="150" stroke="#1e3a5f" stroke-width="0.5" opacity="0.5"/>

  <!-- Grid lines vertical -->
  <line x1="100" y1="0" x2="100" y2="200" stroke="#1e3a5f" stroke-width="0.5" opacity="0.25"/>
  <line x1="200" y1="0" x2="200" y2="200" stroke="#1e3a5f" stroke-width="0.5" opacity="0.25"/>
  <line x1="300" y1="0" x2="300" y2="200" stroke="#1e3a5f" stroke-width="0.5" opacity="0.25"/>
  <line x1="400" y1="0" x2="400" y2="200" stroke="#1e3a5f" stroke-width="0.5" opacity="0.25"/>
  <line x1="500" y1="0" x2="500" y2="200" stroke="#1e3a5f" stroke-width="0.5" opacity="0.25"/>
  <line x1="600" y1="0" x2="600" y2="200" stroke="#1e3a5f" stroke-width="0.5" opacity="0.25"/>
  <line x1="700" y1="0" x2="700" y2="200" stroke="#1e3a5f" stroke-width="0.5" opacity="0.25"/>

  <!-- Corner brackets -->
  <path d="M20,10 L10,10 L10,30" fill="none" stroke="#38bdf8" stroke-width="1.5" opacity="0.7"/>
  <path d="M780,10 L790,10 L790,30" fill="none" stroke="#38bdf8" stroke-width="1.5" opacity="0.7"/>
  <path d="M20,190 L10,190 L10,170" fill="none" stroke="#38bdf8" stroke-width="1.5" opacity="0.7"/>
  <path d="M780,190 L790,190 L790,170" fill="none" stroke="#38bdf8" stroke-width="1.5" opacity="0.7"/>

  <!-- Decorative terminal text -->
  <text x="28" y="70" font-family="'Courier New', monospace" font-size="9" fill="#38bdf8" opacity="0.18">$ docker build .</text>
  <text x="28" y="84" font-family="'Courier New', monospace" font-size="9" fill="#06b6d4" opacity="0.14">$ kubectl apply</text>
  <text x="28" y="98" font-family="'Courier New', monospace" font-size="9" fill="#818cf8" opacity="0.12">$ terraform plan</text>
  <text x="600" y="110" font-family="'Courier New', monospace" font-size="9" fill="#38bdf8" opacity="0.15">$ aws deploy</text>
  <text x="600" y="124" font-family="'Courier New', monospace" font-size="9" fill="#06b6d4" opacity="0.12">$ git push</text>
  <text x="600" y="138" font-family="'Courier New', monospace" font-size="9" fill="#818cf8" opacity="0.10">$ jenkins run</text>

  <!-- ============ GLITCH NAME LAYERS ============ -->

  <!-- Red ghost (left shift) — glitch layer 1 -->
  <text
    x="400" y="94"
    text-anchor="middle"
    dominant-baseline="middle"
    font-family="'Segoe UI', 'Arial', sans-serif"
    font-size="48"
    font-weight="800"
    letter-spacing="1.5"
    fill="#ff003c"
    opacity="0"
    filter="url(#nameGlow)"
  >
    Zaheer Ahmed Khan
    <!-- Normal opacity rhythm -->
    <animate attributeName="opacity" values="0;0;0;0.7;0;0;0;0;0.5;0;0;0;0;0;0.6;0;0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
    <!-- Horizontal glitch shift -->
    <animateTransform attributeName="transform" type="translate" values="0,0;0,0;0,0;-5,2;0,0;0,0;0,0;0,0;-3,1;0,0;0,0;0,0;0,0;0,0;-6,0;0,0;0,0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
  </text>

  <!-- Cyan ghost (right shift) — glitch layer 2 -->
  <text
    x="400" y="94"
    text-anchor="middle"
    dominant-baseline="middle"
    font-family="'Segoe UI', 'Arial', sans-serif"
    font-size="48"
    font-weight="800"
    letter-spacing="1.5"
    fill="#00f7ff"
    opacity="0"
    filter="url(#nameGlow)"
  >
    Zaheer Ahmed Khan
    <animate attributeName="opacity" values="0;0;0;0;0.6;0;0;0;0;0;0.5;0;0;0;0;0.7;0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,0;0,0;0,0;5,-1;0,0;0,0;0,0;0,0;0,0;4,2;0,0;0,0;0,0;0,0;6,-2;0,0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
  </text>

  <!-- Glitch slice 1 — horizontal strip displaced -->
  <text
    x="400" y="94"
    text-anchor="middle"
    dominant-baseline="middle"
    font-family="'Segoe UI', 'Arial', sans-serif"
    font-size="48"
    font-weight="800"
    letter-spacing="1.5"
    fill="url(#nameGrad)"
    clip-path="url(#clip1)"
    opacity="0"
  >
    Zaheer Ahmed Khan
    <animate attributeName="opacity" values="0;0;0;0;0;1;0;0;0;0;0;1;0;0;0;0;0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,0;0,0;0,0;0,0;18,0;0,0;0,0;0,0;0,0;0,0;-14,0;0,0;0,0;0,0;0,0;0,0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
  </text>

  <!-- Glitch slice 2 — another strip -->
  <text
    x="400" y="94"
    text-anchor="middle"
    dominant-baseline="middle"
    font-family="'Segoe UI', 'Arial', sans-serif"
    font-size="48"
    font-weight="800"
    letter-spacing="1.5"
    fill="url(#nameGrad)"
    clip-path="url(#clip2)"
    opacity="0"
  >
    Zaheer Ahmed Khan
    <animate attributeName="opacity" values="0;0;0;0;0;0;0;1;0;0;0;0;0;1;0;0;0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,0;0,0;0,0;0,0;0,0;0,0;-22,0;0,0;0,0;0,0;0,0;0,0;20,0;0,0;0,0;0,0" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
  </text>

  <!-- MAIN name — always visible, glitch flickers -->
  <text
    x="400" y="94"
    text-anchor="middle"
    dominant-baseline="middle"
    font-family="'Segoe UI', 'Arial', sans-serif"
    font-size="48"
    font-weight="800"
    letter-spacing="1.5"
    fill="url(#nameGrad)"
    filter="url(#nameGlow)"
  >
    Zaheer Ahmed Khan
    <!-- Main text flickers briefly during glitch moments -->
    <animate attributeName="opacity" values="1;1;1;0.1;1;0.05;1;0.1;1;1;0.05;1;1;0.1;1;0.05;1" dur="4s" repeatCount="indefinite" calcMode="discrete"/>
  </text>

  <!-- Subtitle -->
  <text
    x="400" y="138"
    text-anchor="middle"
    dominant-baseline="middle"
    font-family="'Fira Code', 'Courier New', monospace"
    font-size="15"
    font-weight="500"
    letter-spacing="4"
    fill="#94a3b8"
    opacity="0"
  >
    ⚡ DevOps Engineer · AWS · CI/CD · IaC ⚡
    <animate attributeName="opacity" values="0;0;0.88" dur="2s" fill="freeze" keyTimes="0;0.5;1"/>
  </text>

  <!-- Animated underline -->
  <rect x="400" y="160" width="0" height="2" rx="1" fill="url(#lineGrad)">
    <animate attributeName="width" values="0;360" dur="1s" begin="0.8s" fill="freeze"/>
    <animate attributeName="x" values="400;220" dur="1s" begin="0.8s" fill="freeze"/>
  </rect>

  <!-- Pulsing end dots -->
  <circle cx="220" cy="161" r="3" fill="#38bdf8" opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.3s" begin="1.8s" fill="freeze"/>
    <animate attributeName="r" values="3;5;3" dur="2s" begin="2.1s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.4;1" dur="2s" begin="2.1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="580" cy="161" r="3" fill="#06b6d4" opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.3s" begin="1.8s" fill="freeze"/>
    <animate attributeName="r" values="3;5;3" dur="2.4s" begin="2.1s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.4;1" dur="2.4s" begin="2.1s" repeatCount="indefinite"/>
  </circle>

  <!-- Floating glowing particles -->
  <circle cx="55" cy="40" r="2.5" fill="#38bdf8" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.9;0" dur="3.5s" begin="0.5s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="40;34;40" dur="3.5s" begin="0.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="745" cy="160" r="2" fill="#818cf8" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.8;0" dur="4s" begin="1s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="160;154;160" dur="4s" begin="1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="22" r="1.8" fill="#06b6d4" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.7;0" dur="5s" begin="0s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="22;16;22" dur="5s" begin="0s" repeatCount="indefinite"/>
  </circle>
  <circle cx="680" cy="55" r="2.2" fill="#38bdf8" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;1;0" dur="3.8s" begin="2s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="55;49;55" dur="3.8s" begin="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="130" cy="165" r="1.6" fill="#818cf8" filter="url(#dotGlow)" opacity="0">
    <animate attributeName="opacity" values="0;0.8;0" dur="4.5s" begin="0.7s" repeatCount="indefinite"/>
    <animate attributeName="cy" values="165;159;165" dur="4.5s" begin="0.7s" repeatCount="indefinite"/>
  </circle>
</svg>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=800&color=00C8FF&center=true&vCenter=true&width=620&lines=Build+%F0%9F%94%A7+%7C+Automate+%E2%9A%A1+%7C+Deploy+%F0%9F%9A%80+%7C+Repeat+%F0%9F%94%84" alt="Typing SVG" />

</div>

---

### 🛠️ Tools & Technologies

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![WSL](https://img.shields.io/badge/WSL-0078D4?style=for-the-badge&logo=windows&logoColor=white)

---

### ☁️ AWS Services

![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white)

---

### 🚀 Focus Areas

![CI/CD](https://img.shields.io/badge/CI%2FCD-0A0A0A?style=for-the-badge&logo=githubactions&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-FF6F00?style=for-the-badge&logo=ansible&logoColor=white)
![Containerization](https://img.shields.io/badge/Containerization-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 📊 GitHub Stats

![Zaheer's GitHub Stats](https://github-readme-stats.vercel.app/api?username=zaheer-ahmed001&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=zaheer-ahmed001&layout=compact&theme=tokyonight)

> *"Automate everything. Deploy anywhere."*

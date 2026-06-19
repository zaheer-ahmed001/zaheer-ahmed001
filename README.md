<div align="center">

<svg width="800" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0a"/>
      <stop offset="50%" style="stop-color:#0d1b2a"/>
      <stop offset="100%" style="stop-color:#0a0a0a"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00C8FF">
        <animate attributeName="stop-color" values="#00C8FF;#0052FF;#00C8FF" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#0052FF">
        <animate attributeName="stop-color" values="#0052FF;#00C8FF;#0052FF" dur="3s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" fill="url(#bg)" rx="12"/>

  <!-- Animated particles -->
  <circle cx="50" cy="50" r="2" fill="#00C8FF" opacity="0.5">
    <animate attributeName="cy" values="50;150;50" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0;0.5" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="120" r="1.5" fill="#0052FF" opacity="0.4">
    <animate attributeName="cy" values="120;30;120" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0;0.4" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="80" r="2" fill="#00C8FF" opacity="0.5">
    <animate attributeName="cy" values="80;160;80" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0;0.5" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="30" r="1.5" fill="#0052FF" opacity="0.3">
    <animate attributeName="cy" values="30;130;30" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="350" cy="170" r="2" fill="#00C8FF" opacity="0.4">
    <animate attributeName="cy" values="170;40;170" dur="4.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0;0.4" dur="4.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Main name text with gradient and glow -->
  <text x="400" y="100" font-family="Fira Code, monospace" font-size="42" font-weight="700"
        fill="url(#textGrad)" text-anchor="middle" filter="url(#glow)">
    Zaheer Ahmed Khan
    <animate attributeName="opacity" values="0;1" dur="1s" fill="freeze"/>
  </text>

  <!-- Subtitle -->
  <text x="400" y="145" font-family="Fira Code, monospace" font-size="18" font-weight="400"
        fill="#ffffff" text-anchor="middle" opacity="0.85">
    Aspiring DevOps Engineer 🚀
    <animate attributeName="opacity" values="0;0.85" dur="1.5s" fill="freeze"/>
  </text>

  <!-- Bottom line decoration -->
  <line x1="200" y1="165" x2="600" y2="165" stroke="url(#textGrad)" stroke-width="1.5" opacity="0.6">
    <animate attributeName="x1" values="400;200;400" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="400;600;400" dur="3s" repeatCount="indefinite"/>
  </line>

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

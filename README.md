<div align="center">

<svg width="640" height="460" viewBox="0 0 640 460" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0a0e27"/>
      <stop offset="100%" stop-color="#141b3d"/>
    </linearGradient>
    <linearGradient id="head" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#e8ecf5"/>
      <stop offset="100%" stop-color="#aab4d4"/>
    </linearGradient>
    <linearGradient id="body" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#1b2450"/>
      <stop offset="100%" stop-color="#0f1533"/>
    </linearGradient>
    <filter id="blur"><feGaussianBlur stdDeviation="18"/></filter>
  </defs>

  <rect width="640" height="460" rx="24" fill="url(#bg)"/>

  <ellipse cx="320" cy="400" rx="170" ry="30" fill="#3b82f6" filter="url(#blur)" opacity="0.35">
    <animate attributeName="opacity" values="0.2;0.45;0.2" dur="3s" repeatCount="indefinite"/>
  </ellipse>

  <circle cx="320" cy="70" r="7" fill="#38bdf8">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="1.6s" repeatCount="indefinite"/>
  </circle>
  <line x1="320" y1="77" x2="320" y2="95" stroke="#5b6aa8" stroke-width="3"/>

  <rect x="260" y="95" width="120" height="95" rx="28" fill="url(#head)"/>
  <rect x="276" y="115" width="88" height="52" rx="18" fill="#0a0e27"/>
  <g>
    <path d="M292 142 Q301 130 310 142" stroke="#38bdf8" stroke-width="5" fill="none" stroke-linecap="round"/>
    <path d="M330 142 Q339 130 348 142" stroke="#38bdf8" stroke-width="5" fill="none" stroke-linecap="round"/>
    <animateTransform attributeName="transform" type="scale" additive="sum"
      values="1,1;1,1;1,0.15;1,1;1,1" keyTimes="0;0.85;0.9;0.95;1"
      dur="4s" repeatCount="indefinite"/>
  </g>

  <rect x="272" y="185" width="96" height="78" rx="18" fill="url(#body)"/>
  <circle cx="320" cy="215" r="15" fill="#0a0e27"/>
  <path d="M320 205 a10 10 0 1 0 0.1 0" fill="none" stroke="#38bdf8" stroke-width="2"/>
  <path d="M312 218 q8 9 16 0" fill="none" stroke="#38bdf8" stroke-width="2"/>

  <g>
    <rect x="242" y="230" width="16" height="55" rx="8" fill="#aab4d4" transform-origin="250 235"/>
    <animateTransform xlink:href="#armL" attributeName="transform" type="rotate" values="0 250 235;-12 250 235;0 250 235" dur="0.9s" repeatCount="indefinite"/>
  </g>
  <rect x="382" y="230" width="16" height="55" rx="8" fill="#aab4d4"/>

  <rect x="290" y="255" width="24" height="40" rx="8" fill="#0f1533"/>
  <rect x="326" y="255" width="24" height="40" rx="8" fill="#0f1533"/>

  <rect x="225" y="300" width="190" height="14" rx="5" fill="#1b2450"/>
  <rect x="235" y="240" width="170" height="62" rx="8" fill="#050814" stroke="#3b82f6" stroke-width="2"/>
  <rect x="235" y="240" width="170" height="10" rx="4" fill="#141b3d"/>

  <g font-family="monospace" font-size="9" fill="#38bdf8">
    <text x="245" y="262">
      &lt;Robot dev="Amit"&gt;
      <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.1;0.7;1" dur="4s" repeatCount="indefinite"/>
    </text>
    <text x="245" y="274">
      &nbsp;&nbsp;build();
      <animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;0.25;0.35;0.75;1" dur="4s" repeatCount="indefinite"/>
    </text>
    <text x="245" y="286">
      &lt;/Robot&gt;
      <animate attributeName="opacity" values="0;0;0;1;1;0" keyTimes="0;0.5;0.6;0.7;0.9;1" dur="4s" repeatCount="indefinite"/>
    </text>
    <rect x="245" y="288" width="6" height="9" fill="#38bdf8">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
  </g>

  <g font-family="monospace" font-weight="bold" opacity="0.85">
    <text x="120" y="330" fill="#60a5fa" font-size="18">&lt;/&gt;
      <animateTransform attributeName="transform" type="translate" values="0 0;0 -18;0 0" dur="3.4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.9;0" dur="3.4s" repeatCount="indefinite"/>
    </text>
    <text x="475" y="345" fill="#a78bfa" font-size="18">{ AI }
      <animateTransform attributeName="transform" type="translate" values="0 0;0 -18;0 0" dur="3.8s" begin="0.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.9;0" dur="3.8s" begin="0.6s" repeatCount="indefinite"/>
    </text>
    <text x="500" y="300" fill="#34d399" font-size="16">git✓
      <animateTransform attributeName="transform" type="translate" values="0 0;0 -14;0 0" dur="3s" begin="1.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.9;0" dur="3s" begin="1.2s" repeatCount="indefinite"/>
    </text>
  </g>

  <text x="320" y="405" text-anchor="middle" font-family="monospace" font-size="14" fill="#8b93c9">
    unit_amit_kumar.compile()
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2.4s" repeatCount="indefinite"/>
  </text>
</svg>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=42&duration=3000&pause=800&color=60A5FA&center=true&vCenter=true&width=900&height=70&lines=AMIT+KUMAR;%F0%9F%A4%96+ROBOTIC+FULL-STACK+DEVELOPER" alt="Amit Kumar" />

![Visitors](https://komarev.com/ghpvc/?username=AmitKumar&label=UNITS+SCANNED&color=3B82F6&style=for-the-badge&labelColor=0a0e27)
![Status](https://img.shields.io/badge/STATUS-ONLINE-38BDF8?style=for-the-badge&labelColor=0a0e27)

</div>

---

<div align="center">

### 🤖 About Me

Hi, I'm **Amit Kumar** — a full-stack developer who builds MERN + AI-powered
systems and ships them to the cloud. I love turning ideas into working
products, learning new tech as fast as it ships, and writing code that
both humans and machines can read.

<table>
<tr>
<td align="center" width="25%">💻<br/><b>MERN + AI</b><br/><sub>Core Stack</sub></td>
<td align="center" width="25%">📍<br/><b>Madhya Pradesh</b><br/><sub>India</sub></td>
<td align="center" width="25%">🎓<br/><b>Always Learning</b><br/><sub>Next.js · AWS · TS</sub></td>
<td align="center" width="25%">❤️<br/><b>Problem Solver</b><br/><sub>Real-time Solutions</sub></td>
</tr>
</table>

— *Keep Coding* 🚀

</div>

---

### `>> COMMS CHANNELS`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-CONNECT-38BDF8?style=for-the-badge&logo=linkedin&logoColor=0a0e27&labelColor=0a0e27)](https://linkedin.com/in/amit-kumar-814263335)
[![Gmail](https://img.shields.io/badge/GMAIL-TRANSMIT-60A5FA?style=for-the-badge&logo=gmail&logoColor=0a0e27&labelColor=0a0e27)](mailto:kumaramitbth2005@gmail.com)
[![Mastodon](https://img.shields.io/badge/MASTODON-SIGNAL-38BDF8?style=for-the-badge&logo=mastodon&logoColor=0a0e27&labelColor=0a0e27)](https://mastodon.social/@AMIT2005KUMAR)
[![GitHub](https://img.shields.io/badge/GITHUB-SOURCE-60A5FA?style=for-the-badge&logo=github&logoColor=0a0e27&labelColor=0a0e27)](https://github.com/AmitKumar)

</div>

---

### `>> CORE MODULES`

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-0a0e27?style=for-the-badge&logo=javascript&logoColor=FFD400)
![TypeScript](https://img.shields.io/badge/TypeScript-0a0e27?style=for-the-badge&logo=typescript&logoColor=38BDF8)
![Python](https://img.shields.io/badge/Python-0a0e27?style=for-the-badge&logo=python&logoColor=38BDF8)
![Java](https://img.shields.io/badge/Java-0a0e27?style=for-the-badge&logo=openjdk&logoColor=FFD400)
![React](https://img.shields.io/badge/React-0a0e27?style=for-the-badge&logo=react&logoColor=60A5FA)
![Next.js](https://img.shields.io/badge/Next.js-0a0e27?style=for-the-badge&logo=nextdotjs&logoColor=38BDF8)
![Node.js](https://img.shields.io/badge/Node.js-0a0e27?style=for-the-badge&logo=nodedotjs&logoColor=38BDF8)
![Express](https://img.shields.io/badge/Express.js-0a0e27?style=for-the-badge&logo=express&logoColor=FFD400)
![MongoDB](https://img.shields.io/badge/MongoDB-0a0e27?style=for-the-badge&logo=mongodb&logoColor=38BDF8)
![AWS](https://img.shields.io/badge/AWS-0a0e27?style=for-the-badge&logo=amazonaws&logoColor=60A5FA)
![Git](https://img.shields.io/badge/Git-0a0e27?style=for-the-badge&logo=git&logoColor=FFD400)

</div>

---

### `>> TELEMETRY`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AmitKumar&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&title_color=38BDF8&icon_color=60A5FA&text_color=c9c9ff&bg_color=0a0e27&border_radius=12" height="180"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmitKumar&layout=compact&hide_border=true&title_color=38BDF8&text_color=c9c9ff&bg_color=0a0e27&border_radius=12" height="180"/>

<img src="https://streak-stats.demolab.com/?user=AmitKumar&hide_border=true&background=0a0e27&ring=60A5FA&fire=38BDF8&currStreakLabel=38BDF8&sideLabels=c9c9ff&dates=6b6b9a&border_radius=12" height="180"/>

</div>

---

<div align="center">

`> UNIT AMIT_KUMAR AWAITING NEXT COMMAND...  █`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1b2450,50:141b3d,100:0a0e27&height=110&section=footer"/>

</div>

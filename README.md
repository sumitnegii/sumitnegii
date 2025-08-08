<!-- Animated Banner -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&center=true&vCenter=true&width=900&height=70&lines=Hey+there!+I'm+Sumit+Singh;MCA+Student;Problem+Solver;Cloud+%26+ML+Enthusiast;DSA+%26+Competitive+Programmer;Always+Learning+Something+New" alt="Typing SVG" />
</p>


<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg"
     xmlns:xlink="http://www.w3.org/1999/xlink"
     width="1200" height="300" viewBox="0 0 1200 300" role="img" aria-label="Sumit Singh banner">
  <defs>
    <!-- Gradient -->
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0" stop-color="#36BCF7"/>
      <stop offset="1" stop-color="#6C63FF"/>
    </linearGradient>

    <!-- Soft inner gradient -->
    <linearGradient id="g2" x1="0" x2="1">
      <stop offset="0" stop-color="rgba(255,255,255,0.06)"/>
      <stop offset="1" stop-color="rgba(255,255,255,0)"/>
    </linearGradient>

    <!-- Mask for typing reveal -->
    <mask id="revealMask">
      <!-- white shows visible area in mask -->
      <rect id="maskRect" x="350" y="165" width="0" height="36" fill="white" rx="3" />
    </mask>

    <!-- Fonts fallback: GitHub will use system fonts -->
  </defs>

  <!-- background rounded card -->
  <rect x="10" y="10" width="1180" height="280" rx="18" fill="url(#g1)" />
  <!-- subtle overlay for depth -->
  <rect x="10" y="10" width="1180" height="280" rx="18" fill="url(#g2)" />

  <!-- left circle with initials -->
  <g transform="translate(40,55)">
    <circle cx="80" cy="80" r="80" fill="#ffffff10" stroke="white" stroke-opacity="0.12" />
    <text x="80" y="100" font-family="Verdana, Arial, sans-serif" font-size="44" text-anchor="middle" fill="white" fill-opacity="0.95" font-weight="700">SS</text>
  </g>

  <!-- Name and subtitle -->
  <text x="320" y="100" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif" font-size="40" fill="white" font-weight="700" letter-spacing="0.5">
    Sumit <tspan fill="#FFD166">Singh</tspan>
  </text>

  <text x="320" y="142" font-family="Inter, Roboto, Helvetica, Arial, sans-serif" font-size="18" fill="white" fill-opacity="0.9">
    MCA Student • Problem Solver • Cloud & ML Enthusiast
  </text>

  <!-- Typing box (static rounded rectangle background) -->
  <g transform="translate(320,160)">
    <rect x="0" y="0" width="760" height="64" rx="10" fill="rgba(255,255,255,0.06)" stroke="rgba(255,255,255,0.06)" />
    <!-- left small indicator dot -->
    <circle cx="22" cy="32" r="6" fill="#36BCF7" />
  </g>

  <!-- Phrases to reveal using mask -->
  <g mask="url(#revealMask)">
    <text x="360" y="190" font-family="Courier New, monospace" font-size="20" fill="white" font-weight="600">
      <tspan id="p1">MCA Student</tspan>
    </text>
  </g>

  <g mask="url(#revealMask)">
    <text x="360" y="190" font-family="Courier New, monospace" font-size="20" fill="white" font-weight="600">
      <tspan id="p2">Problem Solver</tspan>
    </text>
  </g>

  <g mask="url(#revealMask)">
    <text x="360" y="190" font-family="Courier New, monospace" font-size="20" fill="white" font-weight="600">
      <tspan id="p3">DSA & Competitive Programmer</tspan>
    </text>
  </g>

  <!-- Typing cursor -->
  <rect id="cursor" x="360" y="162" width="3" height="28" rx="1" fill="white">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" />
  </rect>

  <!-- SMIL animations to expand & collapse the mask rect to reveal phrases sequentially -->
  <!-- timings: reveal 1 (2.2s), hold (1.4s), collapse (0.3s) => ~3.9s per phrase -->
  <!-- total cycle ~11.7s (repeat indefinitely) -->

  <!-- Phrase 1 reveal -->
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="0" to="420"
           begin="0s" dur="1.8s"
           fill="freeze" />
  <!-- Phrase 1 hold then collapse -->
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="420" to="420"
           begin="1.8s" dur="1.4s"
           fill="freeze" />
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="420" to="0"
           begin="3.2s" dur="0.4s"
           fill="freeze" />

  <!-- Phrase 2 reveal (begin after phrase1 collapsed) -->
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="0" to="420"
           begin="3.6s" dur="1.8s"
           fill="freeze" />
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="420" to="420"
           begin="5.4s" dur="1.4s"
           fill="freeze" />
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="420" to="0"
           begin="6.8s" dur="0.4s"
           fill="freeze" />

  <!-- Phrase 3 reveal -->
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="0" to="520"
           begin="7.2s" dur="1.8s"
           fill="freeze" />
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="520" to="520"
           begin="9.0s" dur="1.6s"
           fill="freeze" />
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="520" to="0"
           begin="10.6s" dur="0.4s"
           fill="freeze" />

  <!-- Loop control: restart cycle by resetting to initial state -->
  <!-- We add a final animate that begins at end of cycle to set width=0 and restart -->
  <animate xlink:href="#maskRect"
           attributeName="width"
           from="0" to="0"
           begin="11.0s" dur="0.01s"
           fill="freeze" />

  <!-- Slight entrance animation for the whole svg when first loaded -->
  <g>
    <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" begin="0s" dur="0.8s" fill="freeze" />
  </g>

  <!-- small footer tagline -->
  <text x="320" y="235" font-family="Inter, Roboto, Helvetica, Arial, sans-serif" font-size="13" fill="white" fill-opacity="0.75">
    ⚡ Code is like humor — when you have to explain it, it's bad.
  </text>
</svg>


<!-- Glitch Banner -->
<p align="center">
  <img src="https://svg-banners.vercel.app/api?type=glitch&text1=Sumit%20Singh&width=900&height=200" alt="Glitch Banner" />
</p>

<!-- Social Links -->
<p align="center">
  <a href="mailto:negisumit308@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/sumitnegi"><img src="https://img.shields.io/badge/LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/sumitnegii"><img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

## 🚀 About Me
- 🎓 MCA student at **Graphic Era Deemed University** *(2024–2026)*
- 💼 Spent 3 years at Afcons Infrastructure Ltd handling IT & payroll (SAP wizardry included)
- 🧠 Into **Problem Solving, DSA, Competitive Programming**
- 🌱 Currently deep-diving into **Cloud Computing & Machine Learning**
- ☕ Runs on coffee and curiosity (in that order)

---

## 🛠 Skills
<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,python,java,mysql,firebase,aws,gcp,docker,git" />
</p>

---

## 📚 Education
- **Master of Computer Applications (MCA)** – Graphic Era Deemed University *(2024–2026)*
- **B.Sc. in Information Technology** – HNB Garhwal University *(2017–2020)*

---

## 💼 Work Experience
**Afcons Infrastructure Ltd, Delhi** *(Nov 2021 – May 2024)*  
- Managed IT & payroll processes using SAP  
- Optimized onboarding workflows with TCS iON + SAP

---

## 🚀 Projects

### 🆘 Crowdsourced Emergency Response Platform *(70% Complete)*
- Real-time geolocation alerts using MERN + Firebase  
- Reduced notification latency by **40%** with WebSocket optimizations

### 👤 Face Recognition System
- Achieved **95% accuracy** using TensorFlow.js + face-api.js  
- Added multi-factor authentication for extra security

### 🏋️ Hetvik The Gym – Website
- Responsive site hosted on Firebase with secure login  
- SEO score 90+ on Lighthouse

---

## 📜 Certifications
- Python – Udemy  
- Google Data Analytics – Coursera  
- Management Excellence – LinkedIn  
- CRM – Great Learning  

---

## 📊 GitHub & LeetCode Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sumitnegii&show_icons=true&theme=react" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sumitnegii&theme=react" />
</p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/sumit_negi02?theme=light&font=Roboto&ext=contest" />
</p>

---

## 📈 Contribution Graph
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sumitnegii&theme=react-dark&bg_color=20232a&hide_border=true" />
</p>

---

<p align="center">
  <i>⚡ "Code is like humor. When you have to explain it, it’s bad." ⚡</i>
</p>

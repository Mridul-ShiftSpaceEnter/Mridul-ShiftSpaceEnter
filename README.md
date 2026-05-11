<div align="center">

<!--
╔══════════════════════════════════════════════════════════════════╗
║   MRIDUL SINGH — GitHub Profile README                          ║
║   Style: Mario-inspired road scene + animated SVG               ║
╚══════════════════════════════════════════════════════════════════╝
-->

<!-- ═══════════════════════════════════════════════════════ -->
<!--                    ANIMATED HERO                         -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="860" height="320" viewBox="0 0 860 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Sky gradient -->
    <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#050d1a"/>
      <stop offset="100%" stop-color="#0d2137"/>
    </linearGradient>
    <!-- Ground gradient -->
    <linearGradient id="grd" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#2d6a2d"/>
      <stop offset="100%" stop-color="#1a4a1a"/>
    </linearGradient>
    <!-- Road gradient -->
    <linearGradient id="roadgrd" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#3a3a3a"/>
      <stop offset="100%" stop-color="#252525"/>
    </linearGradient>
    <!-- Cyan glow for text -->
    <filter id="cglow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Clip path for road dashes -->
    <clipPath id="roadclip">
      <rect x="0" y="264" width="860" height="56"/>
    </clipPath>
  </defs>

  <!-- Sky -->
  <rect width="860" height="320" fill="url(#sky)"/>

  <!-- Stars (static + blinking via animate) -->
  <g fill="white" opacity="0.9">
    <circle cx="42"  cy="18"  r="1.2"><animate attributeName="opacity" values="0.3;1;0.3" dur="2.1s" repeatCount="indefinite"/></circle>
    <circle cx="120" cy="35"  r="1"  ><animate attributeName="opacity" values="1;0.2;1"   dur="1.7s" repeatCount="indefinite"/></circle>
    <circle cx="195" cy="14"  r="1.5"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" repeatCount="indefinite"/></circle>
    <circle cx="260" cy="28"  r="1"  ><animate attributeName="opacity" values="1;0.3;1"   dur="1.9s" repeatCount="indefinite"/></circle>
    <circle cx="340" cy="12"  r="1.2"><animate attributeName="opacity" values="0.4;1;0.4" dur="2.8s" repeatCount="indefinite"/></circle>
    <circle cx="430" cy="22"  r="1"  ><animate attributeName="opacity" values="1;0.2;1"   dur="1.5s" repeatCount="indefinite"/></circle>
    <circle cx="510" cy="9"   r="1.5"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.2s" repeatCount="indefinite"/></circle>
    <circle cx="590" cy="31"  r="1"  ><animate attributeName="opacity" values="0.3;1;0.3" dur="3.0s" repeatCount="indefinite"/></circle>
    <circle cx="670" cy="16"  r="1.2"><animate attributeName="opacity" values="1;0.4;1"   dur="1.8s" repeatCount="indefinite"/></circle>
    <circle cx="760" cy="26"  r="1"  ><animate attributeName="opacity" values="0.5;1;0.5" dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="820" cy="10"  r="1.5"><animate attributeName="opacity" values="1;0.3;1"   dur="2.0s" repeatCount="indefinite"/></circle>
    <circle cx="78"  cy="52"  r="1"  ><animate attributeName="opacity" values="0.7;0.2;0.7" dur="2.3s" repeatCount="indefinite"/></circle>
    <circle cx="165" cy="60"  r="1.2"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.6s" repeatCount="indefinite"/></circle>
    <circle cx="305" cy="48"  r="1"  ><animate attributeName="opacity" values="1;0.5;1"   dur="2.7s" repeatCount="indefinite"/></circle>
    <circle cx="455" cy="55"  r="1.5"><animate attributeName="opacity" values="0.4;1;0.4" dur="1.9s" repeatCount="indefinite"/></circle>
    <circle cx="630" cy="44"  r="1"  ><animate attributeName="opacity" values="1;0.2;1"   dur="2.1s" repeatCount="indefinite"/></circle>
    <circle cx="740" cy="58"  r="1.2"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.4s" repeatCount="indefinite"/></circle>
  </g>

  <!-- Moon -->
  <circle cx="790" cy="48" r="22" fill="#fffde0" opacity="0.9"/>
  <circle cx="802" cy="40" r="18" fill="#0d1f35"/>

  <!-- Mountains back -->
  <polygon points="0,230 90,130 180,230"   fill="#1a3d1a" opacity="0.8"/>
  <polygon points="60,230 170,110 280,230"  fill="#1e4a1e"/>
  <polygon points="200,230 310,95 420,230"  fill="#1a3d1a" opacity="0.9"/>
  <polygon points="350,230 460,120 570,230" fill="#1e4a1e"/>
  <polygon points="500,230 610,100 720,230" fill="#1a3d1a" opacity="0.8"/>
  <polygon points="680,230 790,115 860,200 860,230" fill="#1e4a1e"/>
  <!-- Mountain snow caps -->
  <polygon points="310,95 325,115 295,115"  fill="white" opacity="0.6"/>
  <polygon points="460,120 474,138 446,138" fill="white" opacity="0.5"/>
  <polygon points="610,100 625,120 595,120" fill="white" opacity="0.6"/>

  <!-- Ground -->
  <rect x="0" y="230" width="860" height="34" fill="url(#grd)"/>
  <!-- Ground top edge -->
  <rect x="0" y="230" width="860" height="3" fill="#4a9a4a"/>

  <!-- Trees -->
  <!-- Tree 1 -->
  <rect x="30"  y="218" width="8" height="16" fill="#5c3d1e"/>
  <polygon points="18,218 34,192 50,218"  fill="#2a7a2a"/>
  <polygon points="22,204 34,184 46,204"  fill="#3a9a3a"/>
  <!-- Tree 2 -->
  <rect x="110" y="216" width="8" height="18" fill="#5c3d1e"/>
  <polygon points="98,216 114,188 130,216" fill="#2a7a2a"/>
  <polygon points="102,202 114,180 126,202" fill="#3a9a3a"/>
  <!-- Tree 3 -->
  <rect x="218" y="218" width="8" height="16" fill="#5c3d1e"/>
  <polygon points="206,218 222,194 238,218" fill="#2a7a2a"/>
  <polygon points="210,206 222,186 234,206" fill="#3a9a3a"/>
  <!-- Tree 4 -->
  <rect x="370" y="215" width="8" height="19" fill="#5c3d1e"/>
  <polygon points="358,215 374,187 390,215" fill="#2a7a2a"/>
  <polygon points="362,201 374,179 386,201" fill="#3a9a3a"/>
  <!-- Tree 5 -->
  <rect x="560" y="218" width="8" height="16" fill="#5c3d1e"/>
  <polygon points="548,218 564,192 580,218" fill="#2a7a2a"/>
  <polygon points="552,204 564,184 576,204" fill="#3a9a3a"/>
  <!-- Tree 6 -->
  <rect x="720" y="216" width="8" height="18" fill="#5c3d1e"/>
  <polygon points="708,216 724,188 740,216" fill="#2a7a2a"/>
  <polygon points="712,202 724,180 736,202" fill="#3a9a3a"/>
  <!-- Tree 7 -->
  <rect x="820" y="218" width="8" height="16" fill="#5c3d1e"/>
  <polygon points="808,218 824,194 840,218" fill="#2a7a2a"/>
  <polygon points="812,206 824,186 836,206" fill="#3a9a3a"/>

  <!-- ─── Road ─── -->
  <rect x="0" y="264" width="860" height="56" fill="url(#roadgrd)"/>
  <rect x="0" y="264" width="860" height="3" fill="#555"/>

  <!-- Animated road dashes -->
  <g clip-path="url(#roadclip)">
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="0" to="-80" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="80" to="0" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="160" to="80" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="240" to="160" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="320" to="240" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="400" to="320" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="480" to="400" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="560" to="480" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="640" to="560" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="720" to="640" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="800" to="720" dur="0.55s" repeatCount="indefinite"/>
    </rect>
    <rect y="288" height="4" rx="2" fill="#ffff00" opacity="0.85" width="55">
      <animate attributeName="x" from="880" to="800" dur="0.55s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- ─── Animated Car ─── -->
  <g>
    <animateTransform attributeName="transform" type="translate" from="-120,0" to="980,0" dur="6s" repeatCount="indefinite"/>
    <!-- exhaust puffs -->
    <ellipse cx="-6" cy="300" rx="5" ry="3" fill="white" opacity="0.35">
      <animate attributeName="rx" values="5;10;5" dur="0.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.35;0;0.35" dur="0.5s" repeatCount="indefinite"/>
    </ellipse>
    <!-- car body -->
    <rect x="10" y="274" width="88" height="28" rx="6" fill="#00d2ff" stroke="#0099bb" stroke-width="2"/>
    <!-- car roof -->
    <rect x="24" y="258" width="52" height="18" rx="7" fill="#00b8e0" stroke="#0099bb" stroke-width="1.5"/>
    <!-- windscreen -->
    <rect x="28" y="261" width="36" height="12" rx="3" fill="rgba(200,240,255,0.75)"/>
    <!-- headlight -->
    <circle cx="98" cy="285" r="4" fill="#ffffa0" opacity="0.9"/>
    <!-- wheel L -->
    <circle cx="26" cy="302" r="10" fill="#1a1a1a" stroke="#888" stroke-width="3"/>
    <circle cx="26" cy="302" r="4"  fill="#555"/>
    <!-- wheel R -->
    <circle cx="82" cy="302" r="10" fill="#1a1a1a" stroke="#888" stroke-width="3"/>
    <circle cx="82" cy="302" r="4"  fill="#555"/>
  </g>

  <!-- ─── Question Blocks ─── -->
  <!-- Block 1 -->
  <g>
    <rect x="170" y="138" width="30" height="30" rx="4" fill="#e8a020" stroke="#8b5e00" stroke-width="2.5"/>
    <rect x="172" y="140" width="26" height="5"  rx="1" fill="#ffd060" opacity="0.6"/>
    <rect x="172" y="140" width="5"  height="26" rx="1" fill="#ffd060" opacity="0.6"/>
    <text x="185" y="160" text-anchor="middle" font-size="16" font-weight="900" fill="#8b5e00" font-family="monospace">?</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="1.2s" repeatCount="indefinite"/>
  </g>
  <!-- Block 2 -->
  <g>
    <rect x="410" y="118" width="30" height="30" rx="4" fill="#e8a020" stroke="#8b5e00" stroke-width="2.5"/>
    <rect x="412" y="120" width="26" height="5"  rx="1" fill="#ffd060" opacity="0.6"/>
    <rect x="412" y="120" width="5"  height="26" rx="1" fill="#ffd060" opacity="0.6"/>
    <text x="425" y="140" text-anchor="middle" font-size="16" font-weight="900" fill="#8b5e00" font-family="monospace">?</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-4;0,0" dur="1.5s" repeatCount="indefinite"/>
  </g>
  <!-- Block 3 -->
  <g>
    <rect x="650" y="130" width="30" height="30" rx="4" fill="#e8a020" stroke="#8b5e00" stroke-width="2.5"/>
    <rect x="652" y="132" width="26" height="5"  rx="1" fill="#ffd060" opacity="0.6"/>
    <rect x="652" y="132" width="5"  height="26" rx="1" fill="#ffd060" opacity="0.6"/>
    <text x="665" y="152" text-anchor="middle" font-size="16" font-weight="900" fill="#8b5e00" font-family="monospace">?</text>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="1.0s" repeatCount="indefinite"/>
  </g>

  <!-- ─── HUD overlays ─── -->
  <!-- Score top-left -->
  <text x="18" y="22" font-family="monospace" font-size="12" fill="#ffffff" opacity="0.9">SCORE</text>
  <text x="18" y="38" font-family="monospace" font-size="14" font-weight="700" fill="#00d2ff">000000</text>
  <!-- Coins top-right -->
  <text x="750" y="22" font-family="monospace" font-size="12" fill="#ffffff" opacity="0.9">🪙 x00</text>
  <text x="750" y="38" font-family="monospace" font-size="12" fill="#ffff66">LEVEL  01</text>

  <!-- ─── Hero Name ─── -->
  <text x="430" y="88" text-anchor="middle" font-family="monospace" font-size="30" font-weight="700"
    fill="white" filter="url(#cglow)" letter-spacing="4">MRIDUL SINGH</text>
  <text x="430" y="112" text-anchor="middle" font-family="monospace" font-size="13"
    fill="#00d2ff" letter-spacing="2">AI &amp; AUTOMATION ENGINEER  ·  B.TECH CS</text>
  <text x="430" y="132" text-anchor="middle" font-family="monospace" font-size="11"
    fill="#88ccdd" letter-spacing="1">YOLOv8  ·  LLM Agents  ·  n8n  ·  Real-Time Vision</text>
</svg>

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   SCROLLING TICKER                       -->
<!-- ═══════════════════════════════════════════════════════ -->

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=13&duration=1&pause=1&color=00D2FF&center=true&vCenter=true&repeat=true&width=860&lines=🚗+MRIDUL+SINGH+·+AI+%2B+AUTOMATION+·+YOLOv8+·+LLM+AGENTS+·+n8n+·+60%25+EFFORT+SAVED+·+300%25+ENGAGEMENT+·+CISCO+CERTIFIED+·+MATH+OLYMPIAD+%232+·+BUILDING+SYSTEMS+THAT+THINK,+SEE,+AND+ACT" alt="ticker"/>

</div>

---

## `whoami`

```python
class MridulSingh:
    role        = "AI & Automation Engineer"
    degree      = "B.Tech Computer Science"
    stack       = ["Python", "YOLOv8", "LLMs", "n8n", "SQL", "Tableau"]
    interests   = ["Generative AI", "Computer Vision", "LLM Agents", "Cinema"]
    currently   = "Architecting AI agents that reduce human effort at scale"

    def life_philosophy(self):
        return "Work on things that matter — even if they're outside your lane."
```

---

## ⚡ Mission Stack

| Status | Project |
|:------:|:--------|
| 🟢 **Active** | AI Agent workflows — LLM-driven automation pipelines via n8n |
| 🟢 **Active** | [Real-Time Scene Perception System](https://github.com/Mridul-ShiftSpaceEnter/Real-Time-Scene-Perception-System) — YOLOv8 + spatial audio feedback |
| 🔵 **Researching** | Multimodal LLM integration for vision + language tasks |
| 🟡 **Exploring** | AI × Cybersecurity overlap (post-Cisco certification) |

---

## 🧠 Tech Stack

<!-- ── ANIMATED TECH ROAD ── -->
<div align="center">

<svg width="860" height="72" viewBox="0 0 860 72" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <clipPath id="tc"><rect width="860" height="72"/></clipPath>
  </defs>
  <!-- Road bg -->
  <rect width="860" height="72" rx="10" fill="#1a1a2e"/>
  <rect y="44" width="860" height="28" fill="#2a2a2a"/>
  <rect y="44" width="860" height="3"  fill="#444"/>
  <!-- Dashes -->
  <g clip-path="url(#tc)">
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="0" to="-60" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="60" to="0" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="120" to="60" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="180" to="120" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="240" to="180" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="300" to="240" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="360" to="300" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="420" to="360" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="480" to="420" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="540" to="480" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="600" to="540" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="660" to="600" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="720" to="660" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="780" to="720" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="840" to="780" dur="0.4s" repeatCount="indefinite"/>
    </rect>
    <rect y="55" height="3" rx="1" fill="#ffff00" opacity="0.7" width="40">
      <animate attributeName="x" from="900" to="840" dur="0.4s" repeatCount="indefinite"/>
    </rect>
  </g>
  <!-- Scrolling tech labels -->
  <g clip-path="url(#tc)">
    <g font-family="monospace" font-size="12" font-weight="600">
      <g fill="#FFD43B">
        <rect rx="10" height="22" y="10" opacity="0.15">
          <animate attributeName="x" from="20"   to="-1700" dur="18s" repeatCount="indefinite"/>
          <animate attributeName="width" values="60;60" dur="18s" repeatCount="indefinite"/>
        </rect>
        <text y="26"><tspan><animate attributeName="x" from="34"   to="-1686" dur="18s" repeatCount="indefinite"/>Python</tspan></text>
      </g>
      <g fill="#00FFAB">
        <text y="26"><tspan><animate attributeName="x" from="114"  to="-1606" dur="18s" repeatCount="indefinite"/>YOLOv8</tspan></text>
      </g>
      <g fill="#7BAFD4">
        <text y="26"><tspan><animate attributeName="x" from="200"  to="-1520" dur="18s" repeatCount="indefinite"/>OpenCV</tspan></text>
      </g>
      <g fill="#EA4B71">
        <text y="26"><tspan><animate attributeName="x" from="284"  to="-1436" dur="18s" repeatCount="indefinite"/>n8n</tspan></text>
      </g>
      <g fill="#B39DDB">
        <text y="26"><tspan><animate attributeName="x" from="346"  to="-1374" dur="18s" repeatCount="indefinite"/>GPT-4</tspan></text>
      </g>
      <g fill="#CC785C">
        <text y="26"><tspan><animate attributeName="x" from="426"  to="-1294" dur="18s" repeatCount="indefinite"/>Claude</tspan></text>
      </g>
      <g fill="#4DABF7">
        <text y="26"><tspan><animate attributeName="x" from="508"  to="-1212" dur="18s" repeatCount="indefinite"/>Pandas</tspan></text>
      </g>
      <g fill="#74C0FC">
        <text y="26"><tspan><animate attributeName="x" from="592"  to="-1128" dur="18s" repeatCount="indefinite"/>NumPy</tspan></text>
      </g>
      <g fill="#63E6BE">
        <text y="26"><tspan><animate attributeName="x" from="670"  to="-1050" dur="18s" repeatCount="indefinite"/>SQL</tspan></text>
      </g>
      <g fill="#E97627">
        <text y="26"><tspan><animate attributeName="x" from="730"  to="-990"  dur="18s" repeatCount="indefinite"/>Tableau</tspan></text>
      </g>
      <g fill="#FF8C42">
        <text y="26"><tspan><animate attributeName="x" from="820"  to="-900"  dur="18s" repeatCount="indefinite"/>Java</tspan></text>
      </g>
      <g fill="#A5D8FF">
        <text y="26"><tspan><animate attributeName="x" from="880"  to="-840"  dur="18s" repeatCount="indefinite"/>Matplotlib</tspan></text>
      </g>
      <!-- repeat loop -->
      <g fill="#FFD43B">
        <text y="26"><tspan><animate attributeName="x" from="990"  to="-730"  dur="18s" repeatCount="indefinite"/>Python</tspan></text>
      </g>
      <g fill="#00FFAB">
        <text y="26"><tspan><animate attributeName="x" from="1070" to="-650"  dur="18s" repeatCount="indefinite"/>YOLOv8</tspan></text>
      </g>
      <g fill="#7BAFD4">
        <text y="26"><tspan><animate attributeName="x" from="1156" to="-564"  dur="18s" repeatCount="indefinite"/>OpenCV</tspan></text>
      </g>
      <g fill="#EA4B71">
        <text y="26"><tspan><animate attributeName="x" from="1240" to="-480"  dur="18s" repeatCount="indefinite"/>n8n</tspan></text>
      </g>
      <g fill="#B39DDB">
        <text y="26"><tspan><animate attributeName="x" from="1302" to="-418"  dur="18s" repeatCount="indefinite"/>GPT-4</tspan></text>
      </g>
      <g fill="#CC785C">
        <text y="26"><tspan><animate attributeName="x" from="1382" to="-338"  dur="18s" repeatCount="indefinite"/>Claude</tspan></text>
      </g>
      <g fill="#4DABF7">
        <text y="26"><tspan><animate attributeName="x" from="1464" to="-256"  dur="18s" repeatCount="indefinite"/>Pandas</tspan></text>
      </g>
      <g fill="#74C0FC">
        <text y="26"><tspan><animate attributeName="x" from="1548" to="-172"  dur="18s" repeatCount="indefinite"/>NumPy</tspan></text>
      </g>
      <g fill="#63E6BE">
        <text y="26"><tspan><animate attributeName="x" from="1626" to="-94"   dur="18s" repeatCount="indefinite"/>SQL</tspan></text>
      </g>
      <g fill="#E97627">
        <text y="26"><tspan><animate attributeName="x" from="1686" to="-34"   dur="18s" repeatCount="indefinite"/>Tableau</tspan></text>
      </g>
    </g>
  </g>
</svg>

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%">

### 👁️ Real-Time Scene Perception System
> **Final Year Capstone**

Live video → YOLOv8 object detection → spatial mapping → audio feedback for environmental awareness.

**Impact:** Real accessibility use case. Bridges CV and human UX.

![Python](https://img.shields.io/badge/Python-black?style=flat-square&logo=python&logoColor=FFD43B)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFAB?style=flat-square&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=OpenCV&logoColor=white)

[`→ View Repository`](https://github.com/Mridul-ShiftSpaceEnter/Real-Time-Scene-Perception-System)

</td>
<td width="50%">

### 🤖 LLM Automation Engine
> **AI Workflow Architecture**

n8n + LLM pipelines eliminating **60% of manual effort** in content operations. End-to-end: trigger → generate → review → post.

**Impact:** Scalable automation that runs while you sleep.

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![GPT-4](https://img.shields.io/badge/GPT--4-412991?style=flat-square&logo=openai&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-00d2ff?style=flat-square)

</td>
</tr>
<tr>
<td width="50%">

### 📊 KPI Intelligence Dashboards
> **Data Storytelling**

Raw datasets → decision-ready dashboards. Python ETL pipelines feeding Tableau visualizations for stakeholder consumption.

**Impact:** Data-driven decisions, not gut feelings.

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=Tableau&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat-square&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-316192?style=flat-square&logo=postgresql&logoColor=white)

</td>
<td width="50%">

### 🔐 AI × Security Research
> **Cross-Domain Exploration**

Exploring the intersection of LLMs, automation, and cybersecurity post-Cisco Cybersecurity Essentials certification.

**Focus:** How AI changes the threat/defense landscape.

![Security](https://img.shields.io/badge/Cybersecurity-0a0a1a?style=flat-square&logo=cisco&logoColor=1BA0D7)
![Cisco](https://img.shields.io/badge/Cisco_Certified-1BA0D7?style=flat-square&logo=cisco&logoColor=white)

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Mridul-ShiftSpaceEnter&show_icons=true&theme=transparent&hide_border=true&title_color=00d2ff&icon_color=00d2ff&text_color=ffffff&bg_color=0d1117"/>
  &nbsp;
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mridul-ShiftSpaceEnter&layout=compact&theme=transparent&hide_border=true&title_color=00d2ff&text_color=ffffff&bg_color=0d1117"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mridul-ShiftSpaceEnter&theme=transparent&hide_border=true&ring=00d2ff&fire=00d2ff&currStreakLabel=00d2ff&sideLabels=ffffff&currStreakNum=ffffff&sideNums=ffffff&dates=888888"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Mridul-ShiftSpaceEnter&theme=react-dark&hide_border=true&color=00d2ff&line=00d2ff&point=ffffff&area=true&area_color=00d2ff"/>
</div>

---

## 🏆 Achievements Unlocked

<!-- ── ANIMATED ACHIEVEMENTS BANNER ── -->
<div align="center">

<svg width="860" height="180" viewBox="0 0 860 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="ab" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#0a0a1a"/>
      <stop offset="50%"  stop-color="#0d1b2a"/>
      <stop offset="100%" stop-color="#0a0a1a"/>
    </linearGradient>
  </defs>
  <rect width="860" height="180" rx="12" fill="url(#ab)" stroke="#00d2ff" stroke-width="1.5" stroke-opacity="0.4"/>
  <!-- Top border glow line -->
  <rect x="1" y="1" width="858" height="3" rx="2" fill="#00d2ff" opacity="0.6"/>

  <!-- Row 1 -->
  <rect x="20"  y="22" width="400" height="54" rx="8" fill="#ffffff" fill-opacity="0.04" stroke="#ffffff" stroke-opacity="0.08" stroke-width="0.8"/>
  <text x="40"  y="46"  font-family="monospace" font-size="22">🥈</text>
  <text x="74"  y="44"  font-family="monospace" font-size="13" fill="#ffffff">Math Olympiad</text>
  <text x="74"  y="62"  font-family="monospace" font-size="11" fill="#888">District Rank #2</text>
  <text x="370" y="55"  font-family="monospace" font-size="12" fill="#00d2ff" text-anchor="end">+500 XP</text>

  <rect x="440" y="22" width="400" height="54" rx="8" fill="#ffffff" fill-opacity="0.04" stroke="#ffffff" stroke-opacity="0.08" stroke-width="0.8"/>
  <text x="460" y="46"  font-family="monospace" font-size="22">🔒</text>
  <text x="494" y="44"  font-family="monospace" font-size="13" fill="#ffffff">Cisco Cybersecurity</text>
  <text x="494" y="62"  font-family="monospace" font-size="11" fill="#888">Essentials — Certified</text>
  <text x="810" y="55"  font-family="monospace" font-size="12" fill="#00d2ff" text-anchor="end">+300 XP</text>

  <!-- Row 2 -->
  <rect x="20"  y="98" width="400" height="54" rx="8" fill="#ffffff" fill-opacity="0.04" stroke="#ffffff" stroke-opacity="0.08" stroke-width="0.8"/>
  <text x="40"  y="122" font-family="monospace" font-size="22">📈</text>
  <text x="74"  y="120" font-family="monospace" font-size="13" fill="#ffffff">300% Engagement Boost</text>
  <text x="74"  y="138" font-family="monospace" font-size="11" fill="#888">via content strategy</text>
  <text x="370" y="131" font-family="monospace" font-size="12" fill="#00d2ff" text-anchor="end">+400 XP</text>

  <rect x="440" y="98" width="400" height="54" rx="8" fill="#ffffff" fill-opacity="0.04" stroke="#ffffff" stroke-opacity="0.08" stroke-width="0.8"/>
  <text x="460" y="122" font-family="monospace" font-size="22">⚡</text>
  <text x="494" y="120" font-family="monospace" font-size="13" fill="#ffffff">60% Effort Reduction</text>
  <text x="494" y="138" font-family="monospace" font-size="11" fill="#888">via LLM automation workflows</text>
  <text x="810" y="131" font-family="monospace" font-size="12" fill="#00d2ff" text-anchor="end">+600 XP</text>
</svg>

</div>

---

## 🎬 Side Quest: Cinema

I analyze narrative structure the same way I architect systems — looking for the logic beneath the surface.

> *"The best films, like the best systems, hide their complexity."*

→ [`My Film Log on Letterboxd`](https://letterboxd.com/TheCinephile0/) — where I overthink movies so you don't have to.

---

## 🤝 Let's Build Something

<div align="center">

**Open to:** AI × Security cross-domain projects · LLM agent collaborations · Interesting problems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mridul-s-0099232b6/)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mridulsingh654321@gmail.com)
&nbsp;
[![Letterboxd](https://img.shields.io/badge/Letterboxd-FF8000?style=for-the-badge&logo=letterboxd&logoColor=white)](https://letterboxd.com/TheCinephile0/)
&nbsp;
![Views](https://komarev.com/ghpvc/?username=Mridul-ShiftSpaceEnter&style=for-the-badge&color=00d2ff&label=PROFILE+VIEWS)

<br/>

<!-- FOOTER CAR ANIMATION -->
<svg width="860" height="52" viewBox="0 0 860 52" xmlns="http://www.w3.org/2000/svg">
  <rect width="860" height="52" rx="10" fill="#0a0a1a"/>
  <rect y="28" width="860" height="24" fill="#1a1a1a"/>
  <rect y="28" width="860" height="2" fill="#333"/>
  <!-- dashes -->
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="0" to="-50" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="50"  to="0"   dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="100" to="50"  dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="150" to="100" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="200" to="150" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="250" to="200" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="300" to="250" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="350" to="300" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="400" to="350" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="450" to="400" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="500" to="450" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="550" to="500" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="600" to="550" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="650" to="600" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="700" to="650" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="750" to="700" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="800" to="750" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <rect y="37" height="2" rx="1" fill="#ffff00" opacity="0.6" width="34">
    <animate attributeName="x" from="850" to="800" dur="0.4s" repeatCount="indefinite"/>
  </rect>
  <!-- mini car -->
  <g>
    <animateTransform attributeName="transform" type="translate" from="-80,0" to="940,0" dur="5s" repeatCount="indefinite"/>
    <rect x="0"  y="30" width="60" height="18" rx="4" fill="#00d2ff" stroke="#0088aa" stroke-width="1.5"/>
    <rect x="10" y="20" width="34" height="12" rx="4" fill="#00b8e0" stroke="#0088aa" stroke-width="1"/>
    <circle cx="14" cy="48" r="6" fill="#111" stroke="#777" stroke-width="2"/>
    <circle cx="46" cy="48" r="6" fill="#111" stroke="#777" stroke-width="2"/>
    <circle cx="60" cy="37" r="2.5" fill="#ffffa0" opacity="0.9"/>
  </g>
  <!-- text -->
  <text x="430" y="20" text-anchor="middle" font-family="monospace" font-size="12" fill="#00d2ff" letter-spacing="1">&gt; the terminal is always open _</text>
</svg>

</div>

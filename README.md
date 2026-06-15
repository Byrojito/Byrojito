<div align="center">

<!-- Custom SVG animated header - always loads, no external dependency -->
<svg width="800" height="160" viewBox="0 0 800 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0D1117"/>
      <stop offset="100%" style="stop-color:#161B22"/>
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#A78BFA">
        <animate attributeName="stop-color" values="#A78BFA;#60A5FA;#34D399;#A78BFA" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#60A5FA">
        <animate attributeName="stop-color" values="#60A5FA;#34D399;#A78BFA;#60A5FA" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#A78BFA;stop-opacity:0.8"/>
      <stop offset="50%" style="stop-color:#60A5FA;stop-opacity:0.6"/>
      <stop offset="100%" style="stop-color:#34D399;stop-opacity:0.8"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="800" height="160" fill="url(#bg)" rx="12"/>

  <!-- Animated wave bottom -->
  <path d="M0,130 Q100,110 200,125 Q300,140 400,120 Q500,100 600,118 Q700,136 800,115 L800,160 L0,160 Z" fill="url(#waveGrad)" opacity="0.3">
    <animate attributeName="d" 
      values="M0,130 Q100,110 200,125 Q300,140 400,120 Q500,100 600,118 Q700,136 800,115 L800,160 L0,160 Z;
              M0,120 Q100,140 200,118 Q300,100 400,130 Q500,145 600,125 Q700,108 800,128 L800,160 L0,160 Z;
              M0,130 Q100,110 200,125 Q300,140 400,120 Q500,100 600,118 Q700,136 800,115 L800,160 L0,160 Z"
      dur="6s" repeatCount="indefinite"/>
  </path>

  <!-- Floating dots -->
  <circle cx="50" cy="40" r="3" fill="#A78BFA" opacity="0.6">
    <animate attributeName="cy" values="40;25;40" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="750" cy="60" r="2" fill="#60A5FA" opacity="0.5">
    <animate attributeName="cy" values="60;40;60" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="30" r="4" fill="#34D399" opacity="0.4">
    <animate attributeName="cy" values="30;50;30" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="100" cy="90" r="2" fill="#F472B6" opacity="0.5">
    <animate attributeName="cy" values="90;70;90" dur="3.5s" repeatCount="indefinite"/>
  </circle>

  <!-- Main title -->
  <text x="400" y="65" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="34" font-weight="bold" fill="url(#textGrad)">
    Felipe Rojas Diaz
    <animate attributeName="opacity" values="0;1" dur="1s" fill="freeze"/>
  </text>

  <!-- Subtitle -->
  <text x="400" y="95" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="14" fill="#8B949E" letter-spacing="2">
    SYSTEMS ENGINEER  ·  INFRASTRUCTURE  ·  DISTRIBUTED SYSTEMS
    <animate attributeName="opacity" values="0;0;1" dur="1.5s" fill="freeze"/>
  </text>

  <!-- Bottom tag -->
  <text x="400" y="122" text-anchor="middle" font-family="'Segoe UI', Arial, sans-serif" font-size="12" fill="#A78BFA" opacity="0.8">
    🇨🇴  Universidad de los Andes  —  6to Semestre
  </text>
</svg>

<!-- Typing animation - reliable service -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=Building+systems+that+don%27t+break+under+pressure+%E2%9A%A1;Concurrency+nerd+%7C+Elixir+%26+OTP+enjoyer+%F0%9F%9F%A3;Microservices+%7C+Cloud+%7C+Low-level+magic+%F0%9F%94%A7;Actor+model+%7C+GenServers+%7C+Fault+tolerance+%F0%9F%A7%A0" alt="Typing SVG" />

<br/>

<!-- Social badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](AQUÍ_TU_LINK_DE_LINKEDIN)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tu-correo@uniandes.edu.co)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Byrojito)

![Profile Views](https://komarev.com/ghpvc/?username=Byrojito&color=A78BFA&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 🧠 Who am I?

```elixir
defmodule Felipe do
  @name     "Felipe Rojas Diaz"
  @uni      "Universidad de los Andes 🇨🇴"
  @semester "6th semester — Ingeniería de Sistemas y Computación"

  @interests [
    :distributed_systems,
    :cloud_infrastructure,
    :concurrency_and_parallelism,
    :software_architecture,
    :low_level_programming
  ]

  @currently_learning [:elixir, :otp, :actor_model]
  @side_projects      [:elixir_path, :bite_co]

  def fun_fact, do: "I think about actor models even while eating 🍕"
  def fuel,     do: "Tinto colombiano ☕ — no negociable"
end
```

---

## 🔭 Currently Building

<table>
<tr>
<td width="50%">

### ⚗️ ElixirPath
Learning platform for Elixir & OTP — interactive challenges, OTP process visualizers, and real-time multiplayer coding duels. Building what I wish existed when I started.

`Elixir` `Phoenix` `OTP` `GenServer` `LiveView`

</td>
<td width="50%">

### ☁️ BITE.co
Cloud resource management platform — full microservices architecture, API Gateway, Redis caching, multi-database strategy (PostgreSQL + MongoDB), deployed on AWS Academy.

`AWS` `Docker` `PostgreSQL` `MongoDB` `Redis`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

### 💻 Languages
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Elixir](https://img.shields.io/badge/Elixir-%234B275F.svg?style=for-the-badge&logo=elixir&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Assembly](https://img.shields.io/badge/Assembly-Intel%20IA32-6E40C9?style=for-the-badge&logo=assemblyscript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### ☁️ Infrastructure, Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230089D6.svg?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%23623CE4.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326CE5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)

### 🗄️ Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DC382D.svg?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 🧰 Tools & Platforms
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D4?style=for-the-badge&logo=azure-devops&logoColor=white)

---

## 📁 Featured Projects

<table>
<tr>
<td width="33%">

### 🏥 Continuum
Digital patient health-monitoring platform built on clean architecture principles. Designed for scalability and fault tolerance.

`Java` `Clean Architecture` `REST`

</td>
<td width="33%">

### 📞 VoIP Server
Full VoIP server deployment using **Asterisk** + **Zoiper** on Ubuntu. Configured SIP trunks, extensions, and dial plans from scratch.

`Linux` `Asterisk` `Networking`

</td>
<td width="33%">

### ⚡ Perf Experiments
Latency benchmarking across microservice architectures and API Gateways on AWS. Multi-DB query performance with Redis caching layers.

`AWS` `Microservices` `Redis`

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Byrojito&show_icons=true&theme=tokyonight&border_radius=10&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=A78BFA&text_color=ffffff" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Byrojito&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=ffffff&border_radius=10" width="48%"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Byrojito&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" width="60%"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Byrojito&bg_color=0D1117&color=A78BFA&line=60A5FA&point=34D399&area=true&hide_border=true" width="95%"/>

</div>

---

## ⚡ A bit more about me

```
🎯  Current focus  →  Elixir/OTP + distributed systems design
📚  Reading        →  "Designing Data-Intensive Applications" — Kleppmann
🧩  Obsession      →  How concurrency actually works at the hardware level
🏗️  Architecture   →  Microservices, event-driven, actor model
☕  Fuel           →  Tinto colombiano a cualquier hora
🌎  Based in       →  Bogotá, Colombia 🇨🇴
```

---

<!-- Animated SVG snake contribution graph placeholder text -->
<div align="center">

<!-- Trophy -->
<img src="https://github-profile-trophy.vercel.app/?username=Byrojito&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7" width="100%"/>

<br/><br/>

*"Make it work, make it right, make it fast — in that order."*

<br/>

![Wave](https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom_Up.svg)

</div>

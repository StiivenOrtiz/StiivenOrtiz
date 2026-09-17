<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:2EA043,100:3FB950&height=180&section=header&text=Stiven%20Ortiz%20Nore%C3%B1a&fontSize=44&fontColor=FFFFFF&fontAlignY=34&desc=Software%20Engineer%20%C2%B7%20Android%20%C2%B7%20Backend%20%C2%B7%20Payments&descAlignY=54&descSize=15" width="100%" alt="banner" />

<a href="https://github.com/StiivenOrtiz">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=2EA043&center=true&vCenter=true&width=700&lines=Software+Engineer+%40+Redeban;Built+the+ISO+8583+simulator+Redeban+tests+POS+terminals+with;Kotlin+%C2%B7+Java+%C2%B7+Spring+Boot+%C2%B7+Android;Backend+or+mobile+%E2%80%94+whatever+the+problem+needs" alt="typing" />
</a>

<br/>

<a href="https://www.linkedin.com/in/stiven-ortiz-norena"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

</div>

---

## 🚀 Featured work

### 🏦 ISO 8583 Transactional Simulator
`Java 17` · `Spring Boot` · `Netty` · `React` · custom ISO 8583 parser

The tool the team had been using was old and painful to change, so I read through its source, worked out why it didn't scale, and wrote a replacement from scratch. The new one lets you **add transactions without touching the core** and return custom responses per terminal.

It took about nine months, mostly on my own time. It's fully adopted now: **several areas at Redeban run their POS testing on it**, and merchants use it for their own integration testing. I'm **still adding to it** — new response behaviours for specific business cases, and more ways to connect when the infrastructure won't cooperate.

### 🌿 EcoGuardians 2.0 &nbsp;·&nbsp; [**▶ Play it in your browser**](https://stiivenortiz.github.io/EcoGuardians-2.0/)
`Unity` · `C#` · 3D open world

An open-world game where you walk around Awaq ONGD's biological station in Aguadas, Caldas and learn what they're doing to protect the ecosystem there. It was my **degree thesis**, and it earned a **Laureate** distinction.

I built the information displays, the task system and the minimap, and I was the team's **Scrum Master** for the ten months it took us.

<a href="https://stiivenortiz.github.io/EcoGuardians-2.0/"><img src="https://img.shields.io/badge/▶_Play_EcoGuardians_2.0-2EA043?style=for-the-badge&logo=unity&logoColor=white" alt="play" /></a>

---

## 🧑‍💻 About me

```kotlin
val stiven = SoftwareEngineer(
    company = "Redeban",
    based   = "Colombia 🇨🇴",
    nowOn   = "Android software for POS terminals",
    built   = "An ISO 8583 simulator, now used in production",
    cares   = "Code that is readable today and still correct in two years"
)
```

- 🧭 **Software engineer first.** I've done backend, right now I'm on mobile. I'd rather be useful wherever the problem is than get boxed into one layer.
- 📟 I work on the **Android software running on POS terminals** — the card reader you tap when you buy coffee.
- 🧪 I got into payments through **QA and terminal certification**: writing test suites for each device model, reporting bugs, digging through incidents. A year of breaking software on purpose taught me more about writing it than any course did.
- 🔌 That's where I learned **device integration**. Terminals, peripherals and hosts talking over **serial (RS-232)** and **TCP/IP**, with **ISO 8583** and **EMV** underneath.
- 🔎 I build my own tools for it too: small utilities that intercept POS traffic and show you exactly what the terminal and the host said to each other, plus Python scripts for the boring parts.
- 🤖 I work **spec-first with AI agents** (Claude Code, Antigravity). The prompt was never the hard part. What's hard is writing a spec tight enough that you can actually review what comes back — naming rules, testing gates, a definition of done the agent can't argue with. It's the same requirements work I do for POS features, just pointed somewhere else.
- ☕ On the backend side: **Spring Boot**, **Spring Cloud**, **Netty**, reactive **WebFlux**, PostgreSQL and Docker.
- 🎓 **Systems Engineer** from Pontificia Universidad Javeriana. My thesis earned a **Laureate** distinction.

---

## 🛠️ Tech Stack

**Languages**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=for-the-badge&logo=square&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Netty](https://img.shields.io/badge/Netty-2EA043?style=for-the-badge&logo=apache&logoColor=white)
![Reactor](https://img.shields.io/badge/Project_Reactor-DD0031?style=for-the-badge&logo=reactivex&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=for-the-badge&logo=oracle&logoColor=white)

**Payments & Protocols**

![ISO 8583](https://img.shields.io/badge/ISO_8583-1F2937?style=for-the-badge)
![EMV](https://img.shields.io/badge/EMV-1F2937?style=for-the-badge)
![Serial](https://img.shields.io/badge/Serial_RS--232-4B5563?style=for-the-badge&logo=serialport&logoColor=white)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-2EA043?style=for-the-badge&logo=cisco&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**Cloud & Data**

![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Tooling & Quality**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![ktlint](https://img.shields.io/badge/ktlint-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![detekt](https://img.shields.io/badge/detekt-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Antigravity](https://img.shields.io/badge/Antigravity-4285F4?style=for-the-badge&logo=google&logoColor=white)

---

## 📜 Certifications

![OCI Foundations](https://img.shields.io/badge/Oracle_Cloud_Infrastructure_2025-Foundations_Associate-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![OCI AI Foundations](https://img.shields.io/badge/Oracle_Cloud_Infrastructure_2025-AI_Foundations_Associate-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Oracle Data Platform](https://img.shields.io/badge/Oracle_Data_Platform_2025-Foundations_Associate-F80000?style=for-the-badge&logo=oracle&logoColor=white)

---

## 🌱 Currently learning

What I'm studying at the moment:

![AWS](https://img.shields.io/badge/AWS_Cloud_Practitioner-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)

---

<div align="center">

<img src="https://streak-stats.demolab.com?user=StiivenOrtiz&hide_border=true&background=00000000&stroke=808080&ring=2EA043&fire=3FB950&currStreakLabel=2EA043&sideLabels=808080&currStreakNum=808080&sideNums=808080&dates=808080" alt="streak" />

<img src="https://raw.githubusercontent.com/StiivenOrtiz/StiivenOrtiz/output/snake.svg" alt="snake animation" width="100%" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3FB950,50:2EA043,100:0D1117&height=110&section=footer" width="100%" alt="footer" />

</div>

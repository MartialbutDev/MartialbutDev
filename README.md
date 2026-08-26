<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=header&color=0:0D1117,100:1F6FEB" width="100%" />

<div align="center">

# 👋 Hi, I'm Varren Meg Naive

### `BSIT Student` · `Backend Developer` · `Mobile Developer`

<!-- INTERACTIVE TYPING ANIMATION -->
<a href="https://github.com/MartialbutDev">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=700&lines=Welcome+to+my+GitHub+%F0%9F%91%8B;I+build+web+and+mobile+applications;Backend+%7C+APIs+%7C+Databases;Currently+building+AIMS+%F0%9F%9A%80;Always+learning.+Always+building." alt="Typing animation" />
</a>

<br>

<!-- INTERACTIVE NAVIGATION BAR -->
<a href="#-about-me"><kbd> 👤 About </kbd></a> · <a href="#-tech-stack"><kbd> 🛠️ Tech Stack </kbd></a> · <a href="#-featured-project"><kbd> 🚀 AIMS </kbd></a> · <a href="#-interactive-stats"><kbd> 📊 Stats </kbd></a> · <a href="#-let's-connect"><kbd> 📫 Contact </kbd></a>

<br><br>

<!-- LIVE VISITOR COUNTER -->
<img src="https://komarev.com/ghpvc/?username=MartialbutDev&label=Profile%20Views&color=1F6FEB&style=flat-square" alt="Profile Views" />

</div>

<br>

## 🧑‍💻 About Me

I'm **Varren Meg Naive**, a **BSIT student at the University of Science and Technology of Southern Philippines (USTP)**.

I specialize in building practical software that bridges **robust backend systems, RESTful APIs, and mobile-first interfaces**. Right now, most of my energy is directed toward **AIMS**, a full-stack internship management platform I'm building from the ground up.

<details>
<summary><b>👀 Click to expand my background & philosophy</b></summary>
<br>

*   🎓 **Education:** BSIT @ USTP
*   💻 **Primary Focus:** Backend Development & System Architecture
*   📱 **Also Building In:** Mobile (React Native) & Web (React)
*   🗄️ **Databases:** MySQL / MariaDB
*   🚀 **Current Project:** Academic Internship Management System (AIMS)
*   ⚡ **My Philosophy:** *Plan, build, test, break, fix, repeat.*

</details>

---

## 🎯 What I Do

<table>
<tr>
<td width="33%" valign="top">

**⚙️ Backend**
- PHP / Laravel
- REST API Design
- Auth & Authorization
- Database Design

</td>
<td width="33%" valign="top">

**📱 Mobile**
- React Native (Expo)
- TypeScript
- Expo Router
- Cross-platform UI

</td>
<td width="33%" valign="top">

**🌐 Web**
- React
- JavaScript
- Tailwind CSS
- Responsive UI

</td>
</tr>
</table>

---

## 🚀 Featured Project

<div align="center">

### 📱 Academic Internship Management System — `AIMS`

**A mobile-first platform that digitizes university internship workflows end to end.**

<a href="https://github.com/MartialbutDev/AIMS">
<img src="https://img.shields.io/badge/🚀%20View%20AIMS%20Repository-238636?style=for-the-badge" />
</a>

</div>

AIMS gives students, internship coordinators, host training establishments, and university staff one centralized system to handle applications, documentation, monitoring, and reporting.

<!-- INTERACTIVE ACCORDIONS -->
<details>
<summary><b>✨ Click to view Core Modules</b></summary>
<br>

| Module | Purpose |
|---|---|
| 🔐 **Authentication** | Secure login and role-based access |
| 📝 **Applications** | Digital internship applications |
| 🔎 **OCR** | Automated document extraction & validation |
| ⏱️ **DTR** | Daily Time Record management |
| 📊 **Monitoring** | Internship progress tracking |

</details>

<details>
<summary><b>🏗️ Click to view System Architecture</b></summary>
<br>

```mermaid
graph TD
    User([End Users]) -->|Interacts with| MobileApp
    
    subgraph Frontend
        MobileApp[React Native App<br>Expo + TypeScript]
    end
    
    subgraph Backend
        API[Laravel Backend<br>REST API + PHP]
    end
    
    subgraph Services
        DB[(MySQL)]
        OCR[OCR Validation]
    end
    
    MobileApp <-->|JSON| API
    API <-->|Read / Write| DB
    API <-->|Processing| OCR

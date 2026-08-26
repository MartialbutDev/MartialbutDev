<div align="center">

# 👋 Hi, I'm Varren Meg Naive

### `BSIT Student` · `Backend Developer` · `Mobile Developer`

<a href="https://github.com/MartialbutDev">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=700&lines=Welcome+to+my+GitHub+%F0%9F%91%8B;I+build+web+and+mobile+applications;Backend+%7C+APIs+%7C+Databases;Currently+building+AIMS+%F0%9F%9A%80;Always+learning.+Always+building." alt="Typing animation" />
</a>

<br>

<a href="#-about-me">About</a> · <a href="#-tech-stack">Tech Stack</a> · <a href="#-featured-project">AIMS</a> · <a href="#-github-analytics">Stats</a> · <a href="#-connect-with-me">Contact</a>

<br>

<img src="https://komarev.com/ghpvc/?username=MartialbutDev&label=Profile%20Views&color=1F6FEB&style=flat-square" alt="Profile Views" />

</div>

<br>

## 🧑‍💻 About Me

I'm **Varren Meg Naive**, a **BSIT student at the University of Science and Technology of Southern Philippines (USTP)**.

I engineer practical software solutions that bridge **backend systems, databases, RESTful APIs, and mobile-first interfaces**. Currently, the majority of my focus is dedicated to **AIMS**, a full-stack academic internship management platform I am architecting from the ground up.

<table>
  <tr>
    <td valign="top">🎓</td>
    <td><b>Education</b></td>
    <td>BS in Information Technology @ USTP</td>
  </tr>
  <tr>
    <td valign="top">💻</td>
    <td><b>Primary Focus</b></td>
    <td>Backend Development & API Architecture</td>
  </tr>
  <tr>
    <td valign="top">📱</td>
    <td><b>Also Building In</b></td>
    <td>Mobile (React Native) & Modern Web</td>
  </tr>
  <tr>
    <td valign="top">🚀</td>
    <td><b>Current Project</b></td>
    <td>Academic Internship Management System (AIMS)</td>
  </tr>
  <tr>
    <td valign="top">🌱</td>
    <td><b>Currently Sharpening</b></td>
    <td>Laravel, React Native + TypeScript, System Design</td>
  </tr>
  <tr>
    <td valign="top">⚡</td>
    <td><b>Philosophy</b></td>
    <td>Learn by building — plan, build, break, fix, repeat.</td>
  </tr>
</table>

---

## 🎯 What I Do

<table>
  <tr>
    <td width="33%" valign="top">
      <b>⚙️ Backend & Systems</b><br><br>
      • PHP / Laravel<br>
      • RESTful API Design<br>
      • Auth & Authorization<br>
      • Relational Database Design<br>
      • Business Logic Integration
    </td>
    <td width="33%" valign="top">
      <b>📱 Mobile Development</b><br><br>
      • React Native (Expo)<br>
      • TypeScript<br>
      • Expo Router<br>
      • Third-party API Integration<br>
      • Cross-platform UI/UX
    </td>
    <td width="33%" valign="top">
      <b>🌐 Web Interfaces</b><br><br>
      • React.js<br>
      • JavaScript (ES6+)<br>
      • Tailwind CSS<br>
      • Responsive Design<br>
      • State Management
    </td>
  </tr>
</table>

---

## 🚀 Featured Project

<div align="center">

### 📱 Academic Internship Management System — `AIMS`

**A mobile-first platform digitizing university internship workflows end-to-end.**

<a href="https://github.com/MartialbutDev/AIMS">
<img src="https://img.shields.io/badge/🚀%20Explore%20the%20AIMS%20Repository-238636?style=for-the-badge" />
</a>

</div>

AIMS provides students, internship coordinators, host training establishments (HTEs), and university staff with a centralized ecosystem to handle applications, documentation, monitoring, and reporting—effectively replacing paper-heavy legacy processes.

<details>
<summary><b>✨ Core Modules</b></summary>
<br>

| Module | Purpose |
|---|---|
| 🔐 **Authentication** | Secure, role-based access control (RBAC) |
| 📝 **Applications** | Streamlined digital internship applications |
| 🏢 **HTE Management** | Host Training Establishment records and onboarding |
| 📄 **Documents** | Digital document submission and storage |
| 🔎 **OCR Engine** | Automated document extraction & validation |
| ⏱️ **DTR** | Real-time Daily Time Record management |
| 📖 **Journals** | Weekly progress journals and reflections |
| 📊 **Monitoring** | Live internship progress tracking |
| 📈 **Analytics** | Data-driven insights for coordinators |
| 🔔 **Notifications** | Automated reminders and status updates |

</details>

<details>
<summary><b>🏗️ System Architecture</b></summary>
<br>

```mermaid
graph TD
    User([End Users<br>Students / Staff]) -->|Interacts with| MobileApp
    
    subgraph Frontend
        MobileApp[React Native App<br>Expo + TypeScript]
    end
    
    subgraph Backend Services
        API[Laravel Backend<br>REST API + PHP]
    end
    
    subgraph Data & Utilities
        DB[(MySQL / MariaDB)]
        OCR[OCR Validation Engine]
    end
    
    MobileApp <-->|JSON over HTTPS| API
    API <-->|Read / Write| DB
    API <-->|Image Processing| OCR
    
    style User fill:#0D1117,stroke:#58A6FF,stroke-width:2px,color:#fff
    style MobileApp fill:#20232A,stroke:#61DAFB,stroke-width:2px,color:#fff
    style API fill:#FF2D20,stroke:#fff,stroke-width:2px,color:#fff
    style DB fill:#4479A1,stroke:#fff,stroke-width:2px,color:#fff
    style OCR fill:#3776AB,stroke:#fff,stroke-width:2px,color:#fff

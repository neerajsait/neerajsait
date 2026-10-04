<!-- Paste into README.md of your repo named exactly: neerajsait/neerajsait -->
<!-- Search for ✏️ and fill in your real details. Delete any line that isn't true. -->

<img src="https://capsule-render.vercel.app/api?type=venom&height=250&color=gradient&customColorList=6,11,20&section=header&text=Neeraj%20Venkata%20Sai&fontSize=54&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=I%20build%20secure%20backend%20systems%20that%20hold%20up%20under%20pressure&descSize=18&descAlignY=60" width="100%" alt=""/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=760&lines=Backend+Developer+%E2%80%A2+Java+%26+Spring+Boot+%E2%98%95;Zero-Knowledge+%E2%80%A2+Cybersecurity+%E2%80%A2+Python+%F0%9F%94%90;715%2B+commits+%E2%80%A2+28+repositories+%F0%9F%9A%80;Open+to+full-time+roles+%E2%9C%A8)](https://github.com/neerajsait)

<img src="https://img.shields.io/badge/B.Tech%20CSE-KL%20University-7c3aed?style=for-the-badge&logo=googlescholar&logoColor=white"/>
<img src="https://img.shields.io/badge/Vijayawada-India-ec4899?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/badge/OPEN%20TO%20WORK-22c55e?style=for-the-badge&logo=checkmarx&logoColor=white"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neerajsait/)
[![Email](https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tneerajvenkatasai@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=6,11,20" width="100%" alt=""/>

## 👋 About Me

I'm **Neeraj**, a Computer Science student at **KL University** who enjoys the part of software where mistakes are expensive: authentication, privacy, and systems that must keep working while someone is trying to break them.

My main tool is **Java with Spring Boot**. Around it I've built a **zero-knowledge vault**, **security labs**, a **network monitor** and a **food-ordering app**, which taught me how a real product connects from the screen down to the database.

> ✏️ *Add one personal line: what made you start coding, or what you want to build next.*

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=6,11,20" width="100%" alt=""/>

## 🧰 Skills

<div align="center">
<img src="https://skillicons.dev/icons?i=java,spring,python,flask,js,ts,react,html,css,c,mysql,redis,docker,aws,linux,git&perline=8" alt="skills"/>
</div>

<br/>

| | Skill | Where I've used it |
|:---:|---|---|
| ☕ | **Java · Spring Boot** | RecruiterService: layered REST backend with MySQL |
| 🐍 | **Python** | ZK-Vault and the cybersecurity labs |
| 🔐 | **Security & cryptography** | Zero-knowledge storage, injection and auth-bypass labs |
| 🌐 | **JavaScript · HTML · CSS** | FoodPilot and the Network-Monitor dashboard |
| 🐳 | **Docker · Linux · AWS · Git** | Packaging, running and shipping my projects |

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=6,11,20" width="100%" alt=""/>

## 🛠️ What I Built, and How

### 🔐 ZK-Vault: private storage the server can't read

**The idea:** most vaults ask you to trust the server. I wanted one where the server **cannot** read your data even if it wants to.

```mermaid
flowchart LR
    A["👤 User enters secret"] --> B["🔑 Client derives key<br/>and encrypts data"]
    B --> C["📦 Only ciphertext<br/>leaves the browser"]
    C --> D[("🗄️ Server stores<br/>encrypted blobs")]
    D --> E["🔓 Ciphertext returns,<br/>client decrypts"]
```

- Built in **Python**, with encryption done on the client side
- The server stores data it has no way to read
- ✏️ *Add: which algorithms (AES? PBKDF2? Argon2?), and how you handled keys*

**What it taught me:** "encrypted" and "zero-knowledge" are not the same claim, and good security is mostly about deciding what the server is *not allowed to know*.

🔗 [github.com/neerajsait/ZK-Vault](https://github.com/neerajsait/ZK-Vault)

---

### 💼 RecruiterService: a hiring portal for campus placements

**The idea:** campus hiring is usually tracked in spreadsheets and chats. This is the recruiter side of a placement system: manage job postings, view applications, schedule interviews and see recruitment data.

```mermaid
flowchart LR
    A["🖥️ Recruiter<br/>JSP + Bootstrap"] --> B["⚙️ Spring Boot<br/>Controller"]
    B --> C["🧠 Service layer<br/>business logic"]
    C --> D["📚 Repository"]
    D --> E[("🛢️ MySQL")]
```

- **Spring Boot** backend with MySQL, plus JSP and Bootstrap pages for the recruiter dashboard
- Screens for login, dashboard, job posting list and new job posting
- ✏️ *Add: how login/auth works, how many entities and endpoints you built*

**What it taught me:** structuring a real Java project in layers, designing relational tables, and building every screen a user needs, not just the API.

🔗 [github.com/neerajsait/RecruiterService](https://github.com/neerajsait/RecruiterService)

---

### 🍔 FoodPilot: a food-ordering web app

**The idea:** ✏️ *Describe in one line what problem FoodPilot solves.*

- Built with **JavaScript** ✏️ *(React? Node? which APIs?)*
- ✏️ *List 2 or 3 features: search, cart, ordering, tracking*

**What it taught me:** ✏️ *One real lesson, such as managing state or connecting a frontend to an API.*

> ⚠️ This repo has no description yet. Add one on GitHub so the card on your profile isn't blank.

🔗 [github.com/neerajsait/FoodPilot](https://github.com/neerajsait/FoodPilot)

---

### 📡 Network-Monitor: a web dashboard for network health

**The idea:** see what's happening on a network in one place instead of reading terminal output.

- A web-based dashboard built with **HTML**, CSS and JavaScript
- ✏️ *Add: what it measures (devices? latency? traffic?) and where the data comes from*

**What it taught me:** ✏️ *One real lesson, such as displaying live data clearly.*

🔗 [github.com/neerajsait/Network-Monitor](https://github.com/neerajsait/Network-Monitor)

---

### 🛡️ Cybersecurity Projects: attack it, then fix it

**The idea:** I learn security by breaking things on purpose. These are Python scripts and labs covering penetration testing, injection and authentication bypass.

```mermaid
flowchart LR
    A["🧪 Build a<br/>vulnerable app"] --> B["💥 Attack it"] --> C["🔍 Understand<br/>why it broke"] --> D["🛠️ Patch it"]
```

**What it taught me:** thinking like an attacker makes me write safer backend code.

🔗 [github.com/neerajsait/cybersecurity-projects](https://github.com/neerajsait/cybersecurity-projects)

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=6,11,20" width="100%" alt=""/>

## 🔄 How I Work

```mermaid
flowchart LR
    A["💡 Pick a problem<br/>I don't understand yet"] --> B["📖 Learn just<br/>enough to start"]
    B --> C["🔨 Build a<br/>working version"]
    C --> D["💥 Break it,<br/>find the weak spots"]
    D --> E["🛠️ Fix and<br/>document it"]
    E --> A
```

I don't stop at "it runs." I try to break each project, then I fix it. That habit comes from my security work and it shows up in everything I build.

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=6,11,20" width="100%" alt=""/>

## 📈 How I Grew

| | Stage | What happened |
|:---:|---|---|
| 🌱 | **Foundations** | Started with programming basics ✏️ *(C? Java? when?)* |
| 🌐 | **Web basics** | Built interfaces with HTML, CSS and JavaScript, which became Network-Monitor and FoodPilot |
| ☕ | **Backend** | Learned Spring Boot and MySQL by building RecruiterService end to end |
| 🔐 | **Security** | Moved into cryptography and attack labs, which led to ZK-Vault and cybersecurity-projects |
| 🚀 | **Now** | 715+ commits across 28 repositories ✏️ *(add what you're learning now)* |

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=6,11,20" width="100%" alt=""/>

## 🎯 What I'm Looking For

A **backend or security-focused developer role** where I can write production Java, work with experienced engineers and keep improving. I'm also open to internships and open-source collaboration.

<div align="center">

### 📬 Let's talk

[![LinkedIn](https://img.shields.io/badge/LinkedIn-neerajsait-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neerajsait/)
[![Gmail](https://img.shields.io/badge/tneerajvenkatasai@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tneerajvenkatasai@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=gradient&customColorList=6,11,20&section=footer" width="100%" alt=""/>

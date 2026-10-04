<!-- Paste into README.md of your repo named exactly: neerajsait/neerajsait -->
<!-- Search for ✏️ and replace those bits with your real details before publishing -->

<img src="https://capsule-render.vercel.app/api?type=venom&height=230&color=gradient&customColorList=12,20,24&section=header&text=Neeraj%20Venkata%20Sai&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Backend%20Developer%20%E2%80%A2%20Java%20%E2%80%A2%20Spring%20Boot%20%E2%80%A2%20Security&descSize=18&descAlignY=60" width="100%" alt=""/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=F472B6&center=true&vCenter=true&width=720&lines=Hi%2C+I'm+Neeraj+%F0%9F%91%8B;I+turn+ideas+into+secure+backend+systems;Java+%E2%80%A2+Spring+Boot+%E2%80%A2+Python+%E2%80%A2+Cryptography;715%2B+commits+and+still+shipping+%F0%9F%9A%80)](https://github.com/neerajsait)

![Commits](https://img.shields.io/badge/COMMITS-715%2B-ec4899?style=for-the-badge&logo=git&logoColor=white)
![Repos](https://img.shields.io/badge/REPOS-28-8b5cf6?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/OPEN%20TO%20WORK-YES-22c55e?style=for-the-badge)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neerajsait/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tneerajvenkatasai@gmail.com)

</div>

---

## 🚀 Who I Am

I'm **Neeraj**, a B.Tech Computer Science student at **KL University, Vijayawada**. I build backend systems with **Java and Spring Boot**, and I'm drawn to the problems where security decides whether a system is good: who gets in, what the server can see, and what happens when someone attacks.

I learn by building. Every project below started as something I wanted to understand, and I kept going until it worked end to end.

> ✏️ *Add one sentence about what excites you most, for example "I want to build the kind of backend that handles money safely."*

---

## 🧰 My Skills

<div align="center">
<img src="https://skillicons.dev/icons?i=java,spring,python,flask,js,ts,react,c,mysql,redis,docker,aws,linux,git&perline=7" alt="skills"/>
</div>

| 🎯 Area | What I can do with it |
|---|---|
| **☕ Java / Spring Boot** | Build REST APIs with layered design, JWT authentication and MySQL persistence |
| **🐍 Python / Flask** | Ship ML models and security tools behind clean APIs |
| **🔐 Security** | Client-side encryption, zero-knowledge design, injection and auth-bypass labs |
| **🐳 DevOps basics** | Containerise apps with Docker, work on Linux, deploy on AWS |
| **⚛️ Frontend** | React, JavaScript and TypeScript for UIs that talk to my own backends |

---

## 🛠️ Projects: What I Built and How

<details open>
<summary><b>🔐 ZK-Vault: a vault the server cannot read</b></summary>
<br/>

**The problem:** most password and file vaults make you trust the server. If it's breached, your data goes with it.

**How I built it:**
- Encryption happens **on the client**, so the server only ever stores ciphertext
- Keys are derived from the user's password using ✏️ *(e.g. PBKDF2 / Argon2)* and never leave the client
- Backend in **Python** ✏️ *(Flask?)* that stores and returns encrypted blobs

**What I learned:** why "encrypted" and "zero-knowledge" are different claims, and how much of security is about deciding what the server is *not allowed to know*.

🔗 [View the repo](https://github.com/neerajsait/ZK-Vault)
</details>

<details>
<summary><b>💼 RecruiterService: campus hiring backend</b></summary>
<br/>

**The problem:** campus placements are often tracked in spreadsheets and chat groups, so recruiters lose track of postings, applicants and interview slots.

**How I built it:**
- **Spring Boot** REST backend with controller → service → repository layers
- **MySQL** for jobs, applications and interviews
- **JWT** authentication so each role (recruiter, student, admin) sees only what it should
- Frontend pages with JSP and Bootstrap for the recruiter dashboard

**What I learned:** structuring a real Java project, designing relational tables, and securing endpoints properly.

🔗 [View the repo](https://github.com/neerajsait/RecruiterService)
</details>

<details>
<summary><b>🕵️ Phishing URL Detector: ML that spots bad links</b></summary>
<br/>

**The problem:** phishing links look legitimate, and rule-based filters miss new ones.

**How I built it:**
- Extracted features from URLs (length, special characters, domain patterns, and so on)
- Trained a supervised classifier ✏️ *(which model, accuracy %, dataset size)*
- Wrapped the model in a **Flask** API that classifies a URL in real time

**What I learned:** feature engineering matters more than the model, and a model is only useful once it's behind an API.

🔗 [View the repo](https://github.com/neerajsait/Phishing-URL)
</details>

<details>
<summary><b>🛡️ Cybersecurity Projects: attacks, then fixes</b></summary>
<br/>

**What it is:** a collection of labs and scripts covering SQL injection, authentication bypass and penetration-testing tools.

**How I built it:** I wrote small vulnerable apps on purpose, attacked them, then patched them, so each lab shows both the exploit and the fix.

**What I learned:** thinking like an attacker makes me write safer backend code.

🔗 [View the repo](https://github.com/neerajsait/cybersecurity-projects)
</details>

---

## 📈 How I Grew

| Stage | What I did | What it taught me |
|:---:|---|---|
| 🌱 **Start** | Began with **C and Java** in my first-year coursework ✏️ | Programming fundamentals and problem-solving |
| 🔨 **Build** | Made small web projects in **JavaScript and Python** | How the frontend and backend fit together |
| ☕ **Deepen** | Moved to **Spring Boot**, MySQL and REST design | Writing structured, maintainable backend code |
| 🔐 **Specialise** | Went into **cybersecurity and cryptography**: ZK-Vault, attack labs | Building systems that are secure by design |
| 🤖 **Expand** | Added **ML** with the phishing detector and browser-based face recognition | Applying AI to real problems |
| 🚀 **Now** | Learning **Spring Cloud and system design**, polishing projects, seeking a backend role | Thinking about scale, not just features |

📊 **715+ commits across 28 repositories**, built one project at a time.

---

## 🎯 What I'm Looking For

A **backend or security-focused developer role** where I can write production Java, learn from experienced engineers, and keep building. I'm open to full-time roles, internships and open-source collaboration.

<div align="center">

### 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-neerajsait-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neerajsait/)
[![Gmail](https://img.shields.io/badge/Gmail-tneerajvenkatasai@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tneerajvenkatasai@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=gradient&customColorList=12,20,24&section=footer" width="100%" alt=""/>

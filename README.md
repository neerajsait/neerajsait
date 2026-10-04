<!-- Paste into README.md of your repo named exactly: neerajsait/neerajsait -->
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

> 💡 *I started coding out of curiosity about how systems work under the hood, and now I'm focused on building resilient microservices and automated security auditing tools.*

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=6,11,20" width="100%" alt=""/>

## 🧰 Skills

<div align="center">
<img src="https://skillicons.dev/icons?i=java,spring,python,flask,js,ts,react,html,css,c,mysql,redis,docker,aws,linux,git&perline=8" alt="skills"/>
</div>
<br/>

| | Skill | Where I've used it |
|:---:|---|---|
| ☕ | **Java · Spring Boot** | RecruiterService: layered REST & MVC backend with MySQL |
| 🐍 | **Python · Flask** | ZK-Vault, secure encryption systems, and cybersecurity labs |
| 🔐 | **Security & Cryptography** | Zero-knowledge storage, MFA, RBAC, audit logging, and auth-bypass labs |
| 🌐 | **JavaScript · React · HTML/CSS** | FoodPilot and the Network-Monitor dashboard |
| 🐳 | **Docker · Linux · AWS · Git** | Packaging, running, and shipping my projects |

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

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:161b22&height=4" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=3000&pause=1200&color=61AFFE&background=0D1117&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=85&lines=curl+-X+GET+%22https%3A%2F%2Fgithub.com%2Fneerajsait%22+--include;HTTP%2F1.1+200+OK+%7C+Content-Type%3A+application%2Fjson;%7B+%22name%22%3A+%22Neeraj+Venkata+Sai%22%2C+%22role%22%3A+%22Full-Stack+Dev%22+%7D)](https://github.com/neerajsait)

<br/>

# Developer API

![Version](https://img.shields.io/badge/version-2.5.0-61affe?style=flat-square&labelColor=161b22)
![Status](https://img.shields.io/badge/status-online-49cc90?style=flat-square&labelColor=161b22)
![Uptime](https://img.shields.io/badge/uptime-99.9%25-49cc90?style=flat-square&labelColor=161b22)
![Auth](https://img.shields.io/badge/auth-none%20required-fca130?style=flat-square&labelColor=161b22)
![Format](https://img.shields.io/badge/format-application%2Fjson-61affe?style=flat-square&labelColor=161b22)
![Views](https://komarev.com/ghpvc/?username=neerajsait&style=flat-square&color=61affe&label=requests+served&labelColor=161b22)

</div>

---

```
Base URL  →  https://github.com/neerajsait
Server    →  Vijayawada, India  🇮🇳
Updated   →  2025-07-17
Contact   →  tneerajvenkatasai@gmail.com
```

---

## Endpoints

| Method | Route | Description | Status |
|--------|-------|-------------|--------|
| ![GET](https://img.shields.io/badge/GET-61affe?style=flat-square) | `/profile` | Full developer profile | ![200](https://img.shields.io/badge/200-OK-49cc90?style=flat-square) |
| ![GET](https://img.shields.io/badge/GET-61affe?style=flat-square) | `/profile/skills` | Tech stack & proficiency | ![200](https://img.shields.io/badge/200-OK-49cc90?style=flat-square) |
| ![GET](https://img.shields.io/badge/GET-61affe?style=flat-square) | `/profile/projects` | Featured repositories | ![200](https://img.shields.io/badge/200-OK-49cc90?style=flat-square) |
| ![GET](https://img.shields.io/badge/GET-61affe?style=flat-square) | `/profile/stats` | Commit metrics & activity | ![200](https://img.shields.io/badge/200-OK-49cc90?style=flat-square) |
| ![POST](https://img.shields.io/badge/POST-49cc90?style=flat-square) | `/contact` | Send a collaboration request | ![201](https://img.shields.io/badge/201-Created-49cc90?style=flat-square) |
| ![GET](https://img.shields.io/badge/GET-61affe?style=flat-square) | `/profile/education` | Academic background | ![200](https://img.shields.io/badge/200-OK-49cc90?style=flat-square) |

---

## `GET` `/profile`

> Returns the complete developer object.

```bash
curl -X GET "https://github.com/neerajsait" \
  -H "Accept: application/json"
```

**Response** · `200 OK`

```json
{
  "id":         "neerajsait",
  "name":       "Tiruveedhi Neeraj Venkata Sai",
  "role":       "Full-Stack Developer",
  "headline":   "Building secure, scalable systems at the intersection of web and security",
  "location":   "Vijayawada, Andhra Pradesh, India",
  "timezone":   "IST (UTC+5:30)",
  "available":  true,
  "open_to":    ["full-time roles", "freelance", "open-source collaboration"],
  "fun_fact":   "Writes cleaner code after midnight than before noon"
}
```

---

## `GET` `/profile/skills`

> Returns tech stack with proficiency levels and years of experience.

```bash
curl -X GET "https://github.com/neerajsait/skills" \
  -H "Accept: application/json"
```

**Response** · `200 OK`

```json
{
  "languages": {
    "Java":        { "level": "advanced",      "proficiency": 90 },
    "TypeScript":  { "level": "advanced",      "proficiency": 87 },
    "Python":      { "level": "intermediate",  "proficiency": 78 },
    "JavaScript":  { "level": "advanced",      "proficiency": 85 },
    "C":           { "level": "intermediate",  "proficiency": 65 }
  },
  "frameworks": {
    "Spring Boot": { "level": "advanced",      "proficiency": 88 },
    "React.js":    { "level": "advanced",      "proficiency": 86 },
    "Node.js":     { "level": "intermediate",  "proficiency": 72 },
    "Flask":       { "level": "intermediate",  "proficiency": 68 }
  },
  "tools": {
    "Docker":   { "level": "intermediate",  "proficiency": 80 },
    "MySQL":    { "level": "advanced",      "proficiency": 84 },
    "Git":      { "level": "advanced",      "proficiency": 92 },
    "AWS":      { "level": "beginner",      "proficiency": 50 },
    "Linux":    { "level": "intermediate",  "proficiency": 75 }
  },
  "domains": ["Cybersecurity", "Zero-Knowledge Proofs", "REST APIs", "Microservices", "AI/ML"]
}
```

---

## `GET` `/profile/projects`

> Returns an array of featured projects. Sorted by impact descending.

```bash
curl -X GET "https://github.com/neerajsait/projects?pinned=true&limit=8" \
  -H "Accept: application/json"
```

**Response** · `200 OK`

```json
[
  {
    "id":          "ZK-Vault",
    "url":         "https://github.com/neerajsait/ZK-Vault",
    "description": "Zero-knowledge cryptographic vault — server never sees plaintext",
    "stack":       ["Python", "Cryptography", "ZKP"],
    "tags":        ["security", "cryptography", "privacy"]
  },
  {
    "id":          "Phishing-URL",
    "url":         "https://github.com/neerajsait/Phishing-URL",
    "description": "ML classifier detecting malicious URLs with high accuracy",
    "stack":       ["Python", "Machine Learning", "Flask"],
    "tags":        ["security", "ml", "threat-detection"]
  },
  {
    "id":          "RecruiterService",
    "url":         "https://github.com/neerajsait/RecruiterService",
    "description": "Production-grade recruitment backend with JWT auth & RESTful APIs",
    "stack":       ["Java", "Spring Boot", "MySQL"],
    "tags":        ["backend", "microservices", "rest-api"]
  },
  {
    "id":          "cybersecurity-projects",
    "url":         "https://github.com/neerajsait/cybersecurity-projects",
    "description": "Penetration testing scripts, vulnerability demos, and auth labs",
    "stack":       ["Python", "Flask", "Bash"],
    "tags":        ["security", "pentesting", "ethical-hacking"]
  },
  {
    "id":          "Face-Recognition",
    "url":         "https://github.com/neerajsait/Face-Recognition",
    "description": "Real-time face detection and recognition in the browser",
    "stack":       ["JavaScript", "AI APIs", "Canvas"],
    "tags":        ["ai", "computer-vision", "browser"]
  },
  {
    "id":          "packing-flask-with-docker",
    "url":         "https://github.com/neerajsait/packing-flask-with-docker",
    "description": "Flask web app fully containerized — clean DevOps reference",
    "stack":       ["Python", "Flask", "Docker"],
    "tags":        ["devops", "docker", "containerization"]
  }
]
```

---

## `GET` `/profile/stats`

> Returns live commit metrics, language distribution, and contribution telemetry.

```bash
curl -X GET "https://github.com/neerajsait/stats" \
  -H "Accept: application/json"
```

**Response** · `200 OK`

<div align="center">

<img height="160em" src="https://github-readme-stats.vercel.app/api?username=neerajsait&show_icons=true&hide_border=true&border_radius=6&bg_color=161b22&title_color=61affe&text_color=c9d1d9&icon_color=49cc90&include_all_commits=true&count_private=true" />
<img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=neerajsait&layout=compact&hide_border=true&border_radius=6&bg_color=161b22&title_color=fca130&text_color=c9d1d9&langs_count=8" />

<img src="https://github-readme-streak-stats.herokuapp.com?user=neerajsait&theme=transparent&hide_border=true&border_radius=6&background=161b22&ring=61affe&fire=fca130&currStreakLabel=61affe&sideLabels=c9d1d9&dates=555555" width="55%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=neerajsait&bg_color=161b22&color=61affe&line=49cc90&point=fca130&area=true&area_color=61affe20&hide_border=true&radius=6" width="94%" />

</div>

---

## `POST` `/contact`

> Opens a collaboration session. Returns a connection object on success.

```bash
curl -X POST "https://www.linkedin.com/in/neerajsait" \
  -H "Content-Type: application/json" \
  -d '{
    "from":    "your-name",
    "subject": "collaboration | opportunity | just saying hi",
    "message": "your message here"
  }'
```

**Response** · `201 Created`

```json
{
  "status":    201,
  "message":   "Connection request sent. Response time: usually < 24h",
  "channels": {
    "linkedin":  "https://www.linkedin.com/in/neerajsait",
    "email":     "tneerajvenkatasai@gmail.com",
    "instagram": "https://www.instagram.com/neerajsai.t",
    "github":    "https://github.com/neerajsait"
  }
}
```

---

## `GET` `/profile/education`

> Returns academic credentials and institutional affiliations.

```bash
curl -X GET "https://github.com/neerajsait/education" \
  -H "Accept: application/json"
```

**Response** · `200 OK`

```json
{
  "degree":      "B.Tech, Computer Science & Engineering",
  "institution": "KL University",
  "location":    "Vijayawada, Andhra Pradesh, India",
  "status":      "enrolled",
  "focus":       ["Software Engineering", "Cybersecurity", "Data Structures & Algorithms"]
}
```

---

<div align="center">

```
┌─────────────────────────────────────────────────────────┐
│                    API Rate Limits                       │
│  Stars         →  unlimited (the more the better)       │
│  Forks         →  unlimited (go ahead, build on it)     │
│  Collaborations→  open     (always accepting)           │
│  Cold DMs      →  welcome  (seriously, say hi)          │
└─────────────────────────────────────────────────────────┘
```

![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)
[![LinkedIn](https://img.shields.io/badge/-neerajsait-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/neerajsait/)
&nbsp;
![Email](https://img.shields.io/badge/Gmail-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)
[![Email](https://img.shields.io/badge/-tneerajvenkatasai%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tneerajvenkatasai@gmail.com)

<br/>

`v2.5.0` · `© 2025 neerajsait` · `MIT License` · `All endpoints return JSON`

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:161b22,100:0d1117&height=4" width="100%"/>

</div>

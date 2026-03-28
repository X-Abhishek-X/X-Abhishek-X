<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3500&pause=800&color=00FF41&center=true&vCenter=true&random=false&width=700&lines=Security+Engineer+%2F+Automation+Dev;I+build+tools+that+catch+threats;Detect+%E2%86%92+Respond+%E2%86%92+Patch+%E2%86%92+Monitor;EPSS+%C3%97+CVSS+%3D+what%27s+actually+on+fire" alt="Typing SVG" />

</div>

<p align="center"><i>Building security automation that actually gets deployed — not just demo'd.</i></p>

<br/>

---

### The pipeline

Six tools. One workflow. Built from scratch.

```mermaid
graph TD
    A["🔍 OSINT-Leak-Radar"] --> C["🔬 forensic-timeline-builder"]
    B["📡 wifi-security-auditor"] --> C
    C --> D["⚡ soar-engine"]
    D --> E["🩹 Auto-Patch-AI"]
    D -.->|always on| F["📊 cve-watch"]

    style A fill:#0d1117,stroke:#00ff41,color:#00ff41
    style B fill:#0d1117,stroke:#00ff41,color:#00ff41
    style C fill:#0d1117,stroke:#58a6ff,color:#58a6ff
    style D fill:#0d1117,stroke:#f85149,color:#f85149
    style E fill:#0d1117,stroke:#3fb950,color:#3fb950
    style F fill:#0d1117,stroke:#d29922,color:#d29922
```

<br/>

| Stage | Tool | What it does |
|:---:|---|---|
| 🔍 Recon | **[OSINT-Leak-Radar](https://github.com/X-Abhishek-X/OSINT-Leak-Radar)** | Queries Wayback Machine CDX for `.env` files, SQL dumps, and private keys crawled years ago |
| 📡 Audit | **[wifi-security-auditor](https://github.com/X-Abhishek-X/wifi-security-auditor)** | WPA/WPA2 audit — OUI vendor lookup, WPS detection, PMKID capture without deauthentication |
| 🔬 Investigate | **[forensic-timeline-builder](https://github.com/X-Abhishek-X/forensic-timeline-builder)** | SSH log collection → unified timeline → auto-detection of brute force and privilege escalation |
| ⚡ Respond | **[soar-engine](https://github.com/X-Abhishek-X/soar-engine)** | FastAPI webhook → Redis queue → Celery workers. Async playbooks: VirusTotal enrichment + firewall block + Slack |
| 🩹 Patch | **[Auto-Patch-AI](https://github.com/X-Abhishek-X/Auto-Patch-AI)** | Trivy scans container → LLM (Groq free / OpenAI) writes patched Dockerfile. Free to run. |
| 📊 Monitor | **[cve-watch](https://github.com/X-Abhishek-X/cve-watch)** | NVD + EPSS enrichment. Ranks by `cvss × exploit_probability` — not just severity theatre |

<br/>

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/X-Abhishek-X/X-Abhishek-X/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/X-Abhishek-X/X-Abhishek-X/output/snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/X-Abhishek-X/X-Abhishek-X/output/snake.svg" />
  </picture>
</div>

<br/>

---

### Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=X-Abhishek-X&show_icons=true&theme=github_dark&hide_border=true" />
  &nbsp;
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=X-Abhishek-X&layout=compact&theme=github_dark&hide_border=true" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=X-Abhishek-X&theme=github-compact&hide_border=true&area=true&color=00ff41&line=00ff41&point=ffffff" />
</div>

<br/>

---

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

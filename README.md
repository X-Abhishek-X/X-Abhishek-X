<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3500&pause=800&color=00FF41&center=true&vCenter=true&random=false&width=700&lines=Security+Engineer+%2F+Automation+Dev;I+build+tools+that+catch+threats;Detect+%E2%86%92+Respond+%E2%86%92+Patch+%E2%86%92+Monitor;EPSS+%C3%97+CVSS+%3D+what%27s+actually+on+fire" alt="Typing SVG" />

</div>

<p align="center"><i>Building security automation that actually gets deployed — not just demo'd.</i></p>

<br/>

---

### The pipeline

Six tools. One workflow. Built from scratch.

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

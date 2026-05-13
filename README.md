<div align="center">

```
██╗  ██╗██╗   ██╗███╗   ██╗████████╗███████╗██████╗
 ██║  ██║██║   ██║████╗  ██║╚══██╔══╝██╔════╝██╔══██╗
 ███████║██║   ██║██╔██╗ ██║   ██║   █████╗  ██████╔╝
 ██╔══██║██║   ██║██║╚██╗██║   ██║   ██╔══╝  ██╔══██╗
 ██║  ██║╚██████╔╝██║ ╚████║   ██║   ███████╗██║  ██║
 ╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═══╝   ╚═╝   ╚══════╝╚═╝  ╚═╝
```

**`Hunter B. Franklin`** · Computer Science @ Oregon State

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hunterbfranklin/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hunterfranklinb@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HunterBFranklin)

</div>

## about me

Computer Science student at Oregon State University with a focus in **cybersecurity**. I'm building toward a role in network or cloud security, and ultimately a commission as a **Cyber Officer in the United States Air Force**. My work lives at the intersection of hands-on systems engineering and low-level security tooling.

When I'm not in the lab, I'm studying for certs, writing Python, and building the kind of tools I actually want to use.

## hunter's roadmap

```
 [NOW]──────────────────────────────────────────────────────────────────▶
   │
   ├─ 🔨  HelmSIEM v3.0          self-hosted SIEM on Wazuh + Elasticsearch
   │       └─ next: Suricata integration · Twilio SMS alerting
   │
   ├─ 📜  Cyber Certifications    CompTIA Security+ → Network+ → CySA+
   │
   ├─ 💼  Cybersecurity Role      internship or entry-level SOC / cloud sec
   │
   └─ ✈️   USAF Cyber Officer     commission as a cyber warfare officer
```

## featured project

### 🪖 HelmSIEM
> *A self-hosted, open-source SIEM system built for real threat detection — not a toy.*

HelmSIEM is a full security information and event management pipeline running on **Wazuh 4.14.5**, **Elasticsearch**, and **Docker**, monitored by a Python automation layer I wrote from scratch. It watches a MacBook Pro M3 and Ubuntu 22.04 ARM64 VM, fires tiered email alerts across three severity levels (critical · high · all), and delivers a daily HTML recap at 8 PM PST.

```
Wazuh 4.14.5  ──▶  Elasticsearch  ──▶  Python Layer  ──▶  Gmail SMTP
   (agents)          (indexing)        (query + triage)    (HTML reports)

Monitored endpoints:  MacBook Pro M3  ·  Ubuntu 22.04 LTS ARM64 (UTM)

Alert tiers:          Critical (12–15)  ·  High (7–11)  ·  All (1+)
```

**Stack:** Python 3 · Wazuh · Elasticsearch · Docker · Gmail SMTP · `requests` · `schedule` · `python-dotenv`

**Coming next:**
- `[ ]` Suricata network-layer detection
- `[ ]` Twilio SMS for critical-only alerts
- `[ ]` `docker-compose.yml` one-command spin-up

[![View Repo](https://img.shields.io/badge/github-helm--siem-181717?style=flat-square&logo=github)](https://github.com/HunterBFranklin/helm-siem)

## on deck

### 🔒 Hazy's Keep *(coming soon)*
> A self-hosted, end-to-end encrypted alternative to Google Keep — your notes, your server, your keys.

Zero-knowledge architecture with client-side encryption via the Web Crypto API. Built with React, Tailwind CSS, and Supabase. Designed to be deployable via Docker with a single command.

## currently learning

| track | resource |
|---|---|
| Cybersecurity fundamentals | [roadmap.sh/cybersecurity](https://roadmap.sh/cybersecurity) |
| Google Cybersecurity Certificate | [Coursera / Google](https://grow.google/certificates/cybersecurity/) |
| CCNA prep | Cisco Networking Academy |
| Backend development | [boot.dev](https://boot.dev) |
| Network intermediate | self-study / lab work |
| Languages in progress | Lua · JavaScript · Rust |

---

## stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3AABFF?style=flat-square&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<div align="center">
  <sub>hunterfranklinb@gmail.com · Portland, OR · open to cybersecurity internships & entry-level roles</sub>
</div>

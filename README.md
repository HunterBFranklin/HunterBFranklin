<br>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=28&duration=3000&pause=800&color=FFFFFF&center=true&vCenter=true&width=700&lines=Hunter+B.+Franklin;CS%3A+Cybersecurity+%40+Oregon+State;Nice+to+Meet+You+%F0%9F%A4%9A">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=28&duration=3000&pause=800&color=000000&center=true&vCenter=true&width=700&lines=Hunter+B.+Franklin;CS%3A+Cybersecurity+%40+Oregon+State;Nice+to+Meet+You+%F0%9F%A4%9A">
  <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=28&duration=3000&pause=800&color=000000&center=true&vCenter=true&width=700&lines=Hunter+B.+Franklin;CS%3A+Cybersecurity+%40+Oregon+State;Nice+to+Meet+You+%F0%9F%A4%9A">
</picture>

</div>
<br>
<div align="center">

> 🔍 **Open to cybersecurity internships and entry-level roles**; network security, cloud security, or SOC.
> Actively pursuing CompTIA Security+, CCNA, and Google Cybersecurity Certificate. <br>
> 📓 [Hunter Franklin, 2026: Resume](https://github.com/user-attachments/files/27699724/Hunter.Franklin.04_2026.-.Resume.copy.pdf) <br>

</div>

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
> A self-hosted, open-source SIEM system built for real threat detection.

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

[→ github.com/HunterBFranklin/helm-siem](https://github.com/HunterBFranklin/helm-siem)

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


## stack

[![My Skills](https://skillicons.dev/icons?i=py,js,rust,html,css,nodejs,flask,react,docker,linux,git,github)](https://skillicons.dev)

<div align="center">
  <sub>hunterfranklinb@gmail.com · Portland, OR · open to cybersecurity internships & entry-level roles</sub>
</div>

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

> 🔍 **Open to cybersecurity internships and entry-level roles**; network security, cloud security, or SOC. <br>
> Actively studying for CompTIA Security+ and Google Cybersecurity Certificate. <br>
> 📓 [Hunter Franklin, 07/2026 Resume](https://github.com/user-attachments/files/30632317/Hunter.Franklin.07_2026.-.Resume.IT.pdf) <br>

</div>

## Recent Projects

### 07/2026: Network Security Auditing Tool 
> A tool that I created after my completion of CS 372 and personal research to better protect my personal data online. It's a lightweight Bash script for auditing network security on macOS. Designed for use with a VPN and DNS-over-HTTPS setup, it passively captures and analyzes live traffic to check for common privacy leaks.

[→ github.com/HunterBFranklin/network-audit-tool](https://github.com/HunterBFranklin/network-audit-tool)

## Featured Project

### 🪖 HelmSIEM (in progress)
> A self-hosted, open-source SIEM system built for live endpoint threat detection.

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

## stack

[![My Skills](https://skillicons.dev/icons?i=py,js,rust,html,css,nodejs,flask,react,docker,linux,git,github)](https://skillicons.dev)

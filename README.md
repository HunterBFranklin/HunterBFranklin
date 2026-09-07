<br>
<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=28&duration=3000&pause=800&color=FFFFFF&center=true&vCenter=true&width=700&lines=Hunter+B.+Franklin;CS%3A+Cybersecurity+%40+Oregon+State;Aspiring+Air+Force+17SX;Nice+to+meet+you!+%F0%9F%91%8B">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=28&duration=3000&pause=800&color=000000&center=true&vCenter=true&width=700&lines=Hunter+B.+Franklin;CS%3A+Cybersecurity+%40+Oregon+State;Aspiring+Air+Force+17SX;Nice+to+meet+you!+%F0%9F%91%8B">
  <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=28&duration=3000&pause=800&color=000000&center=true&vCenter=true&width=700&lines=Hunter+B.+Franklin;CS%3A+Cybersecurity+%40+Oregon+State;Aspiring+Air+Force+17SX;Nice+to+meet+you!+%F0%9F%91%8B">
</picture>

</div>
<br>
<div align="center">

🔍 **Open to cybersecurity or IT internships**; interested in network security, cloud security, or SOC.\
:bust_in_silhouette: LinkedIn: [Hunter B. Franklin](https://www.linkedin.com/in/hunterbfranklin/) | :page_facing_up: Resume: [09/2026 Resume](https://github.com/user-attachments/files/31926861/Hunter.Franklin.08.2026.-.Resume.pdf)

</div>

## Recent Projects

### 09/2026: Live Network and .PCAP File Analyzer
> A custom-built network analysis tool created to process live interfaces or previously captured `.pcap` files. Designed from scratch in Python to avoid relying on heavy external IDS engines like `Zeek` or `Suricata`, this tool serves as an underlying microservice for my **HelmSIEM** project (targeted for containerized Kubernetes deployment). It performs core behavioral analysis, including Command and Control (C2) beaconing detection, DNS anomaly/DGA scoring, and threat intelligence lookups against live blocklists.\

[→ github.com/HunterBFranklin/pcap-analyzer](https://github.com/HunterBFranklin/pcap-analyzer)

### 07/2026: Network Security Auditing Tool 
> A tool that I created after my completion of CS 372 and personal research to better protect my personal data online. It's a lightweight Bash script for auditing network security on macOS. Designed for use with a VPN and DNS-over-HTTPS setup, it passively captures and analyzes live traffic to check for common privacy leaks.\

[→ github.com/HunterBFranklin/network-audit-tool](https://github.com/HunterBFranklin/network-audit-tool)

## Featured Project

### 🪖 HelmSIEM (Portfolio Project)
> A self-hosted, open-source SIEM system built for live endpoint threat detection.

HelmSIEM is a full security information and event management pipeline running on **Wazuh 4.14.5**, **Elasticsearch**, and **Docker**, monitored by a Python automation layer I wrote from scratch. It watches a MacBook Pro M3 and Ubuntu 22.04 ARM64 VM, fires tiered email alerts across three severity levels (critical · high · all), and delivers a daily HTML recap at 8 PM PST. I plan to add network analysis alerting, AI alert triage, traceroute, and a UI.

```
Wazuh 4.14.5  ──▶  Elasticsearch  ──▶  Python Layer  ──▶  Gmail SMTP
   (agents)          (indexing)        (query + triage)    (HTML reports)

Monitored endpoints:  MacBook Pro M3  ·  Ubuntu 22.04 LTS ARM64 (UTM)

Alert tiers:          Critical (12–15)  ·  High (7–11)  ·  All (1+)
```

**Current Stack:** Python 3 · Wazuh · Elasticsearch · Docker · Gmail SMTP · `requests` · `schedule` · `python-dotenv`

[→ github.com/HunterBFranklin/helm-siem](https://github.com/HunterBFranklin/helm-siem)

## Currently Learning

I am currently focusing on TryHackMe's 'Cyber Security 101' learning path, GitHub's 'Github Foundations' certification, and Roadmap.sh's 'Cyber Security Expert' learning roadmap. In addition, I am starting my background research for a portfolio project for Air Force Cyber Officer Commissioning and working on various projects like HelmSIEM and an AI/ML project.

## Stack

[![My Skills](https://skillicons.dev/icons?i=py,js,html,css,nodejs,npm,flask,react,docker,kubernetes,bash,powershell,mongodb,supabase,vercel,linux,pycharm,git,github)](https://skillicons.dev)

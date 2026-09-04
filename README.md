<h1 align="center">Shawn Falconbury</h1>

<p align="center">
  <b>Network Engineer</b> — Cisco VoIP/CUCM, enterprise infrastructure automation, IoT<br>
  <sub>Huntsville, AL</sub>
</p>

<p align="center">
  <a href="https://shawn.0x5.net"><img src="https://img.shields.io/badge/Site-shawn.0x5.net-1f6feb?style=flat-square&logo=firefoxbrowser&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/wfalconbury/"><img src="https://img.shields.io/badge/LinkedIn-wfalconbury-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://orcid.org/0000-0003-0719-0233"><img src="https://img.shields.io/badge/ORCID-0000--0003--0719--0233-a6ce39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID"></a>
</p>

---

I build automation for networks that people depend on, and I write down what
went wrong. Most of my repositories exist because the obvious implementation
was wrong in a way that still reported success — those cases get documented at
the point where the mistake would otherwise be made.

**What I care about in a tool:** it fails loudly, it is testable without the
hardware it manages, and the reasoning behind it survives me leaving the room.

---

### Focus areas

| | |
|---|---|
| **Unified Communications** | CUCM administration, CDR analysis, Q.931 cause-code forensics, VoIP/SIP troubleshooting |
| **Network Automation** | Ansible, Python, SNMPv3, configuration management, compliance baselining |
| **Infrastructure Monitoring** | Grafana, UniFi, SNMP polling, alerting, silent-failure detection |
| **IoT & Embedded** | LoRaWAN, sensor networks, RAK4631, Arduino/PlatformIO |

---

### Featured work

#### [`ansible-library`](https://github.com/Shawn-Falconbury/ansible-library) &nbsp;·&nbsp; ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

Clean-room reference implementations of network and systems automation, paired
with a catalogue of **18 documented failure modes that produce a passing
result**. No real address, hostname, or credential has ever been committed, and
CI enforces that on every push — the leak scanner is itself tested against
planted leaks before its clean verdict is trusted.

> The single most useful file is [`docs/gotchas.md`](https://github.com/Shawn-Falconbury/ansible-library/blob/main/docs/gotchas.md).

#### [`cucm-cdr-reporter`](https://github.com/Shawn-Falconbury/cucm-cdr-reporter) &nbsp;·&nbsp; ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

Parses Cisco CUCM Call Detail Records and generates failed-call reports with
Q.931 cause-code analysis — turning raw CDR exports into something a support
desk can act on.

#### [`mcp-server`](https://github.com/Shawn-Falconbury/mcp-server) &nbsp;·&nbsp; ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Custom Model Context Protocol server exposing filesystem, system, Obsidian,
SQLite, and UniFi controller operations to Claude over authenticated HTTPS.
Command whitelisting is explicit; nothing is reachable by default.

#### [`cisco-ios-config-backup`](https://github.com/Shawn-Falconbury/cisco-ios-config-backup) &nbsp;·&nbsp; ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

Automated IOS configuration backup driven over SNMPv3 with SCP transfer, so
neither the trigger nor the transfer crosses the network in the clear.

#### [`rak4631-lorawan-sensor`](https://github.com/Shawn-Falconbury/rak4631-lorawan-sensor) &nbsp;·&nbsp; ![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

Battery-efficient LoRaWAN node: environmental sensing plus GPS tracking, built
around duty-cycle budgets rather than convenience.

---

<details>
<summary><b>Everything else</b> — subnet math, system maintenance, workflow automation, R</summary>

<br>

| Repository | Language | What it is |
|---|---|---|
| [netip-subnet-calculator](https://github.com/Shawn-Falconbury/netip-subnet-calculator) | Java | Cross-platform IPv4/IPv6 subnet calculator with a GUI |
| [linux-system-updater](https://github.com/Shawn-Falconbury/linux-system-updater) | Shell | Debian maintenance with health checks and logging |
| [n8n-workflows](https://github.com/Shawn-Falconbury/n8n-workflows) | JSON | Home-lab and network-management automation workflows |
| [human-typer](https://github.com/Shawn-Falconbury/human-typer) | Python | Keystroke simulator with human-like timing and corrections |
| [r-data-analysis-examples](https://github.com/Shawn-Falconbury/r-data-analysis-examples) | R | Fundamental data-analysis techniques, tidyverse |

</details>

---

### Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)

![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Cisco](https://img.shields.io/badge/-Cisco%20IOS%20%2F%20CUCM-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![UniFi](https://img.shields.io/badge/-UniFi-0559C9?style=flat-square&logo=ubiquiti&logoColor=white)
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

![SNMPv3](https://img.shields.io/badge/-SNMPv3-555?style=flat-square)
![LoRaWAN](https://img.shields.io/badge/-LoRaWAN-555?style=flat-square)
![SIP](https://img.shields.io/badge/-VoIP%20%2F%20SIP-555?style=flat-square)
![SCP](https://img.shields.io/badge/-SCP-555?style=flat-square)
![MCP](https://img.shields.io/badge/-MCP-555?style=flat-square)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shawn-Falconbury&layout=compact&langs_count=8&hide_border=true&bg_color=00000000&title_color=1f6feb&text_color=808080" alt="Top languages">
</p>

---

<p align="center"><i>Building reliable network infrastructure, one script at a time.</i></p>

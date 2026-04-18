# jean-SIEM — Network Architecture Diagram

> Interactive dark/neon network diagram of my SOC Home Lab infrastructure.

## 🔍 Live Demo
👉 [View Diagram](https://jeanc00.github.io/jean-siem-diagram)

---

## 🏗 Architecture Overview

| Component | Details |
|---|---|
| **Host** | iMac i7-10700K · 64GB RAM · macOS |
| **Hypervisor** | VMware Fusion |
| **Firewall / IDS** | pfSense + Suricata (EVE JSON → Splunk) |
| **SIEM** | Splunk Enterprise + Wazuh |
| **AD / DNS** | Windows Server 2025 · DC01 · lab.local |
| **Endpoints** | WIN11-USER01/02 · EXEC-USER03/04 |
| **Blue Team** | Kali Linux · jean-blue · 10.10.50.100 |
| **Red Team** | Kali Linux (Internal + External) |
| **Threat Intel** | VirusTotal API · Hash Reputation |

## 🌐 VLAN Segmentation

| VLAN | Segment | Range |
|---|---|---|
| 10 | Management | 10.10.10.0/24 |
| 20 | Users | 10.10.20.0/24 |
| 30 | Executive | 10.10.30.0/24 |
| 40 | Servers | 10.10.40.0/24 |
| 50 | SOC | 10.10.50.0/24 |

---

## 🛠 Built With
- HTML · CSS · SVG animations · No frameworks

---

> Part of [SOC-Home-Lab](https://github.com/Jeanc00/SOC-Home-Lab) · Jean Carlos Urbaez · Paterson, NJ

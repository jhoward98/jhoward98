# 👋 Hey, I'm Joshua Howard

### Cybersecurity Student → SOC Analyst | Junior DevSecOps Engineer
**University of Arizona | BAS Cyber Operations Defense and Forensics**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Joshua%20Howard-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joshuawilliamhoward/)
[![Security+](https://img.shields.io/badge/CompTIA%20Security%2B-In%20Progress-FF0000?style=for-the-badge&logo=comptia&logoColor=white)](https://www.comptia.org/certifications/security)
[![AZ-900](https://img.shields.io/badge/Microsoft%20AZ--900-On%20Roadmap-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/en-us/certifications/azure-fundamentals/)
[![University of Arizona](https://img.shields.io/badge/University%20of%20Arizona-BAS%20Cyber%20Operations-AB0520?style=for-the-badge&logo=academia&logoColor=white)](https://www.arizona.edu/)

---

## 🧠 About Me

I'm a final-year cybersecurity student at the University of Arizona building real-world SOC skills the hard way — by actually building a SOC.

Right now I'm in the middle of a full home Security Operations Center build using Security Onion 3.1.0, VMware Workstation, Sysmon, Elastic Agent, and Invoke-AtomicRedTeam. Not following a tutorial. Designing the architecture, troubleshooting the pipeline, running attack simulations, and documenting everything. The kind of work I want to do professionally, so I figured I'd start doing it now.

My target is entry-level SOC Analyst or Junior DevSecOps Engineer roles at defense contractors and federal cybersecurity organizations. I'm NSA CAE-CO aligned through my coursework at UA, which means the curriculum maps directly to the skills these organizations actually need.

When something breaks — and in this build, things break — I figure out why. That's the whole point.

> *"Every packet tells a story. I'm learning how to read them."*

---

## 🔨 What I'm Building Right Now

### 🏠 Home SOC Build — Security Onion 3.1.0
> **The flagship project. Everything else feeds into this.**

A fully functional home Security Operations Center built from scratch across two machines, documenting every phase for GitHub and LinkedIn.

**The Stack:**
- **Security Onion 3.1.0** — Standalone deployment on VMware, Oracle Linux 9.7, static IP, dual NIC (management + monitor), Kibana live
- **Windows 11 Enterprise Evaluation VM** — Endpoint with Sysmon v15.20 (SwiftOnSecurity config), Invoke-AtomicRedTeam v2.1.0, and Elastic Agent enrolled in Fleet
- **Pipeline Status** — HEALTHY. 4,879+ events flowing from endpoint to Kibana including 2,787 Sysmon operational events
- **Phase 3 (Active)** — Running MITRE ATT&CK attack simulations via Invoke-AtomicRedTeam, verifying detections in Security Onion Hunt and Alerts views

**Techniques being tested:**
| Technique | ID | Status |
|---|---|---|
| PowerShell Execution | T1059.001 | In Progress |
| Credential Dumping | T1003 | In Progress |
| Valid Accounts | T1078 | In Progress |

📁 [View the Repository →](https://github.com/jhoward98/home-soc-build)

---

## 💻 Tech Stack

### Security & Detection
![Security Onion](https://img.shields.io/badge/Security%20Onion-3.1.0-4A90D9?style=flat-square&logo=linux&logoColor=white)
![Elastic Stack](https://img.shields.io/badge/Elastic%20Stack-Kibana%20%7C%20Fleet-005571?style=flat-square&logo=elastic&logoColor=white)
![Sysmon](https://img.shields.io/badge/Sysmon-v15.20-0078D4?style=flat-square&logo=windows&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-Framework-FF0000?style=flat-square&logo=shield&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-Packet%20Analysis-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Invoke-AtomicRedTeam](https://img.shields.io/badge/Invoke--AtomicRedTeam-v2.1.0-CC0000?style=flat-square&logo=powershell&logoColor=white)

### Programming & Scripting
![Python](https://img.shields.io/badge/Python-Automation%20%7C%20Scripting-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-7.6.2-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Scripting-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

### Infrastructure & Platforms
![VMware](https://img.shields.io/badge/VMware%20Workstation-Pro%2026H1-607078?style=flat-square&logo=vmware&logoColor=white)
![Oracle Linux](https://img.shields.io/badge/Oracle%20Linux-9.7-F80000?style=flat-square&logo=oracle&logoColor=white)
![Windows](https://img.shields.io/badge/Windows%2011-Enterprise-0078D4?style=flat-square&logo=windows&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-Daily%20Driver-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

### Learning & Development Platforms
![TryHackMe](https://img.shields.io/badge/TryHackMe-Premium-212C42?style=flat-square&logo=tryhackme&logoColor=white)
![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-VIP%2B-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)

---

## 📁 Projects

### 🔴 [home-soc-build](https://github.com/jhoward98/home-soc-build)
**Home Security Operations Center — Security Onion 3.1.0**
Full SOC build from scratch. VMware infrastructure, endpoint telemetry pipeline, Sysmon configuration, Elastic Agent fleet enrollment, and MITRE ATT&CK attack simulations with documented detections. Built to demonstrate real-world SOC workflows for defense contractor and federal cybersecurity roles.
`Security Onion` `Elastic Stack` `Sysmon` `MITRE ATT&CK` `VMware` `PowerShell` `Python`

---

### 🐍 [caesar-cipher](https://github.com/jhoward98/caesar-cipher)
**Classic Substitution Cipher in Python**
A clean Python implementation of the Caesar Cipher demonstrating core encryption concepts. Simple, functional, and documented.
`Python` `Cryptography` `Fundamentals`

---

## 🎓 Education & Coursework

**University of Arizona**
BAS Cyber Operations Defense and Forensics — *Final Year*
NSA CAE-CO (Center of Academic Excellence in Cyber Operations) aligned curriculum

Relevant coursework:
- CYBV 400 — Active Cyber Defense (NSA CAE-CO aligned)
- Network Design and Security
- Digital Forensics
- Incident Response

---

## 🎯 What I'm Working Toward

| Goal | Status |
|---|---|
| Complete home SOC build and document on GitHub | 🔄 In Progress |
| Run MITRE ATT&CK simulations and verify detections | 🔄 In Progress |
| CompTIA Security+ SY0-701 | 📚 Studying |
| Microsoft AZ-900 | 🗓️ On Roadmap |
| Entry-level SOC Analyst or Junior DevSecOps role | 🎯 Target |

---

## 📊 GitHub Stats

![Joshua's GitHub Stats](https://streak-stats.demolab.com?user=jhoward98&theme=dark&hide_border=true)

---

## 🤝 Let's Connect

I'm actively looking for entry-level SOC Analyst and Junior DevSecOps Engineer opportunities, especially in defense contractor and federal cybersecurity environments. If you are working in that space or want to talk shop about Security Onion, MITRE ATT&CK, or building home labs that actually do something, let's connect.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-Joshua%20Howard-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joshuawilliamhoward/)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jhoward98&color=F05A28&style=flat-square&label=Profile+Views" alt="Profile Views" />
</p>

<p align="center"><i>Building in public. Learning by doing. One detection at a time.</i></p>
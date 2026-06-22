# 📚 The Red, Blue, and Purple Team Operator's Bookshelf

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ameer-18-star/Red_Blue_Purple_Team_Operators_Bookshelf/graphs/commit-activity)

> *"The art of war teaches us to rely not on the likelihood of the enemy's not coming, but on our own readiness to receive him."* — **Sun Tzu**

A living, meticulously curated bibliography of essential literature for cybersecurity practitioners. Whether you break systems, defend networks, or build the feedback loops in between, this repository serves as your career-long reference guide.

---

## 🧭 The Triad at a Glance

| Domain | Posture | Core Objective | Primary Tradecraft |
| :--- | :--- | :--- | :--- |
| 🔴 **Red Team** | Offensive | Emulate adversaries to stress-test detection controls | Exploit Dev, C2 Infrastructure, Covert Entry, Social Engineering |
| 🔵 **Blue Team** | Defensive | Deny, detect, withstand, and eradicate intrusions | DFIR, SOC Operations, Threat Hunting, Network Hardening |
| 🟣 **Purple Team** | Fusion | Maximize ROI of security controls via iterative testing | Detection Engineering, Breach & Attack Simulation, Threat Intel |

---

## 📋 Table of Contents

1. [🔴 Red Team (Offensive Operations)](#-red-team-offensive-operations)
2. [🔵 Blue Team (Defensive Operations)](#-blue-team-defensive-operations)
3. [🟣 Purple Team (Adversary Emulation & Fusion)](#-purple-team-adversary-emulation--fusion)
4. [🧠 Foundational Core (Pre-Specialization)](#-foundational-core-pre-specialization)
5. [🎯 Suggested Reading Tracks](#-suggested-reading-tracks)
6. [🤝 How to Contribute](#-how-to-contribute)

---

## 🔴 Red Team (Offensive Operations)

### Initial Access & Web Tradecraft
* **[The Web Application Hacker's Handbook (2nd Ed)](https://www.wiley.com/)** — *Dafydd Stuttard & Marcus Pinto* 
  > The undisputed "Old Testament" of web application pentesting. While web tech has evolved, the core logic of finding input validation flaws remains unchanged.
* **[Real-World Bug Hunting: A Field Guide to Web Hacking](https://nostarch.com/realworldbughunting)** — *Peter Yaworski*
  > Excellent, highly digestible breakdowns of actual crowd-sourced vulnerability reports. 

### Network, Infrastructure & C2
* **[The Hacker Playbook 3: Practical Guide to Penetration Testing](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1980901795)** — *Peter Kim*
  > Focuses heavily on Red Team campaigns, setting up redirectors, custom payloads, and lateral movement.
* **[Red Team Development and Operations](https://redteam.guide/)** — *Joe Vest & James McQuiggan*
  > Moves past "just getting root" to teach the *management, scoping, and execution* of a professional threat emulation campaign.

### Evasion & Advanced Exploit Dev
* **[Evading EDR: The Definitive Guide to Bypassing Endpoint Detection](https://nostarch.com/evading-edr)** — *Matt Hand*
  > A masterclass for intermediate operators on how Windows internals interact with user-mode hooks, ETW, and kernel callbacks.

---

## 🔵 Blue Team (Defensive Operations)

### Security Operations & Analysis
* **[Crafting the InfoSec Playbook](https://www.oreilly.com/library/view/crafting-the-infosec/9781491944420/)** — *Jeff Bollinger, Brandon Enright, & Matthew Valites*
  > Teaches analysts how to take raw telemetry and turn it into actionable, high-fidelity alerting logic.
* **[Blue Team Handbook: Incident Response Edition](https://www.amazon.com/Blue-Team-Handbook-condensed-frequently/dp/1494295504)** — *Don Murdoch*
  > The ultimate pocket reference guide to keep on your desk during an active 2:00 AM fire drill.

### Digital Forensics & Incident Response (DFIR)
* **[Incident Response & Computer Forensics (3rd Ed)](https://www.mheducation.com/)** — *Jason T. Luttgens, Matthew Pepe, & Kevin Mandia*
  > The gold standard textbook for managing the lifecycle of a major network intrusion.
* **[The Art of Memory Forensics](https://www.wiley.com/)** — *Michael Hale Ligh et al.*
  > Deep dive into Volatility, dissecting kernel memory, hidden rootkits, and injected DLLs. 

### Threat Hunting
* **[Practical Threat Hunting](https://www.oreilly.com/)** — *Carlos Diaz*
  > Teaches proactive data-interrogation techniques rather than sitting back and waiting for a SIEM dashboard to turn red.

---

## 🟣 Purple Team (Adversary Emulation & Fusion)

* **[Purple Team Strategies](https://www.packtpub.com/)** — *David Routin & Samuel T. S.*
  > Bridges the massive communication void that historically exists between offensive engineers and SOC analysts.
* **[Adversarial Tradecraft in Cybersecurity](https://www.packtpub.com/)** — *Dan Borges*
  > An incredible breakdown of how to build automated, safe, repeatable unit-tests for enterprise network defenses.
* **[Practical Threat Detection Engineering](https://www.packtpub.com/)** — *Megan Roddie, Jason Deyalsingh, & Kevin Gonzalez*
  > Focuses on writing detections as *code*, utilizing CI/CD pipelines to validate that your SIEM rules actually catch what they claim to catch.

---

## 🧠 Foundational Core (Pre-Specialization)

*Don't try to break or defend a stack you don't understand. Read these first:*

* **[Windows Internals, Part 1 & Part 2 (7th Ed)](https://learn.microsoft.com/en-us/sysinternals/resources/windows-internals)** — *Pavel Yosifovich et al.* (The definitive guide to the OS that powers 80% of corporate targets).
* **[TCP/IP Illustrated, Volume 1: The Protocols](https://www.pearson.com/)** — *W. Richard Stevens* (The Bible of packet-level networking).
* **[Practical Packet Analysis](https://nostarch.com/packetanalysis3)** — *Chris Sanders* (How to actually read Wireshark without getting overwhelmed).

---

## 🎯 Suggested Reading Tracks

### 1. The "Zero to SOC Analyst" Track
1. *Practical Packet Analysis* (Sanders)
2. *Blue Team Handbook* (Murdoch)
3. *Crafting the InfoSec Playbook* (Bollinger)

### 2. The "Modern Infrastructure Pentester" Track
1. *TCP/IP Illustrated* (Stevens)
2. *The Hacker Playbook 3* (Kim)
3. *Evading EDR* (Hand)

### 3. The "Assume Breach" Track (Purple)
1. *Windows Internals* (Yosifovich)
2. *Purple Team Strategies* (Routin)
3. *Practical Threat Detection Engineering* (Roddie)

---

# 🛡️ Cybersecurity Labs & Tool Practice  
**Self-Guided Learning & <a href="https://tryhackme.com/paths"> SOC Level 1 Training via TryHackMe </a>| 2025**

This repository documents my hands-on experience and practical learning journey through **TryHackMe** labs and the **SOC Level 1 – Junior Security Analyst** course. It covers foundational skills in **network forensics, intrusion detection, cyber defense frameworks, threat intelligence**, and **incident response**, aligned with real-world SOC operations.

---

## 🎯 Objectives
- Simulate real-world SOC operations  
- Develop familiarity with core defensive tools and techniques  
- Practice incident detection, response, and traffic analysis  

---

## 🧰 Tools Covered & Key Learnings

### 1. Cyber Defense Frameworks & Threat Intelligence

- **MITRE ATT&CK**
  - Mapped attacker behaviors (TTPs) observed in labs  (pyramid of pain , kill chain)
  - Linked attack steps to real-world APT tactics and mitigations  

- **OpenCTI**
  - Managed threat intelligence data (indicators, actors, campaigns)  
  - Visualized attack chains and relationships between threat entities  

### 2. Network Security & Traffic Analysis

- **Wireshark & TShark**
  - Analyzed PCAPs for suspicious patterns (e.g., brute-force, DNS tunneling)  
  - Extracted files and followed TCP/UDP streams  

- **Zeek**
  - Generated detailed network logs (`http.log`, `conn.log`, `dns.log`)  
  - Detected exfiltration activities through log parsing and generating zeek signatures 

- **NetworkMiner**
  - Performed passive network capture analysis  
  - Extracted transferred files, credentials, and metadata  

- **Brim**
  - Conducted high-level PCAP investigation integrated with Zeek logs  
  - Queried large capture datasets efficiently  

### 3. Intrusion Detection Systems

- **Snort**
  - Created and tested custom detection rules for port scans, reverse shells, and web shell traffic  
  - Operated Snort in alert modes with packet logging
  - created different sort rules . 

- **Zeek (IDS Role)**
  - Used scripting extensions and packages for passive detection and alert generation  

---

## 🧠 Skills Gained
- Network protocol analysis and pattern recognition  
- IDS configuration and alert tuning  
- Detection engineering basics  
- Threat hunting using logs and PCAP data  
- Building threat intelligence pipelines with open-source tools  

---

## 🚀 Current Status & Next Steps

- ✅ **Completed:**
  - Cyber Defense Frameworks  
  - Cyber Threat Intelligence  
  - Network Security & Traffic Analysis  

- 🔄 **In Progress:**
  - SIEM Tools & Log Analysis  
  - Endpoint Detection & Response (EDR)  

- 📈 **Progress:**
  - Ranked in the **Top 5%** of TryHackMe learners globally  
  - Updating this repository **weekly** as I work through the **SOC Level 1 – Junior Security Analyst** pathway  

---


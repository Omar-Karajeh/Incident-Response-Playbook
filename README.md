# SOC Incident Response Playbook
### Detection Engineering & Incident Analysis Framework

**Van Helsing Team | Green Circle × Q2Impact**  
**Ranked #1 among all competing groups**

---

## Overview

A hands-on incident response playbook covering 25 real-world attack scenarios across Windows, Active Directory, Linux, and Web environments. Every alert was built, triggered, and documented in a live lab using Splunk as the primary SIEM.

This is not a theoretical document. Each playbook entry includes a working Splunk detection query, a dashboard screenshot, attacker simulation steps, and a full IR lifecycle (Preparation → Detection → Containment → Eradication → Recovery → Lessons Learned).

---

## Coverage

| Category | Scenarios | Examples |
|----------|-----------|---------|
| Windows | 5 | Brute Force, RDP Access, Registry Persistence, Privilege Escalation, Scheduled Task |
| Active Directory | 5 | Log Clearing, NTDS Extraction, WMI Lateral Movement, SMB Enumeration, Service Creation |
| Linux (Kali) | 10 | Root Elevation, Crontab Modification, Symlink Hijacking, SUID Discovery, Firewall Evasion |
| Web (DVWA) | 5 | SQL Injection, XSS, LFI/Directory Traversal, Directory Brute Force, DoS |

---

## What Each Playbook Entry Contains

- **Incident Classification** — Severity, MITRE ATT&CK mapping, detection sources
- **Splunk Alert Rule** — Working SPL query used in the lab
- **Dashboard View** — Screenshot of the triggered alert
- **IR Phases** — Preparation, Detection & Analysis, Containment, Eradication, Recovery, Lessons Learned
- **Success Metrics** — MTTD and MTTC targets
- **Analysis Q&A** — Interview-style questions with answers

---

## MITRE ATT&CK Coverage

`T1110` Brute Force · `T1053` Scheduled Tasks/Cron · `T1547` Registry Persistence  
`T1078` Privilege Escalation · `T1021` Remote Services (RDP/SSH/WMI)  
`T1070` Defense Evasion · `T1003` Credential Dumping (NTDS)  
`T1135` Network Share Discovery · `T1190` Exploit Public-Facing Application  
`T1040` Network Sniffing · `T1036` Masquerading · `T1498` DoS

---

## Tools & Technologies Used

- **SIEM:** Splunk Enterprise (alert creation, dashboards, SPL queries)
- **Target Environments:** Windows 10, Windows 11, Active Directory (test.local), Kali Linux, DVWA
- **Forensics:** Wireshark, Volatility, auditd, Windows Event Logs
- **Attack Simulation:** Hydra, Mimikatz (simulated), WMI, native OS tools

---

## Team

| Name |
|------|
| Omar Ahmad Ismail Karajeh |
| Mohammed Waleed Mohammed Khalaf |
| Neam Anwar Mohammed Alhadithi |
| Areej Usama Mouayad Al-dobagh |
| Ayat Haitham Khalaf Al-Hamimat |

**Supervisor:** Eng. Tareq Obeidat  
**Program:** SOC Analyst Training — Green Circle × Q2Impact  
**Date:** February 2026

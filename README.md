# wazuh-siem-soc-lab
SOC SIEM lab using Wazuh on Kali Linux with Windows 10 endpoint monitoring and File Integrity Detection

# Wazuh SIEM SOC Lab – File Integrity Monitoring & Threat Detection

## Overview
This project demonstrates a fully functional Security Operations Center (SOC) lab built using Wazuh SIEM.  
The lab monitors a Windows 10 endpoint from a Kali Linux SIEM server and detects file tampering, deletions, and suspicious activity in real time.

This lab simulates how SOC analysts detect and investigate endpoint threats.

---

## Lab Architecture

| Component | Role |
|--------|------|
| Kali Linux | Wazuh Manager, Indexer, Dashboard |
| Windows 10 (VirtualBox) | Endpoint monitored by Wazuh |
| Network | Bridged adapter for real LAN communication |

---

## What This Lab Does
- Collects Windows endpoint telemetry  
- Monitors files in real time  
- Detects file creation, deletion, and modification  
- Generates SIEM alerts  
- Provides SOC dashboards and timelines  

---

## Key Features
- Wazuh Manager running on Kali Linux  
- Windows 10 agent securely enrolled  
- File Integrity Monitoring enabled  
- SOC dashboards and alert timelines  

---

## Why This Project Matters
This lab replicates how:
- Blue teams detect endpoint tampering
- SOC analysts investigate alerts
- SIEM platforms correlate security events

This is a real, operational SIEM environment.

---

## SIEM Evidence

![Agent](screenshots/<filename1>.png)
![FIM Events](screenshots/<filename2>.png)
![Dashboard](screenshots/<filename3>.png)
![Inventory](screenshots/<filename4>.png)
![Files](screenshots/<filename5>.png)
![Overview](screenshots/<filename6>.png)


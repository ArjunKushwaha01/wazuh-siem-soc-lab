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

### Windows Agent Connected
![Agent](screenshots/Windows%20agent%20connected.png)

### File Integrity Events
![FIM Events](screenshots/File%20integrity%20events.png)

### FIM Dashboard
![Dashboard](screenshots/FIM%20dashboard.png)

### Agent Inventory
![Inventory](screenshots/Agent%20inventory.png)

### Files Being Monitored
![Files](screenshots/Files%20monitored.png)

### Wazuh SOC Overview
![Overview](screenshots/Wazuh%20overview%20dashboard.png)


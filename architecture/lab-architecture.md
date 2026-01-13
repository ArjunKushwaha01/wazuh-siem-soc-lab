# SOC Lab Architecture

This lab implements a real-world SOC-style SIEM architecture.

Kali Linux hosts the Wazuh Manager, Indexer, and Dashboard.
Windows 10 runs the Wazuh agent and sends security telemetry.

All endpoint data flows securely from Windows to Kali for analysis and alerting.

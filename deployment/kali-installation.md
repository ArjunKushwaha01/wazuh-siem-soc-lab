# Wazuh Installation on Kali Linux

The Wazuh SIEM stack was installed on Kali Linux using the official Wazuh installation script.

curl -sO https://packages.wazuh.com/4.12/wazuh-install.sh
sudo bash ./wazuh-install.sh -a -i

This installed:
- Wazuh Manager
- Wazuh Indexer
- Wazuh Dashboard

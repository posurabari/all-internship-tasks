# nmap-network-scan-task
Nmap-based network port scanning using Kali Linux

##  Objective
To scan the local network using Nmap from a Kali Linux VM (running on VirtualBox) to detect active hosts and identify open/closed ports for security analysis.

## Tools Used
- Nmap
- Kali Linux (VirtualBox)
- Host OS: Windows/Linux

## Scan Details
- **IP Range Scanned:** 192.168.211.0/24
- **Scan Command Used:**
  ```bash
  nmap -sS 192.168.211.0/24 -oN scan_results.txt

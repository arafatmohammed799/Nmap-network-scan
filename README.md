# Nmap-network-scan
A simple Nmap project to demonstrate network scanning and vulnerability enumeration.
# Nmap-network-scan

A simple Nmap project to demonstrate network scanning and vulnerability enumeration.

## 🛠 Tools Used
- **Nmap** – for host discovery, port scanning, and service detection
- **Kali Linux** – OS used for testing
- **Local network (192.168.1.0/24)** – test environment

## 📸 Screenshot Output
Below is a sample output from the scan:

![Nmap Scan Result](Screenshot%202025-08-05%20143142.png)

## 🔍 Example Commands Used

```bash
Basic ping scan to find live hosts
nmap -sP 192.168.1.0/24

Aggressive scan with service detection
nmap -sV -T4 192.168.1.1

Scan all ports on a specific host
nmap -p- 192.168.1.1

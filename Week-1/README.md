# Week 1: Cybersecurity Lab Setup (Kali Linux Virtualization)

## Overview
This project documents my Week 1 lab setup for the **Networkwalks Cybersecurity Internship (Batch B084)**. I configured an isolated Kali Linux virtual machine environment to safely perform network reconnaissance, vulnerability scanning, and penetration testing labs without affecting my host network.

## Objectives Completed
- **Virtualization & Isolation:** Configured Kali Linux inside an isolated NAT network environment.
- **Network & IP Verification:** Confirmed active IPv4 address assignment and verified external internet connectivity (`ping 8.8.8.8`).
- **DNS Resolution:** Tested domain name resolution using `nslookup networkwalks.com`.
- **Backup & Recovery:** Created a clean VM snapshot (`Clean Kali Setup`) to serve as a safe restore point before running security tests.

## Commands Executed
```bash
# Check IP configuration
ip a

# Test external internet connectivity
ping -c 3 8.8.8.8

# Verify DNS resolution
nslookup networkwalks.com
```

## Verification Evidence
1. **`01-network-settings.png`** — Virtual machine network adapter configured in NAT mode.
2. **`02-ip-ping.png`** — Terminal output confirming IP assignment and 0% packet loss to `8.8.8.8`.
3. **`03-nslookup.png`** — Terminal output confirming DNS resolution for `networkwalks.com`.
4. **`04-vm-snapshot.png`** — Clean VM snapshot saved in the hypervisor snapshot manager.

## Author
- **Name:** Jai Bhushan Rane
- **Intern ID:** NW-084-3I7
- **Batch:** B084

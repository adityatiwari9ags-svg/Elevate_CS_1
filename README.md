
##  Objective
The goal of this task was to discover the local network range, perform a TCP scan using Nmap, identify open ports and services, and analyze potential security risks.

##  Tools Used
- Kali Linux VM
- Nmap
- (Optional) Wireshark

##  Steps Performed
1. Discovered local IP and network range using `ip a`.
2. Ran a TCP scan (`nmap -sT -sV 192.168.1.0/24`) to find open ports.
3. Noted IP addresses and the services running on open ports.
4. Assessed potential security risks for the discovered services.
5. Collected screenshots and outputs for evidence.

##  Repository Contents
- `report.docx` — Word report with steps, screenshots, findings, and risks.
- `results.txt` — raw Nmap scan output..

##  Findings (example)
Open ports observed: 23 (Telnet), 53 (DNS), 88 (Kerberos), 443 (HTTPS).  
Potential security risks: Telnet and Kerberos are high-risk; DNS and HTTPS require monitoring and proper configuration.

## 📖 Conclusion
This task demonstrates how to scan a local network, identify open ports and services, and evaluate network exposure risks.

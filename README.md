# Network-Security-Monitoring-Lab-
This project documents the setup and execution of virtual machines of Kali Linux and Ubuntu which were running on a local host machine, including both offensive and defensive systems. Nmap was utilized to perform active network scanning, identify open and closed ports, and enumerate running services on target systems. 
## TOOLS AND TECH
- **Kali Linux VM**
- **Ubuntu Server VM**
- **Nmap**
## OBJECTIVES
- Perform Nmap scans to identify live hosts and enumerate open/closed ports 
- Analyze identified services and detect potentially vulnerable services running on target systems 
- Gain hands-on experience using Nmap commands, flags, and scan types 
- Understand the security risks associated with exposed and unnecessary open ports
##  Nmap SCANNING FINDS
The Nmap scan performed from the Kali Linux VM identified multiple open ports on the Ubuntu Server VM, including:

| Port | Protocol | Service         | Description                         |
|:------|:-----------|:-----------------|:-------------------------------------|
| 80   | TCP       | HTTP             | Web server                           |
| 25565| TCP       | Minecraft        | Game server for Minecraft           |
| 554  | TCP       | RTS (Real Time Streaming) Client | Used for streaming protocols |
| 3128 | TCP       | HTTP Proxy       | Web proxy service                   |
| 465  | TCP       | CML Mail (SMTP over SSL) | Email transmission service   |
| 8080 | TCP       | Unknown          | Unidentified open service on alternate HTTP port |

Note: Additional closed ports and filtered states were detected during the scan.
## OUTCOMES
- Successfully identified open services operating on non-standard and potentially insecure ports 
- Gained practical experience performing Nmap service enumeration and interpreting scan results 
- Recognized the risks associated with unnecessary or poorly secured services running on networked systems 
- Learned to differentiate between common services, game servers, and unknown open ports during reconnaissance 

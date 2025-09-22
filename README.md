# network port scan results
this repository contains the results of network port scan of a metasploitable3 (vulnerable windows machine).I have practiced the NMAP TOOL on a Kali Linux machine. I have installed VMware Workstation. In VMware Workstation, I have installed Kali Linux and Metasploitable 3 (a vulnerable Windows machine) for testing.
## Scan Results 
The scan was perfomed using the following command:
nmap -sS 192.168.10.137(IP OF vulnerable windows machine)
nmap -sV 192.168.10.137 for service version detection
The results are saved in the "scan_results.txt"file.
### Open Ports and Potential Security Risks
The scan revealed the following open ports and potential security risks:
*Port 22: SSH:potential security include brute force attack,privilage escalation,malware upload by attacker
*Port 135: msrpc:potential security include Remote code execution,privilage escalation

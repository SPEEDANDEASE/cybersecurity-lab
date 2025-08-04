## Goal
Practice using Nmap to discover live hosts, detect open ports, and get comfortable with basic scanning techniques in a safe lab.


# Tools Used
- Kali Linux: Attacker machine
- Metasploitable 2: Target machine

# Scans Practiced
### 1. SYN Scan (-sS)
A half-open scan to find open TCP ports quickly.
`bash
nmap -sS <target IP>`

### 2.Ping Scan (-sn)
Find live hosts without scanning for open ports.
`bash
nmap -sn <target IP>`

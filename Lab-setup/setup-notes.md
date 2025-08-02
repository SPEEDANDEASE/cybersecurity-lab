# Lab Setup — Cybersecurity Practice Environment

#Goal
Build a secure, isolated virtual lab to practice real-world ethical hacking and penetration testing without risking my main machine or home network.


#Virtual Machines
- Kali Linux: Main attacker machine, pre-installed with tools like Metasploit, Nmap, Burp Suite, Hydra, and more.
- Metasploitable 2: Intentionally vulnerable Linux target for safe exploitation practice.
- Windows 8 VM: Additional target to practice privilege escalation, post-exploitation, and defense techniques.


#Network Configuration
- VirtualBox Host-Only Network: Fully isolated from the internet.
- Internal IP range: `192.168.x.x`
- Updates: Only the attacker VM has limited internet access for tool updates; targets stay offline.


#Current Status
-  All VMs installed, configured, and tested.
-  Verified network connectivity between Kali ↔ Metasploitable.
-  Snapshots created for easy rollback after exploits.


##  Next Steps
- Perform initial Nmap scans to discover services and open ports.
- Test first exploits using Metasploit.
- Document each tool, command, and result in dedicated folders.

##  Next Steps
- Basic scans with Nmap.
- Test exploits with Metasploit.
- Document each tool & result here step-by-step.

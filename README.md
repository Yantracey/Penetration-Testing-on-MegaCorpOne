# Penetration-Testing-on-MegaCorpOne

# Linux Machines #

In the Linux-focused segment of the engagement, I successfully completed the Shodan activity, leveraging Shodan.io for enumeration on MegaCorpOne. Registering for a Shodan.io account, I performed an nslookup on www.megacorpone.com, identified open ports, and gathered server information, including OS, web server version, and potential vulnerabilities. Additionally, I completed the Recon-ng activity, using Recon-ng and the Shodan API to test MegaCorpOne's domain server info accessibility. The subsequent phase involved a penetration test on MegaCorpOne's network, exploiting weak password security on vpn.megacorpone.com and conducting internal network scans. Further actions included exploiting a vulnerable service on Metasploitable2 and researching C2 frameworks suitable for the assessment. In the Metasploit Exploitation phase, I successfully executed various exploits and achieved a reverse shell on a host. Privilege Escalation and Password Cracking tasks followed, demonstrating a comprehensive exploration of vulnerabilities. Finally, in Persistence, I added an SSH port and created a backdoor account.

# Windows Machines #

Switching to the Windows-focused phase, I conducted a penetration test on MegaCorpOne's network, identifying Windows machines and executing a password spraying attack. LLMNR spoofing and Metasploit modules facilitated gaining unauthorized access and running commands on remote Windows machines. I then created, transferred, and executed a custom payload on a Windows machine, emphasizing privilege escalation and persistence. The subsequent Credential Dumping activities involved using Metasploit kiwi extension to dump cached credentials from a WIN10 machine, successfully cracking the password for the bbanner account. Lateral Movement and Credential Access tasks were executed to move from Windows10 to WINDC01, accessing the domain controller and attempting to crack password hashes. 

This assignment provided a comprehensive hands-on experience in penetration testing methodologies on both Linux and Windows environments within the MegaCorpOne infrastructure.

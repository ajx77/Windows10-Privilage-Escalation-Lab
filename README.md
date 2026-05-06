# 🖥️ Windows 10 Exploitation & Privilage Escalation Lab

## 🎯 Objective

Simulate a real-world Windows 10 compromise by performing enumeration, SMB exploitation, remote command execution, credential dumping, and privilege escalation in a controlled lab environment.

---

## ⚔️ Attack Chain

1. Host Discovery
2. Port & Service Enumeration
3. SMB Share Enumeration
4. Authenticated SMB Access
5. Remote Command Execution
6. Credential Dumping
7. NTLM Hash Extraction
8. Password Cracking
9. Privilege Escalation

---

# 🎯 Key Achievements

- Enumerated Windows 10 services and SMB shares
- Identified accessible SMB services on target machine
- Achieved remote shell access using Impacket SMBExec
- Dumped SAM and LSA credentials using SecretsDump
- Cracked NTLM password hashes using John the Ripper
- Obtained NT AUTHORITY\SYSTEM privileges

---

# 📌 Overview

This project demonstrates a complete Windows 10 exploitation workflow inside a self-hosted penetration testing lab. The attack chain simulates post-compromise activities including service enumeration, SMB interaction, remote execution, credential extraction, and privilege escalation techniques commonly used during internal penetration tests.

---

## 🏗️ Lab Environment

- Kali Linux (Attacker)
- Windows 10 Target Machine
- VirtualBox Internal Network
- SMB Enabled Environment

---

# 🛠️ Tools Used

- Nmap
- SMBClient
- Enum4Linux
- Impacket SMBExec
- Impacket SecretsDump
- John the Ripper
- Kali Linux

---

# 📸 Screenshots

## 🔎 Nmap Enumeration

Identified SMB, RPC, and Microsoft Windows services running on the Windows 10 target.

![Nmap Scan](screenshots/NmapWin10.png)

---

## 📂 SMB Enumeration

Enumerated SMB shares and verified accessible network resources.

![SMB Enumeration](screenshots/smbWin10.png)

---

## 🧭 Remote Shell via SMBExec

Achieved remote command execution and obtained NT AUTHORITY\SYSTEM shell access.

![SMBExec](screenshots/imp-smbexec.png)

---

## 🔍 Enum4Linux Enumeration

Performed SMB and workgroup enumeration against the target machine.

![Enum4Linux](screenshots/enu4linuxWin10.png)

---

## 🔐 Credential Dumping

Dumped SAM and LSA credential hashes using SecretsDump.

![SecretsDump](screenshots/imp-secretdumpWin10.png)

---

## 🔓 Password Hash Cracking

Cracked NTLM hashes using John the Ripper and recovered weak passwords.

![Hash Cracking](screenshots/hashcrackingWin10.png)

---

# ✅ Result

✔ Windows 10 machine successfully compromised  
✔ SYSTEM-level shell access obtained  
✔ Password hashes extracted and cracked  
✔ Full exploitation workflow demonstrated  

---

## 🧠 Skills Demonstrated

- Windows Enumeration
- SMB Exploitation
- Remote Command Execution
- Credential Dumping
- NTLM Hash Cracking
- Post-Exploitation
- Privilege Escalation Concepts
- Impacket Tool Usage

---

## ⚠ Disclaimer

This project was performed in a self-hosted isolated lab environment for educational and ethical penetration testing purposes only.

# 🛡️ Cybersecurity Labs For Testing

Welcome to my personal lab repository! This repository serves as an index and documentation hub for the various virtual machines, vulnerable applications, and environments I have tested, exploited, and documented. 

Whether you are a beginner looking for practice targets or a fellow CTF player, this list contains the labs I have successfully compromised.

---

## 🖥️ Virtual Machines (VMs)

Below is a list of the standalone vulnerable Virtual Machines I have tested. Click on the name of the VM to redirected to the download page.

| Lab Name | OS | Difficulty | Status | Notes / Key Vulnerabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Metasploitable 1](https://www.vulnhub.com/entry/metasploitable-1,28/)** | Linux | Beginner | ✅ Completed | Basic network services, default credentials. |
| **[Metasploitable 2](https://www.vulnhub.com/entry/metasploitable-2,29/)** | Linux | Beginner | ✅ Completed | Vsftpd backdoor, Samba, weak web apps. |
| **[Metasploitable 3](https://github.com/rapid7/metasploitable3)** | Windows/Linux | Intermediate | ✅ Completed | Jenkins, Tomcat, custom exploits. |
| **[Windows 7](https://gist.github.com/ProdeusUnity/9999870f3dc946774bd2f8d1ef59eb01)** | Windows | Beginner | ✅ Completed | EternalBlue (MS17-010), weak SMB configs. |
| **[Windows 11](https://www.microsoft.com/en-us/software-download/windows11)** | Windows | Advanced | ✅ Completed | Modern Windows defenses, privilege escalation. |
| **[DVWA](https://github.com/digininja/DVWA)** | Linux / PHP | Beginner | ✅ Completed | SQL Injection (SQLi), Cross-Site Scripting (XSS), Command Injection, File Inclusion (LFI/RFI). |
| **[OWASP Juice Shop](https://github.com/juice-shop/juice-shop)** | Node.js / Docker | Intermediate | ✅ Completed | Broken Access Control, XSS, SQLi, JWT flaws, Business Logic errors (OWASP Top 10). |


---

## 🧰 Testing Arsenal & Methodology

All virtual machines and web applications in this repository are tested using a structured, professional methodology.

**1. Scanning & Enumeration**
`Nmap`, `Rustscan`, `Gobuster`, `Nikto`

**2. Exploitation & Web Testing**
`Metasploit`, `Burp Suite`, `SQLmap`, `Searchsploit`

**3. Privilege Escalation**
`LinPEAS`, `WinPEAS`, manual SUID/Kernel enumeration, `GTFOBins`

---

## 📂 Writeup Location

This repository only contains safe download links for each testing machine. 
Writeups locations is at:
1. [Metasploitable-1](https://sh4d0wspl01t.github.io/0xWriteups/index.html)
2. [Metasploitable-2](https://sh4d0wspl01t.github.io/0xWriteups/index.html)
3. [Metasploitable-3](https://sh4d0wspl01t.github.io/0xWriteups/index.html)
4. [Windows 7](https://sh4d0wspl01t.github.io/0xWriteups/index.html)
5. [DVWA](https://sh4d0wspl01t.github.io/0xWriteups/index.html)
6. [OWASP Juice Shop](https://sh4d0wspl01t.github.io/0xWriteups/index.html)

---
*Disclaimer: All testing, exploitation, and analysis were performed in isolated, personal lab environments that I own or have explicit permission to test. This repository is strictly for educational purposes.*

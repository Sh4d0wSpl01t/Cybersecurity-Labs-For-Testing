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
| **[Windows 7]** | Windows | Beginner | ✅ Completed | EternalBlue (MS17-010), weak SMB configs. |
| **[Windows 11](https://www.microsoft.com/en-us/software-download/windows11)** | Windows | Advanced | ✅ Completed | Modern Windows defenses, privilege escalation. |
| **[DVWA]** | Linux / PHP | Beginner | ✅ Completed | SQL Injection (SQLi), Cross-Site Scripting (XSS), Command Injection, File Inclusion (LFI/RFI). |
| **[OWASP Juice Shop]** | Node.js / Docker | Intermediate | ✅ Completed | Broken Access Control, XSS, SQLi, JWT flaws, Business Logic errors (OWASP Top 10). |


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

## 📂 Repository Structure

As I continue to test more machines, this repository will be organized as follows:

- 📁 **/Windows** - Writeups for Windows 7, Windows 11, etc.
- 📁 **/Linux** - Writeups for Metasploitable 1, 2, 3, etc.
- 📁 **/Web-Apps** - Writeups for DVWA, Juice Shop, etc.
- 📁 **/Tools** - Custom scripts or notes for specific tools used in the labs.

---
*Disclaimer: All testing, exploitation, and analysis were performed in isolated, personal lab environments that I own or have explicit permission to test. This repository is strictly for educational purposes.*

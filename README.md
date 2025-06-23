# 🎯 OSCP-Preparation-Labs

This repository contains **step-by-step attack walkthroughs** and **privilege escalation techniques** performed in my local ethical hacking lab using:
- 🖥️ Kali Linux
- 🧱 Metasploitable2
- 🪟 Windows 7 / Windows 10
- 🐧 Ubuntu Server

## 🧰 Tools Used
- Nmap, Nikto, Gobuster, Metasploit, sqlmap, netcat
- Manual exploitation techniques
- Privilege escalation using SUID, cronjobs, kernel exploits

## 🔓 Labs Covered

| Lab Name | Target | Summary |
|----------|--------|---------|
| [vsftpd-backdoor.md](metasploitable2-vsftpd-backdoor.md) | Metasploitable2 | Exploited backdoor to gain shell |
| [samba-root-privesc.md](metasploitable2-samba-root.md) | Metasploitable2 | Used Samba exploit to get root |
| [cronjob-privesc.md](ubuntu-cronjob-privesc.md) | Ubuntu | Abused cron misconfig to escalate privileges |
| [windows-unquoted-path.md](windows7-unquoted-service-path.md) | Windows 7 | Privilege escalation via unquoted service path |

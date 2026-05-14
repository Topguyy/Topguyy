<div align="center">

```
████████╗ ██████╗ ██████╗  ██████╗ ██╗   ██╗██╗   ██╗██╗   ██╗
╚══██╔══╝██╔═══██╗██╔══██╗██╔════╝ ██║   ██║╚██╗ ██╔╝╚██╗ ██╔╝
   ██║   ██║   ██║██████╔╝██║  ███╗██║   ██║ ╚████╔╝  ╚████╔╝ 
   ██║   ██║   ██║██╔═══╝ ██║   ██║██║   ██║  ╚██╔╝    ╚██╔╝  
   ██║   ╚██████╔╝██║     ╚██████╔╝╚██████╔╝   ██║      ██║   
   ╚═╝    ╚═════╝ ╚═╝      ╚═════╝  ╚═════╝    ╚═╝      ╚═╝   
```

**`Topguyyy`** — Offensive Security · Active Directory · Red Team

[![HackTheBox](https://img.shields.io/badge/HackTheBox-Profile-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)](https://app.hackthebox.com/public/users/1981999)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-el-tobgui-/)

</div>

---

## whoami

```
> net user Topguyyy /domain

User    : Topguyyy
Degree  : B.Sc Cybersecurity — Faculty of Computers & Data Science, Alexandria University
Role    : Offensive Security Enthusiast
Focus   : Active Directory attacks, internal network pentesting
Location: Cairo, EG
Status  : Learning. Breaking. Improving.
```

I got into offensive security because I wanted to understand how things actually break, not just follow a checklist. Right now I'm deep into Active Directory and internal network pentesting, working my way through the CPTS path on HackTheBox. Every machine I solve gets a writeup, every module gets a deep-dive note. It's slower that way, but it sticks better.

---

## attack surface

```powershell
$focus = @(
    "Active Directory enumeration & abuse",
    "Kerberos attacks (Kerberoasting, AS-REP Roasting, Pass-the-Ticket)",
    "Lateral movement techniques (Pass-the-Hash, WMI, PSExec)",
    "Privilege escalation on Windows",
    "BloodHound / SharpHound attack path analysis",
    "LDAP, SMB, and RPC abuse"
)
```

---

## skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Frameworks & Platforms**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Security Tools**

![Nmap](https://img.shields.io/badge/Nmap-214478?style=flat-square&logo=nmap&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![BloodHound](https://img.shields.io/badge/BloodHound-FF0000?style=flat-square&logo=graphql&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![CrackMapExec](https://img.shields.io/badge/CrackMapExec-black?style=flat-square&logo=gnubash&logoColor=white)

---

## current grind

- [ ] Complete **CPTS** (HackTheBox Certified Penetration Testing Specialist)
- [ ] Write a writeup for every machine I solve along the way
- [ ] Build a home AD lab and document it properly
- [ ] Get comfortable with BloodHound attack path analysis

---

## writeups

I post a writeup for every HTB machine I finish — retired ones only, obviously. I try to explain the *why* behind each step, not just dump commands. Still early but the list is growing.

→ [`htb-writeups`](https://github.com/Topguyyy/htb-writeups)

---

## pentesting notes

One deep-dive note per CPTS module. I go further than what HTB covers — extra research, real-world context, things that didn't click at first, and resources I found along the way.

→ [`htb-pentesting-notes`](https://github.com/Topguyyy/htb-pentesting-notes)

---

## pinned projects (building as i go)

| Repo | What it covers |
|---|---|
| `htb-writeups` | HackTheBox writeups — one per machine, posted after retirement |
| `htb-pentesting-notes` | Deep-dive notes for every CPTS module, going beyond the material |
| `ad-lab-notes` | My home AD lab setup and attack scenarios |
| `kerberos-attacks-explained` | Breaking down Kerberoasting, AS-REP Roasting, ticket attacks |
| `windows-privesc-checklist` | Manual privesc checklist I actually use |

---

<div align="center">

*Cairo → root*

</div>

# TryHackMe — Offensive Security Roadmap

A single-page, cyberpunk-styled visual roadmap for learning offensive security through [TryHackMe](https://tryhackme.com). The page guides learners from zero knowledge to advanced penetration testing skills across seven structured phases.

---

## Overview

The roadmap is designed as a top-to-bottom learning path. Each phase builds on the previous one, with checkpoint milestones to validate progress before moving forward. Estimated completion times range from 3 months (beginner) to 12 months (full path).

---

## Phases

| # | Phase | Difficulty | Focus |
|---|-------|------------|-------|
| 01 | **Foundations** | Beginner | Linux, networking, web basics, cryptography |
| 02 | **Reconnaissance & Enumeration** | Easy | Passive recon, Nmap, web enumeration, service enumeration |
| 03 | **Exploitation Fundamentals** | Medium | Metasploit, password attacks, shells, CVE exploitation |
| 04 | **Web Application Attacks** | Medium–Hard | SQLi, XSS, file inclusion, IDOR, SSRF, Burp Suite |
| 05 | **Privilege Escalation** | Hard | Linux/Windows PrivEsc, Active Directory attacks |
| 06 | **Post-Exploitation & Pivoting** | Hard | Persistence, lateral movement, covering tracks |
| 07 | **CTF Labs & Practice Machines** | Easy–Advanced | Guided machines from Basic Pentesting to Holo Network |

---

## Checkpoints

- **After Phase 2:** Complete the THM "Pre-Security" learning path. You should be able to enumerate a target independently.
- **After Phase 4:** Complete THM's "OWASP Top 10" room and "Jr Penetration Tester" path. You should be able to find and exploit common web vulnerabilities.

---

## Recommended THM Learning Paths

```
Pre-Security → Jr Penetration Tester → Offensive Pentesting → Red Teaming
SOC Level 1  → CompTIA PenTest+ Path → OWASP Top 10
```

---

## Essential Tools Covered

| Tool | Category |
|------|----------|
| Nmap | Port Scanning |
| Gobuster / ffuf | Web Enumeration & Fuzzing |
| Metasploit | Exploitation |
| Burp Suite | Web Proxy |
| Hashcat / John the Ripper | Hash Cracking |
| Hydra | Brute Force |
| sqlmap | SQL Injection |
| Netcat | Shells |
| linPEAS / WinPEAS | PrivEsc Enumeration |
| BloodHound | Active Directory Mapping |
| Wireshark | Packet Analysis |
| impacket | AD Attacks |
| Evil-WinRM | Windows Shells |
| Chisel | Tunneling |

---

## Usage

Open `tryhackme-roadmap.html` directly in any modern browser — no build step or dependencies required. The page uses Google Fonts (loaded from CDN) for its cyberpunk aesthetic.

---

## After TryHackMe

Once the full roadmap is complete, the recommended next steps are:

- **HackTheBox (HTB)** — harder, more realistic machines
- **eJPT Certification** — entry-level penetration testing cert
- **OSCP / CEH** — industry-recognized offensive security certifications

---

> **Disclaimer:** This roadmap is for educational purposes only. Always hack ethically and only on systems you have explicit permission to test.

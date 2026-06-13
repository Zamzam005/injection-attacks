# Injection Attacks — Lab Writeups

## Overview
Practical web application penetration testing 
writeups for all injection-based vulnerabilities 
covered in the TCM Security Practical Bug Bounty 
course. Each lab includes:
- Step-by-step exploitation walkthrough
- Payloads used
- Screenshots as proof of concept
- Impact analysis
- Remediation recommendations

## Tester
- Name: Zamzam Hassan
- Focus: Web Penetration Testing
- OS: Kali Linux
- Tools: Burp Suite, ffuf, sqlmap, curl, 
  netcat, webhook.site

## Environment
- Target: localhost (Bug Bounty Labs)
- Setup: Docker (docker-compose)

## Labs Completed

### File Inclusion
- File Inclusion 0x01 — LFI with path traversal
- File Inclusion 0x02 — LFI with DB credentials disclosure
- File Inclusion 0x03 — LFI via API endpoint

### SQL Injection
- SQL Injection 0x01 — UNION-based SQLi
- SQL Injection 0x02 — Authentication bypass + Blind SQLi
- SQL Injection 0x03 — UNION-based + sqlmap automation
- SQL Injection 0x04 — Second Order SQL Injection

### Cross Site Scripting (XSS)
- XSS 0x01 — Reflected XSS
- XSS 0x02 — Stored XSS with cookie theft
- XSS 0x03 — Stored XSS with cookie exfiltration

### Command Injection
- Command Injection 0x01 — Basic command injection + RCE
- Command Injection 0x02 — Blind command injection
- Command Injection 0x03 — Reverse shell via awk injection

### Server Side Template Injection (SSTI)
- SSTI 0x01 — Twig SSTI to RCE
- SSTI 0x02 — Hidden parameter SSTI to RCE

### XML External Entity (XXE)
- XXE 0x01 — File disclosure via XXE

### Server Side Request Forgery (SSRF)
- SSRF 0x01 — Basic SSRF bypass internal protection
- SSRF 0x02 — Blind SSRF detected via webhook

## Tools Used
- Burp Suite Community — proxy, repeater, intruder
- ffuf — directory and parameter fuzzing
- sqlmap — automated SQL injection
- curl — HTTP testing and command injection
- netcat — reverse shell listener
- webhook.site — out-of-band detection
- vim/nano — XML and payload editing

## Skills Demonstrated
- HTTP request interception and manipulation
- OWASP Top 10 vulnerability identification
- Manual exploitation of complex vulnerabilities
- Automated tool usage (ffuf, sqlmap)
- Out-of-band detection techniques
- Reverse shell exploitation
- Professional vulnerability documentation

## Repository Structure
Each lab has its own folder containing:
- writeup.md — full exploitation walkthrough
- screenshots/ — proof of concept images

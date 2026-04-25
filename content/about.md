---
title: "About"
date: 2026-04-25
draft: false
showDate: false
showReadingTime: false
showAuthor: false
showTableOfContents: true
---

## Who I Am

I'm an offensive security analyst with a primary focus on **web and mobile API security**, actively expanding into **network exploitation** and **Active Directory attacks**.

My approach is hands-on and attacker-oriented. I don't stop at vulnerability discovery — I chain findings, follow the access, and push toward full compromise in controlled lab environments.

---

## What I Do

### Web & API Security

My core strength. I specialize in:

- Broken authentication & session management
- Broken access control — IDOR, privilege escalation, mass assignment
- Business logic flaws
- JWT misconfiguration (alg:none, key confusion, weak secrets)
- Input validation failures — SQLi, SSTI, XXE, SSRF

I intercept, analyze, and manipulate HTTP/S traffic using **Burp Suite** as my primary toolchain — inspecting request/response flows, modifying parameters, replaying attacks, and stress-testing edge cases in REST APIs.

### Mobile Application Security

I approach mobile testing from an **API-first perspective** — the app is an entry point into backend systems. My focus areas:

- Traffic interception via proxy setups (SSL pinning bypass)
- Authentication flow weaknesses
- Token handling and backend validation issues
- Insecure data storage

### Active Directory & Network Exploitation

Actively building depth here. Current capabilities include:

- User, group, and service enumeration
- Credential attacks — password spraying, pass-the-hash
- SMB enumeration with **CrackMapExec** and **Impacket**
- ACL abuse — GenericWrite, targeted Kerberoasting
- Privilege escalation and lateral movement in domain environments

---

## Tools & Environment

I work primarily in **Kali Linux**, terminal-first. Key tools in my workflow:

| Domain | Tools |
|---|---|
| Web/API | Burp Suite, ffuf, sqlmap, nuclei |
| AD/Network | Impacket, CrackMapExec, bloodyAD, BloodHound, Nmap |
| Analysis | Wireshark, tcpdump |

---

## Methodology

My attack path follows a structured flow:

1. **Initial Access** — web/API vulnerabilities or credential-based entry
2. **Enumeration** — map the environment, identify privilege gaps
3. **Privilege Escalation** — local or domain
4. **Lateral Movement** — spread access, gather credentials
5. **Full Compromise** — domain admin or equivalent in lab scope

The goal is always to connect external attack surfaces to internal exploitation paths — bridging web application vulnerabilities with Active Directory compromise.

---

## Current Focus

- Active Directory internals and Kerberos-based attacks (AS-REP Roasting, Kerberoasting, Silver/Golden Tickets)
- Full-scope attack chains: web foothold → internal network → domain compromise
- Building toward red team operation capability

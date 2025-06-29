# 🛡️ Raptack Threat Intelligence Report (May 2025)

**Analyst:** Onaopemipo David Olugbemiro  
**Role:** Cybersecurity Analyst (Threat Intelligence Focus)  
**Report Type:** Passive OSINT-Based Threat Intelligence Report  
**Target Industry:** FinTech  

---

## 🧠 Project Overview

This project is a comprehensive Threat Intelligence Report on **Raptack**, a rising FinTech organization operating in the African digital payments space. The report leverages passive OSINT techniques, MITRE ATT&CK mapping, and adversary profiling to assess potential threats and exposures.

Key deliverables:
- Detailed passive footprinting (no scanning or probing).
- Threat actor profiling with emphasis on **FIN7 (Carbanak Group)**.
- MITRE ATT&CK lifecycle alignment.
- Security risk matrix and actionable recommendations.

---

## 🛠️ Tools & Frameworks Used

| Tool | Purpose |
|------|---------|
| `theHarvester` | Email, IPs, ASN & Subdomain discovery |
| `Google Dorking` | Discover exposed documents & backend files |
| `crt.sh` | Certificate transparency logs / Subdomains |
| `WHOIS` | Domain ownership & expiry profiling |
| `Censys.io` | Port scanning & infrastructure mapping |
| `LinkedIn` | Employee enumeration & tech stack discovery |
| `MITRE ATT&CK` | TTP mapping for threat actor analysis |

---

## 🎯 Threat Actor Highlight

> **Primary Threat Actor Identified:**  
> **FIN7 (Carbanak Group)** – A financially motivated APT with a history of targeting payment processors and APIs used by FinTech organizations.

Mapped using MITRE ATT&CK:
- Initial Access: `T1566.001 – Spearphishing Attachment`
- Credential Access: `T1003 – OS Credential Dumping`
- Execution: `T1059 – Command and Scripting Interpreter`
- Lateral Movement: `T1021.001 – RDP`
- And more…


---

## ✅ Key Recommendations

- Enforce Multi-Factor Authentication (MFA)
- Monitor for exposed credentials on open platforms
- Audit GitHub repos for sensitive data
- Restrict open ports like FTP (21), HTTP (80) and inspect Cloudflare services
- Train staff on phishing & social engineering awareness
- Leverage WAF, rate-limiting & TLS hardening for APIs

---

## 🧩 References

- [MITRE ATT&CK Framework](https://attack.mitre.org)
- [AlienVault OTX](https://otx.alienvault.com)
- [crt.sh](https://crt.sh)
- [SecurityTrails](https://securitytrails.com)
- [theHarvester](https://github.com/laramies/theHarvester)
- [Censys.io](https://search.censys.io)
- [Google Dorks](https://www.exploit-db.com/google-hacking-database)

---

## 🤝 Connect

If you're a recruiter, cybersecurity lead, or tech enthusiast, feel free to connect with me:

📍 **[LinkedIn](https://www.linkedin.com/in/onaopemipo-olugbemiro-1b377828b/)**  
🐦 **[Twitter](https://x.com/myboionaope)**  
💻 **[GitHub](https://github.com/LyticOnaope)**  



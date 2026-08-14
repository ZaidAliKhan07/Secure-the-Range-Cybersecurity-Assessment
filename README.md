# Secure the Range: End-to-End Cybersecurity Assessment

## Project Overview
This project was completed as part of the IT-SIMPLERA Cyber Security Analyst Internship Program.

The objective was to perform an end-to-end security assessment of an authorized lab environment, covering reconnaissance, network scanning, service enumeration, vulnerability assessment, risk analysis, cryptography/TLS review, and remediation planning.

## Assessment Environment
- Simulated Client: Nimbus Retail Co.
- Active Lab Target: Metasploitable 2
- Target IP: 192.168.64.8
- Testing Environment: Kali Linux

## Tools Used
- Nmap
- WHOIS
- Subfinder / Amass
- Certificate Transparency Logs
- Google Dorking
- WhatWeb
- Netcat
- NVD
- Draw.io
- Kali Linux

## Methodology
1. Security foundations and network design
2. Reconnaissance and OSINT
3. Port and service enumeration
4. Web technology identification
5. Vulnerability identification
6. CVE and CVSS analysis
7. Risk assessment
8. HTTPS/TLS review
9. Remediation planning
10. Incident response planning

## Key Findings
- Multiple unnecessary and outdated services were exposed.
- FTP service was identified as vsftpd 2.3.4.
- Samba 3.0.20 was identified on the target.
- PHP 5.2.4 was identified in the web technology stack.
- HTTP was available on port 80 while HTTPS port 443 was closed.
- Several known vulnerabilities were identified for further risk assessment.

## Vulnerabilities Assessed

| CVE | Affected Component | CVSS | Severity |
| --- | --- | --- | --- |
| CVE-2011-2523 | vsftpd 2.3.4 | 9.8 | Critical |
| CVE-2007-2447 | Samba 3.0.20 | 6.0 | Medium |
| CVE-2007-4825 | PHP 5.2.4 | 7.5 | High |

## Key Recommendations
- Remove or upgrade vulnerable and outdated services.
- Enable HTTPS/TLS for web communication.
- Disable unnecessary ports and services.
- Apply network segmentation and least privilege.
- Establish regular patching and vulnerability scanning.
- Implement continuous logging and security monitoring.

## Deliverables
- Vulnerability Assessment Report
- Network Architecture Diagram
- Security Assessment Presentation
- Supporting screenshots and scan evidence

## Ethics Disclaimer
All active scanning and security testing documented in this project was performed only against an authorized lab environment. No unauthorized systems were tested.

## Author
**Zaid Qazi**  
Cyber Security Analyst Intern

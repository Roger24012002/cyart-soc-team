# Week 2 SOC Task – Phishing Analysis & Incident Response

## Overview
This project demonstrates the analysis of a phishing email incident as part of SOC (Security Operations Center) activities. The objective is to identify malicious indicators, classify the alert, and perform incident response using standard frameworks.

---

## Objectives
- Analyze phishing email characteristics
- Identify Indicators of Compromise (IOCs)
- Perform domain reputation check using VirusTotal
- Classify alert priority
- Map attack to MITRE ATT&CK framework
- Document incident response lifecycle

## Tools Used
- VirusTotal – Domain reputation analysis  
- Manual Analysis – Email content inspection  
- MITRE ATT&CK Framework – Attack classification  

##  Project Structure
Week2/
 ├── phishing_report1.pdf
 ├── Screenshots/
 │     ├── phishing_email_sample.png
 │     ├── virustotal_phishing_check.png
 ├── Documentation/
 │     ├── incident_ticket.docx
 │     ├── phishing_analysis.docx
 │     ├── phishing_email_sample.docx


## Analysis Summary
The phishing email used social engineering techniques such as urgency and impersonation to trick users into clicking a malicious link.

The domain `micr0soft-account-reset.com` was identified as suspicious due to typosquatting (use of “0” instead of “o”).

Although VirusTotal showed **0 detections**, the domain was classified as malicious based on behavioral indicators.

## Indicators of Compromise (IOCs)
- Malicious Domain: micr0soft-account-reset.com  
- Sender Email: security-update@micr0soft-support.com  
- URL: http://micr0soft-account-reset.com/login  

## MITRE ATT&CK Mapping
- Tactic: Initial Access  
- Technique: Phishing  
- Technique ID: T1566

  
## Incident Response Steps
1. Preparation – Monitoring tools configured  
2. Identification – Phishing email detected  
3. Containment – Domain blocked  
4. Eradication – Email removed  
5. Recovery – System verified  
6. Lessons Learned – User awareness required  

## Key Learnings
- New phishing domains may bypass detection tools  
- Manual analysis is critical in SOC operations  
- MITRE ATT&CK helps in standardized classification  
- User awareness is essential to prevent attacks  

## Screenshots

### Phishing Email Sample
![Email](Screenshots/phishing_email_sample.png)

### VirusTotal Analysis
![VirusTotal](Screenshots/virustotal_phishing_check.png)


##  References
- https://attack.mitre.org/  
- https://www.virustotal.com/  
- https://owasp.org/  

##  Author
Vinayaka Reddy N V  
Cyber Security Intern – Cyart Tech

# Week 4 Capstone Project

## Comprehensive SOC Incident Response Using Wazuh SIEM

---

##  Project Overview

This capstone project demonstrates a complete Security Operations Center (SOC) workflow using **Wazuh SIEM** in a virtual lab environment. The project includes attack simulation, threat monitoring, event detection, investigation, and containment.

The objective was to gain practical hands-on experience in SOC operations, incident response, log analysis, and threat hunting using real cybersecurity tools.

---

##  Objectives

- Deploy and configure Wazuh SIEM  
- Connect monitored endpoints  
- Simulate attacks in lab environment  
- Detect suspicious activity and failed logins  
- Perform threat hunting investigations  
- Apply containment actions  
- Document full incident response lifecycle  

---

##  Lab Environment

| Machine | Role |
|--------|------|
| Ubuntu Server | Wazuh Manager / Dashboard |
| Windows 11 | Monitored Endpoint |
| Kali Linux | Attacker Machine |
| Metasploitable2 | Vulnerable Target |

---

##  Tools Used

- Wazuh SIEM  
- VMware Workstation  
- Kali Linux  
- Windows 11  
- Nmap  
- Metasploit Framework  
- UFW Firewall  

---

##  Workflow Summary

1. Setup Wazuh SIEM on Ubuntu  
2. Connect Windows endpoint agent  
3. Scan target machine using Nmap  
4. Simulate attack activity using Kali Linux  
5. Generate failed login attempts (Event ID 4625)  
6. Detect events in Wazuh SIEM  
7. Investigate alerts using Threat Hunting  
8. Block suspicious IP using firewall  
9. Perform root cause analysis  
10. Create final incident report  

---

##  Key Security Events

- Windows Failed Login Event ID **4625**  
- Unauthorized login attempts  
- Reconnaissance scanning activity  
- Suspicious authentication behavior  

---

##  Incident Response Actions

- Alert triage completed  
- Failed login attempts investigated  
- Source activity reviewed  
- Suspicious IP blocked using firewall  
- Security posture improved  

---

##  Security Metrics

| Metric | Result |
|-------|--------|
| Mean Time to Detect | 2 Minutes |
| Mean Time to Respond | 10 Minutes |
| Severity Level | High |
| Final Status | Contained |

---

##  Folder Structure

```text
Week4/
├── Executive/
├── Notes/
├── RCA/
├── Report/
├── Screenshots/
└── README.md
````

---

##  Evidence Included

* Wazuh Agent Connected Screenshot
* Threat Hunting Dashboard
* Event ID 4625 Detection
* Nmap Enumeration Results
* Metasploit Simulation
* Firewall Containment Rule

---

##  Conclusion

This project successfully demonstrated a full SOC lifecycle including attack simulation, monitoring, detection, investigation, and containment. Wazuh SIEM provided centralized visibility into security events and enabled effective incident response.

The project enhanced practical cybersecurity skills and showcased how SIEM platforms are used in modern SOC environments.

---

##  Author

**Vinayaka Reddy**
Cybersecurity Enthusiast | SOC | SIEM | VAPT | Threat Detection

```
```


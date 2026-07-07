# Security in Practice Network Defence Lab

An authorised university cyber security lab focused on vulnerability assessment, web application security testing, network monitoring and security hardening.

The lab used an isolated host only virtual network containing Kali Linux, a deliberately vulnerable OWASP/DVWA target and a separate Snort IDPS monitoring system.

> **Authorised lab use only:** All testing was completed in a controlled university environment against intentionally vulnerable systems. No public, production or third party systems were targeted.

## Author

Karanveer Singh Malhi
[LinkedIn](https://www.linkedin.com/in/karanveer-singh-malhi-750793311/)

## Project Overview

This project assessed the security posture of a vulnerable web application and supporting infrastructure. The work combined vulnerability discovery, controlled validation of selected weaknesses, impact analysis and defensive improvements.

The aim was not only to identify weaknesses, but also to evaluate their effect on confidentiality, integrity and availability, then propose practical security controls.

## Lab Environment

The prototype environment included:

- Kali Linux attacker virtual machine
- OWASP Broken Web Applications / DVWA vulnerable target
- Host-only isolated virtual network
- Snort IDS/IDPS monitoring system
- Apache web server and MySQL-backed vulnerable web application

The host-only setup ensured that all assessment traffic remained inside the authorised lab environment.

## Tools Used

- Kali Linux
- Nmap
- Nikto
- OpenVAS
- SQLMap
- Snort IDS/IDPS
- DVWA
- Virtual machines
- Linux command-line tools

## Activities Performed

### Vulnerability Assessment

- Performed service and port discovery
- Identified outdated services and exposed web components
- Reviewed HTTP and server misconfigurations
- Conducted vulnerability scanning and severity analysis
- Correlated findings across Nmap, Nikto and OpenVAS

### Web Application Security Testing

The controlled assessment examined selected web-application weaknesses, including:

- SQL Injection
- Stored Cross-Site Scripting
- File Upload weaknesses
- Local and Remote File Inclusion
- Command Injection
- Missing security headers
- Weak authentication and exposed configuration risks

### Defensive Security Improvements

The project also focused on mitigation and hardening, including:

- Patch and vulnerability management
- Secure input validation
- Parameterised database queries
- Output encoding
- Stronger authentication controls
- Secure file-upload handling
- Reduced attack surface
- Network segmentation
- Security-header improvements
- Logging and monitoring controls
- Snort IDS/IDPS deployment and alerting

## Snort IDPS Monitoring

Snort was used to improve network visibility and monitor suspicious activity within the lab.

The monitoring work considered:

- Detection of suspicious network traffic
- Alert interpretation
- False-positive limitations
- Network-based intrusion detection
- Tuning and operational monitoring considerations
- The role of IDS/IDPS within layered security

## Key Skills Demonstrated

- Vulnerability assessment
- Network security
- Web-application security testing
- Risk and impact analysis
- Security monitoring
- Snort IDS/IDPS
- Secure configuration and hardening
- Threat modelling
- Security reporting
- Ethical security-testing practice

## Security Principles Applied

The lab was designed around the CIA triad:

- **Confidentiality:** Controlled access to sensitive data and systems
- **Integrity:** Protection against unauthorised modification of applications and data
- **Availability:** Maintaining service resilience and reducing disruption risks

## Repository Contents

```text
security-in-practice-network-defence-lab/
├── README.md
├── redacted-security-lab-report.pdf
└── selected-redacted-diagrams-and-results/


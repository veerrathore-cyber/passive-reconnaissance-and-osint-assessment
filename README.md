# Passive Reconnaissance and OSINT Assessment

## Project Overview

This project demonstrates the process of conducting passive reconnaissance and Open Source Intelligence (OSINT) gathering on a target organization. The objective was to identify publicly exposed information using ethical and non-intrusive techniques before any security assessment.

> **Note:** This project involved only passive reconnaissance methods. No active exploitation, intrusive scanning, or unauthorized access attempts were performed.

---

## Objectives

- Understand the reconnaissance phase of ethical hacking.
- Differentiate between passive and active reconnaissance.
- Gather publicly available information using OSINT techniques.
- Perform DNS record analysis.
- Identify exposed resources using Google Dorking.
- Enumerate subdomains using public certificate transparency logs.
- Analyze technologies used by the target website.
- Assess potential security risks and recommend mitigations.

---

## Scope

The assessment focused exclusively on publicly available information related to the target domain.

### Activities Performed:

- Ethical Hacking Phases Review
- Passive vs Active Reconnaissance Analysis
- Google Dorking
- DNS Record Enumeration
- WHOIS Lookup
- Subdomain Enumeration using crt.sh
- Technology Fingerprinting using Wappalyzer
- Risk Identification and Remediation Suggestions

---

## Tools Used

| Tool | Purpose |
|--------|----------|
| Google Search | Information discovery |
| Google Dorks | Finding exposed resources |
| WHOIS | Domain ownership analysis |
| nslookup / dig | DNS record enumeration |
| crt.sh | Subdomain enumeration |
| Wappalyzer | Technology identification |
| Browser | OSINT research |

---

## Tasks Performed

### 1. Ethical Hacking Phases

Studied and documented the phases of ethical hacking:

- Reconnaissance
- Scanning
- Gaining Access
- Maintaining Access
- Covering Tracks
- Reporting

---

### 2. Passive vs Active Reconnaissance

Compared the characteristics, advantages, and limitations of passive and active information gathering techniques.

---

### 3. Google Dorking

Used Google search operators to identify publicly exposed information such as:

- Login pages
- Administrative portals
- Publicly accessible documents
- Indexed resources

---

### 4. DNS Record Enumeration

Collected and analyzed the following DNS records:

- A Record
- MX Record
- NS Record
- TXT Record

---

### 5. WHOIS Analysis

Performed WHOIS lookup to gather publicly available domain registration details.

---

### 6. Subdomain Enumeration

Used **crt.sh** to identify subdomains associated with the target organization through certificate transparency logs.

---

### 7. Technology Fingerprinting

Utilized **Wappalyzer** to identify technologies, frameworks, and services used by the target website.

---

### 8. Risk Analysis and Recommendations

Evaluated findings from a security perspective and suggested appropriate remediation measures to reduce the exposed attack surface.

---

## Screenshots

Screenshots demonstrating the assessment process are available in the `screenshots` directory.

Examples include:

- Google Dork findings
- DNS record lookups
- WHOIS output
- crt.sh results
- Wappalyzer technology analysis

---

## Folder Structure

```text
passive-reconnaissance-and-osint-assessment/
│
├── README.md
├── LICENSE
├── reports/
│   └── reconnaissance_report.pdf
│
└── screenshots/
    ├── google_dork_login.png
    ├── google_dork_admin.png
    ├── dns_a_record.png
    ├── dns_mx_record.png
    ├── dns_ns_record.png
    ├── dns_txt_record.png
    ├── crtsh_subdomains.png
    ├── whois_lookup.png
    └── wappalyzer_results.png
```

---

## Skills Gained

- Passive Reconnaissance
- Open Source Intelligence (OSINT)
- Google Dorking
- DNS Enumeration
- WHOIS Analysis
- Subdomain Enumeration
- Technology Fingerprinting
- Risk Assessment
- Security Documentation
- Technical Reporting

---

## Detailed Report

A complete walkthrough of the assessment process is available in the report below:

- [Reconnaissance Report](reports/reconnaissance_report.pdf)

---

## Disclaimer

This project was conducted strictly for educational purposes within an authorized training environment. All reconnaissance activities were limited to passive information gathering techniques without performing intrusive actions against the target systems.

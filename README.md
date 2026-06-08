# PhishShield – Phishing URL Risk Scoring Tool

## Overview

PhishShield is a rule-based phishing URL risk scoring tool designed to help users evaluate the potential risk level of a URL before visiting it.

The system analyzes URLs using predefined security indicators and assigns a risk score. Based on this score, URLs are classified as Safe, Suspicious, or High Risk, helping users make informed browsing decisions.

---

## Problem Statement

Phishing is a common cybersecurity threat where attackers use deceptive URLs to trick users into revealing sensitive information or accessing malicious websites.

These links are commonly distributed through:

- Email  
- SMS  
- Social media platforms  
- Messaging applications  

PhishShield helps users assess URLs by analyzing known phishing indicators using a rule-based approach.

---

## Features

### URL Risk Scoring

- Accepts user input URL
- Evaluates risk using rule-based logic
- Generates a numerical risk score

---

### Threat Detection Engine

Detects common phishing indicators such as:

- Typosquatting patterns  
- Blacklisted domains (if configured)  
- Phishing-related keywords  
- URL shorteners  
- IP-based URLs  
- Suspicious or uncommon TLDs  
- Missing HTTPS protocol  
- Excessive subdomains  
- Redirect patterns  
- Encoded or obfuscated characters  

---

### Risk Classification

URLs are categorized into:

- Safe  
- Suspicious  
- High Risk  

---

### Scan History

- Stores previously scanned URLs  
- Allows users to review past evaluations  

---

### Security Dashboard

Provides summary analytics including:

- Total URLs scanned  
- Safe URLs count  
- Suspicious URLs count  
- High-risk URLs count  
- Basic threat distribution overview  

---

## Risk Scoring Methodology

Each phishing indicator contributes a weighted score based on severity. The final score is calculated by summing all detected indicators.

### Risk Indicator Table

| Indicator            | Severity  | Score Impact |
|---------------------|----------|--------------|
| Typosquatting       | Critical | 25           |
| Blacklisted Domain  | Critical | 25           |
| Missing HTTPS       | High     | 20           |
| IP Address URL      | High     | 20           |
| Suspicious Keywords | Medium   | 10           |
| URL Shortener       | Medium   | 10           |
| Suspicious TLD      | Medium   | 10           |
| Excess Subdomains   | Medium   | 10           |
| Redirect Pattern    | Low      | 5            |
| Encoded Characters  | Low      | 5            |

### Score Classification

- 0 to 25 → Safe  
- 26 to 60 → Suspicious  
- 61 to 100 → High Risk  

---

## System Workflow

- User submits a URL  
- URL is parsed into components  
- Security rules are applied  
- Risk score is calculated  
- URL is classified  
- Results are displayed  
- Scan history is updated  
- Dashboard statistics are refreshed  

---

## Screenshots

### Launch Screen
https://github.com/MANASA-D-PROJECTS/PHISHSHIELD/blob/main/Launch%20Screen.png

### URL Scanner
https://github.com/MANASA-D-PROJECTS/PHISHSHIELD/blob/main/URL%20Scanner.png

### Threat Indicators and Safety Score
https://github.com/MANASA-D-PROJECTS/PHISHSHIELD/blob/main/Threat%20Indicators%20%26%20Safety%20Score%20of%20URL.png

### Safe Scan History
https://github.com/MANASA-D-PROJECTS/PHISHSHIELD/blob/main/Safe%20Scan%20History.png

### Suspicious Scan History
https://github.com/MANASA-D-PROJECTS/PHISHSHIELD/blob/main/Suspicious%20Scan%20History.png

### High Risk Scan History
https://github.com/MANASA-D-PROJECTS/PHISHSHIELD/blob/main/High%20Risk%20URL's%20Scan%20History.png

### Dashboard
https://github.com/MANASA-D-PROJECTS/PHISHSHIELD/blob/main/PhishShield%20Dashboard.png

---

## Technology Stack

### Frontend

- HTML  
- CSS  
- JavaScript  
- Figma Make (UI design and prototyping)

---

### Core Concepts

- URL parsing and analysis  
- Rule-based security system  
- Phishing detection indicators  
- Risk scoring logic  
- Security analytics visualization  

---

## Limitations

- The system uses rule-based logic and does not include machine learning  
- No real-time threat intelligence API integration  
- Blacklist data is static or manually configured (if used)  
- Detection accuracy depends on predefined rules  

---

## Future Enhancements

- Integration with VirusTotal API for real-time threat intelligence  
- WHOIS domain age analysis  
- Real-time threat intelligence feeds  
- Browser extension for live URL scanning  
- Email phishing detection module  

---

## Learning Outcomes

- Understanding phishing attack patterns  
- Designing rule-based security systems  
- Implementing risk scoring logic  
- Building security-focused web interfaces  
- Creating basic security analytics dashboards  

---

## Author

Name: Manasa D

Education:

- B.Tech Electronics and Communication Engineering  
- M.Tech Cyber Forensics and Information Security  
- MBA Human Resources

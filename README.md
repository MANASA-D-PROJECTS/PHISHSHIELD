# PhishShield

## Overview

PhishShield is a phishing URL detection platform designed to help users identify potentially malicious links before visiting them.

The system analyzes URLs against multiple phishing indicators and generates a risk score, helping users make safer browsing decisions.

---

## Problem Statement

Phishing attacks remain one of the most common cyber threats.

Users often receive links through:

* Email
* SMS
* Social media
* Messaging applications

Many malicious URLs imitate trusted brands and trick users into disclosing sensitive information.

PhishShield provides a simple mechanism to evaluate URLs and identify suspicious characteristics before interaction.

---

## Features

### URL Risk Analysis

Analyze any URL and calculate a threat score.

### Threat Detection Engine

Detects indicators including:

* Typosquatting
* Blacklisted domains
* Phishing keywords
* URL shorteners
* IP-based URLs
* Suspicious TLDs
* Missing HTTPS
* Excessive subdomains
* Redirect patterns
* Encoded characters

### Risk Classification

URLs are categorized as:

* Safe
* Suspicious
* High Risk

### Scan History

Maintains a searchable history of previous scans.

### Security Dashboard

Provides analytics including:

* Total URLs scanned
* Safe URLs
* Suspicious URLs
* High-risk URLs
* Threat distribution
* Threat frequency trends

---

## Risk Scoring Methodology

Each threat indicator contributes to an overall risk score.

Example scoring:

| Indicator           | Severity |
| ------------------- | -------- |
| Typosquatting       | Critical |
| Missing HTTPS       | High     |
| Blacklisted Domain  | Critical |
| Suspicious Keywords | Medium   |
| IP Address URL      | High     |
| URL Shortener       | Medium   |

Final score range:

* 0–25 → Safe
* 26–60 → Suspicious
* 61–100 → High Risk

---

## System Workflow

1. User submits URL.
2. URL components are parsed.
3. Threat indicators are evaluated.
4. Risk score is calculated.
5. Results are displayed.
6. Scan history is updated.
7. Dashboard metrics are refreshed.

---

## Screenshots

### Launch Screen

Launch Screen.png

### URL Scanner

URL Scanner.png

### Threat Indicators & Safety Score of URL

Threat Indicators & Safety Score of URL.png

### Safe Scan History

Safe Scan History.png

### Suspicious Scan History

Suspicious Scan History.png

### High Risk URL's Scan History

High Risk URL's Scan History.png

### PhishShield Dashboard

PhishShield Dashboard.png

---

## Technology Stack

### Frontend

* Figma Make
* HTML
* CSS
* JavaScript

### Security Concepts

* URL Analysis
* Phishing Detection
* Threat Scoring
* Security Analytics

### Future Enhancements

* VirusTotal Integration
* WHOIS Lookup
* Domain Age Verification
* Browser Extension
* Real-Time Threat Intelligence Feeds
* Email Phishing Detection

---

## Learning Outcomes

This project helped demonstrate:

* Cybersecurity fundamentals
* Phishing detection concepts
* Security-focused product design
* Risk assessment methodologies
* Dashboard and reporting design
* Security analytics visualization

---

## Author

Name: Manasa D

Education:

* B.Tech Electronics and Communication Engineering
* M.Tech Cyber Forensics and Information Security
* MBA Human Resources


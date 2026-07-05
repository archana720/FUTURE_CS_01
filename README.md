# FUTURE_CS_01 – Vulnerability Assessment Report for a Live Website

- Internship Track - Cyber Security Intern 
- Host Organization - Future Interns 
- Prepared By - Archana S
- Target Website - OWASP Juice Shop
---

## 🔍 Project Overview

This project was completed as part of the **Future Interns Cyber Security Internship – Task 01**.

The objective of this task was to perform a **passive vulnerability assessment** on a public web application using ethical security testing practices. The assessment focused on identifying common security weaknesses, classifying risks, and providing practical remediation recommendations in a professional report.

> **Disclaimer:** The assessment was conducted on **OWASP Juice Shop**, an intentionally vulnerable web application designed for cybersecurity training and education. No exploitation or unauthorized activities were performed.

---

## 🌐 Target Website

- **Application:** OWASP Juice Shop
- **URL:** https://juice-shop.herokuapp.com/#/
- **Assessment Type:** Passive Vulnerability Assessment

---

## 🎯 Objective

The objectives of this assessment were to:

- Analyze a public website for common security weaknesses.
- Identify exposed services and security misconfigurations.
- Classify findings based on risk severity (Low / Medium / Informational).
- Explain security issues in clear, business-friendly language.
- Recommend practical remediation measures.
- Document the assessment in a professional vulnerability assessment report.

---


## ⚠️ Scope & Ethics

This assessment was conducted following ethical cybersecurity practices and was limited to 
- publicly accessible web pages,
- passive vulnerability scanning, 
- HTTP security header analysis,
- Network and service discovery,
- configuration analysis. 
- No login bypass, vulnerability exploitation, brute-force attacks, Denial-of-Service (DoS), or any activity that could negatively impact the target application was performed. The assessment was carried out as a **passive security audit**, not a penetration test.
---

## 🛠️ Tools Used

### Security & Analysis Tools

- **Nmap** – Port scanning, service detection, and basic vulnerability analysis.
- **OWASP ZAP (Passive Scan)** – Passive identification of web security issues.
- **Browser Developer Tools (Chrome DevTools)** – Inspection of HTTP headers, cookies, and network responses.

### Documentation

- **GitHub** – Project documentation and evidence management.

---

## ✅ Assessment Methodology

The following steps were completed during the assessment:

1. Selected the target web application (OWASP Juice Shop).
2. Performed network reconnaissance using Nmap.
3. Conducted a passive vulnerability assessment using OWASP ZAP.
4. Inspected HTTP response headers and cookies using Browser DevTools.
5. Identified exposed services and security misconfigurations.
6. Classified findings according to risk level.
7. Prepared remediation recommendations.
8. Documented the assessment in a professional report.

---

## 🔍 Assessment Summary
### Nmap

- Identified publicly accessible services.
- Detected HTTP and HTTPS ports.
- Performed service detection.
- Executed safe vulnerability detection scripts.

### OWASP ZAP (Passive Scan)

The assessment identified findings including:

- Content Security Policy (CSP) Header Not Set
- Cross-Domain Misconfiguration
- Missing Anti-Clickjacking Header
- Session ID in URL Rewrite
- Private IP Disclosure
- Timestamp Disclosure
- Missing X-Content-Type-Options Header
- Information Disclosure
- Modern Web Application Detection

### Browser DevTools

Browser DevTools was used to inspect:

- HTTP response headers
- Security headers
- Cookies
- Network requests
- Client-side resources

The observations supported the verification of configuration-related security findings.

---

## 📊 Risk Classification

| Risk Level | Description |
|------------|-------------|
| 🟠 Medium | Security weakness requiring remediation |
| 🟢 Low | Minor security or configuration issue |
| 🔵 Informational | Observation with minimal security impact |

---

## ✨ Deliverables

This repository contains:

- Vulnerability Assessment Report (PDF)
- Nmap scan evidence
- OWASP ZAP passive scan evidence
- Browser DevTools screenshots
- Risk classification
- Remediation recommendations

---

## 📁 Repository Structure

This repository includes:

```text
FUTURE_CS_01/
│
├── README.md
├── Vulnerability_Assessment_Report.pdf
│
└── evidence/
    ├── nmap/
    ├── owasp-zap/
    └── devtools/
```

---

## 📌 Skills Demonstrated

- Vulnerability Assessment
- Network Reconnaissance
- Web Security Analysis
- Security Header Inspection
- Risk Classification
- Security Reporting
- Ethical Security Testing
- Technical Documentation

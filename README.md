# Vulnerability Assessment: OWASP Juice Shop

**Assessor:** Zannu Opeyemi Emmanuel
**Program:** Future Interns Cybersecurity Internship
**Date:** December 2025

## 📄 Project Overview
This repository contains the final security assessment report for the **OWASP Juice Shop**, a modern web application designed with intentional security flaws. The goal of this engagement was to identify, validate, and document vulnerabilities according to the **OWASP Top 10 (2021)** framework.

## 🛠️ Tools Used
* **OWASP ZAP:** Automated vulnerability scanning.
* **Burp Suite Professional/Community:** Manual interception and exploitation.
* **Kali Linux:** Testing environment.

## 🔍 Key Findings
| Severity | Vulnerability | OWASP Category |
| :--- | :--- | :--- |
| **High** | SQL Injection (Login Bypass) | A03: Injection |
| **High** | Insecure Token Design (Weak JWT) | A02: Cryptographic Failures |
| **High** | Insecure Direct Object Reference (IDOR) | A01: Broken Access Control |
| **Medium** | Business Logic Exploitation | A04: Insecure Design |

## 📂 Repository Contents
* `Vulnerability_Assessment_Report.pdf`: The complete professional report detailing findings and remediation.
* `Evidence/`: Screenshots and proof-of-concept logs (sanitized).

## ⚠️ Disclaimer
This project was conducted in a controlled, ethical environment using the [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) for educational purposes.

# VAPT Project: OWASP Juice Shop using Kali Linux

## 🔍 Overview
This project demonstrates an end-to-end Vulnerability Assessment and Penetration Testing (VAPT) on OWASP Juice Shop using Kali Linux tools.

## 🛠 Tools Used
- Kali Linux
- Docker
- Nmap
- Nikto
- Burp Suite
- Metasploit

## 📸 Evidence
All screenshots are stored in the `/screenshots` folder.

## 📄 Report
Detailed findings and remediation steps are documented in `report.md`.

### Executive Summary

During the VAPT engagement on OWASP Juice Shop, two critical vulnerabilities were identified:

1. **SQL Injection on Login Page** The login form was vulnerable to SQL injection, allowing attackers to bypass authentication and access user data. This poses a high risk to confidentiality and integrity.

2. **Sensitive Data Exposure via API** The `/rest/user/whoami` endpoint exposed user details without proper authentication. This could lead to data leakage and privacy violations.

Screenshots and evidence were collected during exploitation, and remediation steps have been suggested to mitigate these risks.

## 🚀 How to Run
```bash
docker run -d -p 3000:3000 bkimminich/juice-shop
```

Visit `http://localhost:3000` to start testing.

## 📬 Author

Sushant — Technical Buisiness Analyst - Cybersecurity and Risk

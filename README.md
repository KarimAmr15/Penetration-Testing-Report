# 🔐 Juice Shop Penetration Testing Report

This repository contains the comprehensive penetration testing report for the **OWASP Juice Shop** web application. The project was conducted as part of the **Software and Mobile Devices Security** course.

---

## 📄 Project Overview

The goal of this project was to conduct a full **black-box penetration test** on the OWASP Juice Shop application. We simulated real-world attack scenarios to identify vulnerabilities in both client-side and server-side components of the web application.

All testing was conducted on a **locally hosted instance** of Juice Shop.

---

## 📌 Scope

- Target: [OWASP Juice Shop](https://github.com/juice-shop/juice-shop) 
- Application Type: Black-box Web Application
- Domain: `localhost:3000`
- All subdomains and endpoints under test scope

---

## 📝 Summary of Findings

- 🔴 **High Severity Issues**: 15
- 🟠 **Medium Severity Issues**: 8
- 🟢 **Low Severity Issues**: 7

Vulnerabilities included:
- SQL Injection
- Cross-Site Scripting (XSS)
- Authentication Bypass
- Privilege Escalation
- Insecure Direct Object References (IDOR)
- CAPTCHA and Upload Bypass
- Information Disclosure

---

## 📌 Highlights

### ✅ Notable High-Severity Vulnerabilities

- Login as Admin 
- Captcha Bypass
- File Upload Size Bypass
- Client/Server-Side XSS
- Admin Page Access
- Register as Admin
- Password Reset Abuse

### 🔧 Tools Used

- **Burp Suite**
- **WFUZZ**
- **Sublist3r**
- **Browser DevTools**

---

## 🛠️ Methodology

1. **Information Gathering**
2. **Threat Modeling**
3. **Exploitation**
4. **Post-Exploitation**
5. **Reporting and Recommendations**

We followed OWASP Top 10 and industry best practices throughout the testing and documentation.

---
## 📚 References

- [OWASP Juice Shop Project](https://owasp.org/www-project-juice-shop/)
- [OWASP Top Ten](https://owasp.org/www-project-top-ten/)
- [Burp Suite Docs](https://portswigger.net/burp)


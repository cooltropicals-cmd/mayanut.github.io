# Security Policy

## Supported Versions
We update security fixes for the following versions of this project:

| Version | Supported          |
|---------|--------------------|
| main    | ✔ Always supported |
| older versions | ❌ Not supported |

If you find a vulnerability in an older version, please test it against `main` before reporting.

---

## Reporting a Vulnerability

If you believe you’ve found a security vulnerability, please contact:

**themayanutcompany@gmail.com**  
Subject: **Security Vulnerability Report**

Please include:
- A detailed description of the issue  
- Steps to reproduce the vulnerability  
- Any relevant URLs, screenshots, or logs  
- Your environment (browser, OS, device)

We will reply within **5 business days**.

---

## Responsible Disclosure

We ask that:
- You give us reasonable time to review and fix issues before public disclosure  
- You avoid testing that affects service availability (no DDoS, spam, or destruction)  
- You do not access private data you do not own  
- You avoid using automated scanners against production servers

We will:
- Review the issue promptly  
- Provide updates as we validate and work on a fix  
- Give credit (optional) if you want acknowledgment after a fix is released  

---

## Scope

This policy applies to:

- **The mayanut.com website**
- **All code in this repository**
- **Public-facing web assets owned by The MayaNut Company**

Out of scope:
- Social media accounts  
- 3rd-party services we use (e.g., GitHub Pages hosting)  
- Physical security or social engineering attacks  

---

## Security Best Practices for Contributors

If you contribute to this repository:

- Do not commit API keys, secrets, tokens, or sensitive environment variables  
- Use `.gitignore` for build or local environment files  
- Sanitize user input before processing or storing  
- Avoid unsafe inline JS or eval-type functions  
- Use HTTPS for all external resources  
- Follow modern security guidelines (CSP, input validation, escape output)

---

## Thank You

We appreciate anyone who helps improve the security and integrity of The MayaNut Company’s digital ecosystem.

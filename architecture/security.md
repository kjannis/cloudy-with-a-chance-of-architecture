# 🔐 Architecture Security

This guide outlines key principles, threats, and practices to design secure systems from the ground up.

---

## 🔒 Security Principles

- **Defense in Depth**: Apply multiple layers of security
- **Least Privilege**: Grant only required access
- **Fail Securely**: Secure default states on failure
- **Secure Defaults**: Make secure behavior the default
- **Separation of Concerns**: Isolate modules and responsibilities

---

## 🧨 Common Threats

| Threat             | Description |
|-------------------|-------------|
| **Injection**      | SQL, NoSQL, command injection attacks |
| **Broken Auth**    | Weak login, session fixation |
| **Sensitive Data Exposure** | Leaked PII, unsecured storage |
| **Security Misconfiguration** | Unpatched systems, open ports |
| **XSS/CSRF**       | Browser-based code injection attacks |

---

## 🛡 Secure Design Practices

- Use HTTPS & TLS everywhere
- Sanitize and validate all inputs
- Implement proper authentication and authorization
- Use API gateways and security headers
- Audit and rotate secrets

---

## 🧰 Tools

- OWASP ZAP
- Snyk / SonarQube
- HashiCorp Vault
- Burp Suite
- JWT Inspector

---

## 📚 Resources

- [OWASP Top Ten](https://owasp.org/www-project-top-ten/)
- [Threat Modeling – Microsoft](https://learn.microsoft.com/en-us/security/compass/what-is-threat-modeling)
- [Security Best Practices – AWS](https://aws.amazon.com/architecture/security-pillar/)
- *Web Application Hacker’s Handbook* – Dafydd Stuttard


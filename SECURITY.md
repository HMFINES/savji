# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
# Security Policy

## 🛡️ Supported Versions

The following versions of AI Learning Coach are currently supported with security updates:

| Version | Supported |
| ------- | --------- |
| 1.x     | Yes       |
| < 1.0   | No        |

Only the latest production release receives security fixes.

---

## 🚨 Reporting a Vulnerability

If you discover a security vulnerability, please report it responsibly.

### Preferred Method

Send an email to:

[security@yourdomain.com](mailto:security@yourdomain.com)

Include:

* Description of the vulnerability
* Steps to reproduce
* Potential impact
* Suggested fix (if available)

You will receive a response within 72 hours.

Please do not publicly disclose vulnerabilities until they are resolved.

---

## 🔐 Security Practices

This project follows these security principles:

### API Key Protection

* API keys are stored in environment variables only
* Secrets are never exposed to client-side code
* Keys are not committed to version control

### Server-Side AI Requests

All AI provider calls are executed on the server to prevent credential leakage.

### Input Validation

User input is validated and sanitized to reduce risk of:

* Injection attacks
* Malformed requests
* Abuse of system resources

### Rate Limiting

Public deployments should implement request limits to prevent:

* API abuse
* Denial-of-service attempts
* Unexpected usage costs

### Dependency Security

* Dependencies are regularly updated
* Known vulnerabilities are monitored using package audit tools

---

## 🧱 Infrastructure Security

Recommended deployment protections:

* HTTPS enforced for all connections
* Secure environment variable storage
* Access control for deployment platform
* Logging and monitoring enabled

---

## 📦 Data Protection

The application avoids storing sensitive personal data by default.

If data storage is enabled:

* Store minimal required information
* Restrict database access
* Use secure authentication methods
* Follow local data protection regulations

---

## ⚠️ Responsible Disclosure

We appreciate responsible disclosure and will:

* Acknowledge your report
* Investigate promptly
* Fix confirmed issues
* Credit contributors when appropriate

---

## 📄 Security Updates

Security updates will be released as patches and documented in the changelog.

Users are encouraged to always run the latest version.

---

End of Security Policy

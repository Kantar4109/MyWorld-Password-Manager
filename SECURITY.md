# Security Policy

## Our Commitment

Security is the foundation of any password manager. We take the security of our application and users' data extremely seriously. This document outlines our security policy and provides instructions for reporting vulnerabilities.

## Supported Versions

We provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |

Older versions may not receive security updates. We strongly recommend always using the latest version.

## Security Features

- **AES-256 Encryption** – Industry-standard encryption for all stored data
- **PBKDF2 Key Derivation** – Master password is never stored; only a derived key is used
- **Memory Protection** – Sensitive data is cleared from memory after use
- **Auto-Lock** – Application locks automatically after inactivity
- **Clipboard Auto-Clear** – Copied passwords are automatically cleared from clipboard
- **No Telemetry** – No data is transmitted; everything stays local

## Reporting a Vulnerability

We appreciate the security research community's efforts in helping keep our users safe. If you discover a security vulnerability, please report it responsibly.

### How to Report

1. **DO NOT** open a public GitHub issue for security vulnerabilities
2. Send an email to: **moner.aldabai@gmail.com**
3. Use the subject line: **[SECURITY] Brief description of the vulnerability**

### What to Include

Please provide as much information as possible:

- Type of vulnerability (e.g., encryption flaw, data exposure, authentication bypass)
- Affected component(s) and version(s)
- Step-by-step instructions to reproduce the issue
- Proof of concept (if available)
- Potential impact assessment
- Any suggested fixes (optional)

### What to Expect

1. **Acknowledgment** – We will acknowledge receipt within 48 hours
2. **Initial Assessment** – We will assess the report within 7 days
3. **Status Updates** – We will keep you informed of our progress
4. **Resolution** – Critical vulnerabilities will be prioritized for immediate patching
5. **Disclosure** – We will coordinate with you on public disclosure timing

### Safe Harbor

We consider security research conducted in accordance with this policy to be:

- Authorized and lawful
- Helpful to the security of our users
- Conducted in good faith

We will not pursue legal action against researchers who:

- Report vulnerabilities in good faith
- Avoid privacy violations, data destruction, or service disruption
- Do not exploit vulnerabilities beyond proof of concept
- Give us reasonable time to address issues before disclosure

## Security Best Practices for Users

1. **Strong Master Password** – Use a long, unique master password that you don't use elsewhere
2. **Regular Updates** – Keep the application updated to receive security patches
3. **Secure Backups** – Store backup files in a secure location
4. **Lock When Away** – Lock the application when stepping away from your computer
5. **Verify Downloads** – Only download from official sources (this GitHub repository)

## Contact

For security-related inquiries:

- **Security Reports:** moner.aldabai@gmail.com
- **General Support:** [GitHub Issues](../../issues) (non-security issues only)

---

Thank you for helping keep our users safe.

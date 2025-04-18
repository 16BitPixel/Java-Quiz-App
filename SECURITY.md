# Security Policy for JavaFX Quiz App

The **JavaFX Quiz App** team is committed to ensuring the security of our application. This document outlines how to report security vulnerabilities and our approach to handling them.

## 🛡️ Reporting a Vulnerability

If you discover a security vulnerability in the JavaFX Quiz App, please report it to us promptly. We appreciate your help in keeping our project secure.

### How to Report

- **Email**: Send a detailed report to [izeno.contact@gmail.com](mailto:izeno.contact@gmail.com).
- **Subject**: Use the subject line `[Security Vulnerability] JavaFX Quiz App`.
- **Details**: Include the following in your report:
  - A description of the vulnerability.
  - Steps to reproduce the issue.
  - Potential impact (e.g., data exposure, unauthorized access).
  - Any suggested fixes, if applicable.
- **Confidentiality**: Do not disclose the vulnerability publicly until we have had a chance to address it.

### What to Expect

- **Acknowledgment**: We will acknowledge receipt of your report within 48 hours.
- **Investigation**: We will investigate the issue and determine its severity.
- **Resolution**: We will work to release a fix as quickly as possible, typically within 30 days for critical issues.
- **Disclosure**: Once the issue is resolved, we will coordinate with you on public disclosure, if desired.

## 🔒 Security Practices

To maintain the security of the JavaFX Quiz App, we follow these practices:

- **Dependency Management**: We use Maven to manage dependencies and regularly update to the latest secure versions.
- **Database Security**: SQLite database operations are parameterized to prevent SQL injection.
- **Input Validation**: User inputs are validated and sanitized to prevent common vulnerabilities like XSS.
- **Secure Development**: We follow secure coding practices, including peer reviews for critical changes.
- **Regular Audits**: We periodically review the codebase for security issues.

## 📜 Supported Versions

We provide security updates for the latest version of the JavaFX Quiz App. Please ensure you are using the most recent release to benefit from security fixes.

## 🙏 Acknowledgments

We thank all security researchers and contributors who help us keep the JavaFX Quiz App secure. If you report a valid vulnerability, we will acknowledge your contribution in our release notes (with your permission).

<p align="center">
  <a href="https://ko-fi.com/O4O6LO7Q1" target="_blank">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="ko-fi" style="border: 0;">
  </a>
</p>
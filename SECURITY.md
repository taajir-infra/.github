# Security Policy

## Reporting Security Vulnerabilities

The taajir-infra organization takes security seriously. We appreciate your efforts to responsibly disclose your findings.

### How to Report a Security Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report security vulnerabilities by:

1. **Opening a private security advisory** in the relevant repository (if enabled)
2. **Emailing the security team** (if contact information is available)
3. **Opening a confidential issue** with the `security` label

### What to Include

When reporting a security vulnerability, please include:

- Type of vulnerability
- Full paths of affected source files
- Location of the affected code (tag/branch/commit or direct URL)
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the vulnerability

### Response Timeline

- **Initial Response**: Within 48 hours of receiving the report
- **Status Updates**: Regular updates on progress toward a fix
- **Resolution**: Coordinated disclosure once a fix is available

## Supported Versions

Security updates are applied to the following versions:

| Version | Supported          |
| ------- | ------------------ |
| main    | :white_check_mark: |
| other   | :x:                |

We recommend always using the latest version from the `main` branch.

## Security Best Practices

When contributing to our repositories:

- Never commit sensitive information (credentials, tokens, keys)
- Use environment variables for configuration
- Keep dependencies up to date
- Follow secure coding practices
- Enable security features (branch protection, required reviews)

## Disclosure Policy

We follow a coordinated disclosure process:

1. Security issue is reported privately
2. Issue is confirmed and investigated
3. Fix is developed and tested
4. Security advisory is prepared
5. Fix is released
6. Advisory is published

Thank you for helping keep our projects and community safe!

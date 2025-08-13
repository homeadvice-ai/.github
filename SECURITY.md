# Security Policy

## Supported Versions

We actively provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take security vulnerabilities seriously. If you discover a security vulnerability in any of our repositories, please report it responsibly.

### How to Report

1. **Do not** open a public GitHub issue for security vulnerabilities
2. Email us directly at: **security@foxly-labs.com**
3. Include the following information:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

### What to Expect

- **Acknowledgment**: We'll acknowledge receipt of your report within 24 hours
- **Initial Assessment**: We'll provide an initial assessment within 72 hours
- **Regular Updates**: We'll keep you updated on our progress weekly
- **Resolution**: We aim to resolve critical issues within 14 days, and other issues within 30 days

### Security Response Process

1. **Triage**: We'll assess the severity and impact of the reported vulnerability
2. **Investigation**: Our security team will investigate and validate the issue
3. **Development**: We'll develop and test a fix
4. **Disclosure**: We'll coordinate responsible disclosure with you
5. **Release**: We'll release the security update and advisories

## Security Best Practices

### For Contributors

- Always use the latest versions of dependencies
- Run security audits regularly (`npm audit`, `pip audit`, etc.)
- Follow secure coding practices
- Never commit secrets, tokens, or credentials to the repository
- Use environment variables for sensitive configuration
- Validate all inputs and sanitize outputs
- Keep dependencies up to date

### For Users

- Keep your installations up to date
- Use strong authentication methods
- Review and monitor access permissions regularly
- Report suspicious activity immediately
- Follow the principle of least privilege

## Security Tools and Practices

We use various security tools and practices:

- **Dependency Scanning**: Automated dependency vulnerability scanning
- **Static Analysis**: Code security analysis (SAST)
- **Dynamic Analysis**: Runtime security testing (DAST)
- **Security Reviews**: Regular security code reviews
- **Incident Response**: Established incident response procedures

## Security Training

All team members receive regular security training covering:

- Secure coding practices
- Common vulnerability types (OWASP Top 10)
- Incident response procedures
- Data protection and privacy requirements

## Compliance

We maintain compliance with:

- Industry security standards
- Data protection regulations (GDPR, CCPA, etc.)
- Privacy requirements
- Audit requirements

## Contact Information

For security-related inquiries:

- **Email**: security@foxly-labs.com
- **Response Time**: Within 24 hours
- **PGP Key**: Available upon request

## Attribution

We appreciate the security research community and will acknowledge researchers who responsibly disclose vulnerabilities (unless they prefer to remain anonymous).

---

**Note**: This security policy applies to all repositories within the foxly-labs organization. For repository-specific security considerations, please refer to individual repository documentation.

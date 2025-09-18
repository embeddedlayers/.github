# Security Policy

## Our Commitment

The EmbeddedLayers security team takes the security of our software products and services seriously. We appreciate your efforts to responsibly disclose your findings.

## Supported Versions

Our team actively maintains security updates for the following versions:

| Project | Version | Supported          |
| ------- | ------- | ------------------ |
| MCP Analytics | 1.x.x | ✅ Active Support |
| PDai | 1.x.x | ✅ Active Support |
| PDaiPostgres | 1.x.x | ✅ Active Support |

## Reporting a Vulnerability

### Where to Report

**DO NOT** create public GitHub issues for security vulnerabilities.

Please report security vulnerabilities to our security team at:
**security@embeddedlayers.com**

### What to Include

To help our security team triage and prioritize your report, please include:

- Type of issue (e.g., buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact assessment
- Any potential mitigations you've identified

### Response Process

1. **Initial Response**: Our security team will acknowledge receipt within 24-48 hours
2. **Triage**: The security team will evaluate the report and assign a severity level
3. **Investigation**: Our engineering team will investigate and validate the finding
4. **Resolution**: We'll work on a fix and coordinate disclosure timing with you
5. **Disclosure**: Once patched, we'll publish a security advisory

### Response Timeline

- **Critical** (CVSS 9.0-10.0): Patch within 24-48 hours
- **High** (CVSS 7.0-8.9): Patch within 7 days
- **Medium** (CVSS 4.0-6.9): Patch within 30 days
- **Low** (CVSS 0.1-3.9): Patch in next regular release

## Security Measures

### What We Do

Our security team implements:
- Regular dependency scanning
- Automated security testing in CI/CD
- Code reviews with security focus
- Penetration testing for major releases
- Security training for our development team
- Incident response procedures

### Data Protection

- All data transmission uses TLS 1.2+
- OAuth2 for API authentication
- Encryption at rest for sensitive data
- Regular security audits
- GDPR/CCPA compliance measures
- Isolated Docker containers for processing

## Recognition

We value the security research community. Researchers who responsibly disclose vulnerabilities may be:
- Acknowledged in security advisories
- Listed in our security hall of fame
- Invited to collaborate with our security team

## Contact

- **Security Issues**: security@embeddedlayers.com
- **General Support**: support@embeddedlayers.com
- **PGP Key**: Available upon request for sensitive communications

---

*This policy is maintained by the EmbeddedLayers Security Team and reviewed quarterly.*

*PeopleDrivenAI LLC (DBA EmbeddedLayers) - Committed to Security Excellence*
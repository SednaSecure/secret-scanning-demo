# Security Policy

## Supported Versions

This repository is a demonstration project.

| Version | Supported |
|---------|-----------|
| main    | Yes       |

## Reporting a Vulnerability

Please do not create a public GitHub issue for security vulnerabilities.

Instead, report security issues privately to the repository maintainers.

Include:

- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested remediation, if known

## Secret Scanning Demo

This repository may intentionally contain fake credentials for demonstrating GitHub Secret Scanning and Push Protection.

**Never use real credentials in this repository.**

Any credential-looking values included in this repository are test values only.

## If a Real Secret Is Accidentally Committed

1. Revoke or rotate the credential immediately.
2. Remove the credential from the source code.
3. Check Git history for additional exposure.
4. Review the GitHub Secret Scanning alert.
5. Confirm that the credential is no longer valid.
6. Close the security alert after remediation.

## Security Features Demonstrated

This repository can be used to demonstrate:

- GitHub Secret Scanning
- Push Protection
- Custom Secret Scanning Patterns
- Code Scanning
- Dependabot
- Branch Protection Rules
- Pull Request Reviews
- Required Status Checks

## Disclaimer

This repository is intended for security training and demonstrations only.

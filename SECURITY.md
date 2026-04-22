# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability in ClipMemory, please report it responsibly.

**Do NOT open a public GitHub issue for security vulnerabilities.**

Instead, please email us at: **security@bitleader.dev**

Or use [GitHub Security Advisories](https://github.com/bitleader-dev/ClipMemory-releases/security/advisories/new) to report the vulnerability privately.

### What to include

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact
- Suggested fix (if any)

### Response timeline

- **Acknowledgment**: Within 48 hours
- **Initial assessment**: Within 5 business days
- **Fix release**: Depending on severity, typically within 1-2 weeks

### Scope

The following are in scope:
- ClipMemory desktop application
- Auto-update mechanism
- Local data storage security

The following are out of scope:
- Third-party dependencies (report to the respective maintainers)
- Issues requiring physical access to the device

## Data Handling

ClipMemory stores clipboard data locally on your device at `%LocalAppData%\ClipMemory\`. No clipboard data is transmitted to external servers. The only network communication is checking for updates via GitHub Releases API.

For more details, see our [Privacy Policy](docs/PRIVACY.md).

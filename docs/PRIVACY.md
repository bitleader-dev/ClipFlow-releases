# Privacy Policy

**Effective Date:** April 14, 2026
**Last Updated:** April 14, 2026

BitLeader inc. ("we", "us", or "our") operates the ClipFlow application (the "App"). This Privacy Policy explains how we handle information when you use our App.

## Summary

**ClipFlow does not collect, transmit, or share any personal data such as clipboard contents.** All clipboard data stays on your device. We only collect anonymous crash and error reports to improve app stability.

## Information We Do NOT Collect

- We do **not** collect clipboard contents
- We do **not** collect personal information (name, email, etc.)
- We do **not** use cookies or tracking technologies
- We do **not** access your contacts, calendar, or other personal data

## Crash & Error Reporting (Sentry)

To improve app stability, ClipFlow uses **Sentry** (Functional Software, Inc.) for automatic crash and error reporting. When an unexpected error occurs, the following **anonymous, non-personal** data is sent:

| Data | Purpose |
|------|---------|
| Error type and stack trace | Identify and fix bugs |
| App version and build | Determine affected versions |
| OS version and architecture | Reproduce environment-specific issues |
| .NET runtime version | Runtime compatibility diagnosis |
| Breadcrumbs (recent app actions) | Understand the sequence of events leading to the error |

**What is NOT sent:**
- Clipboard contents (text, images, files) are **never** transmitted
- No personal identifiers (no user ID, no device ID, no IP-based tracking)
- No clipboard history or stored data
- No file names or file contents

Crash reports are processed by Sentry's EU data center (Frankfurt, Germany) and retained for 90 days. For more information, see [Sentry's Privacy Policy](https://sentry.io/privacy/).

## Data Stored Locally

ClipFlow stores the following data locally on your device:

| Data | Location | Purpose |
|------|----------|---------|
| Clipboard history | `%LocalAppData%\ClipFlow\Clipboard\` | Core functionality |
| App settings | `%LocalAppData%\ClipFlow\settings.json` | User preferences |
| Clipboard images | `%LocalAppData%\ClipFlow\Clipboard\images\` | Image clip storage |
| Temporary files | `%LocalAppData%\ClipFlow\temp\` | Drag-and-drop operations |
| Diagnostic logs | `%LocalAppData%\ClipFlow\Logs\` | Local troubleshooting |
| Crash report cache | `%LocalAppData%\ClipFlow\sentry-cache\` | Offline crash report buffer |

This data (except crash reports) is stored only on your device and is never transmitted to any server.

## Network Communication

ClipFlow makes the following network requests:

- **Update check**: On startup, the App contacts the GitHub Releases API (`api.github.com`) to check for new versions. This request includes only the App's user agent string ("ClipFlow-Updater") and does not transmit any personal data.
- **Update download**: When an update is available, the App downloads the update package from GitHub.
- **Crash reporting**: When an error occurs, an anonymous crash report is sent to Sentry (`ingest.de.sentry.io`). See "Crash & Error Reporting" section above.

No other network communication occurs.

## Third-Party Services

- **Sentry** (Functional Software, Inc.): Used for anonymous crash and error reporting. Data is processed in the EU (Frankfurt). Subject to [Sentry's Privacy Policy](https://sentry.io/privacy/).
- **GitHub** (Microsoft): Used solely for update distribution. Subject to [GitHub's Privacy Policy](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- **Microsoft Store** (if installed via Store): Subject to [Microsoft's Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement).

## Data Deletion

To delete all data stored by ClipFlow:

1. Uninstall the application
2. Delete the folder `%LocalAppData%\ClipFlow\`

## Children's Privacy

ClipFlow does not knowingly collect any information from children under the age of 13.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page with an updated "Last Updated" date.

## Contact

If you have questions about this Privacy Policy, please contact us:

- GitHub Issues: [https://github.com/bitleader-dev/ClipFlow-releases/issues](https://github.com/bitleader-dev/ClipFlow-releases/issues)

---

&copy; 2026 BitLeader inc. All rights reserved.

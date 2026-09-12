# Security Policy

## Reporting a vulnerability

If you believe you've found a security issue in any GhostBundle app, please report it **privately** rather than opening a public issue.

**How to report:**
- Use GitHub's private vulnerability reporting: go to the **Security** tab → **Report a vulnerability**.
- Or email: adaia.daci@yahoo.com

I'll acknowledge your report as soon as I can, usually within a few days.

## Scope

GhostBundle apps run fully offline and store data locally. They do not connect to the internet, collect telemetry, or phone home. The most relevant security concerns would be:

- File handling (opening or saving unexpected file types)
- Local data integrity (corrupting `ghostnotes.ghn`, `session.txt`, etc.)
- Crashes triggered by malformed input

## Out of scope

- Missing features
- Cosmetic issues
- Issues in third-party libraries (please report those upstream: NAudio, PdfiumViewer, PDFium)

## Supported versions

Only the latest release of each app is supported with security fixes.

Thanks for helping keep GhostBundle safe. 🖤

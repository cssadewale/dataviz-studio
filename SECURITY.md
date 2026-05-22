# Security Policy

## Overview

Tableau Stimulator is a client-side only application. All data processing happens entirely
within the user's browser. No data is transmitted to any server, stored in any database,
or shared with any third party.

## Data Privacy

- **Your data never leaves your browser.** All CSV files are processed in browser memory only.
- **No cookies.** The application does not set any cookies.
- **No tracking.** No analytics, no telemetry, no usage tracking of any kind.
- **No accounts.** No login, no registration, no user data collected.
- **Workspace files** are downloaded to your local device only — never uploaded anywhere.

## Supported Versions

| Version | Support Status |
|---|---|
| v7.x | Active — all fixes applied |
| v6.x | Security fixes only |
| v5.x and below | Not supported |

## Reporting a Vulnerability

**Do not open a public GitHub Issue for security vulnerabilities.**

Contact the author directly:

- Email: buildingmyictcareer@gmail.com
- LinkedIn: https://linkedin.com/in/adewalesamsonadeagbo

### What to Include

1. Description of the vulnerability
2. Steps to reproduce it
3. Potential impact
4. Any suggested fixes (optional)

### Response Timeline

- Acknowledgement: Within 48 hours
- Assessment: Within 7 days
- Fix (if confirmed): Within 30 days for critical issues

## Known Limitations

- **Formula evaluation** uses `new Function()` (equivalent to `eval`) to compute calculated fields.
  Only use Tableau Stimulator with CSV files from trusted sources.
- **Inline cell editing** modifies data in browser memory only — no changes persist to the original file.
- **Not designed for PII** in production environments. Anonymise sensitive data before uploading.


## Creator / Owner

This repository is maintained by **Adewale Samson Adeagbo** — Data Scientist, STEM Educator, EdTech Builder and AI-Augmented Solutions Developer based in Lagos, Nigeria.

- Portfolio: https://cssadewale.pages.dev
- HMG Concepts: https://hmgconcepts.pages.dev
- GitHub: https://github.com/cssadewale
- LinkedIn: https://linkedin.com/in/adewalesamsonadeagbo
- YouTube: https://youtube.com/@hmgconcepts
- WhatsApp: +234 810 086 6322
- Email: hmgconcepts@gmail.com / hismarvellousgrace@gmail.com

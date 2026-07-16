# Cookie Emporium — Legal Documents

This repository hosts the public legal documents for **Cookie Emporium**, served via GitHub Pages.

It's kept as a small, separate, public repository so that the privacy policy and terms of service URLs stay live and accessible — even though the main [Cookie Emporium](https://github.com/KRYMauL/Cookie-Emporium) source code repository is private.

## Live pages

- **Privacy Policy:** [krymaul.github.io/Cookie-Emporium-legal/privacy-policy.html](https://krymaul.github.io/Cookie-Emporium-legal/privacy-policy.html)
- **Terms & Conditions:** [krymaul.github.io/Cookie-Emporium-legal/terms-and-conditions.html](https://krymaul.github.io/Cookie-Emporium-legal/terms-and-conditions.html)

## Why this repo exists

Google Play requires a live, publicly accessible privacy policy URL for as long as an app remains published. Keeping these documents in their own lightweight repo means:

- The main app source can stay private without breaking Play Store compliance
- These pages can be updated independently of app releases
- There's nothing here worth protecting, so there's no reason to restrict access

### Security rationale

The main Cookie Emporium repository contains application source code, including monetization logic (ads and in-app purchases). Keeping it private reduces the risk of the app being rebuilt from source and redistributed without ads or purchases intact.

This legal documents repo contains no application code, no build configuration, and no proprietary logic — only static HTML pages required for store compliance. Separating the two means the app source can stay locked down without ever risking the privacy policy or terms going offline as a side effect.

## Updating these documents

1. Edit `privacy-policy.html` or `terms-and-conditions.html` directly
2. Commit and push to `main`
3. GitHub Pages redeploys automatically — changes are typically live within a few minutes

No build step, no dependencies — these are plain, self-contained HTML files.

# 拾形 support website

**English** | [繁體中文](README.zh-TW.md)

Public support and privacy website for 拾形, an iPhone app that reconstructs Gaussian models locally. This repository contains only static website files; no app source, captures, or private review contact information.

- [Website](https://zstar1003.github.io/shixing-app-site/)
- [Support](https://zstar1003.github.io/shixing-app-site/support.html)
- [Privacy](https://zstar1003.github.io/shixing-app-site/privacy.html)
- [Design](docs/plans/2026-10-17-site-design.md)

## Preview and deployment

Run `python3 -m http.server 8765` here and open `http://localhost:8765`. No build step, packages, JavaScript, tracking, or form backend. GitHub Pages serves the root of `main` over HTTPS. Changes go through a task branch and PR; merge only after reviewing links, factual copy, privacy, keyboard use and narrow-screen layout.

Verify the homepage, support page and privacy page return HTTP 200 after deployment. To correct a published mistake, revert the relevant commit through another PR and verify Pages redeploys. Keep the public support email current. Do not add private scan images, phone numbers or account details. The decorative illustration is explicitly labeled as a diagram, not a scan result. The app is still being prepared for release.

# Focuslane

> A quiet focus workspace with a Pomodoro timer, task queue, and daily progress.

[![Quality checks](https://github.com/bhargav-del/focuslane/actions/workflows/quality.yml/badge.svg)](https://github.com/bhargav-del/focuslane/actions/workflows/quality.yml)
[![Latest release](https://img.shields.io/github/v/release/bhargav-del/focuslane?display_name=tag&sort=semver)](https://github.com/bhargav-del/focuslane/releases)
[![License](https://img.shields.io/github/license/bhargav-del/focuslane)](https://github.com/bhargav-del/focuslane/blob/main/LICENSE)

A quiet focus workspace with a Pomodoro timer, task queue, and daily progress. Built as a local-first, dependency-light product experience with a browser build, a portable Windows desktop build, and a scheduled Android APK release.

## What it demonstrates

- 25 / 50 / 90-minute focus blocks
- Pause, resume, reset, and short-break flow
- Local task queue with completion state
- Streak context and deep-work metrics

## Run locally

This is a zero-build static app for the browser:

```bash
git clone https://github.com/bhargav-del/focuslane.git
cd focuslane
python3 -m http.server 4173
```

Open <http://localhost:4173>.

For syntax and metadata checks:

```bash
node --check app.js
```

## Project structure

```text
├── index.html                 Product UI
├── styles.css                 Responsive visual system
├── app.js                    Product interactions
├── desktop/main.cjs           Windows Electron shell
├── capacitor.config.json      Android shell configuration
├── .github/workflows/         Quality, Pages, Windows, and Android automation
└── CHANGELOG.md               Release history
```

## Releases

- [Browser source and releases](https://github.com/bhargav-del/focuslane/releases)
- The Windows portable `.exe` is built by GitHub Actions.
- The Android 7+ (API 24+) `v1.0.0` APK is scheduled for **September 16, 2026 at 08:00 IST**.

## Privacy and security

The core experience runs locally in the browser. No credentials are required. See [SECURITY.md](SECURITY.md) for responsible disclosure guidance.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for setup, testing, and pull-request expectations.

## Roadmap

- Add richer empty and error states
- Expand keyboard navigation
- Add end-to-end browser coverage for the highest-value flows
- Keep the product lightweight before adding network dependencies

## License

MIT © 2026 Yuin

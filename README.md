# Focuslane

A calm focus workspace that makes starting easier.

Focuslane combines a Pomodoro timer, a small task queue, daily progress, and gentle cues for getting into deep work without turning productivity into a noisy scoreboard.

## Highlights
- 25 / 50 / 90-minute focus blocks
- Pause, resume, reset, and short-break flow
- Local task queue with completion state
- Daily focus metrics and streak context
- Responsive, keyboard-friendly UI
- No build step and no external credentials

## Run locally

```bash
python3 -m http.server 4173
```

Open http://localhost:4173.

## License
MIT © 2026 Yuin

## Desktop release

The repository includes a portable Windows desktop build. Every push to `main` runs the Windows packaging workflow and publishes a `.exe` to the repository's **Releases** section. The desktop shell loads the same app locally, so it works without an API key or server.

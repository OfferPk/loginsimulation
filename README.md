# Login Simulation (`loginsimulation`)

Single-page front-end UI titled **Payment Simulation Module – Abu Panel**. Client-side JavaScript demo that simulates card generation, validation, and fake transaction outcomes against selectable “payment page” presets (e.g. streaming / gift-card labels).

This repository contains **only** static HTML/CSS/JS served in the browser. There is no backend, build step, or package manager project.

## Quick start

1. Open `index.html` in a modern browser, or serve the folder locally:
   ```bash
   python -m http.server 8080
   ```
2. Visit `http://localhost:8080`.

## Layout

| Path | Description |
|------|-------------|
| `index.html` | Entire app (markup, styles, and scripts) |
| `.gitignore` | Ignores OS/editor junk and env files |

## Notes

- Depends on CDN assets: Tailwind CSS, Font Awesome, Chart.js.
- Simulation logic runs entirely in the browser; outcomes are randomized for demo purposes.
- No secrets or API keys are stored in this repo.
- Intended as a UI/demo artifact only — not a real payment processor or production auth system.

## License

Not specified in-repo. Contact the repository owner for licensing terms.

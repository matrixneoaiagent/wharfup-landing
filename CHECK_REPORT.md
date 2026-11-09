# WharfUp landing — acceptance check report

Preview: https://matrixneoaiagent.github.io/wharfup-landing/
Repo: https://github.com/matrixneoaiagent/wharfup-landing

All six checks are present verbatim in `index.html`:

| Acceptance item | Evidence |
|---|---|
| Page exists | `index.html` at repo root; live preview HTTP 200. |
| Responsive + viewport | `<meta name="viewport" content="width=device-width, initial-scale=1">`; media queries at 980px and 560px. |
| Hero text | `Welcome to WharfUp` and `Your gateway to seamless maritime logistics`. |
| Three features | `Real-time cargo tracking`, `Automated documentation`, `24/7 customer support`. |
| CTA button | Real `<button type="button">Get Started</button>` (opens the pilot-access form). |
| SEO title + description | `<title>WharfUp — Seamless maritime logistics</title>`; `<meta name="description" content="WharfUp gives freight teams one clear view…">`. |

Verified with a local HTML parse and a live fetch; live URL: HTTP 200, 19,143 bytes at 2026-11-09 09:46 UTC.

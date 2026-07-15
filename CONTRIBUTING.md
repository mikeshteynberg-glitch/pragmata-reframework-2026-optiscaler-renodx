# Contributing

Thanks for improving the suite.

## Before you open a PR

- Test on Windows or Linux (Proton) with a real game build
- One change per PR — preset, doc fix, or platform patch
- Add a line to `CHANGELOG.md` under the current version

## What we need most

- GPU-tier presets (budget / mid / flagship)
- Proton and Steam Deck compatibility notes
- RENODX shader profile contributions

## Profile rules

- No API keys or absolute local paths in committed JSON
- Name files by intent: `ultrawide.json`, `deck.json`, etc.
- Document target resolution and hardware in the PR body

## Issues

Include OS, GPU, driver version, active profile, and a log snippet from `./logs/`.

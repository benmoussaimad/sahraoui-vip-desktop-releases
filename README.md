# Sahraoui VIP — desktop updates (public)

This repository is **only** the public update channel for the Sahraoui VIP Windows app:

- `updater/latest.json` — manifest read by installed clients (`raw.githubusercontent.com`)
- **GitHub Releases** — signed NSIS installers (`.exe` + signatures)

Application source code stays in the private `pos-cafe-frontend` repository. Nothing secret belongs here.

CI on the private repo publishes each release here automatically when `DESKTOP_UPDATES_PAT` is configured.

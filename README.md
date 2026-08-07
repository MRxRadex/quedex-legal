# radex-team-legal

Published legal documents for apps by Valerii Morhun.

| Document | Live URL |
|---|---|
| Privacy Policy (Quedex) | https://mrxradex.github.io/radex-team-legal/ |

## How this is maintained

`index.html` is generated from `docs/privacy_policy.md` in the Quedex
repository, which is the source of truth. When the analytics event contract
changes, update the policy there first, then regenerate and push here.

The page is a single self-contained file: no build step, no dependencies, no
external requests. GitHub Pages serves it straight from `main`.

## Planned

This will move to `quedexgame.com/privacy` once the domain is set up. Until
then the GitHub Pages URL is what ships in the app and in the store listings.

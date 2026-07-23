# US Data Center Capital Map

An interactive map of known US hyperscale and AI data center projects — plotted by location and announced capital, and colored by lifecycle (Meta in blue; peers by under construction / recently delivered / sold-recapitalized).

Click any node to open a deal dossier showing the **capital stack** (equity vs. debt), **deal terms** (spread, GMP, hyperscaler guarantees, lease terms, rent commencement where public), the **counterparties by role** (GP/developer, LP, lender/bond, power provider, tenant), and the **long-term asset owner** for platform sales.

**Live site:** https://jdr5791.github.io/datacenter-capital-map/

Covers **41 projects**, including **all 28 of Meta's US data center locations** (per [datacenters.atmeta.com](https://datacenters.atmeta.com/us-locations/)).

## What it covers

- **Meta** — all 28 US campuses: Hyperion (Blue Owl JV + sale-leaseback) and El Paso (project bond) are the only two with external capital; the other 26 (Prometheus, Altoona, Prineville, Sarpy, etc.) are wholly-owned balance-sheet builds
- **Peer hyperscale / AI** — Stargate/Abilene (Crusoe/Oracle/OpenAI), xAI Colossus, AWS Project Rainier, Microsoft Fairwater, Stargate Michigan/Milam, CoreWeave, Digital Realty × Blackstone
- **Sold / recapitalized platforms** (long-term owners) — Aligned ($40B, AIP/MGX/BlackRock GIP), CyrusOne (KKR/GIP), QTS (Blackstone), Switch (DigitalBridge/IFM), Vantage (DigitalBridge/Silver Lake)

## Method

Assembled entirely from public sources — company releases, investor-relations material, securities filings, and trade press. Per-deal source links appear in each dossier. Fields that are not public (GMP, LP identities, some spreads) are marked "Not publicly disclosed" rather than estimated. Not an investment recommendation.

Built as a single self-contained `index.html` (Plotly.js for the map). No build step.

# MAP Machine Arcade

A retro-arcade dashboard of MAP-machine call-outs at the Aurora facility, covering the last two months (May 8 – Jul 8, 2026) of Slack maintenance/FSQA/escalation data.

Open [`index.html`](index.html) directly, or enable GitHub Pages on this repo (Settings → Pages → Deploy from branch `main` / root) to view it live.

Four selectable stages:

- **Stage 1 · Overview** — volume, weekly/daily trend, status mix, escalation & O2-direction meters
- **Stage 2 · Time Attack** — shift, weekday, and hour-of-day patterns
- **Stage 3 · Player Rankings** — top reporters and resolvers, with average clear time
- **Stage 4 · Boss Room** — hottest lines, downtime distribution, root-cause themes

Data source: Aurora's `issues_log.csv` maintenance log. All figures are computed from 208 MAP-related call-outs (Oxygen/MAP line issues plus direct MAP-machine sealing reports).

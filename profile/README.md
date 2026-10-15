# Clutch

Clutch was a free browser extension that made [Renown.gg](https://renown.gg) (CS2 matchmaking) suck less: FACEIT ranks and team ELO on match pages, match and party auto-accept, ban history, map stats during the ban phase, friend ranks and a dark theme. It shipped on Chrome, Edge, Opera and Firefox in 2025.

**Renown shut down on 30 January 2026** ([their announcement](https://renown.gg/blog/renown-is-shutting-down)), and Clutch stopped working with it. The code stays here, read-only, as an archive.

**Clutch moved on to [setpos.gg](https://setpos.gg)**, a CS2 utility site: instant smoke lineups pulled from pro demos, for every spawn. Come hang out on the [setpos Discord](https://discord.gg/vmDcBmxUt4).

Playing FACEIT now? Get [FACEIT Vision](https://faceitvision.net), a browser extension by our friends and the best one out there.

## Repositories

| Repository | What it is | State |
| --- | --- | --- |
| [website](https://github.com/renown-clutch/website) | The extension's landing page. Static Astro, no client JavaScript. | Live at [clutch.lorem.sh](https://clutch.lorem.sh) |
| [extension](https://github.com/renown-clutch/extension) | The browser extension. Svelte 5, TypeScript, Tailwind, Manifest V3, one codebase for Chrome and Firefox. | Archived |
| [crawler](https://github.com/renown-clutch/crawler) | The backend. Python crawlers that indexed Renown matches, players, bans and FACEIT profiles, and the FastAPI service the extension called. | Archived, offline |
| [privacy-policy](https://github.com/renown-clutch/privacy-policy) | The extension's privacy policy. Settings stayed on your device. | Archived |

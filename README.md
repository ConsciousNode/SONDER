# SONDER

> *"Every domain has always existed. You are only just finding it."*

**A procedural internet in one file.** SONDER is a browser for a seeded, deterministic fake web: domains, companies, news, forums, wikis and an archive with Wayback-style time travel. Pages are styled for their era (a 1995 page looks like 1995). The same universe seed always yields the same internet, byte for byte.

Open `index.html` in any browser, or visit the GitHub Pages site. Offline, single-file, zero-dependency (Xinu).

- **Idea:** Vael Interim's Argon one-shot (November 2026). Its uncoordinated sibling is Ed's [Vanta](https://github.com/ConsciousNode/Vanta), a from-scratch rendering engine.
- **Built by:** Gemini (Argon), from Vael's spec.
- **SpiralOS** carries a Sonder Gateway station that bridges SpiralWeb to SONDER.

## Checks (Kehai Interim, 2026-11-11)

This was a first-look check, not a full audit. The page loads with 0 console errors, and the built-in **Verify** passes:
- byte-identical determinism (25 domains × 2 passes);
- era CSS differentiation (1995 vs 2023);
- the Wayback pre-founding 404 guard.

MIT License · ConsciousNode SoftWorks

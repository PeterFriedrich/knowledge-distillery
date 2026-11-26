# knowledge-distillery

Many sources in, one clear brief out, read or heard.

A personal system that collects podcasts, feeds and reports, filters them to
what the owner cares about, merges the facts sources share, highlights what
each source adds, and delivers digests as text or audio.

## Modules

- **reportcast** (first): narrates reports into a private podcast feed.
  Existing code is coming over as v0.2.

## Constraints

- Everything stays free: a Claude subscription, the free Gemini tier, and
  local text-to-speech (Kokoro). No paid APIs.
- Runs on the owner's Oracle ARM server (aarch64) and publishes through
  GitHub Pages. A Pages URL is unlisted, not secret.
- Code is public; collected source text lives in the private repo
  `knowledge-distillery-data`.

Expect to iterate. Started from `cc-data-project-template` (`docs/COPIER.md`).

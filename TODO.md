# TODO

The source of truth for what's left. Read first every session; update in place.

**Format contract** (`tools/todo_archive.py` depends on it): top-level items are
`- [ ]` / `- [x]` lines directly under `## Open work`; `###` sub-headings may
group them; closed items are moved to `docs/TODO_archive.md` by the tool, which
leaves a one-line stub under `## Done`. An open item can be stale — reproduce the
symptom and re-measure the stated cause before acting on it.

## Open work

- [ ] **Decide what runs on the laptop vs the Oracle box, and how the feed is served.** Large or temporary work (TTS, raw audio, big downloads) probably runs on the owner's laptop; the box has ~6 GB free disk shared by every project. A GitHub Pages feed is public: on the free plan Pages publishes only from a public repo, so the "private" feed is unlisted at best, and audio committed to the repo is visible in its history. Narrating others' reports and serving them publicly is republishing. Options seen: unlisted Pages deployed through Actions (audio not in the repo), serving the feed from the box behind a token (a server-side port/tunnel decision for `server`), or narrating only redistributable reports. Owner, 2026-11-26: settle this during the laying-down work, by what actually fits. Done when the split and the feed route are a `docs/DECISIONS.md` row and the README's Constraints match.
- [ ] **Bring reportcast over as v0.2.** The existing code isn't on the box or on GitHub yet; it comes from wherever it lives now.

## Done

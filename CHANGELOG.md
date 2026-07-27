# Changelog

## v0.3 — Importable Baseline

### Added
- Repository charter and project structure.
- Hall of Fame.
- Candidate pool.
- Chapter and review documentation.
- A clean 78-track CSV containing only entries marked found by the Spotify import result.
- A 22-entry unresolved metadata list.

### Preserved
- Original v0.2 Spotify import output in `data/spotify-import-results-v0.2.csv`.

### Removed from the importable release
- 22 entries that Spotify did not match. They remain candidates, not rejected songs.

### Reasoning
The project needed a trustworthy baseline before replacements and sequencing changes. No unresolved track was silently renamed or substituted.

### Next goals
- Verify the Hall of Fame against exact Spotify metadata.
- Resolve or replace all 22 misses.
- Score and sequence the first 25–30 tracks of v0.9.
- Add Spotify URLs and IDs where available.

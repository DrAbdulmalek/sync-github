# Archival Status — sync-github

> ✅ **This repository is archived on GitHub as of 2026-07-31.**

## Why archived

This was a simple 54-line bash script that scanned `~/GitHub` for all
git repos and synced them with `git pull --ff-only`. Its functionality
is fully covered by [`repo-sync-toolkit`](https://github.com/DrAbdulmalek/repo-sync-toolkit)
as the **Simple Sync** mode (option 8 in the menu, or
`sync-scripts/simple-sync.sh`).

## Migration

| Old (this repo) | New (repo-sync-toolkit) |
|-----------------|------------------------|
| `bash sync-github.sh` | `./sync-scripts/simple-sync.sh [DIR]` |
| Interactive menu option 8 | Menu option 8: "Simple Sync (no config)" |

## Verification

- GitHub archive flag: `true` (verified via API on 2026-07-31).
- README already declared archival; this doc confirms the GitHub state
  now matches the README claim.
- No further changes will be made to this repo. To revive it, un-archive
  via GitHub Settings → Danger Zone → un-archive.

## Reference

- `ECOSYSTEM_STATE.md` in `repo-sync-toolkit` — ecosystem state.

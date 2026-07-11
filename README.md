# sync-github — ⚠️ ARCHIVED

> **This repository has been archived. Development has stopped.**
> 
> All functionality has been merged into [repo-sync-toolkit](https://github.com/DrAbdulmalek/repo-sync-toolkit) as the **Simple Sync** mode (option 8 in the menu, or `sync-scripts/simple-sync.sh`).

## Migration

| Old (this repo) | New (repo-sync-toolkit) |
|-----------------|------------------------|
| `bash sync-github.sh` | `./sync-scripts/simple-sync.sh [DIR]` |
| Interactive menu option 8 | Menu option 8: "Simple Sync (no config)" |

## What repo-sync-toolkit adds on top

- Interactive menu with 18 options
- Push/pull/bidirectional/custom sync
- Dry-run mode
- HuggingFace Spaces support
- Real-time monitoring (inotifywait + polling)
- systemd service integration
- Governance checking
- PyCharm integration
- Token management

## Original purpose

This was a simple 54-line script that scanned `~/GitHub` for all git repos and synced them with `git pull --ff-only`. It served its purpose well for zero-config batch syncing, but repo-sync-toolkit now covers this use case and much more.

---

**Use repo-sync-toolkit going forward:** https://github.com/DrAbdulmalek/repo-sync-toolkit

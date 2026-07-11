# sync-github

Lightweight one-command script to sync all local GitHub repositories.

## Usage

```bash
bash sync-github.sh
```

Scans `~/GitHub/*/`, pulls latest changes, and reports success/failure for each repo.

## Features

- Auto-detects `main` vs `master` branch naming
- Fixes unlinked branches automatically
- Handles diverged histories with `reset --hard` fallback
- Summary report: success/fail/total counts

## vs Repo Sync Toolkit

> **Note**: This is a lightweight helper script for quick bulk sync. For the full-featured sync system with TUI dashboard, token management, HuggingFace support, and real-time monitoring, see [repo-sync-toolkit](https://github.com/DrAbdulmalek/repo-sync-toolkit).

## Requirements

- `git` installed
- GitHub repositories cloned under `~/GitHub/`

## License

MIT
<p align="center">
  <img src="https://raw.githubusercontent.com/mindlore/.github/main/assets/mindlore-logo.png" alt="Mindlore" width="320">
</p>

<p align="center">
  AI-native knowledge system for Claude Code.
</p>

Knowledge persists across sessions. Search happens automatically. Knowledge compounds over time.

## How it works

```
Session Start  → inject last delta + INDEX + version check
During Session → FTS5 layered search (project + global, top 3)
Session End    → structured delta + global git sync
```

Mindlore operates through 14 hooks and 11 skills — invisible background scripts that fire as you work. No commands to run, no workflow changes.

## Quick Start

```bash
npx mindlore init
```

## Links

- [GitHub](https://github.com/mindlore/mindlore)
- [npm](https://www.npmjs.com/package/mindlore)

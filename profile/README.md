# Mindlore

AI-native knowledge system for Claude Code.

Knowledge persists across sessions. Search happens automatically. Knowledge compounds over time.

## How it works

```
Session Start  → inject last delta + INDEX
During Session → FTS5 search on every prompt (top 3 results)
Session End    → structured delta (decisions, changes, open questions)
```

Mindlore operates through Claude Code lifecycle12 hooks — invisible background scripts that fire as you work. No commands to run, no workflow changes.

## Quick Start

```bash
npx mindlore init
```

## Links

- [GitHub](https://github.com/mindlore/mindlore)
- [npm](https://www.npmjs.com/package/mindlore)
- [Changelog](https://github.com/mindlore/mindlore/blob/main/CHANGELOG.md)

## Stats

- 12 hooks | 7 skills | 9-column FTS5 with porter stemmer
- 3 OS x 2 Node CI matrix
- Zero telemetry, zero external services

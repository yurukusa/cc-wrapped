# CC Wrapped

**Spotify Wrapped, but for Claude Code.**

Paste your `cc-session-stats --json` output and get a beautiful, slide-by-slide reveal of your AI usage stats.

**[Try it now](https://yurukusa.github.io/cc-wrapped/)**

## What You Get

- **7 animated slides** revealing your AI stats
- **8 personality types** based on usage patterns (Night Owl, Marathon Runner, All In, etc.)
- **Fun facts** — movie equivalents, coffee counts, streak records
- **Shareable PNG card** — download or share directly to X/Twitter
- **Zero dependencies** — single HTML file, no tracking, runs in your browser

## How to Use

```bash
# 1. Get your stats
npx cc-session-stats --json | pbcopy  # macOS
npx cc-session-stats --json | xclip   # Linux

# 2. Open CC Wrapped
open https://yurukusa.github.io/cc-wrapped/

# 3. Paste and unwrap
```

## Personality Types

| Type | Icon | Trigger |
|------|------|---------|
| Night Owl | 🦉 | Peak activity on Fri/Sat |
| Early Bird | 🐦 | Peak activity on Mon/Tue |
| Weekend Warrior | ⚔️ | >45% hours on weekends |
| Marathon Runner | 🏃 | Longest session >4h |
| Daily Grinder | ⚡ | High streak, short sessions |
| Hyperfocused | 🎯 | Top project >80% of time |
| Polymath | 🌐 | 4+ significant projects |
| All In | 🔥 | >80h total or >3h/day avg |

## cc-toolkit

| Tool | What it does |
|------|-------------|
| [cc-health-check](https://yurukusa.github.io/cc-health-check/) | 20-check setup diagnostic (CLI + web) |
| [cc-session-stats](https://github.com/yurukusa/cc-session-stats) | Usage analytics from session data |
| [cc-audit-log](https://github.com/yurukusa/cc-audit-log) | Human-readable audit trail |
| [cc-cost-check](https://yurukusa.github.io/cc-cost-check/) | Cost per commit calculator |
| **[cc-wrapped](https://yurukusa.github.io/cc-wrapped/)** | Your AI year in review |
| [cc-roast](https://yurukusa.github.io/cc-roast/) | Your CLAUDE.md, brutally honest |

## License

MIT

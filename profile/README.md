# interesting-vibe-coding 🐾

**Tools for the AI coding era** — built around one question: what should the *human* be doing while the agent works?

Not just games. Not just status lights. A small ecosystem of things that make working alongside AI agents feel more natural, more human, and a little more fun.

## Projects

| Repo | What it does |
|------|-------------|
| [**paws**](https://github.com/interesting-vibe-coding/paws) 🐾 | Terminal companion for AI coding agents — press CMD+G to open a game while the agent works; a live status HUD flashes when it needs you back. Supports Kiro CLI, Claude Code, and Codex CLI. |
| [**paws-games**](https://github.com/interesting-vibe-coding/paws-games) | The community game library — Dog Jump · Earth Online · Tetris. Lua plugins, PRs welcome. |
| [**paws-dock**](https://github.com/interesting-vibe-coding/paws-dock) | _(in design)_ Physical ambient interface — moves agent state off the screen and into the room. Light, sound, maybe touch. Works with any agent, not just Paws. |
| [**homebrew-paws**](https://github.com/interesting-vibe-coding/homebrew-paws) | Homebrew tap — `brew install paws`. |

## Quick start

```bash
brew tap interesting-vibe-coding/paws
brew install paws          # launcher + status HUD
brew install paws-games    # Dog Jump · Earth Online · Tetris
```

Then wire up your agent hooks — the [install skill](https://github.com/interesting-vibe-coding/paws/blob/main/skills/paws-install/SKILL.md) handles it — and press **CMD+G**.

## Philosophy

The agent is doing the work. The human should be doing something good with that time — not refreshing a terminal, not doom-scrolling, not missing the moment it needs them back.

Everything here tries to make that handoff cleaner, calmer, and worth looking forward to.

- **You stay in control** — the HUD flags you; it never auto-switches.
- **Zero config** — install and go; agents are auto-detected.
- **Plugin-friendly** — games, integrations, and hardware are all open to contribution.

---

Made by [Do a bit](https://doabit.dev) · MIT

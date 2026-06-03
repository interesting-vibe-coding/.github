# interesting-vibe-coding 🐾

**Interesting ways to vibe-code** — small, playful tools for the age of AI coding agents.

Not just games. We build things that make coding-with-AI feel more human: companions that
wait with you, toys that live in your terminal, and little experiments for the
"agent is thinking…" minutes. More on the way.

## Projects

| Repo | What it does |
|------|-------------|
| [**paws**](https://github.com/interesting-vibe-coding/paws) 🐾 | A terminal companion for AI coding agents — play a game while it works; a live status HUD flags you back the moment it needs you. Supports Kiro CLI, Claude Code, and Codex CLI. |
| [**paws-games**](https://github.com/interesting-vibe-coding/paws-games) | The community game library Paws plays from — Dog Jump · Earth Online · Tetris. PRs welcome. |
| [**homebrew-paws**](https://github.com/interesting-vibe-coding/homebrew-paws) | Homebrew tap — `brew install paws`. |

## Quick start

```bash
brew tap interesting-vibe-coding/paws
brew install paws          # the launcher + status HUD
brew install paws-games    # Dog Jump · Earth Online · Tetris
```

Then add the [Kaku](https://github.com/tw93/kaku) Lua snippet and your agent's hooks — the
[install skill](https://github.com/interesting-vibe-coding/paws/blob/main/skills/paws-install/SKILL.md)
does it for you — and press **CMD+G**.

## Philosophy

- **Zero config** — install and go; the HUD auto-detects running agents.
- **Plugin-friendly** — any terminal binary on your PATH can be a game; install more right from the menu.
- **You stay in control** — the HUD only flags you, it never auto-switches.

---

Made by [Do a bit](https://doabit.dev) · MIT

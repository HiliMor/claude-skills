# Claude Skills

A collection of custom slash commands for [Claude Code](https://code.claude.com).

## Installation

Copy any skill file to your Claude Code commands directory:

```bash
cp commands/claude-whats-new.md ~/.claude/commands/
```

Then restart Claude Code — the command will appear when you type `/`.

---

## Skills

### `/claude-whats-new`

Fetches the official Claude Code changelog and summarizes what's new in plain language.

**Usage:**
- `/claude-whats-new` — short summary of the latest release only
- `/claude-whats-new full` — detailed summary of all recent releases with explanations and examples
- `/claude-whats-new since March 2025` — filter by date or version

**Highlights:**
- TL;DR at the top — the single most important change
- Breaking changes called out separately
- Short by default, detailed on demand

**Source:** [Claude Code Changelog](https://code.claude.com/docs/en/changelog)

---

## Contributing

Feel free to open a PR with your own skills.

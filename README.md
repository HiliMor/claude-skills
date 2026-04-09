# Claude Skills

A collection of custom slash commands for [Claude Code](https://code.claude.com).

## Installation

Copy any skill file to your Claude Code commands directory:

```bash
cp <skill-name>.md ~/.claude/commands/
```

Then restart Claude Code — the command will appear when you type `/`.

---

## Skills

### `/claude-whats-new`

Fetches the official Claude Code changelog and summarizes what's new in plain language — not just listing features, but explaining why they matter and how to use them.

**Highlights:**
- TL;DR at the top — the single most important change
- Breaking changes called out separately
- Practical usage examples for each feature
- Filter by version or date (e.g. `/claude-whats-new since March 2025`)

**Source:** [Claude Code Changelog](https://code.claude.com/docs/en/changelog)

---

## Contributing

Feel free to open a PR with your own skills.

# Claude Skills

A collection of custom slash commands for [Claude Code](https://code.claude.com).

## Installation

Copy any skill file to your Claude Code commands directory:

```bash
cp commands/<skill-name>.md ~/.claude/commands/
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

### `/what-i-learned`

Extracts key lessons from the current conversation and saves them as a dated file in `~/claude-learning-log/`.

**Usage:**
- `/what-i-learned` — run at the end of any session to capture what's worth remembering

**Highlights:**
- 3–7 real lessons per session, not a recap
- Short examples where helpful
- Each session saved as its own file: `YYYY-MM-DD-topic.txt`
- Builds a personal knowledge log over time

---

### `/learn`

Explains any concept in simple beginner-friendly language and saves it automatically to `~/claude-learning-log/`.

**Usage:**
- `/learn git hooks` — explains git hooks and saves the lesson
- `/learn what is an API` — explains APIs and saves the lesson
- `/learn CSS flexbox` — explains flexbox and saves the lesson

**Highlights:**
- Simple language with real-world analogies
- One practical example per concept
- Auto-saved as a dated file in `~/claude-learning-log/`
- No manual step needed

---

## Contributing

Feel free to open a PR with your own skills.

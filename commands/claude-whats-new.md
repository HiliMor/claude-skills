Fetch the Claude Code changelog and summarize what's new.

Check if the user typed "full" after the command (e.g. `/claude-whats-new full`).

- **Default (no argument):** short summary of the most recent release only
- **Full mode (`full`):** detailed summary with explanations and examples, all recent releases

## Instructions

1. Use WebFetch to load: https://code.claude.com/docs/en/changelog
2. Read the full page content
3. If the user passed a version number or date (e.g. "since v1.5" or "since March 2025"), only include changes from that point onward.

### Default mode
- Cover the most recent release only
- One bullet per change, one line each
- No examples, no lengthy explanations
- Start with a single TL;DR sentence

### Full mode
- Cover all recent releases
- For each change: what it is → why it matters → short practical example
- Call out breaking changes in a dedicated section at the top
- Start with a single TL;DR sentence

## Output Format — Default

### TL;DR
One sentence — the most important change.

### What's New (latest release)
- bullet
- bullet

## Output Format — Full

### TL;DR
One sentence — the most important change.

### Breaking Changes (if any)
- What broke and what to do

### What's New in Claude

#### Models
- **Name**: what it is → why it matters → how to use it

#### Claude Code / CLI
- **Feature**: what it is → why it matters → how to use it

#### API & Tools
- **Feature**: what it is → why it matters → how to use it

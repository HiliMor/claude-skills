Fetch the Claude Code changelog and produce a clear, practical summary of what's new — not just listing features, but explaining what they mean and how to use them.

## Instructions

1. Use WebFetch to load: https://code.claude.com/docs/en/changelog
2. Read the full page content
3. If the user passed a version number or date (e.g. "since v1.5" or "since March 2025"), only include changes from that point onward. Otherwise summarize the most recent release.
4. For each change:
   - Say what it is in plain language
   - Explain **why it matters** (what problem it solves)
   - Add a short practical example of **how to use it** where relevant
5. Call out breaking changes in a dedicated section at the top
6. Start with a single TL;DR sentence summarizing the most important change

## Output Format

### TL;DR
One sentence — the single most important change in this release.

---

### Breaking Changes (if any)
- List anything that might break existing setups, with what to do about it

### What's New in Claude

#### Models
- **Name**: what it is → why it matters → how to use it

#### Claude Code / CLI
- **Feature**: what it is → why it matters → how to use it

#### API & Tools
- **Feature**: what it is → why it matters → how to use it

---
name: what-i-learned
description: Extracts key lessons from the current conversation and appends them to a personal learning log at ~/claude-learning-log.txt
---

Review the current conversation and extract what was genuinely learned — not a summary of what was discussed, but the actual lessons, concepts, or skills that someone would want to remember.

## Instructions

1. Read the conversation and identify 3–7 key takeaways
2. For each takeaway:
   - One clear sentence explaining the lesson
   - One short example if it makes the lesson clearer (skip if obvious)
3. Determine the main topic of the session (2–4 words)
4. Format the output as shown below
5. Append the result to ~/claude-learning-log.txt using a bash command
6. Confirm to the user that it was saved

## Rules
- Keep it short — the whole entry should be readable in under a minute
- No fluff, no restating what was discussed — only what's worth remembering
- If nothing meaningful was learned, say so and don't write to the file

## Output Format

```
[YYYY-MM-DD] — Topic
• Lesson one. Example: short example if needed.
• Lesson two. Example: short example if needed.
• Lesson three.
```

## Saving
1. Create the folder ~/claude-learning-log/ if it doesn't exist
2. Generate a filename from the date and topic: YYYY-MM-DD-topic-in-kebab-case.txt (e.g. 2026-04-09-claude-skills.txt)
3. Write the entry to that new file
4. Confirm the filename to the user

---
name: atomic-extraction
description: Convert unstructured text into structured atomic notes using the Leadership OS templates. Useful for meetings, logs, or long-form notes that need to be broken down.
argument-hint: "[sourceText]"
user-invocable: true
---

# atomic-extraction

Use this skill to break unstructured text into atomic notes.

## Expected behavior
- Identify distinct ideas in the provided text.
- For each idea, propose:
  - A note title
  - A target folder
  - A template type (atomic, system, decision, person, meeting)
- Output suggested note bodies in Markdown.

## Parameters
- **sourceText**: Raw text to extract notes from.
- **defaultFolder** (optional): Suggested folder for new notes.

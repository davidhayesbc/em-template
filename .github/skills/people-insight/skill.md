---
name: people-insight
description: Update a person's note based on recent 1-1s and observations. Useful for maintaining accurate People profiles and preparing for future conversations.
argument-hint: "[personFile]"
user-invocable: true
---

# people-insight

Use this skill to update a person's profile in the People/ folder.

## Expected behavior
- Read the person's note and any provided 1-1 notes.
- Update or propose updates to:
  - Strengths
  - Growth areas
  - Motivators
  - Frustrations
- Suggest follow-up questions for the next 1-1.

## Parameters
- **personFile**: Path to the person’s note.
- **oneOnOneFiles** (optional): Paths to recent 1-1 notes.

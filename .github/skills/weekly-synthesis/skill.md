---
name: weekly-synthesis
description: Summarize a week's Daily-Logs into themes, insights, decisions, risks, and follow-ups. Useful when reviewing multiple daily notes and preparing weekly summaries or leadership updates.
argument-hint: "[weekPath]"
user-invocable: true
---

# weekly-synthesis

Use this skill to synthesize a week of Daily-Logs.

## Expected behavior
- Read all files matching the provided path or glob.
- Extract key events, themes, insights, decisions, and risks.
- Produce a concise weekly summary.
- Suggest which items should become atomic notes.

## Parameters
- **weekPath**: A folder or glob pattern such as Daily-Logs/2026-05-*.md.

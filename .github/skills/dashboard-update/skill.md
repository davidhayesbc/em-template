---
name: dashboard-update
description: Propose updates to the Leadership Dashboard using recent Weekly-Summaries. Useful for keeping priorities, risks, and decisions current.
argument-hint: "[weeklySummaryFiles]"
user-invocable: true
---

# dashboard-update

Use this skill to update the Leadership Dashboard.

## Expected behavior
- Read the specified weekly summaries.
- Propose concrete edits to:
  - Current priorities
  - Active risks
  - Team health signals
  - Open decisions
- Output suggested changes as a patch or replacement section.

## Parameters
- **weeklySummaryFiles**: Array of paths to weekly summary files.

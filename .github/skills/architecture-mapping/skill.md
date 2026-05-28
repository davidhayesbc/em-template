---
name: architecture-mapping
description: Summarize and map a system's architecture, dependencies, and reliability concerns. Useful for understanding platform components and identifying risks.
argument-hint: "[systemFile]"
user-invocable: true
---

# architecture-mapping

Use this skill to analyze or summarize a system.

## Expected behavior
- Summarize the system’s purpose, dependencies, and SLIs/SLOs.
- Highlight known pain points and risks.
- Suggest improvements or follow-up notes.

## Parameters
- **systemFile**: Path to the system note.
- **relatedFiles** (optional): Paths to related Architecture, Incidents, or Risks notes.

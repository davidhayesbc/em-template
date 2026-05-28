---
name: decision-ledger
description: Create or update decision records using the Decision template. Useful for ADR-style documentation and tracking architectural or organizational decisions.
argument-hint: "[context] [outcome]"
user-invocable: true
---

# decision-ledger

Use this skill to record decisions in the Decisions/ folder.

## Expected behavior
- Propose a filename under Decisions/.
- Use the Decision template structure.
- Link to any related notes if provided.

## Parameters
- **context**: Short description of the decision context.
- **options** (optional): Options that were considered.
- **outcome**: The chosen option and rationale.
- **relatedFiles** (optional): Paths to related notes.

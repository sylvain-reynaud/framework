---
name: 11-persona
description: Produces an evidence-backed user persona the product and experience work can reason from. Use when the user wants to define, revise, compare, or list who the product serves. Not for requirements, stories, or screens.
argument-hint: product | segment | persona
---

# Persona

```mermaid
flowchart LR
  new([product or segment]) --> frame
  existing([persona]) --> frame
  frame -->|"list"| inventory([Persona inventory])
  frame -->|"no product"| brief([Product Brief offered])
  frame --> discover
  discover -->|"ready or assumptions accepted"| shape
  shape -->|"evidence gap"| discover
  shape --> finalize
  finalize -->|"learn more"| discover
  finalize -->|"revise persona"| shape
  finalize -->|"authorized"| done([Persona])
```

## Actions

Run the flow above. Read only the next action file.

| Action   | Does                                |
| -------- | ------------------------------------ |
| frame    | resolve the product, the case, and the evidence path |
| discover | research, question, and challenge     |
| shape    | compose one persona                   |
| finalize | refine, approve, and persist          |

## Transversal rules

- Keep product decisions with the user.
- Separate evidence, decisions, and assumptions.
- Ask natural questions; never expose actions, references, or unchanged state.
- Require explicit approval or caller-provided bounded authority before any write.

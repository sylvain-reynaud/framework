---
name: 03-engagement-system
description: Designs the product's motivation and gamification system, from core loop to celebrations, with ethical guardrails. Use when the user wants the app to build habits, reward progress, or feel as engaging as a game. Not for a single screen or for code.
argument-hint: product | engagement
---

# Engagement System

```mermaid
flowchart LR
  source([product or engagement]) --> frame
  frame --> model
  model --> mechanics
  mechanics --> safeguard
  safeguard -->|"mechanic rejected"| mechanics
  safeguard --> finalize
  finalize -->|"revise"| model
  finalize -->|"authorized"| done([Engagement System])
```

## Actions

Run the flow above. Read only the next action file.

| Action    | Does                                            |
| --------- | ------------------------------------------------ |
| frame     | scope the product, personas, and the core action |
| model     | build the motivation model and core loop          |
| mechanics | select and calibrate mechanics                    |
| safeguard | check every mechanic against the ethics guardrails |
| finalize  | refine, approve, and persist                       |

## Transversal rules

- Never propose a dark pattern.
- Require explicit approval or caller-provided bounded authority before any write.

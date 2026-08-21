# Celebrations

Celebration intensity scales with how often the trigger fires and how much it means.

## Tiers

| Tier | Frequency | Consequence | Example | Duration |
| --- | --- | --- | --- | --- |
| Micro | every core-action completion, high frequency | low | check mark, small counter increment, subtle haptic | under 1 second, non-blocking |
| Medium | milestone reached, weekly or periodic | moderate | banner, brief animation, short sound cue | 1-3 seconds, skippable |
| Full | rare, once per real achievement | high | full-screen animation, confetti, sound | skippable, at most once per achievement |

## Rules

- Motion: respect `prefers-reduced-motion`; every tier has a static equivalent with no animation.
- Sound: off by default; never autoplay sound without explicit consent.
- Skippability: every celebration above micro is dismissible in one action.
- Proportionality: a full-tier celebration for a micro-frequency event is a red flag; over-celebration erodes trust as much as under-celebration flattens the moment.

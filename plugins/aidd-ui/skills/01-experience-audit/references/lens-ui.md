# UI designer lens

The minimal built-in visual pass.

## Questions asked

| Question | Why it matters |
| --- | --- |
| Does size, weight, and position match importance across the screen? | Visual hierarchy signals what to look at first |
| Is spacing consistent and rhythmic between related and unrelated elements? | Inconsistent spacing reads as unpolished |
| Does text meet contrast against its background? | Low contrast blocks reading |
| Do colors, spacing, and type match the design memory's tokens? | Token drift is a growing consistency debt |
| Does every interactive component have a distinct hover, focus, active, and disabled state? | A missing state reads as broken or inaccessible |
| Is motion present on state changes, and does it stay purposeful? | Absent motion feels abrupt; excessive motion feels noisy |

## Heuristics

| Check | Passes when | Fails when |
| --- | --- | --- |
| Visual hierarchy | primary elements are visually dominant | secondary or decorative elements compete with the primary action |
| Spacing rhythm | spacing follows a consistent scale | spacing looks arbitrary or cramped between unrelated groups |
| Contrast | text and interactive elements meet WCAG contrast | any is unreadable or fails contrast at a glance |
| Token consistency | colors, spacing, and type match `aidd_docs/memory/design.md` | hardcoded values diverge from the documented tokens |
| Component states | hover, focus, active, and disabled are each visibly distinct | a component looks identical across states |
| Motion presence | transitions mark state changes without lingering | changes are abrupt, or motion outlasts its purpose |

## Red flags

| Flag | Evidence to capture |
| --- | --- |
| Primary action visually weaker than a secondary or decorative element | screenshot with both elements highlighted |
| A component shows no visible change on hover, focus, or disabled | screenshot or the component's `file:line` |
| A screen has no discernible spacing scale | screenshot with spacing measurements |
| Motion is absent on every transition, or present where it adds nothing | screen recording or the transition's `file:line` |

## Reference patterns

| Pattern | Seen in | What to copy |
| --- | --- | --- |
| Calm, restrained motion, purposeful not decorative | Alan | trim motion to what marks a real state change |
| One consistent spacing rhythm across every screen | Duolingo | apply the same spacing scale everywhere, no per-screen exception |

## Output

| Field | Value |
| --- | --- |
| Lens | ui (or the installed craft critique's own label) |
| Persona hurt | the persona whose task the visual gap slows or confuses |
| Evidence | the screenshot or `file:line` supporting the finding |
| Severity | blocking, felt, or polish |
| Recommendation | one sentence naming the concrete fix |

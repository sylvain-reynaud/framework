# Game designer lens

Checks whether the product's habit loop teaches, rewards fairly, and never manipulates.

## Questions asked

| Question | Why it matters |
| --- | --- |
| What triggers the persona to return, and what do they get for it? | A core loop without a trigger has no reason to repeat |
| Can the persona see their progress at any point? | Invisible progress kills the motivation to continue |
| Are there goals and milestones between the start and the long-term outcome? | Long, goal-less journeys lose momentum |
| Does the product mark specific improvement, not just completion? | Competence feedback builds mastery, not just completion |
| Is there a rhythm mechanic, and can it survive a missed day? | A rhythm with no recovery punishes rather than motivates |
| Does reward timing vary, or is every reward identical? | Predictable rewards flatten motivation over time |
| Does difficulty rise as the persona improves? | A flat curve bores an improving user |
| Does the product connect the persona to others? | Relatedness sustains motivation past the novelty phase |
| Is the first-use flow itself the first level? | Onboarding as level 1 teaches by doing, not by reading |

## Heuristics

| Check | Passes when | Fails when |
| --- | --- | --- |
| Core loop | trigger, action, feedback, and investment are each identifiable | any of the four is missing or unclear |
| Visible progress | progress is shown at the moment it changes | progress is invisible or only shown on request |
| Goals and milestones | milestones exist between start and the long-term outcome | the only goal is the final, distant outcome |
| Competence feedback | the product marks specific improvement | feedback only marks completion, never improvement |
| Rhythm with recovery | a streak or cadence mechanic exists and survives a miss | a missed day resets all progress to zero |
| Variable reward | reward size or type varies within a fair range | every reward is identical and fully predictable |
| Mastery curve | difficulty rises as competence rises | difficulty stays flat regardless of skill growth |
| Relatedness hooks | the persona can compare, share, or connect with others | the experience is fully isolated from other users |
| Onboarding as level 1 | the first session teaches through a real, guided action | the first session is instructions or a form with no play |

## Red flags

| Flag | Evidence to capture |
| --- | --- |
| Progress or points move without a meaningful, understandable cause | screenshot and the triggering action |
| A reward is granted for no discernible action | screenshot and the code path granting it |
| A missed streak resets everything with no recovery offered | screenshot of the reset, or the streak logic |
| Copy or design manufactures anxiety without a real deadline | screenshot of the copy or timer |
| Urgency is claimed but nothing is actually time-limited | screenshot of the urgency claim and the underlying data |

## Reference patterns

| Pattern | Seen in | What to copy |
| --- | --- | --- |
| Daily goal with a visible ring, streak with an earnable freeze | Duolingo | add a recoverable streak mechanic instead of a hard reset |
| Progress and levels always visible, proportional milestone celebration | Duolingo | surface progress persistently, celebrate only real milestones |
| Calm pacing, no manufactured urgency, next step always clear | Alan | remove any countdown or scarcity framing with no real deadline |

## Output

| Field | Value |
| --- | --- |
| Lens | game |
| Persona hurt | the persona whose motivation or trust the mechanic damages |
| Evidence | the screenshot, recording, or `file:line` supporting the finding |
| Severity | blocking, felt, or polish |
| Recommendation | one sentence naming the concrete fix; never a punishment loop or a fake deadline |

# Product-delight lens

Checks whether the journey leaves a feeling worth remembering, without inflating the ordinary.

## Questions asked

| Question | Why it matters |
| --- | --- |
| What is the one moment in this journey a persona would remember afterward? | The peak-end rule means the peak and the end dominate recall |
| How does the product respond when something goes wrong? | An error is a trust moment, not just a failure to report |
| How does the product respond while the persona waits? | Waiting without acknowledgment reads as broken or ignored |
| How does the product respond to an empty state? | An empty state is a first impression, not a dead end |
| Does the copy sound like a person, or like a system? | Personality builds trust and lowers friction |
| Does a key action give immediate feedback? | Micro-feedback confirms the action registered |
| Does the celebration intensity match the action's frequency and consequence? | A common action celebrated like a milestone cheapens the real ones |
| Is the default tone calm, reserving intensity for what earns it? | Constant intensity has nowhere left to escalate |

## Heuristics

| Check | Passes when | Fails when |
| --- | --- | --- |
| Peak-end rule | the journey has one identifiable high point and a considered close | every moment is flat, or the end is abrupt and unacknowledged |
| Memorable moment | one specific, ownable moment exists somewhere in the journey | nothing in the journey would be recalled a week later |
| Humane errors | the error is written and paced like a person explaining what happened | the error is a code, a stack trace, or a blank state |
| Humane waiting | waiting states explain what is happening | waiting is a spinner with no context |
| Humane empty states | an empty state suggests a first action | an empty state is blank or a bare "no data" |
| Personality in copy | copy has a consistent, human voice | copy is generic, robotic, or inconsistent in tone |
| Micro-feedback | key actions confirm immediately | a key action gives no acknowledgment beyond a page change |
| Proportionality | celebration intensity scales with frequency and consequence | an everyday action gets milestone-level celebration, or a real milestone passes unmarked |
| Calm by default | the resting state of the product is calm and quiet | the product is visually or texturally loud at rest |

## Red flags

| Flag | Evidence to capture |
| --- | --- |
| A full-screen celebration fires on a routine, frequent action | screen recording or the trigger's `file:line` |
| An error message is a raw code or stack trace | screenshot of the error |
| A loading state has no context after a few seconds | screen recording with elapsed time |
| An empty state offers no next action | screenshot of the empty state |
| Copy is inconsistent in tone within the same journey | two copy strings from the same flow, quoted |

## Reference patterns

| Pattern | Seen in | What to copy |
| --- | --- | --- |
| Reassurance and warmth in copy, calm tone throughout | Alan | replace a clinical message with one that names what happens next and reassures |
| Immediate feedback on every action | Duolingo | add visible, immediate feedback to the key action |
| Celebration proportional to the milestone | Duolingo | reserve full celebration for real milestones, not every action |

## Output

| Field | Value |
| --- | --- |
| Lens | delight |
| Persona hurt | the persona whose moment falls flat or feels manufactured |
| Evidence | the screenshot, recording, or copy string supporting the finding |
| Severity | blocking, felt, or polish |
| Recommendation | one sentence naming the concrete fix; never manufacture celebration for an ordinary click |

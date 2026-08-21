# UX designer lens

Checks whether the screen answers the persona's question without making them think.

## Questions asked

| Question | Why it matters |
| --- | --- |
| Does the first screen answer the persona's question within 3 seconds, above the fold? | Glanceability decides whether the persona trusts the product immediately |
| Is the most important information the most visually prominent? | Weak hierarchy hides the answer behind decoration |
| Is advanced detail hidden until asked for? | Progressive disclosure keeps the primary path short |
| How many steps or screens sit between intent and outcome? | Flow length compounds abandonment |
| How many decisions or fields does one screen demand at once? | Cognitive load sets the completion rate |
| Does every state exist and read clearly? | A missing state reads as broken |
| Does the copy say what will happen in plain words? | Ambiguous copy causes hesitation and mistakes |
| When something fails, does the persona know what to do next? | Recovery decides whether a failure ends the session |
| Do a first-time and a returning persona get a distinct, appropriate entry? | A return visit should not repeat onboarding |

## Heuristics

| Check | Passes when | Fails when |
| --- | --- | --- |
| Glanceability | the primary answer is visible with no scroll or interaction | the persona must scroll, click, or infer to get the answer |
| Information hierarchy | size, weight, and position match importance | a secondary element outweighs the primary action or data |
| Progressive disclosure | detail is one interaction away | every field or option is exposed at once |
| Flow length | the primary journey uses the fewest necessary steps | a step exists that does not change the outcome |
| Cognitive load | one primary decision per screen | several unrelated decisions compete on one screen |
| States coverage | loading, empty, error, and success each have a distinct treatment | any state falls back to a blank screen or a raw error |
| Copy clarity | copy names the action and its result in plain words | copy is jargon, ambiguous, or system-centric |
| Error recovery | the error names the cause and the next step | the error is a code, a dead end, or a blank |
| First-use and return paths | a first-timer is guided; a returner is not re-onboarded | both see the identical, unadapted screen |

## Red flags

| Flag | Evidence to capture |
| --- | --- |
| Answer requires a scroll or click on the primary screen | screenshot with the fold line marked |
| Primary action visually subordinate to decoration | screenshot with both elements highlighted |
| A state has no distinct treatment (loading renders blank, error shows a stack) | screenshot of the state, or the render path |
| A flow step exists that does not change the outcome | the step's screen and the step it could skip to |
| Copy uses internal or technical terms the persona would not know | the exact copy string and its screen |

## Reference patterns

| Pattern | Seen in | What to copy |
| --- | --- | --- |
| One clear status, plain language, next step always visible | Alan | state the current status once, in plain words, with the next action beside it |
| One action per screen | Duolingo | strip a multi-decision screen to its single next action |
| Progress always visible on multi-step flows | Duolingo | keep a persistent progress indicator across the flow |
| Reassurance before risk | Alan | name what will not go wrong before an irreversible action |

## Output

| Field | Value |
| --- | --- |
| Lens | ux |
| Persona hurt | the persona whose question goes unanswered |
| Evidence | the screenshot or `file:line` supporting the finding |
| Severity | blocking, felt, or polish |
| Recommendation | one sentence naming the concrete fix |

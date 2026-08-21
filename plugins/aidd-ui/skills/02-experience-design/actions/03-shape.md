# 03 - Shape

Turn each persona's job and arc into a flow of screens, each carrying its data priority, its states, and its tone.

## Input

The persona jobs, first questions, and emotional arcs from immerse.

## Output

The feature's flow and, per screen, the first question it answers, its ranked data, its state matrix, and its copy tone.

## Process

1. **Flow.** Lay out the screens the feature needs, in the order a persona moves through them, ending at the job done.
2. **Prioritize.** Apply [screen data](../references/screen-data.md) to each screen.
3. **States.** Apply [states](../references/states.md) to each screen.
4. **Tone.** Name the copy tone for each screen, consistent with the persona's stakes and the arc it is in.
5. **Check.** Apply [brief quality](../references/brief-quality.md) to the shaped screens.
6. **Show.** Present the flow and screens without persisting them.

## Test

| Case | Pass |
| --- | --- |
| Screen without a first question | no shown screen lacks a first question |
| Screen data | exactly one primary number or status; secondary data ranked |
| States | every applicable state from `states.md` covered, or marked not applicable |
| High-stakes screen | reassurance ranked ahead of information, per the emotional arc |
| Layout or visual choice proposed | rejected; shape names data and states only, never layout or visuals |

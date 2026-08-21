# 02 - Discover

Build an evidence-aware understanding of who this persona represents.

## Input

The framed product or segment, any starting draft, evidence path, and user feedback.

## Output

The current situation, jobs, motivation, rhythm, evidence, and assumptions for this persona.

## Process

1. **Inspect.** Read the selected available sources.
2. **Research.** Run only the selected external research.
3. **Choose.** Apply [techniques](../references/techniques.md) only to unresolved claims.
4. **Challenge.** Surface contradictions that could change who this persona is.
5. **Probe.** Ask one question about the highest-impact gap and wait.
6. **Integrate.** Fold the answer into affected claims.
7. **Repeat.** Return to `Probe` while an unaccepted consequential gap remains.

## Test

| Case | Pass |
| --- | --- |
| Unsupported behavior claim | labeled assumption, never evidence or decision |
| Lens selected | matches the stated uncertainty in `techniques`; creates no artifact |
| Next question | exactly one unanswered, persona-changing question; no answered question repeated |
| Consequential gap | no draft unless the user accepts it as an assumption |
| Evidence available | no question asked whose answer the inspected sources already hold |

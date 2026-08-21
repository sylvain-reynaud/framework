# 01 - Frame

Establish what feature is being designed, who it is for, and what bounds it.

## Input

A spec, a user story, or a plain feature request.

## Output

The framed feature, its personas, and the constraints that shape the design.

## Process

1. **Resolve.** Identify the source artifact: a spec, a story, or a plain feature request; when nothing concrete is given, ask once for it and wait.
2. **People.** Read `aidd_docs/product/personas/*.md` for personas this feature touches.
   - When none exist, offer the persona capability.
   - When the user declines or none apply, continue with one persona explicitly labelled "assumed persona".
3. **Situate.** Read `aidd_docs/product/engagement.md` and `aidd_docs/memory/design.md` when present, and fold their constraints into the framing.
4. **Bound.** State the feature's hard constraints drawn from the source: scope, platform, timeline, or technical limits.
5. **Confirm.** Ask one question when the feature is ambiguous enough to change the design, then wait.

## Test

| Case | Pass |
| --- | --- |
| No source given | workspace unchanged; exactly one open question for the source; no field list |
| Personas missing | persona capability offered, or one persona explicitly labelled "assumed persona" |
| Engagement or design memory present | its constraints folded into the framing |
| Feature ambiguous | exactly one clarifying question asked; nothing invented |
| Feature clear | framing proceeds without asking |

# 01 - Scope

Establish what is being audited and for whom.

## Input

A url, screen, flow, or app target, and the current context.

## Output

The confirmed audit target, loaded personas, and available product context.

## Process

1. **Resolve.** Identify the target from the request: a url, a screen, a flow, or the whole app.
2. **People.** Read `aidd_docs/product/personas/*.md`.
   - When none exist, offer the persona capability, or continue with one persona explicitly labelled "assumed persona".
3. **Situate.** Read `aidd_docs/product/engagement.md` and `aidd_docs/memory/design.md` when present, and carry their content forward for the assess action.
4. **Bound.** Pick the specific screens or flow the audit covers, given the target.
5. **Confirm.** Ask one question when the scope is still ambiguous enough to change the audit, then wait.

## Test

| Case | Pass |
| --- | --- |
| No personas found | persona capability offered, or one persona explicitly labelled "assumed persona" |
| Ambiguous target | exactly one scoping question asked; workspace unchanged |
| `design.md` present | its token file is named in the output context |
| `engagement.md` present | its core action and mechanics are named in the output context |
| Target clear | scoping proceeds without asking |

# 02 - Observe

Capture the screen inventory from the browser or the source.

## Input

The confirmed target and scope.

## Output

The screen inventory: what each screen shows, in what order, per state.

## Process

1. **Capture.** Capture every scoped screen per [evidence](../references/evidence.md).
   - Url given: use the available browser capability for screenshots.
   - No url: read the components and routes covering the scoped screens.
   - Running app needed and no url: ask for one once and wait; never start a server.
2. **States.** Record, per screen, every state listed in [evidence](../references/evidence.md); mark a state unobserved rather than inventing it.
3. **Inventory.** List, per screen, the data it shows and the order it appears in.

## Test

| Case | Pass |
| --- | --- |
| Url given | a screenshot exists per screen and state, desktop and mobile, per [evidence](../references/evidence.md) naming |
| No url given | inventory built from components and routes; browser capability not invoked |
| Running app needed, no url | exactly one question asking for the url; no server started |
| State unobservable | inventory marks it unobserved instead of inventing content |

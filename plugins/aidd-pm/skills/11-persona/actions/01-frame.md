# 01 - Frame

Establish which product or segment is being profiled and which personas already exist.

## Input

A product, a segment, or the current context.

## Output

The resolved product, the existing persona set, the chosen case, and the evidence path.

## Process

1. **Resolve.** Infer the product from current context (a product brief, memory `project-brief.md`); otherwise ask for the product or segment and wait.
   - When no product can be framed, apply [handoffs](../references/handoffs.md) and stop.
2. **Inventory.** List personas already present per [persistence](../references/persistence.md), if any.
   - List asked: show the inventory with each goal and revision, then stop.
3. **Choose.** Ask whether to create a new persona, revise an existing one, or compare two, and wait.
   - Create: continue with no starting draft.
   - Revise: load the named persona as the starting draft.
   - Compare: name the personas to compare; continue to discover for whichever one changes.
4. **Ground.** Apply [evidence](../references/evidence.md) to available sources.
5. **Confirm.** Ask about any ambiguity that could change the segment and wait.
6. **Focus.** Name only project inspection or external research that could resolve a live claim.

## Test

| Case | Pass |
| --- | --- |
| Product not framed | no persona; Product Brief offered; workspace unchanged |
| No personas exist | workspace unchanged; offered to create one; no field list |
| Personas exist | inventory shown before asking create, revise, or compare |
| List asked | inventory with goal and revision per persona; no question asked |
| Segment ambiguous | workspace unchanged; one open question; no persona drafted |
| Revise chosen | response restates the named persona's goal and revision before the first question |
| Research proposed | each path names the claim it may change |

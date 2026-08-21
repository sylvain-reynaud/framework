# 01 - Frame

Establish what product is being designed for and the one action it wants repeated.

## Input

A product, an existing engagement system, or the current context.

## Output

The product scope, personas, the confirmed core action, existing mechanics, and constraints.

## Process

1. **Resolve.** Infer the product from current context (product brief, memory `project-brief.md`); otherwise ask for it and wait.
   - Existing engagement system: load it as the starting draft.
2. **Gather personas.** Load every persona at `aidd_docs/product/personas/*.md`.
   - When none exist, offer the persona capability; if declined, continue with one explicit assumed persona and label it an assumption.
3. **Confirm the core action.** State the candidate single behavior the product wants to become habitual and ask the user to confirm or correct it, then wait.
4. **Inspect.** Look for mechanics already present in the product (streaks, badges, progress bars, notifications) so the system builds on what exists rather than duplicating it.
5. **Bound.** Name constraints: platform, notification budget, brand tone, and any existing design memory `aidd_docs/memory/design.md`.

## Test

| Case | Pass |
| --- | --- |
| Product not identifiable | workspace unchanged; exactly one open question; no field list |
| No personas exist | persona capability offered; one labeled assumption used if declined |
| Core action ambiguous | exactly one confirmation question asked; response awaited |
| Existing mechanics found | listed before the model or mechanics steps run |

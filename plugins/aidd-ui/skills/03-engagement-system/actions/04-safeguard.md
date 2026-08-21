# 04 - Safeguard

Check every mechanic against the ethics guardrails before it can be finalized.

## Input

The calibrated mechanics table.

## Output

An ethics-checked mechanics table and its guardrail metrics.

## Process

1. **Check.** Apply the [ethics](../references/ethics.md) table to every mechanic.
   - When a mechanic fails a check, return to `mechanics` to redesign or drop it.
2. **Confirm accessibility.** Verify every assigned celebration respects reduced motion and sound consent per [celebrations](../references/celebrations.md).
   - When unmet, return to `mechanics` to retier.
3. **Instrument.** Select the guardrail-kind metrics from [metrics](../references/metrics.md) able to reveal anxiety or compulsive use.
4. **Show.** Present the checked table and the metrics and wait.

## Test

| Case | Pass |
| --- | --- |
| Mechanic fails the ethics table | flow returns to mechanics; the failing mechanic is not carried forward unchanged |
| All mechanics pass | table shown unchanged; guardrail metrics named |
| Guardrail metric selected | names the decision it can change |
| Reduced-motion or sound consent unmet | flagged before finalize runs |

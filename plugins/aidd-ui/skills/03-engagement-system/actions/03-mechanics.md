# 03 - Mechanics

Select and calibrate the mechanics that serve the motivation model.

## Input

The motivation model and core loop.

## Output

A selected and calibrated set of mechanics.

## Process

1. **Select.** Choose mechanics from [the catalog](../references/mechanics.md) that serve an unmet need surfaced in the model.
   - Drop any mechanic that serves no named need.
2. **Calibrate.** For each selected mechanic, set its earn rule, decay or reset rule, recovery path, and feedback.
3. **Tier.** Assign each mechanic's feedback a [celebration](../references/celebrations.md) tier matching its frequency and consequence.
4. **Show.** Present the mechanics table and wait for corrections.

## Test

| Case | Pass |
| --- | --- |
| Mechanic proposed | serves a motivation need named in the model |
| Streak-like mechanic selected | includes a freeze or recovery rule |
| Celebration tier assigned | matches frequency x consequence per `celebrations` |
| No serving need found | mechanic dropped, never added |

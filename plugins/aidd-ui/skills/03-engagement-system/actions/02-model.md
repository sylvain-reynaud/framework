# 02 - Model

Build the motivation model and core loop each persona will experience.

## Input

The framed product, its personas, and the confirmed core action.

## Output

Per persona: a motivation profile, the core loop, and the habit rhythm.

## Process

1. **Profile.** Apply [motivation](../references/motivation.md) to each persona, using its existing Motivation profile section when present; otherwise infer one and label it an assumption.
2. **Loop.** Apply [loop](../references/loop.md) to define the core loop and habit rhythm around the confirmed core action.
3. **Show.** Present the model per persona and wait for corrections.

## Test

| Case | Pass |
| --- | --- |
| Persona lacks a motivation profile | inferred profile explicitly labeled an assumption |
| Core loop drafted | trigger, action, variable reward, and investment each named |
| Return trigger proposed | none frames a loss or relies on guilt |
| Model shown | workspace unchanged; user given the chance to correct it |

# 03 - Assess

Walk every expert lens through every loaded persona against the observed evidence.

## Input

The screen inventory, its evidence, and the loaded personas.

## Output

Raw findings, one set per lens, each citing a persona and evidence.

## Process

1. **UX pass.** Apply [the UX lens](../references/lens-ux.md) to the inventory, walking every loaded persona through its questions and heuristics.
2. **UI pass.** When a frontend craft critique capability is installed, run it on the target and use its top findings in place of this lens.
   - Otherwise apply [the UI lens](../references/lens-ui.md) the same way.
3. **Delight pass.** Apply [the delight lens](../references/lens-delight.md) through every persona.
4. **Game pass.** Apply [the game lens](../references/lens-game.md) through every persona.
5. **Attribute.** Record every finding per its lens's Output table.

## Test

| Case | Pass |
| --- | --- |
| Full pass | one finding set per lens |
| Persona coverage | every loaded persona walked through every lens; none skipped |
| Craft critique installed | ui findings come from the critique's top results; [lens-ui](../references/lens-ui.md) not applied |
| Craft critique absent | [lens-ui](../references/lens-ui.md) applied as the built-in ui pass |
| Finding without evidence | held back, never asserted from opinion alone |

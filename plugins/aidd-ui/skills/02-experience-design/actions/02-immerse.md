# 02 - Immerse

Live the feature through each persona before deciding anything about screens.

## Input

The framed feature and its personas.

## Output

Per persona, the situation, the job, the first question they came to answer, and the emotional arc.

## Process

1. **Situate.** For each persona, state the situation that brings them to this feature and the job they are trying to get done.
2. **Question.** Name the single question the persona came to answer first.
3. **Arc.** Apply [emotional arc](../references/emotional-arc.md) to trace entry, during, and exit for a first use and, when the feature has repeat use, a return visit.
4. **Distinguish.** Note where a first-use arc and a return-visit arc diverge for the same persona.
5. **Confirm.** Ask about any persona whose job is unclear before continuing.

## Test

| Case | Pass |
| --- | --- |
| Multiple personas | each has its own situation, job, and first question; none merged |
| First-use feature | entry, during, and exit stated for first use |
| Repeat-use feature | first-use and return arcs both stated and distinguished |
| Persona job unclear | one question asked before shaping continues |
| Assumed persona from frame | carried through with its label intact |

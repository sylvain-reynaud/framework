# 04 - Rank

Turn raw findings into a short, ordered list of premium gaps.

## Input

The findings from every lens pass.

## Output

The top 5 premium gaps and a backlog of the rest.

## Process

1. **Dedupe.** Merge findings that name the same gap across lenses or personas into one, keeping every citing lens and persona.
2. **Score.** Apply [ranking](../references/ranking.md) to each merged gap.
   - Loop back to the observe action when scoring exposes a gap in the evidence.
3. **Shortlist.** Apply the shortlist rule of [ranking](../references/ranking.md).
4. **Recommend.** Give each shortlisted gap one concrete recommendation: which data to surface, which moment to celebrate, or which friction to remove.

## Test

| Case | Pass |
| --- | --- |
| More than 5 gaps found | exactly 5 listed as premium gaps; the rest in the backlog, ordered by score |
| Duplicate finding across lenses | merged into one gap citing every lens and persona that found it |
| Missing evidence during scoring | returns to observe; no gap ranked without evidence |
| Shortlisted gap | carries one concrete, one-sentence recommendation |
| Fewer than 5 gaps found | all listed as premium gaps; backlog empty |

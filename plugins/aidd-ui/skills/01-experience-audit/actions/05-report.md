# 05 - Report

Let the user approve, persist, and route the finished audit.

## Input

The ranked premium gaps, the backlog, the screen inventory, and its evidence.

## Output

An approved experience audit report in session or at its persisted path.

## Process

1. **Compose.** Fill [the template](../assets/experience-audit.md).
2. **Approve.** Present the complete draft and wait for authority.
3. **Place.** Apply [persistence](../references/persistence.md) to resolve the destination file.
4. **Write.** Persist the authorized report; preserve any user edits to the draft.
5. **Verify.** Read back the written file.
6. **Handoff.** Apply [handoffs](../references/handoffs.md) to the next move.

## Test

| Case | Pass |
| --- | --- |
| Unauthorized draft | workspace unchanged; response ends with one approval question |
| Authorized | file exists at `aidd_docs/tasks/<yyyy_mm>/<yyyy_mm_dd>_<slug>/experience-audit.md` |
| Read back | written content matches the approved draft |
| Existing feature folder | reused when clearly the same work, per [persistence](../references/persistence.md) |
| No write | response states that no persisted change occurred |

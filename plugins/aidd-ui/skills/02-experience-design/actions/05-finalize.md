# 05 - Finalize

Let the user refine, approve, and persist the experience brief.

## Input

The framed feature, its personas, the shaped screens, the memorable moment, and any caller-provided authority.

## Output

An authorized experience brief in session or at its resolved path. After writing, report the path and the handoff. Without a write, state that no persisted change occurred.

## Process

1. **Compose.** Fill [the template](../assets/experience.md).
2. **Authorize.** Use caller-provided bounded authority or invite revision, session approval, or persistence.
   - Without persistence authority, ask session or persist and wait.
   - Return to `shape` on a revision request.
3. **Place.** Apply [persistence](../references/persistence.md) to resolve the target path.
4. **Write.** Persist the authorized brief; preserve user edits.
5. **Verify.** Read back the written file.
6. **Handoff.** Apply the handoff in [persistence](../references/persistence.md).

## Test

| Case | Pass |
| --- | --- |
| Unauthorized draft | workspace unchanged; response ends with one open feedback question |
| Content approval only | workspace unchanged; session or persistence requested |
| Feature folder already holds a spec or brainstorm | brief reuses that folder; no duplicate task folder created |
| No feature folder | new dated task folder created |
| Written brief | read back; path matches the standard path; carries no layout or visual decision |
| Handoff | plan capability offered with the persisted path |
| No write | response states that no persisted change occurred |
| Cleanup | no comment, placeholder, or `TODO` remains in the written file |

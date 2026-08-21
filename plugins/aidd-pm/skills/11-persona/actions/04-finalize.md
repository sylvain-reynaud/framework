# 04 - Finalize

Let the user refine, extend, keep, or persist the persona.

## Input

The draft, its sources, and authority.

## Output

An authorized persona in session or at its resolved path. After writing, report its stable identity, changed fields as `before -> after`, affected relations, and verification result. Without a write, state that no persisted change occurred.

## Process

1. **Authorize.** Use caller-provided bounded authority or invite revision, discovery, session approval, or persistence.
   - Without persistence authority: ask session or persist and wait.
2. **Place.** Apply [persistence](../references/persistence.md) to resolve the authorized file.
   - Replacement: require authority for both files.
3. **Write.** Persist the authorized persona; preserve user edits.
4. **Verify.** Read back the changed persona.
5. **Continue.** Apply [handoffs](../references/handoffs.md) to the next move.

## Test

| Case | Pass |
| --- | --- |
| Unauthorized draft | workspace unchanged; response ends with one open feedback question |
| Content approval only | workspace unchanged; session or persistence requested |
| Initial persistence | one `current` persona created; relation fields absent |
| Existing persistence | one `current` persona changed; unauthorized edits preserved |
| Replacement | new persona owns `supersedes`; old persona only becomes `superseded` |
| Report | written path exists, matches the standard path, and its frontmatter parses with `goal` and `revision` |
| Write receipt | stable identity, `before -> after` fields, affected relations, and verification result reported |
| No write | response states that no persisted change occurred |

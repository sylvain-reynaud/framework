# 05 - Finalize

Let the user refine, approve, and persist the engagement system.

## Input

The checked draft, its sources, and authority.

## Output

An authorized engagement system in session or at its resolved path. After writing, report its path, changed fields as `before -> after`, and the verification result. Without a write, state that no persisted change occurred.

## Process

1. **Authorize.** Use caller-provided bounded authority or invite revision or persistence; without persistence authority, ask and wait.
2. **Place.** Apply [persistence](../references/persistence.md) to resolve the file.
3. **Write.** Persist the resolved file, adding the justify-kind metrics from [metrics](../references/metrics.md) to its Metrics section.
4. **Verify.** Read back the written file.
5. **Continue.** Offer the epic or user-stories capability for delivery, and the experience design capability when a specific feature is next.

## Test

| Case | Pass |
| --- | --- |
| Unauthorized draft | workspace unchanged; response ends with one open question |
| Content approval only | workspace unchanged; session or persistence requested |
| Initial persistence | file created at the standard path with `revision: current` |
| Existing persistence | file updated in place; unauthorized edits preserved |
| Report | written path exists, matches the standard path, and verification result is stated |

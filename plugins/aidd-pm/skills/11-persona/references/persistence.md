# Persistence

Write `aidd_docs/product/personas/<persona-slug>.md`. Every changed persona has a non-empty `goal` and one listed revision.

| Situation | Files | Revision |
| --- | --- | --- |
| No persona matches | create one | `current`; omit `supersedes` |
| Revise the current persona | update one | keep `current` and any existing `supersedes` |
| Replace the current persona | create new, update old | new: `current` + `supersedes`; old: `superseded` |
| Several personas current | one file each | `current` per persona, never across the set |

Relation values are project-relative paths.

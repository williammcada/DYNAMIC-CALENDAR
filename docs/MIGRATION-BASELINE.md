# Migration Baseline — Dynamic Calendar

**Recorded:** 18 September 2026  
**Repository:** `williammcada/DYNAMIC-CALENDAR`  
**Branch:** `main`  
**Source-preservation checkpoint:** `cf7ee7a3c2f9019f7600a1783330cbe7a8808947`  
**Record status:** Current source identity. This is not by itself a functional-test, release, or deployment claim.

## Canonical source identity

| Field | Value |
| --- | --- |
| Canonical source path | `Dynamic_Lesson_Calendar_v2.html` |
| Git blob SHA | `8904076ced6734f0dbd2d0d8685afd94b0f82b62` |
| Version represented | v2 source baseline |
| Repository source checkpoint | `cf7ee7a3c2f9019f7600a1783330cbe7a8808947` |

The checkpoint above identifies the application/planning source immediately before this normalization record was committed. Later documentation-only commits do not change the preserved application bytes.

## Verification status

| Check | Result | Evidence / limitation |
| --- | --- | --- |
| Source exists in the default branch | Passed | Repository paths and Git object identities were read directly on 18 September 2026. |
| Byte-preservation comparison | Passed | Passed — the Git blob matched the preserved Library source during the 18 September 2026 audit. |
| Functional workflow | Not run | Source preservation does not establish that imports, gameplay, reports, storage or exports work. |
| Hosted/running application | Not run | Not verified; the application is preserved as a standalone offline HTML file. |

## Documentation authority

- [`PROJECT-BRIEF.md`](PROJECT-BRIEF.md) records purpose, scope, must-retain behavior and verification requirements.
- [`change-specs/INDEX.md`](change-specs/INDEX.md) identifies approved or directional change records.
- [`MIGRATION-NOTE.md`](MIGRATION-NOTE.md) is retained as historical migration context but its pre-upload source-status language is superseded by this baseline.
- This file controls current source identity when an older brief or note says the source was unknown or “TO ESTABLISH.”

## Next gate

Use the committed v2 source as the canonical baseline and verify scheduling, local persistence, backup/restore, CSV and print behavior before further revision.

Do not label a future commit a verified release until the exact candidate has passed the project brief’s required verification and that evidence is preserved.

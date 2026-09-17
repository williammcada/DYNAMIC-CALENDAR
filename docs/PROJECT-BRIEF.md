# Project Brief — Dynamic Calendar

**Brief status:** Migration baseline / requires source verification where noted  
**Brief version:** 0.1  
**Last updated:** 18 September 2026  
**Owner:** William McAda  
**Product credit:** A WILLIAM MCADA PRODUCT  
**Handbook repository:** `williammcada/mcada-project-handbook`  
**Handbook baseline:** `6557a45aaa6d29d7d1abde808e6d0ac248b08820 (AI-START-HERE.md); UNIVERSAL-RULES.md @ aed6fe311aa2e88983f862a30a2d8f05d2ffc04d`  
**Repository:** `williammcada/Dynamic-Calendar`  
**Canonical source status:** Known migration candidate: standalone `Dynamic_Lesson_Calendar_v1.html`; verify the exact latest local file before committing it as canonical.  
**Current project state:** v1 standalone/offline HTML application with local scheduling, editing, backup/export, and print/PDF capabilities.

## 1. Purpose and audience

Dynamic Calendar is an offline, standalone HTML replacement for a fragile Excel lesson schedule, designed to generate and maintain a dynamic teaching calendar while preserving local control of the schedule.

**Primary audience / operator:** Teacher/educator maintaining a lesson sequence and calendar.

## 2. Standards selection

**Universal baseline:** U-01 through U-08 where applicable.

**Conditional modules:** S-04 Distribution/Deployment

Apply only the selected modules and project-local requirements. Do not import restrictions from unrelated projects.

## 3. Project-specific requirements

- Run as a standalone offline HTML application.
- Keep HOLIDAYS and NO-LESSON DAYS as distinct concepts.
- Built-in 2026–27 dates may remain as Holidays.
- Both Holidays and No-Lesson Days need bulk import and Remove all controls.
- Support editable lesson sequence, dates, and events.
- Use local autosave; do not require a cloud account.
- Support JSON backup/restore, CSV export, and print/PDF.
- Skipped days should look normal rather than visually broken.

## 4. Preserve from the current accepted project

- JavaScript lesson scheduling behavior.
- Editable sequence/dates/events.
- Local autosave.
- JSON backup/restore.
- CSV export.
- Print/PDF output.
- Distinct Holidays and No-Lesson Days handling.

## 5. Relationship to other projects

- Standalone teacher utility; not an assessment engine or student game.
- Do not import classroom-game or AAC restrictions into this project.

A conceptual relationship is not proof of an implemented integration. Do not invent a shared API, data schema, identity layer, or deployment dependency without an explicit integration task.

## 6. Source and version discipline

The exact current source artifact or repository commit must be identified before a substantive build. If the field above says the source is not yet established, first locate the latest known-good local file/ZIP or existing repository state and record its exact identity here.

For substantial revisions use:

**DESIGN → CHANGE SPEC → IMPLEMENT → CHECKPOINT → VERIFY → VERIFIED CHECKPOINT → RELEASE → DEPLOY (when applicable)**

A packaging/export/deployment failure must not force reconstruction of an already verified build.

## 7. Definition of done

| # | Requirement / check | Result | Evidence / limitation |
| ---: | --- | --- | --- |
| 1 | Calendar generation produces the expected lesson/date sequence. | Not run | |
| 2 | Holiday and No-Lesson Day logic remain distinct. | Not run | |
| 3 | Bulk import and Remove all work for both date categories. | Not run | |
| 4 | Local autosave and JSON restore reproduce the schedule. | Not run | |
| 5 | CSV and print/PDF outputs match the current calendar. | Not run | |
| 6 | Offline operation works without required network calls. | Not run | |

Allowed results: **Passed / Failed / Not run / Not applicable**. A "Passed" result requires an actual check against the identified candidate.

## 8. Known issues and migration notes

Because this is a local standalone tool, do not accidentally add hosting or account dependencies during migration.

## 9. Handoff files

A substantive AI implementation task should retrieve or receive:

1. `AI-START-HERE.md`;
2. `UNIVERSAL-RULES.md`;
3. the relevant sections of `CONDITIONAL-STANDARDS.md`;
4. this project brief;
5. the exact current source artifact/commit;
6. the approved version-specific change specification;
7. applicable assets and deployment configuration.

Do not reconstruct the current implementation from a historical chat summary when the actual source should be available.

## 10. Ownership

**William McAda**  
**A WILLIAM MCADA PRODUCT**

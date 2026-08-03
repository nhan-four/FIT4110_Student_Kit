# FIT4110 Student Kit — review report

## Scope and method

Audited the complete public file inventories of `FIT4110_setup`, `FIT4110_instructor_setup`, and Labs 02–05, including READMEs, docs, scripts, workflow references, templates, checklists, evidence structures, contracts, sample artefacts, and run guides. The kit is a curated navigation and workflow layer; source lab repositories remain unmodified.

## Documentation audit

- The course progression is technically coherent: setup evidence feeds boundary design; boundary feeds OpenAPI; OpenAPI feeds mock/testing; tests feed container verification; containers feed Compose integration.
- Valuable source materials were retained by direct links and reinforced by concise lab bridges rather than duplicated wholesale.
- Legacy GitHub Classroom language was isolated to the source setup README. This kit contains no Classroom workflow or submission instruction.
- Identified source inconsistencies: Lab 05’s `RUN_COMPOSE.md` refers to a stale clone directory; some source documents vary between “Buổi” and “Lab”; and source guides have duplicated setup/testing explanations. The kit normalizes terminology and points to the canonical lab per stage.

## Technical audit

- Commands provided here use standard Git, Docker, Docker Compose, Node, and curl patterns and avoid real credentials.
- Templates use OpenAPI 3.1 and Problem Details-compatible response media type, environment-driven Compose configuration, health checks, internal networks, and named volumes.
- Safety improvement: cleanup guidance limits removal to the lab stack; broad Docker pruning is not prescribed.
- Source Actions/CI remain useful optional verification, but no grading outcome depends on a platform workflow.

## Educational audit

- Every major stage starts with its purpose, especially for AI/data students moving from models and notebooks to operable services.
- Diagrams cover roadmap, submission flow, boundary, packaging, and Compose topology.
- Templates remove empty-page friction while retaining decisions students must make themselves.
- Assessment rewards reproducibility, evidence, and honest limitations—not only a live demo.

## Remaining improvements

- Before the semester, publish the actual course Google Sheet and due-date policy, then add its approved link.
- Confirm whether final repositories must be public for all cohorts; the current ZIP workflow assumes public access.
- When upstream lab repositories change, rerun this audit and update source links/compatibility notes.

## Readiness assessment

**Ready for immediate use.** The kit gives students one consistent starting point, preserves reusable upstream lab content, and supplies a complete non-Classroom submission path.

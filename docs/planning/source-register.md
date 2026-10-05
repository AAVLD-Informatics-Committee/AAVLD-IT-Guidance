# Source register - working inventory

| ID | Source | Repository path | Classification | Intended use | Notes |
| --- | --- | --- | --- | --- | --- |
| SRC-001 | AAVLD Requirements for an Accredited Veterinary Medical Diagnostic Laboratory, 1137 Version 1 | `references/aavld/AAVLD Requirements for an Accredited Veterinary Medical Diagnostic Laboratory-1137-1.pdf` | Authoritative AAVLD requirement | Primary clause-level traceability. | 37-page PDF; IT-relevant material includes 4.1.4.3, 4.3, 4.10, 5.4.2, 5.4.4, and 5.5. |
| SRC-002 | AAVLD Informatics Subcommittee Accreditation IT Guidance | `references/aavld/IT guidance_12-21-07.pdf` | Historical baseline | Preserve prior purpose, coverage, terminology, and questions for comparison. | October 2007; seven pages; organized as network security, data integrity, and disaster planning. |
| SRC-003 | AAVLD 2025 IT Committee notes | `meetings/AAVLD 2025/IT Guidance DocNotes from 2025 Meeting About.docx` | Committee direction | Record the committee's update decision, purpose clarification, and validation focus. | Notes motions to clarify minimum IT needs, define validation minimums, and prepare a 2026 working-session pre-draft. |
| SRC-004 | ISO/IEC Directives Part 2 | External reference | Development-process reference | Inform document drafting form only. | Do not use as a source of laboratory IT controls. |
| SRC-005 | RFC 8874 | External reference | Development-process reference | Inform GitHub issue/PR and repository practice only. | Adapt to AAVLD governance; do not imply IETF process adoption. |
| SRC-006 | OASIS lifecycle guidance | External reference | Development-process reference | Inform stable working/review/approved artifact stages only. | Use AAVLD stage names. |
| SRC-007 | ISO/IEC 17025 | External reference | Related reference - provisional | Potential contextual alignment. | Classification requires committee confirmation. |
| SRC-008 | NIST CSF / GAMP materials | External reference | Informative technical reference - provisional | Potential non-vendor-specific implementation patterns. | Not a compliance baseline unless AAVLD explicitly adopts a portion. |

## Provenance rule

Do not modify files under `references/` or `meetings/`. Derived notes, matrices, and draft text belong under `docs/` or `guidance/` and must point back to this register.

# AAVLD Guidance for Laboratory Information Technology and Digital Systems

**Working Draft 0.3 - 2026-10-02**

> This is a committee working draft. It has not been approved and does not create
> new AAVLD accreditation requirements or obligations. Its purpose is to help
> laboratories understand and implement existing AAVLD requirements.

## How to read this draft

This draft uses three statement types:

- **AAVLD requirement** identifies a topic addressed by the current authoritative
  AAVLD Requirements. The cited source, rather than this document, controls.
- **Guidance recommendation** is proposed committee advice for implementation. It
  is not an additional accreditation obligation.
- **Example** is an optional pattern, question, or record format. Examples are not
  mandatory and do not endorse a product or vendor.

Examples, illustrations, and screenshots are illustrative only. They are not
click-by-click instructions for a particular product and may not match the
screens or steps of any specific system. They are intended to be general enough
to apply to any technology a laboratory uses. Product logos, vendor names, and
other identifying details are removed or obscured, and some examples may be
generic, artificially generated scenarios rather than records from a real
laboratory.

## 1. Purpose, scope, audience, and use

This guidance is written primarily for laboratories applying existing
accreditation requirements to laboratory information technology and digital
systems that affect diagnostic activities, records, and results. Its core focus
is the minimum IT needs that support AAVLD accreditation, without creating new
accreditation obligations. Assessors and other AAVLD stakeholders may use it as a
shared reference, not as a separate assessor checklist.

It is intended to be vendor-neutral and risk-based. It does not prescribe a
single technical architecture, product, control implementation, or documentary
form. Laboratories should select controls and evidence that are appropriate to
their systems, services, diagnostic activities, and risks.

The guidance is not limited to LIMS. It is intended to address the information
technology issues a laboratory may encounter while gaining or maintaining
accreditation, across any system or service that meets the inclusion test in
Section 3. Each laboratory determines which of its systems the guidance
appropriately applies to.

This guidance does not replace the current AAVLD Requirements, laboratory
policies, contractual obligations, or applicable law. Where an AAVLD requirement
is cited, the current AAVLD Requirements remain authoritative.

## 2. Relationship to AAVLD accreditation requirements

The current AAVLD Requirements address, among other subjects, confidential
electronic information, document and records control, computer-collected data,
laboratory information management systems (LIMS), software, data security,
retrievability, and equipment software. This guidance organizes implementation
considerations around those subjects.

| AAVLD topic | Principal clause(s) | Guidance focus |
| --- | --- | --- |
| Confidential electronic information | 4.1.4.3 | Protection of information in storage and transmission. |
| Documents and records | 4.3; 4.10 | Control, retention, retrieval, security, and change history. |
| Data control and LIMS | 5.4.4 | Intended use, validation, interfaces, security, and continuity. |
| Equipment software | 5.5 | Specifications and safeguards for software affecting diagnostic activities. |

The working requirements-to-guidance matrix in
[`docs/planning/requirements-traceability.md`](../docs/planning/requirements-traceability.md)
records the more detailed clause-level mapping. It will be completed as committee
decisions are made.

**Guidance recommendation.** Laboratories may find it useful to review their IT
practices against ISO/IEC 17025 as a cross-check, so that nothing vital to that
standard is missed. This guidance references ISO/IEC 17025 for that purpose
only. It does not restate the standard or make it an AAVLD accreditation
requirement; the current AAVLD Requirements remain authoritative. See #18.

## 3. System inventory, roles, and risk-based prioritization

**Guidance recommendation.** Maintain an inventory of systems and services that
create, receive, process, store, transmit, report, or support diagnostic and
quality data. The inventory can include LIMS, instrument-connected computers,
interfaces, reporting systems, user-developed tools, spreadsheets, infrastructure,
and externally provided services when they affect relevant data or activities.

**Guidance recommendation.** The laboratory determines which of its systems and
services the guidance applies to. A system or service is in scope when it can
affect one or more of the following:

- diagnostic activities or reported results;
- technical, quality, test, validation, or other retained laboratory records;
- the confidentiality, integrity, availability, security, or retrievability of
  those data and records; or
- the laboratory's ability to meet an existing AAVLD requirement.

**Guidance recommendation.** At a minimum, consider any system whose failure or
error could affect patient diagnosis or treatment. Commonly in-scope items
include:

- LIMS;
- quality-management system;
- analyzer and instrument firmware;
- research tools used in diagnostic or validation work; and
- inventory tools that track reagent lot numbers and chemical expiration dates.

**Example.** Laboratories sometimes overlook items that are not usually thought
of as "IT systems," such as analyzer firmware, instrument control software, or a
spreadsheet used to track reagent lots. These can affect results in the same way
as a LIMS and are worth including in the inventory.

> **Committee review pending:** The candidate category table in
> [`docs/planning/potential-coverage.md`](../docs/planning/potential-coverage.md)
> (Core, Conditional, or Out of scope) will be reviewed at a follow-up
> subcommittee meeting. See #16.

For each in-scope item, identify its intended use, owner, important interfaces,
data handled, supplier or service relationship, and relative impact on diagnostic
activities and records. Use this information to prioritize validation, change
control, access control, backup, recovery, and review effort.

**Example.** A system inventory can record the system name, owner, purpose,
connected systems, data types, criticality, validation/verification evidence,
backup coverage, and last access review.

## 4. Data lifecycle

**AAVLD requirement.** The current AAVLD Requirements address secure and
retrievable test and validation data, protection of technical records and
computer-collected data from unauthorized change, and the ability to retrieve
records during the required retention period. See 4.10 and 5.4.4.

**Guidance recommendation.** Consider the complete lifecycle of relevant data:
creation or receipt, processing, review and approval, reporting or transmission,
storage, retention, retrieval, correction, and disposition. For each material
step, identify the expected data state, responsible role, authorization, retained
evidence, and control against unintended loss or alteration.

**Guidance recommendation.** Establish a documented method for correcting data or
records that preserves the original information when appropriate, identifies who
made the change and when, and allows the reason for the change to be understood.

## 5. Access, security, auditability, and operating environment

**AAVLD requirement.** The current AAVLD Requirements address confidentiality,
security, integrity, retrievability, protection against unauthorized access or
amendment, and the operating environment needed to protect LIMS data. See
4.1.4.3, 4.10, and 5.4.4.

**Guidance recommendation.** Define access roles according to job responsibility
and the system's effect on diagnostic activities and records. Provide, modify,
and remove access through an authorized process. Give special consideration to
privileged access, shared accounts, remote access, and accounts for external
support personnel.

**Guidance recommendation.** Use controls appropriate to the risk to protect data
and systems against unauthorized access, loss, alteration, and unavailability.
Review whether security events, relevant system activity, and data changes can be
investigated when necessary.

**Example.** An access review may identify each active account, assigned role,
approval, last review date, and required follow-up for inactive or excessive
access.

## 6. Software, LIMS, interfaces, and external providers

**AAVLD requirement.** The current AAVLD Requirements address documentation and
validation of user-modified or user-developed software, validation of LIMS
functionality and interfaces before introduction, authorized and documented LIMS
changes, and external-provider accountability. See 5.4.4.3 through 5.4.4.6.

**Guidance recommendation.** Describe the intended use and relevant boundaries of
each LIMS, interface, user-developed tool, and other software that affects
diagnostic activities or records. Identify which organization or role is
responsible for configuration, support, data protection, recovery, change approval,
and evidence retention.

**Guidance recommendation.** When an external provider supports an in-scope
system or data service, document the laboratory's understanding of responsibilities
that affect applicable AAVLD requirements. This may include service scope, access,
data handling, incident communication, backup/recovery responsibilities, change
notification, and available evidence.

**Guidance recommendation.** For interoperability, consider applicable reporting
and data-exchange standards, including federal reporting standards, when
selecting, configuring, or changing reporting systems and interfaces. Using these
standards can make electronic result exchange easier even where they are not
required for AAVLD accreditation. Referencing a standard in this guidance does
not make it an accreditation requirement.

> **Committee review pending:** The specific reporting standards to reference
> have not yet been identified. See #17.

## 7. Validation, verification, and change control

**AAVLD requirement.** The current AAVLD Requirements call for applicable
software and LIMS functionality and interfaces to be validated before use or
implementation, for changes to be authorized and documented, and for relevant
data to remain protected and retrievable. See 5.4.2.2 and 5.4.4.

**Guidance recommendation.** Before introducing a new in-scope system or a change
that may affect diagnostic activities, data, records, or reporting, define the
intended use, relevant risks, acceptance criteria, responsible reviewers, and
evidence needed to show the system or change is fit for that intended use.

**Guidance recommendation.** Retain evidence appropriate to the change. This can
include the change request, impact assessment, test or verification results,
deviations, approvals, implementation record, and any follow-up review. The
amount of evidence should be proportionate to the potential impact on diagnostic
activities and data integrity.

**Guidance recommendation.** Use a risk-based, intended-use approach to decide
how much validation or verification a new system or change needs. For each
change, consider:

- whether the change could affect animal health and, if so, how; and
- how likely the change is to produce an incorrect result if something goes
  wrong, and whether that result would affect the patient.

**Guidance recommendation.** A simple risk matrix that combines the severity of
a potential incorrect result with its likelihood can help a laboratory rank
changes consistently and set the evidence needed for each level.

**Example.** A risk matrix might rate severity from low (cosmetic, with no effect
on results) to high (could change a reported result or a treatment decision),
and likelihood from unlikely to likely. Two changes illustrate the range:

| Change | Severity if wrong | Likelihood | Suggested evidence |
| --- | --- | --- | --- |
| Change the font of a report heading | Low: no effect on the result or interpretation | Unlikely | Focused documented check of the report output. |
| Change the calculation of a sodium:potassium ratio | High: an incorrect ratio could change diagnosis and treatment | Possible | Documented testing against known values, review and approval, and follow-up monitoring. |

A new interface that transfers diagnostic results would similarly warrant
documented end-to-end testing, approval, and follow-up monitoring.

> **Committee review pending:** The subcommittee agrees with this risk-based
> baseline and confirmed that validation, verification, and change-control
> guidance belongs in this document. It will review the minimum evidence,
> definition of a material change, and terminology in depth at a further
> meeting. Where detailed criteria are not agreed, the guidance will at least
> provide a set of references. See #15.

## 8. Backup, recovery, continuity, and nonconforming work

**AAVLD requirement.** The current AAVLD Requirements address accessible, secure
records; protection from loss; LIMS failures; and processes for nonconforming work.
See 4.10 and 5.4.4.4 through 5.4.4.5.

**Guidance recommendation.** Identify the systems and data that need backup,
recovery, continuity, or contingency arrangements. Define responsibilities,
recovery priorities, communication paths, and the evidence retained for recovery
testing or actual recovery events.

**Guidance recommendation.** When a system failure or data concern may affect
diagnostic activities or reported results, use the laboratory's applicable
nonconforming-work process and retain evidence of assessment, action, and
resolution.

**Example.** A recovery test record can identify the system/data scope, backup
source, restoration result, integrity checks, time required, identified gaps, and
corrective action.

## 9. Informative implementation examples

Where practical, the committee may publish optional templates or examples after
agreeing their purpose and boundaries. Candidate aids include a system inventory,
intended-use and risk assessment, validation/verification record, change-control
record, access-review record, backup/recovery test record, and external-provider
review prompts. See [`docs/planning/template-catalog.md`](../docs/planning/template-catalog.md).

Examples should show, without promoting any product, which changes to systems
may need revalidation and which systems fall within this guidance. Examples may
use generic, artificially generated scenarios, including AI-generated content.
Any screenshot has logos, product names, and other identifying details removed
or obscured. See "How to read this draft" for how examples should be
interpreted.

> **Committee review pending:** The committee will decide, once the draft is
> complete, whether separate examples and templates are still needed and which
> to publish. See #9 and #21.

## 10. Traceability and references

### Authoritative source

- AAVLD Requirements for an Accredited Veterinary Medical Diagnostic Laboratory,
  Version 1 (SRC-001 in the source register).

### Supporting project records

- Source register: [`docs/planning/source-register.md`](../docs/planning/source-register.md)
- Requirements traceability: [`docs/planning/requirements-traceability.md`](../docs/planning/requirements-traceability.md)
- Gap analysis: [`docs/planning/gap-analysis.md`](../docs/planning/gap-analysis.md)

### Related and informative sources

Related and informative sources may be added only after committee classification
and approval. Their citation does not make them an accreditation requirement.

- ISO/IEC 17025, General requirements for the competence of testing and
  calibration laboratories (informative cross-check; see Section 2 and #18).
- Applicable reporting and data-exchange standards, including federal reporting
  standards (informative, for interoperability; see Section 6 and #17). Specific
  standards to be identified.

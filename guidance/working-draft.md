# AAVLD Guidance for Laboratory Information Technology and Digital Systems

**Working Draft 0.2 - 2026-08-19**

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

## 3. System inventory, roles, and risk-based prioritization

**Guidance recommendation.** Maintain an inventory of systems and services that
create, receive, process, store, transmit, report, or support diagnostic and
quality data. The inventory can include LIMS, instrument-connected computers,
interfaces, reporting systems, user-developed tools, spreadsheets, infrastructure,
and externally provided services when they affect relevant data or activities.

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

**Example.** A small report-format change may need a focused documented check;
a new interface that transfers diagnostic results may need documented end-to-end
testing, approval, and follow-up monitoring.

> **Committee decision pending:** The committee will define the minimum evidence
> expected for validation, verification, and change control, including the terms
> used for distinct types of systems and changes.

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

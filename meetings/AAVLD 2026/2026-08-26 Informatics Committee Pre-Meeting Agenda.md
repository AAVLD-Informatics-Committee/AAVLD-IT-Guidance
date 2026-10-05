# AAVLD Informatics Committee Pre-Meeting

**Date/time:** Wednesday, August 26, 2026, 1:30-2:30 PM Eastern

**Meeting access:** Use the Microsoft Teams information in the calendar invitation.

**Purpose:** Finalize the proposed Informatics Committee and interoperability
symposium agendas, prepare decision-ready recommendations, and assign owners for
the work needed before the October 15 symposium.

This pre-meeting may develop tentative recommendations and record working
decisions within the participants' delegated authority. Formal committee or AAVLD
approval must be recorded separately when required. Repository merge approval,
committee disposition, and formal AAVLD publication approval are distinct actions.

## Preparation

- Review the proposed symposium flow and identify missing veterinary diagnostic
  laboratory perspectives.
- Bring candidate speakers or facilitators for catalog, ordering/accession,
  results, FHIR alignment, terminology, governance, and adoption topics.
- Review the open [AAVLD IT Guidance issues](https://github.com/AAVLD-Informatics-Committee/AAVLD-IT-Guidance/issues)
  and the [modernization project](https://github.com/orgs/AAVLD-Informatics-Committee/projects/2).
- Be prepared to volunteer or identify owners for pre-symposium work.

## Agenda

1. **0:00-0:05 - Opening, authority, and expected outputs**
   - Confirm facilitator, recorder, and timekeeper.
   - Confirm which outcomes may be recorded as tentative working decisions,
     recommendations for committee ratification, or open questions.
   - Confirm the expected outputs listed below.

2. **0:05-0:20 - Finalize the October 15 symposium agenda**
   - **Welcome: Why Veterinary Laboratories Need an Interoperability Framework**
   - **Defining Veterinary Diagnostic Laboratory Interoperability**
   - **Framework Component 1: Publishing Laboratory Tests and Services**
   - **Framework Component 2: From Test Request to Laboratory Accession**
   - **Framework Component 3: Returning Results, Corrections, and Status**
   - **Making the Framework Sustainable: Mapping, Governance, Adoption, and Change**
   - **From Symposium to Framework: Consensus and Next Steps**
   - Confirm the working format, intended deliverables, and time allocation for
     each topic.
   - Identify proposed guest speakers, facilitators, recorders, and participating
     laboratory or vendor reviewers.

3. **0:20-0:35 - Interoperability Framework repository and pre-symposium decisions**
   - Review the lean repository setup plan and the catalog-to-amended-result
     vertical slice as the primary pre-symposium technical deliverable.
   - Consider the tentative decisions and proposed resolutions in the decision
     lineup below.
   - Identify two laboratories with different LIMS environments, an interface or
     vendor specialist, and a quality/accreditation reviewer for the initial use
     cases and synthetic examples.

4. **0:35-0:52 - Open IT Guidance decisions**
   - **Decision 7:** Is a GitHub repository acceptable to the committee as the
     controlled drafting and review tool?
   - **Decision 9:** How should the guidance provide non-vendor-specific examples
     of candidate aids such as backup/recovery, validation, and change control?
   - **Decision 13:** Is stakeholder or public review required before committee
     approval of the updated IT Guidance?
   - **Decision 15:** What minimum baseline should the IT Guidance cover, and how
     should subjective or risk-based elements be bounded?
   - **Decision 16:** What is the scope of the IT Guidance? Confirm whether it
     should remain non-LIMS-specific while addressing accreditation-related
     problems laboratories encounter.
   - Record the disposition, rationale, decision authority, affected artifacts,
     owner, and any required follow-up for each resolved item.

5. **0:52-0:57 - Committee coordination**
   - Determine a social outing approach for the committee.
   - Discuss updates needed for the committee website.

6. **0:57-1:00 - Closeout**
   - Confirm decisions, unresolved questions, owners, and dates.
   - Confirm which items advance to the Informatics Committee for ratification or
     approval.
   - Confirm the next symposium-planning checkpoint.

## Interoperability Framework decision lineup

### IF-01 - Repository license approach

**Tentative proposed resolution:** Apply the Apache License, Version 2.0 to the
repository's original framework text, schemas, examples, and code, subject to
confirmation that AAVLD has authority to license the material and acceptance of
the approach by the appropriate committee or AAVLD authority.

**Boundary:** Externally sourced material retains its original license,
attribution, copyright, and trademark requirements. Do not copy external
standards or terminology content unless redistribution is permitted. References
to HL7 FHIR must respect HL7 licensing and trademark conditions and must not imply
HL7 endorsement.

### IF-02 - Repository visibility and contributions

**Proposed resolution:** The repository will be public. External contributions
will not be accepted or merged until licensing, contribution terms, maintainers,
and decision authority are recorded.

### IF-03 - Decision and approval authority

**Proposed resolution:** Define and keep separate the repository maintainer who
may merge, the committee authority that may resolve substantive framework
questions, and the AAVLD authority that may approve an official publication.

### IF-04 - Role of FHIR

**Proposed resolution:** The framework defines shared veterinary semantics and
exchange behavior. HL7 FHIR is the first implementation-profile path to be mapped
and tested. FHIR is not a mandatory implementation technology unless AAVLD later
approves a specific conformance requirement or implementation profile.

### IF-05 - Pre-symposium scope

**Proposed resolution:** Prioritize three representative use cases and one
synthetic, machine-validatable vertical slice covering catalog, order,
acknowledgement, validation or rejection, accession, specimen linkage, interim
and final results, and correction or amendment. Include negative cases for an
unknown offering, unacceptable or incomplete specimen information, duplicate
submission, and rejection or cancellation.

Defer production transport, authentication architecture, billing, complete
practice-management workflows, formal FHIR Implementation Guide publication, and
full production deployment requirements unless the committee explicitly brings
them into the pre-symposium scope.

### IF-06 - Terminology alignment

**Proposed resolution:** Treat terminology as a required part of semantic
interoperability. The initial work will evaluate test/service identifiers,
specimen and matrix terms, species and population concepts, methods, analytes,
units, result interpretations, and local-to-shared mappings, including relevant
FHIR, LOINC, SNOMED CT, UCUM, NAHLN, and veterinary sources subject to licensing
and applicability.

### IF-07 - Working-draft status and versioning

**Proposed resolution:** Use dated status labels for pre-symposium material. The
symposium output will not automatically become an approved `v0.1` release. After
outcomes are reconciled and the required authority acts, publish it as **Working
Draft 0.1** or retain it as a dated symposium working package.

### IF-08 - Repository and project sources of truth

**Proposed resolution:** Issues, the accepted decision log, merged repository
content, and tagged release artifacts are authoritative project records. The
GitHub Project is an operational dashboard and does not override recorded issue
or decision dispositions.

## Expected outputs

- Final proposed symposium agenda and list of candidate speakers/facilitators.
- Recorded tentative disposition for IF-01 and as many additional framework
  decisions as the group can responsibly resolve.
- Decision-ready recommendations for IT Guidance Decisions 7, 9, 13, 15, and 16.
- Named owners and target dates for the vertical slice, FHIR/terminology mapping,
  participant recruitment, meeting materials, and website updates.
- A list of unresolved questions to place in GitHub Issues and track in the
  appropriate GitHub Project.

## Recording and privacy rules

- Do not include Microsoft Teams join links, passcodes, attendee email addresses,
  or private contact information in this public repository.
- Do not upload real client, owner, animal, herd, accession, submitter, or
  production-system data. Repository examples must be synthetic.
- Record whether an outcome is a tentative working decision, a recommendation,
  a committee decision, or formal AAVLD approval.
- For each resolved decision, record the authority, date, rationale, source issue,
  affected artifacts, and any superseded decision.

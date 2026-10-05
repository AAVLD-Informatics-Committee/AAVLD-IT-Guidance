# Potential coverage inventory - committee decision aid

## Purpose

This is a comprehensive candidate list for the updated guidance. It is not a
statement of required coverage and does not create new accreditation obligations.
For each entry, the committee should select one of three dispositions:

- **Core:** address in the main guidance.
- **Conditional:** address only when it affects diagnostic activities, data, or
  records within the guidance's scope.
- **Out of scope:** do not address in this version; record the reason or a
  possible future release.

## Inclusion test

An item is a candidate when it can affect one or more of the following:

- diagnostic activities or reported results;
- technical, quality, test, validation, or other retained laboratory records;
- confidentiality, integrity, availability, security, or retrievability of those
  data and records; or
- the laboratory's ability to meet an existing AAVLD requirement.

The current AAVLD Requirements remain the authoritative source for obligations.
The final guidance must distinguish AAVLD-derived material from recommendations
and examples.

## Candidate system and service categories

| Candidate | Initial disposition | Notes for committee |
| --- | --- | --- |
| LIMS/LIS and configured modules | Core candidate | Includes result entry, workflow, reporting, and administration. |
| Instrument-connected computers and instrument software | Core candidate | When they acquire, process, store, or report diagnostic data. |
| Interfaces, middleware, APIs, and data transfers | Core candidate | Includes transfers among instruments, LIMS, reporting, and external systems. |
| Reporting systems, portals, and electronic result delivery | Core candidate | When used to generate, approve, or transmit reports. |
| User-developed tools | Core candidate | Spreadsheets, macros, scripts, local databases, and similar tools used for in-scope activities. |
| Configured commercial software | Conditional candidate | When configuration or extension affects in-scope activities or records. |
| Databases, file stores, archives, and document/record systems | Conditional candidate | When they hold or manage in-scope data or records. |
| Data warehouses, analytics, dashboards, and business intelligence | Conditional candidate | When their output is used for diagnostic or quality decisions. |
| Identity, access, and privileged-access services | Conditional candidate | When they control access to in-scope systems or data. |
| Servers, virtual platforms, operating systems, storage, and networks | Conditional candidate | When their operation materially affects in-scope systems or data. |
| Backup, replication, archival, and recovery services | Core candidate | When they protect in-scope data or support recovery. |
| Cloud, SaaS, hosted, managed, and other external services | Core candidate | When they provide or support in-scope systems or data. |
| Remote support, remote administration, and remote access | Conditional candidate | When access can affect in-scope systems or data. |
| Data-exchange channels and removable media | Conditional candidate | Includes secure transfer services, email, shared storage, and media when used for in-scope data. |
| Mobile devices and mobile applications | Conditional candidate | When used to access, collect, review, approve, or transmit in-scope data. |
| Electronic quality-management, document-control, and training systems | Conditional candidate | When they manage documents, records, competency, or approvals relevant to AAVLD requirements. |
| Electronic signatures and approval workflows | Conditional candidate | When used to authorize in-scope data, records, or changes. |
| Automation, sensors, and environmental-monitoring systems | Conditional candidate | When their data support diagnostic activities, equipment conditions, or retained records. |
| AI/ML and automated decision-support tools | Conditional candidate | When outputs influence diagnostic, quality, reporting, or data-handling decisions. |
| Collaboration and general productivity tools | Conditional candidate | Only when used to create, maintain, transmit, or retain in-scope records or data. |

## Candidate lifecycle and control topics

| Candidate | Initial disposition | Notes for committee |
| --- | --- | --- |
| System inventory, intended use, ownership, and boundaries | Core candidate | Identifies what is in scope and who is accountable. |
| Risk and criticality assessment | Core candidate | Supports proportionate controls and evidence. |
| Supplier/provider selection and accountability | Core candidate | Focus on laboratory responsibilities, not prescribed contract terms. |
| Requirements, specifications, configuration, and documentation | Conditional candidate | Depth should be proportionate to system risk and change. |
| Validation, verification, qualification, and testing | Core candidate | Detailed minimum evidence is a separate committee decision (#15). |
| Change control, release, and configuration management | Core candidate | Includes authorization, impact assessment, testing, and retained evidence. |
| Data integrity, auditability, corrections, and audit trails | Core candidate | Applies where system/data functions support it. |
| Access control, account lifecycle, and privileged access | Core candidate | Outcome-based; avoid dated product-specific controls. |
| Security monitoring, logging, and incident handling | Conditional candidate | Proportionate to risk and ability to investigate relevant events. |
| Backup, restoration, and recovery testing | Core candidate | Includes evidence of restoration and integrity checks. |
| Continuity, contingency operation, and disaster recovery | Core candidate | Include systems and data required for diagnostic operations. |
| System failures, data incidents, and nonconforming work | Core candidate | Link to the laboratory's applicable nonconforming-work process. |
| Record retention, retrieval, archiving, migration, and disposal | Core candidate | Address record availability and preservation during system changes. |
| Training, roles, responsibilities, and segregation of duties | Conditional candidate | Address where needed to operate and control in-scope systems. |
| Periodic review, maintenance, monitoring, and obsolescence | Conditional candidate | Consider recurring review of continuing fitness for intended use. |
| Decommissioning, replacement, and data migration | Conditional candidate | Protect records, traceability, and continuity when systems retire or change. |

## Questions for committee resolution

1. Which candidate system/service categories are Core, Conditional, or Out of
   scope?
2. Which lifecycle/control topics belong in the main guidance versus optional
   examples or templates?
3. Is the inclusion test above clear enough to keep the scope practical and
   vendor-neutral?
4. Are there veterinary diagnostic workflows, systems, or interfaces missing from
   the list?

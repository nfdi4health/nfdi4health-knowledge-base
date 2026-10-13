---
title: Collecting
page_id: collect
description: Collect and acquire clinical, epidemiological and public health research data with consistent documentation, quality controls and participant safeguards, supported by NFDI4Health resources and services.
contributors: [Atinkut A. Zeleke]
related_pages:
  Your_tasks: [data_organisation, data_quality, existing_data, identifiers, metadata, sensitive, storage, data_provenance, ethics, gdpr_compliance, data_security]
---

Good biomedical data collection turns the decisions made during **planning** into consistent, documented practice. Every observation should retain enough context to explain **what was measured, how, when and from which source**, while protecting the people whose data are being used.

For clinical, epidemiological and public health research, collection includes generating new observations and acquiring authorised extracts from existing sources. NFDI4Health supports this work through metadata standards, study discovery, terminology, documentation and quality resources. The research team and data-holding institutions remain responsible for the collection systems, permissions and secure handling of participant-level data.

**Start here:** [Review your planning decisions]({{ '/planning' | relative_url }}) · [Explore NFDI4Health services]({{ '/services' | relative_url }}) · [Return to the research data life cycle]({{ '/data_life_cycle' | relative_url }})

## Learning objectives

After using this guidance, you should be able to:

- distinguish new data collection from acquisition of existing biomedical data;
- translate the study protocol and DMP into a practical collection workflow;
- select suitable collection systems and document variables, instruments and provenance;
- apply quality checks and participant safeguards during collection; and
- identify NFDI4Health resources that support documentation, discovery and preparation for reuse.

## What is biomedical research data collection?

Data collection is the systematic generation or acquisition of information needed to answer a research question. In biomedical research, this may involve participant questionnaires, examinations, laboratory measurements, imaging, wearable devices, clinical records or registry extracts.

**Primary collection** produces new observations for the study. **Secondary acquisition** obtains data that were originally collected for another purpose, such as care, surveillance or an earlier research project. Both require clear definitions, documented provenance and an authorised workflow. Discovering a dataset does not itself give permission to access it.

Collection and documentation belong together. A blood glucose value without its unit, specimen context, measurement method or relevant timing may be difficult to interpret even if the number was entered correctly. Preserve the original observation and its context before creating cleaned or derived versions during [Processing]({{ '/processing' | relative_url }}).

## Why collect and document consistently?

Consistent collection helps teams to:

- **Protect participants:** implement agreed permissions, purpose limits and access safeguards in day-to-day work.
- **Improve validity:** use appropriate instruments, defined procedures and agreed measurement conditions.
- **Reduce preventable errors:** detect missing information, incompatible units, duplicate records and transcription problems early.
- **Support multicentre research:** apply shared definitions while documenting meaningful differences between sites.
- **Keep evidence traceable:** connect observations to their source, instrument version and subsequent corrections.
- **Prepare for FAIR reuse:** capture metadata, variable definitions and provenance while the people who know the context are available.

An unexpected value is not automatically an error. Flag and investigate it rather than silently replacing or deleting it. In health research, unusual observations may be clinically meaningful.

## From the NFDI4Health DMP to a collection workflow

The [NFDI4Health DMP templates](https://www.nfdi4health.de/en/service/guidelines/researchdatamanagementplans.html) provide the agreed data strategy. At collection, convert that strategy into operational instructions, configured systems and assigned responsibilities.

| Planning commitment | What to implement during collection |
| --- | --- |
| **Defined data sources and variables** | A collection specification describing each source, required variable, unit, format, timing and responsible site. |
| **Agreed documentation and standards** | A versioned data dictionary, questionnaire or case report form, collection SOPs and study metadata record. |
| **Data protection and access arrangements** | Approved access roles, participant-ID procedures, secure handling of identity information and documented permissions. |
| **Quality assurance** | Entry checks, pilot testing, instrument checks, site training and a process for investigating discrepancies. |
| **Storage and backups** | Approved collection storage, protected raw exports, backup schedules and tested recovery procedures. |
| **Discovery and reuse** | A maintained description of the study, instruments, access pathway and documentation suitable for later publication. |

### How to prepare and run collection

1. **Confirm readiness.** Check that the relevant approvals, permissions, agreements, collection specification and DMP are in place before recruitment, extraction or transfer begins.
2. **Define and configure instruments.** Translate the protocol into questionnaires, case report forms, device settings or extraction rules. Record versions, skip logic, required fields, codes and permitted values.
3. **Pilot the complete workflow.** Test entry, export, identifiers, missing-value handling, transfers and documentation with approved test or synthetic records. Check that exported values retain their meaning.
4. **Train the team.** Assign responsibilities for collection, discrepancy resolution, metadata maintenance and incident escalation. Record which procedure versions were used in training.
5. **Collect and document together.** Follow the agreed procedures and capture provenance, instrument versions, relevant timing and deviations as observations are generated or received.
6. **Monitor and resolve issues.** Review completeness and consistency; issue queries to the responsible source and record the reason, author and date of each correction.
7. **Prepare a controlled handover.** Deliver a protected raw snapshot, current dictionary, provenance and unresolved-issue log to the processing team. Update the DMP when actual practice changes.

**Expected outputs:** a documented source dataset or extract, collection specification, data dictionary, provenance record, quality/query log and a clear account of access restrictions. These outputs support subsequent processing without losing the original context.

## What should be considered for biomedical collection?

### Data sources and acquisition methods

Your training materials distinguish clinical trial, cohort, public health and registry data. These categories may overlap: a cohort may obtain information from questionnaires, laboratory systems and a disease registry.

| Source or study context | Typical collection or acquisition | Documentation to capture |
| --- | --- | --- |
| **Clinical study** | Visits, electronic case report forms, laboratory results and patient-reported outcomes | Protocol and form versions, visit definitions, source locations and relevant deviations. |
| **Epidemiological cohort** | Repeated questionnaires, examinations, biomarkers and linked records | Recruitment and follow-up periods, instrument versions, measurement conditions and linkage provenance. |
| **Public health research** | Surveys, surveillance, administrative or environmental sources | Sampling frame, reporting coverage, geographic and temporal definitions, aggregation and source revisions. |
| **Registry-based research** | Authorised registry exports or ongoing registry entry | Eligibility definitions, coverage, coding systems, extraction date and changes in registry definitions. |
| **Clinical records and devices** | Approved electronic health record extracts, imaging or wearable outputs | Source-system and device versions, extraction rules, units, time references and known capture limitations. |

For existing data, keep a record of the provider, source version, extraction criteria, acquisition date, permitted uses and known limitations. A clinical record reflects care processes and may not measure a research variable in the same way as a dedicated study instrument.

### Choosing collection systems

Select a system that fits the data, study requirements and institutional safeguards. Examples include **Electronic Data Capture (EDC)** systems for structured study entry, **Laboratory Information Management Systems (LIMS)** for samples and laboratory workflows, and **Electronic Laboratory Notebooks (ELNs)** for experimental records.

Assess access control, traceable corrections, validation rules, exports, interoperability, backup and support. Test whether the exported data preserve labels, missing-value codes, units and repeated observations. Spreadsheet entry requires explicit controls for validation, versions, access and change tracking; a shared spreadsheet alone does not provide a complete controlled collection workflow.

The Health Study Hub supports discovery of study information and resources. It should not be treated as the system for entering participant-level observations. Likewise, an institutional Local Data Hub can organise project resources and access permissions, but its suitability for a particular sensitive-data workflow must be established locally.

### Variables, identifiers and documentation

Use consistent study and participant identifiers. Keep identity or linkage information separately with appropriate access restrictions. Internal participant codes support record management; they are distinct from public study or resource identifiers.

A **data dictionary** describes variables and their interpretation. Study-level metadata describe the resource as a whole. The NFDI4Health Metadata Schema supports structured description of health research resources; it does not replace a variable dictionary or define every clinical measurement.

| Dictionary element | Illustrative example |
| --- | --- |
| **Variable name and label** | `glucose_fasting`: fasting blood glucose concentration. |
| **Type and unit** | Numeric; agreed unit documented explicitly. |
| **Collection context** | Specimen type, assay method and fasting-status definition. |
| **Permitted values or validation** | Study-approved checks; outlying results trigger review rather than automatic deletion. |
| **Missing-value meaning** | Not measured, participant declined and technical failure recorded separately. |
| **Source and version** | Laboratory export, measurement date and relevant method/specification version. |
| **Terminology mapping** | Appropriate standard concept or code, with coding-system version and mapping rationale. |

Avoid placing names or other unnecessary direct identifiers in filenames, dictionary examples, public metadata or query logs. Use controlled examples or synthetic records when demonstrating workflows.

## NFDI4Health services to consider during collection

Use NFDI4Health resources alongside institutional collection and security systems. Service selection depends on the study, available infrastructure and local responsibilities.

| NFDI4Health resource or service | How it supports the *collection* stage |
| --- | --- |
| **[DMP templates and guidelines](https://www.nfdi4health.de/en/service/guidelines/researchdatamanagementplans.html)** | Keep the collection arrangements aligned with the approved strategy; record changes to sources, instruments or responsibilities. |
| **[Health Study Hub]({{ '/services/health-study-hub' | relative_url }})** | Explore existing study descriptions and instruments; prepare non-sensitive descriptions of your study and collection resources for discovery. |
| **[Metadata Schema]({{ '/services/metadata-schema' | relative_url }})** | Capture standardised study and resource metadata alongside collection documentation. |
| **[Local Data Hub](https://www.nfdi4health.de/en/service/local-data-hub.html)** | Organise connected project resources and their permissions within an institutional deployment; prepare selected metadata for publication. |
| **[Terminology Service and Annotation Workbench](https://www.nfdi4health.de/en/service/our-services.html)** | Support standardised descriptions and annotation of health concepts; document mappings and terminology versions. |
| **[Data Quality Assessments]({{ '/services/data-quality' | relative_url }})** | Support repeatable assessment of collected datasets. Evaluate whether dataquieR fits the workflow; dataset assessment complements entry checks and source review. |
| **[Anonymisation resources](https://www.nfdi4health.de/en/service/our-services.html)** | Inform planning of disclosure controls for later outputs. Removing identifiers during collection does not by itself establish anonymity. |
| **[German Portal for Medical Research Data (FDPG)](https://www.nfdi4health.de/en/service/our-services.html)** | Support the application pathway for relevant existing data; acquisition follows the provider's approvals, conditions and agreements. |
| **[Helpdesk](https://www.nfdi4health.de/en/helpdesk.html)** | Obtain guidance on metadata, documentation resources and suitable service contacts. |

Study metadata and documents intended for publication need a separate disclosure review. Even a questionnaire or dictionary may contain confidential information, copyrighted material or accidental identifiers.

## Applying FAIR principles during collection

- **Findable:** maintain study and resource descriptions, consistent identifiers and links among protocols, instruments and dictionaries. Prepare appropriate metadata for the Health Study Hub.
- **Accessible:** document how authorised users obtain data and documentation, including contacts, conditions and institutional access decisions.
- **Interoperable:** use agreed formats, explicit units, standard terms where appropriate and consistent coding. Record mappings rather than assuming similarly named variables are equivalent.
- **Reusable:** preserve collection context, source provenance, instrument versions, quality findings and permitted uses. Document instrument licences and restrictions.

FAIR does not require open access to participant-level health data. Public descriptions can support discovery while the underlying data remain controlled by the responsible institution.

## Collecting sensitive health data responsibly

Implement the safeguards agreed during planning with the responsible institutional experts:

1. **Verify authorised use.** Ensure collection or extraction fits the applicable permissions, lawful basis, relevant condition for processing health data and institutional approvals. Research participation consent and data-processing authorisation are not automatically interchangeable.
2. **Minimise collection.** Collect only information necessary for the defined purpose. Check free-text fields and uploads for unintended identifiers.
3. **Use pseudonymisation appropriately.** Keep linkage keys separately with restricted access. Pseudonymised data remain personal data; replacing names with codes does not make a dataset anonymous.
4. **Control access and transfers.** Use approved systems, appropriate encryption, assigned accounts and traceable access. Check recipient authority and transfer integrity before importing an extract.
5. **Maintain participant-status procedures.** Follow the approved process for withdrawals, restrictions or changes in permissions, and communicate relevant changes to downstream custodians.
6. **Escalate incidents.** Follow institutional procedures for misdirected transfers, unauthorised access and other security or privacy incidents.

Apply the institution's requirements to actual collection practices, including temporary exports and local copies. **Storage & Management remains cross-cutting throughout the life cycle**, covering secure storage, backup, access and retention during collection as well as later stages.

## Example: collecting data in a multicentre epidemiological study

*Illustrative scenario:* The study introduced on the Planning page examines lifestyle factors and incident type 2 diabetes using questionnaires, clinical measurements and authorised health-record extracts from several institutions.

| Collection decision | Practical implementation |
| --- | --- |
| **Use a shared collection specification** | All sites use agreed questionnaire versions, visit definitions and variable codes; local differences are documented. |
| **Keep measurements interpretable** | Each site records laboratory units and relevant methods. Different units remain explicit in source data and are harmonised through documented processing. |
| **Protect participants** | Study IDs appear in research records; identity/linkage files remain under separately controlled institutional access. |
| **Document secondary acquisition** | Each health-record extract has recorded eligibility rules, time coverage, source version and approval conditions. |
| **Monitor quality** | Sites review duplicate IDs, missing visits, incompatible dates and implausible values; corrections are checked against the source and logged. |
| **Connect documentation** | The dictionary and collection SOPs are versioned; suitable study descriptions are prepared using the Metadata Schema and, where deployed, organised in the Local Data Hub. |
| **Prepare handover** | Processing receives a dated raw snapshot, dictionary, provenance and unresolved-query list through an approved transfer or local workflow. |

For example, if one laboratory reports glucose in a different unit, the team records that difference, verifies the source and documents a conversion in the processing workflow. It does not overwrite the original measurement without a traceable record.

## Collection checklist

Use this checklist before collection starts and during scheduled collection reviews:

- [ ] &nbsp;&nbsp;Collection or acquisition is covered by the relevant approvals, permissions and agreements.
- [ ] &nbsp;&nbsp;The protocol, DMP and collection specification are consistent and current.
- [ ] &nbsp;&nbsp;Instruments, forms and extraction rules are versioned, configured and pilot-tested.
- [ ] &nbsp;&nbsp;Staff responsibilities and training are documented.
- [ ] &nbsp;&nbsp;Variable definitions, units, codes and missing-value meanings are recorded.
- [ ] &nbsp;&nbsp;Study and participant identifiers are consistent; identity/linkage information is separately protected.
- [ ] &nbsp;&nbsp;Source provenance, timing and relevant instrument versions are captured.
- [ ] &nbsp;&nbsp;Quality checks, source queries and traceable correction procedures are operating.
- [ ] &nbsp;&nbsp;Approved storage, access, transfer, backup and recovery arrangements are in place.
- [ ] &nbsp;&nbsp;Study metadata and documentation suitable for later discovery are maintained.
- [ ] &nbsp;&nbsp;The handover package includes raw data, dictionary, provenance and unresolved issues.

## When should collection procedures be updated?

Review procedures after protocol amendments, new instruments, new sites, changes to source systems or recurring quality problems. Check whether changes require additional approvals before implementation. Record what changed, why, when and who authorised it; retain previous versions so observations remain interpretable.

Update the DMP when collection practice changes. Do not silently apply a new definition to earlier records. Distinguish correction of an error from a change in measurement or study procedure.

## Further resources and support

- [NFDI4Health services]({{ '/services' | relative_url }}) — overview of metadata, discovery, quality and privacy resources.
- [NFDI4Health Metadata Schema](https://www.nfdi4health.de/en/service/metadata-schema.html) — structured description of health research resources.
- [Local Data Hub](https://www.nfdi4health.de/en/service/local-data-hub.html) — institutional organisation of connected resources and access permissions.
- [Health Study Hub](https://health-study-hub.de/) — discovery of studies and supporting resources.
- [NFDI4Health DMP templates](https://www.nfdi4health.de/en/service/guidelines/researchdatamanagementplans.html) — maintain the agreed data strategy.
- [NFDI4Health Helpdesk](https://www.nfdi4health.de/en/helpdesk.html) — questions about services and documentation workflows.
- [RDMkit: Collecting](https://rdmkit.elixir-europe.org/collecting) — complementary guidance on collection and documentation.
- [GDPR, Regulation (EU) 2016/679](https://eur-lex.europa.eu/eli/reg/2016/679/oj) — official legal text; consult institutional experts for its application.
- [Data organisation]({{ '/data_organisation' | relative_url }}), [metadata management]({{ '/metadata_management' | relative_url }}), [data quality]({{ '/data_quality' | relative_url }}) and [data provenance]({{ '/data_provenance' | relative_url }}) — related practical guidance.
- [Researcher]({{ '/researcher' | relative_url }}) and [data steward]({{ '/data_steward' | relative_url }}) — related roles; [training modules]({{ '/modules' | relative_url }}) — further self-paced learning.

**Previous life-cycle stage:** [Planning]({{ '/planning' | relative_url }}) — agree the data strategy and collection requirements.

**Next life-cycle stage:** [Processing]({{ '/processing' | relative_url }}) — clean, standardise and prepare collected data while preserving their provenance and protections.

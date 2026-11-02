---
title: Preserving
page_id: preserve
description: Select, document and preserve health research data so that they remain secure, understandable and usable for the required period.
related_pages:
  Your_tasks: [data_organisation, data_security, data_publication, metadata, storage, identifiers, licensing, data_provenance, data_deletion]
---

## What is data preservation?

Data preservation keeps research data and the information needed to interpret them usable over time. It includes selecting what to retain, documenting its meaning, checking file integrity, maintaining readable formats and assigning responsibility after the project ends. A backup helps recover lost files; preservation also addresses whether those files can still be opened, understood and used. [1–4]

In health research, preservation covers more than the final analysis table. Study protocols, data dictionaries, processing scripts, analysis settings and quality reports may be essential to explain how a result was produced. Begin planning during [Planning]({{ '/planning' | relative_url }}) and update the arrangements after [Analysing]({{ '/analysing' | relative_url }}).

## Why is data preservation important?

Clinical, cohort and public health data can be costly or impossible to collect again. Preserving their context supports verification of findings and future research, including when staff, software or storage systems change. Responsibilities, resources and retention decisions must therefore extend beyond the project team's immediate needs. [1–4]

## What should be considered for preserving data?

### 1. Select the materials and agree retention responsibilities

Identify the data and documents needed to support published results, meet applicable requirements and enable justified future reuse. Distinguish essential source data, reviewed derived datasets and reusable code from temporary files that can be regenerated. Record selection decisions and the reasons for exclusions. [1,2,4]

Agree a retention schedule with the responsible institution. For each category, record the applicable requirement, the event from which the period runs, the responsible custodian, review dates and the decision process at the end of retention. Requirements can differ between study types and records; do not apply one duration to every health dataset. Resolve the balance between preservation and any applicable deletion obligations with the responsible specialists. [3]

Include costs, contact details and a handover plan in the [data management plan]({{ '/data_management_plan' | relative_url }}). See also [Data deletion]({{ '/data_deletion' | relative_url }}).

### 2. Choose a suitable preservation service

Discuss options with the institutional library, research data management team and IT service. Check the service's documented preservation commitments rather than relying on the existence of a storage account. [1,4,5]

| Check | Question to resolve |
| --- | --- |
| Data suitability | Does the service accept the data type, volume and sensitivity level? |
| Preservation | How are integrity, format readability and migrations managed? |
| Access | Can the service enforce the required restrictions and record access decisions? |
| Sustainability | Who maintains the service, and what happens if it closes? |
| Responsibilities | Who handles metadata, costs, contact changes and retention reviews? |
| Recovery | How are backups, restoration and encryption-key recovery managed? |

Repository certification can inform selection, but its scope and the actual service conditions still need checking. See [Storage]({{ '/storage' | relative_url }}) and [Data security]({{ '/data_security' | relative_url }}).

### 3. Prepare a documented preservation package

Organise a stable release with meaningful file names and a manifest listing its contents and versions. Include enough context for someone outside the original team to understand it. [1,2,5]

- A README explaining the study, file structure, responsible contacts and restrictions.
- Dataset descriptions and variable-level dictionaries, including units, coding and missing-value conventions.
- Relevant protocols, instruments, harmonisation mappings and quality reports.
- Processing and analysis code, software versions and instructions for reproducing outputs.
- Provenance, rights information and relationships to publications and other releases.

Keep confidential operational records, participant information and linkage keys under their appropriate access arrangements. They do not belong in a public documentation bundle. See [Data organisation]({{ '/data_organisation' | relative_url }}), [Documentation and metadata]({{ '/metadata_management' | relative_url }}) and [Data provenance]({{ '/data_provenance' | relative_url }}).

### 4. Preserve meaning when selecting file formats

Use formats accepted by the preservation service, favouring documented, widely supported formats. Depending on the content, suitable options may include CSV or TSV for simple tables, TXT for plain text, XML or JSON for structured information, and PDF/A for stable document presentation. [1,2,4]

Check that conversion retains the information needed for reuse. A CSV export, for example, needs separate documentation for variable labels, value codes, types and units. Keep the original alongside an archival export where needed and permitted. Record conversions and validate the result. A file extension alone does not demonstrate that a file is valid or preservation-ready.

### 5. Verify the deposit and maintain it

Agree file-integrity checks with the service, including checksums at transfer and subsequent checking. Confirm that files can be retrieved and opened, documentation matches the deposited version, and authorised users can access the package. Record acceptance by the custodian. [1,2,4]

Maintain access restrictions and recoverable encryption arrangements over the retention period. Review contact details, software dependencies and readability when systems change. Document migrations and authorised disposal decisions rather than silently overwriting or removing a preserved release.

### 6. Connect preservation with NFDI4Health discovery services

The [Health Study Hub]({{ '/services/health-study-hub' | relative_url }}) supports discoverability of study descriptions and supporting documents. Use the [Metadata Schema]({{ '/services/metadata-schema' | relative_url }}) to describe the resource and its access route. Under the NFDI4Health Publication Policy, participant-level data are not published in the Hub. Their preservation remains a separate institutional responsibility. [6,7]

Connect the public study record to the appropriate documents and access information while keeping restricted data in the agreed environment. Persistent identifiers help identify resources; they do not replace preservation arrangements. See [Identifiers]({{ '/identifiers' | relative_url }}) and [Sharing]({{ '/sharing' | relative_url }}).

## Example: closing a cohort-study project

*Illustrative example.* A study team preserves its reviewed dataset, dictionary, harmonisation mappings and analysis scripts in an approved institutional archive. It validates exported files, records checksums and appoints a continuing custodian. Public study metadata, the protocol and a reviewed dictionary are made discoverable through the Health Study Hub. Participant-level records and linkage keys remain restricted. The retention schedule identifies who will review the package and its access arrangements after the project ends.

## Checklist

- Selection decisions, retention requirements and responsible custodians are recorded.
- The preservation service supports the data's sensitivity and required duration.
- The package includes documentation, provenance, rights and version information.
- File conversions, integrity and retrieval have been checked.
- Ongoing costs, access, key recovery and staff handover are addressed.
- Public metadata accurately describe where and how the retained resources can be accessed.

Continue to [Sharing]({{ '/sharing' | relative_url }}) and [Reusing]({{ '/reusing' | relative_url }}). Preservation planning and review continue throughout the lifecycle.

Learning structure and review checklist informed by Skills4EOSC, *FAIR-by-Design Methodology for learning materials*, version 1.0 (2025), pp. 4–7, [doi:10.5281/zenodo.14711525](https://doi.org/10.5281/zenodo.14711525).

## References

1. Fürst, J., on behalf of NFDI4Health (2026). *Archiving and Long-Term Preservation*. Online RDM training, 17 September 2026, slides 5–12. Project resource: `2026_09_15_Archiving_and_Longterm_Preservation.pptx`.
2. Zeleke, A. (2026). *Data Storage, Backup, Security and Long-Term Preservation in Biomedical Research*, slides 24–33. Project resource:NOT published `2026_09_15_Data_Storage_BackupSecurity_LongTermPreservation.pptx`.
3. Dierkes, J., et al. (2023). *Training concepts in research data management and data science with the focus on health research*, sections 3.4–3.6, pp. 29–33; preservation learning objectives, p. 39. [doi:10.4126/FRL01-006441348](https://doi.org/10.4126/FRL01-006441348).
4. Biernacka, K., et al. (2024). *Train-the-Trainer Concept on Research Data Management*, version 5.1, Unit 10, printed pp. 68–70 (PDF pp. 85–87). [doi:10.5281/zenodo.13927614](https://doi.org/10.5281/zenodo.13927614).
5. FAIRagro. *Data Storage: What is Data Preservation?*, PDF p. 2; *Preparing data for publishing: checklist for deposit*, PDF pp. 2–3. Project resource: `Bricks_pdf.7z`, bricks `09-02_DataStorage_DefinitionDataPreservation_Slides.pdf` and `10-01-11-01_DataPreparation_ChecklistShort.pdf`.
6. Fürst, J., Lindstädt, B., and Shutsko, A. (2025). *Publication Policy of the NFDI4Health*, V2_1, sections 2.1–2.2 and 2.5–2.6. [doi:10.4126/FRL01-006484167](https://doi.org/10.4126/FRL01-006484167).
7. NFDI4Health. [Health Study Hub: Frequently Asked Questions](https://www.nfdi4health.de/en/service/health-study-hub/frequently-asked-questions.html), sections on data publication and the Hub. Accessed 28 October 2026.

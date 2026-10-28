---
title: Processing
page_id: process
description: Prepare health research data for analysis through documented cleaning, quality assessment and harmonisation.
related_pages: 
  Your_tasks: [data_analysis, data_organisation, data_quality, data_provenance, metadata, sensitive, data_security]
training:
  - name: Data processing Search query in TeSS
    registry: TeSS
    url: https://tess.elixir-europe.org/search?q=%22data+process%22#materials
dsw:
- name: List the data formats you will be using for interpretation and describe their
    structure
  uuid: a797cab9-0829-4787-a096-1b5cedc9147f
- name: How will you work with your data?
  uuid: df36fb68-131c-4f31-a42b-684abf523bbc
---

## What is data processing?

Data processing turns collected or received data into documented datasets that are suitable for a defined research purpose. In clinical, epidemiological and public health research, this includes checking data structure, resolving errors, aligning units and coding, deriving variables and documenting each transformation.

Within NFDI4Health, processing connects study data and their documentation with quality assessment, harmonisation and subsequent analysis. It may take place locally at each data-holding institution, including when preparing for distributed analysis. A processed dataset is not automatically suitable for every research question: remaining limitations must be made explicit.

Start with the outputs of [Collecting]({{ '/collecting' | relative_url }}) and the decisions recorded in your [data management plan]({{ '/data_management_plan' | relative_url }}).

## Why is data processing important?

Differences in measurement methods, missing-value codes, units and variable definitions can lead to misleading comparisons. A reproducible processing workflow helps researchers identify these differences, assess fitness for use and understand how an analysis dataset was produced. It also allows corrections to be traced back to their source.

Keep the original data unchanged and work on controlled copies. Unexpected values should be flagged and investigated; they should not be deleted simply because they are unusual.

## What should be considered for data processing?

### 1. Organise and inspect the input data

Identify the source, version and receipt date of each dataset. Check file formats, character encoding, variable types, record counts, identifiers and table relationships before combining files. Distinguish legitimate repeated measurements from duplicate records.

Separate source data, intermediate files, analysis-ready outputs, scripts and documentation. Use consistent file names and version identifiers so that each output can be traced to its inputs.

See [Data organisation]({{ '/data_organisation' | relative_url }}) and [Storage]({{ '/storage' | relative_url }}).

### 2. Check and document data quality

Define checks using the study protocol and data dictionary. Examine missingness, permitted values, ranges, dates, cross-variable consistency and differences between centres or collection waves. Distinguish missing, not applicable, not measured and refusal codes where the source documentation supports this distinction.

NFDI4Health supports quality assessment through **dataquieR**, an R package. Its supporting framework distinguishes integrity, completeness, consistency and accuracy. Configure checks using suitable metadata and review the findings with people who understand the study; a flagged value is a query for investigation, not proof of an error.

Record each issue, the evidence reviewed, the decision and any correction. Repeat relevant checks after transformations and retain unresolved issues in the quality report.

See [Data quality guidance]({{ '/data_quality' | relative_url }}), [NFDI4Health Data Quality Assessments]({{ '/services/data-quality' | relative_url }}) and the [dataquieR framework and documentation](https://dataquality.qihs.uni-greifswald.de/).

### 3. Clean and transform data reproducibly

Use scripts or recorded workflows for format conversions, recoding, unit conversion and derived variables. Define rules before applying them, retain original variables where appropriate and record changes in a transformation log. Avoid undocumented spreadsheet edits.

For each derived variable, document its source variables, formula, units, missing-data handling and applicable population. Agree exclusions and imputation with the analysis team and distinguish these decisions from corrections to verified data errors.

See [Data provenance]({{ '/data_provenance' | relative_url }}) and [Data analysis guidance]({{ '/data_analysis' | relative_url }}).

### 4. Harmonise variables across studies

For cross-study research, first define the variables needed for the research question in a target data schema. Compare source definitions, measurement methods, time points, units and categories before deciding whether variables can be combined.

The NFDI4Health harmonisation workflow uses a target schema, study-specific data dictionaries and documented harmonisation rules. Assess whether harmonisation is complete, partial or impossible for each variable. Preserve this assessment alongside the transformed data; a shared variable name does not establish comparability.

Use terminology identifiers and versions where appropriate, and record source-to-target mappings and any information loss. The NFDI4Health Terminology Service helps locate standardised concepts; the scientific suitability of a mapping still needs review.

See the [NFDI4Health harmonisation protocol](https://github.com/nfdi4health/data-harmonisation-protocol/wiki) and [Terminology Service](https://www.nfdi4health.de/en/service/terminology-service.html).

### 5. Protect sensitive data throughout processing

Use the institutionally approved processing environment and access arrangements for the project. Keep identifying information and linkage keys separate from working research datasets, according to the agreed procedures. Check free-text fields, file names and generated reports for unintended disclosure before exporting them.

Apply the project's agreed pseudonymisation or anonymisation procedures with the responsible data-protection specialists. Do not assume that removing names alone makes a dataset anonymous. Quality reports and processing logs also need appropriate protection when they contain individual-level information.

See [Data sensitivity]({{ '/data_sensitivity' | relative_url }}), [Data security]({{ '/data_security' | relative_url }}) and [Data transfer]({{ '/data_transfer' | relative_url }}).

### 6. Update documentation and prepare the handover

Deliver the processed dataset with its data dictionary, processing scripts, software versions, mapping tables, quality report and documented limitations. Record which source and workflow versions generated the release, who reviewed it and when. Include instructions for rerunning the workflow in the authorised environment.

Update study and resource metadata when processing produces a new dataset version or changes its description. The NFDI4Health metadata schema supports resource description; it complements the variable-level dictionary and transformation records needed to interpret the data.

See [Documentation and metadata]({{ '/metadata_management' | relative_url }}), [NFDI4Health Metadata Schema]({{ '/services/metadata-schema' | relative_url }}) and [Preserving]({{ '/preserving' | relative_url }}).

## Practical example: preparing a multicentre cohort dataset

*Illustrative example, not a report of an implemented NFDI4Health study.*

Two centres provide height and weight measurements for a joint analysis. Height is recorded in centimetres at one centre and metres at the other; missing-value codes also differ.

1. Preserve both input datasets and inspect their dictionaries, participant keys and measurement time points.
2. Agree target definitions and units. Confirm that the measurements refer to comparable visits.
3. Map missing-value codes using the source documentation and convert height to the agreed unit through a versioned script.
4. Check ranges, missingness and consistency before and after conversion. Query unusual values with the relevant centre.
5. Derive BMI only when the required measurements are available and appropriate; document the formula and exclusions.
6. Release the reviewed dataset with the mapping table, scripts, dictionary and quality report. For distributed analysis, apply the agreed workflow locally and use the approved analysis arrangements.

## Checklist before moving to analysis

- Original data are preserved and each input version is identifiable.
- Cleaning and transformation decisions are documented and reproducible.
- Quality checks have been reviewed and unresolved issues are recorded.
- Harmonisation mappings and limits to comparability are explicit.
- Sensitive information is handled under the agreed access and processing arrangements.
- The output dataset, dictionary, scripts and quality report have matching version information.

Continue to [Analysing]({{ '/analysing' | relative_url }}). If issues require changes to capture procedures, return to [Collecting]({{ '/collecting' | relative_url }}).

## Further support and sources

- [NFDI4Health services overview](https://www.nfdi4health.de/en/service/our-services.html)
- [NFDI4Health Data Quality Assessments](https://www.nfdi4health.de/en/service/data-quality-assessments.html)
- [Data quality framework: dimensions and concepts](https://dataquality.qihs.uni-greifswald.de/DQconceptNew.html)
- [NFDI4Health Helpdesk](https://www.nfdi4health.de/en/helpdesk.html)

## Source attribution

Adapted from the ELIXIR RDMkit Processing page included in the original Knowledge Base source. That source credits Rob Hooft and Munazah Andrabi as contributors, and Bert Droesbeke and Flora D’Anna as editors. These credits refer to the original material, not to authorship or review of this NFDI4Health adaptation.

This adaptation expands the health-research workflow, adds NFDI4Health resources and an illustrative example, and updates links to related Knowledge Base guidance.


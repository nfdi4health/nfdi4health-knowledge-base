---
title: Analysing
page_id: analyse
description: Plan, conduct and document reproducible analyses of health research data, including distributed analysis in the NFDI4Health context.
related_pages:
  Your_tasks: [data_analysis, data_organisation, data_quality, data_provenance, metadata, sensitive, data_security, storage]
training:
  - name: Data analysis search query in TeSS
    registry: TeSS
    url: https://tess.elixir-europe.org/search?q=%22data+analysis%22#materials
---

## What is data analysis?

Data analysis uses appropriate methods to answer research questions, describe patterns and evaluate relationships in data. In clinical, epidemiological and public health research, it can include descriptive statistics, statistical modelling, qualitative interpretation and predictive modelling.

Analysis builds on the reviewed datasets and documentation produced during [Processing]({{ '/processing' | relative_url }}). It is often iterative: an unexpected result may reveal a coding issue or require a revised interpretation. Record these decisions and return to processing when corrections are needed, rather than silently changing an analysis input.

In the NFDI4Health context, analysis may be performed within one institution or across several data-holding institutions. Distributed approaches allow analytical tasks to run where the data are held, subject to the participating institutions' access and operating arrangements.

## Why is data analysis important?

Analysis turns research data into evidence. Its credibility depends on the suitability of the methods, the quality and comparability of the data, and transparent reporting of decisions and uncertainty. A reproducible workflow makes it possible to trace a table, figure or model back to the data version, code and settings that produced it.

FAIR practice includes documenting and, where possible, sharing analysis code, workflows and metadata. This does not require unrestricted publication of sensitive participant-level data. Explain how authorised researchers can access the inputs or reproduce the work within an approved environment.

## What should be considered for data analysis?

### 1. Define the research question and analysis plan

Specify the study population, outcomes, exposures, relevant time points and intended comparisons. Agree the methods with the appropriate methodological experts before the main analysis. Document inclusion and exclusion criteria, handling of missing data, relevant adjustment variables and planned sensitivity analyses.

Distinguish planned analyses from exploratory work. If the plan changes, record what changed, why, when and whether results had already been examined. Align the analysis with the study protocol, approved data use and [data management plan]({{ '/data_management_plan' | relative_url }}).

### 2. Confirm that the data are fit for the intended analysis

Review the data dictionary, quality report and processing history. Check variable meanings, measurement units, population coverage and the reasons for missing values. In multicentre or longitudinal work, examine differences between sites, collection waves and measurement methods.

For cross-study analyses, review the harmonisation mappings and any partial or impossible mappings. Consistent labels do not guarantee equivalent measurements. Record which limitations affect the research question and how they will be addressed or reported.

See [Data quality]({{ '/data_quality' | relative_url }}), [NFDI4Health Data Quality Assessments]({{ '/services/data-quality' | relative_url }}) and [Processing]({{ '/processing' | relative_url }}).

### 3. Choose an appropriate analysis environment

Select tools and computing resources that support the required methods, data volumes and access arrangements. Agree where data, code and results will be stored, who can access them and how outputs can leave the environment. Use institutional support when setting up collaborative or distributed workflows.

| Approach | When it may be appropriate | What to agree before starting |
| --- | --- | --- |
| Analysis within a data-holding institution | The required data and computing resources are available locally. | Authorised users, software, storage, backup and output review. |
| Centralised analysis of approved data transfers | Participating institutions permit the necessary data to be brought together. | Transfer arrangements, receiving environment, responsibilities and dataset versions. |
| Distributed analysis | Individual-level data remain at participating institutions while analytical tasks run locally. | Common variable definitions, supported methods, local setup, access and disclosure controls. |

NFDI4Health supports distributed analysis through **DataSHIELD** and **Personal Health Train**. The [official services overview](https://www.nfdi4health.de/en/service/our-services.html) describes DataSHIELD support for clinical, epidemiological and public health research. The [Personal Health Train service page](https://www.nfdi4health.de/en/service/personal-health-train.html) describes bringing analytical tasks to the data; the overview currently describes its NFDI4Health image-analysis use as a pilot.

Confirm suitability and availability with the service team for the intended project. Distributed infrastructure does not by itself resolve methodological differences or replace institutional authorisation and output review.

See [Data security]({{ '/data_security' | relative_url }}), [Data transfer]({{ '/data_transfer' | relative_url }}) and [Storage]({{ '/storage' | relative_url }}).

### 4. Make the workflow reproducible

Keep analysis code under version control and use identifiable, reviewed input datasets. Record software and package versions, dependencies, parameters and random seeds where applicable. Retain an environment specification or other instructions sufficient to recreate the supported setup.

Generate tables and figures from scripts or reproducible reports wherever possible. Record manual steps explicitly. Keep exploratory outputs separate from the reviewed results used in reporting, and avoid including sensitive data, passwords or access tokens in code repositories.

Before releasing a result, rerun the workflow from the documented inputs in a clean session or agreed environment. Ask another team member to review key code and outputs. Some computational methods are not fully deterministic; document relevant limitations rather than promising identical results in every environment.

See [Data analysis guidance]({{ '/data_analysis' | relative_url }}), [Data provenance]({{ '/data_provenance' | relative_url }}) and [Data organisation]({{ '/data_organisation' | relative_url }}).

### 5. Evaluate and interpret the results

Check that denominators, units, labels and uncertainty measures match the analysis. Investigate unexpected patterns with the study team. Report assumptions, missingness, exclusions and limitations that could affect interpretation. Distinguish associations from causal claims and avoid presenting exploratory findings as prespecified conclusions.

For multicentre work, consider whether differences in populations or measurement practices could explain differences in results. For predictive modelling, document training and evaluation procedures and prevent information from evaluation data leaking into model development. The level of methodological review should match the intended use of the findings.

### 6. Review outputs and prepare them for preservation and sharing

Review tables, figures, model objects, logs and notebooks before export or publication. They may reveal sensitive information through small groups, individual observations, free text or embedded data. Apply the agreed institutional disclosure-review process; do not assume that an aggregate output is automatically safe to publish.

Package the approved results with the analysis plan, README, code version, environment information and input dataset references. Document how to reproduce the outputs, access conditions and known limitations. Use appropriate licences for materials that can be released and retain restricted materials in the authorised location.

See [Data sensitivity]({{ '/data_sensitivity' | relative_url }}), [Documentation and metadata]({{ '/metadata_management' | relative_url }}), [Licensing]({{ '/licensing' | relative_url }}) and [Sharing]({{ '/sharing' | relative_url }}).

## Practical example: analysing a multicentre cohort

*Illustrative example, not a report of an implemented NFDI4Health study.*

Two centres have prepared harmonised height and weight measurements and a documented BMI variable. The research team wants to describe BMI distributions and examine their association with an agreed outcome.

1. Finalise the population, measurement time point and analysis plan with the study statistician.
2. Review harmonisation and quality reports, including missing measurements and site differences.
3. Agree whether the work will run in an approved central environment or through a supported distributed setup. Confirm that the required methods are available.
4. Run versioned scripts and record input versions, software settings and any deviations from the plan.
5. Review estimates, uncertainty and site-related limitations. Return to processing if a verified data error is found, then rerun the affected analyses.
6. Apply output review and preserve the approved results with the code, documentation and access information.

## Checklist before moving to preservation and sharing

- The research question, analysis plan and deviations are documented.
- Dataset versions, quality issues and harmonisation limitations are traceable.
- Methods and computing arrangements are appropriate for the intended use.
- Code, dependencies, settings and inputs needed to reproduce the work are recorded.
- Key results have been checked and interpreted with relevant expertise.
- Outputs have passed the agreed disclosure review.
- Approved results, code and documentation are ready for preservation with clear access conditions.

Continue to [Preserving]({{ '/preserving' | relative_url }}) and [Sharing]({{ '/sharing' | relative_url }}). Return to [Processing]({{ '/processing' | relative_url }}) if the analysis identifies data issues requiring correction.

## Further support and sources

- [NFDI4Health services overview](https://www.nfdi4health.de/en/service/our-services.html): distributed analysis and related services.
- [NFDI4Health Personal Health Train](https://www.nfdi4health.de/en/service/personal-health-train.html): concept and implementation examples.
- [NFDI4Health Helpdesk](https://www.nfdi4health.de/en/helpdesk.html): questions on suitable services and support.

## Source attribution

Adapted from the ELIXIR RDMkit Analysing page included in the original Knowledge Base source. That source credits Rob Hooft, Olivier Collin, Munazah Andrabi and Flora D’Anna as contributors, and Munazah Andrabi as editor. These credits refer to the original material, not to authorship or review of this NFDI4Health adaptation.

This adaptation expands health-research analysis planning, reproducibility, distributed analysis, output review and links to related Knowledge Base guidance.

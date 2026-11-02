---
title: Reusing
page_id: reuse
description: Find, assess and responsibly reuse existing health research resources with clear access conditions, provenance and acknowledgement.
related_pages:
  Your_tasks: [data_analysis, transfer, existing_data, identifiers, licensing, data_provenance, data_quality, metadata, sensitive]
---

## What is data reuse?

Data reuse applies existing data or research resources to a further purpose, such as answering a new question, validating findings or designing a new study. Reusable resources include participant-level datasets, aggregate results, questionnaires, dictionaries and code. Reuse depends on understanding the resource and having appropriate permission for the intended use. [1–3]

In NFDI4Health, the Health Study Hub helps researchers find study information and supporting documents. Discovery is the starting point: it does not establish that the underlying participant-level data are suitable or available for a particular project. [4]

## Why is data reuse important?

Reusing existing data can reduce duplicate collection and participant burden, support independent verification and enable comparisons across studies. Its scientific value depends on fitness for the new purpose. A large or well-described dataset may still have the wrong population, time points or measurements for the proposed question. [1–3]

Search for relevant resources during [Planning]({{ '/planning' | relative_url }}) before committing to new collection. If reuse is not feasible, document the reasons so that they inform the next study.

## What should be considered for data reuse?

### 1. Define the data needed before searching

Describe the research question, target population, variables, measurement time points, study design and minimum documentation needed. Consider whether existing measurements are appropriate proxies and what limitations would make a resource unsuitable. [3]

Record search terms, filters, dates and the reasons for retaining or excluding candidate resources. Combine relevant clinical terms with alternative names used by different studies. See [Existing data]({{ '/existing_data' | relative_url }}).

### 2. Find studies and examine their documentation

Search the [Health Study Hub](https://health-study-hub.de/) for relevant studies and supporting resources. Examine protocols, questionnaires and dictionaries where available. Comparing documented variables can help identify candidates for cross-study work, but a matching label does not establish comparable measurements. [4]

Follow links to related resources and use the study's contact or access route to resolve missing information. Record the identifiers and versions consulted. See [Health Study Hub guidance]({{ '/services/health-study-hub' | relative_url }}) and [Documentation and metadata]({{ '/metadata_management' | relative_url }}).

### 3. Establish the permitted use and access route

For public documents, check the licence and any third-party restrictions, including whether adaptation and redistribution are permitted. For participant-level data, agree the proposed purpose, requested variables, approved users, environment and conditions with the data holder through the applicable process. Public metadata or a document licence do not grant permission to use the underlying personal data. [1,3,5]

The [FDPG](https://www.nfdi4health.de/en/service/german-portal-for-medical-research-data-fdpg.html) provides a data-request route, with NFDI4Health coverage being extended. Confirm whether the selected study participates; otherwise follow its stated institutional route. A request may involve feasibility assessment, review and contractual arrangements before access is provided. [6]

See [Licensing]({{ '/licensing' | relative_url }}), [Data sensitivity]({{ '/data_sensitivity' | relative_url }}) and [Data transfer]({{ '/data_transfer' | relative_url }}).

### 4. Assess fitness for the new research question

Review the original purpose and methods rather than relying only on a catalogue summary. Resolve important gaps with the data provider and document remaining uncertainty. [1,3]

| Aspect | Questions for reuse |
| --- | --- |
| Population | Who was included or excluded, and how does this compare with the target population? |
| Measurement | What instruments, units, categories and definitions were used? |
| Time | Do measurement dates, follow-up periods and changes over time match the question? |
| Quality | What missingness, errors or other limitations have been documented? |
| Provenance | Which transformations and corrections produced the available version? |
| Feasibility | Are the necessary variables, permissions, computing resources and expertise available? |

A dataset's suitability can differ between analyses. Record a justified decision to proceed, narrow the question or stop. See [Data quality]({{ '/data_quality' | relative_url }}) and [NFDI4Health Data Quality Assessments]({{ '/services/data-quality' | relative_url }}).

### 5. Harmonise and analyse without losing provenance

Keep the received version identifiable and work on controlled derived copies. Record source-to-target mappings, unit conversions, derived variables and any information loss. NFDI4Health's harmonisation approach uses a target data schema and study-specific dictionaries to assess whether variables can be harmonised completely, partly or not at all. [7]

Plan the analysis environment with the participating institutions. Where supported, DataSHIELD or Personal Health Train can allow analytical tasks to run at data-holding sites. Availability, supported methods and local controls need confirmation for the project. [8]

See [Processing]({{ '/processing' | relative_url }}), [Analysing]({{ '/analysing' | relative_url }}) and [Data provenance]({{ '/data_provenance' | relative_url }}).

### 6. Cite the resources and return useful information

Cite the actual resources used, including creators, title, year, version and persistent identifier where available. Distinguish the study-description identifier from identifiers for documents or datasets. Keep a record of the access date and any restricted release identifier needed to identify the analysed data. [3,5]

Report limitations and follow the agreed acknowledgement and reporting conditions. Tell the data provider about confirmed metadata or quality issues through the appropriate channel. Where permitted, share reusable code, mappings and documentation with clear links to their sources. Do not redistribute restricted inputs merely because a derived output has been created. [3]

See [Identifiers]({{ '/identifiers' | relative_url }}), [Sharing]({{ '/sharing' | relative_url }}) and [Preserving]({{ '/preserving' | relative_url }}).

## Example: assessing two cohorts for a new question

*Illustrative example.* A researcher finds two cohorts with information on physical activity and a health outcome. The dictionaries show that one cohort recorded activity duration while the other used broad frequency categories. The researcher discusses access and measurement details with both data holders, assesses whether a defensible common variable is possible and records the limitations. Only approved data enter the agreed analysis environment. The resulting work cites the source resources and releases permitted code and mapping documentation.

## Checklist

- The research question and minimum data requirements are clear.
- Search decisions, resource identifiers and versions are recorded.
- The intended use and access conditions have been agreed.
- Population, measurement, time coverage and quality have been assessed.
- Harmonisation decisions and analysis provenance are documented.
- Citations, feedback and permitted outputs are prepared.

Return to [Planning]({{ '/planning' | relative_url }}) to turn the reuse assessment into a new study plan. Where data are suitable and access is agreed, continue through [Processing]({{ '/processing' | relative_url }}) and [Analysing]({{ '/analysing' | relative_url }}).

## Source attribution

Learning structure and review checklist informed by Skills4EOSC, *FAIR-by-Design Methodology for learning materials*, version 1.0 (2025), pp. 4–7, [doi:10.5281/zenodo.14711525](https://doi.org/10.5281/zenodo.14711525).

## References

1. Dierkes, J., et al. (2023). *Training concepts in research data management and data science with the focus on health research*, sections 3.4–3.6, pp. 29–33; reuse learning objectives, p. 39. [doi:10.4126/FRL01-006441348](https://doi.org/10.4126/FRL01-006441348).
2. Zeleke, A. (2026). *The Biomedical Research Data Lifecycle*, slides 27–29; Zeleke, A., and Fürst, J. (2026). *FAIR Data Principles & NFDI4Health Services*, slides 15–18. Project resources: `2026_09_15_Biomedical_Research_Data_Lifecycle_Slides.pptx` and `2026_09_16_Biomedical FAIR Principle slides.pptx`.
3. FAIRagro. *Finding Data: Preparing Search*, PDF p. 2; *Check Reusability: Check License* and *Check Fitness-for-use*, PDF p. 2 each; *Reusing responsibly*, PDF pp. 2–3. Project resource: `Bricks_pdf.7z`, bricks `08-03-03-01_FindingData_PreparingSearch.pdf`, `08-03-04-01_DataReuse_CheckLicense.pdf`, `08-03-04-02_DataReuse_CheckFitness4Use.pdf` and `08-03-05_DataReuse_ReuseResponibly.pdf`.
4. NFDI4Health. [Health Study Hub: Frequently Asked Questions](https://www.nfdi4health.de/en/service/health-study-hub/frequently-asked-questions.html), sections on discovery and comparison of study resources. Accessed 28 October 2026.
5. Fürst, J., Lindstädt, B., and Shutsko, A. (2025). *Publication Policy of the NFDI4Health*, V2_1, sections 2.1, 2.4 and 2.5. [doi:10.4126/FRL01-006484167](https://doi.org/10.4126/FRL01-006484167).
6. NFDI4Health. [German Portal for Medical Research Data (FDPG)](https://www.nfdi4health.de/en/service/german-portal-for-medical-research-data-fdpg.html). Accessed 28 October 2026.
7. NFDI4Health. [Harmonisation: Enabling the Reuse of Existing Data](https://www.nfdi4health.de/en/component/sppagebuilder/page/615.html). Accessed 28 October 2026.
8. NFDI4Health. [Our Services](https://www.nfdi4health.de/en/service/our-services.html), sections on harmonisation and distributed analysis. Accessed 28 October 2026.

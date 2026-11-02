---
title: Sharing
page_id: share
description: Make health research resources discoverable and share them through appropriate publication, licensing and controlled-access arrangements.
related_pages:
  Your_tasks: [data_security, data_publication, transfer, identifiers, licensing, metadata, sensitive, data_provenance]
---

## What is data sharing?

Data sharing makes research resources available to others under stated conditions. These resources can include study descriptions, protocols, questionnaires, data dictionaries, code and datasets. The appropriate route depends on the resource: a blank questionnaire may be openly reusable, while participant-level health data need a controlled process. FAIR data can have access restrictions. [1–3]

In NFDI4Health, distinguish publication of metadata and study documents in the Health Study Hub from access to the underlying participant-level data. The Hub does not publish participant/patient individual data collected in studies. It can make the study and its access conditions discoverable. [1,4]

## Why is data sharing important?

Sharing well-documented resources helps researchers discover existing work, assess whether data could answer a new question and avoid unnecessary collection. Clear access conditions and citable versions make collaboration and reuse more reliable. Plan these arrangements early, then update them as the study and its outputs develop. [2,3]

## What should be considered for data sharing?

### 1. Decide what can be shared and by which route

Create an inventory of the resources and review their content, rights and sensitivity. Check that documents intended for publication contain no participant details, completed consent forms, confidential comments or embedded data. Obtain the necessary institutional and rights-holder decisions before release. [1–3]

| Resource | Possible route | Preparation needed |
| --- | --- | --- |
| Study or registry description | Public metadata in the Health Study Hub | Accurate description, access conditions and current contacts. |
| Protocol, blank questionnaire, dictionary or other eligible study document | Publication as a linked resource in the Hub | Content review, suitable format, rights clearance and licence information. |
| Participant-level data | Approved institutional access or supported distributed analysis | Project-specific authorisation, agreements and a suitable environment. |
| Code and reviewed research outputs | An appropriate repository or publication venue | Versioning, documentation, licence and disclosure review. |

Registration with the Health Study Hub should not be assumed to fulfil separate study-registration requirements. See [Data sensitivity]({{ '/data_sensitivity' | relative_url }}), [Data security]({{ '/data_security' | relative_url }}) and [Data publication]({{ '/data_publication' | relative_url }}).

### 2. Prepare metadata and supporting documents

Describe each resource using the [NFDI4Health Metadata Schema]({{ '/services/metadata-schema' | relative_url }}). Complete mandatory fields and relevant recommended fields, including informative titles, methods, population, collection period, keywords, contacts and access information. Link documents, substudies and related publications to the appropriate study record. [1]

For study documents, use readable and reusable formats accepted by the service. Where appropriate, supply structured dictionaries or questionnaires alongside human-readable documentation. Check terminology, units, missing-value codes and version labels. A resource should be understandable without relying on the original author to explain it. [1,2,5]

See [Documentation and metadata]({{ '/metadata_management' | relative_url }}) and [Data organisation]({{ '/data_organisation' | relative_url }}).

### 3. Clarify rights, licences and access conditions

Establish who may authorise publication and whether third-party content limits reuse. For eligible study documents, the NFDI4Health policy recommends less restrictive licences where possible, including Creative Commons options. State the chosen licence and its link inside the downloadable document as well as in its record. Check any exceptions or third-party material explicitly. [1, section 2.4]

Keep document licensing distinct from permission to access or process participant-level data. A licence attached to a questionnaire does not authorise access to completed participant responses. For restricted data, describe the application route, decision-maker, permitted uses and any agreement required. See [Licensing]({{ '/licensing' | relative_url }}) and [Data transfer]({{ '/data_transfer' | relative_url }}).

### 4. Submit and review resources in the Health Study Hub

Follow the current [Health Study Hub](https://health-study-hub.de/) submission route. The Publication Policy describes a workflow of resource selection, metadata preparation, document formatting and licensing, identifier assignment where eligible, and review by the publication team before release. Address any requested corrections and check the published record and files. [1]

Use an existing DOI where appropriate rather than requesting a duplicate for the same published object. Identify whether a citation points to a study description, a document or another resource, and record the version used. Discuss substantive document updates and identifier handling with the publication team. [1, section 2.5]

See [Health Study Hub guidance]({{ '/services/health-study-hub' | relative_url }}) and [Identifiers]({{ '/identifiers' | relative_url }}).

### 5. Explain controlled access clearly

A useful access statement identifies where a request should go, what information is needed and who decides. Keep it current even when data cannot be downloaded directly. The [German Portal for Medical Research Data (FDPG)](https://www.nfdi4health.de/en/service/german-portal-for-medical-research-data-fdpg.html) supports data requests; NFDI4Health is extending its coverage. Confirm whether the relevant study participates and use the route specified by its data holder. [6]

Distributed analysis may be an option when supported by the institutions and the required methods. It still requires agreed permissions, compatible data and output controls. See [Analysing]({{ '/analysing' | relative_url }}).

### 6. Maintain the shared record

Assign responsibility for contact changes, corrections, new versions and links to subsequent publications. Preserve released versions and explain how updates relate to them. Review public metadata and files when the resource or access conditions change. [1,2]

For a publication's data-availability statement, accurately describe what is public and what is restricted. Do not promise access that the data holder has not agreed to provide. See [Preserving]({{ '/preserving' | relative_url }}) and [Data provenance]({{ '/data_provenance' | relative_url }}).

## Example: sharing a completed cohort study

*Illustrative example.* The team publishes a study description, protocol and reviewed data dictionary in the Health Study Hub. It places licence information inside the eligible documents and links them to the study. Participant-level measurements stay at the data-holding institution. The public record explains the access application process and provides a maintained institutional contact. A later article cites the relevant resources and describes the controlled access conditions.

## Checklist

- Public resources and restricted participant-level data are clearly distinguished.
- Documents and metadata have been reviewed for unintended disclosure.
- Publication authority, third-party rights and licences are resolved.
- Metadata, resource relationships, identifiers and versions are accurate.
- The access route and responsible contact are current.
- The published record, downloadable files and links have been checked.

Continue to [Reusing]({{ '/reusing' | relative_url }}). Sharing arrangements should already be considered during [Planning]({{ '/planning' | relative_url }}).

## Source attribution

Learning structure and review checklist informed by Skills4EOSC, *FAIR-by-Design Methodology for learning materials*, version 1.0 (2025), pp. 4–7, [doi:10.5281/zenodo.14711525](https://doi.org/10.5281/zenodo.14711525).

## References

1. Fürst, J., Lindstädt, B., and Shutsko, A. (2025). *Publication Policy of the NFDI4Health*, V2_1, sections 2.1–2.7, pp. 3–15. [doi:10.4126/FRL01-006484167](https://doi.org/10.4126/FRL01-006484167).
2. Dierkes, J., et al. (2023). *Training concepts in research data management and data science with the focus on health research*, sections 3.4–3.6, pp. 29–33, and learning objectives, pp. 38–39. [doi:10.4126/FRL01-006441348](https://doi.org/10.4126/FRL01-006441348).
3. Biernacka, K., et al. (2024). *Train-the-Trainer Concept on Research Data Management*, version 5.1, Unit 15, printed pp. 88–91 (PDF pp. 105–108). [doi:10.5281/zenodo.13927614](https://doi.org/10.5281/zenodo.13927614).
4. NFDI4Health. [Health Study Hub: Frequently Asked Questions](https://www.nfdi4health.de/en/service/health-study-hub/frequently-asked-questions.html). Accessed 28 October 2026.
5. FAIRagro. *Preparing data for publishing: checklist for deposit*, PDF pp. 2–3. Project resource: `Bricks_pdf.7z`, brick `10-01-11-01_DataPreparation_ChecklistShort.pdf`.
6. NFDI4Health. [German Portal for Medical Research Data (FDPG)](https://www.nfdi4health.de/en/service/german-portal-for-medical-research-data-fdpg.html) and [Our Services](https://www.nfdi4health.de/en/service/our-services.html). Accessed 28 October 2026.
7. Zeleke, A. (2026). *The Biomedical Research Data Lifecycle*, slides 25–29. Project resource: `2026_09_15_Biomedical_Research_Data_Lifecycle_Slides.pptx`. Supports the stage structure and cohort example.
8. Fürst, J., on behalf of NFDI4Health (2026). *Data Management Planning*, slides 3, 7 and 10; *Sensitive Data and Privacy*, slides 3–10. Online RDM training, 17 September 2026. Project resources: `2026_09_15_Data_Management_Planning.pptx` and `2026_09_15_Sensitive_Data_and_Privacy.pptx`. Background for planning and content review.

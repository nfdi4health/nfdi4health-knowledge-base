---
title: Contribute to the NFDI4Health Knowledge Base
description: Submit service, module and research data lifecycle content by Word, Markdown or GitHub.
permalink: /how_to_contribute
sidebar: contribute
---

# Contribute to the NFDI4Health Knowledge Base

The NFDI4Health Knowledge Base is developed collaboratively by data stewards, service owners and other subject experts. We especially invite colleagues responsible for **NFDI4Health services**, **self-paced learning modules**, and **biomedical research data life-cycle guidance** to contribute or maintain relevant pages.

**You do not need GitHub experience to contribute.** Choose the route that suits you:

| Route | Suitable for | What happens next |
| --- | --- | --- |
| **Submit Word or Markdown to the coordination team** | Service owners and subject experts who prefer familiar document editing | The coordinator records the submission, arranges reviews and prepares the website update. |
| **Contribute through GitHub** | Colleagues comfortable with browser-based Markdown or Git | Open a pull request; subject and editorial reviewers check it before an authorised maintainer merges it. |
| **Volunteer as an editor or reviewer** | Colleagues willing to check clarity, evidence, biomedical accuracy, accessibility or website quality | Join a review team coordinated through agreed NFDI4Health channels; publishing access is assigned separately. |

## 1. Choose the right content template

The templates guide the content, but you may submit partial drafts. The [Module Authoring Template V001]({{ '/assets/contribution-templates/NFDI4Health_Module_Authoring_Template_V001.docx' | relative_url }}) is the **data-steward-agreed** structure for new self-paced modules (sections 0–15).

| Content | Word template | Markdown template | Reference example |
| --- | --- | --- | --- |
| **Service description** | [Word]({{ '/assets/contribution-templates/NFDI4Health_Service_Content_Template.docx' | relative_url }}) | [Markdown]({{ '/assets/contribution-templates/nfdi4health-service-template.md' | relative_url }}) | [Health Study Hub Word source]({{ '/assets/contribution-examples/EXACT_Service_Health_Study_Hub.docx' | relative_url }}) and [original Markdown](https://github.com/nfdi4health/nfdi4health-knowledge-base/blob/3f4025bc5171f13c9d07d789957d3d5d530f17d8/pages/tool_assembly/health_study_hub.md) |
| **Self-paced learning module** | [Agreed V001 Word]({{ '/assets/contribution-templates/NFDI4Health_Module_Authoring_Template_V001.docx' | relative_url }}) | [Agreed V001 Markdown]({{ '/assets/contribution-templates/NFDI4Health_Module_Authoring_Template_V001.md' | relative_url }}) | [FAIR module V001 mapping (Word)]({{ '/assets/contribution-examples/EXAMPLE_FAIR_Module_Agreed_V001_SOURCE_FAITHFUL.docx' | relative_url }}) / [Markdown]({{ '/assets/contribution-examples/EXAMPLE_FAIR_Module_Agreed_V001_SOURCE_FAITHFUL.md' | relative_url }}) |
| **Research data life-cycle guidance** | [Word]({{ '/assets/contribution-templates/NFDI4Health_Lifecycle_Guidance_Template.docx' | relative_url }}) | [Markdown]({{ '/assets/contribution-templates/nfdi4health-lifecycle-template.md' | relative_url }}) | [Sharing Word source]({{ '/assets/contribution-examples/EXACT_Lifecycle_Sharing.docx' | relative_url }}) and [original Markdown](https://github.com/nfdi4health/nfdi4health-knowledge-base/blob/3f4025bc5171f13c9d07d789957d3d5d530f17d8/pages/data_life_cycle/sharing.md) |

**About the examples:** The Health Study Hub and Sharing files reproduce existing source pages, not a simplified adaptation. The FAIR module is a **source-faithful mapping of an in-preparation catalogue entry**, not a finished module; missing parts are explicitly labelled. The published [Module Catalogue]({{ '/modules' | relative_url }}) is itself a catalogue rather than a complete course.

## 2. Submit your contribution

### Route A — Word or Markdown to the coordination team

1. Select the relevant template and complete the sections you can already provide.
2. Identify the subject expert / proposed content steward, institutional affiliation, applicable service, and references. Indicate whether attribution details may be published.
3. Send the editable file, image/source credits, and any supporting links using the **designated NFDI4Health Knowledge Base coordination channel**. **[Coordination team: insert an approved submission address or internal channel before publishing this page.]**
4. The coordination team acknowledges and logs the submission, asks for any missing essentials, arranges subject and editorial review, and converts the approved version into a GitHub pull request.
5. Review any substantive changes requested by the reviewers. An authorised maintainer publishes after checks are complete.

See [submitting through the coordination team]({{ '/submit_to_coordination' | relative_url }}) for the full procedure.

### Route B — GitHub

1. Read the [content standards]({{ '/content_standards' | relative_url }}) and choose a template.
2. Open an [Issue](https://github.com/nfdi4health/nfdi4health-knowledge-base/issues/new/choose) for a new topic or significant change (small corrections may proceed directly).
3. Edit the appropriate Markdown file in a new branch or fork. **Do not edit `main` directly.**
4. Open a [pull request](https://github.com/nfdi4health/nfdi4health-knowledge-base/pulls) and complete its review checklist.
5. Address comments. A coordinator assigns reviewers; an authorised maintainer merges only after the applicable checks and reviews are complete.

See the [GitHub step-by-step guide]({{ '/github_way' | relative_url }}).

## 3. Responsibility and recognition

- **Content steward / service owner:** checks the scientific and service-specific facts, URLs, scope, access conditions, and changes when the service evolves.
- **Volunteer subject reviewer:** checks accuracy and whether claims are supported by authoritative sources; is distinct from the author where practicable.
- **Volunteer editorial reviewer:** checks readability, structure, citations, copyright, FAIR relevance and accessibility.
- **Knowledge Base coordinator:** manages intake, reviewer assignment, decisions, consistency and the publication queue.
- **Technical maintainer:** checks build status and safely publishes through the repository workflow.

A page may acknowledge its contributors using the existing `contributors` metadata and `_data/CONTRIBUTORS.yaml`, subject to consent. Content responsibility is **not** exclusive copyright ownership or automatic permission to merge code.

## 4. Quality, privacy and licensing

Use clear, actionable language and link to current NFDI4Health service documentation. Distinguish operational from planned features and separate public metadata discovery from controlled access to sensitive data. Do **not** submit identifiable patient information, restricted datasets, credentials, confidential internal documents or unlicensed third-party images to a public repository or editorial package.

Check the [content standards]({{ '/content_standards' | relative_url }}) and [copyright guidelines]({{ '/copyright' | relative_url }}). Existing repository licence statements should be reviewed by the coordination team before any new licensing policy is formally adopted.

## 5. Become a volunteer editor or reviewer

We welcome volunteers with expertise in biomedical RDM, NFDI4Health services, training design, language editing, accessibility and GitHub/Jekyll. Reviewers do **not** need publication permissions: subject review and editorial suggestions can be coordinated through Word comments or GitHub pull-request reviews.

See [editorial roles and review process]({{ '/editorial_workflow' | relative_url }}). The coordination team will confirm responsibilities, availability and access before assigning work.

**Questions or corrections?** Use an [Issue](https://github.com/nfdi4health/nfdi4health-knowledge-base/issues/new/choose) or the approved coordination channel.

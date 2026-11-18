---
title: Submit a service or resource
description: Propose or update NFDI4Health service information and suggest relevant external resources for the Knowledge Base.
permalink: /tool_resource_update
sidebar: contribute
search_exclude: false
contributors:
  - Atinkut A. Zeleke
---

The NFDI4Health Knowledge Base brings together practical guidance on services, research data management and learning resources for clinical, epidemiological and public health research. **Service owners, data stewards and subject experts** can help keep this information accurate and useful.

This guide explains how to propose a **new NFDI4Health service page**, **update an existing page**, or **recommend an external tool or resource**. A recommendation does not automatically become an official NFDI4Health service or a published Knowledge Base entry.

## 1. Choose the type of contribution

| Contribution | When to use it | What to prepare |
| --- | --- | --- |
| **New NFDI4Health service page** | A service is confirmed as part of the NFDI4Health service portfolio but is not yet described in the Knowledge Base. | Official service information, a responsible service owner or content steward, and the appropriate service template. |
| **Update an existing service page** | A service's features, access conditions, documentation, support contact or status have changed; or an existing description needs correction. | The existing Knowledge Base page URL, the proposed changes and sources that verify them. |
| **Suggest an external tool or resource** | A third-party tool, standard, repository, publication or training resource could help users carry out a relevant biomedical RDM task. | Its official URL, purpose, relevance, maintainer, supporting evidence and any usage or licensing constraints. Clearly identify it as external. |

For a **new self-paced learning module** or **research data life-cycle guidance**, use the corresponding template on the [main contribution page]({{ '/how_to_contribute' | relative_url }}) instead. An external resource may be linked from an existing page without requiring a separate service page.

## 2. Check the existing content first

1. Browse the [NFDI4Health Services overview]({{ '/services' | relative_url }}) and related [research data life-cycle guidance]({{ '/data_life_cycle' | relative_url }}).
2. Check whether the service or resource is already described or linked. If so, propose an **update** rather than a duplicate page.
3. For an NFDI4Health service, confirm the **official service name, URL, current status and responsible team** against an authoritative source, such as the [NFDI4Health service overview](https://www.nfdi4health.de/en/service.html) and the service's own documentation.
4. If a service is planned, in a pilot phase, restricted to particular users or not yet available, state that clearly. **Do not describe planned capabilities as operational features.**
5. Confirm with the relevant service owner or content steward who can check the facts and help maintain the entry.

If you are uncertain whether a proposal belongs in the Knowledge Base, [contact the coordination team]({{ '/submit_to_coordination' | relative_url }}) before preparing a complete page.

## 3. Prepare the information

For a **new NFDI4Health service page**, use the existing [Word service template]({{ '/assets/contribution-templates/NFDI4Health_Service_Content_Template.docx' | relative_url }}) or [Markdown service template]({{ '/assets/contribution-templates/nfdi4health-service-template.md' | relative_url }}). Both are available through the [main contribution page]({{ '/how_to_contribute' | relative_url }}).

Provide the following information where applicable:

| Information | What to include |
| --- | --- |
| **Service or resource identity** | Official name, verified URL, short description and responsible organisation or team. |
| **Audience and purpose** | Who should use it, the biomedical RDM task it supports and a realistic example without identifiable participant data. |
| **Current status and access** | Whether the service is operational, a pilot or planned (if confirmed); eligibility, access restrictions, necessary approvals and support route. |
| **Functions and limitations** | What users can do, what they cannot do, known constraints and any dependencies. |
| **FAIR and life-cycle relevance** | Explain how it supports relevant FAIR principles and stages such as planning, collection, processing, analysis, preservation, sharing or reuse. |
| **Data protection context** | Distinguish publicly discoverable metadata from access to controlled or sensitive individual-level health data. Avoid unsupported legal or compliance claims. |
| **Evidence and attribution** | Official documentation, specifications, relevant references, dates or versions, and permissions or licences for any reused material. |
| **Content responsibility** | Proposed content steward or service owner, their affiliation, and any preferred publicly shareable contact or correction route. |

For an **existing page**, provide its URL, identify the sections to change and explain the reason for the update. For an **external resource**, a concise description with verified links may be sufficient; the coordination team can decide with subject reviewers whether it belongs on an existing guidance page or merits further treatment.

**Important:** Do not upload participant-level health data, identifying patient examples, credentials, confidential service documents or restricted attachments to GitHub or public submission channels. Include images or screenshots only when you have the necessary reuse rights and have removed sensitive information.

## 4. Submit the contribution

You can contribute without a GitHub account. Choose either route:

### Route A — Submit Word or Markdown to the coordination team

1. Fill in the relevant service template, or prepare a concise update or external-resource suggestion.
2. Include authoritative links and the person or team who can verify the information.
3. Send the material to the coordination team using the [Word or Markdown submission instructions]({{ '/submit_to_coordination' | relative_url }}).
4. Respond to any questions or proposed revisions during the review.

The coordination team can prepare the technical website update, while the service owner or named content steward remains responsible for verifying specialist information. **Submission is not automatic approval or publication.**

### Route B — Contribute through GitHub

1. For a substantial new page, first open a [GitHub Issue](https://github.com/nfdi4health/nfdi4health-knowledge-base/issues/new/choose) to agree on scope, ownership and location.
2. Edit the appropriate Markdown page on a **new branch or fork**, using the service template when creating a new service page. Do **not** commit directly to `main`.
3. Open a [pull request](https://github.com/nfdi4health/nfdi4health-knowledge-base/pulls) describing the change, the evidence and the proposed content steward.
4. Address reviewer comments. An authorised repository maintainer handles the final merge after the applicable checks.

See [Contribute using GitHub]({{ '/github_way' | relative_url }}) for detailed instructions.

## 5. Review, publication and maintenance

The proposed Knowledge Base editorial workflow involves these checks:

1. **Scope and ownership:** Is the contribution relevant to NFDI4Health users, and is its official or external status clearly identified?
2. **Subject review:** Are the functions, service status, access conditions, biomedical examples and references accurate?
3. **Editorial review:** Is the wording understandable, accessible, properly attributed and consistent with the [content standards]({{ '/content_standards' | relative_url }})?
4. **Technical checks:** Do the links, Markdown formatting and page metadata work in the website preview?
5. **Publication:** After relevant reviews and approval, an authorised maintainer merges and checks the public page.

These steps describe a **proposed operating model**, subject to confirmation by the NFDI4Health coordination team; they should not be interpreted as a formally approved consortium policy. See [editorial roles and review]({{ '/editorial_workflow' | relative_url }}).

Service information needs updating as services evolve. Content stewards are encouraged to report changed access requirements, URLs, features or service status, and to respond to correction requests. No fixed review interval is imposed by this page.

## Submission checklist

- [ ] I checked for an existing service page or resource reference.
- [ ] I clearly identified the contribution as an NFDI4Health service, an update, or an **external** resource.
- [ ] I verified the official URL, current status, scope and available features.
- [ ] I identified a suitable subject expert or proposed content steward for factual checks.
- [ ] I explained the intended audience, practical biomedical RDM use and relevant FAIR or life-cycle context.
- [ ] I included authoritative sources and required attribution or licence information.
- [ ] I excluded confidential material and identifiable health data.
- [ ] I selected a submission route and provided the existing page URL if proposing an update.

## Related guidance

- [Start contributing]({{ '/how_to_contribute' | relative_url }})
- [Submit Word or Markdown]({{ '/submit_to_coordination' | relative_url }})
- [Contribute using GitHub]({{ '/github_way' | relative_url }})
- [Content standards]({{ '/content_standards' | relative_url }})
- [Copyright and attribution]({{ '/copyright' | relative_url }})

## Source and attribution

This page replaces the inherited RDMkit **“Add new tool or resource”** instructions with an NFDI4Health-specific contribution process. The original RDMkit guidance is available at [RDMkit – Add new tool or resource](https://rdmkit.elixir-europe.org/tool_resource_update) and is credited to its original contributors under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The workflow described above is adapted for the NFDI4Health Knowledge Base; it does **not** imply that RDMkit registry automation is implemented for NFDI4Health.

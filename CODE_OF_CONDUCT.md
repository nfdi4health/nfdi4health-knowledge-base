---
title: Code of Conduct
description: Proposed community, research-integrity, privacy and publication principles for contributors to the NFDI4Health Knowledge Base.
permalink: /CODE_OF_CONDUCT
redirect_from:
  - /code_of_conduct
  - /code_of_conduct/
sidebar: contribute
search_exclude: false
toc: true
contributors:
  - Atinkut A. Zeleke
---

> **Status — proposed Knowledge Base guidance:** This document sets out expectations for people contributing to the NFDI4Health Knowledge Base. It is **not yet an approved, consortium-wide NFDI4Health Code of Conduct** or an independent disciplinary procedure. The Knowledge Base coordination team and the relevant NFDI4Health governance bodies must review it before formal adoption. Applicable laws, institutional policies, platform rules and formally approved NFDI4Health policies continue to apply.

The NFDI4Health Knowledge Base is a shared resource for researchers, data stewards, service owners, trainers and infrastructure specialists working with clinical, epidemiological and public health research data. We aim to make collaboration **respectful, inclusive, scientifically reliable and responsible with sensitive information**.

This guidance is intended for Knowledge Base contributions and interactions, including GitHub issues and pull requests, editorial feedback, learning resources and related project discussions. It does not replace a host institution's procedures or an event organiser's Code of Conduct.

## 1. Respectful and inclusive collaboration

Contributors should:

- **Treat others with dignity.** Respect different professional backgrounds, perspectives, languages, experiences and levels of technical confidence.
- **Use constructive language.** Discuss the evidence and content rather than attacking the person who submitted it. Explain suggested changes and invite clarification.
- **Make participation accessible.** Use understandable language, avoid unnecessary jargon and welcome contributors who are new to GitHub, Markdown or biomedical research data management.
- **Respect boundaries and privacy.** Do not share private conversations, photographs, contact details or identifying information without an appropriate basis and permission.
- **Respond professionally to review.** Be open to corrections, acknowledge mistakes and disclose conflicts of interest when they may affect a review.

Harassment, discrimination, threats, intimidation, unwanted sexual attention, deliberate exclusion, repeated personal attacks, doxxing and retaliation for raising concerns are unacceptable in Knowledge Base collaboration.

## 2. Research integrity and reliable information

Knowledge Base content should reflect recognised standards of good research practice, including the [DFG Guidelines for Safeguarding Good Research Practice](https://www.dfg.de/en/basics-topics/basics-and-principles-of-funding/good-research-practice/code-of-conduct). Contributors should:

- Make factual claims verifiable through current, authoritative sources; distinguish evidence from opinion, illustration or work in progress.
- Describe NFDI4Health services accurately, including their **verified status, access conditions, limitations and intended users**. Do not present a pilot or planned feature as operational.
- State the relevance to biomedical research, FAIR principles and the relevant [research data life-cycle stages]({{ '/data_life_cycle' | relative_url }}) where appropriate.
- Credit original authors and sources; avoid plagiarism, fabricated references, manipulated examples or misrepresentation of others' contributions.
- Correct errors transparently. For a substantive update, explain what changed and retain the repository's normal version history.

The [content standards]({{ '/content_standards' | relative_url }}) provide the working editorial checklist. Institutional research-integrity rules remain authoritative for the researchers and institutions to which they apply.

## 3. Privacy, confidentiality and responsible health-data use

Health information can reveal highly sensitive facts about individuals. Contributors must respect the [EU General Data Protection Regulation (GDPR)](https://eur-lex.europa.eu/eli/reg/2016/679), applicable national law, contractual or ethical restrictions, and their institution's approved procedures.

For material proposed for this **public Knowledge Base**:

- **Do not upload identifiable participant- or patient-level data**, clinical records, actual case histories, consent records, credentials, unpublished confidential documents or restricted datasets.
- Use synthetic or fully fictional biomedical examples. Remove identifying details from screenshots, figures, logs, metadata and file properties.
- Do not assume that pseudonymisation alone permits public disclosure or that public metadata implies permission to access the underlying health data.
- Explain restrictions honestly. Access to sensitive health data may require a separate application, review or authorisation by the responsible data holder.
- If a contribution contains information that may be confidential or identifying, **stop public submission** and seek guidance through an appropriate non-public institutional or project channel.

**Publication Policy distinction:** The [NFDI4Health Publication Policy](https://www.nfdi4health.de/en/service/health-study-hub/publication-policy-and-metadata-schema.html) governs publication of study or registry descriptions and study documents through the **Health Study Hub**. It excludes participant-level individual data from publication there and requires quality checks of submitted metadata and study documents. These principles inform our Knowledge Base safeguards, but the Health Study Hub's submission, DOI and metadata procedures must **not** be described as mandatory steps for editing a Knowledge Base page.

## 4. Attribution, copyright and responsible publication

Contributors should submit material they created or are authorised to share and should make reuse conditions clear:

- Cite sources, standards, software and third-party materials; include version information or a DOI when available.
- Obtain the necessary rights before reusing photographs, screenshots, diagrams, tables or substantial passages. Provide creator, source, licence and required attribution.
- Do not assume that publicly accessible material is openly licensed.
- Check that links work and that important statements are still current before proposing publication.
- Use the appropriate [service, module or life-cycle template]({{ '/how_to_contribute' | relative_url }}) and respond to substantive editorial comments before a page is released.

For **study documents submitted to the Health Study Hub**, the NFDI4Health Publication Policy (version V2_1, sections 2.4–2.7) describes licensing, identifiers, recommended file formats and publication review. It favours clear, reusable licences and properly marked study documents. **These are Health Study Hub publication requirements and recommendations, not an automatic licence assignment to Knowledge Base submissions.**

The Knowledge Base repository currently contains **inherited RDMkit licence wording** describing CC BY 4.0 for documentation and MIT for software, subject to exceptions. The coordination team must confirm rights, attribution and the definitive Knowledge Base licensing statement before announcing a new overarching policy. See [Copyright and attribution]({{ '/copyright' | relative_url }}).

## 5. NFDI4Health identity, corporate design and accessibility

Contributions should be visually consistent with the NFDI4Health Knowledge Base and usable by a diverse audience:

- Follow the existing [Knowledge Base style guide]({{ '/style_guide' | relative_url }}) and page templates. The current site design system uses **NFDI4Health blue `#00578c`**, darker blue `#003f66`, accent `#c23669`, **Exo 2** for headings and **Open Sans** for body text. These are the **current Knowledge Base implementation choices**, not a claim that a separate consortium-wide corporate design manual has been formally verified.
- Reuse the site's existing layouts and styles instead of introducing unreviewed colours, typography, inline styling or competing logos.
- Use NFDI4Health names, logos and other brand assets in the appropriate context. Do not imply official endorsement of an external tool, service or resource without verification.
- Make headings meaningful, links descriptive, tables understandable and images accessible through appropriate alternative text. Do not communicate essential information by colour alone.
- Aim for the accessibility practices described in the [W3C Web Content Accessibility Guidelines (WCAG) 2.2](https://www.w3.org/TR/WCAG22/) while following any applicable legal and institutional accessibility requirements.

## 6. Collaborative review and publication decisions

The [contribution routes]({{ '/how_to_contribute' | relative_url }}) allow submissions by Word, Markdown or GitHub. Good collaboration means keeping suggestions traceable and accepting that publication requires review:

1. Check whether a topic or service page already exists and propose an update rather than a duplicate.
2. Identify a suitable service owner, subject expert or proposed content steward who can verify specialist information.
3. For GitHub contributions, use a separate branch or fork and open a pull request; do **not** commit directly to `main`.
4. Address factual, privacy, copyright, accessibility and presentation issues raised during review.
5. Leave final publication to a maintainer with the appropriate repository permissions after the applicable checks.

The division between coordinator, subject reviewer, editorial reviewer and technical maintainer is a **proposed Knowledge Base operating model** that still requires confirmation. Submitting a page or reviewing it does not itself grant publishing authority. See [Editorial review and volunteer team]({{ '/editorial_workflow' | relative_url }}).

## 7. Raising concerns safely

If you notice a problem, choose a channel appropriate to its sensitivity:

| Concern | Appropriate first step |
| --- | --- |
| **Broken link, factual error, accessibility issue or unclear attribution** | Raise a [GitHub Issue](https://github.com/nfdi4health/nfdi4health-knowledge-base/issues/new/choose) **only if** the description can safely be public, or contact the Knowledge Base coordination team through the [contribution channel]({{ '/submit_to_coordination' | relative_url }}). |
| **Suspected disclosure of health data, credentials or confidential material** | Do **not** reproduce the sensitive information in a public issue. Contact the responsible service owner or institutional data protection/security contact through a non-public channel. |
| **Harassment, discrimination, threats or research misconduct** | Use the relevant **institutional confidential reporting, ombudsperson or safeguarding channel**, or request privately from the responsible project or event organiser the appropriate contact. Do not post personal allegations or identifying details publicly. |
| **Immediate threat to personal safety** | Contact the appropriate local emergency services. |

There is **no verified NFDI4Health Knowledge Base-specific conduct response committee or confidential reporting mailbox** established by this draft. Such contacts, decision powers, confidentiality arrangements and any escalation or appeal process must be confirmed by the responsible governance body before they are published as official procedures. In particular, the former **RDMkit/ELIXIR reporting contacts and enforcement team do not represent NFDI4Health**.

## 8. Handling a concern

Pending formal adoption of a Knowledge Base-specific procedure, issues should be handled using applicable institutional processes, existing platform rules and authorised project responsibilities. Where appropriate, maintainers may ask for a correction, hold a contribution for review or remove unsafe material within their existing permissions. They must not claim disciplinary powers granted by the former RDMkit Code of Conduct.

People handling reports should avoid unnecessary disclosure, minimise the personal information collected, recognise possible conflicts of interest, and direct serious concerns to the appropriate authorised body. This page does not promise particular sanctions, confidentiality outcomes or resolution deadlines.

## Quick checklist for contributors

- [ ] I communicate respectfully and make room for different perspectives and experience levels.
- [ ] My claims are accurate, referenced and clear about service status or limitations.
- [ ] My contribution contains no identifiable health data, credentials or confidential attachments.
- [ ] I have permission to reuse text, images and other third-party material and have provided attribution.
- [ ] I have followed the Knowledge Base templates, branding and accessibility guidance.
- [ ] I have identified an appropriate reviewer or content steward and used the agreed contribution route.
- [ ] I will raise sensitive or personal concerns privately, not in a public GitHub issue.

## Sources, scope and acknowledgements

- **NFDI4Health Publication Policy**, version V2_1, released 21 February 2025; DOI **10.4126/FRL01-006484167**, particularly sections 2.1, 2.4, 2.6 and 2.7. The supplied version was used in preparing this page; see the [official NFDI4Health publication policy overview](https://www.nfdi4health.de/en/service/health-study-hub/publication-policy-and-metadata-schema.html). Its direct scope is **Health Study Hub resource publication**.
- [DFG Guidelines for Safeguarding Good Research Practice](https://www.dfg.de/en/basics-topics/basics-and-principles-of-funding/good-research-practice/code-of-conduct) — research integrity framework; implementation and enforcement depend on the relevant institutions' rules.
- [Regulation (EU) 2016/679 (GDPR)](https://eur-lex.europa.eu/eli/reg/2016/679) — legal framework for personal-data processing, including health-data safeguards.
- [W3C Web Content Accessibility Guidelines 2.2](https://www.w3.org/TR/WCAG22/) — technical guidance for accessible web content.
- [Knowledge Base content standards]({{ '/content_standards' | relative_url }}), [style guide]({{ '/style_guide' | relative_url }}) and [copyright guidance]({{ '/copyright' | relative_url }}) — current project working guidance; where indicated, still subject to approval.

**Acknowledgement of the inherited source:** The previous repository page was the [RDMkit Code of Conduct](https://github.com/elixir-europe/rdmkit/blob/master/CODE_OF_CONDUCT.md), derived from community codes including **The Turing Way**, **The Carpentries**, the **Alan Turing Institute Data Study Group** and **Citizen Lab**, with attribution under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). This replacement is written for the NFDI4Health Knowledge Base. None of the former RDMkit contact persons, enforcement roles or incident procedures are carried over as NFDI4Health authorities.

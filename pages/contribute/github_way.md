---
title: Contribute using GitHub
permalink: /github_way
sidebar: contribute
---

# Contribute using GitHub

Use this route if you are comfortable editing Markdown in a browser or working with Git locally. GitHub lets reviewers discuss a proposed change before it becomes public on the Knowledge Base website.

## Before editing

- Create or sign in to a [GitHub account](https://github.com/signup).
- Read the [content standards]({{ '/content_standards' | relative_url }}) and [copyright guidelines]({{ '/copyright' | relative_url }}).
- Find the existing page or use the correct [content template]({{ '/how_to_contribute' | relative_url }}). Modules must use the data-steward-agreed **V001 sections 0–15**.
- For a substantial new page, look for an existing [Issue](https://github.com/nfdi4health/nfdi4health-knowledge-base/issues) and open one if needed, so the coordinator and service owner can agree on scope and location.

## Browser-based contribution: step by step

1. Open the [NFDI4Health repository](https://github.com/nfdi4health/nfdi4health-knowledge-base).
2. Navigate to the Markdown file you want to update; the repository currently has examples under `pages/tool_assembly/`, `pages/Modules.md` and `pages/data_life_cycle/`.
3. Choose **Edit this file** (pencil symbol). If GitHub cannot edit the repository in your account, it may offer to fork it.
4. Make your changes in Markdown. Preserve the existing YAML front matter, page permalink and working site links unless a change has been agreed.
5. Commit the change to a **new branch or fork**, not directly to `main`.
6. Open a **pull request** with your contribution branch as the head and `nfdi4health/nfdi4health-knowledge-base:main` as the base. Explain the problem, proposed change, source links, service owner and any licences/permissions. If the content is still being developed, mark the pull request as a draft.
7. Complete the pull-request checklist, link the relevant Issue (for example, `Closes #123` when appropriate), and identify the responsible NFDI4Health data steward or service owner. The coordination team assigns the applicable reviewers.
8. Respond to review comments. Push or commit revisions to the same pull-request branch so the discussion and history remain together.
9. Wait for the applicable subject/editorial review and site checks. **An authorised maintainer**, not the contributor by default, merges the approved change.
10. Once merged, check the resulting [public Knowledge Base](https://nfdi4health.github.io/nfdi4health-knowledge-base/) page and report incorrect rendering or broken links.

GitHub interface wording may vary. [Official GitHub pull-request instructions](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## What to include in your pull request

A reviewer should be able to understand the change without guessing. Include:

- **Content type:** Service page / Self-paced module / Research data life-cycle page / Correction.
- **Change summary:** What was added, corrected or removed and why.
- **Responsible subject expert:** Name or team responsible for verifying the facts and maintaining updates (confirm permission before publishing personal contact details).
- **Evidence:** Links to official NFDI4Health service information, publications, policy documents and other references.
- **Checks:** Relevant licences and image credits; no confidential or identifiable personal health data; internal links checked; page metadata preserved.
- **Review status:** Any unresolved issues, planned service features or parts that are still drafts.

New self-paced modules should use the agreed **NFDI4Health Training Module Authoring Template V001 (sections 0–15)**. The template allows partial contributions; mark incomplete parts rather than presenting them as published guidance.

## Working locally (optional)

Fork or clone the repository, create a topic branch from the current `main`, change the correct Markdown files, commit with a descriptive message, push your branch and open a PR. Keep changes focused so reviewers can understand them. Ask a technical maintainer before changing theme files, deployment workflows, metadata schemas or navigation.

## Pages and metadata

- **Service pages:** existing source files are under `pages/tool_assembly/`. Use the service template when proposing new service documentation.
- **Training modules:** `pages/Modules.md` is currently a **catalogue**, not a complete training module. Agree on the file location and URL for a new module before creating it.
- **Life-cycle pages:** update the relevant file under `pages/data_life_cycle/` rather than creating a duplicate.
- **Contributor credit:** the site can display names recorded in a page's `contributors` front matter and `_data/CONTRIBUTORS.yaml`; ask for consent before adding personal identifiers.

## Review, approval and publication

The coordination team arranges subject-matter and editorial review. For significant new content, these functions should be carried out separately from the author where practicable. Volunteer reviewers can comment and recommend acceptance or revisions; **being a reviewer does not automatically grant GitHub merge or publishing permissions**.

An authorised maintainer checks the pull request, metadata and site build before merging. Publication occurs only after merge and a successful GitHub Pages deployment. The contributor or content steward should check the live page for formatting, factual accuracy and broken links. Future changes use the same review workflow.

## What reviewers will check

Source-supported claims, service status, health-data privacy, correct internal links, copyright/licences, accessibility, page metadata, language and whether the website build passes. Reviewers may request changes; this is part of collaborative quality assurance, not a rejection of the contributor.

**Alternative:** If you do not want to use GitHub, [submit Word or Markdown to the coordination team]({{ '/submit_to_coordination' | relative_url }}).

---
title: Page metadata
description: Practical YAML front matter guidance for contributors to the NFDI4Health Knowledge Base.
permalink: /page_metadata
sidebar: contribute
search_exclude: false
contributors: [Atinkut A. Zeleke]
---

Page metadata tells the NFDI4Health Knowledge Base how to display, identify and connect a page. It is written as **YAML front matter** at the very beginning of a Markdown file. The Knowledge Base uses Jekyll and the ELIXIR Toolkit Theme to turn those files into web pages.

This guide describes the metadata used in the **current NFDI4Health Knowledge Base prototype** and the recommended approach for new contributions. Some existing pages retain metadata inherited from RDMkit; those fields are identified separately below because they are not automatically part of the proposed NFDI4Health authoring standard.

**Page metadata is not biomedical study metadata.** The fields described here configure Knowledge Base web pages. They do not replace NFDI4Health study descriptions, research data documentation or domain-specific metadata standards.

## What is YAML front matter?

Front matter appears at the top of a Markdown file, between two lines containing three hyphens (`---`). Each field has a name and value.

For example:

```yaml
---
title: Page metadata
description: Practical YAML front matter guidance for NFDI4Health contributors.
permalink: /page_metadata
sidebar: contribute
contributors: [Atinkut A. Zeleke]
---
```

The website theme uses the `title` field to display the main page heading. **Do not repeat this title as a Markdown `#` heading in the body**, as doing so can create duplicate titles.

When editing an existing page, retain its front matter unless a change has been agreed and its effects on navigation, links and rendering have been checked.

## Metadata fields used in the Knowledge Base

The following fields appear in the current repository or are supported by its Jekyll configuration. They do not all need to be present on every page.

| Field | Purpose | Guidance |
| --- | --- | --- |
| `title` | Main page title shown by the theme. | Required for published content; use a clear, specific title. |
| `description` | Short description of a page. | Recommended for newly authored NFDI4Health guidance. Use one informative sentence. |
| `summary` | Brief summary used by some existing service pages. | Preserve where already used; do not change to `description` without checking the page and any listings that use it. |
| `permalink` | Public URL path of the page. | Recommended for stable pages; begin with `/` and avoid unnecessary URL changes. |
| `sidebar` | Sidebar navigation group. | Use `contribute` for contributor guidance and `data_management` where appropriate for the main Knowledge Base. |
| `contributors` | People credited for creating or adapting a page. | Use registered names from `_data/CONTRIBUTORS.yaml`. |
| `search_exclude` | Controls inclusion in the **site's own search**. | Set `false` for normal public guidance and `true` for pages that should not appear in site search. |
| `toc` | Controls the on-page table of contents when supported by the theme. | Use `false` only when the contents list is inappropriate; otherwise rely on the page defaults. |
| `redirect_from` | Additional old URL paths that redirect to the page. | Use for deliberate URL migrations, after technical review. |
| `sitemap` | Controls sitemap inclusion where the relevant plugin supports it. | Usually leave unchanged; do not confuse it with internal site search. |
| `no_robots` | Controls search-engine indexing where supported by the theme. | The prototype currently sets `no_robots: true` in `_config.yml`; changing indexing policy requires project approval. |

The repository's `_config.yml` also defines default values, including the page layout, a default sidebar and a fallback permalink. Consequently, an omitted field does not always mean that a feature is disabled. Contributors should avoid copying unnecessary configuration into every page.

### Contributor names and recognition

The current contributor registry is `_data/CONTRIBUTORS.yaml`. The spelling of each name in the page's `contributors` list must match a key in that file for the theme to associate the person's profile with the page.

For example:

```yaml
contributors: [Atinkut A. Zeleke]
```

Only list people whose contribution has been established. A contributor credit is **not** the same as publication approval or responsibility for ongoing scientific maintenance.

The separate `_data/nfdi4health_data_stewards.yml` file supports the Knowledge Base's data steward information; it is **not interchangeable** with the contributor registry.

For review responsibilities, see the [editorial review guidance]({{ '/editorial_workflow' | relative_url }}).

## Metadata examples from current NFDI4Health content

The examples below reflect metadata patterns used in the present prototype. They are guides to page configuration, not replacements for the content templates or review requirements.

### Contributor guidance page

The contributor section uses the `contribute` sidebar and a stable permalink:

```yaml
---
title: Page metadata
description: Practical YAML front matter guidance for NFDI4Health contributors.
permalink: /page_metadata
sidebar: contribute
search_exclude: false
contributors: [Atinkut A. Zeleke]
---
```

### Biomedical research data life-cycle overview

The main lifecycle overview uses the `data_management` sidebar and identifies its contributor. The example below shows the relevant fields; the existing page also has redirects that must be preserved when editing it.

```yaml
---
title: Research Data Life Cycle
description: Guidance through the biomedical research data life cycle and its NFDI4Health connections.
permalink: /data_life_cycle
sidebar: data_management
search_exclude: false
contributors: [Atinkut A. Zeleke]
---
```

For lifecycle stage pages already carrying `page_id` or `related_pages` fields, keep those existing fields until the corresponding links and templates have been reviewed. See the [Research Data Life Cycle]({{ '/data_life_cycle' | relative_url }}) overview.

### NFDI4Health service page

Existing service descriptions, such as Health Study Hub, use `summary` and an explicit service URL. Some also retain inherited theme fields such as `type: Tool_assembly`.

```yaml
---
title: Health Study Hub
summary: Discover, publish, and reuse clinical, epidemiological, and public health study metadata in a FAIR-aligned environment.
permalink: /services/health-study-hub
---
```

This excerpt demonstrates **currently used fields**, not an instruction to remove other fields from the existing page. Service-specific information—including verified URLs, access arrangements, FAIR relevance, lifecycle connections, limitations, references and a responsible content steward—belongs in the **page body and approved service template**, not in arbitrary new YAML keys.

See the [NFDI4Health Services]({{ '/services' | relative_url }}) overview.

### Training module catalogue

The current module catalogue uses:

```yaml
---
title: Training Module Catalogue
description: NFDI4Health self-paced learning modules, consortium training materials and selected external training resources.
permalink: /modules
sidebar: data_management
toc: true
search_exclude: false
---
```

**A catalogue entry is not a completed self-paced module.** Individual modules must follow the agreed NFDI4Health Module Authoring Template V001, with its sections 0–15 and the necessary instructional review. Do not invent module-specific YAML keys as a substitute for those content sections.

See the [Module Catalogue]({{ '/modules' | relative_url }}) and [contribution standards]({{ '/content_standards' | relative_url }}).

## URLs and internal links

The `permalink` controls the page's public address. Changing it can break existing links, QR codes and bookmarks. Preserve established URLs whenever possible.

To link between Knowledge Base pages, use the Jekyll `relative_url` filter so links work in both the Netlify branch preview and the GitHub Pages publication.

{% raw %}
```liquid
[Research Data Life Cycle]({{ '/data_life_cycle' | relative_url }})
```
{% endraw %}

Do not place the GitHub Pages base path directly into each internal Markdown link. If a published permalink must change, discuss a redirect and verify both the previous and new URLs.

## Inherited RDMkit metadata: review before reuse

The NFDI4Health repository was adapted from RDMkit. Some older pages and templates still contain its original metadata conventions.

| Inherited field or convention | Current guidance |
| --- | --- |
| `page_id` and `related_pages` | Still occur in some lifecycle and other inherited pages. Do not add RDMkit's `Your_tasks`, `Your_domain` or `Tool_assembly` relationships to new pages without a confirmed mapping to the NFDI4Health navigation. Preserve existing working links during migration. |
| `training` entries pointing to TeSS or other RDMkit resources | Do not assume that these entries automatically populate NFDI4Health training modules. Link to verified training resources and use the agreed module workflow. |
| `dsw`, `faircookbook` and `fairsharing` | Some inherited metadata reflects RDMkit-specific integrations. Their automated updates or availability must not be assumed for NFDI4Health. |
| `ref_to_main_resources` and `national_resources` | Specific to older RDMkit resource-listing workflows; not part of the standard metadata for NFDI4Health service pages. |
| `type`, `type_img` and `layout` | Theme and template fields that may be set automatically in `_config.yml` or retained for existing page layouts. Do not remove them from an established page without checking the rendering. |
| `editors`, `coordinators`, `affiliations` and other legacy credit fields | Do not treat inherited lists as an approved NFDI4Health editorial or governance model. Use the confirmed contributor registry and follow the project's review process. |

**Important:** This table is a migration warning, not a request to delete fields from existing pages. Some legacy fields remain necessary until pages, navigation and theme features have been systematically reviewed.

New NFDI4Health content should prioritise stable URLs, accurate contributor recognition, clear content structure, accessible links and verified references.

## YAML editing and validation checklist

Before submitting a Markdown page or pull request:

1. **Check the front matter.** Confirm that the opening and closing `---` lines exist and that YAML uses consistent indentation.
2. **Check the page title.** Keep one `title` field and do not add another Markdown `#` heading in the body.
3. **Preserve URLs.** Confirm that `permalink` and any `redirect_from` entries are intentional and do not conflict with another page.
4. **Check navigation.** Use the correct sidebar and verify the page appears in the expected section.
5. **Check attribution.** Use registered contributor names; retain required credit and licence details for adapted material.
6. **Check links and content.** Use `relative_url` for internal links; remove confidential or identifiable health information.
7. **Check legacy dependencies.** Do not remove RDMkit fields that may still support an inherited page without reviewing their effect.
8. **Preview the result.** Confirm the page builds and renders on the branch preview, including the main title, table of contents, links and contributor display.
9. **Complete review.** Obtain applicable subject and editorial checks before an authorised maintainer publishes the page.

For writing and Markdown syntax, see the [Markdown cheat sheet]({{ '/markdown_cheat_sheet' | relative_url }}) and [NFDI4Health contribution standards]({{ '/content_standards' | relative_url }}).

## Related contribution guidance

- [Start contributing]({{ '/how_to_contribute' | relative_url }})
- [Markdown cheat sheet]({{ '/markdown_cheat_sheet' | relative_url }})
- [Content standards]({{ '/content_standards' | relative_url }})
- [Copyright and attribution]({{ '/copyright' | relative_url }})
- [Editorial review and volunteer team]({{ '/editorial_workflow' | relative_url }})

## Source and attribution

This guide is adapted from the [RDMkit Page metadata guide](https://rdmkit.elixir-europe.org/page_metadata), distributed as part of RDMkit documentation under the [Creative Commons Attribution 4.0 International licence](https://creativecommons.org/licenses/by/4.0/).

It has been revised for the NFDI4Health Knowledge Base to distinguish current page configuration from inherited RDMkit conventions, document the repository's actual fields and align examples with biomedical research data management and the emerging NFDI4Health contribution workflow. The acknowledgement recognises the source; it does not imply that RDMkit maintains NFDI4Health guidance.

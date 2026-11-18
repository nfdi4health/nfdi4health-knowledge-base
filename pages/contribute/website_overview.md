---
title: Page IDs and URLs
description: Find and maintain page identifiers and stable URLs in the NFDI4Health Knowledge Base.
permalink: /website_overview
sidebar: contribute
search_exclude: false
contributors: [Atinkut A. Zeleke]
---

This page helps NFDI4Health Knowledge Base contributors and maintainers find existing pages, link to them correctly and avoid breaking established URLs. It replaces the inherited RDMkit-generated list, which was tied to a sidebar and did not provide a reliable inventory of all NFDI4Health pages.

**Important:** A page's public URL is not necessarily its `page_id`. For most new contributions, use a stable `permalink` and the required page metadata; **do not introduce a new `page_id` simply to give a page a URL**.

## What identifies a Knowledge Base page?

| Item | Where to find it | What it means |
| --- | --- | --- |
| **Source file** | A Markdown file in the repository's `pages/` directory | The file that contributors edit. Its location is not necessarily the public URL. |
| **Page title** | `title` in YAML front matter | The visible heading displayed by the website theme. |
| **Public URL** | `permalink` in front matter, or the site's fallback URL rule | The address readers use to open or link to the page. This is the preferred identifier when linking between pages. |
| **Legacy page ID** | `page_id`, if present in an existing file | An inherited identifier that may be used by older templates or cross-references. It is not required for every new NFDI4Health page. |
| **Related pages** | `related_pages`, if present | A legacy relationship field. Retain it until any dependent display logic or links have been checked. |
| **Navigation entry** | `_data/sidebars/*.yml` | The label and URL used in a sidebar. A navigation entry should point to a valid page, but is not itself a page ID. |

For field-by-field guidance, see [Page metadata]({{ '/page_metadata' | relative_url }}).

## Main NFDI4Health page URLs

The following are the principal routes configured in the current Knowledge Base navigation. They are **a useful starting point, not a complete inventory of individual pages**.

| Knowledge Base section | Public path |
| --- | --- |
| [Research Data Life Cycle]({{ '/data_life_cycle' | relative_url }}) | `/data_life_cycle` |
| [Your role]({{ '/your_role' | relative_url }}) | `/your_role` |
| [NFDI4Health services]({{ '/services' | relative_url }}) | `/services` |
| [How-to guides]({{ '/your_tasks' | relative_url }}) | `/your_tasks` |
| [Module catalogue]({{ '/modules' | relative_url }}) | `/modules` |
| [Training resources]({{ '/all_training_resources' | relative_url }}) | `/all_training_resources` |
| [Start contributing]({{ '/how_to_contribute' | relative_url }}) | `/how_to_contribute` |
| [Page metadata]({{ '/page_metadata' | relative_url }}) | `/page_metadata` |
| [Page IDs and URLs]({{ '/website_overview' | relative_url }}) | `/website_overview` |

These paths are site-relative. The theme adds the appropriate site base path when links use Jekyll's `relative_url` filter.

## How to find a page's current identifier

1. Open the [Knowledge Base repository](https://github.com/nfdi4health/nfdi4health-knowledge-base) and select the branch you are working on.
2. Use **Go to file** or repository search to locate the Markdown page by its title or topic.
3. Read the YAML front matter between the opening `---` lines. Check `permalink` and, if present, `page_id`, `related_pages` and `redirect_from`.
4. Check the relevant file in [`_data/sidebars/`](https://github.com/nfdi4health/nfdi4health-knowledge-base/tree/main/_data/sidebars) if the page is linked from a navigation menu. Use the same branch when reviewing the sidebar.
5. Open the corresponding preview URL and check that the intended page loads, the title appears once and internal links work.

If a page has no explicit `permalink`, check the defaults in `_config.yml` before assuming its published URL. The current project configuration provides a fallback based on the filename.

## Add or update a page safely

For a new contributor guidance page, a simple example is:

```yaml
---
title: Example contributor guidance
description: A short description of the guidance.
permalink: /example_contributor_guidance
sidebar: contribute
search_exclude: false
---
```

- Use a **unique, stable `permalink`** and check that no other page already uses it.
- Do not repeat the front matter title as a Markdown `#` heading: the theme already displays the title.
- When updating an existing page, preserve its current public URL unless a migration is deliberately agreed.
- If a URL must change, review `redirect_from` and update relevant navigation entries and internal links.
- Keep inherited `page_id` and `related_pages` fields until any dependencies have been reviewed; do not assign new values without an identified technical need.
- Use site-relative links such as `[Page metadata]({% raw %}{{ '/page_metadata' | relative_url }}{% endraw %})` rather than hard-coding the GitHub Pages domain or base path.

## Before submitting a change

- [ ] The source file and the intended public URL have been identified.
- [ ] The permalink is unique; existing URLs and redirects have been preserved where necessary.
- [ ] The title appears only once in the rendered page.
- [ ] Any sidebar entry points to the correct public path.
- [ ] Internal links work in the branch preview.
- [ ] Legacy identifiers have not been removed without a dependency check.
- [ ] Changes have been submitted through the [GitHub contribution workflow]({{ '/github_way' | relative_url }}) for review.

This page documents **website identifiers**, not NFDI4Health research-study metadata or participant identifiers. Never place sensitive personal health data in public page files or examples.

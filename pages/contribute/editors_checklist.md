---
title: Editors checklist
summary: Checklist to run through before merging a pull request (PR).
---

## Before merging a pull request (PR), check that:
1. The page layout in the preview looks correct.
2. The new page is linked in the appropriate [sidebar](https://github.com/nfdi4health/nfdi4health-knowledge-base/tree/main/_data/sidebars) menu, in the same branch as the PR.
3. Contributor names are listed in the [CONTRIBUTORS file](https://github.com/nfdi4health/nfdi4health-knowledge-base/blob/main/_data/CONTRIBUTORS.yaml), in the same branch as the PR.
4. Relevant metadata fields are correctly filled in (see [page metadata](page_metadata)). Some critical ones:
   * unique `page_id` ([List of page IDs](website_overview))
   * `contributors`
   * `search_exclude` must be deleted
   * `description`
5. Any tools or resources mentioned are tagged with the [correct snippet](tool_resource_update) and described in [tool_and_resource_list.yml](https://github.com/nfdi4health/nfdi4health-knowledge-base/blob/main/_data/tool_and_resource_list.yml).
6. The content follows the [style guide](style_guide) and existing page templates.
7. There are no [copyright](copyright) issues with the content.
8. When a new page is added, a news item is added to [news.yml](https://github.com/nfdi4health/nfdi4health-knowledge-base/blob/main/_data/news.yml), in the same branch as the PR.
9. Contributors are acknowledged for their work.

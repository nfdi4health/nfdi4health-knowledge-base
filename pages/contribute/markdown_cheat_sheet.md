---
title: Markdown cheat sheet
description: Practical Markdown guidance for contributors to the NFDI4Health Knowledge Base.
permalink: /markdown_cheat_sheet
sidebar: contribute
search_exclude: false
contributors: [Atinkut A. Zeleke]
---

The NFDI4Health Knowledge Base uses Markdown to develop and maintain service descriptions, self-paced learning modules, and biomedical research data life-cycle guidance.

This cheat sheet provides practical Markdown formatting examples for contributors who wish to create or update Knowledge Base content through GitHub.

**You do not need GitHub experience to contribute.** Contributors may also prepare content using the approved Word or Markdown templates and submit their materials to the coordination team. For further information, see the [How to Contribute]({{ '/how_to_contribute' | relative_url }}) page.

When editing an existing page, preserve its YAML front matter, permalink and sidebar settings unless changes have been agreed with the coordination team.

For content requirements, consult the [NFDI4Health contribution standards]({{ '/content_standards' | relative_url }}).

The following examples demonstrate commonly used Markdown features. All contributions should follow the NFDI4Health Knowledge Base writing, accessibility, attribution and privacy requirements.


## Headings

Headings organise Knowledge Base content and make it easier for readers to navigate a page.

### Page titles

The NFDI4Health Knowledge Base automatically generates the main page heading from the `title` field in the YAML front matter.

For example:

```yaml
---
title: NFDI4Health Research Data Life Cycle
---
```

**Important:** Do not repeat the page title using a Markdown `#` heading in the page body. Doing so can result in duplicate titles.

### Section headings

Use level-two headings (`##`) for main sections and level-three headings (`###`) for subsections.

Example:

```markdown
## Purpose

Explain why the service or guidance is relevant.

## Typical use cases

Describe practical applications in biomedical research.

### Example: Clinical research

Explain how researchers might use the service.
```

### Good practices

- Use clear and descriptive headings.
- Follow a logical heading hierarchy.
- Do not skip heading levels unnecessarily.
- Keep headings concise and meaningful.
- Avoid using headings only to change text size.
- Use the page's YAML `title` field for its main title.

## Bold text

**Bold** text

Using:
```
**Bold** text
```

Make sure there are no spaces between the asterisks and the text you want to put in bold.

## Italic text

*Italic* text

Using:
```
*Italic* text
```

Make sure there are no spaces between the asterisks and the text you want to put in italic.

## File names/ files / software names

`Text` can be highlighted using:

```md
`Text`
```

## Tables

Markdown tables help organise information clearly and consistently across NFDI4Health Knowledge Base pages.

For example, contributors can use tables to summarise the information required for service descriptions, self-paced learning modules and research data life-cycle guidance.

### Example: NFDI4Health content types

The following Markdown code creates a simple table:

```md
| Content type | Information to include |
| --- | --- |
| Service description | Purpose, target users, access conditions, FAIR relevance and references |
| Self-paced learning module | Learning objectives, core concepts, practical workflow and self-check questions |
| Research data life-cycle guidance | Recommended actions, biomedical examples, safeguards, related services and references |
```

**Result:**

| Content type | Information to include |
| --- | --- |
| Service description | Purpose, target users, access conditions, FAIR relevance and references |
| Self-paced learning module | Learning objectives, core concepts, practical workflow and self-check questions |
| Research data life-cycle guidance | Recommended actions, biomedical examples, safeguards, related services and references |

### Recommendations for tables

- Use clear and informative column headings.
- Keep descriptions concise and understandable.
- Avoid excessively wide tables.
- Ensure that tables remain readable on mobile devices.
- Provide references for scientific or technical claims.
- Do not use tables solely for visual page layout.
## Message boxes

Message boxes, also called callouts, highlight important information within NFDI4Health Knowledge Base pages.

The Knowledge Base theme provides four types of callouts.

### Note

Use notes to provide additional information.

{% include callout.html type="note" content="Use the appropriate NFDI4Health content template when preparing a new contribution." %}

### Tip

Use tips to provide practical recommendations.

{% include callout.html type="tip" content="Link to current NFDI4Health service documentation and include relevant references." %}

### Warning

Use warnings to highlight potential risks.

{% include callout.html type="warning" content="Never upload identifiable personal health data, confidential research information or institutional credentials to a public repository." %}

### Important

Use important callouts to highlight essential requirements.

{% include callout.html type="important" content="Content must undergo the applicable editorial and subject review before publication by an authorised maintainer." %}

### Markdown syntax

Callouts are inserted using the following Jekyll syntax:

{% raw %}
```liquid
{% include callout.html type="warning" content="Do not include identifiable health data." %}
```
{% endraw %}

Replace `warning` with `note`, `tip` or `important` according to the intended purpose.

### Recommendations

- Use callouts only when information requires particular attention.
- Keep messages short and specific.
- Avoid placing several callouts directly after one another in ordinary guidance pages.
- Do not use callouts as substitutes for clear explanations.
- Ensure that important information is understandable without relying solely on colour.

## Images

Images can help explain biomedical research data management concepts, workflows, services and research data life-cycle stages.

Contributors should use images only when they improve understanding. All images must be accessible, appropriately licensed and suitable for public distribution.

### Adding images using Markdown

The standard Markdown syntax is:

```md
![Alternative text describing the image](path/to/image.png)
```

For example, a contributor documenting the biomedical research data life cycle could include a diagram showing the relationships between its stages.

The image filename and path must correspond to an existing file in the repository.

### Adding images using the Jekyll theme

The NFDI4Health Knowledge Base uses the ELIXIR Toolkit Theme, which provides an image component supporting captions and accessibility information.

An image can be inserted using the following syntax:

{% raw %}
```liquid
{% include image.html
   file="data_life_cycle/diagram.svg"
   alt="Diagram illustrating the stages of the biomedical research data life cycle"
   caption="Overview of the biomedical research data life cycle"
%}
```
{% endraw %}

The filename above is illustrative. Replace it with the path to an actual image uploaded to the repository's `images` directory.

Useful attributes include:

- `file`: Path to the image within the image directory.
- `alt`: Meaningful text describing the image for people using screen readers.
- `caption`: A visible description explaining the image.
- `max-width`: Maximum displayed image width, when appropriate.
- `click`: Allows the image to be opened separately when supported by the theme.

### Image accessibility

When preparing images:

- Provide meaningful alternative text describing the information conveyed.
- Explain complex diagrams in the surrounding text.
- Ensure that text remains readable when images are resized.
- Use sufficient colour contrast.
- Do not communicate important information through colour alone.
- Avoid embedding long paragraphs of text inside images.

### Copyright and attribution

Contributors must provide the following information for each submitted image:

1. Image title or description.
2. Creator or copyright holder.
3. Original source or URL.
4. Licence and required attribution.
5. Any modifications made to the original image.

Use original diagrams, appropriately licensed material or images for which publication permission has been obtained.

### Privacy and sensitive health data

Do not upload images containing identifiable patient information, confidential research data, institutional credentials or restricted screenshots.

For biomedical examples, prefer fictional or synthetic data unless the necessary permissions and legal approvals have been confirmed.

For additional requirements, consult the [NFDI4Health contribution standards]({{ '/content_standards' | relative_url }}) and [copyright and attribution guidelines]({{ '/copyright' | relative_url }}).



## Icons

The NFDI4Health Knowledge Base can use Font Awesome icons to help readers identify different types of content.

Icons should support the written information, not replace descriptive text. See the [Font Awesome icon library](https://fontawesome.com/icons) for available icons.

### Example: Research data services

```html
<i class="fa-solid fa-database" aria-hidden="true"></i> Research data services
<i class="fa-solid fa-graduation-cap" aria-hidden="true"></i> Self-paced learning modules
<i class="fa-solid fa-diagram-project" aria-hidden="true"></i> Research data life cycle
```

### Accessibility considerations

- Always provide a meaningful text label alongside an icon.
- Do not communicate essential information through icons alone.
- Use `aria-hidden="true"` for decorative icons when the accompanying text already conveys their meaning.
- Check that icons display correctly in the Netlify preview.

## Links

Links connect NFDI4Health Knowledge Base pages with relevant services, learning modules, research data life-cycle guidance and authoritative external resources.

Use descriptive link text so readers understand where a link leads.

### External links

External links connect readers to websites outside the Knowledge Base.

For example:

```md
[NFDI4Health official website](https://www.nfdi4health.de/)
```

**Result:**

[NFDI4Health official website](https://www.nfdi4health.de/)

When adding external links:

- Prefer official NFDI4Health service websites and authoritative sources.
- Verify that the destination is correct and accessible.
- Use HTTPS whenever available.
- Avoid linking to outdated, restricted or unreliable resources.
- Provide references for scientific and technical claims.

### Internal Knowledge Base links

Internal links connect related pages within the NFDI4Health Knowledge Base.

Because the Knowledge Base is deployed through GitHub Pages and Netlify, internal links should use Jekyll's `relative_url` filter.

For example:

{% raw %}
```liquid
[Research Data Life Cycle]({{ '/data_life_cycle' | relative_url }})
```
{% endraw %}

**Result:**

[Research Data Life Cycle]({{ '/data_life_cycle' | relative_url }})

This approach helps internal links work correctly across different deployment environments.

### Linking related Knowledge Base content

Where relevant, connect a page to:

- Related NFDI4Health services.
- Relevant research data life-cycle stages.
- Self-paced learning modules.
- Practical how-to guides.
- Guidance for specific user roles.

For example, a service description may link to the relevant research data life-cycle stage and an associated learning module.

### Good practices for links

- Use meaningful link descriptions instead of phrases such as "click here".
- Check that internal links point to existing Knowledge Base pages.
- Avoid unnecessary duplication of information across pages.
- Review external links periodically.
- Do not link to confidential documents or restricted information without appropriate authorisation.

For additional guidance, consult the [NFDI4Health contribution standards]({{ '/content_standards' | relative_url }}).

## Code blocks and YAML examples

Code blocks are used to display Markdown syntax, YAML metadata and other technical examples without interpreting them as ordinary page content.

A code block begins and ends with three backticks. Adding a language identifier, such as `yaml` or `md`, enables syntax highlighting.

### Example: YAML front matter

Every Knowledge Base page uses YAML front matter to define important page information.

For example:

```yaml
---
title: Contribute using GitHub
permalink: /github_way
sidebar: contribute
---
```

The metadata defines:

- `title`: The title displayed at the top of the page.
- `permalink`: The permanent URL assigned to the page.
- `sidebar`: The navigation menu associated with the page.

**Important:** The Knowledge Base theme automatically displays the title defined in the YAML metadata. Do not repeat it using a top-level Markdown heading (`#`) in the page body.

When updating an existing page, preserve its working metadata unless changes have been agreed with the coordination team.

### Example: Markdown content structure

The following example demonstrates how to organise guidance within a Knowledge Base page:

```md
## Recommended actions

1. Identify the relevant research data management requirements.
2. Document the applicable procedures and responsibilities.
3. Check the relevant NFDI4Health services and guidance.
4. Record supporting references and sources.

## Further information

Provide links to relevant services, standards and learning materials.
```

### Recommendations

- Use code blocks only when they help readers understand a technical procedure.
- Specify the appropriate language for syntax highlighting.
- Keep examples concise and clearly explained.
- Never include passwords, API tokens, confidential information or identifiable personal health data.
- Ensure that technical examples are checked before publication.


## Lists and sublists

Lists help present research data management guidance in a clear, structured and actionable format.

Use bullet points for related information without a required sequence. Use numbered lists when actions should be performed in a particular order.

### Bulleted lists

For example, a Knowledge Base page might describe important considerations when preparing biomedical research data for sharing.

Markdown syntax:

```md
- Data documentation
- Metadata quality
- Access conditions
  - Publicly accessible metadata
  - Controlled access to sensitive data
- Licensing and reuse conditions
```

**Result:**

- Data documentation
- Metadata quality
- Access conditions
  - Publicly accessible metadata
  - Controlled access to sensitive data
- Licensing and reuse conditions

### Numbered lists

Numbered lists are useful for explaining workflows and recommended procedures.

Markdown syntax:

```md
1. Identify the research data management requirements.
2. Determine the relevant institutional policies and safeguards.
3. Identify applicable NFDI4Health services.
4. Document the workflow and responsibilities.
5. Verify the information and supporting references.
```

**Result:**

1. Identify the research data management requirements.
2. Determine the relevant institutional policies and safeguards.
3. Identify applicable NFDI4Health services.
4. Document the workflow and responsibilities.
5. Verify the information and supporting references.

### Recommendations

- Use short, descriptive list items.
- Maintain consistent grammatical structure.
- Use numbered lists for sequential instructions.
- Avoid unnecessary levels of nesting.
- Explain specialist terminology when appropriate.
- Ensure that lists remain readable on mobile devices.

## Block quotes

Block quotes are used to distinguish quoted text from the surrounding content.

In the NFDI4Health Knowledge Base, quotations may be useful when referring to official guidance, policies, standards or documented recommendations.

Use the `>` symbol at the beginning of a line to create a block quote.

### Example: Quoting NFDI4Health contribution guidance

The following Markdown syntax creates a block quote:

```md
> Use synthetic, fully fictional examples unless explicit approval and legal clearance exist.
```

**Result:**

> Use synthetic, fully fictional examples unless explicit approval and legal clearance exist.

Source: [NFDI4Health contribution standards]({{ '/content_standards' | relative_url }}).

### Recommendations for quotations

- Reproduce quotations accurately without changing their meaning.
- Clearly identify the original source.
- Provide a citation or link to the referenced document.
- Use quotations only when necessary; otherwise, summarise the information in your own words.
- Respect copyright and licensing requirements.
- Do not reproduce confidential documents or restricted information.

For longer passages, consider summarising the relevant guidance and linking to the original source instead of reproducing extensive text.
## Collapsible guidance

Collapsible sections allow readers to expand additional information without displaying it permanently on the page.

They can be useful for supplementary explanations, examples and frequently asked questions.

### Example: Preparing a service description

The following example creates an expandable checklist.

<details>
  <summary>What should I check before submitting a service description?</summary>
  <ul>
    <li>Confirm the current service name, status and official URL.</li>
    <li>Describe the intended users and access conditions.</li>
    <li>Identify relevant FAIR and research data life-cycle activities.</li>
    <li>Provide references and a responsible content steward.</li>
  </ul>
</details>

### HTML syntax

```html
<details>
  <summary>What should I check before submitting a service description?</summary>
  <ul>
    <li>Confirm the current service name, status and official URL.</li>
    <li>Describe the intended users and access conditions.</li>
    <li>Identify relevant FAIR and research data life-cycle activities.</li>
    <li>Provide references and a responsible content steward.</li>
  </ul>
</details>
```

### Recommendations

- Use clear and informative summary text.
- Keep essential instructions visible in the main page content.
- Use collapsible sections primarily for supplementary information.
- Do not hide important privacy warnings or access restrictions inside collapsed sections.
- Check that the content remains accessible using a keyboard.

## Paragraphs and line breaks

Markdown provides simple ways to organise text into readable paragraphs.

### Creating paragraphs

Leave one empty line between paragraphs.

For example:

```md
The first paragraph introduces the research data management topic.

The second paragraph provides additional guidance or recommendations.
```

This creates two separate paragraphs.

### Creating a line break

For a line break without starting a new paragraph, an HTML `<br>` element can be used when necessary.

Example:

```md
First line of text.<br>
Second line of text.
```

### Recommendations

- Prefer ordinary paragraphs rather than manually inserting multiple line breaks.
- Use headings and lists to organise longer content.
- Avoid excessive blank spaces and unnecessary HTML formatting.
- Keep text readable on desktop and mobile devices.
- Allow the Knowledge Base theme to control spacing and layout wherever possible.

  ## Source and attribution

This guide is adapted from the [RDMkit Markdown cheat sheet](https://rdmkit.elixir-europe.org/markdown_cheat_sheet), originally credited to Bert Droesbeke.

The original RDMkit documentation is distributed under the [Creative Commons Attribution 4.0 International licence](https://creativecommons.org/licenses/by/4.0/).

The content has been revised for the NFDI4Health Knowledge Base, including examples relating to biomedical research data management, NFDI4Health services, self-paced learning modules, accessibility and data privacy.

This acknowledgement recognises the original source and does not imply that RDMkit is responsible for maintaining the NFDI4Health contribution guidance.

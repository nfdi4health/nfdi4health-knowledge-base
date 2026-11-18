---
title: Markdown cheat sheet
summary: This is a cheat sheet to showcase what is possible within the markdown pages.
contributors: [Bert Droesbeke]
search_exclude: true
---

The NFDI4Health Knowledge Base uses Markdown to develop and maintain service descriptions, self-paced learning modules, and biomedical research data life-cycle guidance.

This cheat sheet provides practical Markdown formatting examples for contributors who wish to create or update Knowledge Base content through GitHub.

**You do not need GitHub experience to contribute.** Contributors may also prepare content using the approved Word or Markdown templates and submit their materials to the coordination team. For further information, see the [How to Contribute]({{ '/how_to_contribute' | relative_url }}) page.

When editing an existing page, preserve its YAML front matter, permalink and sidebar settings unless changes have been agreed with the coordination team.

For content requirements, consult the [NFDI4Health contribution standards]({{ '/content_standards' | relative_url }}).

The following examples demonstrate commonly used Markdown features. All contributions should follow the NFDI4Health Knowledge Base writing, accessibility, attribution and privacy requirements.


## Titles

Using:
```
## Title
```

### Sub titles

Using:
```
### Sub titles
```

#### Sub sub titles

Using:
```
#### Sub sub titles
```

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

Change the content attribute in the code snippet to change the text in the message box

{% include callout.html type="note" content="This is my note." %}

{% include callout.html type="tip" content="This is my tip." %}

{% include callout.html type="warning" content="This is my warning." %}

{% include callout.html type="important" content="This is my important info." %}


This is done by using this snippet:
{% raw %}
```
{% include callout.html type="note" content="This is my note." %}
```
{% endraw %}
note can be replaced with tip, warning, important, depending on the type of message you want. 
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

Go to the [Font Awesome library](https://fontawesome.com/) to see the available icons.

The Font Awesome icons allow you to adjust their size by simply adding `fa-2x`, `fa-3x` and so forth as a class to the icon to adjust their size to two times or three times the original size. As vector icons, they scale crisply at any size.

Here's an example of how to scale up a camera icon:

```html
<i class="fa-solid fa-camera-retro"></i> normal size (1x)
<i class="fa-solid fa-camera-retro fa-lg"></i> fa-lg
<i class="fa-solid fa-camera-retro fa-2x"></i> fa-2x
<i class="fa-solid fa-camera-retro fa-3x"></i> fa-3x
<i class="fa-solid fa-camera-retro fa-4x"></i> fa-4x
<i class="fa-solid fa-camera-retro fa-5x"></i> fa-5x
```

Here's what they render to:

<i class="fa-solid fa-camera-retro"></i> 1x
<i class="fa-solid fa-camera-retro fa-lg"></i> fa-lg
<i class="fa-solid fa-camera-retro fa-2x"></i> fa-2x
<i class="fa-solid fa-camera-retro fa-3x"></i> fa-3x
<i class="fa-solid fa-camera-retro fa-4x"></i> fa-4x
<i class="fa-solid fa-camera-retro fa-5x"></i> fa-5x

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

## Emoji's

Use GitHub emoticons! This [github page about emoticons](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) has a cheat sheet for all the emoticons.
:+1: is made with `:+1:`

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


## List and sub-list 

* List line 1
* List line 2
    * Sublist line 1

Is made with:

```md
* List line 1
* List line 2
    * Sublist line 1
		* Subsublist line 1
```

Numbered lists look like this:

1. Number one
2. Number two
3. Number three
   1. Sub number one
   2. Sub number two

and are made with:

```md
1. Number one
1. Number two
1. Number three
   1. Sub number one
   1. Sub number two

```

## Block quotes

You can add a blockquote using:

```md
> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
>
> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

```

Giving:

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 

> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
>
> Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 


## A collapsible piece of text

<details>
  <summary>Click to expand!</summary>
<ol>
Text
</ol>
</details>
<br>
Is made with this code snippet:

```html
<details>
  <summary>Click to expand!</summary>
<ol>
Text
</ol>
</details>
```


## Enforce space between two lines

To have space between two lines of text, simply leave one empty line in between the line in the markdown. If more is needed, you can force this with:


```md
<br>
```

## Enforce line break

When you want to have a line of text.\\
And another line underneath it without space, use:

```md
When you want to have a line of text.\\
And another line underneath it without space, use:
```

Without these backslashes

```
When you want to have a line of text.
And another line underneath it without space, use:
```

looks like this:

When you want to have a line of text.
And another line underneath it without space, use:

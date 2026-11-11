---
title: NFDI4Health Data Stewards
permalink: /contributors
toc: false
github:
  file_path: _data/nfdi4health_data_stewards.yml
---

The NFDI4Health Knowledge Base is developed and maintained with contributions from NFDI4Health data stewards and subject-matter experts.

Data stewards contribute their expertise to service descriptions, learning modules, and research data life cycle guidance. They help ensure that content is accurate, relevant, and regularly updated.

## Our Data Stewards

{% for steward in site.data.nfdi4health_data_stewards %}
<div class="card mb-4" style="max-width: 440px;">
  <div class="card-body text-center">

    {% if steward.github %}
    <img
      src="https://github.com/{{ steward.github }}.png?size=240"
      alt="Profile image of {{ steward.name }}"
      class="rounded-circle mb-3"
      style="width: 120px; height: 120px; object-fit: cover;"
      loading="lazy">
    {% endif %}

    <h3 class="card-title">{{ steward.name }}</h3>

    <p class="card-text">
      <strong>{{ steward.role }}</strong>
    </p>

    <p class="card-text">
      {{ steward.affiliation }}
    </p>

    <p>
      {% if steward.github %}
      <a href="https://github.com/{{ steward.github }}">GitHub</a>
      {% endif %}

      {% if steward.orcid %}
      | <a href="{{ steward.orcid }}">ORCID</a>
      {% endif %}
    </p>

  </div>
</div>
{% endfor %}

## Become a Contributor

NFDI4Health data stewards are invited to contribute and maintain content within their areas of expertise.

New contributors will be added to this directory once their participation and profile details have been confirmed.

For more information, visit our [How to Contribute]({{ '/how_to_contribute' | relative_url }}) page.

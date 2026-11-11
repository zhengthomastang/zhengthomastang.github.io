---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
excerpt: "Research publications in multimodal AI, computer vision, and model evaluation."
---

{% assign publications = site.publications | where_exp: "publication", "publication.hidden != true" | where_exp: "publication", "publication.published != false" | sort: "date" | reverse %}
{% assign publication_year = "" %}

<div class="publication-list">
{% for publication in publications %}
  {% assign year = publication.date | date: "%Y" %}
  {% assign publication_id = publication.title | slugify %}
  {% if year != publication_year %}
    <h2 class="publication-year" id="year-{{ year }}">{{ year }}</h2>
    {% assign publication_year = year %}
  {% endif %}
  <article class="publication-card" aria-labelledby="publication-{{ publication_id }}">
    {% if publication.image %}
      <a class="publication-card__image" href="{{ publication.url | relative_url }}" tabindex="-1" aria-hidden="true">
        <img src="{{ publication.image | relative_url }}" alt="" loading="lazy">
      </a>
    {% endif %}
    <div class="publication-card__body">
      <h3 id="publication-{{ publication_id }}"><a href="{{ publication.url | relative_url }}">{{ publication.title | escape }}</a></h3>
      {% include publication-meta.html publication=publication %}
      {% include publication-links.html publication=publication %}
    </div>
  </article>
{% endfor %}
</div>

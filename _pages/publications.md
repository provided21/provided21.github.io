---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Conference Papers

{% for post in site.publications reversed %}
  {% if post.paper_type == "conference" %}
    {% include publication-card.html %}
  {% endif %}
{% endfor %}

## Journal Papers

{% for post in site.publications reversed %}
  {% if post.paper_type == "journal" %}
    {% include publication-card.html %}
  {% endif %}
{% endfor %}

## Preprints

{% for post in site.publications reversed %}
  {% if post.paper_type == "preprint" %}
    {% include publication-card.html %}
  {% endif %}
{% endfor %}

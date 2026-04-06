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

## Online Platforms for Social Connection

{% assign platform_pubs = site.publications | where: 'research_area', 'Online Platforms for Social Connection' | sort: 'date' | reverse %}
{% for post in platform_pubs %}
  {% include archive-single.html %}
{% endfor %}

## Collaborative Work

{% assign other_pubs = site.publications | where: 'research_area', 'Collaborative Work' | sort: 'date' | reverse %}
{% for post in other_pubs %}
  {% include archive-single.html %}
{% endfor %}

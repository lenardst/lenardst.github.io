---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Peer-reviewed articles, preprints, and conference papers on coordination,
organization design, and online platforms.
{% if author.googlescholar %}Also on <a href="{{ author.googlescholar }}" target="_blank" rel="noopener noreferrer">Google Scholar</a>.{% endif %}

## Collaborative Work

{% assign other_pubs = site.publications | where: 'research_area', 'Collaborative Work' | sort: 'date' | reverse %}
{% for post in other_pubs %}
  {% include archive-single.html %}
{% endfor %}

## Online Platforms for Social Connection

{% assign platform_pubs = site.publications | where: 'research_area', 'Online Platforms for Social Connection' | sort: 'date' | reverse %}
{% for post in platform_pubs %}
  {% include archive-single.html %}
{% endfor %}

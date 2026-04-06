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

{% assign areas = site.publications | map: 'research_area' | compact | uniq | sort %}

{% for area in areas %}
## {{ area }}

{% assign area_pubs = site.publications | where: 'research_area', area | sort: 'date' | reverse %}
{% for post in area_pubs %}
  {% include archive-single.html %}
{% endfor %}

{% endfor %}

{% assign remaining = site.publications | where_exp: 'item', 'item.research_area == nil or item.research_area == ""' | sort: 'date' | reverse %}
{% if remaining.size > 0 %}

## Other Publications

{% for post in remaining %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

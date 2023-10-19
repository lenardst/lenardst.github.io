---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Information Systems, University of Münster, 2021
* M.S. in Sociology and Social Research, Utrecht University, 2014
* Ph.D in Organizational Behavior, Stanford Graduate School of Business, 2028 (expected)

Work experience
======
* Summer 2022: Research Intern
  * Utrecht University

* 2019 - 2022: Research Assistant / TA
  * University of Münster

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

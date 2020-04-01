---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[Full CV](#)

Education
======
* <i>B.A.</i>: Earth and Oceanographic Science, Classics Minor, Bowdoin College, 2014
* <i>PhD Candidate</i>: Earth & Planetary Science, Isotope Geochemistry, UC Santa Cruz, expected 2021

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

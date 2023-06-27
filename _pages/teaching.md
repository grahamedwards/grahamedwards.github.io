---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

My approach to teaching reflects my teaching and outreach work in museums, K-12 classrooms, college classrooms, field sites, and laboratories...

## Previously taught courses:
{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

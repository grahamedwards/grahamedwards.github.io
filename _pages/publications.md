---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Additional co-authored papers and abstracts on <a href="https://scholar.google.com/citations?user=KHLOvgcAAAAJ">Google Scholar</a> and the  <a href="https://ui.adsabs.harvard.edu/search/q=author%3A%22Edwards%2C%20Graham%20Harper%22">Astrophysics Data System</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

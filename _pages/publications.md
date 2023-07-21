---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

You can also find a complete list of articles on my [Google Scholar profile](https://scholar.google.es/citations?user=gqRwKssAAAAJ&hl).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}

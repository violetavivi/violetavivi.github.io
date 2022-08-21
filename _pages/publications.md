---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find a more updated list of articles on my [Google Scholar profile](https://scholar.google.es/citations?user=gqRwKssAAAAJ&hl).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

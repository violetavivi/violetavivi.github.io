---
layout: archive
permalink: /research/
author_profile: true
---
Theoretical Ecology | Interaction Networks | Complex Systems
{: .notice}

You can also find a complete list of articles on my [Google Scholar profile](https://scholar.google.es/citations?user=gqRwKssAAAAJ&hl).

<div style="margin-top: 2em;">
  {% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
  {% for post in sorted_pubs %}
    {% include archive-single-publications.html %}
  {% endfor %}
</div>

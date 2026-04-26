---
layout: archive
permalink: /research/
author_profile: true
---
Theoretical Ecology  +  Interaction Networks  +  Complex Systems
{: .notice}

<div style="margin-top: 2em;">
  {% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
  {% for post in sorted_pubs %}
    {% include archive-single-publications.html %}
  {% endfor %}
</div>

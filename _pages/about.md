---
permalink: /
excerpt: "Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

:wave: Postdoctoral fellow at University of Oxford, part of the [SalGo lab](https://www.salgo.ox.ac.uk/). Formerly at Doñana Biological Station (CSIC), Spain, studying the variation of ecological interactions. 
<p style="text-align: justify"> 
My research focuses on ecological systems, lying at the intersection of theoretical and quantitative ecology. I humbly address one of the central questions in ecology: how ecological interactions shape the coexistence and long-term persistence of species. To explore this, I integrate data from field observations and experiments with theoretical frameworks using techniques from dynamical systems, complex networks, and computation.

</p>
  - Currently working on: Ecological interactions, Invasion graphs, Temporal networks, Coexistence, Structural Stability
 
 
You can find a surely outdated CV [here](http://violetavivi.github.io/files/myCV.pdf).


## Education
:hatched_chick: PhD in Complex Systems, [_IFISC_](https://ifisc.uib-csic.es/en/) (Institute for Cross-Disciplinary Physics and Complex Systems), Spain
      
:hatching_chick: Master in Physics and Physical Technologies, :egg: Bachelor in Physics, _University of Zaragoza_, Spain


## Publications
<ul>
  {% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
  {% for post in sorted_pubs %}
    {% include archive-single-publications-about.html %}
  {% endfor %}
</ul>
  

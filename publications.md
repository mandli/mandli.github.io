---
title: Publications
layout: page
---
{% bibliography --file my_pubs.bib --template long_bib --query !@unpublished --query !@phdthesis %}

### Submitted

{% bibliography --file my_pubs.bib --template long_bib --query @unpublished %}

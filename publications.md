---
title: Publications
layout: page
---
{% bibliography --file articles.bib --template long_bib --query !@unpublished --query !@phdthesis %}

### Submitted

{% bibliography --file articles.bib --template long_bib --query @unpublished %}

---
layout: page
permalink: /repositories/
title: Repositories
description:
nav: true
nav_order: 4
---

<p>
A curated selection of open-source projects I develop and maintain. For the complete list, see <a href="https://github.com/mandli">GitHub</a>.
</p>

{% assign featured = site.data.software | where: "featured", true %}
{% include software_cards_large.html items=featured %}

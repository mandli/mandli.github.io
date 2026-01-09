---
layout: page
title: Open Source Scientific Software
description: Development and stewardship of open-source software for numerical simulation of hyperbolic PDEs and geophysical hazards.
img: assets/img/thumbs/geoclaw_icon.png
importance: 4
category: work
related_publications: true
tags: open source software, scientific computing, reproducible research, high performance computing
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/open_source/clawpack_stacked.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/open_source/geoclaw_stacked.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/open_source/pyclaw_stacked.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

# Overview

Open-source software development is a central component of my research program. This project focuses on the **design, implementation, and long-term maintenance of community-driven scientific software** for numerical simulation, with an emphasis on correctness, scalability, and reproducibility.

My contributions emphasize software as a **research product**, not merely an implementation detail.

## Core Software Projects

- **GeoClaw** – Adaptive storm surge and tsunami modeling  
  <https://github.com/clawpack/geoclaw>

- **PyClaw** – Python-based framework for solving hyperbolic PDEs  
  <https://github.com/clawpack/pyclaw>

- **Clawpack** – Open-source ecosystem for wave propagation problems  
  <https://www.clawpack.org>

These tools are used internationally in research, education, and applied hazard modeling.

## Design Principles

These software efforts support research areas including [Numerical Methods for Hyperbolic PDEs]({% link _projects/numerical_methods_hyperbolic_pdes.md %})￼and [Coastal Flooding & Storm Surge Modeling]({% link _projects/coastal_flooding_storm_surge.md %}).

- Close coupling between **numerical methods and software architecture**
- Performance portability across HPC platforms
- Transparent algorithms enabling reproducibility
- Extensibility for interdisciplinary applications
- Community engagement and mentorship

## Impact

- Broad adoption in geophysical and applied mathematics communities
- Support for reproducible, open computational science
- Training of students and early-career researchers through real research software
- Long-term sustainability of research codes beyond individual projects or grants

## Representative Publications

- Clawpack software ecosystem {% cite MandliEtAl.2016 %}
- PyClaw: scalable tools for wave propagation {% cite KetchesonEtAl.2012 %}
- GeoClaw for depth-averaged geophysical flows {% cite BergerEtAl.2011 %}

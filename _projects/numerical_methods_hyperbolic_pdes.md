---
layout: page
title: Numerical Methods for Hyperbolic PDEs
description: Finite-volume and adaptive numerical methods for nonlinear hyperbolic PDEs, motivated by transport-dominated systems in geophysical and environmental modeling.
img: assets/img/thumbs/wall_overtopping.png
importance: 2
category: work
related_publications: true
tags: hyperbolic PDEs, finite volume methods, adaptive mesh refinement, numerical analysis
---

# Overview

In my research I focus on the development of **robust numerical methods for nonlinear hyperbolic partial differential equations**, with an emphasis on transport-dominated systems arising in geophysical and environmental applications.

My work in this area combines numerical analysis, algorithm design, and large-scale computation, often motivated by challenges encountered in applied geophysical and environmental modeling. This work provides the mathematical foundation for several applied and interdisciplinary research areas described elsewhere on this site.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/hyperbolic/multilayer_coords.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Above: Coordinate system for the two-layer shallow water system demonstrating internal waves, from {% cite mandli.2013.numerical %}.  
            <br> <br>
            Right: Riemann solver demonstrating water overtopping a zero-width barrier on sloping bathymetry, from {% cite li.2021.hbox %}.
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/hyperbolic/wall_overtopping.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Core Themes

- Finite-volume methods for conservation laws
- Treatment of dry states, wetting/drying, and sharp interfaces
- Adaptive mesh refinement for multiscale solutions
- Stability and accuracy in complex geometries
- Transport-dominated and nonsmooth solution behavior

## Methods & Approaches

Key methodological contributions include:

- Finite-volume schemes for **shallow water and multilayer flow models**
- Adaptive mesh refinement strategies for hyperbolic systems
- Cut-cell and barrier methods for complex domains
- Transport-aware approaches to reduced-order modeling
- Algorithmic foundations supporting scalable implementations

## Connections to Other Projects

This work underpins several related efforts, including:

- [Coastal Flooding & Storm Surge Modeling]({% link _projects/coastal_flooding_storm_surge.md %})
- [Uncertainty Quantification & Risk]({% link _projects/uncertainty_risk.md %})
- [Open-Source Scientific Software]({% link _projects/open_source_software.md %})

## Representative Publications

- Adaptive mesh refinement for storm surge {% cite mandli.2014.adaptive berger.2011.geoclaw %}
- Finite-volume methods for shallow water systems {% cite mandli.2013.numerical %}
- Transport-dominated model reduction {% cite rim.2018.displacement rim.2023.manifold %}
- Open-source frameworks for hyperbolic PDEs {% cite mandli.2016.clawpack ketcheson.2012.pyclaw %}

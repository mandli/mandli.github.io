---
layout: page
title: Numerical Methods for Hyperbolic PDEs
description: Design and analysis of finite-volume and adaptive numerical methods for nonlinear hyperbolic partial differential equations with applications to geophysical flows.
img: assets/img/thumbs/wall_overtopping.png
importance: 2
category: work
related_publications: true
tags: hyperbolic PDEs, finite volume methods, adaptive mesh refinement, numerical analysis
---

# Overview

In my research I focus on the development of **robust numerical methods for nonlinear hyperbolic partial differential equations**, with an emphasis on transport-dominated systems arising in geophysical and environmental applications.

My work in this area combines numerical analysis, algorithm design, and large-scale computation, often motivated by challenges encountered in real-world coastal and hazard modeling.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/hyperbolic/multilayer_coords.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Above: Coordinate system for the two-layer shallow water system demonstrating internal waves, from {% cite Mandli.2013 %}.  
            <br> <br>
            Right: Riemann solver demonstrating water overtopping a zero-width barrier on sloping bathymetry, from {% cite Li.2021 %}.
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

## Methods & Contributions

Key methodological contributions include:

- Finite-volume schemes for **shallow water and multilayer flow models**
- Adaptive mesh refinement strategies for hyperbolic systems
- Cut-cell and barrier methods for complex domains
- Transport-aware approaches to reduced-order modeling
- Algorithmic foundations supporting scalable implementations

These methods often serve as the numerical backbone for larger modeling frameworks, including coastal flooding and hazard simulations.

## Connections to Other Projects

This work underpins several related efforts, including:

- [Coastal Flooding & Storm Surge Modeling]({% link _projects/coastal_flooding_storm_surge.md %})
- [Uncertainty Quantification & Risk]({% link _projects/uncertainty_risk.md %})
- [Open-Source Scientific Software]({% link _projects/open_source_software.md %})

## Representative Publications

- Adaptive mesh refinement for storm surge {% cite Mandli.2014 BergerEtAl.2011 %}
- Finite-volume methods for shallow water systems {% cite Mandli.2013 %}
- Transport-dominated model reduction {% cite Rim.2018 Rim.2023 %}
- Open-source frameworks for hyperbolic PDEs {% cite Mandli.2016 Ketcheson.2012 %}

## Status

**Ongoing**, with continued emphasis on scalable algorithms, complex geometries, and integration with uncertainty-aware modeling.

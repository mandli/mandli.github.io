---
layout: page
title: Uncertainty Quantification and Risk
description: Uncertainty quantification and risk analysis for geophysical hazard models, emphasizing scalable methods and decision-relevant interpretation under climate change.
img: assets/img/thumbs/musigma1-762.png
importance: 3
category: work
related_publications: true
tags: uncertainty quantification, risk assessment, climate hazards, surrogate modeling
---

# Overview

Uncertainty is inherent in computational models of geophysical systems, arising from incomplete observations, model assumptions, and future climate conditions. This project focuses on **quantifying, propagating, and interpreting uncertainty** in computational models, with the goal of producing **risk-relevant and decision-supporting outputs** rather than single deterministic predictions.

My work emphasizes uncertainty-aware modeling strategies that remain computationally feasible for large-scale, high-resolution simulations. It builds upon earlier contributions to uncertainty quantification and inverse problems for geophysical systems, extending these ideas to modern, large-scale risk assessment under climate change.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="proj-fig">
            {% include figure.liquid loading="eager" path="assets/img/projects/uq/monotone_decomp.png" title="example image" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <div class="proj-fig">
            {% include figure.liquid loading="eager" path="assets/img/thumbs/musigma1-762.png" title="example image" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption mt-2 mb-4">
    Left: Monotone decomposition for transport aware model reduction from {% cite Rim.2023 %}.  Right: Changes in the return curves for Jamaica Bay NYC for the current climate (blue), projected climate in 2050 (orange), and projected climate in 2100 (red) from {% cite Sarhadi.2024 %}.
</div>

## Core Questions

- How should uncertainty in storms, sea level rise, and model parameters be represented in coastal hazard models?
- What uncertainty information is most relevant for risk assessment and decision-making?
- How can uncertainty be propagated efficiently in computationally expensive geophysical models?
- How do climate-driven nonstationarities alter traditional risk metrics?

## Methods & Approaches

My research integrates uncertainty quantification techniques with numerical simulation and data-driven modeling, including:

- **Polynomial chaos and surrogate modeling** for efficient uncertainty propagation
- **Bayesian inference and inverse methods** for parameter estimation in geophysical models
- **Ensemble-based approaches** for storm surge and compound flooding scenarios
- **Reduced-order and transport-aware models** for computationally intensive systems
- **Risk and exceedance analysis** under nonstationary climate assumptions

These methods are often developed in close connection with large-scale numerical models, ensuring consistency between uncertainty treatment and underlying physics.

## Foundations & Early Work

My work in uncertainty quantification builds on earlier contributions to polynomial chaos methods, Bayesian inference, and inverse problems for geophysical and transport-dominated systems. These efforts focused on quantifying parametric uncertainty, inferring poorly constrained model inputs, and developing surrogate models compatible with large-scale numerical solvers.

This foundation continues to inform my current work on risk-aware coastal hazard modeling, particularly in settings where uncertainty is high and data are limited.

## Applications

Representative applications include:

- Probabilistic flood risk assessment for urban infrastructure
- Climate-driven changes in compound flooding risk
- Evaluation of coastal protection strategies under uncertain future conditions
- Interpretation of hazard uncertainty for stakeholder-facing studies

Many of these efforts are closely linked to the [Coastal Flooding & Storm Surge Modeling]({% link _projects/coastal_flooding_storm_surge.md %}) project, where uncertainty-aware methods are applied at scale. This work also draws on foundational numerical methods described in [Numerical Methods for Hyperbolic PDEs]({% link _projects/numerical_methods_hyperbolic_pdes.md %}).

## Outcomes

### Scientific Contributions

- Frameworks for uncertainty-aware coastal hazard modeling
- Methods for integrating uncertainty quantification with high-resolution simulations

### Impact

- Risk metrics that move beyond deterministic flood maps
- Improved [communication of uncertainty to interdisciplinary collaborators]({% link _projects/convergence_science_decision_support.md %})
- Support for climate adaptation and resilience planning under deep uncertainty

## Representative Publications

### Foundations of Uncertainty Quantification

- Quantifying uncertainties in tsunami source inversion {% cite Sraj.2017 Giraldi.2017 %}
- Bayesian inference of geophysical parameters {% cite Sraj.2014 %}
- Polynomial chaos surrogates for transport-dominated systems {% cite Rim.2018 %}

### Risk, Climate, and Coastal Applications

- Climate change contributions to compound flooding {% cite Sarhadi.2024 %}
- Coastal flood hazards under climate change {% cite Hemmati.2025 %}
- Optimization of coastal protection under uncertainty {% cite Miura.2025 %}

---
layout: page
title: Coastal Flooding & Storm Surge Modeling
description: Development of high-resolution, adaptive numerical models for storm surge and coastal flooding, with applications to urban infrastructure, compound flooding, and climate-driven risk assessment.
img: assets/img/sandy_nyc/S12_L05_AT/surface_nyc.png
importance: 1
category: work
related_publications: true
keywords: AMR, shallow water equations, uncertainty quantification, climate risk
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/S10_L00_AT/surface_nyc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/S12_L05_AT/surface_nyc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hurricane Sandy simulations using <a href="https://github.com/clawpack/geoclaw">GeoClaw</a> 4 hours before land fall in different scenarios. Left: Original storm and mean sea-level. Right: Hypothetical scenario with Hurricane Sandy with increased wind strength by 20% and sea-level set to 50 cm above mean sea-level.
</div>

# Overview

Coastal flooding driven by storm surge, tides, waves, and river inflows poses increasing risks to coastal communities and critical infrastructure. This project develops numerically robust, high-resolution models for coastal flooding that integrate advanced numerical methods with real-world geophysical complexity, enabling both scientific insight and actionable risk assessment.

My work in this area spans algorithm development, open-source software, and applied modeling, with applications ranging from hurricanes and tsunamis to compound flooding in urban environments under climate change. Much of this work is implemented through open-source modeling frameworks including [GeoClaw](https://github.com/clawpack/geoclaw) and [AMRClaw](https://github.com/clawpack/amrclaw), which are part of the broader [Clawpack](https://www.clawpack.org) ecosystem.

## Key Scientific Questions

- How can storm surge and coastal flooding be modeled accurately across widely varying spatial and temporal scales?
- How do coastal geometry, barriers, and infrastructure influence flood extent and hazard?
- How can uncertainty in storms, sea level rise, and model parameters be quantified and propagated to risk-relevant outputs?
- What numerical strategies enable high-resolution simulations at continental or city scales without prohibitive computational cost?

## My Role

- Numerical methods lead for shallow-water and storm surge models
- Core developer and maintainer of adaptive mesh refinement (AMR) coastal flow software
- Principal investigator / co-investigator on multiple federally funded coastal flooding projects
- Advisor and mentor to PhD students and postdocs developing next-generation flood models

My contributions focus on bridging theory, algorithms, and software while ensuring models remain usable by interdisciplinary teams and stakeholders.

## Methods & Technical Approach

This project combines several methodological threads:

- Depth-averaged and multilayer shallow water equations for storm surge and inundation
- Adaptive mesh refinement (AMR) to dynamically resolve coastlines, barriers, and urban features (e.g. {% cite MandliDawson.2014 BergerEtAl.2011 %})
- Finite-volume methods designed to handle dry states, wetting/drying, and complex bathymetry {% cite %}
- Coupling strategies for coastal–hydrologic interactions and compound flooding
- Uncertainty quantification using surrogate models, ensembles, and probabilistic frameworks
- High-performance computing for large-scale and ensemble simulations

These methods are implemented and tested through open-source software frameworks to ensure transparency, reproducibility, and long-term sustainability.

## Applications & Case Studies

Representative applications include:

- Hurricane-driven storm surge and inundation along U.S. coastlines
- Urban flood risk for critical infrastructure (e.g. New York City transportation systems; {% cite Miura.2025 Sarhadi.2024 %})
- Barrier island breaching and morphodynamic impacts on mainland flooding ({% cite 10.5194/nhess-25-3125-2025 %})
- Compound flooding from storm surge, tides, precipitation, and river discharge
- Climate change scenarios, including sea level rise and changing storm characteristics

Many studies are developed in collaboration with climate scientists, engineers, planners, and decision-makers to ensure relevance beyond academia.

## Outcomes

### Scientific Contributions

- Peer-reviewed advances in AMR methods for coastal and geophysical flows
- New numerical techniques for handling barriers, dry states, and multiscale dynamics

### Software

- **GeoClaw** – Open-source storm surge and tsunami modeling software with adaptive mesh refinement <https://github.com/clawpack/geoclaw>
- **PyClaw** – Python-based framework for solving hyperbolic PDEs and prototyping numerical methods <https://github.com/clawpack/pyclaw>
- Long-term development of open-source coastal flooding and storm surge modeling tools
- Widely used research and educational codes supporting reproducible science

### Impact

- Improved understanding of coastal flood hazards under present and future climates
- Decision-relevant flood maps and risk metrics for vulnerable coastal regions
- Training of students and early-career researchers in computational geoscience

## Funding & Collaboration

This work has been supported by funding from federal agencies including NSF, NOAA, DOE, and related programs, often in close collaboration with:

- Applied mathematicians and computational scientists
- Climate scientists and oceanographers
- Civil and coastal engineers
- Policy and stakeholder-facing research teams

Many projects involve multi-institutional collaborations linking academia, national labs, and operational partners.

## Status

**Ongoing**: This project continues to evolve, with current efforts emphasizing compound flooding, climate-driven risk assessment, scalable uncertainty quantification, and tighter integration with decision-support frameworks.

## Related

### Selected Publications

- Optimization of coastal protection {% cite Miura.2025 %}
- Climate Change Contributions to compound flooding {% cite Sarhadi.2024  %}
- Coastal flood hazards due to climate change {% cite Hemmati.2025 %}
- Coupled coastal-hydrologic modeling {% cite Hamidi.2025 %}

### Related Initiativs

- [NASA Sea Level Change Team](https://sealevel.nasa.gov)
- Extra-tropical storms (e.g. nor'easters)

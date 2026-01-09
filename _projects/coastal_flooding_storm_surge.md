---
layout: page
title: Coastal Flooding & Storm Surge Modeling
description: Development of high-resolution, adaptive numerical models for storm surge and coastal flooding, with applications to urban infrastructure, compound flooding, and climate-driven risk assessment.
img: assets/img/sandy_nyc/S12_L05_AT/surface_nyc.png
importance: 1
category: work
related_publications: true
tags: AMR, shallow water equations, uncertainty quantification, climate risk
---

---

_Adaptive numerical modeling of storm surge and coastal flooding, from algorithms and open-source software to climate-driven risk assessment in urban and coastal environments._

---

**Jump to:** [Methods](#methods--technical-approach) · [Applications](#applications--case-studies) · [Outcomes](#outcomes) · [References](#related)

---

# Overview

Coastal flooding driven by storm surge, tides, waves, and river inflows poses increasing risks to coastal communities and critical infrastructure. This project develops numerically robust, high-resolution models for coastal flooding that integrate advanced numerical methods with real-world geophysical complexity, enabling both scientific insight and actionable risk assessment.

My work in this area spans algorithm development, open-source software, and applied modeling, with applications ranging from hurricanes and tsunamis to compound flooding in urban environments under climate change. Much of this work is implemented through open-source modeling frameworks including [GeoClaw](https://github.com/clawpack/geoclaw) and [AMRClaw](https://github.com/clawpack/amrclaw), which are part of the broader [Clawpack](https://www.clawpack.org) ecosystem.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/S10_L00_AT/surface_nyc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/S10_L00_AT/currents_nyc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/S12_L05_AT/surface_nyc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/S12_L05_AT/currents_nyc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/surface_colorbar_horizontal.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/speed_colorbar_horizontal.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Hurricane Sandy simulations in the New York City region using <a href="https://github.com/clawpack/geoclaw">GeoClaw</a>.
Surface elevation (left) and flow speed (right) four hours before landfall.
Top: historical storm and mean sea level. Bottom: hypothetical scenario with +20% wind strength and +50 cm sea-level rise.
</div>

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

- Depth-averaged and multilayer shallow water equations <d-cite key="Mandli.2013"></d-cite> <d-cite key="Schwarzschild.2018"></d-cite> for storm surge and inundation
- Adaptive mesh refinement (AMR) to dynamically resolve coastlines, barriers, and urban features (e.g. {% cite MandliDawson.2014 %})
- Finite-volume methods designed to handle dry states, wetting/drying, and complex bathymetry {% cite Berger.2011 %}
- Coupling strategies for coastal–hydrologic interactions and compound flooding {% cite Hamidi.2025 %}
- Uncertainty quantification using surrogate models, ensembles, and probabilistic frameworks
- High-performance computing for large-scale and ensemble simulations

These methods are implemented and tested through open-source software frameworks to ensure transparency, reproducibility, and long-term sustainability.

## Applications & Case Studies

Representative applications include:

- Hurricane-driven storm surge and inundation along U.S. coastlines
- Urban flood risk for critical infrastructure (e.g. New York City transportation systems; {% cite Miura.2025 Sarhadi.2024 %})
- Barrier island breaching and morphodynamic impacts on mainland flooding {% cite Jeffries.2025 Hoagland.2023 %}
- Compound flooding from storm surge, tides, precipitation, and river discharge {% cite Hamidi.2025 Chegini.2022 Muñoz.2022 %}
- Climate change scenarios, including sea level rise and changing storm characteristics {% cite Sarhadi.2024 Hamidi.2025 %}

Together, these case studies emphasize the importance of resolving fine-scale coastal features while retaining regional context, particularly under nonstationary climate conditions. Many studies are developed in collaboration with climate scientists, engineers, planners, and decision-makers to ensure relevance beyond academia.

<div class="row justify-content-sm-left">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/fig6_b-1136.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 md-md-0">
        Changes in the return curves for Jamaica Bay NYC for the current climate (blue), projected climate in 2050 (orange), and projected climate in 2100 (red) from {% cite Sarhadi.2024 %}.
    </div>
</div>
<div class="row justify-content-sm-right">
    <div class="col-sm mt-3 mt-md-0">
        Flooding risk to lower Manhattan subway lines with number of openings into the subway from {% cite Miura.2025 %}.
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sandy_nyc/14ftHeightFloodBopenings-1159_m.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Outcomes

### Scientific Contributions

- Peer-reviewed advances in AMR methods for coastal and geophysical flows
- New numerical techniques for handling barriers, dry states, and multiscale dynamics

### Software

- **GeoClaw** – Open-source storm surge and tsunami modeling software with adaptive mesh refinement  
  <https://github.com/clawpack/geoclaw>
- **PyClaw** – Python-based framework for solving hyperbolic PDEs and prototyping numerical methods  
  <https://github.com/clawpack/pyclaw>

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
- Climate change contributions to compound flooding {% cite Sarhadi.2024  %}
- Coastal flood hazards due to climate change {% cite Hemmati.2025 %}
- Coupled coastal-hydrologic modeling {% cite Hamidi.2025 %}

### Related Initiatives

- [NASA Sea Level Change Team](https://sealevel.nasa.gov)
- Change in coastal surge risk from extra-tropical storms (e.g. nor’easters)
- [Assessing the public health risk due to tropical cyclone impacts on petrochemical facilities](https://www.nationalacademies.org/programs/GULF-GHRB-22-P-468/awarded-projects#)

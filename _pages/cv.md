---
layout: page
title: CV
permalink: /cv/
nav: true
nav_order: 5
description:
---

<div class="row">
  <div class="col-sm-8">
    <p><strong>Computational applied mathematician</strong> working on coastal flooding, storm surge, and geophysical hazards, with expertise in finite-volume methods, adaptive mesh refinement (AMR), uncertainty quantification, and high-performance scientific computing.</p>
    <p>
      <a class="btn btn-primary" href="{% link assets/pdf/cv_2026_01_07.pdf %}">Download full CV (PDF)</a>
      <a class="btn btn-outline-primary" href="{% link _pages/publications.md %}">Publications</a>
      <a class="btn btn-outline-primary" href="{% link _pages/projects.md %}">Research</a>
    </p>
  </div>
  <div class="col-sm-4">
    <ul>
      <li><strong>Now:</strong> Scientist IV, NSF NCAR</li>
      <li><strong>Location:</strong> Brooklyn, NY</li>
      <li><strong>PhD:</strong> Applied Mathematics (University of Washington)</li>
      <li><strong>GitHub:</strong> <a href="https://github.com/mandli">mandli</a></li>
    </ul>
  </div>
</div>

## Research highlights

- Develops numerical methods and scientific software for nonlinear hyperbolic PDEs, with emphasis on adaptive finite-volume schemes and transport-dominated systems.
- Leads and contributes to widely used open-source software for geophysical and hazard modeling, including **Clawpack**, **GeoClaw**, and **PyClaw**, supporting applications across academia, government, and industry.
- Conducts interdisciplinary research at the interface of applied mathematics, climate science, and coastal risk, with applications to storm surge, compound flooding, and infrastructure resilience.
- Collaborates with national laboratories, federal agencies, and international partners on decision-relevant modeling for climate and hazard impacts.

<p class="small">
  <strong>Selected metrics:</strong>
  2,100+ citations · h-index 24 · i10-index 36 ·
  <a href="https://scholar.google.com/citations?user=gsX-cv8AAAAJ" target="_blank" rel="noopener">
    Google Scholar
  </a>
</p>

## Appointments

- **NSF National Center for Atmospheric Research (NCAR)** — Scientist IV, CGD Lab (2025–present)
- **Flatiron Institute, Center for Computational Mathematics** — Research Scientist (2023–2024)
- **Columbia University**, Applied Physics & Applied Mathematics  
  Assistant Professor (2014–2019) · Associate Professor (2019–2023) · Research Scientist (2023)
- **University of Texas at Austin**, ICES — Postdoctoral Research Fellow / Research Associate (2011–2014)

## Open-source software (selected)

<div class="row">
  {% for s in site.data.software %}
  <div class="col-md-6 mb-3">
    <div class="card h-100">
      <div class="card-body">
        <h5 class="card-title">{{ s.name }}</h5>
        <p class="card-text">{{ s.blurb }}</p>
        <a class="card-link" href="{{ s.link_url }}" target="_blank" rel="noopener">{{ s.link_text }}</a>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

## Teaching & mentoring (at a glance)

- **Teaching areas:** numerical analysis, finite-volume methods, hyperbolic PDEs, uncertainty quantification, computational science.
- **Courses taught (selected):** Uncertainty Quantification; Finite Volume Methods for Hyperbolic PDEs; Numerical Methods for PDEs; Introduction to Numerical Methods.
- **Doctoral mentoring:** Advising and co-advising PhD students in applied mathematics, civil engineering, and climate science, with dissertations spanning adaptive methods, coastal flooding, and optimization of protective strategies.
- **Postdoctoral mentoring:** Mentored postdoctoral and early-career researchers now in research scientist and tenure-track faculty positions.

## Service (selected)

- Organizer and leadership roles in SIAM and applied mathematics communities, including SIAM New York-New Jersey-Pennsylvania Section conferences.
- Program and organizing committee member for international conferences in computational science and high-performance computing.
- Panelist and contributor to national discussions on climate risk, hazard modeling, and convergent research.
- Extensive editorial and peer-review service for journals in applied mathematics, computational science, and geophysics.

<hr/>
<p><strong>Full details:</strong> <a href="/assets/pdf/CV.pdf">Download CV (PDF)</a></p>

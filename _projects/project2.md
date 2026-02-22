---
layout: page
title: Orbital Stability
description: Mean motion resonances, chaotic diffusion, and the stability of planetary systems

img: assets/img/stability/poincare.png
importance: 2
category: research
related_publications: false
---
### Stability boundary for S-type orbits
As part of the work on the eccentricity cascade, I also study the dynamical stability of S-type planetary orbits, where a planet orbits one star in the presence of an external stellar companion. By modeling the planet–companion interaction as a sequence of discrete gravitational kicks, I show that the onset of instability can be understood as a transition to chaotic diffusion in the planet’s semimajor axis. This approach yields a simple, closed-form analytical criterion for long-term orbital stability, along with a characteristic instability timescale. The resulting stability boundary agrees well with classical numerical results, and provides a clear physical explanation for why S-type orbits become unstable as the companion’s eccentricity and proximity increase.

Paper link: <a href="https://iopscience.iop.org/article/10.3847/1538-4357/ae201b"> see Section 2 and Appendices</a>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stability/boundary.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stability/t_instab.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Comparison between our analytical stability criterion (Equation (8) in the paper) and the empirical stability boundary from Holman & Wiegert (1999). Right: Instability timescale as a function of the dimensionless parameter K, which quantifies the system's initial conditions. 
</div>


### Secular dynamics of compact planetary systems

Many exoplanet systems pack several planets into extremely tight orbits, right on the edge of instability. While the long-term ("secular") evolution of such systems is formally understood, the standard solutions are mathematically heavy and often offer little intuition, especially once more than two planets are involved. In this project, I focus on the compact three-planet case and show that the dynamics simplify dramatically when the planets are closely spaced.

In this limit, the planets' eccentricities can be decomposed into a small number of clean, geometrically intuitive modes. All planets share a conserved "center-of-mass eccentricity", while the remaining modes describe how eccentricity is exchanged between neighboring planets. This immediately explains why two-planet systems behave so simply, and why three-planet systems show richer behavior, including oscillations in the relative eccentricities that can slowly reshape stability boundaries.

We derive analytic expressions for these modes, explore when they remain accurate beyond the strict compact limit, and test them against full N-body simulations. The result is a clearer, more intuitive framework for understanding the secular evolution and stability of tightly packed planetary systems, and for connecting classical celestial mechanics to the architectures revealed by modern exoplanet surveys.
 
Paper link: <a href="https://iopscience.iop.org/article/10.3847/1538-4357/ad3af1">secular dynamics of compact three-planet systems</a>
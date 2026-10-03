---
title: First Ph.D. paper published in CMAME
date: '2023-10-13'
image: /images/news/2023-10-semi-implicit-thm-mpm.png
label: Comput. Methods Appl. Mech. Eng.
image_fit: cover
headline: A semi-implicit material point method for coupled thermo-hydro-mechanical simulation of saturated porous media in large deformation
summary: Jidu's first SCI paper from his Ph.D. at HKUST, a stabilized semi-implicit THM material point method for saturated porous media, was published in Computer Methods in Applied Mechanics and Engineering.
citation: '**Yu J.D.**, Zhao J.D.\*, Liang W.J., Zhao S.W. (2024). A semi-implicit material point method for coupled thermo-hydro-mechanical simulation of saturated porous media in large deformation. *Computer Methods in Applied Mechanics and Engineering*, 418, 116462.'
link: https://doi.org/10.1016/j.cma.2023.116462
---

This paper is the first SCI publication from Jidu's Ph.D. research at HKUST, and the foundation of the THM-coupled MPM framework that his later work on frozen soils and hydrate-bearing sediments builds upon.

Engineering systems such as geothermal energy and radioactive waste repositories involve coupled thermo-hydro-mechanical (THM) processes in porous media that can undergo large deformation. Conventional mesh-based methods struggle with mesh distortion in these problems.

In this work, we develop a stabilized material point method for THM problems in biphasic solid-fluid mixtures. A novel staggered solution scheme solves for four primary variables: solid displacement, liquid velocity, pore pressure and temperature. A semi-implicit fractional step approach handles both incompressible and weakly compressible fluids while avoiding pressure oscillations, using equal-order interpolation.

Benchmarks including the heating of a saturated half-space and thermally induced slope failure demonstrate the stability, accuracy and efficiency of the method in large-deformation THM problems.

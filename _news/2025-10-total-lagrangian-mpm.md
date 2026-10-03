---
title: Total-Lagrangian MPM for porous media published in IJNME
date: '2025-10-04'
image: /images/news/2025-10-total-lagrangian-mpm.png
label: Int. J. Numer. Methods Eng.
image_fit: cover
headline: A total-Lagrangian material point method for fast and stable hydromechanical modeling of porous media
summary: A collaborative study on a semi-implicit total-Lagrangian MPM that speeds up hydromechanical simulations of saturated porous media.
citation: Liang W.J., Chandra B., **Yu J.D.**, Yin Z.Y.\*, Zhao J.D. (2025). *International Journal for Numerical Methods in Engineering*, 126(19), e70135.
link: https://doi.org/10.1002/nme.70135
---

Conventional updated-Lagrangian MPM can be slow and unstable for hydromechanical analysis of saturated porous media.

This collaborative work presents a semi-implicit total-Lagrangian MPM. The fractional step method separates pore pressure from the kinematic fields, and the semi-implicit scheme avoids the small time steps imposed by permeability and fluid compressibility. Because shape functions are evaluated only once in the reference configuration, cell-crossing instabilities disappear and the system matrices keep a fixed structure, which allows an efficient Cholesky factorization.

Benchmarks show large speed-ups over conventional approaches while keeping accuracy.

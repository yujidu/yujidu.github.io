---
title: Virtual heat flux method published in IJNME
date: '2026-06-21'
image: /images/news/2026-06-virtual-heat-flux.png
label: Int. J. Numer. Methods Eng.
image_fit: cover
headline: A virtual heat flux method for simple and accurate Neumann thermal boundary imposition in the material point method
summary: A new way to impose heat-flux boundary conditions in the material point method without tracking the boundary, now published in the International Journal for Numerical Methods in Engineering.
citation: '**Yu J.D.**, Zhao J.D. (2026). *International Journal for Numerical Methods in Engineering*, 127(12), e70371.'
link: https://doi.org/10.1002/nme.70371
---

Thermal boundary conditions are hard to apply in the material point method (MPM): the background grid is fixed and regular, while the material boundary is curved, moving and constantly changing, so the two rarely line up.

In this paper we introduce the **virtual heat flux method (VHFM)**. Instead of locating the boundary explicitly, it builds a virtual flux field that already satisfies the prescribed boundary condition, which turns the boundary integral into a volume integral that MPM handles naturally. A unified form of this virtual field extends the idea to general Neumann boundary conditions.

Numerical tests with curved, moving and evolving boundaries show that the method is accurate and converges well while staying simple to implement and cheap to run, making it a practical building block for thermo-mechanical MPM simulations.

---
permalink: /
layout: archive
title: "Welcome to my homepage!"
excerpt: "Home"
author_profile: false
hero_image: berkeley.jpg
redirect_from: 
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher in the Department of Civil and Environmental Engineering at the **University of California, Berkeley**, working with [Prof. Kenichi Soga](https://geomechanics.berkeley.edu/people/soga/). My research develops high-fidelity computational methods for geomaterials in extreme environments, where coupled thermal, hydraulic, mechanical and chemical (THMC) processes drive large deformation and failure.

My work centers on the **material point method (MPM)** and its coupling with the discrete element method (DEM) and fluid solvers. I have developed fully coupled THM/THMC-MPM formulations and multiscale MPM-DEM frameworks to simulate freezing and thawing in permafrost, phase transition in methane hydrate-bearing sediments, and the geohazards they trigger, from thaw-induced landslides to submarine slope instability. This work has appeared in leading journals in computational and solid mechanics, including *JMPS*, *CMAME*, *IJNME*, *IJNAMG* and *Computers and Geotechnics*.

I received my Ph.D. in Civil Engineering from **HKUST** in 2025 under the supervision of [Prof. Jidong Zhao](https://jzhao.people.ust.hk/), and my B.Eng. and M.Eng. in hydraulic engineering from **Hohai University**. Before joining Berkeley, I was a postdoctoral researcher at HKUST, and I have been a visiting researcher at UC Berkeley and University College London.

**Research interests**
* Particle and hybrid numerical methods: MPM, DEM, MPM-DEM, MPM-FVM
* Multiphysics (THM/C) modeling of multiphase granular media, e.g., frozen soils and hydrate-bearing sediments
* Climate-driven geohazards: permafrost thaw, rainfall-induced landslides, hydrate dissociation-induced instability
* Geomechanics in extreme environments: submarine, deep underground and extraterrestrial
* Machine learning-aided multiscale and multiphysics modeling
* 3D printing of extrusion-based materials: rheology and numerical modeling

I am open to collaborations and academic opportunities.

<section class="home-section">
  <div class="home-section__head">
    <h2>News</h2>
    <a class="home-section__more" href="{{ '/news/' | relative_url }}">See more →</a>
  </div>
  {% include news-timeline.html count=5 %}
</section>

{% comment %}
  Homepage sections are hidden for now. Delete this comment tag and the
  matching endcomment at the bottom to show them again.
{% endcomment %}
{% comment %}
<section class="home-section">
  <div class="home-section__head">
    <h2>Research</h2>
    <a class="home-section__more" href="{{ '/research/' | relative_url }}">See more →</a>
  </div>
  <div class="research-list">
    <a class="research-item" href="{{ '/research/' | relative_url }}">
      <div class="research-item__media"><img src="{{ '/images/Thermal_slope.gif' | relative_url }}" alt="Failure of a thermal-sensitive slope" loading="lazy"></div>
      <div class="research-item__text">
        <h3>Thermo-hydro-mechanical coupled MPM for saturated porous media</h3>
        <p>A stabilized, efficient semi-implicit MPM with a four-variable <em>u-v-p-T</em> formulation for non-isothermal saturated porous media, handling both incompressible and weakly compressible fluids.</p>
      </div>
    </a>
    <a class="research-item" href="{{ '/research/' | relative_url }}">
      <div class="research-item__media"><img src="{{ '/images/ThawingFooting.gif' | relative_url }}" alt="Strip footing on unthawed and thawing ground" loading="lazy"></div>
      <div class="research-item__text">
        <h3>Coupled MPM for modelling freezing and thawing of porous media</h3>
        <p>Thermo-hydro-mechanical MPM for simulating freezing and thawing in granular soils, e.g. rapid penetration of a strip footing on unthawed vs. thawing ground.</p>
      </div>
    </a>
    <a class="research-item" href="{{ '/research/' | relative_url }}">
      <div class="research-item__media"><img src="{{ '/images/FT_cycles.gif' | relative_url }}" alt="THM responses during freeze-thaw cycles" loading="lazy"></div>
      <div class="research-item__text">
        <h3>Multiscale modeling of granular media subject to freeze-thaw cycles</h3>
        <p>Multiscale modeling of the coupled THM behavior of saturated porous media during repeated freeze-thaw cycles.</p>
      </div>
    </a>
    <a class="research-item" href="{{ '/research/' | relative_url }}">
      <div class="research-item__media"><img src="{{ '/images/Thermal_wave_E7.gif' | relative_url }}" alt="Wave propagation caused by thermal expansion" loading="lazy"></div>
      <div class="research-item__text">
        <h3>THM modeling of porous media with compressible fluid</h3>
        <p>Wave propagation caused by thermal expansion initiated from the boundaries, captured with an improved fractional step formulation.</p>
      </div>
    </a>
  </div>
</section>

<section class="home-section">
  <div class="home-section__head">
    <h2>Selected Publications</h2>
    <a class="home-section__more" href="{{ '/publications/' | relative_url }}">See more →</a>
  </div>
  {% include pub-list.html group="journal" count=5 %}
</section>

<section class="home-section">
  <div class="home-section__head">
    <h2>Education &amp; Experience</h2>
    <a class="home-section__more" href="{{ '/cv/' | relative_url }}">See more →</a>
  </div>
  <ul class="home-timeline">
    <li><span class="home-timeline__date">2025 – now</span><span><strong>Postdoctoral Researcher</strong>, HKUST</span></li>
    <li><span class="home-timeline__date">2024 – 2025</span><span><strong>Visiting Scholar</strong>, University of California, Berkeley</span></li>
    <li><span class="home-timeline__date">2021 – 2025</span><span><strong>Ph.D.</strong> in Civil Engineering, HKUST</span></li>
    <li><span class="home-timeline__date">2018 – 2021</span><span><strong>M.Eng.</strong> in Hydraulic Structure Engineering, Hohai University</span></li>
    <li><span class="home-timeline__date">2014 – 2018</span><span><strong>B.Eng.</strong> in Water Conservancy and Hydropower Engineering, Hohai University</span></li>
  </ul>
</section>
{% endcomment %}

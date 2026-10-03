---
permalink: /
layout: archive
title: "Welcome to my homepage!"
excerpt: "Home"
author_profile: true
header:
  image: berkeley.jpg
redirect_from: 
  - /about/
  - /about.html
---

I am Jidu Yu (Chinese: 于际都) and I was born and raised in [XuZhou](https://en.wikipedia.org/wiki/Xuzhou), a historical and cultural city in China. 

I obtained my PhD degree in Civil Engineering from the Hong Kong University of Science and Technology (HKUST) in 2025, and B.Eng and M.Eng degrees in Hydraulic Engineering from Hohai University (HHU) in 2018 and 2021, respectively. Now, I am a postdoctoral researcher at HKUST, supervised by [Prof Zhao Jidong](http://jzhao.people.ust.hk/).

My current research interest focuses on:
* Particle or mesh-free methods, and hybrid methods, e.g., MPM, DEM, MPM-DEM, MPM-FVM.
* Multiphysics modelling of multiphase granular soils, particularly for frozen soils and hydrate soils. 
* Climate-driven geohazards, e.g., rainfall-induced landslides, permafrost thaw-related problems.

<section class="home-section">
  <div class="home-section__head">
    <h2>Research</h2>
    <a class="home-section__more" href="{{ '/research/' | relative_url }}">See more →</a>
  </div>
  <div class="research-grid">
    <a class="research-card" href="{{ '/research/' | relative_url }}">
      <img src="{{ '/images/Thermal_slope.gif' | relative_url }}" alt="Failure of a thermal-sensitive slope" loading="lazy">
      <span>Thermo-hydro-mechanical coupled MPM for saturated porous media</span>
    </a>
    <a class="research-card" href="{{ '/research/' | relative_url }}">
      <img src="{{ '/images/ThawingFooting.gif' | relative_url }}" alt="Strip footing on thawing ground" loading="lazy">
      <span>Coupled MPM for modelling freezing and thawing of porous media</span>
    </a>
    <a class="research-card" href="{{ '/research/' | relative_url }}">
      <img src="{{ '/images/FT_cycles.gif' | relative_url }}" alt="Freeze-thaw cycles" loading="lazy">
      <span>Multiscale modeling of granular media subject to freeze-thaw cycles</span>
    </a>
    <a class="research-card" href="{{ '/research/' | relative_url }}">
      <img src="{{ '/images/Thermal_wave_E7.gif' | relative_url }}" alt="Thermal wave propagation" loading="lazy">
      <span>THM modeling of porous media with compressible fluid</span>
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

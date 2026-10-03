---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
hero_image: berkeley.jpg
---

<div class="research-rows">
  <article class="research-row">
    <div class="research-row__media">
      <div class="news-thumb">
        <div class="news-thumb__frame news-thumb__frame--contain"><img src="{{ '/images/Thermal_slope.gif' | relative_url }}" alt="Failure of a thermal-sensitive slope" loading="lazy"></div>
        <div class="news-thumb__label">Failure of a thermal-sensitive slope</div>
      </div>
    </div>
    <div class="research-row__body">
      <h2 class="research-row__title">Thermo-hydro-mechanical coupled MPM for saturated porous media</h2>
      <p>Stabilized and efficient material point method (MPM) algorithms for modelling the thermo-hydro-mechanical (THM) response of saturated porous media in large deformation.</p>
      <ul><li>Four-variable <em>u-v-p-T</em> formulation for non-isothermal saturated porous media</li><li>Semi-implicit solution scheme based on the fractional step method</li><li>Handles both incompressible and weakly compressible pore fluids</li></ul>
      <p class="research-row__paper">Key paper: <a href="https://doi.org/10.1016/j.cma.2023.116462" target="_blank" rel="noopener">CMAME 2024</a></p>
    </div>
  </article>
  <article class="research-row">
    <div class="research-row__media">
      <div class="news-thumb">
        <div class="news-thumb__frame news-thumb__frame--contain"><img src="{{ '/images/ThawingFooting.gif' | relative_url }}" alt="Strip footing on unthawed (left) vs. thawing (right) ground" loading="lazy"></div>
        <div class="news-thumb__label">Strip footing on unthawed (left) vs. thawing (right) ground</div>
      </div>
    </div>
    <div class="research-row__body">
      <h2 class="research-row__title">Coupled MPM for freezing and thawing of porous media</h2>
      <p>A three-phase THM-coupled MPM that captures phase change between ice and water and the large deformation that follows, for permafrost thaw and related geohazards.</p>
      <ul><li>Ice treated as part of the solid skeleton, with ice-saturation-dependent strength</li><li>Captures conduction- and convection-dominated thermal regimes</li><li>Applied to rapid footing penetration and thaw-induced failure</li></ul>
      <p class="research-row__paper">Key paper: <a href="https://doi.org/10.1002/nag.3794" target="_blank" rel="noopener">IJNAMG 2024</a></p>
    </div>
  </article>
  <article class="research-row">
    <div class="research-row__media">
      <div class="news-thumb">
        <div class="news-thumb__frame news-thumb__frame--contain"><img src="{{ '/images/FT_cycles.gif' | relative_url }}" alt="THM response of saturated porous media during freeze-thaw cycles" loading="lazy"></div>
        <div class="news-thumb__label">THM response of saturated porous media during freeze-thaw cycles</div>
      </div>
    </div>
    <div class="research-row__body">
      <h2 class="research-row__title">Multiscale modeling of granular media under freeze-thaw cycles</h2>
      <p>A hierarchical MPM-DEM framework that links grain-scale ice bonding and melting to the macroscopic coupled THM behavior of frozen granular soils.</p>
      <ul><li>DEM representative volume element embedded at each material point</li><li>Reveals how ice bonding strengthens soil and how melting reduces bearing capacity</li></ul>
      <p class="research-row__paper">Key paper: <a href="https://doi.org/10.1016/j.compgeo.2024.106349" target="_blank" rel="noopener">Comput. Geotech. 2024</a></p>
    </div>
  </article>
  <article class="research-row">
    <div class="research-row__media">
      <div class="news-thumb">
        <div class="news-thumb__frame news-thumb__frame--contain"><img src="{{ '/images/Thermal_wave_E7.gif' | relative_url }}" alt="Waves from thermal expansion at the left and bottom boundaries" loading="lazy"></div>
        <div class="news-thumb__label">Waves from thermal expansion at the left and bottom boundaries</div>
      </div>
    </div>
    <div class="research-row__body">
      <h2 class="research-row__title">THM modeling of porous media with compressible fluid</h2>
      <p>An improved fractional step MPM that accounts for pore-fluid compressibility and thermal effects, capturing pressure shock waves under mechanical or thermal loading.</p>
      <ul><li>Node-based implicit scheme for the intermediate variables</li><li>Extends naturally to three-phase porous media</li></ul>
      <p class="research-row__paper">Key paper: <a href="https://doi.org/10.1016/j.cma.2025.118100" target="_blank" rel="noopener">CMAME 2025</a></p>
    </div>
  </article>
</div>

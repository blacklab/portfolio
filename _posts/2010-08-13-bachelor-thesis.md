---
layout: portfolio_entry
title: "Bachelor's Thesis: Offline BRDF Computation for Microscale Volumes"
tags: "Study Research"
summary: "In this thesis I implemented algorithms to pre-calculate the behaviour of light in microscale magnitudes which can be described by Bidirectional Reflectance Distribution Functions (BRDF)."
---
#### Abstract
While the physics of light are well known, computer scientists still struggle to use this knowledge for real-time rendering of photo realistic images. Especially the phenomena of light in microscale magnitudes are hard to simulate or estimate in real-time.

This thesis will propose a way to pre-calculate the behaviour of light in microscale magnitudes which can be described by Bidirectional Reflectance Distribution Functions (BRDF). The described pre-calculation or offline computation will be specialized on volumes.

A modified Path Tracer named Photon Tracer will be used to compute BRDF data offline. This means the data is calculated and stored and can then be later used to render more realistic images in real-time.

#### Details
The offline rendering process was implemented for [Voreen](http://voreen.uni-muenster.de/) in C/C++.

You can download the full thesis [here]({{ site.url }}/downloads/Bachelors_Thesis_Karsten_Jeschkies.pdf).

<ul class="thumbnails">
  <li class="span4">
    <a href="{{ site.url }}/assets/img/zebra_luma_raytraced.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="Ray Traced" src="{{ site.url }}/assets/img/zebra_luma_raytraced.png">
    </a>
  </li>
  <li class="span4">
    <a href="{{ site.url }}/assets/img/zebra_brdf_top.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="BRDF" src="{{ site.url }}/assets/img/zebra_brdf_top.png">
    </a>
  </li>
</ul>

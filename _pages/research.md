---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Our research focuses primarily on high order numerical methods for both linear and nonlinear hyperbolic partial differential equations (PDEs) which are provably reliable and efficient. A significant advantage of high order methods for time-dependent hyperbolic PDEs is their low numerical dispersion and dissipation compared to low order methods, which allows for the high-fidelity propagation of waves, vortices, and subgrid features over long time and length scales. 

Our work focuses on four main areas: 
- [**Nonlinear conservation laws**](#entropy-stable-methods-for-nonlinear-conservation-laws)
- [**Wave propagation in heterogeneous media**](#efficient-high-order-methods-for-wave-propagation)
- [**Simulations on curved geometries**](#efficient-high-order-dg-methods-on-curved-meshes)
- [**Unstructured hybrid meshes**](#efficient-high-order-methods-for-wave-propagation)

You can find a complete list of publications on my [**Google Scholar page**](https://scholar.google.com/citations?user=nA29Z5YAAAAJ&hl=en/), or on arXiv under "Jesse Chan". 

### Entropy stable methods for nonlinear conservation laws

Nonlinear conservation laws govern the behavior of fluid phenomena such as compressible or shallow water flows, and are notoriously sensitive to problems of instability. The presence of numerical dissipation imparts stability to numerical simulations.  Thus, for nonlinear conservation laws, the attractive low numerical dissipation of high order methods becomes a double-edged sword, rendering many high order methods unstable without additional ad-hoc regularization such as artificial viscosity, slope limiting, or filtering.

Discretely entropy stable methods aim 

- ESDG Gauss preprint
- ESDG curved
- ESDG

[*Back to top*](#top)

### Efficient high order methods for wave propagation



- BBWADG
- Elastic WADG media
- WADG heterogeneous media
- BBDG

[*Back to top*](#top)

### Efficient high order DG methods on curved meshes

- WADG curved
- BIDG
- IGA-DG

[*Back to top*](#top)

### High order DG methods on hybrid meshes 

Appropriate choices of basis

- Hybridg
- BBPyr
- Orthogonal pyr basis.
- Pyr nodes

[*Back to top*](#top)

{% include base_path %}

{% comment %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}

{% comment %}
Our research focuses on computational mechanics and the efficient numerical solution of partial differential equations. Recent work in this group has focused on accurate high order methods for time-dependent wave propagation and fluid dynamics, as well as their efficient implementation on Graphics Processing Units (GPUs). 
{% endcomment %}


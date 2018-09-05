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
- [**Simulations on curved geometries**](#efficient-and-stable-high-order-methods-on-curved-meshes)
- [**Finite element methods on hybrid meshes**](#finite-element-methods-on-hybrid-meshes)

You can find a complete list of publications on my [**Google Scholar page**](https://scholar.google.com/citations?user=nA29Z5YAAAAJ&hl=en/), or on my [**CV**](../files/jcv.pdf). Selected preprints are also available on arXiv under "Jesse Chan".

### Entropy stable methods for nonlinear conservation laws

Nonlinear conservation laws govern the behavior of fluid phenomena such as compressible or shallow water flows. Numerical simulations of such phenomena are sensitive to problems of instability. For low order methods, this instability can be offset by the presence of numerical dissipation, which decreases accuracy but has a stabilizing effect on simulations.  However, the low numerical dissipation of high order methods becomes a double-edged sword, reducing robustness and rendering many high order discretizations unstable without additional regularization such as artificial viscosity, slope limiting, or filtering. This regularization is typically ad-hoc and can reduce accuracy. 

Discretely entropy stable methods aim to restore stability while maintaining high order accuracy by ensuring that numerical solutions satisfy a physically consistent entropy inequality. This entropy inequality serves as a generalization of the conservation or dissipation of energy to nonlinear PDEs, and ensures that the numerical solution does not blow up so long as the solution is physical (e.g. positive density, pressure). 

Below is a horizontally periodic version of a compressible inviscid weak shock-vortex interaction from [Shu 1998](https://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19980007543.pdf) using an entropy stable method on a quadrilateral mesh of 100-by-50 elements of polynomial degree 4. No regularization is applied apart from a consistent [interface dissipation](https://www.sciencedirect.com/science/article/pii/S0021999116306477), yet the solution remains stable in the presence of the shock. 

<img src="../files/shockVortexTp3.png" width="450" />
<img src="../files/shockVortexTp7.png" width="450" />

#### Selected relevant papers:

- [On discretely entropy conservative and entropy stable discontinuous Galerkin methods](https://www.sciencedirect.com/science/article/pii/S0021999118301153)
- [Discretely entropy stable weight-adjusted discontinuous Galerkin methods on curvilinear meshes](https://arxiv.org/abs/1805.10934)

[*Back to top*](#top)

### Efficient high order methods for wave propagation



#### Selected relevant papers: 

- [Bernstein-Bezier weight-adjusted discontinuous Galerkin methods for wave propagation in heterogeneous media](https://arxiv.org/abs/1808.08645)
- [Weight‐adjusted discontinuous Galerkin methods: matrix‐valued weights and elastic wave propagation in heterogeneous media](https://onlinelibrary.wiley.com/doi/abs/10.1002/nme.5720)
- [Weight-Adjusted discontinuous Galerkin methods: wave propagation in heterogeneous media](https://epubs.siam.org/doi/abs/10.1137/16M1089186)
- [GPU-Accelerated Bernstein-Bezier Discontinuous Galerkin Methods for Wave Problems](https://epubs.siam.org/doi/abs/10.1137/15M1053542)

[*Back to top*](#top)

### Efficient and stable high order methods on curved meshes

#### Selected relevant papers: 

- WADG curved
- BIDG
- IGA-DG

[*Back to top*](#top)

### Finite element methods on hybrid meshes 

<img src="../files/hybrid_elems.png" width="850" />

Appropriate choices of basis

It is generally straightforward to construct high order finite element spaces on hexahedral, tetrahedral, and prismatic elements. However, constructing high order approximation spaces on pyramids is challenging 

- [GPU-accelerated discontinuous Galerkin methods on hybrid meshes](https://www.sciencedirect.com/science/article/pii/S0021999116300353)
- [A Short Note on a Bernstein-Bezier Basis for the Pyramid](https://epubs.siam.org/doi/abs/10.1137/15M1036397?journalCode=sjoce3)
- [Orthogonal bases for vertex-mapped pyramids](https://epubs.siam.org/doi/abs/10.1137/15M1011408)
- [hp finite element trace inequalities for the pyramid](https://www.sciencedirect.com/science/article/pii/S0898122115000358)
#- [A comparison of high order interpolation nodes for the pyramid](https://epubs.siam.org/doi/abs/10.1137/141000105)

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


---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


{% comment %}
Our research focuses on computational mechanics and the efficient numerical solution of partial differential equations. Recent work in this group has focused on accurate high order methods for time-dependent wave propagation and fluid dynamics, as well as their efficient implementation on Graphics Processing Units (GPUs). 
{% endcomment %}

Our research focuses primarily on numerical methods for both linear and nonlinear hyperbolic partial differential equations which are provably reliable, accurate, and efficient. 

You can find a complete list of publications on my [**Google Scholar page**](https://scholar.google.com/citations?user=nA29Z5YAAAAJ&hl=en/), or on arXiv under "Jesse Chan". 

### Entropy stable methods for nonlinear conservation laws

Nonlinear conservation laws 

- ESDG
- ESDG curved
- ESDG Gauss preprint
- 

### Efficient high order DG methods on curved geometries

- WADG curved
- BIDG
- 

### Efficient high order methods for wave propagation

- BBDG
- BBWADG
- Hermite
- 

### High order DG methods on hybrid meshes 

Appropriate choices of basis
- Prism DG
- Hybridg
- BBPyr
- Orthogonal pyr basis.
- Pyr nodes


{% include base_path %}

{% comment %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}

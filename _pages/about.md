---
permalink: /
title: "Home"
excerpt: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Research interests: 

Our group focuses on computational mechanics and the efficient numerical solution of partial differential equations. Recent work in this group has focused on provably stable and high ordeer accurate methods for time-dependent wave propagation and fluid dynamics, as well as their efficient implementation on Graphics Processing Units (GPUs). 

We gratefully acknowledge the support of the NSF (DMS-1719818 and DMS-1712639) in making this work possible.

## Recent news:

* February 2019: our preprint "Skew-symmetric entropy stable modal discontinuous Galerkin formulations" is as an [arXiv preprint](https://arxiv.org/abs/1902.01828). We construct DG formulations which retain entropy stability under relaxed quadrature accuracy, which are applicable to hybrid meshes with mixed element types. 
* September 2018: our preprint "Efficient entropy stable Gauss collocation schemes" is available as an [arXiv preprint](https://arxiv.org/abs/1809.01178). Entropy stable collocation-DG schemes on tensor product elements typically utilize Gauss-Lobatto quadratures. We extend entropy stable collocation schemes to more accurate Gauss quadratures, which improve error significantly on curved meshes. 
* September 2018: our preprint "Leapfrog Time-stepping for Hermite methods", which describes a high order extension of the well-known Yee-scheme for time-domain wave propagation, is available as an [arXiv preprint](https://arxiv.org/abs/1808.10481). 
* August 2018: Kaihang Guo successfully defended his MA thesis on low-complexity GPU-accelerated DG methods for wave propagation in media with sub-cell heterogeneities. This work is available online in an [arXiv preprint](https://arxiv.org/abs/1808.08645).
* August 2018: Jesse Chan is featured in the CAAM [video](https://www.youtube.com/watch?v=lMfHpvXGPAY) for the School of Engineering.
* June 2018: our paper on [discretely entropy stable DG methods](https://www.sciencedirect.com/science/article/pii/S0021999118301153) is now online. We show how to generalize the construction of discretely entropy stable methods to ``modal'' DG formulations. The resulting formulations extend semi-discrete entropy stability theory to arbitrary bases and standard finite element quadrature rules.
* May 2018: our paper on [explicit time-stepping isogeometric methods](https://www.sciencedirect.com/science/article/pii/S0045782518300240) is now online. In this paper, we show how to efficiently combine isogeometric finite elements with explicit time-stepping while avoiding the inversion of a dense mass matrix. These methods also have the advantage of a better CFL constant at high orders of approximation.
* Jan 2018: Kaihang Guo receives the [K2i fellowship](https://caamweb.rice.edu/news/k2i-fellowships-2017) from the Ken Kennedy Institute.
* Jan 2018: our paper on [provably stable DG methods for elasticity with sub-cell heterogeneities](https://onlinelibrary.wiley.com/doi/abs/10.1002/nme.5720) is available online. This work extends the "weight-adjusted mass matrix" (generalized mass lumping) to matrix-valued weights and applies it to elastic wave propagation. By factoring material coefficients into the mass matrix, we simplify the formulation of stable DG methods for both isotropic and anisotropic media.


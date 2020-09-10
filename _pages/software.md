---
layout: single
title: "Software"
permalink: /software/
author_profile: true
---

I maintain two Julia packages which reproduce functionality from the Matlab codes from [Nodal Discontinuous Galerkin Methods](https://link.springer.com/book/10.1007/978-0-387-72067-8) by Hesthaven and Warburton.
- [NodesAndModes.jl](https://github.com/jlchan/NodesAndModes.jl): a registered Julia package which provides interpolation and quadrature nodes on various reference elements.  
- [StartUpDG.jl](https://github.com/jlchan/StartUpDG.jl): constructs physical mesh data structures given reference element data. Simple uniform meshes are also included.

I also maintain two Julia packages for entropy stable methods and flux differencing:
- [EntropyStableEuler.jl](https://github.com/jlchan/EntropyStableEuler.jl): implementation of entropy conservative and kinetic-energy preserving fluxes of [Chandrashekar](https://arxiv.org/abs/1209.4994) for the compressible Euler equations.
- [FluxDiffUtils.jl](https://github.com/jlchan/FluxDiffUtils.jl): functions for the efficient computation of Hadamard product in flux differencing, as well as Jacobian matrices for flux differencing discretizations. Specializes to either dense or sparse matrix operators. 


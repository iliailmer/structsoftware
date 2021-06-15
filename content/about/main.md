Title: Structural Identifiability Software
Date: 2021-01-22 11:00
Category: About

A collection of links to software projects related to the question of structural identifiability in dynamical systems.

1. [Structural Identifiability Analyzer (SIAN)](https://github.com/pogudingleb/SIAN/).
   
    * A Maple implementation of the Structural Identifiability Analyzer [1, 2]. This program requires Maple 2020.1 or later for best results. The program allows to determine global and local identifiability properties for parameters in dynamical systems with a fixed probability of correctness. The program takes advantage of Maple's fast Groebner basis computation and can be run in a reasonable time on a personal laptop.

2. [SIAN-Julia](https://github.com/alexeyovchinnikov/SIAN-Julia)
    * This is the open-source implementation of the SIAN algorithm in Julia. The main advantage is that it requires no paid software to work with, only the free Julia version 1.5.0 and higher. The program takes advantage of GrobnerBasis.jl package (see [here](https://github.com/ederc/GroebnerBasis.jl)). For faster computation, we provide the ability to set a positive prime characteristic to speedup Groebner Basis calculation. Note that this may loosen the guarantee of correctness.

3. [Structural Identifiability Toolbox](https://maple.cloud/app/6509768948056064/Structural+Identifiability+Toolbox)
    * This is a free version of the Maple package, it provides access to Maple code without the need to install it. In addition to structural identifiability, the app provides information about identifiable functions of parameters as described in [3].

## References

[1] [Global Identifiability of Differential Models](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpa.21921), Communications on Pure and Applied Mathematics, Volume 73, Issue 9, Pages 1831-1879, 2020.

[2] [SIAN: software for structural identifiability analysis of ODE models](https://doi.org/10.1093/bioinformatics/bty1069) (Bioinformatics, Volume 35, Issue 16, Pages 2873–2874, 2019)

[3] [Computing all identifiable functions for ODE models](https://arxiv.org/abs/2004.07774), a paper with implementation located [here](https://github.com/pogudingleb/AllIdentifiableFunctions).
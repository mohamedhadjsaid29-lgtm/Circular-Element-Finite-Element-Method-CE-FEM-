# Circular Element Finite Element Method (CE-FEM) Engine

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23161240.svg)](https://doi.org/10.5281/zenodo.23161240)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

CE-FEM is a novel computational mechanics framework that replaces classical polynomial shape functions and Gauss quadrature with an exact geometric circle-to-ellipse transformation ($\pi a b \equiv \pi R_0^2$).

## Core Features
- **Shape-Function-Free Kinematics:** Direct strain extraction from cardinal nodal differences.
- **Exact Area/Volume Invariance:** Mass preservation to $10^{-16}$ double-precision machine epsilon.
- **$O(h^2)$ Hourglass-to-Gradient Enhancement:** Physical bending stiffness without numerical integration.
- **Multi-Physics Coverage:** Structural elasticity, Venturi flows, NACA 4412 wing aerodynamics, Pascal hydraulic jacks, and thermal smoke plumes.

## Citation
If you use or adapt this code in your research, please cite the Zenodo publication:
> Hadj Said, Mohamed. (2026). *Circular Element Finite Element Method (CE-FEM): A Purely Geometric, Area-Preserving Continuum Mechanics Framework*. Zenodo. https://doi.org/10.5281/zenodo.23161240

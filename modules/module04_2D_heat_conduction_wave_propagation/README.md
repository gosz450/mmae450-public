# Module 4: Two-Dimensional Heat Conduction and Wave Propagation

In the previous modules, we focused on one-dimensional models to develop core ideas in discretization, linear systems, and time integration. In this module, we extend those ideas to **two spatial dimensions** and examine how the underlying physics strongly influences both the numerical method and the computational cost.

The module is divided into two closely related parts:

1. **Two-dimensional heat conduction**, a diffusive process governed by a parabolic partial differential equation.
2. **Wave propagation**, a fundamentally different physical phenomenon governed by a hyperbolic partial differential equation.

Although both problems are posed on two-dimensional spatial domains, they lead to very different numerical behavior, stability constraints, and solver requirements. Understanding this contrast is one of the main goals of the module.

---

## Part I: Two-Dimensional Heat Conduction

We begin by extending the one-dimensional heat equation to two spatial dimensions. Using finite differences on a rectangular grid, we derive the classic **five-point stencil** approximation of the Laplacian and show how steady and transient problems lead to large, sparse algebraic systems.

Key topics include:
- The 2D heat equation and the Laplace equation
- Rectangular grids and index notation \((i,j)\)
- The five-point finite-difference stencil
- Steady-state conduction as a sparse linear system
- Gauss–Seidel iteration applied directly to the grid
- FTCS time integration in two dimensions
- Stability restrictions and time-step selection

We emphasize how two-dimensional problems dramatically increase the number of unknowns and motivate the use of iterative solvers.

---

## Part II: Wave Propagation in Two Dimensions

The second part of the module introduces **wave propagation**, where disturbances travel with finite speed and clear directionality. This behavior contrasts sharply with the smooth, diffusive spreading seen in heat conduction.

Topics include:
- The 2D wave equation
- Physical interpretation of wave speed and characteristics
- Explicit time integration schemes
- CFL (Courant–Friedrichs–Lewy) stability conditions
- Differences between parabolic and hyperbolic PDEs
- Numerical artifacts such as dispersion and reflection

By comparing heat conduction and wave propagation side by side, we highlight how the governing physics dictates the numerical strategy.

---

## Learning Objectives

After completing this module, you should be able to:

- Formulate the 2D heat equation and wave equation on rectangular domains
- Construct finite-difference grids and index mappings in two dimensions
- Derive and implement the five-point stencil for the Laplacian
- Solve steady 2D heat conduction problems using Gauss–Seidel iteration
- Implement explicit time-stepping schemes in two dimensions
- Analyze stability constraints for diffusive and wave problems
- Explain why different physical models require different numerical approaches

---

## Module Materials

This module includes:
- Lecture slides covering theory and numerical formulation
- Jupyter notebooks demonstrating:
  - Steady 2D heat conduction
  - Transient heat diffusion
  - Wave propagation and stability effects
- Homework assignments focused on:
  - Transient heat conduction in a rectangular plate
  - Interpretation of numerical results and stability behavior

---

## Big Picture

Two-dimensional problems mark a turning point in computational
mechanics. Even simple geometries lead to large systems that cannot be
solved efficiently by hand or by direct methods alone. At the same time,
the contrast between heat conduction and wave propagation illustrates a
central theme of this course:

> **Numerical methods are inseparable from the physics they
> approximate.**

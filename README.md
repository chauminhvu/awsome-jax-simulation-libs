# awsome-jax-simulation-libs
A selection of high-quality, actively maintained JAX-based libraries tailored for numerical simulations including Finite Element Analysis (FEA), Computational Fluid Dynamics (CFD), and more.

JAX is a library for high-performance numerical computing and machine learning research that leverages `XLA` to compile and run `NumPy` programs on GPUs and TPUs. JAX also provides composable function transformations for automatic differentiation, vectorization, parallelization, and more.

# Project table

| Library Name   | License         | Documentations | FEM | CFD | DEM | Mul-Phy | ML | DO | PFM | LBM | MD |
|----------------|---------------- | -------------- | --- | --- | --- | ------------ | -- | -- | --- | --- | -- |
| [jax-am](https://github.com/tianjuxue/jax-am) <br> ![Github Star](https://img.shields.io/github/stars/tianjuxue/jax-am) <br> ![Github Fork](https://img.shields.io/github/forks/tianjuxue/jax-am) | ![License](https://img.shields.io/github/license/tianjuxue/jax-am) | Notebooks, demos, PDF | - | 🟢 | 🟢 | - | - | - | 🟢 | 🟢 | - |
| [jax-fem](https://github.com/deepmodeling/jax-fem) <br> ![Github Star](https://img.shields.io/github/stars/deepmodeling/jax-fem) <br> ![Github Fork](https://img.shields.io/github/forks/deepmodeling/jax-fem) | ![License](https://img.shields.io/github/license/deepmodeling/jax-fem) | Demos  | 🟢 | - | - | 🟢 | 🟢 | 🟢 | - | - |  - |
| [JAX-Fluids](https://github.com/tumaer/JAXFLUIDS) <br> ![Github Star](https://img.shields.io/github/stars/tumaer/JAXFLUIDS) <br> ![Github Fork](https://img.shields.io/github/forks/tumaer/JAXFLUIDS) | ![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg) | Webdocs, notebooks, demos  | - | 🟢 | - | - | 🟢 | 🟢 | - | - |  - |
| [jax-cfd](https://github.com/google/jax-cfd) <br> ![Github Star](https://img.shields.io/github/stars/google/jax-cfd) <br> ![Github Fork](https://img.shields.io/github/forks/google/jax-cfd) | ![License](https://img.shields.io/github/license/google/jax-cfd) | Notebooks, demos  | - | 🟢 | - | - | 🟢 | - | - | - |  - |
| [XLB](https://github.com/Autodesk/XLB) <br> ![Github Star](https://img.shields.io/github/stars/Autodesk/XLB) <br> ![Github Fork](https://img.shields.io/github/forks/Autodesk/XLB) | ![License](https://img.shields.io/badge/License-Apache_2.0-green.svg) | Demos  | - | 🟢 | - | - | 🟢 | - | - | 🟢 |  - |
| [jax-md](https://github.com/jax-md/jax-md) <br> ![Github Star](https://img.shields.io/github/stars/jax-md/jax-md) <br> ![Github Fork](https://img.shields.io/github/forks/jax-md/jax-md) | ![License](https://img.shields.io/github/license/jax-md/jax-md) | YouTube, Notebooks, demos  | - | - | - | - | 🟢 | - | - | - |  🟢 |

# Support educational repository
- [machine-learning-and-simulation](https://github.com/Ceyron/machine-learning-and-simulation) ![Github Star](https://img.shields.io/github/stars/Ceyron/machine-learning-and-simulation) ![Github Fork](https://img.shields.io/github/forks/Ceyron/machine-learning-and-simulation) 


## Domains
- FEM: Finite Element Method is a numerical method for solving partial differential equations (PDEs) that arise from modeling physical phenomena, such as heat transfer, fluid flow, stress, deformation, etc. FEM involves discretizing the domain into finite elements and applying variational or Galerkin methods to obtain a system of linear or nonlinear equations that can be solved using various techniques
- CFD: Computational Fluid Dynamics is a branch of fluid mechanics that uses numerical methods and algorithms to analyze and simulate the behavior of fluids, such as gases and liquids, and their interactions with solid boundaries, heat sources, chemical reactions, etc. CFD involves solving the Navier-Stokes equations or their simplified versions, such as the Euler equations or the Reynolds-averaged Navier-Stokes equations, using various discretization and solution methods.
- DEM: Discrete Element Method is a numerical technique for modeling the motion and interaction of a large number of discrete particles, such as granular materials, powders, or rocks. DEM accounts for the contact forces, friction, cohesion, and collision between the particles, and can be coupled with other methods, such as CFD or FEA, to model multiphysics problems.
- Mul-Phy: Multi-physics is a term that refers to the simulation of systems that involve multiple physical phenomena or domains, such as fluid-structure interaction, electro-mechanical coupling, or thermo-mechanical coupling
- ML: ML-based Surrogate Model is a machine learning approach for approximating complex systems or phenomena that are difficult or expensive to simulate directly. Surrogate models can be used to optimize, analyze, or understand the behavior of the original system, while reducing the computational cost and time. Surrogate models can be based on various types of machine learning models, such as neural networks, Gaussian processes, or polynomial chaos expansions.
- DO: Design Optimization is a process of finding the best design parameters that satisfy certain objectives and constraints, such as minimizing the cost, maximizing the performance, or improving the reliability of a system. Design optimization can be applied to various engineering problems, such as structural design, fluid dynamics, or additive manufacturing.
- PFM: Phase Field Method is a numerical technique for modeling the evolution of microstructures in materials, such as phase transitions, grain growth, solidification, or fracture. PFM uses a set of continuous variables, called phase fields, to represent the spatial distribution and orientation of different phases or defects in the material. PFM can capture complex phenomena, such as nucleation, coarsening, or anisotropy, using a set of coupled PDEs.
- LBM: Lattice Boltzmann Method is a numerical method for simulating fluid flow and transport phenomena, such as heat transfer, diffusion, or reaction. LBM is based on a simplified version of the Boltzmann equation, which describes the statistical behavior of a gas of particles. LBM uses a regular lattice to discretize the space and time, and a set of discrete velocities to discretize the particle distribution function. LBM can handle complex geometries, multiphase flows, and nonlinear effects, using a simple and efficient algorithm.
- MD: Molecular Dynamics is a numerical method for simulating the motion and interaction of atoms and molecules in a system, such as a protein, a crystal, or a gas. MD uses classical mechanics or quantum mechanics to model the forces and potentials between the particles, and integrates the equations of motion to obtain the trajectories and velocities of the particles. MD can reveal the structural, dynamical, and thermodynamical properties of the system at different time and length scales.

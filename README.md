# Entropy-Stable DGSEM for Burgers’ Equation

A Python research scaffold for studying entropy conservation and stability in a one-dimensional discontinuous Galerkin spectral element method (DGSEM).

## Numerical experiments

- Construct Legendre–Gauss–Lobatto nodes, quadrature weights and differentiation matrices, then check the discrete summation-by-parts identity.
- Test convergence on linear advection before moving to nonlinear fluxes.
- Reproduce a discrete entropy residual in a standard collocated discretisation of Burgers’ equation and test how entropy-conservative flux differencing changes that residual.
- Compare the evolution of discrete entropy in multi-element simulations using different volume and interface fluxes.
- Compare Roe and Godunov fluxes on a separate finite-volume test with expansion data.

The notebook is a scaffold for reproducing and extending these experiments. The examples document the behaviour observed in the configurations tested.

Developed during undergraduate research at the University of Warwick with Dr Andreas Dedner.

## Run the notebook

Install `jupyter`, `numpy` and `matplotlib`. Open `dgsem_scaffold.ipynb` and run the cells in order.

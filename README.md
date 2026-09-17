# MHD Waves Numerical Solver
Numerical solvers and mathematical derivation for linear MHD waves in a magnetic flux tube using Python.

## Project Description:
The aim is investigating linear Magnetohydrodynamic (MHD) waves within a magnetic flux tube using a cylindrical coordinate system. Through the ideal MHD model, the project studies the physical transitions between different waves regimes.

## Methodology:
* **Mathematical Derivation:** The dispersion relation for trapped MHD was derived applying the boundary conditions for displacement and pressure (Type I and Type II modified and Bessel functions were employed)
* **Numerical Root-Finding:** created a numerical algorithm in Python (`scipy.optimize.brentq`) to solve the non-linear dispersion relations
* **Dispersion:** computed the dimensionless speed against the dimensionless wavenumber to study the behavior of kink and sausage waves
* **Eigenfunction Visualization:** Modeled and plotted the radial profile of the normalized total pressure perturbations to study the trapped nature of waves across the internal and external plasma

## Tools:
* **Language:** Python
* **Libraries:** `numpy`, `scipy`, `matplotlib`
* **Core competencies:** Applied Mathematics, Magnetohydrodynamics(MHD), Numerical Simulations, Complex Modeling

## Repository Contents:
* `Waves and Instabilities Numerical Solver.ipynb`: Jupyter Notebook containing the numerical implementations
* `MHD Waves and Instabilities numerical derivations.pdf`: report containing the physical assumptions, mathematical proofs and analysis of the results


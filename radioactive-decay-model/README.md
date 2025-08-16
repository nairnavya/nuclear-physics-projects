# Computational Modeling of a Radioactive Decay Chain

## Summary

In this project, I implement and compare two methods for solving a three-component radioactive decay chain ($N_{A} \rightarrow N_{B} \rightarrow N_{C}$): a direct analytical solution and a numerical approximation using the Explicit Euler method. By plotting both results, I validate the accuracy of the computational model.

A comprehensive report detailing the underlying physics is available in the `/report/` directory.

## Key Features

- **Solve Analytically:** Implements the exact mathematical equations to find the true solution for the decay chain.
- **Solve Numerically:** Approximates the system's evolution using the Explicit Euler forward difference method.
- **Simulate Scenarios:** Easily customizes initial conditions and half-lives via a simple CSV input file.
- **Validate Results:** Plots both solutions on the same axes to visually demonstrate the numerical model's accuracy.

## How to Run

1.  Follow the setup instructions in the main repository's `README.md` to create and activate the virtual environment.
2.  Install dependencies from this folder: `pip install -r requirements.txt`.
3.  Open and run the Jupyter Notebook: `/src/decay_chain_simulation.ipynb`.
# Nuclear Reactor Criticality Analysis

## Summary

This project determines a nuclear reactor's criticality (k-eff) by modeling its neutron balance. I formulate the system as a matrix eigenvalue problem and solve it computationally for both a simplified 2-group and a more complex 8-group model to test the method's scalability.

A comprehensive report detailing the underlying physics is available in the `/report/` directory.

## Key Features

- **Construct Physics Matrices:** Builds the Migration (M) and Fission (F) matrices directly from raw cross-section data.
- **Solve Directly:** Utilizes NumPy's `linalg.eig` function for an accurate, one-shot solution for all eigenvalues.
- **Solve Iteratively:** Implements the Power Iteration algorithm to efficiently find the dominant eigenvalue (k-eff).
- **Analyze at Scale:** The code is generalized to solve for any number of energy groups defined in the input file.

## How to Run

1.  Follow the setup instructions in the main repository's `README.md` to create and activate the virtual environment.
2.  Install dependencies from this folder: `pip install -r requirements.txt`.
3.  Open and run the Jupyter Notebook: `/src/criticality_simulation.ipynb`.
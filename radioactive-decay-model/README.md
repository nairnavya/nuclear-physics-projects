# Computational Modeling of a Radioactive Decay Chain

## Summary

In this project, I implement and compare analytical and numerical solutions for a three-component radioactive decay chain ($N_{A} \rightarrow N_{B} \rightarrow N_{C}$). I model the time-dependent concentrations of each nuclide and validate the numerical approximation (Explicit Euler method) against the exact analytical solution.

A comprehensive report detailing the underlying physics and mathematical derivations is available here: [/report/radioactive_decay_theory.pdf](./report/radioactive_decay_theory.pdf).

## Key Features

- **Analytical Solver:** Implements mathematical equations for the decay chain.
- **Numerical Solver:** Uses the Explicit Euler forward difference method to approximate the system's evolution.
- **Parameterizable Simulation:** Easily customize initial conditions, half-lives, and time steps via a CSV file.
- **Comparative Visualization:** Plots both solutions on the same axes to visually demonstrate the numerical model's accuracy.

## Tech Stack

- Python 3
- Jupyter Notebook
- NumPy
- SciPy
- Matplotlib
- Pandas

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/radioactive-decay-model.git](https://github.com/YOUR_USERNAME/radioactive-decay-model.git)
    cd radioactive-decay-model
    ```
2.  **Create and activate the virtual environment:**
    ```bash
    # Create the environment
    python3 -m venv venv
    # Activate on macOS/Linux
    source venv/bin/activate
    # Or, activate on Windows
    # .\venv\Scripts\activate
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Customize Parameters (Optional):**
    Edit the values in `/data/input/sample_parameters.csv` to run your own simulation.

5.  **Run the Simulation:**
    Open and run the Jupyter Notebook located at `/src/decay_chain_simulation.ipynb`. The notebook contains the full analysis, visualizations, and will generate an output file at `/data/output/simulation_results.csv`.

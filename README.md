# Computational Physics Models in Python

In this repository, I explore concepts in nuclear engineering through a collection of computational models built in Python. Each project is self-contained and showcases different numerical methods for simulating complex physical systems.

---

## Getting Started

To run these projects, you'll need to set up a local environment.

1.  **Clone the repository:**
    ```bash
    git clone git@github.com:nairnavya/nuclear-physics-projects.git
    cd nuclear-physics-projects
    ```
2.  **Create and activate a virtual environment:**
    This creates an isolated environment for the project's dependencies.
    ```bash
    # Create the environment
    python3 -m venv venv
    # Activate on macOS/Linux
    source venv/bin/activate
    # Or, activate on Windows
    # .\venv\Scripts\activate
    ```
3.  **Install the required libraries:**
    Navigate into a specific project's folder and use its `requirements.txt` file. For example:
    ```bash
    cd radioactive-decay-model
    pip install -r requirements.txt
    ```

---

## Projects

### 1. [Radioactive Decay Kinetics](./radioactive-decay-model/)
This project implements and compares analytical vs. numerical solutions for a three-component radioactive decay chain.
* **Tech Stack:** Python, Jupyter, NumPy, SciPy, Matplotlib.

### 2. [Nuclear Reactor Criticality Analysis](./reactor-criticality-analysis/)
This project solves the neutron balance eigenvalue problem for a multi-group diffusion model to determine a reactor's criticality (k-eff).
* **Tech Stack:** Python, Jupyter, NumPy, SciPy.
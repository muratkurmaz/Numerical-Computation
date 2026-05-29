# Numerical Computation Exercises

A collection of numerical computation notebooks covering root-finding, optimisation, nonlinear PDE solvers, and finite-difference methods.

The repository is organised as a small portfolio of scientific-computing exercises written in Python/Jupyter. The focus is on implementing numerical algorithms directly, analysing convergence behaviour, and visualising numerical results.

## Topics Covered

- Newton's method, bisection, and Dekker-style root-finding
- Gradient descent with momentum for nonlinear systems
- One-dimensional viscous Burgers' equation
- Anisotropic diffusion and conjugate-gradient style linear solvers
- Finite-difference discretisation and numerical error analysis

## Repository Structure

```text
.
├── notebooks/
│   ├── newton-and-dekkers-methods.ipynb
│   ├── gradient-descent-with-momentum.ipynb
│   ├── one-dimensional-burgers-equation.ipynb
│   └── anisotropic-diffusion-and-conjugate-gradient.ipynb
├── docs/
│   └── exercise-summary.md
├── requirements.txt
├── environment.yml
├── .gitignore
└── README.md
```

## Getting Started

Clone the repository:

```bash
git clone git@github-muratkurmaz:muratkurmaz/numerical-computation-exercises.git
cd numerical-computation-exercises
```

Create a virtual environment and install the dependencies:

```bash
python -m venv .venv
.venv\Scripts\activate    # Windows CMD
pip install -r requirements.txt
```

On macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook notebooks
```

## Notebook Guide

| Notebook | Description |
|---|---|
| `newton-and-dekkers-methods.ipynb` | Root-finding experiments using Newton-type and bracketing methods, including convergence-order analysis. |
| `gradient-descent-with-momentum.ipynb` | Optimisation exercise studying gradient descent with momentum and graphical convergence behaviour. |
| `one-dimensional-burgers-equation.ipynb` | Finite-difference solution of the viscous Burgers' equation using nonlinear system solvers. |
| `anisotropic-diffusion-and-conjugate-gradient.ipynb` | Finite-difference anisotropic diffusion model with sparse linear algebra and iterative methods. |

## Skills Demonstrated

- Python-based scientific computing
- Numerical algorithms and convergence analysis
- Sparse matrix construction
- Finite-difference discretisation
- Nonlinear system solving
- Scientific visualisation with Matplotlib

## Author

Murat Kurmaz  
MSc High Performance Computing and Data Science, University of Edinburgh

## License

This project is licensed under the MIT License.

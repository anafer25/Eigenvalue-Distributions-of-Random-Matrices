# Eigenvalue-Distributions-of-Random-Matrices

This project explores the **eigenvalue distributions of random matrices** using Python. It compares matrices generated with **binary (0-1) entries** and **Gaussian (normal) entries** to illustrate how different random distributions affect the spectrum of eigenvalues.

The code computes the **absolute values (norms) of eigenvalues** for many random matrices and visualizes the results using **side-by-side histograms**.

## Features
- Generates **binary random matrices** (elements 0 or 1) and computes eigenvalues.
- Generates **Gaussian random matrices** (mean 0, variance 1) and computes eigenvalues.
- Repeats the process for multiple trials to gather sufficient statistical data.
- Plots **histograms** of the eigenvalue norms for both matrix types side by side.
- Uses **NumPy** for matrix operations and **Matplotlib** for visualization.
- Modular, object-oriented design ready for extension (e.g., other random distributions or larger matrices).

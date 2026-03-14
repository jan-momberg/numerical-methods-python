# Numerical Methods in Python

Implementation and analysis of classical algorithms from **numerical linear algebra** and **scientific computing** using Python.

The project focuses on **runtime analysis**, **numerical stability**, and **convergence behaviour** of fundamental numerical algorithms.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NumPy](https://img.shields.io/badge/NumPy-Scientific_Computing-orange)
![SciPy](https://img.shields.io/badge/SciPy-Linear_Algebra-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)

---

## Example Result

<p align="center">
  <img src="images/power_method_convergence.png" width="600">
</p>

Example: convergence behaviour of the **Power Method** when approximating the dominant eigenvalue.

---

# Overview

This repository contains a collection of **Jupyter notebooks implementing classical numerical algorithms**.

The experiments analyze:

* algorithmic **runtime behaviour**
* **numerical stability**
* **convergence properties**

The implementations are written in **Python** using the scientific computing ecosystem:

* NumPy
* SciPy
* Matplotlib
* Jupyter Notebook

The project serves as both a **learning resource** and a **demonstration of numerical algorithm implementations**.

---

# Topics Covered

## Tridiagonal Linear Systems

* Thomas algorithm
* comparison with dense linear solvers
* comparison with sparse solvers
* runtime benchmarking

---

## Iterative Methods

* Jacobi method
* Gauss–Seidel method
* convergence analysis
* performance comparison

---

## Least Squares Problems

* solution via normal equations
* solution via QR decomposition
* analysis of numerical stability

---

## Polynomial Interpolation

* Lagrange interpolation
* Newton interpolation
* comparison of equidistant nodes vs Chebyshev nodes
* visualization of interpolation behaviour

---

## Eigenvalue Computation

* Power method
* Rayleigh quotient
* convergence analysis for dominant eigenvalues

---

# Notebook Overview

## Tridiagonal Linear Systems

Implementation of the **Thomas algorithm** and comparison with dense and sparse solvers.

Notebook:

```
notebooks/01_tridiagonal_systems.ipynb
```

![Runtime comparison](images/tridiagonal_runtime_comparison.png)

---

## Iterative Methods

Comparison of **Jacobi** and **Gauss–Seidel** methods and analysis of convergence behaviour.

Notebook:

```
notebooks/02_iterative_methods.ipynb
```

![Iterative convergence](images/iterative_methods_convergence.png)

---

## Least Squares Problems

Stability comparison between solving least squares problems using:

* normal equations
* QR decomposition

Notebook:

```
notebooks/03_least_squares.ipynb
```

![Least squares stability](images/least_squares_stability.png)

---

## Polynomial Interpolation

Comparison between interpolation with:

* equidistant nodes
* Chebyshev nodes

Notebook:

```
notebooks/04_polynomial_interpolation.ipynb
```

![Polynomial interpolation](images/polynomial_interpolation_comparison.png)

---

## Eigenvalue Computation

Investigation of the convergence behaviour of the **Power Method**.

Notebook:

```
notebooks/05_eigenvalues.ipynb
```

![Power method convergence](images/power_method_convergence.png)

---

# Repository Structure

```text
numerical-methods-python
│
├── notebooks
│   ├── 01_tridiagonal_systems.ipynb
│   ├── 02_iterative_methods.ipynb
│   ├── 03_least_squares.ipynb
│   ├── 04_polynomial_interpolation.ipynb
│   └── 05_eigenvalues.ipynb
│
├── images
│   ├── tridiagonal_runtime_comparison.png
│   ├── iterative_methods_convergence.png
│   ├── least_squares_stability.png
│   ├── polynomial_interpolation_comparison.png
│   └── power_method_convergence.png
│
├── README.md
└── requirements.txt
```

---

# Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

# Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks in the **notebooks** directory to explore the experiments.

---

# Learning Goals

This project demonstrates:

* implementation of classical numerical algorithms
* comparison of different numerical methods
* analysis of runtime complexity
* investigation of numerical stability
* visualization of algorithm convergence

The repository illustrates fundamental techniques used in:

* **scientific computing**
* **numerical linear algebra**
* **data science**
* **machine learning**

---

# Author

**Jan Momberg**

GitHub: https://github.com/jan-momberg


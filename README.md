# Numerical Methods in Python

Implementation and analysis of classical algorithms from **numerical linear algebra** and **scientific computing** using Python.

The project focuses on the implementation, comparison, and analysis of numerical algorithms with respect to:

* runtime behaviour
* numerical stability
* convergence properties

<p align="center">
  <img src="images/power_method_convergence.png" width="600">
</p>

---

## Overview

This repository contains a collection of **Jupyter notebooks implementing classical algorithms from numerical linear algebra and scientific computing**.

The experiments are implemented in **Python** using the scientific computing ecosystem:

* **NumPy**
* **SciPy**
* **Matplotlib**
* **Jupyter Notebook**

The repository serves both as:

* a **learning project for numerical algorithms**
* a **demonstration of numerical method implementations and analysis**

---

## Topics Covered

The repository includes implementations and experiments for several fundamental numerical methods.

### 1. Tridiagonal Linear Systems

* Implementation of the **Thomas algorithm**
* Comparison with **dense linear solvers**
* Comparison with **sparse solvers**
* Runtime benchmarking

---

### 2. Iterative Methods

* **Jacobi method**
* **Gauss–Seidel method**
* Convergence analysis
* Performance comparison

---

### 3. Least Squares Problems

* Solving least squares via **normal equations**
* Solving least squares via **QR decomposition**
* Analysis of **numerical stability**

---

### 4. Polynomial Interpolation

* **Lagrange interpolation**
* **Newton interpolation**
* Comparison of **equidistant nodes vs. Chebyshev nodes**
* Visualization of interpolation behaviour

---

### 5. Eigenvalue Computation

* **Power method**
* **Rayleigh quotient**
* Analysis of convergence behaviour for dominant eigenvalues

---

## Example Results

### Tridiagonal Linear Systems

Runtime comparison between the **Thomas algorithm** and general-purpose solvers.

![Runtime comparison](images/tridiagonal_runtime_comparison.png)

---

### Iterative Methods

Convergence comparison of **Jacobi** and **Gauss–Seidel** methods.

![Iterative methods convergence](images/iterative_methods_convergence.png)

---

### Least Squares

Stability comparison between solving least squares problems via:

* **normal equations**
* **QR decomposition**

![Least squares stability](images/least_squares_stability.png)

---

### Polynomial Interpolation

Comparison of polynomial interpolation using:

* **equidistant nodes**
* **Chebyshev nodes**

![Polynomial interpolation](images/polynomial_interpolation_comparison.png)

---

### Eigenvalue Computation

Convergence behaviour of the **power method** when approximating dominant eigenvalues.

![Power method convergence](images/power_method_convergence.png)

---

## Repository Structure

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

## Installation

Clone the repository:

```bash
git clone https://github.com/jan-momberg/numerical-methods-python.git
cd numerical-methods-python
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open the notebooks in the **`notebooks`** directory to explore the numerical experiments and visualizations.

---

## Requirements

The project uses the following Python libraries:

* NumPy
* SciPy
* Matplotlib
* Jupyter Notebook

---

## Learning Goals

This project demonstrates:

* implementation of classical numerical algorithms
* comparison of different numerical methods
* analysis of runtime behaviour
* investigation of numerical stability
* visualization of convergence behaviour

The repository illustrates fundamental techniques used in **scientific computing and numerical linear algebra**.

---

## Author

Jan Momberg

GitHub:
https://github.com/jan-momberg


# Simultaneous Equations Solver

This repository contains Python implementations of three different methods to solve simultaneous linear equations with three variables:

1. **Jacobi's Method**
2. **Gauss-Seidel Method**
3. **Gauss Elimination Method**

Each method is implemented in a separate Jupyter Notebook, and the code is designed to solve a system of three linear equations with three variables.

## Methods Overview

### 1. Jacobi's Method
Jacobi's method is an iterative algorithm for solving systems of linear equations. It starts with an initial guess and iteratively improves the solution until convergence is achieved. This method is simple but may require many iterations to reach an accurate solution.

### 2. Gauss-Seidel Method
The Gauss-Seidel method is an improvement over Jacobi's method. It uses the latest values of the variables as soon as they are computed, which often leads to faster convergence compared to Jacobi's method.

### 3. Gauss Elimination Method
Gauss elimination is a direct method for solving systems of linear equations. It transforms the system into an upper triangular form using row operations, and then back-substitutes to find the solution. This method is more efficient for smaller systems and provides an exact solution.

## Repository Structure

- **Jacobi's method.ipynb**: Contains the implementation of Jacobi's method.
- **Guass seidal method.ipynb**: Contains the implementation of the Gauss-Seidel method.
- **Guass elimination.ipynb**: Contains the implementation of the Gauss elimination method.

## Usage

Each notebook contains the following steps:

1. **Define the Equations**: The system of equations is defined as strings.
2. **Extract Constants**: Functions are provided to extract the coefficients and constants from the equations.
3. **Solve the Equations**: The respective method is applied to solve the equations.
4. **Output the Solution**: The final values of the variables are printed.

### Example

For example, in the `Jacobi's method.ipynb` notebook, the system of equations is defined as:

```python
eq1 = "5x + 2y + 1z = 12"
eq2 = "1x + 4y + 2z = 15"
eq3 = "1x + 2y + 5z = 20"

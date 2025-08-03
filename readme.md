# -*- coding: utf-8 -*-
"""
Title: Design Optimization Algorithm Comparison

Description:
This script visualizes and compares the performance of various optimization algorithms 
on benchmark functions such as Ackley, Rastrigin, Rosenbrock, Booth, Matyas, Himmelblau, and Beale. 
The algorithms implemented include:

- Brute Force Search
- Gradient Descent
- Simulated Annealing
- Genetic Algorithm
- Pattern Search (Hooke-Jeeves method)

Each algorithm searches for the global minimum of the chosen objective functions.
The optimization is performed using NumPy only (no external optimization libraries), 
and results are visualized using both 3D surfaces and 2D contour plots.

Visualizations also include:
- Individual function surfaces
- Locations of optima found by each method
- A sinusoidal metaphor representation of each optimizer's result

Usage:
- Run the script in a Python environment with NumPy, Matplotlib, and SymPy installed.
- The Ackley function is used as the primary test case for optimization.
- Modify the selected function or optimizer configurations as needed.

Author: [Bokono]
Original Source: Google Colab notebook
Converted: Automatically into standalone Python script
Date: [Insert Date]

Dependencies:
- numpy
- matplotlib
- sympy

"""

# Formative 3 - Probability Distributions, Bayesian Probability, and Gradient Descent Implementation
** Group 12 **

## Overview

This repository contains the group submission for Formative 3, covering three core topics in machine learning: Bivariate Normal Distribution, Bayesian Probability, and Gradient Descent (both manual and coded).


## Repository Structure

```
Formative-3_Group-12/
│
├── Formative_3_Part_1.ipynb           # Part 1: Bivariate Normal Distribution
├── Formative_3_Part_2.ipynb           # Part 2: Bayesian Probability
├── Formative_3_Part_3_Manual_Calculations.pdf  # Part 3: Manual Gradient Descent
├── Formative_3_Part_4.ipynb           # Part 4: Gradient Descent in Code
├── StudentsPerformance.csv            # Dataset used in Part 2
├── Contributions list.pdf             # Group contribution breakdown
└── README.md
```

---

## Part Descriptions

### Part 1 — Bivariate Normal Distribution
Implements the Bivariate Normal Distribution (BVN) PDF from scratch using NumPy. Includes both a 3D surface plot and a 2D contour plot to visualise the distribution.


### Part 2 — Bayesian Probability
Uses the  IMDb Movie Reviews Dataset to apply Bayes' Theorem in Python. Involves loading and cleaning the dataset, selecting relevant keywords/features, computing conditional probabilities, and presenting results.


### Part 3 — Manual Gradient Descent Calculations
Each group member manually completed one full iteration of gradient descent for linear regression (y = mx + b) using:
- Initial values: m₀ = −1, b₀ = 1, α = 0.1
- Data points: (1, 3) and (3, 6)

Each iteration shows: predictions, errors, MSE, Chain Rule derivation, and parameter updates.


### Part 4 — Gradient Descent in Code
Implements the gradient descent algorithm in Python to fit a linear regression model to the same data points used in Part 3. Includes:
- Gradient descent loop with parameter update history
- SciPy `minimize` cross-check to verify correctness
- **Plot 1:** m and b convergence over iterations (vs. SciPy optimal values)
- **Plot 2:** MSE reduction over iterations (log scale)


## How to Run

All notebooks are designed to run in **Google Colab**.

1. Open the relevant `.ipynb` file in Colab
2. Run all cells in order
3. No additional installs required — all libraries (`numpy`, `matplotlib`, `scipy`) are available by default in Colab



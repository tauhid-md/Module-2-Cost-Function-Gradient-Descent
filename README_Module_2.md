# Module 2 – Cost Function and Gradient Descent

This repository contains my solved **Module 2 worksheet** on implementing linear regression with one input feature using NumPy and Python.

## Problem Statement

The worksheet uses house size (in thousands of square feet) to predict house price (in INR lakhs) with a simple linear regression model.

## Topics Covered

- Linear regression hypothesis: `h(x) = w*x + b`
- Computing the cost function
- Computing gradients for parameters `w` and `b`
- Gradient descent and parameter updates
- Learning rate and number of iterations
- Plotting cost versus iterations
- Predicting prices for different house sizes

## Tools and Technologies

- Python
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

## How to Run

1. Download `Module_2_Cost_Function_Gradient_Descent_Solved.ipynb` from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook** and upload the downloaded notebook.
4. Run all cells from top to bottom using **Shift + Enter**.

NumPy and Matplotlib are commonly available in Google Colab. If needed, install them with:

```python
!pip install numpy matplotlib
```

## Main Functions Implemented

- `compute_cost(x, y, b, w)`: calculates the mean squared error cost with the `1/(2*m)` factor.
- `compute_gradient(x, y, w, b)`: calculates the gradients with respect to `w` and `b`.
- `gradient_descent(...)`: repeatedly updates `w` and `b` to reduce the cost.

## Predictions

After training, the notebook uses the learned parameters to predict house prices for:
- 1000 sqft
- 2000 sqft
- 1750 sqft

The worksheet's expected approximate predictions are 31.6, 48.1, and 44.0 Thousand INR respectively.

## Repository Structure

```text
Module-2-Cost-Function-Gradient-Descent/
├── Module_2_Cost_Function_Gradient_Descent_Solved.ipynb
└── README.md
```

## Learning Outcome

After completing this worksheet, I practiced how a linear regression model learns its parameters using a cost function, gradients, and gradient descent, and how the trained model can make predictions.

---
**Module:** 2 – Cost Function and Gradient Descent  
**Status:** Completed

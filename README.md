# From Scratch: Linear Regression, Binary Classification, and Multiclass Classification

This project demonstrates the manual implementation of **Linear Regression**, **Binary Classification (Logistic Regression)**, and **Multiclass Classification (Softmax Regression)** using only `numpy` and `pandas`.

The objective was to build machine learning algorithms **entirely from scratch**, without relying on any pre-built machine learning libraries. This approach highlights a solid understanding of algorithmic foundations and mathematical optimization.

---

## Project Structure

- `scratch_regress.ipynb` — Linear Regression implemented from scratch
- `scratch_bin_class.ipynb` — Logistic Regression for Binary Classification implemented from scratch
- `scratch_multi_class.ipynb` — Logistic Regression with Softmax for Multiclass Classification implemented from scratch

---

## Key Features

- Manual **Gradient Descent** implementation with learning rate decay
- Support for **L1 and L2 regularization**
- Full **data preprocessing pipeline**:
  - Outlier removal
  - Feature scaling
  - Feature engineering (polynomial features, distance-based features)
- Manual implementation of:
  - Loss functions
  - Gradient calculations
- Training progress visualization (loss curves, accuracy, F1 macro score)
- Evaluation with appropriate metrics:
  - `R²` for regression
  - `Accuracy` for binary classification
  - `F1-macro` for multiclass classification
- Comprehensive Exploratory Data Analysis (EDA)

---

## Summary of Results

| Task                         | Implemented Algorithm               | Final Performance   |
|------------------------------|-------------------------------------|---------------------|
| Linear Regression            | Gradient Descent, Normal Equation   | R² ≈ 0.9945         |
| Binary Classification        | Logistic Regression                 | Accuracy ≈ 88.5%    |
| Multiclass Classification    | Softmax + Log Loss                  | F1 Macro ≈ 0.97     |

---

## Tools and packages
- Python (Jupyter Notebook)
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`


## Datasets Description

All datasets used in this project are fully synthetic and artificially generated. The datasets were created solely for the purpose of demonstrating the algorithmic implementation and mathematical concepts.

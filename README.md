# Applied Nonlinear Regression: Polynomial & Spline Models

**Author:** Abigail Albury-Bloom
**Focus:** Nonlinear Regression, Model Flexibility, and Assumption Evaluation
**Tools:** Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Kaggle

---

## Overview

This repository demonstrates applied **nonlinear regression techniques** using the Abalone dataset, a commonly used benchmark for predictive modeling. The project focuses on extending linear regression through **polynomial terms** and **spline-based methods** to capture nonlinear relationships while carefully evaluating assumptions and model behavior.

The analysis emphasizes:

* When and why linear models fail
* How nonlinear extensions improve model fit
* Trade-offs between flexibility, interpretability, and generalization
* Clear interpretation of regression results

All analysis is reproducible and includes both executable notebooks and written summaries.

---

## Problem Context

**Regression with Abalone Dataset (Kaggle)**
The goal is to predict a continuous outcome related to abalone characteristics using nonlinear regression methods. This type of problem mirrors real-world scenarios where relationships between predictors and outcomes are rarely purely linear.

---

## Models Implemented

### 1. Polynomial Regression

* Introduced nonlinear terms to capture curvature
* Evaluated different polynomial degrees
* Assessed overfitting risk and model stability

**Key considerations:** model complexity, variance inflation, extrapolation behavior

---

### 2. Spline Regression

* Used spline functions to model smooth nonlinear relationships
* Compared spline-based models to polynomial alternatives
* Examined boundary behavior and smoothness

**Key considerations:** knot placement, smoothness constraints, interpretability

---

## Evaluation & Diagnostics

* Compared model performance using Kaggle evaluation metrics
* Examined residual patterns and goodness-of-fit
* Investigated assumptions including linearity, homoscedasticity, and error behavior
* Interpreted trade-offs between flexibility and generalization

---

## Files Included

* `Albury-BloomADDS8555-4.ipynb` – Complete modeling workflow and evaluation
* `Albury-BloomADDS8555-4.pdf` – Interpreted report with figures and conclusions
* `abalone_polynomial_submission.csv` – Kaggle submission output (polynomial model)
* `abalone_spline_submission.csv` – Kaggle submission output (spline model)

---

## Key Skills Demonstrated

* Nonlinear regression modeling
* Polynomial feature engineering
* Spline regression techniques
* Model diagnostics and assumption checking
* Comparative model evaluation
* Applied regression interpretation

---

## Why This Project Matters

Many real-world regression problems involve nonlinear relationships. This project demonstrates the ability to:

* Recognize limitations of linear models
* Apply appropriate nonlinear methods
* Evaluate model assumptions rigorously
* Communicate results clearly to technical and non-technical audiences

---

## Contact

**Abigail Albury-Bloom**
🔗 LinkedIn: [https://www.linkedin.com/in/abigail-albury-bloom/](https://www.linkedin.com/in/abigail-albury-bloom/)

---

*This repository is part of an applied machine learning portfolio focused on regression modeling and evaluation.*

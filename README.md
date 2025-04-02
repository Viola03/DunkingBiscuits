# Dunking Biscuits in Tea – Data Science & Fluid Dynamics Project

This project investigates the capillary flow of tea into different types of biscuits using both physical models (the Washburn equation) and machine learning approaches. The aim is to classify biscuits based on their soaking characteristics, compare theoretical and data-driven predictions of absorption, and explore structural properties such as pore radius.

---

## Objectives

- Predict liquid rise height using both the Washburn equation and machine learning models
- Classify biscuit types (Digestive, Hobnob, Rich Tea) based on soaking parameters
- Infer structural properties (e.g., pore radius) from macroscopic data
- Evaluate how well classical physics aligns with experimental observations
- Apply trained models to identify biscuit types in time-resolved, unlabeled trials

---

## Methods & Tools

- **Python** with `pandas`, `matplotlib`, `scikit-learn`, `xgboost`
- **Washburn model** for capillary action
- **Gradient Boosting**, **Random Forest**, **Logistic Regression**, etc. for classification
- Visual inspection and curve-fitting of time-resolved L-vs-t data

---

## Notebook Table of Contents

1. **Exploratory Data Analysis**
   - Description of datasets: dunking, time-resolved, microscopy including correlation matrices, biscuit feature distributions
2. **Preprocessing**
   - Feature scaling, encoding, and cleaning
3. **Machine Learning Models**
   - Classifiers and regressors for biscuit type and L prediction
4. **Model Evaluation**
   - Accuracy, R², residuals, error metrics, feature importances
5. **Washburn Equation Modelling**
   - Fitting, prediction accuracy
6. **Pore Radius Estimation**
   - From both physics and ML-based regression
7. **Time-Resolved Data Analysis**
   - Identifying unknown biscuits from soaking profiles



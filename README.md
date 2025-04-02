# Dunking Biscuits in Tea – AI & Data Science Project

This project investigates the capillary flow of tea into different types of biscuits using both physical models (the Washburn equation) and machine learning approaches. The aim is to classify biscuits based on their soaking characteristics, compare theoretical and data-driven predictions of absorption, and explore structural properties such as pore radius.

---

## Objectives

- Predict liquid rise height using both the Washburn equation and machine learning models
- Classify biscuit types (Digestive, Hobnob, Rich Tea) based on soaking parameters
- Infer structural properties (e.g., pore radius) from macroscopic data
- Evaluate how well classical physics aligns with experimental observations
- Apply trained models to identify biscuit types in time-resolved, unlabeled trials

---

## Notebook Rough Table of Contents

1. **Exploratory Data Analysis**
   - Description of datasets: dunking, time-resolved, microscopy including correlation matrices, biscuit feature distributions
   - Feature scaling, encoding, and cleaning
2. **Machine Learning Models**
   - Classifiers and regressors for biscuit type and L prediction
   - Accuracy, R², residuals, error metrics, feature importances
3. **Pore Radius Investigation**
   - Across biscuit types classified from previous classifiers and Kmeans. 
4. **Pore Radius Estimation**
   - From both physics and ML-based regression
7. **Time-Resolved Data Analysis**
   - Identifying unknown biscuits from soaking profiles



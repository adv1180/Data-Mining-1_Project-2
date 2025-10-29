# STA 5703 Data Mining Methodology I

## Project 2: High-Dimensional Regression on Maize Flowering Time

## Project Overview
* **Goal:** Build and compare multiple high-dimensional regression pipelines to predict maize flowering time (`dtoa` - days to anthesis) using SNP marker data.
* **Dataset:** 278 samples with 7,389 SNP marker features + target variable (`dtoa`).
* **Data Source:** Buckler et al. (2009), "The Genetic Architecture of Maize Flowering Time," Science 325.
* **Models Implemented:**
    * Ridge Regression Cross-Validation (L2 regularization)
    * Lasso Regression Cross-Validation (L1 regularization)
    * Elastic Net Cross-Validation
    * Principal Components Regression (PCR)
    * Partial Least Squares (PLS)
    * Criterion-Based Selection (LassoLarsIC using AIC/BIC)

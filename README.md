[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rileybarka/Lab-6-Airbnb-Regression-Ensemble/blob/main/notebooks/Lab6.ipynb)

# Lab 6: Regression Modeling and Ensemble Methods

This lab explores regression modeling using the Airbnb NYC listings dataset, including individual regressors and ensemble techniques such as stacking, Gradient Boosted Trees, and Random Forest.

---

## Dataset Used

| Dataset | Description |
|---------|-------------|
| **Airbnb Listings NYC (Dec 2021)** | Modified Airbnb listings dataset used for regression modeling and evaluation. |

---

## Objectives

- Load and prepare the Airbnb dataset (feature engineering, label definition, train-test split)  
- Train and evaluate two individual regression models  
- Apply stacking ensemble method on the individual regressors  
- Train and evaluate Gradient Boosted Decision Trees  
- Train and evaluate Random Forest regressors  
- Visualize and compare model performance metrics  

---

## Methodology

1. Data loading and preprocessing  
2. Model training:
   - Two individual regressors  
   - Stacking ensemble using the individual regressors  
   - Gradient Boosted Decision Trees  
   - Random Forest  
3. Model evaluation using appropriate regression metrics (e.g., MAE, RMSE, R²)  
4. Visualization of comparative model performance  

---

## Setup Instructions

### Open in Google Colab  
Click the badge above.

### Run Locally

```bash
git clone https://github.com/rileybarka/Lab-6-Airbnb-Regression-Ensemble.git
cd Lab-6-Airbnb-Regression-Ensemble/notebooks
jupyter notebook Lab6.ipynb

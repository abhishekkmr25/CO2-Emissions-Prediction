# CO₂ Emissions Regression

A regression project focused on understanding and predicting vehicle **CO₂ emissions (g/km)** using engine, fuel-consumption, and vehicle characteristics.

## What I Did

- Performed data cleaning and preprocessing, including missing-value handling and categorical feature consolidation.
- Conducted EDA to understand CO₂ emissions and its relationship with different vehicle characteristics.
- Encoded categorical variables and prepared the data for regression modelling.
- Checked **multicollinearity using VIF** and removed highly redundant predictors.
- Built **OLS regression** manually using the normal equation and verified the results using `statsmodels`.
- Evaluated models using **R², Adjusted R², RMSE, and MAE**.
- Performed residual diagnostics using **Breusch–Pagan, White test, HC3 robust standard errors, and Ramsey RESET**.
- Built and tuned **Ridge and Lasso regression** using 5-fold cross-validation.
- Compared model performance and examined the trade-off between fit, regularization, and generalization.

## Target

**CO₂ Emissions (g/km)**

## Models

- **Linear Regression / OLS** – baseline model and statistical inference
- **Ridge Regression** – L2 regularization to control coefficient instability
- **Lasso Regression** – L1 regularization with feature-selection capability

## Key Features

- Engine Size
- Cylinders
- Fuel Consumption
- Vehicle Class
- Transmission
- Fuel Type

## Tech Stack

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `Statsmodels` · `Matplotlib` · `Seaborn`

## Workflow

**Data Cleaning → EDA → Feature Engineering → Encoding → Train/Test Split → VIF → OLS → Residual Diagnostics → Ridge/Lasso → Model Comparison**


1. Keep the dataset in the working directory.
2. Open `CO2_Emissions_Regression_Project_final.ipynb`.
3. Run the notebook sequentially from top to bottom.


# House Price Prediction — Machine Learning Project

## Objective
Predict the selling price of houses based on their characteristics
(area, bedrooms, location...) using supervised ML models.

Academic project completed in a team of 3 at EFREI Paris.

## Dataset
- **Source** : King County House Sales (Seattle, USA)
- **Size** : 21,613 houses, 21 variables
- **Target** : Selling price (regression)

## Full Pipeline
1. Data loading and exploratory analysis (EDA)
2. Data cleaning — handling missing values
3. Correlation visualization (seaborn, matplotlib)
4. Training 5 regression models :
   - Linear Regression
   - Decision Tree
   - Random Forest — best model
   - Lasso Regression
   - KNN Regressor
5. Performance comparison (R², MSE)

## Results
| Model | R² Score |
|---|---|
| Random Forest | Best |
| Linear Regression | Baseline |
| Decision Tree | Overfitting detected |
| Lasso | Regularization tested |
| KNN | Non-linear comparison |

> Random Forest Regressor achieved the highest prediction accuracy.

## Tech Stack
Python · pandas · numpy · scikit-learn · matplotlib · seaborn · Jupyter Notebook

## Run the project
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook Projet_Machine_Learning.ipynb
```

## Team
EFREI project — Laurent Qiu, Alexis Perrin, Alex Brulé

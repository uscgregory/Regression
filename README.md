# Predicting Cancer Mortality Rates for US Counties

The goal of this project is to determine cancer mortality rates by US county using data aggregated from a number of sources including the American Community Survey (census.gov), clinicaltrials.gov, and cancer.gov. The dataset for this project can be found at [data.world](https://data.world/nrippner/ols-regression-challenge)

Please review the final results of my analysis by viewing the [Regression Results - Executive Summary]() 

In the course of this project I performed the following analysis

#### [Data Cleaning](https://github.com/uscgregory/Regression/blob/main/Regression%20-%20Data%20Cleaning.ipynb)
 - Identify and treat missing data (Imputation and Deleting)
 - Identify and treat incorrect/erroneous data
 - Explore relationships between Independent and Dependent variables
 - Treat non-linear relationships (Transformation, Deletion)

#### [Data Exploration](https://github.com/uscgregory/Regression/blob/main/Regression%20-%20Data%20Exploration.ipynb)
 - Explore distributions and correlations among variables

#### [Linear Models](https://github.com/uscgregory/Regression/blob/main/Regression%20-%20Linear%20Models.ipynb)
 - Feature Selection using SelectKBest
 - Linear Regression (OLS)
 - Assumption Testing w/ Visualizations (Linearity, Normality, Multicollinearity, Homoscadasticity)
 - Checking for Influential Points (Cooks Distance)
 - Lasso, Ridge, and ElasticNet Regression

#### [Alternative Analysis](https://github.com/uscgregory/Regression/blob/main/Regression%20-%20Alternative%20Models.ipynb)
 - Decision Tree Regressor 
 - Random Forest Regressor 
 - Support Vector Machine Regression
 - Gradiant Boosting Regression

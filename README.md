# Decoding-Diamond-Prices
A statistical analysis of diamond prices utilizing linear regression, model diagnostics, AIC-based selection, multicollinearity assessment, and uncertainty quantification. 



## Objectives
-Identifying the most influential predictors of diamond prices
-Evaluate model assumptions and apply transformations when necessary
-Address multicollinearity utilizing variance inflation factors (VIF)
-Compare potential models using AIC-based model selection
-Quantify uncertainty through confidence and prediction intervals

## Data
The dataset used for this project contains 2,000 randomly sampled observations of diamond sales with the following attributes:
- **Price** (USD)
- **Carat**
- **Cut**
- **Color**
- **Clarity**
- **Depth**
- **Table**
- **Physical dimensions** (x, y, z)


## Methodology
- Exploratory data analysis using summary statistics and visualizations
- Simple and multiple linear regression modeling
- Assumption diagnostics (normality, homoscedasticity, linearity)
- Log transformation to improve model fit
- Model refinement using AIC-based stepwise selection
- Multicollinearity assessment via variance inflation factors (VIF)
- Prediction and uncertainty quantification

## Key Findings
- Carat weight is the dominant predictor of diamond price
- Log transformation substantially improves model assumptions and fit
- Grading attributes such as cut, color, and clarity provide additional explanatory power
- Multicollinearity among size-related variables required feature refinement
- Prediction intervals reveal substantial variability in individual diamond prices

## Files
- `Diamonds.Rmd` — Full analysis and code
- `Diamonds.pdf` — Rendered report
- `data/` — Dataset used in the analysis

## Tools & Libraries
- R
- tidyverse
- broom
- MASS
- car
- knitr

## Notes
This project was completed as part of a linear regression course and refined to serve as a portfolio-ready data science project.

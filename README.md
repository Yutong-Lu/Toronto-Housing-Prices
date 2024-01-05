# Toronto Home Prices Linear Regression Model

**Author:** Yutong Lu - 1005738356  

**Date:** October 25, 2021  

## Introduction

- **Objective:** To analyze factors influencing home prices in Toronto.
- **Data Sources:** "Wellbeing Toronto – economics" and "Wellbeing Toronto – demographics" datasets from 2011.

## Hypothesis

- Hypothesizing a linear relationship between home prices and variables such as local employment, business establishments, child care spaces, and debt risk category.

## Data

### Data Collection

- Utilizes datasets from Toronto City Planning and other sources like TransUnion and Realosophy.com.
- Focus on variables: child care spaces, debt risk score, home prices, local employment, and business establishments.

### Data Cleaning

- Process involved renaming columns, converting data types, and creating new variables for analysis.

## Important Variables

- Key variables: "home prices in 10K CAD", "risk category", "employment per area", "businesses per area", and "child care spaces per area".

## Methodology

- Employed frequentist linear regression model.
- Used step-wise backward selection based on R2 and adjusted R2 values.
- Conducted partial F tests and Student’s T-tests for statistical significance.

## Results

- Found significant linear relationship between debt risk category and home prices.
- Child care spaces did not show a significant linear relationship with home prices.
- Employment and business per area were less relevant in explaining home prices.

## Conclusions

- High-debt-risk neighborhoods likely to have lower home prices.
- Child care spaces and employment rates are not significantly linearly related to home prices in Toronto.
- Provides insights for families considering home purchases in relation to neighborhood characteristics.

## Limitations and Future Research

- Limitations include potential violation of homoscedasticity and linearity assumptions.
- Future research could explore different methods of normalizing variables and consider the relationship between child care spaces as a categorical var

# Tipping Analysis and Prediction

## Introduction
This project aims to analyze and predict the tips received by waiters based on various factors such as bill amount, day of the week, time of the day, and customer gender. The results of our analysis can help waiters improve their service and income, as well as help restaurant managers optimize their pricing and staffing strategies.

## Project Goals
- Perform exploratory data analysis (EDA) on the tipping dataset to understand the distribution and relationships of variables
- Build a predictive model using polynomial linear regression to predict tips based on several factors
- Perform hypothesis testing to examine the relationships between variables
- Evaluate the model performance using mean squared error and R-squared
- Document the entire project with a README file that includes a brief introduction, project goals, data sources, methodology, and key findings

## Data Sources
The tipping dataset is obtained from Kaggle (https://www.kaggle.com/jsphyg/tipping). It contains 244 observations and 7 variables, including the total bill amount, tip amount, day of the week, time of day, customer gender, smoker status, and party size.

## Methodology
We perform exploratory data analysis (EDA) on the tipping dataset by visualizing the distribution of variables using histograms, box plots, and bar plots. We then preprocess the data using a pipeline with a column transformer for numeric and categorical features, fit a polynomial linear regression model with degree 2 to the training set, and evaluate the model performance using mean squared error and R-squared. We also perform hypothesis testing on the relationship between tips and bill amount using OLS regression with statsmodels.

## Key Findings
- The tip amount and bill amount are right-skewed, which may require some data transformation later.
- There is a significant positive relationship between tips and bill amount (p < 0.001).
- The model performance on the testing set is reasonable with an MSE of 1.06 and an R-squared of 0.48.
- Factors such as day of the week, time of day, and customer gender may also have an impact on the tips received by waiters.

## Conclusion
Our analysis and prediction can provide valuable insights into the tipping behavior of customers and help waiters and restaurant managers make data-driven decisions to improve their service and business.

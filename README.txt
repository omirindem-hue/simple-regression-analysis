Marketing ROI Analysis Using Simple Linear Regression
Project Overview

This project analyzes the relationship between marketing expenditure and sales using Simple Linear Regression. The aim is to identify the marketing channel with the strongest impact on sales and recommend how a company should allocate its marketing budget to maximize return on investment (ROI).

Dataset

The dataset contains the following variables:

TV advertising expenditure
Radio advertising expenditure
Social Media advertising expenditure
Sales
Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Statsmodels
Jupyter Notebook
Project Workflow
Loaded the dataset.
Cleaned missing values.
Performed Exploratory Data Analysis (EDA).
Visualized relationships between advertising channels and Sales.
Identified TV advertising as the variable most correlated with Sales.
Built a Simple Linear Regression model using Ordinary Least Squares (OLS).
Evaluated the model using diagnostic plots.
Interpreted the regression results.
Recommended an ROI-based marketing budget allocation.
Results
TV advertising showed the strongest correlation with Sales.
The regression model achieved an R-squared value of 0.993, indicating that approximately 99.3% of the variation in Sales is explained by TV advertising.
TV advertising was found to be a statistically significant predictor of Sales (p-value < 0.05).
Recommendation

Based on the analysis, the company should allocate a larger proportion of its marketing budget to TV advertising, as it demonstrates the strongest positive impact on Sales and is expected to generate the highest return on investment (ROI).

How to Run

Install the required libraries:

pip install pandas numpy matplotlib seaborn statsmodels

Open simple_linear_regression_analysis.ipynb in Jupyter Notebook and run all cells.
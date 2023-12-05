# Witdatascience
## Introduction
The purpose of this project is to analyze sleep efficiency data to understand the factors that may influence sleep quality. The research question revolves around identifying the relationship between various features (such as age, gender, sleep duration, etc.) and sleep efficiency. The primary goal is to build predictive models that can estimate sleep efficiency based on these features.


My 3 questions from the dataset are

-What is the Relationship Between Age and Sleep Efficiency?

-How Do Lifestyle Choices, Such as Caffeine and Alcohol Consumption, Impact Sleep Efficiency?

-Which Model Performs Best in Predicting Sleep Efficiency?

## Selection of Data

The dataset used in this project is sourced from Kaggle. The dataset includes information on sleep-related factors such as age, gender, sleep duration, sleep efficiency, REM sleep percentage, and more. 

![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/Data__preview.png)
## Methods
Tools:
For data analysis and inference, the project utilizes a set of powerful tools:
NumPy
SciPy
Pandas 
Scikit-learn

Data Cleaning:

Missing values in specific columns (e.g., Awakenings, Caffeine consumption) are handled by filling them with appropriate default values.
Data Transformation:

Categorical variables, such as "Gender" and "Smoking status," are encoded into numerical values (0 or 1) for compatibility with machine learning algorithms.
Conducted EDA, visualizing target distribution, correlation matrix, and pairplots.

Selected Linear Regression, considering assumptions, and evaluated with cross-validation.

Explored Ridge, Lasso, Random Forest models, evaluating performance and cross-validation.

Incorporated polynomial features, Neural Network, and Gradient Boosting for comparison.

Evaluated models using MSE, R-squared, and cross-validation scores.

Visualized feature importance, particularly in the Gradient Boosting model.

Additional Tools/Modules Used 

Matplotlib and Seaborn

XGBoost

Streamlit

## Reference

https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency/code

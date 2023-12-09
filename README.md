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

## Results
### What is the Relationship Between Age and Sleep Efficiency?

The relationship between age and sleep efficiency was explored using scatter plots, examining various sleep-related features. In the visual representation, the scatter plot for "Sleep efficiency vs Age" indicates a diverse distribution. While there doesn't seem to be a clear linear pattern, the scatter points reveal a spread of sleep efficiency scores across different age groups. This suggests that age alone may not be the sole determinant of sleep efficiency, and other factors might contribute to the observed variations. 

![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/Age_Sleepeff.png)


![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/Sleepeff_features.png)


### How Do Lifestyle Choices, Such as Caffeine and Alcohol Consumption, Impact Sleep Efficiency?

In our exploration of sleep efficiency, we looked into how lifestyle choices, specifically caffeine and alcohol consumption, might affect our sleep. We used visualizations and numbers from a big set of sleep-related data to understand this better. For caffeine, it seemed like people who drank less had better sleep efficiency, showing a positive connection. Numbers supported this, indicating higher sleep efficiency in those with little to no caffeine.

![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/impact_of%20_caffeine.png)

 Turning to alcohol, our data suggested a possible downside – higher alcohol intake might lead to lower sleep efficiency. Visual clues and numbers hinted at this trend. We also considered outliers, showing us that people respond differently. In conclusion, our findings highlight how lifestyle choices, like caffeine and alcohol, can impact sleep quality, offering insights for everyone to consider for better sleep.
 
![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/impact_of%20_alchohol.png)





## Reference

https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency/code

# Witdatascience
## Introduction
The purpose of this project is to analyze sleep efficiency data to understand the factors that may influence sleep quality. The research question revolves around identifying the relationship between various features (such as age, gender, sleep duration, etc.) and sleep efficiency. The primary goal is to build predictive models that can estimate sleep efficiency based on these features.


My 3 questions from the dataset are

1 What is the Relationship Between Age and Sleep Efficiency?

2 How Do Lifestyle Choices, Such as Caffeine and Alcohol Consumption, Impact Sleep Efficiency?

3 Which Model Performs Best in Predicting Sleep Efficiency?

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


In my exploration of predictive modeling, I delved into the intricacies of Ridge, Lasso, and Random Forest models, meticulously evaluating their performance using metrics like Mean Squared Error (MSE), R-squared, and cross-validation scores. To broaden the comparative analysis, I incorporated polynomial features, Neural Network, and Gradient Boosting into the modeling framework. The assessment covered a diverse set of evaluation criteria, providing a comprehensive understanding of each model's strengths and weaknesses.

To gain deeper insights into the predictive features, I focused on visualizing feature importance, with a special emphasis on the Gradient Boosting model. This step was crucial in understanding the impact of variables on predictive outcomes and refining the models accordingly.

In addition to the modeling techniques, I utilized essential tools and modules to enhance the analysis. Matplotlib and Seaborn were employed for clear visual representation, aiding in the interpretation of results. XGBoost contributed to the implementation of boosting algorithms, adding another layer of sophistication to the analysis.

Collectively, these components constituted a comprehensive and insightful examination, blending sophisticated modeling approaches with efficient tools to gain a thorough understanding of the predictive terrain.
## Results

### What is the Relationship Between Age and Sleep Efficiency?

The relationship between age and sleep efficiency was explored using scatter plots, examining various sleep-related features. In the visual representation, the scatter plot for "Sleep efficiency vs Age" indicates a diverse distribution. While there doesn't seem to be a clear linear pattern, the scatter points reveal a spread of sleep efficiency scores across different age groups. This suggests that age alone may not be the sole determinant of sleep efficiency, and other factors might contribute to the observed variations. 

![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/Age_Slpeff.png)




### How Do Lifestyle Choices, Such as Caffeine and Alcohol Consumption, Impact Sleep Efficiency?

In our exploration of sleep efficiency, we looked into how lifestyle choices, specifically caffeine and alcohol consumption, might affect our sleep. We used visualizations and numbers from a big set of sleep-related data to understand this better. For caffeine, it seemed like people who drank less had better sleep efficiency, showing a positive connection. Numbers supported this, indicating higher sleep efficiency in those with little to no caffeine.

![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/impact_of%20_caffeine.png)

Turning to alcohol, our data suggested a possible downside – higher alcohol intake might lead to lower sleep efficiency. Visual clues and numbers hinted at this trend. We also considered outliers, showing us that people respond differently. In conclusion, our findings highlight how lifestyle choices, like caffeine and alcohol, can impact sleep quality, offering insights for everyone to consider for better sleep.
 
![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/impact_of%20_alchohol.png)

### Which Model Performs Best in Predicting Sleep Efficiency?

In predicting sleep efficiency, various models were employed and assessed for their performance. Linear regression, Ridge regression, Lasso regression, and Random Forest regression were among the models evaluated. After conducting cross-validation and measuring mean squared error (MSE) and R-squared (R2) scores, it was observed that the Random Forest model exhibited the most favorable results. The Random Forest model demonstrated a lower MSE and a higher R2, suggesting superior predictive capabilities compared to the other models. This indicates that, among the models tested, the Random Forest regression model is more effective in capturing the complexities of the data and providing accurate predictions for sleep efficiency.


![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/Model_results.png)

The Random Forest model performs the best among the considered models, exhibiting the lowest MSE and the highest R2 score. This suggests that Random Forest is the most effective in predicting sleep efficiency based on the given features.

## Discussion 

The scatter plot analysis indicates a diverse distribution in the relationship between age and sleep efficiency, suggesting age alone might not be the sole determinant. Further exploration into additional factors did enhance our understanding.Reduced caffeine intake shows a positive correlation with higher sleep efficiency, while higher alcohol consumption is associated with lower sleep efficiency. Individual variations, highlighted by outliers, emphasize the need for personalized considerations.The Random Forest model excels in predicting sleep efficiency, showcasing lower mean squared error and higher R-squared scores. This indicates its effectiveness in capturing complex data patterns for accurate predictions. Future research could refine this model or explore alternative approaches.

![Ashutosh's github activity graph](https://github.com/joosmith/Witdatascience/blob/main/graph/Sleepeff_features.png)


## Summary

The relationship between age and sleep efficiency, the impact of lifestyle choices (like caffeine and alcohol) on sleep, and the best predictive model. Visualizations showed a varied age-sleep efficiency connection, highlighting the need for multiple considerations. Regarding lifestyle, less caffeine linked to better sleep, while higher alcohol suggested the opposite. The Random Forest model outshone others, boasting lower error and higher accuracy in predicting sleep efficiency. These findings stress the complexity of sleep determinants, underlining lifestyle's role and Random Forest's efficacy in forecasting sleep quality.
## Reference

https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency/code

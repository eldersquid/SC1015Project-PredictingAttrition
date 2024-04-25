# Employee Attrition Prediction

## About

This project focuses on predicting employee attrition using organizational data. We aim to build a predictive model to identify employees who are likely to leave the organization, allowing HR to intervene early with retention measures. The dataset used in this project is from Kaggle, titled "HR Analytics: Employee Attrition Prediction".

The project steps include:
1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Model Selection
5. Model Evaluation

## Content

- [HR Analytics Source Code](https://github.com/eldersquid/SC1015Project-PredictingAttrition/blob/main/hr-analytics.ipynb)
- [HR Dataset](https://github.com/eldersquid/SC1015Project-PredictingAttrition/blob/main/HR-Employee-Attrition.csv)
- [Presentation Slides](https://github.com/eldersquid/SC1015Project-PredictingAttrition/blob/e00e1064126af3ba09747599ee19669b03ee36b9/Misc_Presentation/Predicting%20Attrition%20-%20SC1015.pptx)
- [Presentation Transcript](https://github.com/eldersquid/SC1015Project-PredictingAttrition/blob/e00e1064126af3ba09747599ee19669b03ee36b9/Misc_Presentation/DATA%20SCIENCE%20MINI%20PROJECT%20TRANSCRIPT.pdf)

## Contributors

- Danish and Andrea equal in contribution as we have helped one another to complete the tasks given to us.

## Problem Definition

- Can we find the factors that contribute the most to attrition?
- Which machine learning model would be the best to predict employee attrition?
- Can we then predict employee attrition based on a dataset?

## Project Motivation

Our project is aimed at tackling the increasing rate of employee voluntary attrition. Using data analytics and machine learning techniques, we aim at predicting potential attrition cases beforehand so that the HR department can take proactive measures.

The machine learning problem is set up as a classification problem - Will an employee leave or stay? Our models predict the likelihood of employee attrition based on individual characteristics.

## Models/Techniques Used

1. SMOTE
2. Logistic Regression
3. Decision Tree Classifier
4. Random Forest Classifier
5. Feature Importance

## Conclusion

- Factors influencing attrition include: overtime work, frequent business travel, years since last promotion, job roles (e.g. sales representatives, laboratory technician)
- Logistic Regression was chosen as the optimal model due to its balance between recall and precision.
- By using the Logistic Regression model, we can identify employees with higher chances of attrition and help HR to take appropriate action to retain valuable employees.
- Balancing imbalanced datasets with SMOTE

## Recommendations

1. Evaluate workload and overtime policies to reduce stress and improve work-life balance.
2. Review business travel requirements to minimize work-life imbalance.
3. Research reasons behind high attrition rates in specific job roles (e.g., Sales Representatives, Laboratory Technicians) to develop targeted retention programs.
4. Implement programs for regular promotions and career growth opportunities.
5. Recognize importance of supportive managers and encourage longer tenure with the same manager to improve retention.

## What did we learn from this project?

- Exploratory data analysis and visualization techniques
- Handling imbalanced datasets using SMOTE resampling technique
- One-hot encoding for categorical variables
- Model selection based on accuracy, precision, recall, and F1-score
- Model training and evaluation using sklearn


## References
- [2021 US Bureau of Labor Statistics](https://www.bls.gov/news.release/archives/jolts_03092022.pdf)
- [Kaggle - HR Analytics: Employee Attrition Prediction](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction/data)
- [SMOTE: Synthetic Minority Over-sampling Technique](https://jair.org/index.php/jair/article/view/10302)
- [Precision, recall, F1 score](https://en.wikipedia.org/wiki/Precision_and_recall)
- [Logistic Regression, Decision Trees, Random Forests in Sklearn](https://scikit-learn.org/stable/index.html)

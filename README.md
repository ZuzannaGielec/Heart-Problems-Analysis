# Heart Disease Analysis with Machine Learning

**Collaborators:** [Zuzanna Gielec](https://github.com/ZuzannaGielec), [MatasGedziunas](https://github.com/MatasGedziunas?tab=overview&from=2023-12-01&to=2023-12-31), [IgnasTa](https://github.com/IgnasTa?tab=overview&from=2024-05-01&to=2024-05-29), [Imane Zagrari]

## Introduction
This project aims to analyze heart disease data using machine learning techniques. The dataset contains information about various factors related to heart health, such as age, smoking status, alcohol consumption, BMI, sleeping patterns, and physical activity. The analysis includes both descriptive statistics and the development of a machine learning model to predict the likelihood of heart disease based on the provided features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset Source](#dataset-source)
- [Analytical Queries](#analytical-queries)
- [Machine Learning Model](#machine-learning-model)
- [Presentation of Results](#presentation-of-results)

## Dataset Source
The dataset used in this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease). It provides personal key indicators of heart disease and serves as the foundation for the analytical and predictive tasks undertaken in this project.


## Analytical Queries
### Query 1: Average Age
The average age of patients with heart disease is approximately 68 years, while the average age of patients without heart disease is around 55 years.

### Query 2: Percentage of Smokers
Approximately 7.91% of smokers have heart disease.

### Query 3: Percentage of Alcohol Consumers
Around 39.64% of alcohol consumers have heart disease.

### Query 4: BMI Difference
Patients with heart disease have an average BMI of 29.49, compared to 28.62 for patients without heart disease.

### Query 5: Sleeping Time Difference
The average sleeping time for patients with heart disease is 7.04 hours, slightly higher than the average of 7.02 hours for patients without heart disease.

### Query 6: Physical Activity
Approximately 63.37% of patients with heart disease engage in physical activity.

## Machine Learning Model
### Algorithm Used
Logistic Regression was chosen as the machine learning algorithm for predicting heart disease. Categorical variables were transformed into numerical ones using StringIndexer and OneHotEncoder. The model achieved an overall accuracy of 94.9% and a specificity of 98.9%, with a sensitivity of 25%.

### Presentation of Results
- The results of the logistic regression model, including ROC AUC, accuracy, sensitivity, and specificity, are saved in a .csv file.
- The coefficients of the model, indicating the impact of each variable, are saved in another .csv file. The top 10 most important variables are also visualized using matplotlib.

## Conclusion
This analysis provides valuable insights into the factors associated with heart disease and demonstrates the effectiveness of machine learning techniques in predicting heart health based on various features.

For detailed implementation, please refer to the code in this repository.

# Project: Heart Disease Prediction Using Naive Bayes
  
## Table of Contents 
1. [Overview](#overview)
2. [Results](#results) 
3. [Data](#data)
4. [Setup](#setup)
5. [Analysis Steps](#analysis-steps)
6. [Conclusion](#conclusion)

## Overview
This project focuses on predicting the likelihood of heart disease using various predictors from a cleaned dataset. We explore the data through visualizations and build multiple Naive Bayes models—specifically, Gaussian and Multinomial—to identify which model offers the best predictive accuracy.

## Results
The Multinomial Naive Bayes model emerged as the most effective, explaining 90% of the variance between individuals with and without heart disease for both the training and test datasets, indicating no overfitting. This model exclusively utilized categorical predictors, aligning with insights gained from exploratory visualizations.

Box plots illustrated minimal differences in sleep hours between those with and without heart disease. Although a higher BMI was observed among individuals with heart disease, the difference was not substantial. Additionally, a significant proportion of heart disease cases occurred among individuals aged 50-74.

## Data
The dataset used in this analysis is derived from the 2020 CDC survey, encompassing health-related data from approximately 400,000 adults. This cleaned dataset includes 18 variables, with no missing values, and focuses on heart disease as a classification problem.

Key variables include:

- **HeartDisease:** Indicator of coronary heart disease (CHD) or myocardial infarction (MI).
- **BMI:** Body Mass Index.
- **Smoking:** Indicates whether the individual has smoked at least 100 cigarettes.
- **AlcoholDrinking:** Defines heavy drinkers based on weekly alcohol consumption.
- **Stroke:** Indicates a history of stroke.
- **PhysicalHealth:** Number of days in the past 30 days that physical health was not good.
- **MentalHealth:** Number of days in the past 30 days that mental health was not good.
- **DiffWalking:** Indicates difficulty walking or climbing stairs.
- **Sex:** Gender of the respondent.
- **AgeCategory:** Age group of the respondent.
- **Race:** Imputed race/ethnicity.
- **Diabetic:** Indicates a history of diabetes.
- **PhysicalActivity:** Indicates whether the respondent engaged in physical activity in the past 30 days.
- **GenHealth:** Self-reported general health status.
- **SleepTime:** Average hours of sleep in a 24-hour period.
- **Asthma:** Indicates a history of asthma.
- **KidneyDisease:** Indicates a history of kidney disease.
- **SkinCancer:** Indicates a history of skin cancer.

## Setup
To begin, ensure that the necessary libraries are installed and import the cleaned dataset. The data is preprocessed to convert ordinal variables into integers, facilitating the modeling process.

## Analysis Steps
1. **Data Exploration:** Utilize visualizations such as box plots and scatter plots to understand relationships between variables and the target variable.
2. **Model Development:**
   - **Gaussian Naive Bayes:** Create a model using only numerical variables.
   - **Multinomial Naive Bayes:** Create a model using only categorical variables.
   - **All Variables:** Create a model that incorporates both categorical and numerical variables.
3. **Model Evaluation:** Assess the accuracy of each model using training and test datasets to identify the best performer.

## Conclusion
All models displayed satisfactory accuracy, with the Multinomial Naive Bayes model achieving the highest performance. The Gaussian Naive Bayes model incorporating all variables showed the least accuracy, yet still maintained an over 82% accuracy rate in predicting heart disease.

This analysis provides valuable insights into the factors associated with heart disease, contributing to better understanding and potential prevention strategies.

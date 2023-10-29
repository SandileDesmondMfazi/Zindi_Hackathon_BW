
## BENK ACCOUNT ACCESS CLASSIFIER
# Predictive Pioneers - Bank Account Prediction Model
**Team Members:**
- Sandile Mfazi (Team Lead)
- Emily Shaibu
- Melissa Tshipietsile
- Ketra Molwane

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Feature Selection](#feature-selection)
- [Model Selection](#model-selection)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Deployment](#deployment)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)
- [Steps](#Steps)


---

## Introduction

Welcome to the Predictive Pioneers' Hackathon project. We are a team of final year students from the Botswana Accountancy College, passionate about data science and its applications. In this hackathon, we have developed a predictive model to determine whether an individual has a bank account or not.

## Problem Statement

In many parts of the world, financial inclusion is a critical issue. To address this problem, we aim to predict who is likely to have a bank account, which can be useful for governments, financial institutions, and policymakers to target their efforts effectively.

## Data Collection

We obtained a dataset from Zindi that contains various demographic, economic, and social information for individuals. The dataset includes features such as age, education leve, country, and more.

## Data Preprocessing

- Handling missing data: We addressed missing data points through imputation.
- Data cleaning: We removed duplicates and irrelevant columns.
- Data transformation: We scaled numerical features and one-hot encoded categorical variables.
- Outlier handling: Outliers were detected and either removed or transformed.

## Model Selection

Our selection was chosen based on the model with the lowest error rate, we experimented with various models which included SVC, Logistic regression, ANN, gradient descent, CatBoost and decision trees. After careful consideration, we chose XGBoost as our predictive model due to its excellent performance in classification tasks.

## Model Training

We split the dataset into training and testing sets (70:30), and used XGBoost library to train our model. We fine-tuned hyperparameters to optimize performance.

## Evaluation

We evaluated our model using various metrics such as accuracy, precision, recall, and F1-score.

## Conclusion

Our project aims to bring about positive change by helping identify individuals who are likely to have a bank account. This information can be utilized to design better financial inclusion programs and policies.

## Acknowledgments

We would like to thank Zindi for providing the dataset used in this project, and our mentors for their guidance and support throughout the hackathon.

##Steps

**HOW TO SET UP FOLDERS AND WHERE EACH FILE IS SAVED**
click the link to the repo and clone the repository


**ORDER IN WHICH TO RUN CODE**
the code can be run from top to bottom in its respective order 


**EXPLANATIONS OF FEATURES USED**
(SANDILE Answer)


**ENVIRONMENT FOR THE CODE TO BE RUN **
No environment in place


**HARDWARE NEEDED** 
Google Colab was used in the making of this model

**EXPECTED RUN TIME FOR EACH NOTEBOOK**


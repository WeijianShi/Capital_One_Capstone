# Capital_One_Capstone


### 1. Introduction
During 2021 summer, led by principle data scientist (<a href="mailto:zixiang.ma@capitalone.com">Zixiang Ma</a>) at Capital One, I conducted this capstone project
, focusing on constructing a model to identify the credit card fraud. 

### 2. Tech Details

#### 2.1 Imbalanced data problem
This is quite common in credit card fraud. In the collected data, less than 10% of records are fraud
cases. So certain techniques are applied to solve the imbalanced data problem, including but not limited to:
* SMOTE(Synthetic Minority Oversampling Technique)
* Oversampling / Undersampling 

#### 2.2 Machine Learning Modelling
Applied multiple machine learning binary classification algorithms, including the decision tree, random forest
, XGBoost, etc.

#### 2.3 Parameter Tuning
Applied K-fold cross-validation, after fine-tuning the model, the best model classification f1-score was <strong>75.68%</strong>, which is 
close to the industrial model's performance.

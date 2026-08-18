Health Insurance Cost Prediction

Project Overview

This project predicts health insurance charges using machine learning.
The analysis uses factors such as age, BMI, number of children, sex,
smoking status, and region to understand and predict insurance costs.

Objective

The main objective is to: - Analyze the factors affecting health
insurance charges. - Explore relationships between customer features and
insurance costs. - Build Linear Regression models. - Compare model
performance and identify the best-performing model.

Dataset Features

The project uses the following features:

Age -- Age of the policyholder

Sex -- Gender of the policyholder

BMI -- Body Mass Index

Children -- Number of children/dependents

Smoker -- Smoking status

Region -- Residential region

Charges -- Medical insurance cost (target variable)

Machine Learning Models

Three Linear Regression models were developed:

Model     Features         Test R²

Model 1   Age Only           9.70%
Model 2   Age + BMI         14.03%
Model 3   All Features      77.24%

Model 1 -- Age Only

This model uses only age to predict insurance charges.

Model 2 -- Age and BMI

This model uses age and BMI as predictors.

Model 3 -- All Features

This model uses all available features. It achieved the best performance
with a Test R² of 77.24%.

Key Observations

Insurance charges tend to increase with age.

BMI is associated with insurance charges.

Smoking status has a strong influence on insurance charges.

Using multiple features gives much better predictions than using age
alone.

Model 3 performed significantly better than Model 1 and Model 2.

Conclusion

The project shows that health insurance charges depend on multiple
factors. Among the three Linear Regression models, the All Features
model performed best, achieving a Test R² of 0.772436 (77.24%).
Therefore, considering multiple customer and health-related features
provides a more effective prediction of insurance charges.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook / Google Colab

Project Workflow

Import the dataset

Perform data exploration

Clean and preprocess the data

Perform data visualization

Build Linear Regression models

Evaluate model performance using MSE and R²

Compare the models

Select the best-performing model

Draw observations and conclusion

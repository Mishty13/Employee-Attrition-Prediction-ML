
# Employee Attrition Prediction using Machine Learning

## Overview

This project predicts whether an employee is likely to leave an organization using machine learning techniques. The analysis is based on the IBM HR Analytics Employee Attrition dataset and aims to identify the key factors influencing employee turnover.

## Project Objectives

* Analyze employee attrition patterns.
* Perform data cleaning and preprocessing.
* Explore relationships between HR factors and attrition.
* Train and compare multiple machine learning models.
* Identify the most important factors contributing to employee attrition.
* Provide actionable HR recommendations based on the findings.

## Dataset

* IBM HR Analytics Employee Attrition Dataset
* Total Records: 1,470
* Target Variable: Attrition (Yes/No)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Models

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

## Model Performance

| Model               | Accuracy | Precision |    Recall |  F1-Score |   ROC-AUC |
| ------------------- | -------: | --------: | --------: | --------: | --------: |
| Logistic Regression |    75.5% |     35.6% | **66.0%** | **46.3%** | **80.4%** |
| Random Forest       |    83.3% |     46.9% |     31.9% |     38.0% |     78.0% |
| Gradient Boosting   |    85.0% |     58.8% |     21.3% |     31.2% |     79.4% |

## Key Findings

* Overtime was the strongest predictor of employee attrition.
* Frequent business travel increased the likelihood of employees leaving.
* Sales Representatives and Laboratory Technicians were identified as high-risk job roles.
* Employees with longer periods since their last promotion were more likely to leave.
* Work-life balance and career growth significantly influenced employee retention.

## Repository Structure

```text
analysis.ipynb
HR_Attrition.csv
summary.pdf
requirements.txt
charts/
README.md
```

## Author

**Mishty Giri**

B.Tech Computer Science Student

Internship Project – XYlofy AI

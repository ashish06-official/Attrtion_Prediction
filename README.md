# AI-Powered Employee Attrition Prediction and Workforce Analytics

## Overview

Employee attrition is one of the most critical challenges faced by organizations today. Losing skilled employees can result in increased recruitment costs, reduced productivity, and loss of organizational knowledge.

This project uses Machine Learning to analyze employee data and predict whether an employee is likely to leave the organization. In addition to prediction, the project provides insights into the key factors influencing employee attrition through data analysis and feature importance evaluation.

The goal of this project is to help organizations identify at-risk employees early and take proactive measures to improve employee retention.

---

## Problem Statement

Organizations often struggle to identify employees who are likely to resign. Traditional methods rely heavily on manual observation and experience, making it difficult to detect attrition risks at scale.

This project addresses the problem by developing an intelligent prediction system capable of:

* Predicting employee attrition risk
* Identifying important factors contributing to attrition
* Supporting data-driven HR decision making
* Improving workforce retention strategies

---

## Dataset

The project uses the IBM HR Analytics Employee Attrition Dataset.

### Dataset Information

* Total Records: 1470 Employees
* Features: Employee demographics, job information, compensation details, satisfaction metrics, and work-related factors
* Target Variable: Attrition

### Target Variable

| Value | Meaning         |
| ----- | --------------- |
| 0     | Employee Stayed |
| 1     | Employee Left   |

---

## Features Used

The following features were selected for model training:

* Age
* BusinessTravel
* Department
* DistanceFromHome
* Education
* EducationField
* EnvironmentSatisfaction
* JobInvolvement
* JobLevel
* JobRole
* JobSatisfaction
* MaritalStatus
* MonthlyIncome
* NumCompaniesWorked
* OverTime
* PercentSalaryHike
* TotalWorkingYears
* WorkLifeBalance
* YearsAtCompany
* YearsInCurrentRole
* YearsSinceLastPromotion
* YearsWithCurrManager

---

## Project Workflow

### 1. Data Collection

* Load employee attrition dataset
* Inspect dataset structure
* Understand feature meanings

### 2. Data Preprocessing

* Remove unnecessary columns
* Handle categorical variables
* Label encoding
* Data cleaning
* Feature selection

### 3. Exploratory Data Analysis

* Attrition distribution analysis
* Employee demographics analysis
* Salary and experience analysis
* Satisfaction level analysis
* Correlation analysis

### 4. Data Balancing

Since attrition data is imbalanced, SMOTE (Synthetic Minority Oversampling Technique) was used to balance the dataset and improve model performance.

### 5. Model Training

The following machine learning models were evaluated:

* Decision Tree Classifier
* Random Forest Classifier

Cross-validation was performed to compare model performance.

### 6. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score
* Cross Validation

### 7. Feature Importance Analysis

Random Forest Feature Importance was used to identify the most influential factors affecting employee attrition.

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Joblib

### Development Environment

* Google Colab
* GitHub

---

## Key Insights

Analysis of employee data revealed several factors strongly associated with attrition:

* Employees working overtime are more likely to leave.
* Lower job satisfaction increases attrition risk.
* Employees with fewer years at the company tend to have higher attrition rates.
* Monthly income influences employee retention.
* Work-life balance plays a significant role in employee satisfaction and retention.

---

## Model Performance

The Random Forest Classifier achieved the best performance among the evaluated models.

Evaluation metrics include:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Cross Validation Accuracy


---

## Future Improvements

Future enhancements for the project include:

* Streamlit-based interactive web application
* Explainable AI using SHAP
* Employee retention recommendation system
* Department-wise attrition analytics dashboard
* Real-time prediction interface
* Cloud deployment

---

## Conclusion

This project demonstrates the application of machine learning in Human Resource Analytics by predicting employee attrition and identifying key factors that influence employee retention. The developed system can assist organizations in making informed workforce decisions and implementing proactive retention strategies.

---

## Author

Ashish

Artificial Intelligence and Machine Learning Student

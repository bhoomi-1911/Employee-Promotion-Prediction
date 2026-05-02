# Employee-Promotion-Prediction
Project Overview

This project focuses on predicting whether an employee will be promoted based on various factors such as performance, experience, engagement, and organizational attributes. The goal is to build and compare multiple machine learning models to support data-driven promotion decisions in organizations.

The problem is treated as a binary classification task, where:

0 → Not Promoted
1 → Promoted
Dataset Description

The dataset contains employee-related attributes such as:

Demographics: age, gender, marital status
Work details: department, years at company, role experience
Performance metrics: performance scores, KPI achievement
Behavioral metrics: engagement score, satisfaction score
Compensation: salary, bonus, stock options

The dataset is imbalanced, with significantly more non-promoted employees than promoted employees.

Workflow

The project follows a complete machine learning pipeline:

1. Data Preprocessing
Handling missing values
Encoding categorical variables
Feature scaling for models like SVM and Logistic Regression
Train-test split
2. Exploratory Data Analysis (EDA)
Class distribution analysis
Feature distribution visualization
Correlation heatmaps
Boxplots for promotion comparison
3. Feature Engineering
Creation of new features such as:
performance_growth
efficiency
promotion_gap
4. Feature Selection
SelectKBest method used
Top 10, 20, and 30 features evaluated
Machine Learning Models Used
Support Vector Machine (SVM)
Logistic Regression
Gaussian Naive Bayes
Random Forest
Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix

Special focus was given to the minority class (Promoted employees) due to dataset imbalance.

Key Results
Random Forest achieved the highest accuracy (~0.91)
SVM provided the best balance between precision and recall
Logistic Regression performed moderately well with stable results
Naive Bayes showed high recall but low precision
Best Model

Support Vector Machine (SVM) is the most suitable model because it provides the best balance between detecting promoted employees and overall performance.

Conclusion

This study demonstrates that employee promotion prediction is a challenging classification problem due to class imbalance. While ensemble methods like Random Forest achieve high accuracy, SVM provides the most balanced and reliable performance for identifying promoted employees.

Dataset link: https://www.kaggle.com/datasets/rohit8527kmr7518/employee-promtion-prediction

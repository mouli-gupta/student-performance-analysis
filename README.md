# Student Performance Analysis

A comprehensive data analytics and machine learning project that analyzes student performance data to identify the academic, demographic, and family-related factors influencing achievement and predicts students' overall academic performance using regression models.

---

## Overview

This project analyzes student performance data using **Exploratory Data Analysis (EDA)**, **Feature Engineering**, **Statistical Hypothesis Testing**, and **Machine Learning**.

The objective is to identify the factors that significantly affect student performance and build predictive models capable of estimating students' overall academic performance.

### Project Workflow

The project follows a complete end-to-end data science workflow, including data preprocessing, exploratory data analysis, feature engineering, statistical hypothesis testing, predictive modeling, model evaluation, feature importance analysis, and business recommendations.

---

## Dataset

**Source:** Student Score Dataset

**Total Records:** 30,641 

### Features

- Gender
- Ethnic Group
- Parent Education
- Parent Marital Status
- Number of Siblings
- Sports Participation
- Test Preparation
- Math Score
- Reading Score
- Writing Score

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## Data Preprocessing

The dataset was cleaned and prepared for analysis using the following preprocessing techniques:
- Removed unnecessary columns
- Handled missing categorical values using Mode Imputation
- Handled missing numerical values using Median Imputation
- Encoded categorical variables using One-Hot Encoding

---

## Exploratory Data Analysis

The project explores how various demographic, educational, and behavioral factors influence student performance.

### Analysis Performed

- Gender Distribution
- Parent Education Analysis
- Parent Marital Status Analysis
- Subject-wise Score Distribution
- Total Score Distribution
- Correlation Analysis
- Sports Participation Analysis
- Ethnic Group Distribution

### Key Observations

- Reading and Writing scores exhibit the strongest positive correlation.
- Mathematics scores are generally lower than Reading and Writing scores.
- Students whose parents have higher education levels generally perform better.
- Parent marital status has little impact on academic performance.

---

## Feature Engineering

New features were engineered to provide a more comprehensive representation of students' overall academic performance.

- Total Score
- Average Score
- Performance Categories (Poor, Average, Good, Excellent)
- Standardized Score (Z-Score)

These engineered features provide a more comprehensive measure of student performance than individual subject scores.

---

## Statistical Analysis

Statistical hypothesis testing was performed to validate findings from the exploratory analysis.

### Independent T-Test

**Objective**

Evaluate whether completing test preparation significantly improves academic performance.

**Result**

- Test preparation has a statistically significant positive impact on academic performance.
- Students who completed test preparation scored approximately **10% higher on average**.

### One-Way ANOVA

**Objective**

Evaluate whether parental education significantly influences academic performance.

**Result**

- Parent education level has a statistically significant effect on student performance.

---

## Machine Learning Modeling

Three regression models were trained and evaluated to predict students' overall academic performance:

- Linear Regression
- Decision Tree Regressor
- Tuned Random Forest Regressor

The Random Forest model was optimized using **GridSearchCV** to identify the best-performing hyperparameters.

---

## Model Evaluation

The models were evaluated using multiple regression metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- 5-Fold Cross Validation

Additional model evaluation techniques included:

- Actual vs Predicted Analysis
- Learning Curve
- Residual Analysis

The Tuned Random Forest Regressor achieved the highest predictive performance and was selected as the final model.

---

## Feature Importance Analysis

Random Forest Feature Importance was used to identify the variables that contribute most to predicting student performance.

This analysis highlights the demographic and educational factors that have the greatest influence on academic achievement.

---

## Key Insights

- Test preparation significantly improves academic performance.
- Parent education has a strong positive influence on student achievement.
- Students participating in sports tend to perform slightly better academically.
- Reading and Writing scores exhibit the strongest positive correlation.
- Male and female students demonstrate similar overall academic performance.
- The Tuned Random Forest model outperformed the other regression models.

---

## Repository Structure

The repository is organized as follows:

```text
Student-Performance-Analysis/
│
├── Student_Performance_Analysis.ipynb
├── student_score.csv
├── README.md
```
---

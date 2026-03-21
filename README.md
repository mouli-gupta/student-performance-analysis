# Student Performance Analysis

A data analysis and machine learning project focused on identifying key factors affecting student academic performance.

---

## Overview

This project explores student performance data to uncover patterns and relationships influencing scores in Math, Reading, and Writing.

The workflow includes data preprocessing, visualization, statistical testing, and predictive modeling.

Full Report: [View PDF](student_analysis.pdf)

---

## Dataset

- Source: Student Score Dataset  
- Records: 30,641  

Features include:
- Gender  
- Ethnic Group  
- Parental Education  
- Test Preparation  
- Weekly Study Hours  
- Math, Reading, Writing Scores  

---

## Tech Stack

Python  
Pandas, NumPy  
Matplotlib, Seaborn  
Scikit-learn  
SciPy  

---

## Data Preprocessing

- Missing values handled using:
  - Mode for categorical features  
  - Median for numerical features  
- Removed irrelevant columns  
- Encoded categorical variables  

---

## Exploratory Data Analysis

- Gender distribution analysis  
- Impact of parental education  
- Effect of marital status  
- Score distributions  
- Correlation analysis  

Key insights:
- Reading and Writing scores are strongly correlated  
- Math is relatively more difficult compared to other subjects  

---

## Feature Engineering

- Total Score  
- Average Score  
- Performance categories (Poor, Average, Good, Excellent)  
- Z-score normalization  

---

## Statistical Analysis

- Performed T-test to evaluate impact of test preparation  
- Test preparation has a statistically significant effect (p < 0.05)  
- Students with test preparation scored approximately 10 percent higher on average  

---

## Machine Learning Model

Model: Linear Regression  

Objective:  
Predict Math Score using demographic and behavioral features  

Performance:  
- R² Score: 0.289  
- Mean Absolute Error: 10.38  

Key drivers:
- Ethnic Group  
- Lunch Type  
- Gender  
- Parental Education  
- Sports Activity  

---

## Key Insights

- Parental education strongly impacts performance  
- Test preparation significantly improves scores  
- Sports activity shows a slight positive impact  
- Gender performance is nearly equal  
- Most students fall in the average range  

---



# Student Performance Analysis

A complete data analysis and machine learning project focused on understanding the factors affecting student academic performance using real-world data.

---

##  Overview

This project analyzes student performance data to uncover patterns, relationships, and key factors that influence scores in Math, Reading, and Writing.

The analysis includes data cleaning, visualization, statistical testing, and predictive modeling.

Full Report: [View PDF](student_analysis.pdf)

---

##  Dataset

- Source: Student Score Dataset
- Total Records: 30,641
- Features include:
  - Gender
  - Ethnic Group
  - Parental Education
  - Test Preparation
  - Weekly Study Hours
  - Scores in Math, Reading, Writing

---

##  Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Data Preprocessing

- Handled missing values using:
  - Mode (categorical features)
  - Median (numerical features)
- Removed irrelevant columns
- Encoded categorical variables for modeling

---

##  Exploratory Data Analysis

- Gender distribution analysis
- Impact of parental education on performance
- Effect of marital status (minimal impact)
- Subject-wise score distribution
- Correlation analysis between subjects

 Key Insight:
- Reading and Writing scores are highly correlated
- Math is relatively more difficult compared to other subjects :contentReference[oaicite:0]{index=0}

---

##  Feature Engineering

- Created:
  - Total Score
  - Average Score
  - Performance categories (Poor, Average, Good, Excellent)
  - Z-score for normalization

---

##  Statistical Analysis

Performed hypothesis testing using T-test:

- Test preparation has a **statistically significant impact** on performance (p < 0.05) :contentReference[oaicite:1]{index=1}
- Students who completed test prep scored **~10% higher on average** :contentReference[oaicite:2]{index=2}

---

##  Machine Learning Model

Model Used:
- Linear Regression

###  Objective:
Predict Math Score based on demographic and behavioral features

###  Performance:
- R² Score: 0.289
- Mean Absolute Error: 10.38

###  Key Drivers:
- Ethnic Group
- Lunch Type
- Gender
- Parental Education
- Sports Activity :contentReference[oaicite:3]{index=3}

---

##  Key Insights

- Parental education significantly impacts student performance
- Test preparation improves scores notably
- Sports activity has a slight positive effect
- Gender performance is nearly equal with slight variation
- Most students fall in the average performance range

---



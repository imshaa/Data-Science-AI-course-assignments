# Week 5 - Supervised Learning: Regression

## Objective
This week focused on applying **Linear Regression** to predict students’ final grades (G3) using earlier academic performance data.

---

## Dataset
**File Used:** `students.csv`  
The dataset includes student information such as grades, study time, absences, and more.  
**Target Variable:** `G3` (Final Grade)

---

## Steps Performed

### 1. Data Loading
- Loaded `students.csv` using Pandas.
- Displayed column names to understand dataset structure.

### 2. Feature Selection
- Selected features: **G1**, **G2**, and **failures**.  
- Target variable: **G3** (Final Grade).

### 3. Train-Test Split
- Split dataset into **80% training** and **20% testing** using `train_test_split()`.

### 4. Model Training
- Applied **Linear Regression** from Scikit-Learn.
- Model was trained on training data.

### 5. Model Coefficients
- Positive coefficients for `G1` and `G2` indicate higher earlier grades lead to higher final grades.  
- Negative coefficient for `failures` means more past failures lower the final grade.

### 6. Predictions
- Generated predictions for test data and displayed first 10 actual vs predicted results.

### 7. Model Evaluation
- **Mean Absolute Error (MAE):** ~0.73  
- **Root Mean Squared Error (RMSE):** ~1.15  
- Indicates predictions are close to real values with small errors.

### 8. Interpretation
- The model effectively predicts final grades based on earlier grades.  
- G1 and G2 are strong predictors; failures have an inverse impact.  
- Errors around 1–2 show that the model performs reliably for this dataset.

---

## Summary
- Built and trained a **Linear Regression model** on student performance data.  
- Identified how early grades and failures affect final grades.  
- Successfully completed **first regression-based supervised learning task**.

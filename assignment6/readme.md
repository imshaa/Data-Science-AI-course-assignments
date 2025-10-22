# Week 6: Machine Learning Classification

## Overview
In this week’s task, i have applied **classification algorithms** to predict whether a student passes or fails based on academic and personal data from the `students.csv` dataset.  
The project involved data preprocessing, model training, and performance comparison between multiple algorithms.

---

## Class Task
### Models Used:
- **Decision Tree Classifier:** A single tree that splits data using conditions like `G1`, `G2`, and `studytime` to classify pass/fail outcomes.  
- **Random Forest Classifier:** An ensemble of multiple Decision Trees combined for more accurate and stable predictions.

### Result:
Both models were trained and tested, with accuracy scores printed for performance comparison.

---

## Assignment
### Models Applied:
- **Logistic Regression:** Predicts the probability of students passing based on linear relationships in the data.  
- **Random Forest Classifier:** Reused from the class task for comparison.

### Comparison:
Each model’s accuracy was calculated and compared.  
The model with higher accuracy was considered the better performer.

---

## Key Steps:
1. **Data Preparation:**  
   Converted `G3` (final grade) into binary labels — pass (1) and fail (0).
2. **Feature Selection:**  
   Used features like `G1`, `G2`, `studytime`, `failures`, and `absences`.
3. **Train-Test Split:**  
   Split data into 80% training and 20% testing.
4. **Model Training & Evaluation:**  
   Trained models and compared their accuracy.

---

## Conclusion
Both **Logistic Regression** and **Random Forest** were effective, but **Logistic Regression** performed better in this case.

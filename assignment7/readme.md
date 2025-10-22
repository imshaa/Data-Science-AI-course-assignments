# Week 7: Model Evaluation

## Overview
In this week’s assignment, I have evaluated the performance of a **Random Forest Classifier** on the `students.csv` dataset.  
The goal was to predict whether a student passes or fails based on academic data and then analyze how well the model performs using different evaluation metrics.

---

## Class Task: Confusion Matrix & ROC Curve

### Steps Completed:
- Trained a **Random Forest Classifier** using features: `G1`, `G2`, and `studytime`.
- Generated a **Confusion Matrix** to show correct and incorrect classifications.
- Plotted a **ROC Curve** and calculated the **AUC (Area Under Curve)** score.

### Explanation:
- **Confusion Matrix:** Displays true vs. predicted outcomes for Pass and Fail cases.  
- **ROC Curve:** Visualizes how well the model distinguishes between the two classes.  
- **AUC Value:** Indicates model quality (closer to 1.0 means better performance).

---

## Assignment: Model Evaluation Metrics

### Metrics Calculated:
- **Precision:** Out of all students predicted as *Pass*, how many actually passed.  
- **Recall:** Out of all students who actually passed, how many were correctly predicted.  
- **F1 Score:** The balance between Precision and Recall (higher score means better model).

### Results:
The Precision, Recall, and F1 Scores were computed to understand the model’s strengths and weaknesses.

---

## Project Milestone & Reflection
In this project, I have analyzed that **Recall** is the most important metric.  
The reason is that identifying students likely to fail is crucial for early intervention and support.  
A higher Recall ensures that most at-risk students are detected and can be assisted in time.

---

## Summary
- Dataset: `students.csv`  
- Model Used: **Random Forest Classifier**  
- Evaluation Methods: Confusion Matrix, ROC Curve, Precision, Recall, F1 Score  
- Key Focus: Model interpretability and performance evaluation


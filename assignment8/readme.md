# Week 8: Unsupervised Learning

## Overview
In this week’s project milestone, I have applied **Unsupervised Learning** techniques to the `students.csv` dataset.  
The goal was to identify hidden patterns and group students based on their academic performance and study habits using **K-Means Clustering** and **PCA (Principal Component Analysis)**.

---

## Class Task: K-Means Clustering & PCA

### Steps Completed:
- Selected key numeric features: `G1`, `G2`, `G3`, `studytime`, and `absences`.
- Standardized the data using **StandardScaler** to bring all values to the same scale.
- Applied **K-Means Clustering** to group students into 3 clusters.
- Used **PCA** to reduce data dimensions for 2D visualization.
- Visualized the clusters to observe distinct student performance groups.

### Outcome:
Each student was assigned to a cluster (0, 1, or 2), representing different academic behavior patterns.

---

## Assignment Task: Cluster Analysis

### Cluster Insights:
I have analyzed the **average values** of features within each cluster:
- One cluster represents **high-performing students** with strong grades and study time.
- Another cluster includes **average students** with moderate performance.
- The third cluster groups **students with lower grades and higher absences**.

This analysis helped identify distinct learning groups within the dataset.

---

## Project Milestone
Through this task, I have added an **Unsupervised Learning** component to the overall project.  
By combining **K-Means Clustering** and **PCA visualization**, I discovered meaningful student patterns that can help in academic performance analysis and targeted improvement strategies.

---

## Summary
- **Dataset:** `students.csv`  
- **Techniques Used:** K-Means Clustering, PCA, StandardScaler  
- **Goal:** Discover hidden patterns in student performance  
- **Result:** Three student clusters identified based on grades, study time, and absences

# Assignment 4 – Statistics & Probability  
**Dataset:** `students.csv`

## Overview
This assignment focuses on understanding statistical measures and relationships within the dataset using **Descriptive Statistics** and **Correlation Analysis**.  
The goal was to identify which features are most related to the target variable **(G3 – Final Grade)** and interpret their predictive importance.

---

## Class Task – Basic Statistics
Performed statistical analysis on key numeric features (`G1`, `G2`, `G3`, `studytime`, `absences`, `famrel`, `freetime`).

### Calculations:
- **Mean:** Average value of each feature.  
- **Median:** Middle value representing central tendency.  
- **Mode:** Most frequent value in the data.  
- **Variance:** Measure of data spread.

**Outcome:**  
Helped understand how data is distributed and detect variations in student performance and behavior.

---

## Assignment Task – Correlation Analysis
A **correlation matrix** was generated to measure how strongly each feature relates to the final grade (**G3**).  
Then, correlation values were sorted to find the **Top 3 most related features**.

### Results:
- **Top 3 Features Most Related to G3:**  
  1. **G2 (2nd Period Grade)**  
  2. **G1 (1st Period Grade)**  
  3. **Studytime**  

These variables show the strongest positive relationship with the final grade, indicating they are key predictors of student performance.

---

## Insights & Key Takeaways
- Statistical metrics provided a clear view of data trends and variability.  
- Correlation analysis helped identify which academic factors influence success.  
- **Key Predictive Variables:** `G1`, `G2`, and `Studytime` — most useful for performance prediction.  

---

**Tools Used:** Python, Pandas, NumPy, SciPy  
**Environment:** Google Colab  

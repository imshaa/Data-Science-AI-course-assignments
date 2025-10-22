#  Week 2: Data Cleaning & Preprocessing

##  Class Task
In this class task, I have:
- Identified and removed **duplicate records** from a dataset  
- Handled **missing values** using appropriate techniques  
- Detected and treated **outliers** to improve data quality  

These steps help prepare data for accurate machine learning and statistical analysis.

---

##  Assignment Task
### Goal  
Apply data cleaning techniques on my project dataset — **Student Performance Dataset** — and generate a “before vs after cleaning” comparison.

### Project Dataset Overview  
The dataset contains student information such as grades (`G1`, `G2`, `G3`), study time, absences, family relationships, and other academic and personal factors.  
The goal of this project is to analyze and predict student performance using clean and reliable data.

---

## 🧹 Steps Performed
1. **Removed Duplicates** – Ensured each student record is unique  
2. **Handled Missing Values** –  
   - Filled numeric columns with their **mean** value  
   - Filled categorical columns with their **mode** (most common value)  
3. **Treated Outliers** – Removed extreme values using the **Interquartile Range (IQR)** method  
4. **Saved Cleaned Dataset** – Exported as `students.csv`

---

## 📊 Before vs After Cleaning Report

| Step | Description | Before Cleaning | After Cleaning |
|------|--------------|----------------|----------------|
| Shape (Rows, Columns) | Total size of dataset | 395 rows, 33 columns | 382 rows, 33 columns |
| Duplicate Rows | Repeated student entries | 3 | 0 |
| Missing Values | Incomplete or blank cells | 5 total | 0 |
| Outliers | Extreme numeric values | Present | Removed |

---

##  Final Summary
After cleaning, the dataset became **more consistent, complete, and ready for analysis**.  
This process ensures that upcoming tasks like **regression, classification, and clustering** will produce more accurate and reliable results.

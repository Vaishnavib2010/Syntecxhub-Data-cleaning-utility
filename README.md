# Syntecxhub-Data-cleaning-utility
Data cleaning and preprocessing of a diabetes dataset using Python and Pandas.

# Diabetes Data Cleaning & Preprocessing

## 📌 Project Overview
This project focuses on cleaning and preprocessing a diabetes dataset to make it ready for data analysis and machine learning tasks. The workflow ensures data consistency, correctness, and usability by handling duplicates, fixing data types, and standardizing column names.

---

## 🗂 Dataset
- **Original file:** `Diabetes Missing Data.csv`
- **Cleaned file:** `diabetes_cleaned.csv`
- The dataset contains medical and demographic attributes used for diabetes prediction.

---

## 🧹 Data Cleaning Steps
The following preprocessing steps were applied:

1. Removed duplicate records  
2. Standardized column names  
   - Converted to lowercase  
   - Replaced spaces with underscores  
   - Removed special characters  
3. Fixed incorrect data types  
   - Converted numerical columns to proper numeric types  
   - Invalid values coerced to `NaN`  
4. Exported a cleaned, analysis-ready dataset  

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas**
- **GitHub**

---

## 📁 Project Structure
diabetes-data-cleaning/
│── Diabetes Missing Data.csv
│── diabetes_cleaned.csv
│── data_cleaning.py
│── README.md

🎯 Learning Outcomes

Practical experience with real-world data cleaning
Understanding data quality issues
Writing reproducible preprocessing pipelines
Using GitHub for project version control

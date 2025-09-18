# SQL Data Cleaning, Transformation, and Analysis

## 📌 Overview
This repository demonstrates how to take **raw data** and turn it into **clean, structured, and insight-ready datasets** using SQL.  
It includes:
- Data cleaning  
- Data transformation  
- Statistical summaries (mean, median, mode, counts, distributions)  

The project reflects **real-world SQL workflows** where datasets need both **preparation** and **analysis** before they can be used for reporting or decision-making.

---

## 🔍 What This Project Covers
### 1. **Data Cleaning**
- Handling missing values (`NULL`)  
- Removing duplicates using `ROW_NUMBER()` with `PARTITION BY`  
- Standardizing string formats (e.g., trimming spaces, lower/upper casing)  
- Validating numeric ranges & applying logical business rules  

### 2. **Data Transformation**
- Creating new columns using `CASE WHEN`  
- Type conversions (string → integer, float, date)  
- Aggregating data with `GROUP BY`, `HAVING`  
- Joining multiple tables for richer datasets  

### 3. **Descriptive Statistics**
- **Mean**: `AVG()`  
- **Median**: using `PERCENTILE_CONT(0.5)` (where supported) or window functions  
- **Mode**: using `COUNT(*)` + `ORDER BY` for frequency  
- **Distribution insights**: min, max, standard deviation (`STDEV`, `VAR`)  
- Summaries using Common Table Expressions (CTEs)  

---

## 📊 Key Highlights
- Starts from **messy raw data** → ends with **analysis-ready dataset**  
- Covers **end-to-end SQL process**: cleaning → transforming → analyzing  
- Includes **statistical SQL queries** for better insights  
- Reusable SQL templates for data quality checks and descriptive stats  

---



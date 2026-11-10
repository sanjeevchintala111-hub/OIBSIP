
# Data Cleaning – Cafe Sales Dataset

**Oasis Infobyte Internship Program (OIBSIP)**  
**Domain:** Data Analytics  
**Level:** 1  
**Task:** 3 – Cleaning Data

## Project Overview

This project focuses on cleaning and preparing a messy Cafe Sales dataset for further analysis. The dataset contains missing values, inconsistent entries, incorrect data types, duplicate records, and potential outliers.

The objective is to improve data quality and produce a structured, analysis-ready dataset using Python.

## Dataset Information

- **Dataset:** `dirty_cafe_sales.csv`
- **Output:** `cleaned_cafe_sales.csv`
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Data Cleaning Process

### 1. Data Inspection
- Loaded the dataset using Pandas.
- Checked the number of rows and columns.
- Examined column names and data types.
- Identified missing values and duplicate records.

### 2. Handling Missing and Inconsistent Values
- Replaced `ERROR` and `UNKNOWN` entries with missing values.
- Converted numerical columns into appropriate numeric data types.
- Applied suitable strategies to handle missing values.
- Calculated missing `Total Spent` values using Quantity × Price Per Unit wherever possible.

### 3. Data Standardization
- Removed unnecessary leading and trailing spaces.
- Standardized categorical values.
- Converted the Transaction Date column into datetime format.
- Extracted Year, Month, and Day for further analysis.

### 4. Duplicate Removal
- Identified duplicate records.
- Removed duplicate rows where applicable.

### 5. Outlier Detection
- Used the Interquartile Range (IQR) method to identify potential outliers.
- Examined unusual values in numerical columns.
- Retained valid extreme values rather than removing them automatically.

### 6. Data Type Correction
- Converted Quantity, Price Per Unit, and Total Spent into numeric types.
- Converted Transaction Date into datetime format.

### 7. Exporting Cleaned Data
Saved the cleaned dataset as:

`cleaned_cafe_sales.csv`

## Project Structure

```text
DataAnalytics-L1-CleaningData/
│
├── dirty_cafe_sales.csv
├── cleaned_cafe_sales.csv
├── cleaning_notebook.ipynb
└── README.md
```

## Key Skills Demonstrated

- Data Cleaning and Preprocessing
- Missing Value Handling
- Duplicate Detection and Removal
- Data Standardization
- Date and Data Type Conversion
- Outlier Detection using IQR
- Python and Pandas
- Data Quality Assessment

## Conclusion

This project demonstrates the importance of data cleaning before performing data analysis. By identifying and correcting data-quality issues, the original Cafe Sales dataset was transformed into a cleaner and more consistent dataset suitable for further analysis.

---

**Internship:** Oasis Infobyte (OIBSIP)  
**Domain:** Data Analytics  
**Task:** Level 1 – Task 3

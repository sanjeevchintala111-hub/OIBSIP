
# House Price Prediction Using Linear Regression

**Oasis Infobyte Internship Program (OIBSIP)**  
**Domain:** Data Analytics  
**Level:** 2  
**Task:** 1 – Predicting House Prices with Linear Regression

## Project Overview

This project focuses on predicting house prices using a Linear Regression machine learning model.

The objective is to understand how different housing features, such as area, number of bedrooms, bathrooms, floors, location, and property condition, influence house prices and to build a model that predicts prices based on these features.

## Dataset Information

- **Dataset:** Housing Price Dataset
- **Total Records:** 2,000
- **Features:** 10 columns
- **Target Variable:** Price

### Dataset Features

| Feature | Description |
|---|---|
| Id | Unique property identifier |
| Area | Size of the house |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Floors | Number of floors |
| YearBuilt | Year the house was built |
| Location | House location |
| Condition | Property condition |
| Garage | Garage availability/details |
| Price | House price (target variable) |

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading and Inspection
- Imported the dataset using Pandas.
- Examined dataset dimensions, columns, and data types.
- Checked missing values and duplicate records.

### 2. Exploratory Data Analysis (EDA)
- Analysed numerical and categorical features.
- Explored relationships between house features and prices.
- Used visualizations to understand data distributions and patterns.

### 3. Data Preprocessing
- Prepared the dataset for machine learning.
- Converted categorical variables into numerical format using One-Hot Encoding.
- Separated independent variables (X) and target variable (y).

### 4. Model Building
- Split the dataset into training and testing sets.
- Built a Linear Regression model using Scikit-learn.
- Trained the model using the training dataset.

### 5. Model Evaluation
Evaluated model performance using suitable regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

### 6. Prediction
Used the trained Linear Regression model to predict house prices from the test dataset.

## Project Structure

```text
DataAnalytics-L2-HousePricePrediction/
│
├── housing_price_dataset.csv
├── housing_price_analysis.ipynb
└── README.md
```

## Key Skills Demonstrated

- Exploratory Data Analysis
- Data Preprocessing
- One-Hot Encoding
- Linear Regression
- Train-Test Split
- Machine Learning
- Model Evaluation
- Data Visualization
- Python and Scikit-learn

## Conclusion

This project demonstrates how Linear Regression can be applied to predict house prices using housing-related features. It provides practical experience in data preprocessing, exploratory analysis, machine learning model development, and performance evaluation.

---

**Internship:** Oasis Infobyte (OIBSIP)  
**Domain:** Data Analytics  
**Task:** Level 2 – Task 1

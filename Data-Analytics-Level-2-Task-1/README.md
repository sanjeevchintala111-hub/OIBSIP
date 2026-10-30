
# House Price Prediction – Linear Regression

## Project Overview
This project focuses on predicting house prices using Machine Learning techniques. It uses a dataset containing information about house size, number of bedrooms, bathrooms, floors, year built, location, condition, and garage availability.

The objective is to build a **Linear Regression model** that predicts house prices based on these features.

## Internship Details
- **Organization:** Oasis Infobyte
- **Program:** AICTE Oasis Infobyte Internship
- **Level:** Level 2
- **Task:** Task 1 – House Price Prediction

## Dataset Information
- **Total Records:** 2,000
- **Total Original Columns:** 10
- **Target Variable:** `Price`

### Features Used
- Area
- Bedrooms
- Bathrooms
- Floors
- YearBuilt
- Location
- Condition
- Garage

The `Id` column was removed because it does not provide meaningful information for price prediction.

## Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded and explored the dataset.
2. Performed data quality checks for missing and duplicate values.
3. Conducted Exploratory Data Analysis (EDA).
4. Visualized house price distributions and feature relationships.
5. Converted categorical variables using One-Hot Encoding.
6. Split the dataset into training and testing sets.
7. Trained a Linear Regression model.
8. Predicted house prices using the test dataset.
9. Evaluated model performance.
10. Performed residual analysis and visualized feature coefficients.

## Model Evaluation
The model was evaluated using the following metrics:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination

The actual evaluation values are available in the Jupyter Notebook output.

## Project Structure
```text
Data-Analytics-Level-2-Task-1/
│
├── house_price_prediction.ipynb
├── README.md
└── House Price Prediction Dataset.csv
```

*Note: The dataset file can be kept locally rather than uploaded to GitHub. If it is not included, provide its source in this README.*

## Conclusion
This project demonstrates how Linear Regression can be applied to a house price prediction problem. It covers the complete basic machine learning workflow, from data exploration and preprocessing to model training, prediction, and evaluation.

The project provided practical experience with Python-based data analysis and supervised machine learning.

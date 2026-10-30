
# Customer Segmentation Analysis

## Oasis Infobyte Internship – Level 1, Task 2

## 1. Project Overview

Customer Segmentation Analysis is a data analytics project that groups customers based on their purchasing behaviour.

The objective is to identify different types of customers using RFM (Recency, Frequency, and Monetary) analysis and K-Means clustering.

This analysis helps businesses understand customer behaviour and develop targeted marketing strategies.

## 2. Dataset

**Dataset:** Online Retail Dataset

**File:** `Online Retail.xlsx`

The dataset contains retail transaction records, including:
- Invoice Number
- Invoice Date
- Customer ID
- Quantity
- Unit Price

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 4. Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Handling Missing Values and Duplicate Records
4. Removing Cancelled Transactions and Invalid Quantities
5. Calculating Total Transaction Amount
6. RFM Analysis
7. Feature Transformation using Log Scaling
8. Feature Standardization
9. Elbow Method for Cluster Evaluation
10. K-Means Clustering
11. Customer Segment Profiling
12. Data Visualization

## 5. RFM Analysis

RFM analysis evaluates customers using three important metrics:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How many unique orders a customer placed.
- **Monetary:** The total amount spent by a customer.

## 6. Customer Segmentation Results

A total of **4,338 customers** were grouped into four clusters using K-Means clustering.

| Cluster | Customers | Customer Segment |
|---|---:|---|
| 0 | 879 | Recent, lower-spending customers |
| 1 | 700 | High-value, frequent customers |
| 2 | 1,171 | Moderate-value customers |
| 3 | 1,588 | Inactive or at-risk customers |

### Business Recommendations

- **Cluster 0:** Encourage repeat purchases through personalized offers.
- **Cluster 1:** Provide loyalty rewards and exclusive benefits.
- **Cluster 2:** Improve engagement through targeted promotions.
- **Cluster 3:** Use reactivation campaigns to encourage customers to return.

## 7. Project Files

```text
Data-Analytics-Level-1-Task-2/
│
├── customer_segmentation.ipynb
├── customer_rfm_segments.csv
├── customer_segment_profiles.csv
└── README.md
```

- `customer_segmentation.ipynb` – Complete analysis and visualizations.
- `customer_rfm_segments.csv` – Customer-level RFM values and cluster assignments.
- `customer_segment_profiles.csv` – Summary of customer segments.
- `README.md` – Project documentation.

## 8. Conclusion

This project demonstrates how data analytics and machine learning techniques can be used to understand customer purchasing behaviour.

By combining RFM analysis with K-Means clustering, customers can be grouped into meaningful segments, helping businesses make better marketing and customer-retention decisions.

---

**Internship:** Oasis Infobyte  
**Program:** Data Analytics Internship  
**Task:** Level 1 – Task 2  
**Project:** Customer Segmentation Analysis

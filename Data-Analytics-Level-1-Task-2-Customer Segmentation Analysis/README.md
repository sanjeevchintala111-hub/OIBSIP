# Customer Segmentation Analysis

## OIBSIP – Level 1, Task 2 | Data Analytics Internship

### Project Overview

This project focuses on segmenting an e-commerce company's customer base based on purchasing behaviour using **RFM Analysis and K-Means Clustering**.

The objective is to identify different customer groups and understand their purchasing patterns to help businesses develop targeted marketing strategies and improve customer retention.

### Dataset Information

- **Dataset:** Online Retail Dataset
- **Source:** UCI Machine Learning Repository
- **Original Records:** 541,909
- **Columns:** 5
- **Customers Identified After Cleaning:** 4,338

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Workflow

1. **Data Loading and Inspection**
   - Loaded the Online Retail dataset.
   - Examined dataset dimensions, data types and missing values.

2. **Data Cleaning**
   - Handled missing Customer IDs.
   - Removed duplicate records.
   - Prepared transaction data for customer-level analysis.

3. **RFM Analysis**

   Used three important customer behaviour metrics:

   - **Recency:** How recently a customer made a purchase.
   - **Frequency:** How frequently a customer purchased.
   - **Monetary:** How much money a customer spent.

4. **Feature Scaling**
   - Applied StandardScaler to standardise RFM features.

5. **K-Means Clustering**
   - Used the Elbow Method to determine the optimal number of clusters.
   - Applied K-Means clustering with 4 clusters.

6. **Customer Segmentation**
   - Analysed customer groups.
   - Calculated cluster profiles.
   - Compared customer purchasing behaviour.

7. **Visualisation and Insights**
   - Visualised customer segments.
   - Analysed cluster sizes.
   - Identified opportunities for targeted marketing.

### Clustering Results

The K-Means algorithm identified four customer segments.

| Cluster | Number of Customers |
|---|---:|
| Cluster 0 | 879 |
| Cluster 1 | 700 |
| Cluster 2 | 1,171 |
| Cluster 3 | 1,588 |
| **Total** | **4,338** |

### Key Business Applications

- Identify high-value customers.
- Develop targeted marketing campaigns.
- Improve customer retention.
- Identify customers who may need re-engagement.
- Support data-driven business decisions.

### Project Files

```text
DataAnalytics-L1-CustomerSegmentation/
│
├── Online Retail.xlsx
├── customer_segmentation.ipynb
├── customer_rfm_segments.csv
├── customer_segment_profiles.csv
└── README.md
```

### Conclusion

This project demonstrates how RFM analysis and K-Means clustering can be used to understand customer purchasing behaviour and divide customers into meaningful groups.

The resulting customer segments can help businesses improve marketing strategies, strengthen customer relationships and make better business decisions.

---

**Internship:** AICTE Oasis Infobyte Internship Program  
**Track:** Data Analytics  
**Level:** Level 1  
**Task:** Task 2 – Customer Segmentation Analysis

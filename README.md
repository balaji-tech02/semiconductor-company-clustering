# Semiconductor Company Segmentation Using K-Means Clustering

## Overview

This project applies **K-Means Clustering**, an unsupervised machine learning technique, to segment semiconductor companies based on their financial performance. By analyzing key financial indicators such as revenue, operating income, operating margin, research and development (R&D) expenditure, and capital expenditure (CAPEX), the project identifies natural groupings of companies and uncovers hidden business patterns.

The analysis follows a complete machine learning workflow, including data exploration, preprocessing, feature transformation, cluster evaluation, and business interpretation.

---

## Business Problem

Semiconductor companies differ significantly in terms of financial performance and investment strategy. Understanding these differences can help investors, analysts, and decision-makers identify companies with similar financial characteristics.

The objective of this project is to group companies into meaningful segments without using predefined labels.

---

## Dataset

**Dataset:** `chip_companies_financials.csv`

### Features Used

| Feature | Description |
|---------|-------------|
| Revenue | Annual company revenue (USD Billion) |
| Operating Margin | Operating profit margin (%) |
| Operating Income | Annual operating income (USD Billion) |
| R&D Spend | Research and Development expenditure (USD Billion) |
| CAPEX | Capital expenditure (USD Billion) |

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Methodology

The project was completed using the following workflow:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Correlation Analysis
4. Feature Selection
5. Log Transformation of Skewed Features
6. Feature Scaling using StandardScaler
7. Determining the Optimal Number of Clusters
   - Elbow Method
   - Silhouette Score
8. K-Means Clustering
9. Cluster Profiling
10. Business Interpretation

---

## Exploratory Data Analysis

The dataset was explored to understand the distribution and relationships between financial variables.

The analysis included:

- Distribution of financial metrics
- Correlation heatmap
- Identification of skewed variables
- Log transformation for highly skewed features
- Feature scaling before clustering

---

## Clustering Model

**Algorithm**

- K-Means Clustering

**Cluster Evaluation**

- Elbow Method
- Silhouette Score

**Optimal Number of Clusters**

- **K = 2**

---

## Results

The model identified two distinct groups of semiconductor companies.

### Cluster 0

- Higher revenue
- Higher operating income
- Higher R&D investment
- Higher CAPEX

This cluster represents large, established semiconductor companies with significant financial resources and investment capacity.

### Cluster 1

- Lower revenue
- Lower operating income
- Lower R&D investment
- Lower CAPEX

This cluster represents relatively smaller companies with more limited financial resources.

---

## Key Insights

- Semiconductor companies naturally separate into two financial segments.
- Revenue, R&D expenditure, and CAPEX are the strongest differentiating features.
- Larger companies consistently invest more in research and infrastructure.
- K-Means successfully identified meaningful business segments suitable for strategic analysis.

---

## Repository Structure

```
semiconductor-company-clustering/

├── 01_chip_companies_financials.csv
├── 02_Semiconductor_Company_Clustering_Using_KMeans.ipynb
└── README.md
```

---

## Future Improvements

- Compare K-Means with Hierarchical Clustering and DBSCAN.
- Apply Principal Component Analysis (PCA) for visualization.
- Build an interactive dashboard.
- Incorporate additional financial and operational variables.
- Evaluate cluster stability using alternative validation metrics.

---

## Author

**Balaji Elangovan**

 Machine Learning Engineer | Data Science Enthusiast

---

## Acknowledgement

This project was developed as part of a machine learning portfolio to demonstrate practical applications of unsupervised learning for business analytics and company segmentation.

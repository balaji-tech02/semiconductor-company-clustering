# Semiconductor Company Segmentation Using K-Means Clustering

## Project Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment semiconductor companies based on their financial characteristics. By analyzing key financial metrics, the project identifies natural groupings of companies and uncovers hidden patterns that support business analysis and strategic decision-making.

---

## Business Objective

The objectives of this project are to:

- Segment semiconductor companies into meaningful groups based on their financial performance.
- Identify hidden patterns among companies using unsupervised learning.
- Compare the financial characteristics of different company segments.
- Generate business insights through cluster profiling.

---

## Dataset

**Dataset Used:** `chip_companies_financials.csv`

### Features

- Revenue (USD Billion)
- Operating Margin (%)
- Operating Income (USD Billion)
- R&D Spend (USD Billion)
- Capital Expenditure (USD Billion)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

```
Business Objective
        ↓
Data Loading
        ↓
Feature Selection
        ↓
Exploratory Data Analysis
        ↓
Correlation Analysis
        ↓
Log Transformation
        ↓
Feature Scaling
        ↓
Elbow Method
        ↓
Silhouette Score
        ↓
K-Means Clustering
        ↓
Cluster Profiling
        ↓
Business Insights
        ↓
Conclusion
```

---

## Exploratory Data Analysis

The following analyses were performed before clustering:

- Distribution analysis of financial variables
- Correlation analysis
- Log transformation for highly skewed features
- Feature scaling using StandardScaler

---

## Machine Learning

### Algorithm

- K-Means Clustering

### Cluster Evaluation

- Elbow Method
- Silhouette Score

### Optimal Number of Clusters

- K = 2

---

## Cluster Interpretation

The clustering algorithm identified **two distinct groups** of semiconductor companies based on their financial characteristics.

### Cluster 0

Characteristics:

- Higher revenue
- Higher operating income
- Higher R&D expenditure
- Higher capital expenditure

Represents larger, well-established semiconductor companies.

### Cluster 1

Characteristics:

- Lower revenue
- Lower operating income
- Lower R&D expenditure
- Lower capital expenditure

Represents smaller or mid-sized semiconductor companies.

---

## Key Findings

- Company size is the primary factor driving segmentation.
- Larger companies invest significantly more in research and capital expansion.
- Financial investment patterns clearly distinguish the two clusters.
- K-Means successfully identified meaningful business segments suitable for competitive benchmarking.

---

## Business Applications

This project can support:

- Company segmentation
- Competitive benchmarking
- Investment research
- Business strategy
- Market analysis
- Industry intelligence

---

## Repository Structure

```
Semiconductor-Company-Segmentation-Using-KMeans/
│
├── chip_companies_financials.csv
├── Semiconductor_Company_Segmentation_Using_KMeans.ipynb
├── README.md
└── images/ (optional)
```

---

## Future Improvements

- Compare K-Means with Hierarchical Clustering and DBSCAN.
- Apply Principal Component Analysis (PCA) for cluster visualization.
- Experiment with additional financial and operational features.
- Develop an interactive dashboard for cluster exploration.

---

## Author

**Balaji Elangovan**

Machine learning Engineer 

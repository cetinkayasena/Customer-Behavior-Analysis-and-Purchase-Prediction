```markdown
# Modeling Customer Behavior to Predict Purchase Success from Session Data

## Project Overview

This project focuses on analyzing customer behavior in e-commerce platforms to predict purchase success and segment customers effectively. Using two distinct datasets, the study investigates user actions at both session-level and customer-history-level to build interpretable and accurate machine learning models. The outcomes provide valuable insights for enhancing marketing strategies and personalized customer targeting.

---

## Methodology

- **Data Sources:**
  - **Dataset 1:** User session data with behavioral metrics such as page views, session duration, bounce rate, and a binary target variable `Revenue` indicating purchase success. Contains 12,230 records.
  - **Dataset 2:** Historical billing records (2010-2011), including customer ID, invoice date, quantity, and unit price, used for customer segmentation via RFM analysis.

- **Data Processing:**
  - Cleaning and preprocessing (missing values, categorical encoding, SMOTE for class imbalance).
  - Feature engineering (one-hot encoding for categorical variables, RFM variable creation).
  - Scaling numerical variables for clustering.

- **Modeling:**
  - Machine learning models applied: Logistic Regression, Random Forest, and XGBoost.
  - Addressed class imbalance with SMOTE.
  - Models evaluated with multi-dimensional metrics: accuracy, recall, F1-score, ROC-AUC.
  - Explainability supported via SHAP analysis.

- **Segmentation:**
  - Behavioral segmentation based on visitor type (new vs returning visitors).
  - Customer segmentation using RFM scoring and K-Means clustering.
  - Clusters visualized with PCA and Elbow method for determining cluster numbers.

- **Ethics & Privacy:**
  - Data anonymized and used in compliance with GDPR and ethical research standards.
  - Focus on aggregate user behavior; no personal identification performed.

---

## Key Findings

- XGBoost achieved the best predictive performance with ROC-AUC of 0.918.
- New visitors showed more distinct behavioral patterns allowing better purchase predictions.
- RFM-based segmentation identified four main customer groups with varied behavioral characteristics.
- SHAP analysis highlighted the most impactful features influencing purchase decisions, such as page values and exit rates.

---

## Visualizations

- Correlation matrix and heatmaps for variable relationships.
- ROC curves for model discrimination performance.
- SHAP summary plots and dependence charts.
- Cluster visualizations via PCA scatter plots.
- Radar, bar charts, and confusion matrices for model insights.

---

## How to Use This Repository

1. Clone the repository:
```

git clone [https://github.com/cetinkayasena/Modeling-Customer-Behavior-to-Predict-Purchase-Success.git](https://github.com/cetinkayasena/Modeling-Customer-Behavior-to-Predict-Purchase-Success.git)

```
2. Explore datasets and Jupyter notebooks for detailed analysis.
3. Reproduce modeling and segmentation steps using the provided notebooks.
4. Review visualizations and performance metrics.

---

## References

- Sakar, C., & Kastro, K. (2018). [Dataset reference for session data].
- Chen, Y. (2015). [RFM analysis and customer segmentation].

---

## Contact

For any questions or collaboration, please contact:  
Sena Çetinkaya - seenaacetinkaya@gmail.com

---

*This project adheres to ethical standards and ensures the privacy of all data subjects involved.*

```

---

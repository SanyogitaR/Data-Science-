# 🧠 Customer Segmentation Using Unsupervised Machine Learning

This project applies **unsupervised machine learning (K-Means Clustering)** to segment customers based on their demographic and purchasing behavior. The goal is to help businesses better understand their customers for more effective targeting and engagement.

---

## 📌 Objective

To group customers into meaningful clusters using unsupervised learning, enabling insights into shopping habits, income levels, and lifestyle choices.

---

## 📊 Dataset Overview

- Total Records: **2240 customers**
- Features include:
  - Demographics: Age, Marital Status, Education, Income
  - Children at Home: `Kidhome`, `Teenhome`
  - Enrollment Year
  - Spending habits across various product categories

---

## 🧰 Tools & Libraries

- Python
- Pandas
- Seaborn / Matplotlib
- Scikit-learn

---

## 🔍 Workflow

1. **Data Cleaning**
   - Removed duplicates and null values
   - Handled categorical data through encoding

2. **Feature Scaling**
   - Applied MinMaxScaler for normalization

3. **Clustering**
   - Applied **K-Means Clustering**
   - Used dimensionality reduction (e.g., PCA or t-SNE) for visualization

4. **Cluster Validation**
   - Elbow Method helped estimate the range
   - Final model trained with **5 clusters** (as validated visually and by silhouette score)

---

## 📈 Results

- ✅ **5 customer segments** identified
- Each segment groups customers by behavioral and financial patterns
- Allows for actionable business insights like:
  - High spenders with children
  - Young, single, low spenders
  - Older customers with premium tastes, etc.

---

## 📸 Cluster Visualization

Here’s the t-SNE visualization of the 5 clusters:



Each dot represents a customer, grouped visually by similarities across multiple variables.

---

## 💼 Applications

- 🎯 **Targeted Marketing** — Run campaigns tailored to specific clusters
- 🛍️ **Product Recommendations** — Personalize offerings per segment
- 💬 **Customer Retention** — Identify churn-prone clusters
- 📊 **Business Intelligence** — Inform product stocking and regional strategies




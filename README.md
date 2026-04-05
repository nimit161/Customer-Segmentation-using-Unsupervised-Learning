# 🛒 Customer Segmentation using Unsupervised Learning

## 📌 Project Overview

In this project, I performed **customer segmentation** using unsupervised machine learning techniques to identify distinct groups of customers based on their behavior.

The dataset contains customer-related attributes such as **Age, Annual Income, and Spending Score**, which were used to uncover hidden patterns without any predefined labels.

---

## 🎯 Problem Statement

Businesses often struggle to understand:

* Which customers are most valuable
* How different customers behave
* How to target customers effectively

This project aims to solve this by grouping customers into meaningful segments.

---

## 📊 Dataset Description

The dataset includes the following features:

* **CustomerID** – Unique identifier
* **Gender** – Male/Female
* **Age** – Customer age
* **Annual Income (k$)** – Yearly income
* **Spending Score (1–100)** – Customer spending behavior

---

## ⚙️ Tools & Libraries

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🔍 Workflow

### 1. Data Exploration

* Checked dataset structure and summary statistics
* Visualized distributions of Age, Income, and Spending Score
* Identified relationships between features

---

### 2. Data Preprocessing

* Selected relevant features for clustering
* Encoded categorical variables (Gender)
* Applied **StandardScaler** to normalize data

---

### 3. Clustering Approach

* Applied **K-Means Clustering**
* Used **Elbow Method** to determine optimal number of clusters

---

### 4. Dimensionality Reduction

* Applied **PCA (Principal Component Analysis)**
* Reduced data to 2D for visualization

---

### 5. Cluster Visualization

* Visualized customer groups using scatter plots
* Clearly separated clusters based on behavior

---

## 🧠 Key Insights

The model identified distinct customer segments:

* 💰 **High Income – High Spending**
  → Premium customers, target with exclusive offers

* 💸 **Low Income – High Spending**
  → Deal-driven customers, respond well to discounts

* 🧍 **Average Customers**
  → Require engagement strategies

* 💤 **Low Spending Customers**
  → Potential churn, need attention

---

## 🎯 Outcome

Instead of predicting a target variable, this project:

* Discovered hidden customer groups
* Transformed raw data into actionable insights
* Helped define **data-driven marketing strategies**

---

## 📈 Key Learnings

* Understanding data without labels
* Importance of feature scaling in clustering
* Choosing optimal clusters using Elbow Method
* Translating clusters into business insights

---

## 🚀 Future Work

* Apply **DBSCAN** for density-based clustering
* Build a **recommendation system** on top of segments
* Deploy model using **Streamlit**
* Use real-world large-scale datasets

---

## 📂 Project Structure

```id="g7k9pz"
├── data/
│   └── customer_segmentation.csv
├── notebook/
│   └── customer_segmentation.ipynb
├── README.md
```

---

## 🤝 Connect

If you found this project useful, feel free to connect or contribute!

---

## ⭐ Support

Give this repo a ⭐ if you like it!

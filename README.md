# 🛒 Customer Segmentation using Machine Learning

## 📌 Overview

This project focuses on **Customer Segmentation** using Machine Learning techniques like **PCA, K-Means, and Agglomerative Clustering**.

The goal is to group customers based on their behavior, spending patterns, and demographics to help businesses make better marketing decisions.

---

## 📂 Dataset

* Dataset: SmartCart Customers Dataset
* Contains customer information such as:

  * Income
  * Spending on products
  * Education
  * Marital Status
  * Recency
  * Response

---

## ⚙️ Steps Performed

### 1. Data Preprocessing

* Handled missing values
* Feature engineering:

  * Age calculation
  * Total Spending
  * Customer Tenure
  * Total Children
* Removed unnecessary columns 

---

### 2. Feature Engineering

* Converted categorical features:

  * Education grouped into levels
  * Marital status converted to "Living_With"

---

### 3. Encoding & Scaling

* One-Hot Encoding for categorical features
* Standard Scaling for normalization

---

### 4. Dimensionality Reduction

* Applied **PCA (Principal Component Analysis)** to reduce dimensions
* Visualized data in **3D space**

---

### 5. Clustering Techniques

* K-Means Clustering
* Agglomerative Clustering

---

### 6. Finding Optimal Clusters

* Elbow Method (WCSS)
* Silhouette Score

---

### 7. Visualization

* 3D Cluster Visualization
* Heatmaps
* Pairplots
* Cluster-wise analysis

---

## 📊 Results

* Optimal clusters found using Elbow & Silhouette methods
* Customers grouped into distinct segments
* Clear patterns observed in spending and income

---

## 🧠 Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 🚀 Future Improvements

* Deploy model using Streamlit / Flask
* Add real-time prediction
* Use advanced clustering (DBSCAN, HDBSCAN)

---

## 🙌 Conclusion

This project demonstrates how Machine Learning can be used to **analyze customer behavior and improve business strategies**.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

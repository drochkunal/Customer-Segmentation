# Customer Segmentation using K-Means

## 📌 Overview

This project performs customer segmentation on an online retail dataset to identify distinct customer groups based on purchasing behavior.
The goal is to help businesses understand customers and enable targeted marketing strategies.

---

## 📊 Dataset

* Dataset: Online Retail Dataset
* Source: Kaggle
* Link: https://www.kaggle.com/datasets/tunguz/online-retail

Note:

* The original dataset (~45 MB) is not included due to size limitations.
* The project can run using a sample dataset if provided.

---

## 🧠 Methodology

### 1. Data Cleaning

* Removed missing values
* Filtered invalid transactions (negative quantities, cancelled orders)

### 2. Feature Engineering

* Created a new feature:

  * `TotalPrice = Quantity × UnitPrice`

* Built RFM features:

  * **Recency** → Days since last purchase
  * **Frequency** → Number of transactions
  * **Monetary** → Total spending

---

### 3. Clustering (K-Means)

* Applied K-Means clustering algorithm
* Used Elbow Method to determine optimal number of clusters
* Segmented customers into meaningful groups

---

## 📈 Results & Insights

* Identified different types of customers:

  * High-value customers
  * Frequent buyers
  * Low-engagement customers

* These insights can help in:

  * Personalized marketing
  * Customer retention strategies
  * Revenue optimization

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## ▶️ How to Run

1. Download dataset from Kaggle
2. Place `Online Retail.csv` in project folder
3. Run the notebook

---

## 📌 Key Learnings

* Data preprocessing and cleaning
* Feature engineering using RFM analysis
* Unsupervised learning with K-Means
* Extracting business insights from data

---

## 🚀 Future Improvements

* Try advanced clustering (DBSCAN, Hierarchical)
* Build an interactive dashboard
* Add customer lifetime value prediction

# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** on the `Mall_Customers.csv` dataset to segment mall customers based on their **Annual Income** and **Spending Score**. The goal is to help businesses better understand customer behavior and create targeted marketing strategies.

---

## 📊 Problem Statement

Businesses often treat all customers the same, but customer behavior varies widely based on their spending habits and income. By segmenting customers into distinct groups, companies can:

- 🎯 Target ads more effectively  
- 🤝 Personalize services  
- 📈 Boost customer retention  

---

## 💡 Features Used for Clustering

- **Annual Income (k$)**  
- **Spending Score (1–100)**  

---

## 🧪 Steps Involved

### 1. Data Preprocessing
- Checked for missing and duplicate values
- Cleaned the dataset

### 2. Exploratory Data Analysis (EDA)
- Visualized data distributions
- Selected relevant features for clustering

### 3. Finding Optimal Number of Clusters
- Used the **Elbow Method**
- Optimal clusters determined: `n = 7`

### 4. Modeling
- Applied `KMeans` from scikit-learn with `n_clusters=7`
- Visualized results using 2D scatter plots

### 5. Cluster Interpretation
Identified distinct customer types such as:
- High-income, low spenders  
- Low-income, high spenders  
- Average customers, etc.

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer_segmentation.git
   cd customer_segmentation
    ```
2. Install the required dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the script:
   ```
   python customer_segmentation.py
   ```

# 🍷 K-Means Clustering on Wine Quality Dataset

Machine Learning project implementing the **K-Means Clustering** algorithm to analyze and group wine characteristics based on physicochemical properties using unsupervised learning techniques.

---

## 📌 Project Overview

This project explores the application of the **K-Means clustering algorithm** on the Wine Quality dataset.  
The main objective is to identify natural groupings within the dataset based on wine attributes such as acidity, alcohol content, pH, sulphates, and more.

The workflow includes:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Elbow Method for optimal cluster selection
- K-Means model training
- Cluster visualization
- Correlation analysis

---

## 📂 Dataset

Dataset used in this project:

- **WineQT Dataset**
- Contains physicochemical properties of wine samples
- Numerical features suitable for clustering analysis

### Features Used

| Feature |
|---|
| Fixed Acidity |
| Volatile Acidity |
| Citric Acid |
| Residual Sugar |
| Chlorides |
| Free Sulfur Dioxide |
| Total Sulfur Dioxide |
| Density |
| pH |
| Sulphates |
| Alcohol |

---

## 🧠 Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to partition data into several clusters based on similarity.

The algorithm works by:

1. Selecting the number of clusters *(K)*
2. Initializing centroids
3. Calculating distances between data points and centroids
4. Updating centroids iteratively
5. Repeating until convergence

---

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning Library |

---

## 📊 Data Preprocessing

The preprocessing steps performed include:

- Removing duplicate data
- Feature selection
- Data normalization using `StandardScaler`
- Correlation analysis using heatmap visualization

---

## 📈 Elbow Method

The **Elbow Method** is used to determine the optimal number of clusters.

```python
for i in range(1, 11):
    kmeans = KMeans(n_clusters=i, random_state=0)

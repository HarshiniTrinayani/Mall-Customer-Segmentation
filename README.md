# 🛍️ Mall Customer Segmentation Using Unsupervised Learning

## 📌 Project Overview

This project focuses on segmenting mall customers based on their annual income and spending score using **Unsupervised Machine Learning Algorithms**.

Customer segmentation helps businesses understand customer behaviour, identify different spending patterns, and develop targeted marketing strategies.

Three clustering algorithms are implemented and compared:
- K-Means Clustering
- Hierarchical (Agglomerative) Clustering
- DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

## 🎯 Objectives

- Explore and understand customer data.
- Apply different unsupervised learning algorithms.
- Visualize customer clusters.
- Compare clustering performance using evaluation metrics.
- Identify meaningful customer segments.

## 📊 Dataset

**Mall Customers Dataset**

The dataset contains customer information, including:

| Feature | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands |
| Spending Score (1-100) | Spending score assigned by the mall |

Dataset Source: [Mall Customers Dataset – GitHub](https://raw.githubusercontent.com/ffzs/dataset/master/Mall_Customers.csv)

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

## 🧠 Algorithms Implemented

### 1. K-Means Clustering
- Partitions customers into clusters.
- Uses the Elbow Method to determine the optimal number of clusters.
- Visualizes the resulting customer segments.

### 2. Hierarchical Clustering
- Uses Agglomerative Clustering.
- Builds a hierarchical structure of customer groups.
- Uses a dendrogram to visualize cluster formation.

### 3. DBSCAN
- Density-based clustering algorithm.
- Uses EPS and MinPts parameters.
- Identifies dense customer groups and noise points.

## 📈 Model Evaluation

The clustering algorithms are evaluated using:

- **Silhouette Score:** Measures how well-separated the clusters are.
- **Davies-Bouldin Index:** Measures similarity between clusters. Lower values indicate better separation.

## 📂 Project Structure

```text
Mall-Customer-Segmentation/
│
├── Mall_Customer_Segmentation.ipynb
├── README.md
└── Mall_Customer_Segmentation_Report.docx
```

## 🚀 How to Run

1. Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/Mall-Customer-Segmentation.git
```

2. Navigate to the project folder:

```bash
cd Mall-Customer-Segmentation
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook Mall_Customer_Segmentation.ipynb
```

5. Run all cells to execute the clustering algorithms and generate visualizations.

## 🔍 Expected Outcome

The project demonstrates how unsupervised learning techniques can group customers based on similarities in their income and spending behaviour.

The resulting clusters can help businesses understand different customer categories and support data-driven marketing decisions.

## 👩‍💻 Project Information

**Subject:** Unsupervised Learning Algorithms

**Project Title:** Mall Customer Segmentation Using Unsupervised Learning Algorithms

**Language:** Python

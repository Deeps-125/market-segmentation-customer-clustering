# Market Segmentation using Customer Clustering

## 📌 Project Overview

This project is an Unsupervised Machine Learning project that uses K-Means Clustering to segment customers based on their demographic and purchasing behavior.

The objective is to identify different groups of customers with similar characteristics and spending patterns.

## 🛠️ Tech Stack & Tools

* Python
* Pandas
* Scikit-Learn
* Matplotlib
* K-Means Clustering
* Google Colab

## 📊 Dataset

The project uses the Marketing Campaign dataset containing customer demographic and purchasing information.

The main features used for clustering are:

* Age
* Income
* Total Children
* Total Spending

Since this is an unsupervised learning project, there is no predefined target variable.

## 🤖 Machine Learning Approach

The project follows these steps:

1. Load the dataset
2. Handle missing values
3. Create relevant customer features
4. Standardize the data using StandardScaler
5. Determine the number of clusters using the Elbow Method
6. Apply K-Means Clustering
7. Evaluate the clusters using the Silhouette Score
8. Analyze cluster centers
9. Visualize customer segments
10. Use PCA for 2D cluster visualization

## 📈 Results

The K-Means algorithm groups customers into different segments based on their demographic and purchasing characteristics.

The project includes:

* Elbow Method visualization
* Silhouette Score
* Cluster Centers
* Customer Cluster Visualization
* PCA-based Cluster Visualization

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Upload `marketing_campaign.csv` to the Colab environment.
3. Run all the cells.
4. View the clustering results and visualizations.

## 📁 Project Structure

```text
Market-Segmentation-Customer-Clustering/
│
├── market_segmentation.ipynb
└── README.md
```

## 🎯 Project Objective

The main objective of this project is to apply Unsupervised Machine Learning techniques to identify meaningful customer segments based on demographic and purchasing behavior.

# Customer Segmentation ML Project 

## 📌 Project Overview

This repository demonstrates a **Customer Segmentation Machine Learning Project** using the **K-Means Clustering** algorithm.  
The goal is to group similar customers based on their demographic and behavioral attributes — such as Annual Income and Spending Score — to extract meaningful customer segments for targeted marketing strategies.

K-Means is an unsupervised learning algorithm that identifies natural groupings in data by minimizing the distance between data points and cluster centroids. :contentReference[oaicite:1]{index=1}

---

## 📊 Dataset

The dataset used in this project is `Mall_Customers.csv`, which typically contains fields such as:

| Column           | Description |
|------------------|-------------|
| CustomerID       | Unique customer identifier |
| Gender           | Customer gender |
| Age              | Customer age |
| Annual Income    | Annual income (in k$) |
| Spending Score   | Spending score assigned by the mall |

> This dataset is commonly used for customer segmentation examples and can also be sourced from Kaggle. :contentReference[oaicite:2]{index=2}

---

## 🚀 Features

✔ Load and explore the customer dataset  
✔ Preprocess the data (handling missing values, selecting relevant features)  
✔ Apply the **Elbow Method** to determine the optimal number of clusters  
✔ Train the **K-Means Clustering** model  
✔ Visualize and interpret the resulting customer clusters

---

## 🧠 Methodology

1. **Data Loading & Exploration**  
   Load the dataset and review basic statistics and structure.

2. **Data Preprocessing**  
   Select numerical variables and scale features if needed.

3. **Finding Optimal K (Elbow Method)**  
   Plot Within-Cluster Sum of Squares (WCSS) against different `k` values to identify the elbow point.

4. **K-Means Clustering**  
   Apply the K-Means algorithm with the chosen number of clusters.

5. **Analysis & Visualization**  
   Visualize the clusters using scatter plots and interpret groups.

---

## 🛠 Technologies Used

| Technology | Use |
|------------|-----|
| Python     | Programming language |
| NumPy      | Numerical computations |
| Pandas     | Data manipulation |
| Matplotlib | Visualization |
| scikit-learn | Machine Learning (K-Means) |
| Jupyter Notebook | Workflow & documentation |

---



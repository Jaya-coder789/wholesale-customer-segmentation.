# 🤖 Wholesale AI

## ML-Based Wholesale Customer Segmentation

Wholesale AI is a **Machine Learning-based customer segmentation and analytics web application** that analyzes wholesale customer purchasing behavior and groups customers with similar spending patterns.

The system uses **K-Means Clustering** to perform customer segmentation and **PCA (Principal Component Analysis)** to visualize the resulting clusters in a 2D space.

---

## 📌 Project Overview

Wholesale businesses have customers with different purchasing behaviors. Some customers purchase large quantities, while others have moderate or low spending.

Wholesale AI analyzes customer spending across different product categories and automatically identifies groups of customers with similar purchasing behavior.

The application provides an interactive dashboard for:

* Customer analysis
* Customer segmentation
* Data exploration
* Data preprocessing
* Cluster analysis
* PCA visualization
* Model performance evaluation
* Segment comparison
* Business recommendations
* Business insights

---

## 🎯 Objectives

The main objectives of the project are:

1. Analyze wholesale customer purchasing patterns.
2. Clean and preprocess customer spending data.
3. Standardize numerical features for Machine Learning.
4. Determine a suitable number of clusters.
5. Apply K-Means Clustering to segment customers.
6. Use PCA for 2D cluster visualization.
7. Compare customer segments.
8. Generate business insights and recommendations.
9. Provide an easy-to-use web dashboard.

---

## 🧠 Machine Learning Workflow

```text
Customer Dataset
       ↓
Exploratory Data Analysis
       ↓
Data Preprocessing
       ↓
Feature Selection
       ↓
Standardization
       ↓
Elbow Method
       ↓
Silhouette Score
       ↓
Select Best K
       ↓
K-Means Clustering
       ↓
Customer Segments
       ↓
PCA
       ↓
2D Cluster Visualization
       ↓
Business Insi
```
------

## 🔄Technologies Used

* Python
* Pandas and NumPy
* Scikit-learn
* Matplotlib and Seaborn
* Streamlit (if used)

----

## 🧠 Machine Learning Algorithms

* K-Means Clustering: Groups customers with similar spending patterns.
* PCA: Reduces data dimensions for 2D visualization.
* Elbow Method: Helps select the number of clusters.
* Silhouette Score: Evaluates cluster quality.

----

## 🔄 Workflow

 * Dataset → Data Preprocessing → Feature Scaling
      *   → Elbow Method → K-Means Clustering
       *  → PCA Visualization → Business Insights

        

## 📁Project Structure
        
Wholesale-AI/
├── data/
│   └── wholesale_customers.csv
├── app.py
├── requirements.txt
└── README.md

----

## Results

The system groups customers based on their spending behavior and visualizes the resulting clusters using PCA.

## Expected outcomes:

* Identification of customer segments.
* Better understanding of purchasing patterns.
* Data-driven business insights.

----

## 💡Business Insights

* Identify high-spending customer groups.
* Understand product category preferences.
* Support targeted marketing strategies.
* Improve customer relationship management.
* Support inventory planning.

----

## ⚙️ Installation and Usage

1. Clone the repository

git clone <your-repository-url>

2. Install dependencies

pip install -r requirements.txt

3. Run the application (if using Streamlit)

streamlit run app.py

---
## ✅ Conclusion

Wholesale AI uses Machine Learning to analyze customer purchasing behavior and group similar customers using K-Means Clustering. PCA helps visualize customer segments, while the Elbow Method and Silhouette Score help evaluate clustering quality. This project helps businesses understand customer spending patterns, improve marketing strategies, and make better data-driven decisions.

----

## 👩‍💻 Author

Jaya Bhunte
Artificial Intelligence and Data Science Engineering Student.




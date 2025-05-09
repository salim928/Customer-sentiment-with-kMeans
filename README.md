# Customer Segmentation using K-Means Clustering
An end-to-end data science project uncovering actionable insights from customer purchase behavior.

## 📌 Overview
This project implements K-Means clustering to segment customers based on their purchasing patterns, using the RFM (Recency, Frequency, Monetary Value) framework. Key steps included exploratory data analysis (EDA), feature engineering, model optimization, and strategic recommendations.

## 🛠️ Tools & Technologies
*Python Libraries*: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly

*Clustering Algorithm*: K-Means (optimized with Elbow Method and Silhouette Analysis)

*Visualization*: Violin plots, scatter plots, RFM histograms

## 📂 Project Steps
### 1. Exploratory Data Analysis (EDA)
Analyzed distributions of purchase amounts, time intervals, and customer demographics.

Identified outliers and surprising trends (e.g., a small group of high-frequency, low-spend customers).

### 2. Data Cleaning
Handled missing values, duplicate records, and inconsistent formatting.

Normalized scales for monetary values and time-based features.

### 3. Feature Engineering
Built RFM metrics:

Recency: Days since last purchase

Frequency: Total number of purchases

Monetary Value: Total spending per customer

### 4. Modeling & Optimization
Applied K-Means clustering and determined optimal clusters (k=4) using:

Elbow Method (inertia vs. cluster count)

Silhouette Analysis (cluster separation quality)

### 5. Advanced Visualization
Violin plots to compare RFM distributions across clusters.

3D Scatter plots (Recency vs. Frequency vs. Monetary) to visualize segment separation.

### 6. Actionable Insights
Segmented customers into 4 distinct groups (e.g., "High-Value Loyalists," "At-Risk Customers").

Recommended targeted strategies:

Personalized discounts for "At-Risk" customers.

Loyalty programs for "High-Value" segments.

##  📊 Results
Cluster Visualization Example: 3D visualization of customer segments

## 🚀 Future Work
Implement DBSCAN to detect non-spherical clusters.

Integrate time-series analysis for dynamic segmentation.

## 🔍 Explore the Code
Full implementation: Jupyter Notebook

Dataset: data/raw/purchase_history.csv

Key Enhancements:
Structure: Broken into clear sections (Overview, Tools, Steps, Results).

Technical Depth: Added specifics like k=4 and library names.

Reproducibility: Linked to hypothetical notebook/dataset paths (update with your actual files).

Visuals: Placeholder for images (replace with your plots).

Call-to-Action: Encourages exploration of your code.

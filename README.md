# Zeotap
# **Customer Segmentation and Analysis Project**

This project focuses on performing **Exploratory Data Analysis (EDA)**, **Lookalike Modeling**, **Customer Segmentation** using clustering techniques, and utilizing advanced machine learning models such as **XGBoost** and **Contrastive Learning** on a customer dataset. The objective of this analysis is to gain meaningful business insights and perform segmentation to help improve business strategies.

## **Table of Contents**
1. [Introduction](#introduction)
2. [Data Overview](#data-overview)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - Customer Distribution by Region
   - Trend of Customer Signups Over Time
   - Average Spending per Transaction
   - Product Distribution by Category
4. [Lookalike Model](#lookalike-model)
5. [Clustering Analysis](#clustering-analysis)
   - Clustering Techniques Used
   - PCA and Dimensionality Reduction
   - Clustering Results and Evaluation Metrics
6. [Machine Learning Models](#machine-learning-models)
   - XGBoost
   - Contrastive Learning


## **Introduction**
The goal of this project is to perform customer segmentation analysis using various machine learning techniques such as **Exploratory Data Analysis (EDA)**, **Lookalike Modeling**, **Clustering**, and **Advanced Machine Learning Models** like **XGBoost** and **Contrastive Learning**. We aim to provide meaningful insights into customer behavior, sales trends, and effective customer engagement strategies to help improve business outcomes.

## **Data Overview**
The dataset used for this analysis includes various customer attributes such as **demographics**, **purchase history**, **spending behavior**, and **transaction data**. This data was analyzed to derive key insights about customer trends, product performance, and revenue generation.

## **Exploratory Data Analysis (EDA)**

### **Customer Distribution by Region**
The analysis of the customer distribution by region shows that:
- **South America** has the highest number of customers, followed by **Europe**, **North America**, and **Asia**.
- This distribution indicates the regions with the highest customer engagement and provides insights into potential markets for expansion.

### **Trend of Customer Signups Over Time**
The analysis of customer signups from 2022 to 2024 indicates:
- **An upward trend** in customer signups each year, with the number of signups peaking in 2024.
- The **growth rate** is positive, with an increasing number of customers each year.

### **Average Spending per Transaction**
The graph depicting average spending over time shows:
- **Fluctuating trends**, but with an overall **upward movement**.
- The **average spending per transaction** in the most recent month is **757.04**.

### **Product Distribution by Category**
The distribution of products by category shows:
- **Books** have the highest number of products, followed by **Electronics**, **Clothing**, and **Home Decor**.

## **Lookalike Model**
The **Lookalike Model** was created to identify customer segments that are similar to existing high-value customers. This model helps businesses target similar users to increase sales and engagement. The results of the lookalike analysis have been used to generate targeted marketing strategies.

## **Clustering Analysis**

### **Clustering Techniques Used**
For customer segmentation, the following clustering techniques were used:
1. **Agglomerative Clustering**
2. **KMeans Clustering**
3. **Affinity Propagation**
4. **Self-Organizing Maps (SOM)**

Each technique was evaluated using **DB Index** to assess the cluster quality.

### **PCA and Dimensionality Reduction**
Before applying clustering algorithms, **Principal Component Analysis (PCA)** was used to reduce the dimensionality of the dataset. The following steps were taken:
- **Standardization of Data**: Ensured all features were on the same scale.
- **PCA Transformation**: Reduced the number of features while preserving key information.
- **Cluster Analysis**: Applied clustering techniques to the reduced data to improve performance and visualization.

### **Clustering Results and Evaluation Metrics**
After applying clustering algorithms and PCA, the following results were observed:
- **Number of Clusters**: The optimal number of clusters was determined based on the silhouette scores and DB index values.
- **DB Index Values**:
  - **Agglomerative Clustering**: 0.9088
  - **KMeans Clustering**: 0.9141
  - **Affinity Propagation**: 1.0199
  - **Self-Organizing Map**: 0.7494

These DB Index values helped evaluate the quality of the clusters formed by each algorithm. The lower the DB Index, the better the clustering.

## **Machine Learning Models**

### **XGBoost**
**XGBoost** was employed as a powerful machine learning model for predicting customer behavior. After training the model on the dataset, it achieved a **100% test accuracy**. The model performed excellently, indicating its high predictive capability and robustness in handling large datasets.

### **Contrastive Learning**
**Contrastive Learning** was utilized to enhance the model's understanding of customer segments and their relationships. This technique uses a **self-supervised learning** approach to identify similarities and dissimilarities between customer pairs, which helped in identifying unique segments. The model achieved a **75.05% accuracy**.

These machine learning models played a crucial role in enhancing the segmentation and prediction tasks, providing valuable insights for customer targeting and engagement.





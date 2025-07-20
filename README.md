# Predictive-Data-Analysis-for-SME-Customer-Relationship-Management
This project performs an in-depth analysis of customer data to identify distinct customer segments and build a predictive model to forecast customer churn. The goal is to understand customer behavior, proactively identify customers at risk of churning, and inform targeted marketing and retention strategies.

## Project Overview

The analysis involves several key steps:

1.  **Data Loading and Exploration:** Loading the customer dataset and performing initial explorations to understand its structure, identify missing values, and examine descriptive statistics.
2.  **Data Preprocessing:** Handling missing data by imputation and checking for duplicates.
3.  **Customer Segmentation (Clustering):** Applying K-Means clustering to segment customers based on various behavioral and demographic attributes. The optimal number of clusters is determined using the Elbow Method.
4.  **Cluster Analysis and Visualization:** Analyzing the characteristics of each identified cluster and visualizing them using techniques like PCA and box/count plots to understand the different customer segments.
5.  **Customer Churn Prediction:** Building a classification model (Random Forest Classifier) to predict customer churn based on the available features. The model performance is evaluated using metrics like accuracy, ROC AUC, confusion matrix, and classification report.
6.  **Churn Risk Identification and Visualization:** Identifying high-risk customers based on the prediction model's output and visualizing the distribution of churn probability across clusters and key features.
7.  **Feature Importance Analysis:** Analyzing the importance of different features in predicting churn to understand the key drivers of customer attrition.
8.  **KPI Calculation and Visualization:** Defining and visualizing relevant Key Performance Indicators (KPIs) such as overall churn rate, churn rate by cluster, and average cashback amount by cluster.
9.  **Tailored Marketing Strategies and Sales Growth Opportunities:** Developing targeted strategies for customer retention and sales growth based on the insights gained from segmentation and churn prediction.

## Dataset

The dataset used in this project contains various customer attributes, including demographic information, purchasing behavior, engagement metrics, and churn status.

## Technologies and Libraries Used

*   Python
*   Pandas (for data manipulation and analysis)
*   NumPy (for numerical operations)
*   Matplotlib (for data visualization)
*   Seaborn (for enhanced data visualization)
*   Scikit-learn (for preprocessing, clustering, and machine learning models)

## Key Findings

*   Distinct customer clusters were identified with varying characteristics and churn rates.
*   Customer churn probability differs significantly across clusters.
*   Key features influencing churn prediction include Tenure, Cashback Amount, and Warehouse to Home distance.
*   The churn prediction model demonstrates strong performance in identifying potential churners.
*   Analysis of KPIs provides insights into overall churn and cluster-specific behaviors.

## How to Use

To run this analysis, you will need to have Python and the required libraries installed. The notebook can be run in environments like Google Colab or a local Jupyter Notebook setup.

1.  Clone the repository (if applicable).
2.  Ensure you have the `DatAI.xlsx` file in the correct directory or upload it as prompted in the notebook.
3.  Run the notebook cells sequentially to execute the analysis.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvements, please open a pull request or an issue.

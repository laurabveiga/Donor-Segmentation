# Donor Segmentation & Unsupervised Machine Learning Pipeline

## Project Overview
This repository contains an end-to-end unsupervised machine learning and behavioral segmentation pipeline developed in Python. The objective is to identify distinct donor profiles, optimize fundraising engagement strategies, and uncover underlying donation patterns using customer behavioral and transactional datasets.

## Key Technical Features
* **Exploratory Data Analysis & Data Quality Assurance:** Systematic ingestion, null-value imputation, identification and treatment of outliers, and distribution checks using Pandas and NumPy.
* **Feature Engineering & Transformation:** Logarithmic transformations and robust scaling (StandardScaler / RobustScaler) applied to address high feature skewness and variance differences across donation metrics.
* **Dimensionality Reduction:** Principal Component Analysis (PCA) implemented to reduce multi-collinearity, project high-dimensional behavioral features, and analyze cumulative explained variance.
* **Clustering Architecture & Evaluation:** Comparative clustering implementations using K-Means and Hierarchical/Agglomerative Clustering. Cluster validity was evaluated using Elbow curves (Inertia) and Silhouette Score analysis to determine optimal cluster separation.
* **Visual Data Dissemination:** Comprehensive diagnostic visualizations scripted using Matplotlib and Seaborn, including correlation heatmaps, PCA component scatter plots, and cluster feature distribution comparisons.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## Repository Structure
* `Machine Learning.ipynb`: Full analytical notebook containing the data preprocessing, model execution, cluster evaluation, and statistical visual outputs.
* `README.md`: Project documentation and methodology summary.

## Author
* **Laura Borges Veiga, Inês Brunheta, Rihanna Jamal, and Mariana Caldeira** — Information Management Students at NOVA IMS
* LinkedIn: [linkedin.com/in/laura-veiga-student](https://www.linkedin.com/in/laura-veiga-student)

# Supply Chain Late Delivery Risk 🔴⚠️ ![license](https://img.shields.io/github/license/Pegah-Ardehkhani/SupplyChain-LateDeliveryRisk.svg) <a href="https://colab.research.google.com/github/Pegah-Ardehkhani/SupplyChain-LateDeliveryRisk/blob/main/Late%20Delivery%20Risk.ipynb" target="_parent\"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> [![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.org/github/Pegah-Ardehkhani/SupplyChain-LateDeliveryRisk/blob/main/Late%20Delivery%20Risk.ipynb)

<p align="center">
  <img width="550" height="450" src="https://zeorouteplanner-blog.s3.ap-south-1.amazonaws.com/wp-content/uploads/2021/02/Plan-optimized-routes-with-Zeo-Route-Planner.gif">
</p>

## Dataset 📔

[DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

## About

This project analyzes and predicts late deliveries in a supply chain dataset using **machine learning models**. The goal is to identify the risk of late delivery for orders based on features like customer, product, shipping, and sales data.

Key components of the project:

* **Exploratory Data Analysis (EDA):** Understand the dataset, feature distributions, and relationships.
* **Data Preprocessing:** Handle missing values, encode categorical variables, and extract features from dates.
* **Predictive Modeling:** Implemented multiple classifiers including Random Forest, Logistic Regression, XGBoost, Decision Tree, and K-Nearest Neighbors to predict `Late_delivery_risk`.
* **Evaluation:** Used metrics such as accuracy, recall, F1-score, confusion matrix, and ROC-AUC for performance comparison.
* **Feature Importance & Explainability:** Analyzed feature contributions using Random Forest importance, LIME, SHAP, and counterfactual explanations with DiCE.

This project provides a complete pipeline for **risk prediction in supply chain management**, helping stakeholders identify potential late deliveries and optimize operations.

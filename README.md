# Comprehensive Retail Anomaly Detection Project

## Project Overview
This project implements and compares multiple anomaly detection approaches on retail sales data to identify unusual sales patterns that may indicate business issues.

## Problem Statement
Detecting anomalies early in retail sales helps businesses prevent losses and make informed decisions. The goal is to evaluate domain-specific, statistical, and machine learning methods for robustness.

## Dataset
- Retail sales data covering multiple stores and products
- Daily sales aggregated for anomaly analysis
- Not included in repo for privacy - a sample file and data description are present

## Methods Implemented
1. SQL-Based Business Rules: Domain-specific threshold rules in a SQL database
2. Statistical Methods: Z-Score, Interquartile Range (IQR), and Modified Z-Score calculations
3. Machine Learning Methods: Isolation Forest, One-Class SVM, Local Outlier Factor (LOF)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

## Key Results
- Statistical IQR method achieved perfect F1-Score of 1.0 on test data
- Machine learning methods showed good detection but with some false positives
- SHAP explainability identified important features like total sales, volatility, and days with zero sales as key anomaly indicators

## Usage Instructions
1. Install required packages:
2. Run the Jupyter Notebook in `notebooks/Comprehensive_Retail_Anomaly_Detection.ipynb` to reproduce analysis and visualizations.

## Exports
- Processed metrics and results are saved in `Exports/` folder
- Sample datasets and snapshots are in `datasets/`

## Visualizations & Explainability
- Key plots and dashboards are embedded in the notebook
- SHAP values explain model decisions clearly for stakeholder trust

---

Feel free to explore, reproduce, and extend this project for retail anomaly detection use cases.

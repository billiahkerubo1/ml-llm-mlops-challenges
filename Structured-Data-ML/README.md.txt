# Part 1: Structured Data & Machine Learning Challenge

---

## Problem Statement

This part involves working with structured sales data to:

- Clean and prepare the dataset for machine learning.
- Forecast daily total sales for store-category combinations.
- Perform customer (store) segmentation based on available features.

---

## Files Included

- `part1-solution.ipynb` — Jupyter Notebook containing the full code.
- `part1-report.pdf` — Detailed report of methodology, insights, and results.

---

## Challenge Breakdown

### 1. Data Preprocessing 

- Load and clean the dataset, handling missing values appropriately.
- Perform exploratory data analysis (EDA) to understand patterns and relationships.
- Engineer relevant features to improve model performance (e.g., date features, lag variables).
- Prepare the data for modeling through encoding, scaling, etc.

### 2. Sales Forecasting 

- Develop a machine learning model to forecast **daily total_sales** for each **store-category** combination.
- Create a **14-day sales forecast** for January 2024 (extending beyond the dataset).
- Evaluate the model using appropriate metrics (e.g., MAE, RMSE).
- Analyze feature importance to identify key drivers of sales.

### 3. Customer Segmentation

- Segment stores into meaningful groups using clustering techniques (e.g., K-Means).
- Provide actionable insights for each segment.
- Suggest store-specific strategies based on the segmentation analysis.



Requirements:
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- RandomForest



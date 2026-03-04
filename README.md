Customer & Marketing Analytics: ROI, Segmentation, and Churn Prediction
Project Overview

This project demonstrates an end-to-end data analytics pipeline for a simulated ride-hailing business (BG-Ride). It focuses on transforming raw transactional and marketing spend data into actionable business insights, specifically targeting budget optimization and customer retention.
Key Features

    ROI Attribution: Calculated Return on Investment (ROI) across multiple marketing channels (Facebook, Google, TikTok) to identify the most efficient spend.

    Customer Segmentation: Implemented RFM (Recency, Frequency, Monetary) analysis combined with K-Means Clustering (K=4) to categorize customers into 4 tiers: Platinum, Gold, Silver, and Bronze.

    Predictive Churn Modeling: Utilized the BG/NBD Model (via PyMC-Marketing) to estimate the probability of customers being "alive" and identified a 43% dropout rate after the first purchase.

    Automated Data Pipeline: Built a structured workflow in Python for data loading, quality validation, feature engineering, and automated export of at-risk customer lists.

Tech Stack

    Language: Python 

    Libraries: Pandas, NumPy, Scikit-learn, PyMC-Marketing, Matplotlib, Seaborn

    Data Format: Parquet (for efficient storage and processing)

Business Insights & Impact

    Budget Reallocation: Identified Facebook as the top-performing channel with 1.77x ROI, leading to a recommendation to pause TikTok (0.99x) and reallocate budget to Facebook. 

    Retention Strategy: Identified 88 high-value (Platinum/Silver) customers at critical churn risk (p_alive<0.30) for immediate CRM intervention. 

How to Use

    Data: Ensure marketing_spend.parquet and customer_transactions.parquet are in the project folder.

    Execution: Run main.ipynb to process the data and generate analysis results.


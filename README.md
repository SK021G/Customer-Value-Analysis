# Customer Value Analysis using RFM & Regression

## Project Overview
This project transforms transactional retail data into actionable insights using RFM segmentation and predictive modeling.

## Business Context
* **Challenge:** Inefficient marketing spend and lack of revenue forecasting capabilities.
* **Objective:** Segment customers for targeted campaigns and predict Customer Lifetime Value (CLV).

## Key Features
* **RFM Segmentation:** Customers grouped into "High-Value", "At-Risk", etc., using Recency, Frequency, and Monetary scores.
* **Predictive CLV:** Built a Linear Regression model to predict future spend based on purchase history.
    * *Note:* The model achieves **R² ~ 0.88** on high-frequency customer cohorts, demonstrating strong predictability for loyal segments and 0.42 on general data.
* **Power BI Ready:** Output data is structured for direct dashboard integration.

## Tools Used
* Python (Pandas, Scikit-Learn)
* Online Retail II Dataset (UCI ML Repository)

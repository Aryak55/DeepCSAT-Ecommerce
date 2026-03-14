# DeepCSAT-Ecommerce
Deep Learning ANN model to predict e-commerce customer satisfaction (CSAT) scores from support interaction data — with EDA, feature engineering, and deployment-ready prediction pipeline.
# DeepCSAT: E-Commerce Customer Satisfaction Score Prediction

## Overview
Deep Learning ANN model to predict CSAT scores (1–5) for e-commerce customer support interactions on the Shopzilla platform.

## Dataset
~85,907 customer support records with features including channel, category, agent tenure, shift, and response time.

## Models Used
- Logistic Regression (baseline)
- Random Forest
- **ANN (Deep Learning)** — Best performer

## Key Findings
- Agent tenure is the #1 predictor of CSAT
- Returns/Reverse Pickup is the lowest-CSAT category
- Morning shift outperforms Night shift consistently

## How to Run
1. Clone the repo
2. Install dependencies: `pip install tensorflow scikit-learn pandas numpy matplotlib seaborn`
3. Run `DeepCSAT_Ecommerce_CSAT_Prediction.ipynb` top to bottom

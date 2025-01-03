# ONLINE-PAYMENT-FRAUD-DETECTION-USING-MACHINE-LEARNING-MODEL-FOR-BLOSSOM-BANK
## Project Overview
This project focuses on building a robust machine learning model to predict online payment fraud for Blossom Bank, a multinational financial services group headquartered in London. Fraud detection is critical to prevent financial losses and maintain trust among customers.

## Table of Contents
1. [Introduction](#introduction)
2. [Executive Summary](#executive-summary)
3. [Data Analysis and Feature Engineering](#data-analysis-and-feature-engineering)
4. [Machine Learning Models](#machine-learning-models)
5. [Visualization and Insights](#visualization-and-insights)
6. [Model Evaluation](#model-evaluation)
7. [Conclusion and Recommendations](#conclusion-and-recommendations)
8. [Future Work](#future-work)

---

## Introduction
Fraud detection is a critical business process to identify and mitigate scams. This project develops a machine learning-based solution for predicting fraudulent transactions, thereby protecting customers and businesses.

---

## Executive Summary
Blossom Bank's goal was to predict online payment fraud using historical transaction data. 

### Key Steps:
1. Data collection, preprocessing, and verification.
2. Exploratory Data Analysis (EDA) to identify patterns and relationships.
3. Feature engineering with one-hot encoding for categorical variables.
4. Model training and evaluation using:
   - Logistic Regression
   - Random Forest
   - Decision Tree
   - K-Nearest Neighbors

The Random Forest model outperformed others with an accuracy of **99.97%** and a recall score of **87%**, making it the optimal choice for deployment.

---

## Data Analysis and Feature Engineering
### Key Insights:
- Transaction types like `cash_out` and `transfer` are most associated with fraud.
- Fraudulent transactions are relatively rare but have distinct characteristics.
- Features like `balance before` and `balance after` transactions are highly correlated.

### Steps Taken:
1. Handled missing values and verified data types.
2. Conducted univariate, bivariate, and multivariate analyses.
3. Performed feature engineering using one-hot encoding.

---

## Machine Learning Models
### Algorithms Used:
1. **Logistic Regression**
2. **Random Forest** - Best performer with **99.97% accuracy**.
3. **Decision Tree**
4. **K-Nearest Neighbors**

Models were trained on 80% of the data and tested on the remaining 20%. Cross-validation confirmed the superior performance of the Random Forest model.

---

## Visualization and Insights
### Key Findings:
- Most transactions are non-fraudulent.
- Fraudulent transactions are concentrated in specific ranges and transaction types (`cash_out`, `transfer`).
- The dataset is imbalanced, requiring careful model evaluation.

#### Example Graphs:
1. **Transaction Distribution:** Fraud vs. Non-Fraud
2. **Correlation Heatmap:** Relationships between features
3. **Transaction Type Analysis:** Fraudulent vs. Common transactions

![Screenshot 2025-01-03 101437](https://github.com/user-attachments/assets/09a836a4-c601-4034-a6c4-27a8af90de8d)

![Correlation Heatmap](link_to_graph_image_2)

---

## Model Evaluation
### Random Forest Performance:
- **Accuracy:** 99.97%
- **Precision:** 99%
- **Recall:** 87%
- **Cross-Validation Recall:** 87%

### Decision Tree Performance:
- **Accuracy:** 99.96%
- **Precision:** 82%
- **Recall:** 82%

Random Forest was selected for deployment due to its high recall score, crucial for minimizing false negatives.

---

## Conclusion and Recommendations
### Key Recommendations:
1. Deploy the Random Forest Classifier.
2. Implement fraud prevention measures:
   - Two-factor authentication.
   - Frequent PIN/password updates.
   - Alerts for unaccounted transactions.
3. Employ a data engineer to ensure dataset quality and balance.

---

## Future Work
- Enhance data preprocessing to address outliers and imbalance.
- Explore advanced machine learning models like XGBoost or Neural Networks.
- Incorporate real-time fraud detection with streaming data.

---

Thank you for exploring this project! For any inquiries, feel free to contact [Ketan Arora](mailto:your_email@example.com).

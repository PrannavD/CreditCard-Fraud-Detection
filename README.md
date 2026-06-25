# Credit Card Fraud Detection System

## Overview
This project implements a machine learning solution to detect fraudulent credit card transactions. Utilizing a dataset of over 284,000 transactions, the system addresses extreme class imbalance to provide reliable anomaly detection for financial security.

## Technical Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Imbalanced-learn
- **Algorithm:** Logistic Regression (Classification)
- **Techniques:** Under-sampling, Train-Test Splitting, Feature Engineering

## Key Challenges & Solutions
- **The Imbalance Problem:** The original dataset contained only 0.17% fraud cases. A naive model would achieve 99% accuracy by simply predicting 'Legit' every time. 
- **The Solution:** I implemented a strategic **Under-Sampling** method to create a balanced sub-sample, allowing the model to learn the specific nuances of fraudulent patterns without being overwhelmed by legitimate data.

## Performance Results
- **Training Accuracy:** 100%
- **Test Accuracy:** 98.9%
- **Model Reliability:** The high test accuracy indicates excellent generalization, making it a viable prototype for real-time transaction monitoring.

## How to Run
1. Clone the repository.
2. Ensure `creditcard.csv` is in the root directory.
3. Run the notebook in Google Colab or a local Jupyter environment.

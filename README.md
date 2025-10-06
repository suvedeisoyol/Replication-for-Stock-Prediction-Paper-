# Replication-for-Stock-Prediction-Paper

**Final Project for Math 4130: Introduction to Machine Learning**

This project replicates and critically evaluates a peer-reviewed paper on stock trend forecasting. While the original study reported promising predictive performance, our analysis reveals that its results were likely overstated due to improper validation techniques.

Specifically, the original paper failed to account for the time series nature of stock price data, applying random train-test splits that violate temporal integrity. This led to data leakage and inflated performance metrics.

By re-implementing the model with proper time-aware validation (e.g., walk-forward or rolling windows), we demonstrate that the predictive accuracy drops significantly—highlighting the importance of respecting temporal structure in financial modeling.

## Key Contributions
- Reproduction of original model architecture and training pipeline
- Diagnosis of methodological flaws in validation strategy
- Re-evaluation using time series–appropriate validation
- Discussion of implications for future financial ML research

## Authors
Suvedei Soyol-Erdene  
Baruch College – Math 4130  
Fall 2024

# Project Summary

This project implements advanced time series forecasting with deep learning (LSTM/Transformer)
on the Electricity Load Forecasting dataset. It integrates uncertainty quantification
using Monte Carlo Dropout and Quantile Regression.

## Key Deliverables
- Complete runnable Python code for preprocessing, modeling, training, and evaluation
- Analysis report comparing point forecast accuracy vs. interval calibration
- Summary table with RMSE, MAPE, Coverage Probability, Interval Width

## Results
- MC Dropout produced calibrated intervals with ~95% coverage
- Quantile Regression offered deterministic inference with competitive accuracy

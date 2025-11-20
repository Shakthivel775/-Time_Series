# Advanced Time Series Forecasting Project

## Overview
This repository contains code and documentation for forecasting electricity load
using deep learning models with uncertainty quantification.

## Dataset
- Source: Kaggle Electricity Load Forecasting (continuous_dataset.csv)
- Frequency: Hourly
- Target: Load/Demand

## Models
- LSTM with Monte Carlo Dropout
- LSTM with Quantile Regression

## Evaluation Metrics
- RMSE, MAE, MAPE
- Coverage Probability, Interval Width
- CRPS

## How to Run
1. Open the notebook in Google Colab
2. Mount Google Drive and set CONFIG paths
3. Run all cells to train and evaluate models
4. Results are saved in summary.md and plots folder

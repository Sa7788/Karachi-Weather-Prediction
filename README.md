# Karachi Temperature Prediction using LSTM

A deep learning project that predicts average temperatures in Karachi using LSTM (Long Short-Term Memory) neural networks. The model is trained on historical temperature data from 1995 to 2018 and validated on 2019 data.

## Overview

This project implements a temperature prediction model for Karachi, Pakistan using time series analysis and deep learning. The LSTM model achieves an RMSE of 1.86°F on the test set, demonstrating good predictive performance.

## Features

- Data preprocessing and cleaning of Karachi temperature dataset
- Time series analysis of temperature trends (1995-2019)
- LSTM model implementation using TensorFlow/Keras
- Model evaluation and visualization of predictions

## Technical Details

- **Model Architecture:**
  - Two LSTM layers (64 and 32 units)
  - Dense output layer
  - ReLU activation
  - Adam optimizer
  - MSE loss function

- **Data Processing:**
  - Removal of temperatures below 32°F (outliers)
  - MinMax scaling
  - Time series generation with 20-step sequences

## Requirements

- Python 3.x
- TensorFlow
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results

The model achieves an RMSE of 1.86°F on 2019 test data, showing strong predictive capabilities for temperature forecasting in Karachi.


## Dataset

The dataset contains daily average temperatures for Karachi from 1995 to 2020, with the following features:
- Date (Year-Month-Day)
- Average Temperature (°F)

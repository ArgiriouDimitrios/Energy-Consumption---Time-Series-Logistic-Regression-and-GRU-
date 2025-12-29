# Energy-Consumption---Time-Series-Logistic-Regression-and-GRU-
Multivariate time series forecasting of household energy consumption using a GRU-based neural network with proper temporal validation and early stopping.

**Project Overview**
--This project implements a multivariate time series forecasting pipeline for household energy consumption using a GRU-based neural network. The objective is to      ----predict hourly Global Active Power based on historical consumption patterns and auxiliary electrical measurements.

**Dataset**
The dataset contains minute-level household power consumption measurements, which were:
--Parsed into a datetime index
--Cleaned and imputed using forward/backward filling
--Resampled to hourly resolution for computational efficiency and noise reduction

**Model Architecture**
--GRU layer for temporal feature extraction
--Dropout regularization
--Dense layers for regression output

**Evaluation Metrics**
The model was evaluated using:
--Mean Absolute Error (MAE)
--Root Mean Squared Error (RMSE)

**Future Improvements**
--Sequence-to-sequence GRU for direct multi-step forecasting
--Incorporation of calendar features (hour, day of week)
--Comparison with classical statistical models (ARIMA


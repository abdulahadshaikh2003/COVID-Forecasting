# Time Series Forecasting: ARIMA vs Prophet

This project presents a **comparative analysis** between two popular time series forecasting models: **ARIMA** and **Facebook Prophet**. The goal is to evaluate which model performs better on a given dataset by comparing accuracy and interpreting the forecasting components.

## Models Used

- **ARIMA (AutoRegressive Integrated Moving Average)**  
  Traditional statistical model effective for linear, stationary time series.

- **Prophet**
  Developed by Facebook, designed for time series with strong seasonality and trend components.

## Evaluation Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Files

- `forecast_comparison.ipynb` – Main Jupyter notebook with:
  - ARIMA & Prophet modeling
  - Accuracy comparison
  - Visual forecast plots
  - Trend and seasonality interpretation

## Highlights

- Side-by-side visualization of predictions
- Plot of ARIMA residuals and Prophet components
- Clean evaluation using RMSE for both models
- Interpretation of ARIMA coefficients and Prophet trends

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt

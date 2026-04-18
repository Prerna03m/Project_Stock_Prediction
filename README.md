# Stock Price Prediction using ARIMA, SARIMA and LSTM

This project focuses on forecasting stock prices using statistical time series models and deep learning techniques. It compares the performance of ARIMA, SARIMA, and LSTM models using historical stock data.

## Project Overview

The objective of this project is to analyze stock price data, build predictive models, and evaluate their performance. The project demonstrates an end-to-end time series forecasting pipeline.

## Models Used

- ARIMA (AutoRegressive Integrated Moving Average)
- SARIMA (Seasonal ARIMA)
- LSTM (Long Short-Term Memory)

## Workflow

1. Data collection using yfinance
2. Data preprocessing and normalization
3. Train-test split
4. Model building:
   - LSTM model
   - ARIMA model
   - SARIMA model
5. Model evaluation using MAE and R²
6. Visualization of actual vs predicted values

## Evaluation Metrics

- Mean Absolute Error (MAE)
- R-squared (R² Score)

## Results

The models were compared based on prediction accuracy. ARIMA and SARIMA performed well for structured time series data, while LSTM captured more complex patterns.

(Add your actual MAE and R² values here if needed)

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels
- TensorFlow / Keras
- yfinance

## Project Structure

- Project_Stock_Prediction.ipynb

## Conclusion

ARIMA and SARIMA are effective for linear and seasonal trends, while LSTM is useful for capturing nonlinear patterns. The project highlights the strengths of combining statistical and deep learning approaches for time series forecasting.

## Future Work

- Hyperparameter tuning
- Testing additional models like Prophet or GRU
- Model deployment

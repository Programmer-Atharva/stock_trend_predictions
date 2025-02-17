# Stock Trend Prediction App

This Streamlit application predicts stock trends using a pre-trained Keras model.  It allows users to select a stock ticker and date range, displays historical data and visualizations, and then uses the model to generate predictions.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)



## Introduction

This project provides a simple and interactive way to visualize stock data and explore predictions made by a machine learning model.  It uses the `yfinance` library to download historical stock data, `matplotlib` for visualizations, `scikit-learn` for data scaling, `Keras` (or `TensorFlow`) for model loading and prediction, and `Streamlit` to create the interactive web application.

## Features

- **Interactive Stock Selection:** Users can enter any valid stock ticker symbol (e.g., AAPL, MSFT, GOOG).
- **Date Range Selection:** Users can specify the start and end dates for the data.
- **Data Display:** Displays a summary of the downloaded historical stock data.
- **Visualizations:**
    - Closing price vs. time chart.
    - Closing price vs. time chart with 100-day moving average.
    - Closing price vs. time chart with 100 and 200-day moving averages.
- **Predictions:** Loads a pre-trained Keras model (`keras_model.h5`) and generates stock price predictions.
- **Prediction Visualization:** Plots the original stock prices against the predicted prices.
- **Error Handling:** Includes error handling for invalid tickers, data retrieval issues, and missing model files.

## Installation

1. **Clone the repository:**
 ```bash
git clone https://github.com/Programmer-Atharva/stock_trend_predictions.git
```
```bash
cd stock_trend_prediction
```

2.  **Create a virtual environment (recommended):**

```bash
python3 -m venv myenv
```
```bash
source myenv/bin/activate  # On Windows: myenv\Scripts\activate
```

3. **Install the required packages:**
```bash
pip install -r requirements.txt
```

4. **Run the Streamlit app:**
```bash
streamlit run app.py 
```

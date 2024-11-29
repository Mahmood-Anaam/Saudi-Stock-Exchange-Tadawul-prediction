# Saudi Stock Exchange (Tadawul) Prediction

<a href="https://colab.research.google.com/github/Mahmood-Anaam/Saudi-Stock-Exchange-Tadawul-prediction/blob/main/notebooks/Tadawul_stocks_2015_2020_healthcare_spimaco.ipynb" target="_parent\">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This project focuses on forecasting the stock prices of Saudi Pharmaceutical Industries and Medical Appliances Corporation (SPIMACO), a leading company in the healthcare sector, using historical data from 2015 to 2020. Stock price forecasting plays a crucial role in financial decision-making, helping investors and stakeholders assess market trends and develop effective investment strategies. The analysis employs ARIMA (AutoRegressive Integrated Moving Average), a widely-used statistical model for time series forecasting.

The primary goal of this project is to build a reliable forecasting model that captures long-term trends while minimizing prediction errors. The process involves cleaning and preparing the dataset, analyzing stationarity, identifying optimal ARIMA parameters, and evaluating the model's performance. The insights gained from this analysis provide a foundation for future optimization and broader applications in financial planning.

## Methodology

The project is structured into the following key phases to ensure a systematic approach to time series forecasting:

1. **Data Preparation and Cleaning:**
   - Historical stock price data for SPIMACO was loaded and preprocessed. Missing values were addressed using forward-filling, and the data was made stationary through differencing to meet the requirements of ARIMA modeling.

2. **Exploratory Data Analysis (EDA):**
   - Data trends, seasonality, and volatility were explored through visualizations and statistical summaries. Decomposition analysis was used to isolate the trend, seasonality, and residual components.

3. **Stationarity and Parameter Identification:**
   - Stationarity was verified using the Augmented Dickey-Fuller (ADF) test, while ACF and PACF plots guided the selection of initial ARIMA parameters (\(p, d, q\)).

4. **Model Training and Evaluation:**
   - The ARIMA model was trained on the training dataset and evaluated on the test dataset using metrics such as Mean Absolute Error (MAE). Actual vs. predicted plots were used to assess performance visually.




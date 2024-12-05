# Saudi Stock Exchange (Tadawul) Prediction: SPIMACO & CHEMICAL.

<div>
<a href="https://colab.research.google.com/github/Mahmood-Anaam/Saudi-Stock-Exchange-Tadawul-prediction/blob/main/notebooks/Tadawul_stocks_2015_2020_healthcare_spimaco.ipynb" target="_parent">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
   
<a href="https://colab.research.google.com/github/Mahmood-Anaam/Saudi-Stock-Exchange-Tadawul-prediction/blob/main/notebooks/Tadawul_stocks_2015_2020_healthcare_chemical.ipynb" target="_parent">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
</div>


This project focuses on forecasting the stock prices of two prominent companies in the Saudi Stock Exchange (Tadawul) from the Health Care sector:

1. **Saudi Pharmaceutical Industries and Medical Appliances Corporation (SPIMACO)**.
2. **Saudi Chemical Co. (CHEMICAL)**.

Both companies were analyzed using historical data from 2015 to 2020 to gain insights into stock trends and build reliable forecasting models. Stock price forecasting is critical in financial decision-making, aiding investors and stakeholders in assessing market trends and devising effective investment strategies. The analysis employs ARIMA (AutoRegressive Integrated Moving Average), a widely-used statistical model for time series forecasting.

The primary goal of this project is to build reliable forecasting models that capture long-term trends while minimizing prediction errors. The process involves cleaning and preparing datasets, analyzing stationarity, identifying optimal ARIMA parameters, and evaluating the models' performance. The insights gained provide a foundation for future optimization and broader applications in financial planning.

## Methodology

The project is structured into the following key phases to ensure a systematic approach to time series forecasting:

1. **Data Preparation and Cleaning:**
   - Historical stock price data for both SPIMACO and Saudi Chemical Co. were loaded and preprocessed. Missing values were addressed using forward-filling, and the data was made stationary through differencing to meet the requirements of ARIMA modeling.

2. **Exploratory Data Analysis (EDA):**
   - Data trends, seasonality, and volatility were explored through visualizations and statistical summaries for both companies. Decomposition analysis was used to isolate the trend, seasonality, and residual components, providing a clearer understanding of the underlying patterns.

3. **Stationarity and Parameter Identification:**
   - Stationarity was verified using the Augmented Dickey-Fuller (ADF) test for both datasets, ensuring the series met the requirements of ARIMA. ACF and PACF plots guided the selection of initial ARIMA parameters (\(p, d, q\)) for SPIMACO and Saudi Chemical Co.

4. **Model Training and Evaluation:**
   - Separate ARIMA models were trained for SPIMACO and Saudi Chemical Co. on their respective training datasets. Evaluation was conducted using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Actual vs. predicted plots were used to visually assess model performance.

## Insights
1. **SPIMACO**:
   - The ARIMA model effectively captured long-term trends but struggled with short-term fluctuations. The model demonstrated solid predictive capabilities for stable periods.

2. **Saudi Chemical Co.**:
   - The ARIMA model provided a reliable baseline for forecasting. However, like SPIMACO, it faced challenges in capturing high volatility during certain periods.

Both analyses highlight the strengths of ARIMA for trend detection while emphasizing the need for advanced techniques, such as SARIMA or machine learning models, to better handle short-term volatility and external influences.

## Future Work
- Extend the analysis to incorporate external factors, such as economic indicators and news sentiment, to improve forecasting accuracy.
- Explore advanced models like SARIMA for seasonality and LSTMs for non-linear dependencies.
- Apply similar methodologies to other companies in the Saudi Stock Exchange for a broader perspective on sector trends.

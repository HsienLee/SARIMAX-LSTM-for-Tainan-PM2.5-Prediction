	This study presents a hybrid modeling approach combining Seasonal Autoregressive Integrated Moving Average with Exogenous Variables (SARIMAX) and Long Short-Term Memory (LSTM) neural networks for the prediction of PM2.5 air pollution levels. The proposed model aims to leverage the strengths of both statistical and deep learning methods to improve forecasting accuracy.

	In the first stage, a SARIMAX model is developed to capture the linear and seasonal patterns inherent in the PM2.5 time series data. Autocorrelation and partial autocorrelation analyses are conducted to determine the optimal parameters for the SARIMAX model. The model is then fitted to the historical data to generate initial forecasts.

	The residuals obtained from the SARIMAX model, representing the nonlinear patterns not captured in the first stage, are used as input for the LSTM neural network in the second stage. The LSTM model is trained on these residuals to learn complex nonlinear dependencies and temporal dynamics within the data.

	Finally, the forecasts from the SARIMAX model are combined with the predictions of the LSTM model to produce the final PM2.5 concentration forecasts. This integration effectively adjusts the initial SARIMAX forecasts by incorporating the nonlinear corrections learned by the LSTM network.

	Experimental results demonstrate that the SARIMAX-LSTM hybrid model outperforms traditional single-model approaches in predicting PM2.5 levels, achieving higher accuracy and better capturing of both linear and nonlinear patterns in the data. The enhanced forecasting capability of this hybrid model provides valuable insights for air quality management and can assist policymakers in making informed decisions to mitigate air pollution impacts.

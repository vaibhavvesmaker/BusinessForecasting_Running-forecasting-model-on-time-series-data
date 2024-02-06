# BusinessForecasting_Running-forecasting-model-on-time-series-data
Running forecasting model on  time series data

**Model Output Summary**

- **Model Name**: Time Series Forecasting Model
- **Dataset Used**: Boston Dataset (Monthly Dollar Volume of Sales on Boston Stock Exchange and Combined New York and American Stock Exchange)
- **Time Period**: January 1967 – November 1969

**Model Performance Metrics**

1. **ME (Mean Error)**: -6.82411
   - Interpretation: The model tends to underestimate the values on average.

2. **RMSE (Root Mean Squared Error)**: 37.4424
   - Interpretation: The average magnitude of forecast errors is 37.4424, indicating the typical deviation of forecasts from actual values.

3. **MAE (Mean Absolute Error)**: 27.12859
   - Interpretation: The average absolute deviation of forecasts from actual values is 27.12859.

4. **MPE (Mean Percentage Error)**: -6.724361
   - Interpretation: The model has an average percentage error of -6.724361, suggesting an overall underestimation.

5. **MAPE (Mean Absolute Percentage Error)**: 21.27763
   - Interpretation: The average absolute percentage deviation of forecasts from actual values is 21.27763.

6. **MASE (Mean Absolute Scaled Error)**: 0.3433243
   - Interpretation: The model's performance is 0.3433243 times as accurate as a simple benchmark (naïve forecast).

7. **ACF1 (Autocorrelation of Residuals)**: -0.03517022
   - Interpretation: The autocorrelation of residuals shows a slight negative correlation, suggesting some irregularities in the model's errors.

**Model Evaluation and Interpretation**

- The model exhibits a negative bias (ME) and a tendency to underestimate values on average.
- The RMSE and MAE values indicate a moderate level of forecast accuracy, with errors of approximately 37.44 and 27.13, respectively.
- The MPE and MAPE values indicate an overall underestimation, with an average percentage error of -6.72% and an average absolute percentage error of 21.28%.
- The MASE suggests that the model is approximately 0.34 times as accurate as a simple benchmark (naïve forecast).
- The ACF1 value indicates some negative autocorrelation in the residuals, suggesting the need for further model refinement.

Please note that the choice of the "best" model depends on the specific forecasting goals and requirements. While this model provides insights into the dataset, further analysis and model refinement may be necessary to improve forecast accuracy and reduce bias.

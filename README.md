# Tourism Time Series Forecasting using SARIMA, SARIMAX, and Hybrid Models

This repository contains a research project on **time series forecasting of aggregated monthly tourist arrivals in Indonesia**. The study focuses on comparing the forecasting performance of three approaches: **SARIMA, SARIMAX, and Hybrid models**.

The objective of this research is to identify the most accurate forecasting strategy for modeling tourist arrival patterns that exhibit **seasonality, trends, and external influences**.

## Project Overview

Tourism is one of the most important sectors contributing to Indonesia’s economic growth. Accurate forecasting of tourist arrivals is essential for supporting tourism planning, infrastructure development, and policy decision-making.

This study analyzes **monthly national tourist arrival data from the Central Bureau of Statistics (BPS)** and evaluates different time series forecasting models.

Three forecasting approaches are implemented:

* **SARIMA** – to capture seasonal patterns in the time series
* **SARIMAX** – to incorporate external variables such as travel policy
* **Hybrid Models** – combining statistical models with neural networks to capture nonlinear patterns

## Dataset

The dataset consists of **monthly aggregated tourist arrivals in Indonesia** obtained from the **Central Bureau of Statistics (BPS)**.

Key characteristics of the dataset:

* Monthly time series data
* Seasonal tourism patterns
* Trend changes over time
* External factors such as travel policy interventions

## Methodology

The research follows several main stages:

1. **Data Preprocessing**

   * Data cleaning
   * Handling missing values
   * Time index formatting

2. **Exploratory Time Series Analysis**

   * Visualization of tourist arrival trends
   * Identification of seasonal patterns

3. **Stationarity Testing**

   * Augmented Dickey-Fuller (ADF) test
   * Differencing transformation

4. **Model Development**

   * SARIMA modeling
   * SARIMAX modeling with exogenous variables
   * Hybrid models combining statistical methods and neural networks

5. **Model Evaluation**

Models are evaluated using the following metrics:

* RMSE (Root Mean Square Error)
* MAE (Mean Absolute Error)
* MAPE (Mean Absolute Percentage Error)

## Results

The experimental results show that **SARIMAX achieved the best forecasting performance** compared to SARIMA and hybrid approaches.

Key findings:

* Incorporating **exogenous variables** improves forecasting accuracy.
* Tourist arrival data shows strong **annual seasonality**.
* Hybrid models provide competitive performance but did not outperform the SARIMAX model in this study.

## Forecasting

The best model is used to generate:

* **Short-term forecasts (12 months ahead)**
* **Long-term forecasts (24 months ahead)**

The results show a gradual increase in tourist arrivals with recurring seasonal peaks during mid-year periods.

## Technologies Used

* Python
* Pandas
* NumPy
* Statsmodels
* Scikit-learn
* Matplotlib
* Seaborn

## Repository Structure

* `Source_Code_Tubes_ADW.ipynb` — time series modeling and forecasting implementation
* `dataset` — tourism arrival dataset from BPS
* `paper` — research report
* `README.md` — project documentation

## Conclusion

This study demonstrates that **SARIMAX is the most effective model** for forecasting aggregated monthly tourist arrivals in Indonesia. The inclusion of external variables improves the model’s ability to capture structural changes in tourism demand.

These findings highlight the importance of integrating **exogenous factors in time series forecasting models** to support tourism planning and policy development.

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

Models are evaluated using:

* RMSE (Root Mean Square Error)
* MAE (Mean Absolute Error)
* MAPE (Mean Absolute Percentage Error)

## Results

The experimental results show that **SARIMAX achieved the best forecasting performance** compared to SARIMA and hybrid approaches.

Key findings:

* Incorporating **exogenous variables** improves forecasting accuracy
* Tourist arrival data shows strong **annual seasonality**
* Hybrid models provide competitive performance but do not outperform SARIMAX in this study

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
* `Data baru.xlsx` — tourism arrival dataset
* `PAPER ADW KELOMPOK 11.pdf` — research report
* `README.md` — project documentation

## Research Team

1. Aura Aulia Anastasya Hadi Putri
2. Christa M. A. Tella Ware
3. Helen Setyo Anggun

## Conclusion

This study demonstrates that **SARIMAX provides the best forecasting accuracy** for aggregated monthly tourist arrivals in Indonesia. The inclusion of exogenous variables improves the model’s ability to capture structural changes in tourism demand and enhances forecasting performance.

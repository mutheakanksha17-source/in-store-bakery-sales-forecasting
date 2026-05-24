# In-Store Bakery Daily Forecasting

A machine learning and time series forecasting project focused on predicting daily bakery sales to support inventory optimisation and reduce waste in retail environments.

This project was completed as part of a university-industry collaboration with Co-op Uk.

---

## Project Overview

Retail bakery products experience significant fluctuations in daily demand due to:
- weather conditions
- seasonality
- promotions
- day-of-week effects
- customer behaviour patterns

Accurate forecasting is important for:
- reducing inventory waste
- improving stock management
- minimising overproduction
- improving customer satisfaction

This project explored machine learning and time series approaches for forecasting bakery product sales across multiple stores.

---

## Objectives

- Forecast daily bakery sales using historical sales and external data
- Analyse the impact of weather and seasonal factors on sales
- Compare machine learning and time series forecasting models
- Identify the most effective forecasting models for different stores

---

## Data Sources

The analysis combined:
- historical bakery sales data
- weather data
- promotional activity information
- seasonal and calendar-based features

---

## Methodology

### Data Preprocessing
- missing value handling
- outlier detection
- white noise elimination
- stationarity testing
- chronological train-test splitting

### Feature Engineering
Features included:
- weekday
- season
- rainfall
- product code
- weather variables

### Models Evaluated
- SARIMA
- LSTM
- Random Forest
- LightGBM

### Evaluation Metrics
- RMSE
- MAE

---

## Key Findings

- Different stores exhibited different sales patterns, requiring store-specific forecasting models.
- LightGBM achieved the best performance for Store 5751.
- Random Forest performed best for Stores 8093 and 8037.
- Weather and seasonal variables influenced sales performance in several stores.
- Machine learning models provided reasonably accurate forecasting performance but required further refinement for production deployment.

---

## Technologies Used

- Python
- pandas
- scikit-learn
- LightGBM
- statsmodels
- NumPy
- Matplotlib

---

## Team Project

This project was completed as part of a collaborative university-industry co-op project in partnership with Co-op.

Contributions included:
- data preprocessing
- exploratory data analysis
- feature engineering
- forecasting analysis
- model evaluation
- reporting

---

## Repository Structure

```text
coop-bakery-sales-forecasting/
│
├── README.md
├── game_changers_report.pdf
```

---

## Confidentiality Notice

Due to project and data confidentiality restrictions, the original datasets and implementation code cannot be publicly shared.

This repository contains:
- project overview
- methodology
- findings
- final report

No confidential retail data has been included.

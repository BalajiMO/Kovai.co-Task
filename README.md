# Kovai.co-Task

This project forecasts daily passenger journeys for Canberra's public transport services (Local Route, Light Rail, etc.) using **ARIMA** and models. The solution helps transit authorities optimize resource allocation and service planning.

- **Data Preprocessing**: Handles missing values, stationarity checks (ADF test), and outlier detection
- **Model Training**: Automated parameter selection for ARIMA (p,d,q) using ACF/PACF analysis
- **Evaluation**: Metrics like MAE, RMSE, and MAPE with walk-forward validation
- **Visualization**: Interactive plots comparing actual vs predicted demand

- **Source**: [ACT Government Open Data Portal](https://www.data.act.gov.au/)  
**Columns**:
- `Date`: Daily timestamp
- `Local Route`: Passenger counts for local bus services
- `Light Rail`: Light rail journeys  
- `Peak Service`: High-frequency routes during rush hours
- `School`: School-specific transport
- `Rapid Route`: Express bus services

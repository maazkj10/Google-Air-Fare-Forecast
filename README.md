# Google Flights Airfare Forecast

## Description
This project uses Google Flights data to analyze and forecast airfare trends. The focus is on identifying actionable insights for consumers and industry stakeholders through comprehensive data analysis and machine learning.

## Key Findings
1. **Price Trends**:
   - Average airfare: $509.67 with a standard deviation of $385.88.
   - Lowest price: $16.61, highest price: $6639.68.

2. **Feature Importance**:
   - Key predictors of airfare include `destination`, `fare_class`, `delta` (days to departure), and `departure date`.

3. **Model Performance**:
   - Model: **XGBoost Regressor**
   - **MAPE**:
     - Train: 36.46%
     - Validation: 60.72%
     - Test: 60.72%
   - The model significantly outperformed the benchmark on key metrics.

4. **Class-Specific Insights**:
   - Economy fares have lower prediction error (MAPE: 59.67%).
   - Business and First-Class fares show slightly higher errors.

## Features
- **Exploratory Data Analysis**: Patterns in booking and departure times, fare distributions.
- **Machine Learning**: The XGBoost Regressor model was used for predictions, with hyperparameter tuning to optimize performance.
- **Visualizations**: Airfare trends by airline, origin, and destination.

## Visualizations
Include example plots or references to plots in your notebook:
- Airfare distribution across airlines.
- Price trends by booking and departure windows.
- Feature importance from the XGBoost model.

## Results
- Significant improvement in airfare prediction accuracy compared to benchmarks.
- Visualized results highlight actionable trends in air travel pricing.

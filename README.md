# Google Flights Airfare Forecast - Project

## Description
This project uses Google Flights data to analyze and forecast airfare trends through comprehensive data analysis and machine learning techniques. The goal is to identify key factors influencing airfare pricing and develop a model that can accurately forecast prices for unseen data.

## Data
The dataset includes data for a subset of domestic flights within the US and contains the following key features:
- **Destination**: The final location of the flight.
- **Fare Class**: The ticket class (Economy, Business, First-Class).
- **Delta**: The number of days between the booking date and the departure date.
- **Departure Date**: The date of the flight.
- **Airfare**: The price of the ticket (target variable).

### Data Processing
The data was preprocessed to:
- Remove missing values.
- Handle outliers that could skew predictions.
- Transform categorical variables into machine-readable formats.
- Conduct Exploratory Data Analysis (EDA) to uncover patterns and relationships.

## Key Findings
1. **Price Trends**:
   - Average airfare: $509.67 with a standard deviation of $385.88.
   - Lowest price: $16.61, highest price: $6639.68.

2. **Feature Importance**:
   - Key predictors of airfare include `destination`, `fare_class`, `delta` (days to departure), and `departure date`.

3. **Model Performance**:
   - Model: **XGBoost Regressor**
   - **Mean Absolute Percentage Error (MAPE)**:
     - Train: 36.46%
     - Validation: 60.72%
     - Test: 60.72%
   - The model significantly outperformed the benchmark on key metrics.

4. **Class-Specific Insights**:
   - Economy fares have lower prediction error (MAPE: 59.67%).
   - Business and First-Class fares exhibit slightly higher errors.

## Features
- **Exploratory Data Analysis**: Analyzed patterns in booking and departure times, fare distributions, and other significant trends.
- **Machine Learning**: The XGBoost Regressor model was implemented with hyperparameter tuning to achieve optimal performance.
- **Visualizations**: Created to show airfare trends by airline, origin, destination, and other factors.

## Visualizations
Key visualizations include:
- **Airfare Distribution**: Comparing price distributions across different airlines.
- **Booking vs. Departure Trends**: Analyzing how prices vary by booking date and departure date.
- **Feature Importance Plot**: Showing the relative importance of different predictors in the model.

## Results
- Significant improvement in airfare prediction accuracy compared to benchmarks.
- Visualized results provide actionable insights into air travel pricing trends.

## Dataset Description

The dataset used in this project is the **Walmart Cleaned Sales Dataset**, which contains historical retail sales data across multiple stores and departments.

### Overview
The dataset provides time series information on sales performance, allowing analysis of trends, seasonality, and anomalies over time. It is suitable for forecasting tasks using statistical and machine learning models.

### Key Features

**Date**  
Represents the time index of the data. This is the primary variable used to construct the time series.

**Store**  
Identifier for each Walmart store. Can be used to analyze sales per location or aggregated across all stores.

**Dept (Department)**  
Represents different product departments within each store. Useful for more granular analysis.

**Weekly_Sales**  
The main target variable. Continuous numerical values representing total sales for a given store and department at a specific time.

**Holiday_Flag**  
Indicates whether the week includes a major holiday (1 = holiday, 0 = non-holiday). Useful for detecting seasonal spikes.

**Temperature**  
Average temperature during the time period. Can be used as an external regressor.

**Fuel_Price**  
Fuel price at the time of observation. May influence consumer behavior.

**CPI (Consumer Price Index)**  
Economic indicator representing inflation levels.

**Unemployment**  
Unemployment rate at the time of observation, reflecting economic conditions.

### Time Series Characteristics

- Frequency: Weekly observations  
- Type: Continuous time series (sales values)  
- Length: Sufficient number of observations for forecasting (> 75)  
- Potential components:
  - Trend (long-term increase or decrease in sales)
  - Seasonality (weekly/holiday effects)
  - Irregular fluctuations (noise or anomalies)

### Usage in This Project

For this project, the dataset will be:
1. Aggregated (if needed) to form a single time series
2. Analyzed for trends, seasonality, and anomalies
3. Modeled using time series techniques (ARIMA, SARIMA, Prophet)
4. Used to generate forecasts and evaluate prediction accuracy

The dataset provides a realistic scenario for sales forecasting, with patterns similar to those observed in other industries such as telecommunications.
# prophet-challenge

# Mercado Libre Growth Analysis with Prophet

## Introduction
This project aims to analyze the relationship between Google search trends and stock price patterns for Mercado Libre, the largest e-commerce platform in Latin America. The analysis involves using the Prophet forecasting model to predict search traffic and its impact on stock price trends.

## Instructions
1. **Step 1: Find Unusual Patterns in Hourly Google Search Traffic**
   - Analyze Google search data for May 2020.
   - Compare total search traffic for May 2020 with the monthly median.
   - Assess if search traffic increased during Mercado Libre's financial release month.

2. **Step 2: Mine the Search Traffic Data for Seasonality**
   - Group hourly search data to analyze traffic patterns by hour, day of the week, and week of the year.
   - Identify time-based trends in the data.

3. **Step 3: Relate the Search Traffic to Stock Price Patterns**
   - Read and plot stock price data.
   - Concatenate stock price data with search data.
   - Slice data for the first half of 2020 and plot.
   - Create columns for Lagged Search Trends, Stock Volatility, and Hourly Stock Return.
   - Analyze the relationship between lagged search traffic and stock volatility/returns.

4. **Step 4: Create a Time Series Model with Prophet**
   - Set up Google search data for a Prophet forecasting model.
   - Plot the forecast and analyze the components to determine popular times, busiest days, and low points in search traffic.

## Requirements
- Python 3.x
- pandas
- Prophet
- Matplotlib

## Usage
1. Clone the repository.
2. Install the required libraries: `pip install -r requirements.txt`.
3. Run the provided notebook or Python script to perform the analysis.
4. Ensure the necessary datasets are available in the specified locations.

## Conclusion
This analysis provides insights into the relationship between Google search trends and stock price patterns for Mercado Libre. By leveraging Prophet's forecasting capabilities, the company can make informed decisions to optimize marketing strategies and anticipate stock market trends.


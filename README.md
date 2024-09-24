*Time Series Decomposition: Trend and Seasonality Analysis*


*Overview*

This code performs time series decomposition on a given dataset, extracting trend and seasonality components.


*Requirements*

- Python 3.x
- Pandas
- Matplotlib
- NumPy


*Dataset*

- Expected format: CSV file with 'Date' and 'Close' columns
- Example dataset: Tesla monthly stock prices (provided in `/content/tesla month stock new.csv`)


*Code Structure*

1. `calculate_trend()`: computes trend component using moving averages
2. `calculate_seasonality()`: computes seasonality component by subtracting trend from original data
3. Main script: loads data, calculates trend and seasonality, and visualizes results


*Usage*

1. Replace `/content/tesla month stock new.csv` with your own dataset path.
2. Run the script using Python 
3. Visualize the results: original data, trend, and seasonality.


*Functions*

*calculate_trend(xt, t)*

- Computes trend component using moving averages.
- Parameters:
    - `xt`: original data values
    - `t`: timestamp values
- Returns: trend values


*calculate_seasonality(xt, trend, t)*

- Computes seasonality component by subtracting trend from original data.
- Parameters:
    - `xt`: original data values
    - `trend`: trend values
    - `t`: timestamp values
- Returns: seasonality values


*Visualization*

- Original data
- Trend component
- Seasonality component

Author
Aarthi.B

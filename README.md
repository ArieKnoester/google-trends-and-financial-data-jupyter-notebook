# google-trends-and-financial-data-jupyter-notebook

A Jupyter Notebook exercise which compares Google Trends (Web search data) with other time series data.

## Sources:
* [Unemployment Rate from FRED](https://fred.stlouisfed.org/series/UNRATE/)
* [Google Trends](https://trends.google.com/trends/explore)
* [Yahoo Finance Tesla Stock Price](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)
* [Yahoo Finance Bitcoin Stock Price](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)

###  Contains examples of:
* Return boolean if dataframe contains NaN values, finding the rows with NaNs, and removing them
* .resample() to convert time series from daily to monthly periodicity
* matplotlib.dates locators for styling ticks on the x axis
* .rolling() for smoothing out data
* Various styling, such as linestyles, markers, grid, and dpi

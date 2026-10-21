# Page-view forecasting for ad placement

Forecast daily page views per page so an ad-infrastructure company can place ads where traffic will be, across pages in different languages and regions.

## What's inside

- EDA of the per-page view history, including language and access-type breakdowns
- Stationarity checks: Dickey–Fuller test, seasonal decomposition, differencing
- ACF and PACF plots to choose model orders
- ARIMA and SARIMAX models with a shared evaluation function
- Facebook Prophet as a comparison

## Files

- `forecast_ad.ipynb` — full analysis
- `forecast_ad.pdf` — rendered notebook

Libraries: pandas, statsmodels, fbprophet, scikit-learn.

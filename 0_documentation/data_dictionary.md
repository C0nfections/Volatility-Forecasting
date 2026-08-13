# Data Dictionary

## Raw FRED series

| Variable | FRED series | Meaning |
|---|---|---|
| `sp500` | `SP500` | S&P 500 daily index level |
| `vix` | `VIXCLS` | CBOE Volatility Index |
| `dgs10` | `DGS10` | 10-year Treasury constant maturity rate |
| `fed_funds` | `DFF` | Effective federal funds rate |

## Created variables

| Variable | Meaning |
|---|---|
| `sp500_return` | Daily S&P 500 log return |
| `abs_return` | Absolute value of daily log return |
| `vol_5` | Annualized realized volatility over the past 5 trading days |
| `vol_20` | Annualized realized volatility over the past 20 trading days |
| `target_vol_5` | Annualized realized volatility over the next 5 trading days; this is the prediction target |
| `abs_return_lag1` | Yesterday's absolute return |
| `abs_return_lag2` | Absolute return from two trading days ago |
| `vix_lag1` | Yesterday's VIX |
| `vol_5_lag1` | Yesterday's 5-day realized volatility |
| `vol_20_lag1` | Yesterday's 20-day realized volatility |

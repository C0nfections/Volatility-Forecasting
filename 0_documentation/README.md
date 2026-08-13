## Folder structure

- `0_documentation`: project overview, data dictionary, and notes.
- `1_data`: raw FRED CSV files downloaded by the code.
- `2_code`: main R Markdown report.
- `3_output/figures`: plots.
- `3_output/tables`: model comparison tables.

## Main file

Open and knit:

`2_code/Final Project Code.Rmd`

The R Markdown file downloads FRED (Federal Reserve Economic Data) data, creates volatility features, and fits models, and produces any outputs found in `3_output`.

## Data sources used

- S&P 500 Index (`SP500`)
- CBOE Volatility Index (`VIXCLS`)
- 10-Year Treasury Constant Maturity Rate (`DGS10`)
- Effective Federal Funds Rate (`DFF`)

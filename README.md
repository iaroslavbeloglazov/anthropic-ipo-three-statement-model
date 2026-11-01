
# Anthropic — Three-Statement Financial Model

**Python | Pandas | Financial Analysis | Forecasting**

## Overview

An integrated 3 statement financial model of Anthropic,
based on publicly available Anthropic S1 filing.

The project aims to reconstruct historical financial
statements and develop a financial forecasting engine.

## Data Source

Historical financial statements are sourced from
Anthropic's S-1 registration statement.

[S-1 1 anthropicpbc-sx1](https://www.sec.gov/Archives/edgar/data/2130357/000162828026067168/anthropicpbc-sx1.htm)

All financial values are reported in USD millions,
unless otherwise stated.

## Methodology

### 1. Historical Financial Statements

Reconstruction of:

- Income Statement
- Balance Sheet
- Cash Flow Statement

Historical calculations will be validated against
reported financial data.

### 2. Financial Forecasting (Planned)

Forecasting revenue, operating expenses, working
capital, capital expenditures and financing needs.

### 3. Scenario Analysis (Planned)

- Base Case
- Bull Case
- Bear Case

## Tech Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Matplotlib

## Project Structure

    anthropic-financial-model/
    ├── data
    │   ├── balance_sheet.csv
    │   ├── cash_flow.csv
    │   └── income_statement.csv
    ├── notebooks
    │   ├── 01_historical.ipynb
    │   ├── 02_forecasting.ipynb
    │   └── 03_scenarios.ipynb
    ├── src
    │   └── financial_model.py
    ├── README.md
    └── requirements.txt

## Progress

- [ ] Extract historical financial statements
- [ ] Validate historical financial data
- [ ] Implement forecasting engine
- [ ] Integrate financial statements
- [ ] Add scenario analysis
- [ ] Visualize financial results

## Disclaimer

This project is for educational and research purposes
only and does not constitute investment advice.

# License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.

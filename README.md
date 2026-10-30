# BUSA3022 Analytics implementation plan and portfolio
## Project Overview

This project explores Australian share-market trends using ASX 200 data and the RBA Cash Rate Target. It includes data sources and Python notebooks demonstrating parts of the proposed analytics pipeline.

## Repository Contents

### data_sources/

- asx200_historical.csv – ASX 200 historical data from Yahoo Finance.

- BUSA3022 Cash Rate Target 22Oct.xlsx – RBA Cash Rate Target data.

## Python Notebooks

- Part 1: Data Pipeline Implementation – demonstrates data ingestion and validation.

- Part 2: Data Curation – demonstrates data preparation and calculation of a 20-trading-day rolling average.

## Data Sources

- Yahoo Finance: https://au.finance.yahoo.com/quote/%5EAXJO/history/?period1=1761091200&period2=1792627200

- Reserve Bank of Australia: https://www.rba.gov.au/statistics/tables/

Both datasets were retrieved on 22 October 2026.

## Note

The notebooks demonstrate selected parts of the proposed analytics system as proof of concept. They are not a fully automated production pipeline.

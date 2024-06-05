# Forecasting Tomorrow : Navigating Chaos to Predict Stock Market Trends

## Directory Structure

### FinalReport.pdf

PDF file containing the final report for the project.

### src/

- 01_GettingTickers.ipynb (10 lines of code) - Contains code to scrape Wikipedia for list of ticker symbols of S&P500 companies

- 02_ScrapingData.ipynb (20 lines of code) - Contains code to use yfinance to get daily price data for the companies whose ticker symbols were obtained above.

- 03_DataProcessing.ipynb (70 lines of code) - Contains code to arrange closing prices into time series observations that span 6 weeks.

- 04_Model.ipynb (200 lines of code) - Contains code to load and visualize data, split into training, validation, and test sets, define and train an RNN model, and visualize results.


### data/

#### tickers

- S&P500-tickers.csv - contains ticker symbols for S&P500 companies.

#### processed-data/

- data_6weeks_2020.csv - contains processed data for all companies corresponding to the tickers for the year 2020.

- data_6weeks_2021.csv - contains processed data for all companies corresponding to the tickers for the year 2021.

- data_6weeks_2022.csv - contains processed data for all companies corresponding to the tickers for the year 2022.

- data_6weeks_2023.csv - contains processed data for all companies corresponding to the tickers for the year 2023.

#### scraped-data/

- S&P500_data_2020.csv - contains scraped data for all companies corresponding to the tickers for the year 2020.

- S&P500_data_2021.csv - contains scraped data for all companies corresponding to the tickers for the year 2021.

- S&P500_data_2022.csv - contains scraped data for all companies corresponding to the tickers for the year 2022.

- S&P500_data_2023.csv - contains scraped data for all companies corresponding to the tickers for the year 2023.

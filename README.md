# NASDAQ_analysis

# Johnson & Johnson (JNJ) – Data Card

## Project Overview
This project presents a stock market analysis of Johnson & Johnson (JNJ). The goal was to collect historical stock price data, perform basic statistical analysis, and extract key performance indicators (KPIs) for the selected period.

## Source of Data

The dataset used in this project contains historical stock market data for Johnson & Johnson (JNJ), a publicly traded company.

The data was collected using the Python library `yfinance`, which retrieves financial data from Yahoo Finance.

Details of the dataset:
- Company: Johnson & Johnson
- Ticker: JNJ
- Source: Yahoo Finance (via yfinance API)
- Data type: Time series financial data
- Time range: from 2022-03-17 to 2022-12-31
- Frequency: daily data (interval = 1d)

The dataset includes the following variables:
- Open price
- Close price
- High price
- Low price
- Volume

Each row represents one trading day.

## KPIs

The following key performance indicators (KPIs) were calculated based on the dataset:

1. **Average Closing Price**  
   The mean value of the closing stock price over the selected period.

2. **Maximum Price**  
   The highest recorded stock price during the analyzed period.

3. **Minimum Price**  
   The lowest recorded stock price during the analyzed period.

4. **Average Opening Price**  
   The mean value of the opening stock price.

5. **Price Range**  
   The difference between the maximum and minimum price.

6. **Trading Volume Analysis**  
   Evaluation of how actively the stock was traded.

7. **Price Trends**  
   Observation of how the stock price changed over time (based on Open and Close prices).

## Conclusion

Based on the analysis of Johnson & Johnson stock data from March 2022 to December 2022, the company exhibited relatively stable price behavior over the selected period.

Although fluctuations in stock price were observed, they remained within a moderate range, suggesting limited volatility compared to more dynamic stocks. The difference between opening and closing prices also indicates normal daily market movements rather than extreme changes.

The analysis confirms that Johnson & Johnson is a relatively stable and mature company, with predictable stock behavior over time.

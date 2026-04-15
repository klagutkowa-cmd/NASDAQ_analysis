# NASDAQ_analysis - Data cards
This project presents a comparative stock market analysis of five companies listed on NASDAQ. 
The goal was to collect historical data, calculate key performance indicators (KPIs), and compare stock behavior across different industries.

# 1. Johnson & Johnson (JNJ)

### Project Overview
This project presents a stock market analysis of Johnson & Johnson (JNJ). The goal was to collect historical stock price data, inspect its structure and quality, and analyze selected financial indicators for the chosen period.

### Source of Data

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
- Dividends
- Stock Splits

Each row represents one trading day.

### Financial Indicators and Data Quality Metrics

The following indicators and metrics were analyzed based on the dataset:

#### Financial Indicators
1. **Minimum Close Price**  
   The lowest closing price recorded during the analyzed period.

2. **Maximum Close Price**  
   The highest closing price recorded during the analyzed period.

3. **Price Range**  
   The difference between the maximum and minimum closing price.

4. **Close Price Trend Over Time**  
   A time series visualization showing how Johnson & Johnson’s closing price changed during the selected period.

#### Data Quality Metrics
5. **Missing Values Analysis**  
   Verification of whether the dataset contains missing values.

6. **Duplicate Rate**  
   Evaluation of whether duplicate records are present in the dataset.

7. **Outlier Rate**  
   Detection of unusual values in the Close price column using the IQR method.

8. **Data Accuracy Rate**  
   Measurement of the percentage of valid records based on positive Close price, positive Volume, and non-negative Dividends.

9. **Invalid Value Rate**  
   Share of records that do not meet the validity criteria.

10. **Close Price Field Accuracy Rate**  
    Verification that all Close price values are valid and greater than zero.

### Conclusion

Based on the analysis of Johnson & Johnson stock data from March 2022 to December 2022, the company exhibited relatively stable stock price behavior.

The difference between the minimum and maximum closing price was moderate, indicating limited volatility compared to more dynamic companies. The closing price trend suggests gradual changes over time rather than sudden fluctuations.

At the same time, the dataset demonstrated high quality, with no missing values, no duplicates, and a high level of data accuracy, making it reliable for analysis.

Overall, Johnson & Johnson can be characterized as a stable and mature company with predictable stock behavior during the analyzed period.

# 2. Netflix (NFLX)

### Project Overview
This project presents a stock market analysis of Netflix (NFLX). The goal was to collect historical stock price data, inspect its structure and quality, and analyze selected financial indicators for the chosen period.

### Source of Data

The dataset used in this project contains historical stock market data for Netflix (NFLX), a publicly traded company.

The data was collected using the Python library `yfinance`, which retrieves financial data from Yahoo Finance.

Details of the dataset:
- Company: Netflix
- Ticker: NFLX
- Source: Yahoo Finance (via yfinance API)
- Data type: Time series financial data
- Time range: from 2020-02-03 to 2020-08-03
- Frequency: daily data (interval = 1d)

The dataset includes the following variables:
- Open price
- Close price
- High price
- Low price
- Volume
- Dividends
- Stock Splits

Each row represents one trading day.

### Financial Indicators and Data Quality Metrics

The following indicators and metrics were analyzed based on the dataset:

#### Financial Indicators
1. **Minimum Close Price**  
   The lowest closing price recorded during the analyzed period.

2. **Maximum Close Price**  
   The highest closing price recorded during the analyzed period.

3. **Price Range**  
   The difference between the maximum and minimum closing price.

4. **Close Price Trend Over Time**  
   A time series visualization showing how Netflix’s closing price changed during the selected period.

#### Data Quality Metrics
5. **Missing Values Analysis**  
   Verification of whether the dataset contains missing values.

6. **Duplicate Rate**  
   Evaluation of whether duplicate records are present in the dataset.

7. **Outlier Rate**  
   Detection of unusual values in the Close price column using the IQR method.

8. **Data Accuracy Rate**  
   Measurement of the percentage of valid records based on positive Close price, positive Volume, and non-negative Dividends.

9. **Invalid Value Rate**  
   Share of records that do not meet the validity criteria.

10. **Close Price Field Accuracy Rate**  
    Verification that all Close price values are valid and greater than zero.

### Conclusion

Based on the analysis of Netflix stock data from February 2020 to August 2020, the company exhibited dynamic stock price behavior during the selected period.

The closing price ranged from approximately 29.88 to 54.87, resulting in a price difference of about 24.99, which indicates substantial variation over time. At the same time, the dataset proved to be of very high quality, with no missing values, no duplicates, no detected outliers in the Close price column, and a 100% data accuracy rate.

The analysis suggests that Netflix was characterized by strong price movement during this period, while the underlying dataset was complete, consistent, and reliable for further analysis.

# 3. Visa (V)

### Project Overview
This project presents a stock market analysis of Visa (V). The goal was to collect historical stock price data, inspect its structure and quality, and analyze selected financial indicators for the chosen period.

### Source of Data

The dataset used in this project contains historical stock market data for Visa (V), a publicly traded company.

The data was collected using the Python library `yfinance`, which retrieves financial data from Yahoo Finance.

Details of the dataset:
- Company: Visa
- Ticker: V
- Source: Yahoo Finance (via yfinance API)
- Data type: Time series financial data
- Time range: from 2015-01-15 to 2015-09-07
- Frequency: daily data (interval = 1d)

The dataset includes the following variables:
- Open price
- Close price
- High price
- Low price
- Volume
- Dividends
- Stock Splits

Each row represents one trading day.

### Financial Indicators and Data Quality Metrics

The following indicators and metrics were analyzed based on the dataset:

#### Financial Indicators
1. **Minimum Close Price**  
   The lowest closing price recorded during the analyzed period.

2. **Maximum Close Price**  
   The highest closing price recorded during the analyzed period.

3. **Price Range**  
   The difference between the maximum and minimum closing price.

4. **Close Price Trend Over Time**  
   A time series visualization showing how Visa’s closing price changed during the selected period.

#### Data Quality Metrics
5. **Missing Values Analysis**  
   Verification of whether the dataset contains missing values.

6. **Duplicate Rate**  
   Evaluation of whether duplicate records are present in the dataset.

7. **Outlier Rate**  
   Detection of unusual values in the Close price column using the IQR method.

8. **Data Accuracy Rate**  
   Measurement of the percentage of valid records based on positive Close price, positive Volume, and non-negative Dividends.

9. **Invalid Value Rate**  
   Share of records that do not meet the validity criteria.

10. **Close Price Field Accuracy Rate**  
    Verification that all Close price values are valid and greater than zero.

### Conclusion

Based on the analysis of Visa stock data from January 2015 to September 2015, the company demonstrated relatively stable but steadily evolving stock price behavior.

The difference between the minimum and maximum closing price indicates moderate variability, suggesting that Visa combines elements of stability with gradual growth. The price trend over time reflects consistent market performance without extreme fluctuations.

Additionally, the dataset showed very high quality, with no missing values, no duplicates, and a high data accuracy rate, ensuring reliability of the analysis.

Overall, Visa can be characterized as a financially stable company with consistent growth patterns and moderate volatility.

# 4. JPMorgan Chase & Co. (JPM)

### Project Overview
This project presents a stock market analysis of JPMorgan Chase & Co. (JPM). The goal was to collect historical stock price data, inspect its structure and quality, and analyze selected financial indicators for the chosen period.

### Source of Data

The dataset used in this project contains historical stock market data for JPMorgan Chase & Co. (JPM), a publicly traded company.

The data was collected using the Python library `yfinance`, which retrieves financial data from Yahoo Finance.

Details of the dataset:
- Company: JPMorgan Chase & Co.
- Ticker: JPM
- Source: Yahoo Finance (via yfinance API)
- Data type: Time series financial data
- Time range: from 2020-06-01 to 2020-08-31
- Frequency: daily data (interval = 1d)

The dataset includes the following variables:
- Open price
- Close price
- High price
- Low price
- Volume
- Dividends
- Stock Splits

Each row represents one trading day.

### Financial Indicators and Data Quality Metrics

The following indicators and metrics were analyzed based on the dataset:

#### Financial Indicators
1. **Minimum Close Price**  
   The lowest closing price recorded during the analyzed period.

2. **Maximum Close Price**  
   The highest closing price recorded during the analyzed period.

3. **Price Range**  
   The difference between the maximum and minimum closing price.

4. **Close Price Trend Over Time**  
   A time series visualization showing how JPMorgan’s closing price changed during the selected period.

#### Data Quality Metrics
5. **Missing Values Analysis**  
   Verification of whether the dataset contains missing values.

6. **Duplicate Rate**  
   Evaluation of whether duplicate records are present in the dataset.

7. **Outlier Rate**  
   Detection of unusual values in the Close price column using the IQR method.

8. **Data Accuracy Rate**  
   Measurement of the percentage of valid records based on positive Close price, positive Volume, and non-negative Dividends.

9. **Invalid Value Rate**  
   Share of records that do not meet the validity criteria.

10. **Close Price Field Accuracy Rate**  
    Verification that all Close price values are valid and greater than zero.

### Conclusion

Based on the analysis of JPMorgan stock data from June 2020 to August 2020, the company demonstrated stable stock performance with moderate fluctuations.

The difference between minimum and maximum closing prices indicates controlled variability, typical for large financial institutions. The price trend suggests steady growth with periodic changes, likely reflecting broader economic conditions and market sentiment.

Additionally, the dataset showed high quality, with no missing values, no duplicates, and a high data accuracy rate, ensuring reliability of the analysis.

Overall, JPMorgan can be characterized as a stable financial institution with consistent performance and moderate sensitivity to market changes.

# 5. Mastercard (MA)

### Project Overview
This project presents a stock market analysis of Mastercard (MA). The goal was to collect historical stock price data, inspect its structure and quality, and analyze selected financial indicators for the chosen period.

### Source of Data

The dataset used in this project contains historical stock market data for Mastercard (MA), a publicly traded company.

The data was collected using the Python library `yfinance`, which retrieves financial data from Yahoo Finance.

Details of the dataset:
- Company: Mastercard
- Ticker: MA
- Source: Yahoo Finance (via yfinance API)
- Data type: Time series financial data
- Time range: from 2025-01-02 to 2025-07-01
- Frequency: daily data (interval = 1d)

The dataset includes the following variables:
- Open price
- Close price
- High price
- Low price
- Volume
- Dividends
- Stock Splits

Each row represents one trading day.

### Financial Indicators and Data Quality Metrics

The following indicators and metrics were analyzed based on the dataset:

#### Financial Indicators
1. **Minimum Close Price**  
   The lowest closing price recorded during the analyzed period.

2. **Maximum Close Price**  
   The highest closing price recorded during the analyzed period.

3. **Price Range**  
   The difference between the maximum and minimum closing price.

4. **Close Price Trend Over Time**  
   A time series visualization showing how Mastercard’s closing price changed during the selected period.

#### Data Quality Metrics
5. **Missing Values Analysis**  
   Verification of whether the dataset contains missing values.

6. **Duplicate Rate**  
   Evaluation of whether duplicate records are present in the dataset.

7. **Outlier Rate**  
   Detection of unusual values in the Close price column using the IQR method.

8. **Data Accuracy Rate**  
   Measurement of the percentage of valid records based on positive Close price, positive Volume, and non-negative Dividends.

9. **Invalid Value Rate**  
   Share of records that do not meet the validity criteria.

10. **Close Price Field Accuracy Rate**  
    Verification that all Close price values are valid and greater than zero.

### Conclusion

Based on the analysis of Mastercard stock data from January 2025 to July 2025, the company demonstrated stable growth with moderate fluctuations.

The difference between the minimum and maximum closing price indicates a steady upward trend combined with controlled variability. Compared to more volatile companies, Mastercard shows consistent performance, reflecting strong market position and investor confidence.

The dataset also proved to be of high quality, with no missing values, no duplicates, and a high data accuracy rate, ensuring reliability of the analysis.

Overall, Mastercard can be characterized as a stable, growth-oriented company with predictable performance and moderate volatility.

# Overall Comparison & Conclusion

The comparative analysis of the selected companies reveals clear differences in stock behavior across industries.

- **Johnson & Johnson (JNJ)** exhibits the highest level of stability, with limited price fluctuations. This is typical for a mature healthcare company with predictable performance.

- **Netflix (NFLX)** shows the highest volatility and the most dynamic price movements, representing a growth-oriented technology company highly sensitive to market conditions and investor sentiment.

- **JPMorgan (JPM)** demonstrates stable performance with moderate variability, reflecting the influence of macroeconomic factors typical for large financial institutions.

- **Visa (V)** presents a balanced profile, combining stability with steady growth. The company shows consistent performance without extreme fluctuations.

- **Mastercard (MA)** also demonstrates stable growth with moderate volatility, similar to Visa, reflecting strong market positioning and investor confidence.

Overall, the analysis highlights how industry type influences stock performance:
- Technology companies tend to be more volatile
- Healthcare companies show the highest stability
- Financial institutions reflect macroeconomic conditions
- Payment companies combine growth with relatively low risk

Additionally, all datasets analyzed in this project demonstrated high data quality, with no missing values, no duplicates, and high accuracy rates, ensuring reliable and consistent results across all analyses.

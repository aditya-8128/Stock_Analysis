Comprehensive Quantitative Analysis of Stock Market Data

### Project Overview
This project aimed to perform a comprehensive quantitative analysis of stock market data using various statistical and inferential techniques. The analysis included descriptive statistics, time series analysis, volatility analysis, correlation analysis, comparative analysis, advanced metrics (Sharpe Ratio, Beta, CAGR), and inferential statistics with hypothesis testing. The primary goal was to derive meaningful insights about the performance, risk, and relationships of different stocks.

### Data Description
The dataset consists of daily stock prices for multiple companies, including their opening, closing, high, low, adjusted close prices, and trading volume. The stocks analyzed were AAPL, GOOG, MSFT, and NFLX.

### Analysis Components

#### Descriptive Statistics
Descriptive statistics provided a summary of key statistical measures such as mean, median, standard deviation, and percentiles for the closing prices of each stock. Key observations include:
- *AAPL*: Average closing price of $158.24 with a standard deviation of $7.36.
- *GOOG*: Average closing price of $100.63 with a standard deviation of $6.28.
- *MSFT*: Average closing price of $275.04 with a standard deviation of $17.68.
- *NFLX*: Average closing price of $327.61 with a standard deviation of $18.55.

#### Time Series Analysis
The time series analysis revealed the trends and patterns of closing prices over time. Notable observations include:
- *AAPL and MSFT*: Showed a general upward trend during the period.
- *NFLX*: Exhibited more pronounced fluctuations compared to other stocks.
- *GOOG*: Displayed relatively stable price movements.

#### Volatility Analysis
Volatility was measured using the standard deviation of closing prices:
- *NFLX*: Highest volatility with a standard deviation of $18.55.
- *MSFT*: Next highest, with $17.68.
- *AAPL*: Lower volatility at $7.36.
- *GOOG*: Least volatile with $6.28.

#### Correlation Analysis
The correlation matrix indicated the relationships between the stocks:
- *AAPL and MSFT*: Showed a higher positive correlation, suggesting that their prices tend to move together.
- *GOOG and NFLX*: Showed varying degrees of positive correlation with other stocks, indicating different degrees of price relationship.

#### Comparative Analysis
The percentage change in closing prices from the start to the end of the period highlighted performance differences:
- *MSFT*: Highest positive change of approximately 16.10%.
- *AAPL*: Positive change of 12.23%.
- *GOOG*: Slight negative change of -1.69%.
- *NFLX*: Significant negative change of -11.07%.

### Advanced Metrics
- *Sharpe Ratio*: Indicates the risk-adjusted return. Higher values are better.
- *Beta*: Measures the stock's volatility in relation to the market. A beta of 1 indicates that the stock moves with the market.
- *CAGR*: Compound Annual Growth Rate shows the mean annual growth rate of an investment over a specified period of time longer than one year.

### Inferential Statistics and Hypothesis Testing
- *Normality Test (Shapiro-Wilk Test)*:
  - Most daily returns were found to follow a normal distribution.
- *T-Test (AAPL vs. MSFT)*:
  - No significant difference between the daily returns of AAPL and MSFT (p-value > 0.05).
- *ANOVA Test*:
  - No significant difference in the daily returns across AAPL, GOOG, MSFT, and NFLX (p-value > 0.05).

### Conclusions
Based on the analyses performed, the following conclusions were drawn:
- *Descriptive Analysis*: MSFT and NFLX had higher average closing prices and greater volatility, indicating they were more volatile investments.
- *Time Series Trends*: AAPL and MSFT showed consistent upward trends, while NFLX experienced significant fluctuations.
- *Volatility Analysis*: NFLX was the most volatile stock, suggesting higher risk.
- *Correlation Analysis*: AAPL and MSFT had higher positive correlations, implying that their prices tend to move together.
- *Performance Comparison*: MSFT showed the best performance over the period with a significant positive change, while NFLX had the worst performance with a notable decline.
- *Advanced Metrics*: MSFT had the highest Sharpe ratio, indicating the best risk-adjusted return. NFLX had the highest beta, suggesting higher market-related volatility.
- *Hypothesis Testing*: No significant difference in the daily returns across different stocks, and the daily returns generally followed a normal distribution.

This comprehensive analysis provided valuable insights into the performance, risk, and relationships of different stocks, aiding in making informed investment decisions.

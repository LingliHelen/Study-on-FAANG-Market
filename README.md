# Impact of Market Events on FAANG Stocks
This project analyzes how major macroeconomic events influence the stock performance of major technology companies including Apple, Microsoft, and Meta.

The analysis covers a three-year period from August 1, 2022, to August 1, 2025, and applies an event study framework to evaluate market reactions around key economic announcements.

## Ressearch Question
How do major macroeconomic announcements (e.g. Federal Reserve interest rate decisions, inflation releases) impact major technology firms' short-term stock performance?

## Data Sources
Historical stock price data was retrieved using the **yfinance API**.

Time period:  
August 1, 2022 – August 1, 2025

Stocks analyzed:

- Apple (AAPL)
- Microsoft (MSFT)
- Meta (META)

## Methodology
1. Download historical stock prices using **yfinance**
2. Compute **daily returns** 
3. Identify key macroeconomic event dates
4. Construct an **event window of [-5, +5] trading days** to capture market reactions before and after each event
5. Visualize cumulative stock returns around each event to examine market reactions

## Example Visualization


## Market Events Considered
- Federal Reserve implement an increase in interest rates
- The dissemination of inflation data
- Significant Disclosures within the Technological Sphere

## Tools & Libraries
- Python
- yfinance API for data retrieval
- pandas, numpy for data manipulation
- matplotlib, seaborn for visualization

## How to Run
No setup required — just click "Open in Colab" at the top of Market_Impact_on_FAANG.ipynb to open and run the notebook directly in Google Colab.



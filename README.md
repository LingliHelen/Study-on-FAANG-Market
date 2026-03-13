# Event Study: Impact of Macroeconomic Announcements on FAANG Stocks
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
1. Download historical stock prices using the **yfinance API**
2. Compute **daily returns** 
3. Identify key macroeconomic event dates
4. Construct an **event window of [-5, +5] trading days** to capture market reactions before and after each event
5. Visualize cumulative stock returns around each event to examine market reactions

## Example Visualization
Cumulative stock returns around a Federal Reserve interest rate announcement using an event study window of [-5, +5] trading days.
<img width="1042" height="148" alt="Screenshot 2026-03-13 at 00 48 52" src="https://github.com/user-attachments/assets/a682472a-ae18-4c8d-be46-bc25c5445d3a" />
The figure illustrates cumulative stock returns around a Federal Reserve rate hike announcement. 
The dashed vertical line represents the event date (Day 0), allowing us to observe market reactions before and after the announcement.

## Key Findings
The event study suggests that macroeconomic announcements can generate noticeable short-term movements in technology stock returns. 
Market reactions appear to vary across companies, indicating different sensitivities to macroeconomic news. 
These results highlight the importance of macroeconomic information in shaping short-term market behavior.

## Market Events Considered
- Federal Reserve interest rate hike announcements
- U.S. inflation (CPI) releases
- Major technology sector earnings announcements
  
## Tools & Libraries
- Python (data analysis and visualization)
- yfinance API for data retrieval
- pandas, numpy for data manipulation
- matplotlib, seaborn for visualization

## How to Run
No setup required — just click "Open in Colab" at the top of Market_Impact_on_FAANG.ipynb to open and run the notebook directly in Google Colab.



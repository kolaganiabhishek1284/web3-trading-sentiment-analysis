# Web3 Trading Behavior vs Market Sentiment Analysis

## Project Overview
This project analyzes the relationship between trader behavior and overall market sentiment in the cryptocurrency market. By combining Bitcoin Fear & Greed sentiment data with real historical trading data from Hyperliquid, the study explores how trader profitability, leverage usage, and trading volume vary across different emotional market states.

The primary goal is to understand whether traders behave more aggressively during Greed periods and more conservatively during Fear periods, and how these behaviors impact trading outcomes.

---

## Objective
To analyze how trading behavior (profitability, risk exposure, and activity level) aligns or diverges from market sentiment (Fear vs Greed), and to identify behavioral patterns that can support smarter trading strategies in Web3 markets.

---

## Folder Structure

---

## Datasets Used
1. **Bitcoin Fear & Greed Index**
   - Columns: Date, Classification (Fear / Greed)
   - Purpose: Represents overall market sentiment on a daily basis

2. **Hyperliquid Historical Trader Data**
   - Includes: account, symbol, execution price, size, side, time, closedPnL, leverage, event
   - Purpose: Captures real trader behavior and performance metrics

---

## Methodology
- Converted timestamps into daily format to align trades with market sentiment
- Merged trader data with sentiment data using the trading date
- Aggregated key metrics such as average PnL, leverage, volume, and trade count
- Compared trader behavior during Fear and Greed periods
- Visualized differences using bar charts and box plots

---

## Key Insights
- Traders tend to use higher leverage during Greed periods, indicating increased risk appetite
- Average profitability is higher during Greed, but profit volatility also increases
- Fear periods show reduced trading volume and more conservative leverage usage
- Market sentiment influences trader aggression more than price direction

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Google Colab Usage
All notebooks were developed and executed in **Google Colab**.  
Datasets were manually uploaded into the Colab environment as provided via Google Drive links.  
Notebook access is set to **“Anyone with the link can view.”**

---

## Author
**Kolagani Abhishek**

---

## Notes
- The repository structure strictly follows the assignment instructions
- All outputs (CSV files and charts) are saved within the appropriate folders
- The analysis and report are written in original, human-authored language

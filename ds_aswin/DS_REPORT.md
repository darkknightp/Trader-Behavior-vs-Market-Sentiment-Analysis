# Trader Behavior vs Market Sentiment Analysis
**Web3 Trading Data Science Project**

**Candidate:** Aswin  
**Position:** Junior Data Scientist  
**Company:** PrimeTrade  
**Date:** January 2025

---

## 1. Problem Statement

Cryptocurrency markets are highly sentiment-driven. This analysis investigates **how market sentiment (Fear & Greed Index) influences trader performance on Hyperliquid**, a decentralized exchange.

**Research Question:** Do traders perform better during Fear or Greed periods, and how does their behavior (volume, risk-taking) change with sentiment?

---

## 2. Dataset Description

### Fear & Greed Index
- **Source:** Bitcoin market sentiment tracker
- **Period:** [Your start date] to [Your end date]
- **Records:** [X] daily observations
- **Categories:** Extreme Fear (0-24), Fear (25-49), Neutral (50-54), Greed (55-74), Extreme Greed (75-100)

### Hyperliquid Trading Data
- **Source:** On-chain DEX trading records
- **Period:** [Your start date] to [Your end date]
- **Records:** [X] individual trades across [X] days
- **Key Metrics:** Closed P&L, trade volume, leverage, timestamps

---

## 3. Methodology

### Data Preprocessing
1. **Timestamp Conversion:** Converted trading timestamps to datetime format for date alignment
2. **Data Aggregation:** Grouped individual trades by day to match sentiment frequency
3. **Merging:** Combined sentiment and trading data using date as the key
4. **Metrics Calculated:**
   - Average daily P&L by sentiment
   - Trading volume (trades per day) by sentiment
   - Average leverage usage by sentiment

### Analysis Approach
- **Tool:** Python (pandas, matplotlib, seaborn)
- **Methods:** GroupBy aggregations, data visualization, comparative analysis
- **Visualizations:** 5 charts showing sentiment distribution, profitability, volume, leverage, and time trends

---

## 4. Key Findings

### Finding #1: Profitability Patterns
**[Insert Chart: Profitability by Sentiment]**

- **Best Performance:** [Sentiment type] periods show average daily P&L of $[X]
- **Worst Performance:** [Sentiment type] periods show average daily P&L of $[X]
- **Difference:** [X]% higher profitability during [sentiment]

**Interpretation:** [Your interpretation - e.g., "Traders achieve better returns during Fear periods, suggesting successful traders employ contrarian strategies"]

---

### Finding #2: Trading Volume
**[Insert Chart: Volume by Sentiment]**

- **Most Active:** [Sentiment] periods average [X] trades per day
- **Least Active:** [Sentiment] periods average [X] trades per day
- **Pattern:** Trading volume is [higher/lower] during [sentiment]

**Interpretation:** [Your interpretation - e.g., "Increased activity during Greed indicates higher market participation when sentiment is positive"]

---

### Finding #3: Risk Behavior (Leverage)
**[Insert Chart: Leverage by Sentiment]**

- **Highest Risk:** [Sentiment] periods show [X]x average leverage
- **Lowest Risk:** [Sentiment] periods show [X]x average leverage
- **Pattern:** Leverage usage [increases/decreases] with [sentiment]

**Interpretation:** [Your interpretation - e.g., "Traders take on significantly more risk during Greed periods, indicating overconfidence"]

---

### Finding #4: Time Trends
**[Insert Chart: Daily Activity Trend]**

- Sentiment shifts create visible impacts on trading volume
- [Pattern observed - e.g., "Volume spikes align with extreme sentiment periods"]

---

## 5. Summary Statistics

| Sentiment | Avg Daily P&L | Avg Trades/Day | Trading Days |
|-----------|---------------|----------------|--------------|
| Extreme Fear | $[X] | [X] | [X] |
| Fear | $[X] | [X] | [X] |
| Neutral | $[X] | [X] | [X] |
| Greed | $[X] | [X] | [X] |
| Extreme Greed | $[X] | [X] | [X] |

---

## 6. Business Recommendations

### For Individual Traders
1. **Timing Strategy:** Consider [sentiment] periods as optimal entry points based on historical profitability
2. **Risk Management:** Be cautious with leverage during [sentiment] when risk-taking increases
3. **Volume Analysis:** Use sentiment shifts as signals for market activity changes

### For Trading Platforms
1. **Sentiment Alerts:** Implement real-time notifications when Fear & Greed Index reaches extreme levels
2. **Risk Warnings:** Auto-alert users when average leverage exceeds safe thresholds during specific sentiment periods
3. **Educational Content:** Provide guidance on optimal strategies for different sentiment regimes

### For Further Analysis
1. Segment traders into profitable vs unprofitable groups
2. Analyze specific cryptocurrencies separately
3. Build predictive models using sentiment as a feature

---

## 7. Limitations

- **Time Period:** Analysis limited to available data ([date range])
- **Causation:** Correlation does not imply causation; sentiment may not directly cause performance
- **External Factors:** Other market conditions (regulations, news, macroeconomics) not accounted for
- **Sample Bias:** Only includes Hyperliquid traders; may not generalize to all markets

---

## 8. Conclusion

This analysis reveals that **market sentiment significantly influences trader behavior on decentralized exchanges**. Key findings include:

1. [Summary of profitability finding]
2. [Summary of volume finding]
3. [Summary of risk behavior finding]

These insights can help traders optimize entry/exit timing, platforms improve user experience through sentiment-based features, and risk managers better understand behavioral patterns during different market conditions.

**The data suggests that [your main conclusion - e.g., 'contrarian strategies may outperform momentum trading in crypto markets'].**

---

## Technical Appendix

**Code Repository:** [GitHub link]  
**Notebook:** `notebook_1.ipynb` (Google Colab)  
**Processed Data:** `csv_files/merged_trading_sentiment.csv`  
**Visualizations:** All charts in `outputs/` folder

**Libraries Used:**
- pandas 2.x (data manipulation)
- matplotlib 3.x (visualization)
- seaborn 0.x (statistical plots)
- numpy 1.x (numerical operations)

---

**Report Prepared By:** Aswin  
**Contact:** [Your email]  
**Submission:** Junior Data Scientist Position - PrimeTrade

# 📊 Trader Behavior vs Market Sentiment Analysis

**Data Science Project - Aswin**

---

## 🎯 Project Overview

This project analyzes how market sentiment (Fear & Greed Index) influences trader performance on Hyperliquid, a decentralized exchange. The goal is to uncover patterns that can help traders make better decisions.

### Key Question
**Do traders perform better during Fear or Greed periods?**

---

## 📂 Project Structure

```
ds_aswin/
├── notebook_1.ipynb                      # Main analysis notebook
├── csv_files/
│   └── merged_trading_sentiment.csv      # Processed dataset
├── outputs/
│   ├── 01_sentiment_distribution.png
│   ├── 02_profitability_by_sentiment.png
│   ├── 03_volume_by_sentiment.png
│   ├── 04_leverage_by_sentiment.png
│   └── 05_time_trends.png
├── ds_report.pdf                         # Final analysis report
└── README.md                             # This file
```

---

## 📊 Datasets

### 1. Fear & Greed Index
- **Source:** Bitcoin market sentiment tracker
- **Format:** Daily values (0-100)
- **Categories:** Extreme Fear, Fear, Neutral, Greed, Extreme Greed

### 2. Hyperliquid Trading Data
- **Source:** On-chain trading records
- **Contains:** Individual trades with P&L, volume, leverage
- **Size:** 30+ MB

---

## 🚀 How to Run

### Step 1: Open in Google Colab
1. Upload `notebook_1.ipynb` to [Google Colab](https://colab.research.google.com/)
2. Or click the Colab link: [Open in Colab]

### Step 2: Run All Cells
1. Click **Runtime** → **Run all**
2. The notebook will:
   - Download datasets automatically from Google Drive
   - Clean and merge the data
   - Create 5 visualizations
   - Generate insights

### Step 3: View Results
- Charts will be saved in `outputs/` folder
- Processed data in `csv_files/` folder
- Summary statistics displayed in notebook

**Expected Runtime:** 5-10 minutes

---

## 📈 Analysis Summary

The analysis answers three key questions:

1. **Profitability:** Which sentiment period has the best returns?
2. **Activity:** How does trading volume change with sentiment?
3. **Risk:** Do traders use more leverage during Fear or Greed?

---

## 🛠️ Technical Stack

- **Language:** Python 3.x
- **Libraries:**
  - `pandas` - Data manipulation
  - `matplotlib` - Visualization
  - `seaborn` - Statistical plots
  - `numpy` - Numerical operations

- **Platform:** Google Colab
- **Data Size:** ~35 MB total

---

## 📊 Visualizations

The project creates 5 professional charts:

1. **Sentiment Distribution** - How often each sentiment occurs
2. **Profitability by Sentiment** - Average daily P&L comparison
3. **Volume by Sentiment** - Trading activity patterns
4. **Leverage by Sentiment** - Risk-taking behavior
5. **Time Trends** - Sentiment and volume over time

All charts are high-resolution (300 DPI) and ready for presentations.

---

## 🎓 Skills Demonstrated

- Data loading and preprocessing
- Date/time handling
- Data aggregation (groupby)
- Data visualization
- Business insight generation
- Professional documentation

---

## 📝 Notes

- All data is publicly available
- Analysis is reproducible - anyone can run the notebook

---

**Last Updated:** January 2026  
**Status:** Complete ✅

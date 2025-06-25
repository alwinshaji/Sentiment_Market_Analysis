# 📊 Bitcoin Market Sentiment & Trader Behavior Analysis

## 🚀 Project Overview
This project analyzes how Bitcoin market sentiment (Extreme Fear, Fear, Neutral, Greed, Extreme Greed) affects trader behavior and performance. Using historical trade data from Hyperliquid, we explore:
- Profit and loss during different sentiment phases
- Trade direction biases (buy vs sell)
- Trade sizes and leverage patterns
- Risk and volatility indicators
- Time-based performance trends

---

## 🔍 Data Sources
- **Fear & Greed Index**: Daily sentiment labels (Extreme Fear to Extreme Greed)
- **Historical Data** (not included in repo due to size): detailed trade logs (timestamp, account, side, size, closed PnL, start position, etc.)

To run this notebook, download the historical trade CSV from this Google drive link and make sure it is in the same directory as the notebook file : https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing


---

## 📁 Repository Contents

.
├── Sentiment_Market_Analysis.ipynb # Main analysis notebook
├── fear_greed_index.csv # Daily sentiment data
├── historical_data.csv (download separately) # Trader dataset (large file excluded)
└── README.md # This overview

---

## 🛠️ How to Run
1. Open the notebook in Jupyter.
2. Ensure both datasets are present in the same folder.
3. Run all cells (`Kernel → Restart & Run All`) to reproduce plots and results.

---

## 📈 Analysis Highlights
1. **Closed PnL Distribution**: Highest avg profits in Fear phases; median PnL = 0 (few big winners).
2. **Buy vs Sell Performance**: Buys win in Fear; sells win in Greed.
3. **Average Trade Size**: Largest during Fear; moderate in Neutral and Greed.
4. **Leverage (Start Position)**: Cleaned positive values show highest median in Extreme Fear.
5. **Average Closed PnL by Side**: Confirms directional bias per sentiment.
6. **PnL Volatility**: Highest under Extreme Fear; neutral most stable.
7. **Time Trends**: Daily PnL and sentiment count series highlight temporal patterns.

---

## ⚠️ Limitations
- **Historical trade data not included** due to large size. Add it manually.
- `Start Position` used as leverage proxy—actual leverage details not available.
- Median PnL = 0 indicates high skew; a few large trades drive results.

---

## 🎯 Next Steps / Contribution Ideas
- Analyze trader consistency across sentiments
- Predictive modeling: forecast profit likelihood based on features
- Extend the time-based analysis (e.g. weekday/hourly performance)
- Add actual leverage or capital metrics if available

---

## 👤 Author
Alwin SHaji 
---

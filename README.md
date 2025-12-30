# 📊 Crypto Sentiment & PnL Research

**Analyzing the relationship between Bitcoin Market Sentiment (Fear & Greed Index) and Trader Performance on Hyperliquid DEX**

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🎯 Key Findings

| Sentiment | Avg PnL/Trade | Win Rate | Total Trades |
|-----------|---------------|----------|--------------|
| **Extreme Greed** | **$67.89** ⭐ | **46.5%** | 39,992 |
| Fear | $54.29 | 42.1% | 61,837 |
| Greed | $42.74 | 38.5% | 50,303 |
| Neutral | $34.31 | 39.7% | 37,686 |
| Extreme Fear | $34.54 | 37.1% | 21,400 |

> **💡 Key Insight:** Traders perform **2x better** during Extreme Greed vs Extreme Fear periods!

---

## 📁 Project Structure

```
├── sentiment_trader_analysis.ipynb    # Main analysis notebook
├── executed_analysis.ipynb            # Notebook with execution results
├── fear_greed_index.csv               # Bitcoin Fear & Greed Index data
├── historical_data.csv                # Hyperliquid trading data
├── sentiment_performance_summary.csv  # Aggregated performance by sentiment
├── trader_statistics.csv              # Individual trader metrics
├── daily_performance.csv              # Daily aggregated data
└── *.png                              # Generated visualizations
```

---

## 📈 Visualizations

The analysis generates multiple visualizations including:
- Fear & Greed Index time series during trading period
- Performance metrics by sentiment classification
- Cumulative PnL vs Sentiment overlay
- Trader performance distribution
- Asset-sentiment performance heatmaps

---

## 🚀 Trading Strategies Derived

1. **Ride the Greed Wave** 📈 - Increase position sizes when sentiment > 75
2. **Fear Zone Caution** ⚠️ - Reduce exposure during panic (< 25)
3. **Neutral Zone Scalping** 🎯 - Short-term trades with balanced risk/reward
4. **Sentiment-Weighted Sizing** 📊 - Scale positions dynamically based on mood

---

## 🔧 Setup & Usage

```bash
# Clone the repository
git clone https://github.com/CodeGovindz/crypto-sentiment-pnl-research.git
cd crypto-sentiment-pnl-research

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Run the notebook
jupyter notebook sentiment_trader_analysis.ipynb
```

---

## 📊 Data Sources

- **Fear & Greed Index**: Historical Bitcoin market sentiment (2018-2025)
- **Trading Data**: 211K+ trades from Hyperliquid DEX (Sep 2024 - May 2025)

---

## 📝 Analysis Highlights

- **211,218+ trades** analyzed from **32 unique traders**
- **$1.19 billion** total trading volume
- **81% of traders** were profitable overall
- Comprehensive correlation between sentiment regimes and trading outcomes

---

## 🤝 Contributing

Feel free to open issues or submit pull requests for improvements!

---

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

---

*Built with ❤️ using Python, Pandas, and Jupyter*

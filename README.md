# 🥈 Silver Price Analysis (2016–2026)
### Exploratory Data Analysis & Market Insights

**Author:** Areeba Bushra  
**Data Source:** Yahoo Finance — Silver Futures (SI=F)  
**Period:** 2016 – 2026 (10 Years)  
**Tools:** Python, Jupyter Notebook, pandas, matplotlib, seaborn, yfinance

---

## 📌 Overview

This project explores 10 years of silver futures price data (2016–2026) fetched live from Yahoo Finance. It covers price trends, moving averages, volatility patterns, momentum indicators (RSI & MACD), monthly seasonality, and the real-world factors driving silver's market movements in 2024–2026. Built with AI assistance as a learning project — exploring financial data analysis and technical indicators.

---

## 📂 Notebook Structure

| Section | Description |
|---|---|
| 1. Imports & Config | Libraries and consistent color palette setup |
| 2. Data Collection | Live data fetch via `yfinance` (SI=F ticker) |
| 3. Preprocessing & Feature Engineering | Date features, daily returns, cumulative returns |
| 4. Statistical Summary | Key price insights, win rate, volatility metrics |
| 5. Price Trend & Moving Averages | 20/50/200-day MAs with bullish/bearish zones |
| 6. Price & Returns Distribution | Histograms, box plots, cumulative return chart |
| 7. Volatility & Bollinger Bands | Rolling volatility, ATR, Bollinger Band analysis |
| 8. RSI & MACD | Momentum indicators with live signal status |
| 9. Yearly Performance | Annual returns, volatility, and volume by year |
| 10. Monthly Seasonality | Win rate, return heatmap, distribution by month |
| 11. Day-of-Week Analysis | Return and volume patterns by trading day |
| 12. Correlation Analysis | Feature correlation heatmap |
| 13. Market Insights | Research-backed drivers of silver's price surge |
| 14. Executive Summary | Full findings printed in one clean output |

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `yfinance` | Fetching historical silver futures data |
| `pandas` | Data manipulation and feature engineering |
| `numpy` | Numerical calculations |
| `matplotlib` | All chart visualizations |
| `seaborn` | Heatmaps and statistical plots |

---

## ⚙️ How to Run

**1. Clone the repository**
```bash
git clone https://github.com/AreebaBushra/silver-price-analysis.git
cd silver-price-analysis
```

**2. Install dependencies**
```bash
pip install yfinance pandas numpy matplotlib seaborn jupyter
```

**3. Run the notebook**
```bash
jupyter notebook Silver-Price-Analysis.ipynb
```

> No dataset download needed — data is fetched live from Yahoo Finance each time you run it.

---

## 💡 Key Findings

- Silver delivered a **significant positive return** over the 10-year period driven by industrial demand
- **2020** showed extreme volatility due to COVID-19 market disruption and the historic silver squeeze
- **January and July** historically show the strongest average daily returns
- Bollinger Band analysis reveals silver frequently enters overbought territory during industrial demand spikes
- RSI and MACD signals confirm bullish momentum entering 2025–2026

---

## 🌍 Why Silver Is Rising (2024–2026)

Based on market research conducted as part of this analysis:

-  **Solar demand** — 230M+ oz consumed in 2024, representing 29% of all industrial silver demand
-  **EV growth** — Electric vehicles use 2–3× more silver than traditional cars
-  **AI & data centers** — Silver critical for electrical contacts and thermal management in servers
-  **Supply deficits** — 5th consecutive year of global deficit in 2025 (~115–120M oz/year shortfall)
-  **Safe-haven demand** — Economic uncertainty and a weakening USD driving investment demand

---




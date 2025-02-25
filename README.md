# Great Britain (GB) Electricity Market Intraday Trading Strategy

This repository contains a research project focused on developing an **intraday trading strategy** for the GB electricity market. The strategy leverages insights from **day-ahead and intraday price dynamics**, incorporating **weather-driven factors** to optimize electricity trading for **profit maximization and risk mitigation**.

## 📌 Project Overview
This study analyzes electricity price data from **the first week of December 2024**, focusing on **intraday price patterns** and their correlation with **temperature**. The project explores three trading strategies:

### ⚡ Trading Strategies:
1. **Intraday Trading** – Reacting to real-time price fluctuations by **buying during off-peak hours** and **selling during peak hours**.
2. **Volatility-Based Scalping** – Capitalizing on price fluctuations during volatile periods for **short-term profits**.
3. **Seasonal Arbitrage** – Exploiting **seasonal trends and cold snaps** for **long-term gains**.

## 🔍 Key Findings
- **Price Trends** – Intraday prices are **significantly higher** than day-ahead prices, peaking during **evening hours**.
- **Temperature Correlation** – Lower temperatures **increase demand**, driving **higher prices**.
- **Volatility Patterns** – Volatility spikes during **rapid temperature changes** and **peak demand periods**.

## 📂 Files Included
- **📊 Data** – GB day-ahead and intraday electricity price datasets:
  - `GB_dayahead_pricedata.csv`
  - `GB_intraday_pricedata.csv`
- **📜 Code** – Python notebook implementing data analysis & trading strategy simulations:
  - `electricity_analysis.py`
- **📖 Documentation** – Research proposal outlining methodology & findings:
  - `findings_RP.pdf`

## 🚀 Usage
1. **Clone the repository**:
   ```sh
   git clone https://github.com/vybhav345/Electricity-Trading-Optimization.git

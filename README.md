# 🌍 Global Asset Allocation & Risk Analysis (2021-2025)

### 📊 Project Overview
In a volatile global market, "Where should I put my money?" is a data problem, not a guessing game. 
This project utilizes **Python** to analyze 5 years of historical market data, comparing the risk-adjusted returns of four distinct asset classes:
1. **Nifty 50** (Indian Equities)
2. **Nasdaq 100** (US Tech)
3. **Gold** (Commodities)
4. **Bitcoin** (Cryptocurrency)

The goal was to build a volatility-proof portfolio model by understanding correlations and maximum drawdowns.

### 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `yfinance` (Data Extraction), `Pandas` (Data Cleaning & Manipulation), `Matplotlib` & `Seaborn` (Visualization), `NumPy` (Statistical Analysis).

### 🔍 Key Analysis & Insights

**1. Correlation Matrix (The "Safe Haven" Test)**
* **Hypothesis:** Does Bitcoin act as "Digital Gold" during market crashes?
* **Finding:** My analysis revealed a high positive correlation between **Bitcoin and Nasdaq**, suggesting Bitcoin behaves more like a tech stock than a hedge.
* **The Hedge:** **Gold** showed a correlation of **[Insert Correlation Number, e.g., 0.12]** with Indian Equities, validating it as the superior portfolio diversifier.

**2. Risk vs. Reward (Sharpe Ratio)**
* Calculated the **Sharpe Ratio** to measure risk-adjusted returns.
* While Bitcoin offered the highest raw return, it also carried a **Max Drawdown of [Insert Max Crash %]**.
* A diversified mix (70% Stocks / 30% Gold) offered the most stable growth trajectory.

### 📉 Visualizations
*<img width="1005" height="529" alt="image" src="https://github.com/user-attachments/assets/a598c9c4-fda7-4a03-b342-50b18feaa081" />
*

### 🚀 How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install yfinance pandas matplotlib seaborn`.
3.  Run the script to fetch live data from Yahoo Finance API.

---
*Created by Sai Krishna Reddy | BBA Data Analytics*

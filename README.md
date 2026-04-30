# Earnings Surprise & Stock Price Reaction Analysis

Analyzing the effect of earnings surprises on short-term stock price reactions using S&P 500 data.

---

## Overview

While earnings surprises provide a standardized metric for evaluating company performance, stock price reactions are rarely that simple. This project investigates how much of the short-term price movement can be explained by earnings surprises alone, and whether other factors — such as sector, market conditions, or company size — play a significant role.

---

## Research Question

How strongly do earnings surprises explain short-term stock price reactions, and what other factors moderate this relationship?

---

## Data Sources

- **yfinance** — Historical stock price data and earnings history for S&P 500 companies
- **Wikipedia** — S&P 500 company list and sector classifications

---

## Methodology

1. Collect earnings and historical stock price data for S&P 500 companies via the yfinance API
2. Engineer features by calculating earnings surprise percentage, short-term price reactions, and additional variables such as sector and market cap
3. Perform exploratory data analysis (EDA) to examine distributions and visualize correlations between earnings surprises and stock price reactions using pandas, NumPy, and Matplotlib
4. Conduct statistical analysis to quantify the strength of the relationship between earnings surprise magnitude and short-term price movements
5. Train machine learning models (Random Forest, XGBoost) to predict stock price reactions and extract feature importance scores
6. Summarize findings and identify which factors most strongly moderate the earnings surprise effect on stock prices

---

## Tech Stack

**Languages & Libraries:** Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost, yfinance

---

## How to Run

**1. Clone the repository**
```bash
git clone https://github.com/SiHyunDanielRyu/earnings-surprise-analysis.git
cd earnings-surprise-analysis
```

**2. Create and activate a virtual environment**
```bash
python -m venv venv
source venv/bin/activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Run the notebooks in order**
```
01_data_collection.ipynb
02_feature_engineering.ipynb
03_eda.ipynb
04_modeling.ipynb
```

---

## Results

*To be updated as the project progresses.*

---

## Author

Si-Hyun Daniel Ryu — Northeastern University, BS Computer Science & Data Science
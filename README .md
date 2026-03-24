# 📈 Stock Market Analytics — Data Analytics Internship Project

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=flat)
![NLP](https://img.shields.io/badge/NLP-TextBlob%20%7C%20VADER-purple?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 📌 Project Overview

A complete **end-to-end Data Analytics project** on S&P 500 Stock Market data covering data collection, exploratory data analysis, data visualization, and sentiment analysis on financial news.

**Dataset:** [S&P 500 Stock Data 2013–2018](https://www.kaggle.com/datasets/camnugent/sandp500) — Kaggle

---

## ✅ Tasks Completed

| # | Task | Description |
|---|------|-------------|
| 1 | 📂 Data Collection | Loaded & cleaned S&P 500 stock price data |
| 2 | 🔍 Exploratory Data Analysis | Price trends, volatility, correlations, hypothesis testing |
| 3 | 📊 Data Visualization | 8 charts + master dashboard using Matplotlib & Seaborn |
| 4 | 💬 Sentiment Analysis | Classified financial news headlines using TextBlob & VADER |

---

## 🔍 Key Findings

- 📊 **Opening price** is an extremely strong predictor of closing price (correlation > 0.99)
- 📉 **Volume alone** does not predict daily returns
- 🏆 Majority of S&P 500 stocks **gained value** between 2013 and 2018
- 💬 Financial news headlines tend to be **mixed** — both positive and negative in sentiment
- ⚠️ Some stocks showed **extreme volatility** while others remained very stable

---

## 📊 Visualizations

| Chart | Description |
|-------|-------------|
| Top 10 Best Performers | Horizontal bar chart of highest returning stocks |
| Top 10 Most Traded | Stocks with highest average daily trading volume |
| Stock Price Trends | Line chart of top 5 performers over time |
| Avg Price by Year | S&P 500 market trend from 2013 to 2018 |
| Most Volatile Stocks | Bar chart of stocks with highest price swings |
| Volume vs Daily Return | Scatter plot exploring volume-return relationship |
| Gainers vs Losers | Pie chart showing overall market performance |
| Master Dashboard | Combined 6-panel analytics dashboard |

---

## 🛠 Tools & Libraries

```
Python 3.10
├── pandas          — Data manipulation & analysis
├── numpy           — Numerical computing
├── matplotlib      — Data visualization
├── seaborn         — Statistical visualizations
├── beautifulsoup4  — Web scraping for news headlines
├── requests        — HTTP requests
├── textblob        — Sentiment analysis (TextBlob)
└── vaderSentiment  — Sentiment analysis (VADER)
```

---

## 📁 Project Structure

```
tockMarketAnalytics/
│
├── StockMarket_Analytics.ipynb   ← Main notebook (all 4 tasks)
│
├── stocks_clean_sample.csv                        ← Cleaned stock dataset
├── stocks_sentiment_results.csv            ← Sentiment analysis results
│
├── stocks_dashboard.png                    ← Master analytics dashboard
├── stocks_sentiment_analysis.png           ← Sentiment analysis charts
│
└── README.md                               ← You are here!
```

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/alysaqiib/CodeAlpha_StockMarketAnalytics.git
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn textblob vaderSentiment requests beautifulsoup4
python -m textblob.download_corpora
```

**3. Open the notebook**
- Upload `StockMarket_Analytics.ipynb` to [Google Colab](https://colab.research.google.com)
- Upload `all_stocks_5yr.csv` from Kaggle when prompted
- Run all cells from top to bottom ▶️

---

## 📬 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/muhammad-ali-495819283)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/alysaqiib)

---

⭐ **If you found this project useful, consider giving it a star!**

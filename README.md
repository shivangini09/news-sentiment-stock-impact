# news-sentiment-stock-impact
# 📰📈 News Sentiment & Stock Impact Analysis

A project that explores the relationship between financial news sentiment and short-term stock price movements using NLP and statistical analysis.

This repo implements a clean, modular pipeline that collects headlines and stock data, scores sentiment using FinBERT, and applies time series techniques to evaluate predictive relationships.

---

## 🔍 Project Overview

Can financial news help predict short-term stock movements?

This project:
- Collects 1-year of news headlines for **AAPL**, **TSLA**, **AMZN**
- Uses **FinBERT** (finance-specific BERT model) to generate daily sentiment scores
- Aligns sentiment with daily stock returns
- Tests correlations and Granger Causality
- Visualizes findings using **Plotly** and **Seaborn**

---

## 🛠️ Tech Stack

| Task                   | Tool                                                                 |
|------------------------|----------------------------------------------------------------------|
| News Collection        | [NewsAPI](https://newsapi.org/), fallback: Yahoo Finance Scraping   |
| Stock Price Data       | [`yfinance`](https://pypi.org/project/yfinance/)                     |
| Sentiment Analysis     | [`FinBERT`](https://huggingface.co/ProsusAI/finbert) via Transformers|
| NLP Preprocessing      | [`spaCy`](https://spacy.io/) (v3+)                                   |
| Data Manipulation      | `pandas`, `NumPy`                                                    |
| Statistical Tests      | `statsmodels` (Granger Causality, OLS)                               |
| Visualization          | `Plotly`, `Seaborn`                                                  |
| Dashboard (Optional)   | `Streamlit`                                                          |
| Notebooks              | Jupyter with markdown commentary                                     |

---



---

## 📂 Folder Structure
news-sentiment-stock-impact/

├── config/               -> API keys, constants

├── data/                 -> Raw and cleaned data files (CSV, JSON)

├── docs/                 -> Project planning docs, diagrams

├── notebooks/            -> Jupyter Notebooks (week-wise)

├── outputs/              -> Plots, charts, results

├── scripts/              -> Python modules for scraping, sentiment, etc.

├── tests/                ->  Unit tests

├── .env.example          -> Template for environment variables

├── README.md             -> Project overview and instructions

└── requirements.txt      -> Python dependencies



---

👤 Author

Built with 🧠 + 💻 by Shivangini Rathore


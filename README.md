# sentiment-trading-tesla
A fun NLP-driven trading strategy using Tesla sentiment data and yfinance stock prices

# 💸 Mood & Money: Tesla Sentiment-Aware Trading Strategy

This project explores a fun and simple trading strategy using **fake Tesla news headlines** and **VADER sentiment analysis** to simulate how market mood might affect trading.

---

## 🧠 What It Does

- Uses `vaderSentiment` NLP tool to score the mood of Tesla-related headlines
- Simulates buying TSLA when sentiment is positive, selling when it's negative
- Compares this strategy to a basic Buy & Hold
- Visualizes portfolio performance over time

---

## 📊 Tools Used

- `pandas` for data manipulation
- `yfinance` to download TSLA historical stock data
- `vaderSentiment` for natural language sentiment scoring
- `matplotlib` for visualization

---

## 🚀 Results

📈 The strategy dynamically adjusts based on mood — and it performs comparably (or better) than buy-and-hold depending on the mood data. Try using **real headlines** for even better results!

---

## 🧪 Try It Yourself

Clone this repo and open the notebook in Jupyter:

```bash
git clone https://github.com/YOUR_USERNAME/sentiment-trading-tesla.git

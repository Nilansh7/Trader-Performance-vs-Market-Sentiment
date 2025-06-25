# Trader-Performance-vs-Market-Sentiment
A data analysis project that investigates how Bitcoin market sentiment (Fear &amp; Greed Index) impacts trader performance using real historical trade data from Hyperliquid. Includes sentiment-wise analysis of trade volume, win rate, average profits, and behavioral patterns under different market emotions.


# Trader Performance vs Market Sentiment

This project explores the relationship between trader performance and market sentiment using two datasets: the Bitcoin Fear & Greed Index and historical trade data from Hyperliquid. The goal is to uncover hidden patterns and generate insights that can support smarter trading strategies.

---

## 📁 Datasets Used

### 1. Bitcoin Fear & Greed Index
- **Columns**: `date`, `value`, `classification`
- Sentiment classifications include: `Extreme Fear`, `Fear`, `Neutral`, `Greed`, `Extreme Greed`.

### 2. Historical Trader Data (from Hyperliquid)
- **Columns include**: `Account`, `Coin`, `Execution Price`, `Size USD`, `Side`, `Timestamp`, `Closed PnL`, and more.
- Covers a wide range of trades across different assets and timeframes.

---

## 🎯 Objective

- Analyze how market sentiment impacts trader behavior and profitability.
- Identify trading volume patterns under different sentiment conditions.
- Visualize how winning trades and profits vary across fear/greed cycles.

---

## 🔍 Key Insights

- **Trade Frequency**: Most trades occurred during periods of **Fear** and **Extreme Greed**.
- **Average Profitability**: Higher average profit was observed in certain sentiment types.
- **Win Rate**: Traders had a higher percentage of profitable trades in `Fear` than in `Extreme Greed`.
- **Volume Analysis**: Significant trading volume was noticed during `Fear`, indicating cautious but active market participation.

---

## 📊 Visualizations

- Bar charts showing number of trades by sentiment.
- Average and median `Closed PnL` per sentiment.
- Win rate (%) by sentiment.
- USD traded volume distribution.
- Box plots showing profit/loss distribution under each sentiment.

---

## 🧰 Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Trader-Performance-vs-Market-Sentiment.git
   cd Trader-Performance-vs-Market-Sentiment

# trader-behavior-sentiment-analysis

# 🧠 Trader Behavior Insights from Market Sentiment

### **Analyzing Hyperliquid Trader Performance vs Bitcoin Fear & Greed Index**

This project explores how **market sentiment influences trader behavior and performance**.
Using **historical Hyperliquid trading data** and the **Bitcoin Fear & Greed Index**, the analysis uncovers patterns in:

* Profitability
* Win rate
* Leverage usage
* Trading volume
* Buy/Sell biases

This project is part of a **data science hiring assignment** for the *Trader Behavior Insights* role.

---

## 🚀 Project Objectives

1. **Clean & preprocess** raw sentiment and trading data.
2. **Aggregate trades daily** and engineer performance features.
3. **Merge datasets** to align trader metrics with daily sentiment values.
4. **Analyze relationships** between:

   * Fear & Greed Index
   * Daily PnL
   * Win rate
   * Trading frequency
   * Leverage
5. **Generate insights** that can contribute to smarter algorithmic trading strategies.
6. Deliver a **1–2 page PDF report** and a **clean reproducible notebook**.

---

## 📂 Repository Structure

```
trader-behavior-sentiment-analysis/
│
├── data/
│   └── merged_trade_sentiment_daily.csv
│
├── notebooks/
│   └── trader_sentiment_analysis_notebook.ipynb
│
├── reports/
│   └── trader_sentiment_report.pdf
│
├── images/
│   ├── plot_fear_vs_pnl.png
│   ├── plot_fear_vs_winrate.png
│   └── plot_timeseries_fear_pnl.png
│
├── README.md
└── requirements.txt
```

> **Note:** Raw datasets are not included due to size & confidentiality. Only the cleaned merged dataset is provided.

---

## 📊 Key Insights (Summary)

### 📌 1. Sentiment & PnL

We find initial correlation between **FearGreed index values** and **daily PnL**.
Extreme fear often coincides with **higher volatility**, influencing trader performance.

### 📌 2. Win-rate Behavior

Win rate shows varying behavior with sentiment shifts — suggesting different trader reactions in fear-dominated markets.

### 📌 3. Trading Volume & Activity

Number of trades and notional exposure change with market sentiment, indicating behavioral shifts in risk appetite.

### 📌 4. Leverage Patterns

Average leverage varies by sentiment regime, revealing how traders adjust risk during fearful vs greedy markets.

---

## 🛠️ How to Run the Notebook

### **1. Install dependencies**

```
pip install -r requirements.txt
```

### **2. Open the notebook**

```
jupyter notebook notebooks/trader_sentiment_analysis_notebook.ipynb
```

### **3. Run all cells**

This will:

* Load the merged dataset
* Generate summary statistics
* Visualize sentiment vs performance patterns
* Allow you to extend the analysis

---

## 📑 Deliverables

This repo includes:

✔ **1–2 page PDF report** with executive summary & visuals
✔ **Reproducible Jupyter notebook**
✔ **Merged daily dataset**
✔ **Plots for presentation**
✔ **README (this file)**

---

## 📈 Future Improvements

These enhancements can deepen the analysis:

* **Segment traders** by profitability or trade frequency
* **Rolling-window features** (7d/14d sentiment trends)
* **Predictive modeling**:

  * Logistic regression for profitable day prediction
  * RandomForest for nonlinear behavior
* **Regime detection** (fear streaks vs greed streaks)
* **Symbol-level analysis** for multi-asset traders

---

## 🤝 About This Assignment

This project was completed as part of the hiring process for:

**Junior Data Scientist – Trader Behavior Insights**

If you're reviewing this repository, thank you for the opportunity.

---


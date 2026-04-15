# 📊 Behavioral & Quantitative Analysis of Crypto Traders under Market Sentiment

## 🚀 Overview
This project explores the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader performance** using real-world trading data.

The objective is to uncover **behavioral patterns, profitability trends, and strategic insights** that can help design more effective trading strategies.

---

## 🎯 Key Findings

- 📈 **Fear sentiment delivers the highest profitability (~750 average profit)**
- 🚀 A **Fear-based contrarian strategy generates ~200K cumulative profit**
- ⚠️ **Neutral markets exhibit high volatility and overtrading behavior**
- 📉 Weak correlation (**~0.18**) between trade size and profitability
- 🧠 Traders increase activity during Greed/Neutral without consistent returns

---

## 📂 Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- Fear / Greed classification  
- Daily sentiment values  

### 2. Trader Execution Data (Hyperliquid)
- Account-level trade data  
- Trade size, direction (Long/Short)  
- Execution price, timestamps  
- Profit & Loss (PnL)  

---

## ⚙️ Tech Stack

- **Python**
- **Pandas, NumPy** – Data processing  
- **Matplotlib, Seaborn, Plotly** – Visualization  
- **Scikit-learn** – Clustering (KMeans)  
- **Streamlit** – Interactive dashboard  

---

## 📊 Analysis Workflow

- Data cleaning & preprocessing  
- Feature engineering (profitability, trade size, direction)  
- Sentiment-based performance analysis  
- Statistical testing (t-test)  
- Trader clustering (behavioral segmentation)  
- Strategy backtesting (Fear vs Greed)  

---

## 📈 Key Insights

### 🔹 Profitability
- Traders perform significantly better during **Fear periods**
- Greed sentiment does not translate into higher returns  

### 🔹 Behavioral Patterns
- **Overtrading observed in Neutral markets**
- Traders increase position sizes without proportional gains  

### 🔹 Strategy Edge
- A **contrarian strategy (trading during Fear)**:
  - Outperforms all other approaches  
  - Provides better risk-adjusted returns  

---

## 🧪 Strategy Backtesting

| Strategy     | Performance        |
|--------------|-------------------|
| Fear-based   | 🚀 High returns   |
| Greed-based  | ⚠️ Flat / weak    |

---

## 📊 Interactive Dashboard

Run the Streamlit dashboard:

    streamlit run app.py

### Features

- 📌 **Key metrics** (Total Profit, Avg Profit, Win Rate)  
- 📊 **Sentiment-based filtering**  
- 📉 **Interactive visualizations (Plotly)**  
- 🚀 **Strategy comparison (Fear vs Greed)**  

---

## 📦 Project Structure

    bitcoin-trader-analysis/
    │── data/
    │── notebook.ipynb
    │── app.py
    │── report.pdf
    │── requirements.txt
    │── README.md
    │── .gitignore

---

## ▶️ How to Run

    git clone <your-repo-link>
    cd bitcoin-trader-analysis

    python -m venv venv
    venv\Scripts\activate

    pip install -r requirements.txt

    streamlit run app.py

---

## 🎯 Conclusion

Market sentiment plays a critical role in shaping trader behavior and performance.

A **Fear-based contrarian strategy provides a clear edge**, while Neutral and Greed regimes introduce inefficiencies and increased risk.

---

## 👤 Author

**Ronak Ghosh**

---

## 📌 Note

This project is for **educational and research purposes only** and does not constitute financial advice.
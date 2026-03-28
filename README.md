#  Trader Behavior Analysis using Market Sentiment

## 1. Objective

Analyze how market sentiment (Fear vs Greed) impacts trader behavior and performance on Hyperliquid. The objective is to uncover behavioral patterns and derive actionable trading strategies.

---

## 2. Setup & How to Run

### 🔹 Requirements

* Python 3.x
* Jupyter Notebook

### 🔹 Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 🔹 Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/trader-behavior-analysis.git
cd trader-behavior-analysis
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open and run:

```text
Trader_Behavior_Analysis.ipynb
```

---

## 3. Output (Charts & Tables)

The notebook generates:

* 📈 Average PnL comparison (Fear vs Greed)
* 📊 Trade frequency analysis
* 📉 Win rate comparison
* 📦 Trader-level metrics (PnL, trade size, activity)

---

## 4. Methodology

* Loaded and cleaned sentiment and trading datasets
* Handled missing values and duplicates
* Converted timestamps and standardized date formats
* Resolved dataset mismatch using weekday-based sentiment mapping
* Engineered key features:

  * Daily PnL per trader
  * Win rate
  * Trade frequency
  * Average trade size
* Performed exploratory data analysis with visualizations

---

## 5. Key Insights

1. **Performance Difference**

   * Traders tend to achieve slightly higher average PnL during Fear conditions

2. **Trading Activity**

   * Trade frequency remains relatively consistent across both market sentiments

3. **Risk Behavior**

   * Win rate declines during Greed, indicating increased risk-taking and overconfidence

---

## 6. Strategy Recommendations

1. **During Fear Markets**

   * Use controlled/moderate leverage
   * Focus on disciplined execution

2. **During Greed Markets**

   * Avoid overtrading
   * Apply strict stop-loss rules

3. **General Strategy**

   * Reduce position size during high volatility
   * Maintain consistent risk management practices

---

## 7. Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---



---

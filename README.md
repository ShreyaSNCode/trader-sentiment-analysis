# Trader Performance vs Market Sentiment Analysis

## 📌 Objective
Analyze how market sentiment (Fear/Greed) influences trader behavior, risk-taking, and profitability.

---

## 📂 Datasets
- Historical Trader Data (Hyperliquid)
- Bitcoin Market Sentiment (Fear/Greed Index)

---

## ⚙️ Methodology

1. Cleaned and standardized datasets  
2. Converted timestamps and aligned data at daily level  
3. Merged datasets on date  
4. Engineered features:
   - Profitability (PnL)
   - Trade size (risk proxy)
   - Win rate
5. Performed behavioral and performance analysis  
6. Built a simple predictive model (Random Forest)

---

## 📊 Key Insights

- Traders take **larger positions during Fear**, but profitability is lower → inefficient risk-taking  
- **Extreme Greed shows highest profitability**, indicating strong market conditions  
- Trade size has a **greater impact on profitability than sentiment alone**  

---

## 🚀 Strategy Recommendations

- Reduce position sizes during Fear periods to avoid emotional trading  
- Increase participation during Extreme Greed phases  
- Focus on disciplined execution rather than increasing exposure  

---

## 🤖 Bonus: Predictive Model

- Built a Random Forest model to predict trade profitability  
- Achieved ~63% accuracy after removing data leakage  
- Found that **trade size dominates prediction over sentiment**

---

## ▶️ How to Run

1. Download notebook  
2. Install requirements:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

# Portfolio-Risk-Analysis-VaR-Calculation
Simulated portfolio losses using Monte Carlo and Historical VaR methods on historical stock data. Evaluated portfolio risk under different scenarios and stress tests, providing actionable insights for risk management.

This project demonstrates **portfolio risk assessment** using historical stock prices. We calculate **daily returns**, perform **Value-at-Risk (VaR)** analysis using both **Historical** and **Monte Carlo simulation** methods, and visualize the portfolio risk distribution.

---

## Features

- Processed **historical stock price data** for multiple stocks.
- Calculated **daily portfolio returns** using customizable weights.
- Computed **95% Historical VaR**.
- Computed **95% Monte Carlo VaR** for simulated portfolio returns.
- Plotted **portfolio returns distribution** with VaR thresholds.

---

## Dataset

- **Source:** [Kaggle – Stock Time Series 2005-2017](https://www.kaggle.com/datasets/szrlee/stock-time-series-20050101-to-20171231)
- **Columns:** `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Name` (ticker added during preprocessing)
- Combined multiple CSVs into a single DataFrame for analysis.
- Sampled **10-stock portfolios** for efficient computation in Colab.

---

## Technologies & Tools

- Python (pandas, numpy, matplotlib, seaborn)
- Portfolio risk metrics (VaR, Monte Carlo simulation)
- Data preprocessing and visualization

---

## How to Run

1. Upload the ZIP dataset to Colab or Drive.
2. Run the extraction and combination script to merge all stock CSVs.
3. Execute the notebook step by step:
   - Preprocess & pivot data
   - Calculate daily returns
   - Compute portfolio returns
   - Historical VaR & Monte Carlo VaR
   - Visualize portfolio risk
4. Adjust portfolio weights or number of stocks for customized analysis.

---

## Sample Output

- **Portfolio Returns Distribution**  
- **Historical VaR 95%**  
- **Monte Carlo VaR 95%**  

*Visualizations show risk and potential losses under normal market conditions and simulated scenarios.*

---

## Notes

- Sampling smaller portfolios (~10 stocks) avoids Colab memory issues.  
- Aggregation (`mean`) is applied to handle duplicate entries in historical data.  
- Weights are adjustable to simulate different portfolio strategies.

---

## Author

**SAGAR METI** 
Data Science Enthusiast | Madras School Of Economics

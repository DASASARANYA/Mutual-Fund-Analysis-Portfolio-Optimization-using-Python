# Mutual-Fund-Analysis-Portfolio-Optimization-using-Python

This project performs end-to-end mutual fund analysis — from data cleaning to EDA, performance metrics, and portfolio creation.
It uses historical NAV data to evaluate risk–return profiles and builds Conservative, Balanced, and Aggressive portfolios using a simple weight-based model.

This project notebook:
📄 Mutual_Fund_Plan_with_Python.ipynb
🛠 Built using: Python, Pandas, NumPy, Matplotlib, Seaborn

📌 Project Objectives

Clean, preprocess, and transform mutual fund NAV data

Generate monthly returns from daily NAV

Perform Exploratory Data Analysis (EDA)

Evaluate funds using:

Annual Return

Volatility (Risk)

Sharpe Ratio

Build 3 types of portfolios:

Conservative

Balanced

Aggressive

🧹 1. Data Cleaning Steps

Convert Date column → datetime

Remove duplicates

Forward & backward fill missing NAV values

Sort data by date

Resample from Daily to Monthly NAV

Calculate Monthly % Returns

📊 2. Exploratory Data Analysis (EDA)

The notebook includes visualizations like:

Monthly return distribution

Outlier boxplot

Correlation heatmap (to check diversification)

Growth of ₹1 invested over time

These graphs provide clarity on volatility, fund behavior, and diversification benefits.

📈 3. Performance Metrics

For each mutual fund:

Annual Return = mean monthly return × 12

Annual Volatility = monthly std × √12

Sharpe Ratio (Risk-adjusted return)

A risk-free rate of 4% is assumed for Sharpe calculations.

💼 4. Portfolio Models

Three portfolio types were constructed:

Conservative Portfolio

Focus: Stability

Higher allocation to lower-volatility funds

Balanced Portfolio

Focus: Best risk-return balance

Performed best in analysis (highest Sharpe)

Aggressive Portfolio

Focus: Maximum returns

Higher allocation to historically high-growth funds

Each portfolio includes:

Weight distribution

Annual expected return

Portfolio volatility

Sharpe Ratio

📉 5. Portfolio Comparison Visuals

The notebook includes:

Return vs Risk (Bar Chart)

Sharpe Ratio comparison

Pie charts for allocations

These help visually justify the recommended portfolio.

🏆 6. Final Recommendation

Based on Sharpe ratio and overall risk-return efficiency:

✅ Balanced Portfolio is Recommended

It offers:

High risk-adjusted return

Moderate volatility

Strong diversification

🤝 Author

Dasa Saranya
Data Analytics | Python | Visualization | Portfolio Modelling

# 📈 Building a Portfolio Using the Efficient Frontier (Python & Jupyter)

This project demonstrates how to construct an optimized investment portfolio using **Modern Portfolio Theory (MPT)** and the **Efficient Frontier** — implemented entirely in a Jupyter Notebook.  

It walks through the complete workflow of portfolio analysis: **data collection**, **data processing**, **Monte Carlo simulation**, and **data visualization**, all in Python.

---

## 🧩 Project Overview

The Efficient Frontier is a cornerstone concept in modern portfolio theory.  
It represents the set of optimal portfolios that offer the **highest expected return for a defined level of risk** (or the lowest risk for a given level of return).

This notebook illustrates the step-by-step process of building such a portfolio using historical stock data.

---

## 🗂️ Contents

### 1. Data Gathering
- Fetch historical stock price data using `yfinance` or similar APIs.
- Select a group of assets (e.g., AAPL, MSFT, GOOG, AMZN, etc.).
- Clean and align the data for analysis.

### 2. Data Processing
- Calculate **daily returns** and **covariance matrix** of selected assets.
- Compute pairwise **correlation coefficients**.
- Summarize risk and return characteristics for each stock.

### 3. Monte Carlo Simulation
- Generate thousands of random portfolios by varying asset weights.
- Calculate **expected returns**, **volatility**, and **Sharpe ratios** for each portfolio.
- Identify the **optimal portfolio** based on the highest Sharpe ratio.

### 4. Data Visualization
- Plot all simulated portfolios on the risk-return plane.
- Highlight the **Efficient Frontier** curve.
- Mark the **maximum Sharpe ratio portfolio** and **minimum volatility portfolio**.
- Visualize weight allocations for optimal portfolios.

---

## 🧠 Key Concepts Covered
- Efficient Frontier Theory  
- Portfolio Optimization  
- Monte Carlo Simulation  
- Covariance & Correlation Analysis  
- Sharpe Ratio Calculation  
- Financial Data Visualization  

---

## 💻 Technologies Used
- **Python 3**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **yfinance**

---

## 📊 Example Visualization

*(Optional — Add an image once available)*  
```markdown
![Efficient Frontier Example](images/efficient_frontier.png)

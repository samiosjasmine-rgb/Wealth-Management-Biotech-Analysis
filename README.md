Wealth Management Project: Healthcare and Biotech ETF Analysis vs S&P 500
Overview

This project analyses the performance of the iShares Biotechnology ETF (IBB), the Health Care Select Sector SPDR Fund (XLV), and the SPDR S&P 500 ETF Trust (SPY) between 2020 and 2024. The objective is to evaluate sector-specific opportunities in healthcare and biotechnology compared with the broader market. This mirrors the type of analysis wealth managers perform when advising clients on portfolio allocation.

Methodology

Data source: Yahoo Finance

Tools: Python (pandas, NumPy, matplotlib, yfinance)

Metrics analysed:

Daily and cumulative returns

Normalized price comparisons

Annualised return, volatility, and Sharpe ratio

Risk vs return analysis

Maximum drawdown and rolling volatility

The analysis was implemented in Python, and outputs include both numerical summary metrics and visualisations.

Results

Key findings from the analysis:

Biotechnology (IBB): Higher long-term returns but significantly greater volatility and deeper drawdowns. Represents a high-risk, high-reward profile.

Healthcare (XLV): Lower but more stable returns compared to biotech. Acts as a defensive sector with reduced volatility.

S&P 500 (SPY): Provides a diversified benchmark with balanced risk and return, smoothing volatility compared to sector-specific funds.

Outputs

The repository includes:

Python script: wm_healthcare_biotech_clean.py (clean version)

Jupyter Notebook (optional): A Colab-compatible notebook version

Outputs folder: Contains charts and summary CSV file

Normalized Price Comparison (01_normalized_price.png)

Cumulative Returns (02_cumulative_return.png)

Rolling Volatility (03_rolling_volatility.png)

Histograms of Daily Returns (04_histogram_XLV.png, 04_histogram_IBB.png, 04_histogram_SPY.png)

Risk vs Return Scatterplot (05_risk_vs_return.png)

Summary Metrics (summary_metrics.csv)

Insights

This project demonstrates how Python can be applied to replicate the type of sector analysis used in wealth management. By comparing biotech, healthcare, and broad market exposure, the analysis highlights the trade-offs clients face between risk and reward, and shows how data-driven insights can inform investment decisions.

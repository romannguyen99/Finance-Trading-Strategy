# Quantitative Investment Strategy: K-Means Clustering for Momentum Investing
## 1. Introduction
This project demonstrates a quantitative investment strategy that uses K-Means clustering and modern portfolio optimization techniques to identify and invest in high-momentum stocks. The core idea is to group stocks based on their financial and technical characteristics in order to construct a risk-adjusted portfolio.
## 2. Background
Traditional investment strategies often rely on fundamental analysis or static technical indicators. However, financial markets are dynamic and non-stationary, changing the market behavior over time. This strategy addresses this challenge by:

1.  **Dynamic Stock Grouping**: Using K-Means clustering, stocks are categorized into distinct behavioral styles each month, adapting to evolving market regimes.
2.  **Momentum Capture**: The strategy specifically targets stocks within clusters identified as having strong positive momentum, based on a comprehensive set of features including returns, volatility, and Fama-French factor exposures.
3.  **Risk-Adjusted Optimization**: The portfolio is optimized to maximize the Sharpe Ratio, ensuring that returns are achieved with an acceptable level of risk.
4.  **Monthly Rebalancing**: The entire process is repeated monthly, allowing the portfolio to continuously adapt to new market information and maintain exposure to the most promising momentum stocks.

**The goal is to illustrate how a systematic, data-driven approach can potentially generate superior risk-adjusted returns in the stock market.**

QuantFinance-Trading

This project, developed by Mostafa Ismail, focuses on Quantitative Trading, building a trading strategy by generating alpha and optimizing a portfolio. It leverages various financial strategies and backtesting techniques to deliver a comprehensive approach to quantitative finance.

The project is divided into five sections:

    Trading with Momentum Strategy:
        A trading signal was generated based on the Momentum Indicator.
        The strategy was tested to evaluate its profitability potential.

    Break-Out Strategy:
        Implemented a Break-Out Strategy, where stocks break out of a range due to significant news or market pressure from large investors.

    Smart-Beta Portfolio Optimization:
        Built a portfolio using Quadratic Programming to optimize the asset weights.
        The portfolio was benchmarked by calculating a tracking error against a chosen index.

    Multi-Factor Model using PCA:
        Developed a statistical risk model using Principal Component Analysis (PCA).
        Factors were created and evaluated using factor-weighted returns, quantile analysis, Sharpe ratio, and turnover analysis.
        The portfolio was optimized using the risk model with various optimization formulations.

    Backtesting:
        Developed a robust backtester using Barra data to simulate portfolio optimization, incorporating transaction costs.
        The backtester was built with computational efficiency in mind to allow for fast and realistic backtesting.
        Performance attribution was performed to identify the key drivers of the portfolio's profit-and-loss (PnL).

Dataset

This project was originally inspired by a curriculum project, with datasets provided by partners such as Quotemedia, Barra, and Sharadar. For proprietary reasons, external users may need to source their own financial data to replicate the results.

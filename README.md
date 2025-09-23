# Projects from EC 432: Data Science for Financial Time Series
This repository showcases three out of the seven homework projects that I completed for EC 432, which I took in Winter 2025 at UCLA. All projects use stock market data from the yfinance package.

## 📈 Project 4: Risk Modeling of Microsoft Stock Using Value at Risk and Expected Shortfall
- Analyzed 12 years of Microsoft (MSFT) daily stock data (2012–2024) by computing log returns and applying risk estimation techniques
- Built nonparametric, normal, and t-distribution VaR and ES models at the 1% level, highlighting the impact of distributional assumptions on tail risk
- Implemented Monte Carlo bootstrapping with 1,000 replications to construct 95% confidence intervals for nonparametric VaR and ES estimates
- Applied Extreme Value Theory by estimating the left-tail index and extrapolating 0.1% VaR and ES to assess extreme downside exposure

## 📈 Project 7: Forecasting Financial Returns with ARMA Models
- Analyzed daily S&P 500 returns (2010–2024), estimated mean/variance, and compared price movements against a simulated random walk
- Tested whether a computer-generated random walk can predict the stock market via regression analysis
- Modeled Apple (AAPL) daily returns using AR, MA, and ARMA processes with AIC model selection
- Conducted diagnostic checks (ACF, Ljung-Box test, residual analysis) to assess whether returns exhibit white noise characteristics
- Implemented a rolling-window forecast evaluation (AR(1), MA(1), ARMA(1,1)) to compare out-of-sample predictive performance

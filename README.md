# Projects from EC 432: Data Science for Financial Time Series
This repository showcases two out of the seven homework projects that I completed for EC 432, which I took in Winter 2025 at UCLA.

## Project 2: Statistical Analysis of Microsoft Financial Returns
- Retrieved and processed Microsoft stock price data from Yahoo Finance using Python
- Estimated empirical distributions of daily log returns, utilizing ECDF and kernel density estimation
- Performed statistical tests to validate normality assumptions, including Jarque-Bera and skewness/kurtosis tests
- Implemented bootstrapping to estimate confidence intervals for Student-t distribution parameters
- Constructed visualizations of the data, such as probability density plots and quantile-quantile plots

## Project 7: Forecasting Financial Returns with ARMA Models
- Analyzed daily S&P 500 returns (2010–2024), estimated mean/variance, and compared actual price movements against a simulated random walk
- Tested whether a computer-generated random walk can predict the stock market via regression analysis
- Modeled Apple (AAPL) daily returns using AR, MA, and ARMA processes with AIC model selection
- Conducted diagnostic checks (ACF, Ljung-Box test, residual analysis) to assess whether returns exhibit white noise characteristics
- Implemented a rolling-window forecast evaluation (AR(1), MA(1), ARMA(1,1)) to compare out-of-sample predictive performance

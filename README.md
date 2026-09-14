# tail-risk-var-analysis
Comparing tail-risk estimation across asset classes using Gaussian, Historical, and Cornish-Fisher Value-at-Risk.

## Research Question
How does tail-risk estimation differ across Bitcoin, Gold, and the S&P 500 when Value-at-Risk is estimated using a normal distribution versus the Cornish-Fisher expansion?
The aim of this project is to investigate whether accounting for skewness and kurtosis materially changes estimated tail risk, and to identify which asset class is most affected by this adjustment.

## Asset Selection
The analysis compares three different asset classes:

- **Bitcoin** represents cryptocurrency and is included because of its relatively high volatility and potential for extreme price movements.
- **Gold** represents a commodity and provides a contrasting asset with different risk characteristics.
- **S&P 500** represents the broader equity market and provides a benchmark for traditional market risk.

Using these three assets allows the analysis to examine whether the difference between Gaussian and Cornish-Fisher VaR is similar across markets or is more significant for assets with different return distributions.
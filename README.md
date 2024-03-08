# DHML
Master Thesis: Machine Learning for Direction Prediction in Equity Returns

Based on: L. Del Viva, C. Sala, and A. B. Souza. Directional Information in Equity Returns.
SSRN Electronic Journal, 2023. ISSN 1556-5068. doi: 10.2139/ssrn.4575793. URL
https://www.ssrn.com/abstract=4575793

## Abstract
Del Viva et al. (2023) introduced a Directional High Minus Low strategy that
buys stocks deemed most likely to have positive returns and sells stocks with the lowest
probability of positive returns based on Pooled OLS. Such a D-HML strategy generates
about 1% alpha over established asset pricing models. In this paper, we build on Del Viva
et al. (2023) by including additional predictors and employing more advanced machine
learning (ML) algorithms (Ridge and Lasso regression, Decision Trees, and Random
Forests) for direction prediction. We show that simply applying ML models on the same
data does not bring any major benefits to the D-HML strategy. However, our results
show that the performance of the D-HML strategy can be further improved by employing
ML models on the original dataset enhanced by additional market and financial ratios.


## Contents:
- DataManipulation_DailyReturns: cleaning the daily data, induction of day and week-based variables.
- DataManipulation_Monthly: Creation of Base, Market, and Financials datasets used to train models.
- Results__ notebooks: Contain evaluation of predictive performance of ML models and backtesting of the resulting portfolios.
Folders:
- BaseData__ folders: contain cross-validation and predictions of ML models trained on the Base dataset. Contains stock sorting and portfolio formation.
- MarketData folder: contains cross-validation and predictions of ML models trained on the Market dataset. Contains stock sorting and portfolio formation.
- FinancialData folder: contains cross-validation and predictions of ML models trained on the Financial dataset. Contains stock sorting and portfolio formation.

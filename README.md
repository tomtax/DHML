# DHML
Master Thesis: Machine Learning for Direction Prediction in Equity Returns

Based on: L. Del Viva, C. Sala, and A. B. Souza. Directional Information in Equity Returns.
SSRN Electronic Journal, 2023. ISSN 1556-5068. doi: 10.2139/ssrn.4575793. URL
https://www.ssrn.com/abstract=4575793


## Contents:
- DataManipulation_DailyReturns: cleaning the daily data, induction of day and week-based variables.
- DataManipulation_Monthly: Creation of Base, Market, and Financials datasets used to train models.
- Results__ notebooks: Contain evaluation of predictive performance of ML models and backtesting of the resulting portfolios.
Folders:
- BaseData__ folders: contain cross-validation and predictions of ML models trained on the Base dataset. Contains stock sorting and portfolio formation.
- MarketData folder: contains cross-validation and predictions of ML models trained on the Market dataset. Contains stock sorting and portfolio formation.
- FinancialData folder: contains cross-validation and predictions of ML models trained on the Financial dataset. Contains stock sorting and portfolio formation.

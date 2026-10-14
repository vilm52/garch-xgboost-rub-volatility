# garch-xgboost-rub-volatility
**GARCH-XGBoost for RUB Exchange Rate Volatility Forecasting**

**Project Description**

This repository contains the Python code and source data used in a study of exchange rate volatility forecasting for the Russian ruble (RUB) against the US dollar (USD) and the euro (EUR).

The study investigates a hybrid forecasting approach combining the GARCH(1,1) model and XGBoost. The GARCH model captures conditional heteroskedasticity, while XGBoost models nonlinear patterns in the residuals of the statistical model.

**Methods**

GARCH(1,1): statistical modeling of conditional volatility.

XGBoost: machine learning model for capturing nonlinear dependencies.

Hybrid GARCH-XGBoost: combination of statistical and machine learning forecasts.

Forecast evaluation: comparison of forecasting performance using appropriate error metrics.

**Repository Contents**

*.py — Python code for data processing, model estimation, forecasting, and evaluation.

XML_daily.xml — source exchange rate data, if used in the analysis.

XML_dynamic.xml — source exchange rate data, if used in the analysis.

XML_dynamic_EUR.xml — source exchange rate data, if used in the analysis.

**Requirements**

Python 3 and the following libraries may be required, depending on the code:

pandas

numpy

matplotlib

scikit-learn

statsmodels

xgboost

**Reproducibility**

To reproduce the results, install the required dependencies, review the data paths in the Python script, and run the analysis.

The exact data files used, date range, model parameters, and evaluation metrics should be specified in the research paper or in the corresponding code.

**Citation**

If you use this code in academic work, please cite the corresponding research paper once its bibliographic details are available.

**Data Availability**

The source data files are included for research reproducibility, subject to the applicable terms of use and redistribution permissions.

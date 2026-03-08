# Credit Risk Modeling Framework (PD-LGD-EAD)

## Objective

The objective of this project is to build an end-to-end credit risk modeling framework to estimate key risk parameters including Probability of Default (PD), Loss Given Default (LGD), and Exposure at Default (EAD).

The project simulates a regulatory-style credit risk modeling pipeline similar to those used by financial institutions for risk management and regulatory reporting (e.g., CECL, IFRS9, and CCAR).

The framework includes model development, validation metrics (ROC-AUC, KS statistic, WOE-IV analysis, PSI stability testing), decile analysis, and macroeconomic stress testing to estimate portfolio expected loss under different economic scenarios.

This project implements an end-to-end credit risk modeling pipeline using Python.

## Features

- Probability of Default (PD) model
- Loss Given Default (LGD)
- Exposure at Default (EAD)
- Expected Loss calculation
- KS statistic
- WOE & Information Value
- Population Stability Index (PSI)
- Stress testing
- Decile and Lift analysis

## Tech Stack

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib  
ScorecardPy  
yfinance


## MODEL PERFORMANCE SUMMARY
ROC AUC Score (PD Model): 0.726
KS Statistic: 0.339
Population Stability Index (PSI): 0.000
Average Expected Loss: 734.37
## NVDA Stock Price Direction Prediction using Machine Learning 

## Project Overview
This project predicts whether NVIDIA (NVDA) stock will go UP or DOWN the next trading day using a Random Forest classifier.

## Dataset
- Source : Yahoo Finance
- Stock : NVDA (NVIDIA Corportation)
- Period : January 2020 to present
- Size : ~1,500 daily records

## Features Used
- Ratio10: Short-term price momentum (Close / 10-day MA)
- Ratio50: Long-term trend indicator (Close / 50-day MA)
- Volatility: 10-day rolling standard deviation of resturns
- RSI: Relative Strength Index

## Model
- Algorithm: Random Forest Classifier
- Tree : 100
- Min samples split: 50
- Criterion: Gini impurity

## Results
|model              |Accuracy|F1 Score|AUC|
|Logistic Regression|54.55% | 70.59%| 0.512|
|Random Forest      |51.95% |62.05% |0.519 |

## Libraries Used 
- Python
- scikit - learn
- pandas
- numpy
- matplotlib
- yfinance


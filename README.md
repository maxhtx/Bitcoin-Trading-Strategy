# Bitcoin Trading Strategy with Machine Learning Model

## Overview

This project implements a trading strategy based on a machine learning model's predictions for Bitcoin prices. The strategy buys Bitcoin when the model predicts a return above a certain threshold and sells it when certain conditions are met (e.g., reaching a profit target or stop-loss level, or after a certain time period).

Additionaly, I have analyzed several different take-profit and stop-loss levels that could be useful when developing a 'target' variable

## Features

- Uses machine learning model predictions to make trading decisions. (XGBoost Classifier)
- Buys Bitcoin when the predicted future return exceeds a threshold.
- Sells Bitcoin based on profit targets, stop-loss levels, or after a specified holding period.
- Calculates returns and performance metrics for different threshold, profit, and stop-loss levels.

## Data

- The initial Raw data is Max_Data.csv. This will get you started
- Throughout the code there are various checkpoints where i have saved data, in case there are computational issues.
- You can download these checkpoint datasets from this repository

## Requirements

- Python 3.x
- Pandas
- NumPy
- Sklearn
- XGBoost

Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

Author
Max Helman

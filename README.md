# Currency Exchange Rate Prediction

![Currency Exchange](https://img.freepik.com/premium-vector/currency-exchange-money-dollar-euro-golden-round-currency-coins_172107-1946.jpg?w=1380)

## Overview

This repository contains a predictive model for forecasting the exchange rate of the Indian currency (INR) against the US dollar (USD). The historical exchange rate data was retrieved from [Investing.com](https://www.investing.com/currencies/usd-inr-historical-data).

You can also find a pre-trained model in `.pkl` format that you can download and use for your own predictions.

## Getting Started

To use the pre-trained model, you'll need to load it using the `joblib` library. Here's an example of how to do it in Python:

```python
import joblib

file_path = 'Model -- Currency Exchange Rate Prediction --.pkl'
loaded_model = joblib.load(file_path)
```
## Usage

To make predictions using the model, you need to provide three input features:

- Opening Price
- High Price
- Low Price

The model will then give you the predicted closing price.

You can also explore the data and see the methods used to build the model in the `main.ipynb` notebook provided in this repository.

## Model Details

The predictive model was built using the DecisionTreeRegressor algorithm, and it achieved a Mean Square Error (MSE) of 0.05 on the test data.

## Requirements

To use this code and the pre-trained model, you should have a good understanding of Python and the following libraries installed:

- `scikit-learn` (sklearn)
- `joblib`
- `pandas`
- `matplotlib`

## Contact

If you have any questions or need further assistance, you can reach out to me via the following channels:

- Telegram: [Mustafa Mohammad](https://t.me/ha12qw)
- Facebook: [Mustafa Mohammad](https://www.facebook.com/profile.php?id=100049592914479)

Feel free to explore the code and use the model for your currency exchange rate predictions.

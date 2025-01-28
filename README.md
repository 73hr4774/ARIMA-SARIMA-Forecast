# Yahoo Stock Price Prediction using ARIMA and SARIMA

This repository contains a Python script that demonstrates the use of ARIMA and SARIMA models for predicting Yahoo stock prices.

## Data

The script uses the `yahoo_stock.csv` file as input, which contains historical Yahoo stock data. This data should include columns for 'Date' and 'Close' prices. Make sure to place this file in the same directory as the script.

## Model Implementation

- The script first loads and preprocesses the data, converting the 'Date' column to datetime objects and setting it as the index.
- It then splits the data into training and testing sets.
- ARIMA and SARIMA models are trained using the training data.
- The models are used to forecast stock prices for the testing period.
- The forecasted prices are compared to the actual prices using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).
- Finally, a plot is generated to visualize the training data, test data, and the forecasts from both models.

## Requirements

To run this script, you'll need to have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- statsmodels
- scikit-learn

You can install these libraries using pip:
## Usage

1.  Clone this repository to your local machine.
2.  Place the `yahoo_stock.csv` file in the repository directory.
3.  Open the script in a Python environment (e.g., Google Colab, Jupyter Notebook).
4.  Execute the script to train the models, generate forecasts, and view the results.

## Results

The script will print the MSE, RMSE, and MAE for both ARIMA and SARIMA models. It will also display a plot showing the forecasts and actual stock prices.

## Contributing

Feel free to contribute to this project by suggesting improvements or adding new features.

## License

This project is licensed under the MIT License.

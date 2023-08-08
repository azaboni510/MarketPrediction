Stock Price Prediction using LSTM
This repository contains code for predicting stock prices using Long Short-Term Memory (LSTM) networks. Specifically, it focuses on predicting the stock price of Tesla, Inc. (TSLA), but it can be easily adapted for other stocks.

Overview
The project uses a deep learning model with multiple LSTM layers to predict the future stock prices of a given company. The code leverages historical stock data, trains the model on it, and then predicts future prices. It also includes a visualization of the actual vs. predicted prices.

Requirements
Python 3.7+
TensorFlow 2.x
yfinance
scikit-learn
matplotlib
pandas
Installation
Clone the repository and navigate to the directory:

bash
Copy code
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
Install the necessary packages using pip:

bash
Copy code
pip install -r requirements.txt
Note: It is recommended to create a virtual environment before installing the packages to avoid conflicts.

Usage
Run the main script:

bash
Copy code
python main.py
The script will download the required data, train the model, and display the prediction plot.

Customization
You can change the company variable in the code to predict the stock price for a different company. Make sure the company symbol is valid and available on Yahoo Finance.

Acknowledgments
This project is inspired by various research in the field of financial forecasting and leverages open-source tools such as TensorFlow, yfinance, and scikit-learn.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Contact
Feel free to reach out if you have any questions or if you want to contribute to the project.

Email: azaboni@sfsu.edu  
GitHub: @azaboni510

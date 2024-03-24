# Educational Stock Picker Using AI Sentiment Analysis

## Overview
This project is an illustrative example of how sentiment analysis can be applied to stock picking. It fetches historical stock data, performs a simulated sentiment analysis, and makes basic recommendations based on the sentiment. The project is designed for educational purposes only and should not be used for real-world trading decisions.

## Installation

### Prerequisites
- Python 3.x installed on your system.
- Familiarity with Python and command-line operations.

### Required Libraries
You will need to install the following Python libraries:
- 'yfinance': To fetch historical stock data from Yahoo Finance.
- 'textblob': For performing basic sentiment analysis.

Install these libraries using the following command:
'''bash
pip install yfinance textblob'''

#### How It Works

Fetching Historical Stock Data
The script utilises the yfinance library to obtain historical market data for a specified stock ticker, like "AAPL" for Apple Inc. This data includes various stock market indicators over a selected period.

Sentiment Analysis (Simulated)
Given the educational nature of this project, sentiment analysis is simulated. In real applications, this would involve analysing text data such as news headlines or financial reports to determine the market's sentiment towards the stock.

Making a Prediction
The script makes a rudimentary recommendation (e.g., "Buy" or "Sell") based on the simulated sentiment analysis. This simplistic approach is for educational purposes and does not encompass the complexities of actual stock trading decisions.

##### Educational Purpose Disclaimer

Please note this project is for educational purposes only and not suitable for real trading. The sentiment analysis is simulated, and the recommendations are based on oversimplified assumptions.

###### Contributing

Contributions to enhance the educational value of this project are welcome. Please ensure any contributions maintain the project's educational intent.

####### License

This project is open-source and available under the MIT License.

######## Acknowledgements

1. yfinance for providing access to Yahoo Finance's historical stock data.
2. textblob for the sentiment analysis framework used in this project.

Thank you for exploring this educational tool. It is designed to offer a basic introduction to the application of AI in stock market analysis.

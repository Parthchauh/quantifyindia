
# QuantifyIndia

QuantifyIndia is a Python package designed to provide easy access to real-time and historical stock market data from the National Stock Exchange of India (NSE). This package leverages the `nsetools` library to fetch stock information and enables users to analyze stock performance over time.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Get Real-time Stock Data](#get-real-time-stock-data)
  - [Get Historical Stock Data](#get-historical-stock-data)
- [Use Cases](#use-cases)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

You can install the QuantifyIndia package using pip. To install the latest version from PyPI, run:

```bash
pip install quantifyindia
```

## Usage

### Get Real-time Stock Data
You can fetch real-time stock data using the `get_realtime_data` function. Here’s an example:

```python
from quantifyindia.nse_data import get_realtime_data

# Fetch real-time data for a stock
stock_data = get_realtime_data('RELIANCE')
print(stock_data)
```

### Get Historical Stock Data
To get historical stock data for a specific period, use the `get_historical_data()` function:

```python
from quantifyindia.nse_data import get_historical_data

# Fetch historical data for a stock
historical_data = get_historical_data('RELIANCE', '2023-01-01', '2023-12-31')
print(historical_data)
```

## Use Cases

- **Real-time Analysis**: Investors can track stock prices in real-time to make informed decisions.
- **Historical Data Analysis**: Users can analyze historical stock performance over specific time periods to identify trends.
- **Automated Trading Strategies**: Integrate with trading algorithms to automate buy/sell decisions based on real-time data.
- **Portfolio Management**: Keep track of multiple stocks and their performance metrics.

## Contributing
We welcome contributions to the QuantifyIndia package! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or feedback, feel free to reach out:

Email: [cparth495@gmail.com](mailto:cparth495@gmail.com)  
GitHub: [Parthchauh](https://github.com/Parthchauh)

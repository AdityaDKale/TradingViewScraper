# Real-time Data Collection and Excel Logging

This Python script is designed to connect to TradingView's WebSocket API, retrieve real-time market data, and log it to an Excel file. The script fetches price data for a specified symbol and logs the data, including timestamp and price, into an Excel file. It is designed to run forever on repl collecting the data you like.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- The `websocket-client` library (`pip install websocket-client`)
- The `openpyxl` library (`pip install openpyxl`)

## Usage

1. Clone this repository or copy the script to your project directory.
2. Ensure you have the necessary libraries installed.
3. Run the script using the command: `main.py`.

## Features

- Fetches real-time market data from TradingView's WebSocket API.
- Logs data into an Excel file with today's date as the filename.
- Data includes timestamp, symbol, and price.

## Configuration

1. Specify the desired symbol by updating the `symbol_id` variable.
2. Update the WebSocket URL if necessary (`tradingViewSocket`).
3. The script will create a new Excel file named with today's date in the `Output` folder.

## Notes

- This script is designed to showcase real-time data collection and Excel logging. It can be extended and customized to suit more advanced trading strategies.
- The script handles interruptions and restarts, maintaining a single Excel file for each day.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Disclaimer:** Trading involves risk, and this script is provided for educational purposes only. Make sure to understand and comply with relevant regulations and perform proper testing before deploying any trading strategies.

# Crypto Historical Data to PostgreSQL

This project retrieves historical cryptocurrency data from Binance using the `ccxt` library and saves it to a PostgreSQL database.

## Features
- Fetches OHLCV data for specified cryptocurrency pairs.
- Stores the data directly in a PostgreSQL database.
- Automatically creates tables for each trading pair.

## Prerequisites
- Python 3.8+
- PostgreSQL database
- Binance account for API access (optional).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/neil-the-nice-dev/SQL-GET-DATA-CRYPTO
   cd SQL-GET-DATA-CRYPTO
   pip install -r requirements.txt
   python main.ipynb

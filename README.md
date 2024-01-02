# --Crypto-triangular-bot

## Introduction

This Python script is a simple crypto arbitrage bot that leverages the Binance API to explore price differentials between BTC, USDT, and ROSE. The bot attempts to capitalize on these differences by executing buy and sell orders.

## Configuration

Before running the script, make sure to provide your Binance API key and secret:

```python
api_key = ""
api_secret = ""

## Dependencies

- Python 3.x
- Binance API (pip install python-binance)
- Twisted (pip install twisted)


## Important Notes

- This bot performs arbitrage based on a predefined gap threshold.
- It executes limit orders to buy and sell assets.
- Use it responsibly and be aware of potential risks.

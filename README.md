# Cryptocurrency exchange arbitrage software

This progam calculates the arbitrage percentage between exchanges

### Usage

```shell
python percentage.py cryptocurrency [marketIn] [marketOut] [options]
```

### Supported Markets and Cryptocurrencies

#### Markets:

- Europe/NA:
	- Coinbase Pro

- Asia:
	- coinone
	- korbit

#### Cryptocurrencies:

- BCH
- BTC
- ETH
- LTC

#### Options

- --html | Output in html for easy usage in webapps.
- --loop | Enter loop mode, the program will repeat checking every few seconds.

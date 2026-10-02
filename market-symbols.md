# A practical watchlist for an LED market ticker

This guide is from Turionics, the maker of the LED desk ticker. It explains how to identify a quote and build a readable watchlist. The examples are display configuration, not investment recommendations.

## Choose the quote you mean

An index level, an ETF share price and a futures quote describe different instruments. Their numbers need not match, even when all three follow the same market.

| Symbol | Quote | Where to add it in the Turionics panel |
| --- | --- | --- |
| `BTC` | Bitcoin | Crypto |
| `ETH` | Ethereum | Crypto |
| `NVDA` | NVIDIA shares | Stocks |
| `AAPL` | Apple shares | Stocks |
| `^GSPC` | S&P 500 index level, in points | Stocks → Other… |
| `SPY` | SPDR S&P 500 ETF share price | Stocks → Other… |
| `QQQ` | Invesco QQQ ETF share price | Stocks → Other… |
| `ES=F` | Yahoo Finance S&P 500 futures quote | Stocks → Other… |
| `EURUSD=X` | EUR/USD exchange rate | Forex → EUR/USD, or Stocks → Other… |
| `GC=F` | Yahoo Finance gold futures quote | Commodities, or Stocks → Other… |
| `^TNX` | U.S. 10-year Treasury yield, displayed as a percentage | Stocks → Other… |

The caret in `^GSPC`, the equals sign in `ES=F` and the suffix in `EURUSD=X` are part of the symbol. Keep them when entering a custom Yahoo Finance symbol.

## Add the watchlist

1. Connect the ticker to Wi-Fi using the device's setup instructions.
2. Open its control panel in a browser on the same network.
3. Pick Crypto, Stocks, Forex or Commodities.
4. Select an instrument from the list. For a custom symbol, choose **Other…** and enter the exact symbol.
5. Read the returned full name before adding it. This distinguishes an index from an ETF or futures contract.
6. Add a few familiar entries first, then set the rotation and brightness for your desk.

For example, start with `BTC`, `NVDA`, `^GSPC`, `EURUSD=X` and `GC=F`. Add `SPY` as a separate entry when you want to see an ETF share price alongside the index level. Quotes can update on different schedules; use the instrument name and market session to interpret them.

## Check symbols and setup details

- [Turionics user manual](https://turionics.com/user-manual/): connection and control-panel instructions.
- [Full symbol cheat sheet](https://turionics.com/2026/09/23/stock-ticker-symbols-for-a-desk-ticker/): more markets and symbol examples.
- [S&P 500 display guide](https://turionics.com/2026/09/29/sp-500-ticker-display/): index, ETF and futures setup.
- [Yahoo Finance](https://finance.yahoo.com/): check the exact ticker and instrument name for custom non-crypto entries.

The same display rotates through crypto, stocks, ETFs, indices, futures, Treasury yields, forex and commodities. The control panel runs in a browser; there is no app, account or subscription.

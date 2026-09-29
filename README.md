# Hi, I'm Valentine Tur 👋

I design, build and test **[Turionics](https://turionics.com/?utm_source=github&utm_medium=profile)** LED market tickers in my workshop in Warsaw.

[![Turionics green LED ticker showing the live Bitcoin price](https://turionics.com/wp-content/uploads/2026/01/2-green-photoshop.jpg)](https://turionics.com/shop/?utm_source=github&utm_medium=profile)

**Turionics** is a live market ticker for your desk: a 64×8 LED display driven by a Seeed XIAO ESP32-C6 that shows the prices you care about in one rotating carousel of up to 100 items:

- **Crypto**: Bitcoin, Ethereum, Solana, XRP and 1000+ coins from Coinbase or Binance, updating every second
- **Stocks**: NVIDIA, Apple, Tesla, Microsoft and listings from the world's major exchanges, each in its own currency
- **ETFs**: SPY, VOO, QQQ, GLD and more
- **Market indices**: S&P 500, Nasdaq, Dow Jones, DAX, FTSE 100, Nikkei 225, Hang Seng
- **Futures**: stock index, oil, gold, grains and CME Bitcoin futures
- **Commodities**: gold, silver, platinum, copper, crude oil, natural gas
- **Forex**: EUR/USD, GBP/USD, USD/JPY and any other pair
- **U.S. Treasury yields**: 13-week, 5-, 10- and 30-year

The text never scrolls: long prices are shortened smartly so one glance is enough. Setup takes about five minutes in any browser, with no app, no account and no subscription.

### Under the hood
Seeed XIAO ESP32-C6, eight MAX7219 8×8 modules, USB-C, under 5 W. Crypto streams straight from the exchange over WebSocket, with automatic fallback between Coinbase, Binance and Binance.US. Stocks, indices, futures and yields come from Yahoo Finance, and polling pauses while each exchange is closed. OTA firmware updates are verified before install and roll back automatically on a failed boot.

### Links
- 🛒 Shop: [turionics.com](https://turionics.com/?utm_source=github&utm_medium=profile)
- 🪙 [Bitcoin price ticker](https://turionics.com/product/bitcoin-price-ticker-green-display-500-other-cryptocurrencies/?utm_source=github&utm_medium=profile)
- 🔤 [Ticker symbol cheat sheet](https://turionics.com/2026/09/23/stock-ticker-symbols-for-a-desk-ticker/)
- ✉️ contact@turionics.com

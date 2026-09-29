# Hi, I'm Valentine Tur 👋

I design, build and test **[Turionics](https://turionics.com/?utm_source=github&utm_medium=profile)** LED market tickers in my workshop in Warsaw.

[![Turionics LED ticker showing the S&P 500](https://turionics.com/wp-content/uploads/2026/09/sp-500-ticker-display-desk-v147.jpg)](https://turionics.com/?utm_source=github&utm_medium=profile)

**Turionics** is a live market ticker for your desk: a 64×8 LED display driven by a Seeed XIAO ESP32-C6 that shows the prices you care about in one rotating carousel of up to 100 items:

- **Crypto**: 1000+ coins from Coinbase or Binance, updating every second
- **Stocks and ETFs**: US and international listings, each in its own currency
- **Indices and futures**: S&P 500, Nasdaq, Dow, DAX, Nikkei, E-mini futures, in points
- **U.S. Treasury yields**, **forex pairs**, **gold, oil and other commodities**

The text never scrolls: long prices are shortened smartly so one glance is enough. Setup takes about five minutes in any browser, with no app, no account and no subscription.

### Under the hood
Seeed XIAO ESP32-C6, eight MAX7219 8×8 modules, USB-C, under 5 W. Crypto streams straight from the exchange over WebSocket, with automatic fallback between Coinbase, Binance and Binance.US. Stocks, indices, futures and yields come from Yahoo Finance, and polling pauses while each exchange is closed. OTA firmware updates are verified before install and roll back automatically on a failed boot.

### Links
- 🛒 Shop: [turionics.com](https://turionics.com/?utm_source=github&utm_medium=profile)
- 📈 [S&P 500 on your desk: every symbol](https://turionics.com/2026/09/29/sp-500-ticker-display/)
- 🔤 [Ticker symbol cheat sheet](https://turionics.com/2026/09/23/stock-ticker-symbols-for-a-desk-ticker/)
- ✉️ contact@turionics.com

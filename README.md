# tradingview
# Manual Options Trade Journal – Pine Script

This project is a Pine Script implementation for TradingView that allows users to manually log options trades into a live table overlay on a chart.

## ✨ Features

- 📥 Manual entry of ticker, premium, contracts, strike, expiry, notes
- 📈 Auto-filled live data: timestamp, price, and % change since first log
- 🧾 Tabular logging for trade journaling and exporting to Google Sheets
- 🔧 Fully customizable and designed to support product experimentation

## 🎯 Use Case

This project was built to support a real-world trading workflow for options traders who:
- Prefer to manually log trades while watching charts
- Want a visual, copyable ledger that evolves in real-time
- Want to later analyze entries/exits in spreadsheets/tabular data or dashboards

## 💡 Why I Built This

- get my first exposure to scripting
- learn more about coding, trading, and using code to trade
- learn about Pine Script 

## 🛠 How It Works

1. Toggle the `Log Trade` switch inside TradingView’s indicator settings
2. Fill in your trade metadata (ticker, premium, etc.)
3. The script captures timestamp, price, and calculates % change
4. Each new trade adds a row to the table (up to 50 max)

## 📷 Screenshot

<img width="1130" alt="image" src="https://github.com/user-attachments/assets/79af17b6-c359-462a-979e-027c4080bfa3" />


## 🧰 Built With

- Pine Script (v6)
- TradingView charting platform

## 📤 Future Improvements

- Add a reset button
- Export data to webhook or external store (via companion script)
- Add P/L visualization

---

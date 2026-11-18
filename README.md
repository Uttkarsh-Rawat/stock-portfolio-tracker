# stock-portfolio-tracker
A beginner-friendly Python stock portfolio tracker that calculates investment value using manually defined stock prices and can export the summary to CSV.
# 📈 Stock Portfolio Tracker

A simple Python program that calculates the total value of your stock holdings using manually defined stock prices.

## ✨ Features

- 📊 Displays supported stock symbols and their prices.
- ⌨️ Accepts stock symbols and share quantities from the user.
- 🧮 Calculates the value of each holding and the total investment.
- 💾 Optionally saves the portfolio summary to a CSV file.
- ✅ Checks that quantities are positive whole numbers.

## 🛠️ Requirements

- 🐍 Python 3
- 📦 No external packages required

## 🚀 Run the program

Open a terminal in this folder and run:

```bash
python stock_portfolio_tracker.py
```

On some Windows installations, use:

```bash
py stock_portfolio_tracker.py
```

## 📝 How to use

1. Enter a stock symbol shown in the available stock list, such as `AAPL`.
2. Enter the number of shares you own.
3. Repeat for other stocks. If you enter the same symbol more than once, the quantities are combined.
4. Type `DONE` when you have finished entering stocks.
5. Review the per-stock values and total investment.
6. Enter `y` when asked whether to save a CSV report. The report will be written to `portfolio.csv` in the current folder.

## 💡 Example

With 3 shares of AAPL at $180 each and 2 shares of TSLA at $250 each:

```text
AAPL: 3 shares × $180.00 = $540.00
TSLA: 2 shares × $250.00 = $500.00
Total investment: $1040.00
```

## ⚙️ Changing stock prices

Open `stock_portfolio_tracker.py` and edit the `STOCK_PRICES` dictionary near the top of the file. For example:

```python
STOCK_PRICES = {
    "AAPL": 180.00,
    "TSLA": 250.00,
}
```

> ⚠️ These are manually entered example prices. The program does not fetch live market prices.

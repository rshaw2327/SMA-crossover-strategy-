📈 SMA Crossover Trading Strategy (Python)

This project implements a Simple Moving Average (SMA) crossover trading strategy using Python, pandas, NumPy, and matplotlib. It performs vectorized backtesting on EUR/USD price data and compares strategy performance against a buy-and-hold benchmark.

🚀 Strategy Overview

The strategy uses two moving averages:

Short-term SMA (e.g., 50-day)

Long-term SMA (e.g., 200-day)
<img width="1223" height="709" alt="image" src="https://github.com/user-attachments/assets/254d2f4b-7e7c-45da-b146-5b74d0dd066d" />

Trading Logic:

Go Long (1) when SMA_short > SMA_long

Go Short (-1) when SMA_short < SMA_long

<img width="1198" height="695" alt="image" src="https://github.com/user-attachments/assets/0f696b28-745a-4007-baec-2d3bacea8a3e" />


Returns are calculated using log returns, and performance metrics are annualized.

📊 Example Output

<img width="1346" height="681" alt="image" src="https://github.com/user-attachments/assets/bc913000-331f-4da7-ba61-2821bc3dd0ad" />


The script:

Plots price and moving averages

Visualizes trading positions

Calculates:

Total returns

Annualized return

Annualized volatility

Strategy vs. buy-and-hold comparison

⚠️ Disclaimer

This project is for educational purposes only. It does not constitute financial advice. Past performance does not guarantee future results.


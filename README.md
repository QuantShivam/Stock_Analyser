# 📈 Stock Analyser

A terminal-based portfolio analyser for NSE/BSE stocks — built with pure Python, no libraries needed.

## 🖥️ Output Preview

```
══════════════════════════════════════════════════════════════
  STOCK-WISE BREAKDOWN
══════════════════════════════════════════════════════════════
  STOCK        BUY ₹    NOW ₹   QTY      P&L ₹   RETURN  STATUS
  ────────────────────────────────────────────────────────────
  RELIANCE   1307.00  1433.95    10    1269.50    9.71%  WIN  🟢
  TATAPOWER   365.05   387.65    15     338.99    6.19%  WIN  🟢
  TATASTEEL   216.33   186.79     5    -147.70  -13.66%  LOSS 🔴
  HDFCBANK   1440.00  1720.00     8    2240.00   19.44%  WIN  🟢
══════════════════════════════════════════════════════════════
  PORTFOLIO SUMMARY
══════════════════════════════════════════════════════════════
  Total Invested              ₹      27837.40
  Total P&L                   ₹       3700.79
  Overall Return                        13.29%
  Winning Trades               3 stock(s)
  Losing Trades                1 stock(s)
══════════════════════════════════════════════════════════════
  BEST & WORST PERFORMER
══════════════════════════════════════════════════════════════
  🏆 Best  → HDFCBANK      +19.44%   ₹    2240.00
  📉 Worst → TATASTEEL     -13.66%   ₹    -147.70
══════════════════════════════════════════════════════════════
```

## ▶️ How to Run

```bash
python Stock_Analyser.py
```

## ✏️ How to Customise

Edit these 4 lines at the top of the file with your own stocks:

```python
stocks         = ["RELIANCE", "TATAPOWER", "TATASTEEL", "HDFCBANK"]
buy_prices     = [1307.00, 365.05, 216.33, 1440.00]
current_prices = [1433.95, 387.65, 186.79, 1720.00]
quantities     = [10, 15, 5, 8]
```

## 🧠 Concepts Used

- Variables & Data Types
- Operators & Arithmetic
- String Formatting (f-strings)
- Conditional Logic (if/elif/else)
- Loops (for)
- Lists
- Functions

## 👤 Author

**Shivam Tyagi** — learning Python & quant trading from scratch, Delhi, India.

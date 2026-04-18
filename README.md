# 📊 Short-Term Trading Strategy (T+1)

## 🚀 Overview
This project implements a **short-term trading strategy** on the NIFTY index based on a simple idea:

> Buy today → Sell the next trading day (T+1)

The strategy is enhanced using:
- Price-based signals (momentum / mean reversion)

---

## 🧠 Strategy Logic

### 1. Mean Reversion
- Buy when daily return < -1%
- Sell next day
- Assumption: Market overreacts → short-term correction

### 2. Momentum
- Buy when daily return > +1%
- Sell next day
- Assumption: Trend continues for short horizon

---
🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib / Seaborn


+++
date = '2025-10-01T09:05:48+08:00'
#draft = true
title = 'Turtle Trading System'
+++

# What is Turtle Trading System?

Turtle Trading System is rules-based trend-following strategy developed by legendary commodity trader Richard Dennis in the 1980s. Below are the rule for trading:

## 1. Position Size & Risk Management (Unit System)

The maximum portion size are 2% of your current portofolio and you have to calculate it after every trade. It is recommended to use only 1% of your portofolio. For entry you have to calculate unit size. Unit Size are calculated based on you portion size (in this case 1%) and divided by ATR (Average True Range) times by 2 (maximum loss are 2 ATR). In the formula ATR will be known as **N**. So the formula should be like **Unit Size = 1% * portfolio / 2N**.

## 2. Entry Rules (Breakouts)

There are 2 System for Entry using Turtle Trading System. There are:

### A. System 1 - Using 20 Trading Days

In the trading view you can use **Donchian Channel Strategy**, set the value to 20 and change it into days time frame.

### B. System 2 - Using 55 Trading Days

In the trading view you can use **Donchian Channel Strategy**, set the value to 55 and change it into days time frame.

Use long position after it break the higher position and use short position after it break the lower position.

## 3. Pyramiding (Adding to Winners)

For every **0.5N** from the lass trade add additional Unit Size for maximum **4 unit size** (4% of porto) for every trade.

## 4. Stop-Loss (Risk Management)

For stop loss are based on 2 ATR (Average True Range) or in our formula 2N. It should be updated everytime your entry

## 5. Exit Rules (Taking Profits)

There are 2 System for Exit using Turtle Trading System. There are:

### A. System 1 - Using 10 Trading Days

In the trading view you can use **Donchian Channel Strategy**, set the value to 10 and change it into days time frame.

### B. System 2 - Using 20 Trading Days

In the trading view you can use **Donchian Channel Strategy**, set the value to 20 and change it into days time frame.

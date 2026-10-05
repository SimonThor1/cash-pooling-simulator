# cash-pooling-simulator
Just for fun!
# Cash Pooling Simulator

A small project exploring how a cash pool affects interest costs and
income for a company with several bank accounts.

## Background
Companies with several accounts often have some in overdraft while
others hold surplus cash. A cash pool nets these balances, which can
reduce interest costs. This project simulates the effect using
fictional data.

## What it does
- Reads daily balances for several accounts (example data included)
- Calculates net interest with and without a cash pool
- Shows the difference in a simple chart

## How to run
pip install -r requirements.txt
python src/simulate.py

## Assumptions
- Fictional data and interest rates
- Simplified model (no fees, taxes or limits)

## Possible extensions
- Different interest rates per account
- Notional vs. physical pooling
- Multi-currency accounts

## Author
Simon Thorsell, Economics student at Uppsala University

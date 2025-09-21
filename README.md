# portfolio-optimisation-capm
Public-data demo: stock returns, 2-asset portfolio, and CAPM regression with Yahoo Finance

# Portfolio Optimisation & CAPM (Public Data Demo)

> Original coursework used Bloomberg (restricted). This repo reproduces the workflow using **public data** (Yahoo Finance) so anyone can run it.

## What this shows
- Download prices (Yahoo Finance) for an equity and a market index
- Compute daily returns + quick summary stats
- Simple 2-asset portfolio risk/return sweep
- CAPM regression: excess returns of stock on market (β, α, R²)

## How to run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt

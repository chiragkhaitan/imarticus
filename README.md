# Portfolio Reporting System — Final V2

React + Vite prototype for a portfolio reporting presentation.

## Features
- Two client profiles: Mid-Tier and High-Net-Worth
- Manual BUY/SELL transactions and backdated trades
- Holdings with buy date, holding period, buy value, market price, market value and MTM
- Built-in illustrative historical market-price dataset (no API required)
- MTM calculation boxes with formulas
- Multi-currency cash and FX-to-INR calculations
- Benchmark selector: NIFTY 50, SENSEX, S&P 500, NASDAQ Composite, FTSE 100
- Period selector: 1 Month, 3 Months, 6 Months, 1 Year
- Portfolio vs benchmark charts
- Downloadable/printable client statement; browser Print → Save as PDF
- Audit trail, client comparison and system architecture

## Run
npm install
npm run dev

## Deploy
Push to GitHub. Vercel automatically redeploys the latest commit.

## Important
Market prices are illustrative historical data included in the prototype. The app does not claim live exchange/API connectivity.

## Final presentation updates
- Holdings table explicitly shows Security, Asset, CCY, Qty, Buy Value, Current Value, Gain/Loss and Holding Period.
- Market Price Feed card demonstrates the MTM price-source layer without claiming a live Bloomberg connection.
- Performance supports 1 Month, 3 Months, 6 Months, YTD and 1 Year, plus NIFTY 50, SENSEX, S&P 500, NASDAQ Composite and FTSE 100.
- Architecture explicitly merges Internal Portfolio Data with an External Market Data Feed before Portfolio Valuation / MTM.

## Final clean-up
The architecture and market-feed sections were given responsive, non-overlapping layouts for desktop and mobile presentation.

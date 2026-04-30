# Autonomous Equity — Trade Log

Public, timestamped record of trades executed by the Autonomous Equity C2 signal account.

## Publication Delay

All data is published with a **7-day delay**. Trades and positions are not visible until at least 7 calendar days after they occurred.

## Data Format

### `trades/YYYY-MM-DD.csv`
Closed trades by close date. Columns: ticker, side, qty, entry_price, exit_price, pnl, opened_at, closed_at, hold_days.

### `positions/YYYY-MM-DD.csv`
End-of-day open position snapshots. Columns: ticker, side, qty, entry_price, opened_at.

### `summary/YYYY-MM-DD.md`
Daily summary: trades opened/closed, open positions, day P&L.

## Disclaimer

Past performance does not guarantee future results. This log is provided for transparency and informational purposes only. It does not constitute investment advice. Trading involves risk of loss.

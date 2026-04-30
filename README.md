# Autonomous Equity — Trade Log

Public, timestamped record of all trades executed by the Autonomous Equity platform.

## Publication Delay

All data is published with a **7-day delay**. Trades and positions are not visible until at least 7 calendar days after they occurred. This prevents real-time position freeloading while maintaining full transparency.

## Data Format

### `trades/YYYY-MM-DD.csv`
Closed trades by close date. Columns: ticker, side, qty, entry_price, exit_price, pnl, strategy_id, regime, opened_at, closed_at, hold_days, account.

### `positions/YYYY-MM-DD.csv`
End-of-day open position snapshots. Columns: ticker, side, qty, entry_price, strategy_id, regime, opened_at, account.

### `summary/YYYY-MM-DD.md`
Daily summary including total P&L, trade counts, open positions, and regime at close.

## Accounts

- **personal** — Founder's paper trading account
- **c2** — C2 subscriber signal account

## Disclaimer

Past performance does not guarantee future results. This log is provided for transparency and informational purposes only. It does not constitute investment advice. Trading involves risk of loss. The strategies, signals, and positions documented here are from a paper trading environment and may not reflect results achievable in live trading.

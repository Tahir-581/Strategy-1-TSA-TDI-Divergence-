# TSA TDI Divergence Strategy (TradingView)

Pine Script **strategy** combining **TSA TDI** (Traders Dynamic Index variant) with **regular divergence** detection and optional candle confirmation for entries.

## Files

| File | Description |
|------|-------------|
| `TSA_TDI_Divergence_Strategy.pine` | Full Pine Script source |
| `README.md` | Documentation (this file) |

> If the `.pine` file is missing, check git history — source may have lived in README before migration.

## Strategy summary

- Detects pivot highs/lows and regular bullish/bearish divergences on TDI
- Optional bullish/bearish candle confirmation for entries
- Configurable stop loss / take profit (pips)
- Overlay strategy on price chart

## Import into TradingView

1. Open **Pine Editor** on TradingView.
2. Paste contents of `TSA_TDI_Divergence_Strategy.pine`.
3. **Save** → **Add to chart**.
4. Enable **Strategy Tester** for backtests.
5. Tune inputs: pivot period, TDI lengths, SL/TP, divergence lookback.

## Disclaimer

For educational and research purposes only. Not financial advice. Backtest thoroughly before live trading.

## License

Private — personal use.

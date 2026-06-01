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

## Installation

1. Install [TradingView](https://www.tradingview.com/) (free account is sufficient).
2. Open the **Pine Editor** from any chart.

## Usage

1. Paste contents of `TSA_TDI_Divergence_Strategy.pine` into the editor.
2. Click **Save** → **Add to chart**.
3. Open **Strategy Tester** to backtest on your symbol/timeframe.
4. Tune inputs: pivot period, TDI lengths, SL/TP, divergence lookback.

## Disclaimer

For educational and research purposes only. Not financial advice. Backtest thoroughly before live trading.

## License

Private — personal use.

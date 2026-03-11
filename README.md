# NQ/YM TradingView Indicator

Pine Script v5 indicator for day trading NQ (NASDAQ 100 E-mini) and YM (Dow E-mini) futures.

## Features

- **Support/Resistance Zones** - Auto-detected from pivot highs/lows
- **Fair Value Gaps (FVGs)** - Bullish and bearish imbalance detection
- **Fibonacci Levels** - 0.236, 0.382, 0.5, 0.618, 0.786 with custom colors
- **Time-Gated Signals** - Buy/Sell alerts only during first hour after market open
- **Risk Management** - Auto SL/TP plotting with R:R ratios
- **Position Sizing** - Contract calculation based on account risk

## Installation

1. Open TradingView → Pine Editor (bottom panel)
2. Delete default code
3. Copy/paste `nq_ym_srfvg_indicator.pine`
4. Click "Add to Chart"
5. Apply to NQ1! or YM1! on 5m or 15m timeframe

## Settings

| Setting | Default | Description |
|---------|---------|-------------|
| Market Open Hour | 9 | ET hour (9 = 9:30 AM) |
| Signal Window | 60 | Minutes after open to allow signals |
| S/R Lookback | 10 | Bars to confirm pivot high/low |
| Stop Loss | 25 | Ticks (NQ: 0.25/pt, YM: 1/pt) |
| Risk % | 1.0 | Account risk per trade |

## Fibonacci Colors

- 0.236: White
- 0.382: Yellow
- 0.500: Red
- 0.618: Lime Green
- 0.786: Cyan/Teal

## License

MIT - Use at your own risk. Not financial advice.
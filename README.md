# Engulfing Breakouts (BigE)

Engulfing Breakouts is a trend-following breakout indicator designed to catch high-conviction continuation moves using structure, volatility, and candle dominance.

It is built for volatile instruments such as NASDAQ indices and USDJPY, where false breakouts and sideways chop are common. The script focuses on quality over frequency and is intended to be used with alerts and trader discretion, not automation.

The indicator combines short- and long-term moving averages for trend context, clearing-bar breakouts for structure confirmation, ATR-based volatility filtering, and strict “elephant candle” requirements to avoid weak or random signals. Entries only occur when price expands decisively out of consolidation in the direction of the prevailing trend.

## How to use

Apply the indicator to an intraday chart of NAS or USDJPY. The 20 SMA defines short-term trend behavior and resets the system when crossed with sufficient momentum. The 200 SMA provides higher-timeframe bias and visual context. Signals are only meaningful when price is clearly aligned with the broader direction.

A long signal appears below the bar when price breaks above recent highs after clearing resistance, printing a large-bodied candle with strong range expansion and minimal wick noise. A short signal appears above the bar under the opposite conditions. These candles represent volatility expansion and institutional participation rather than random price movement.

The indicator allows up to two entries per trend leg. The first signal is usually the most important; the second acts as confirmation or continuation if volatility persists. Exits are managed internally using an ATR-based trailing mechanism and moving-average context, but execution decisions are left to the trader.

This indicator is intended to be used with alerts. When an alert triggers, quickly assess higher-timeframe structure, nearby support or resistance, and overall market conditions before entering. If the market is clearly ranging or compressed, signals should be ignored. When volatility is present, BigE is designed to highlight moments where the probability of follow-through is meaningfully higher than average.

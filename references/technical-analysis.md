# Technical Analysis Guide — Indian Markets

Methodology for analyzing NSE/BSE stocks using price action, indicators, and patterns.

---

## Indicators — Quick Reference

### Trend Indicators

| Indicator | What It Shows | Bullish Signal | Bearish Signal |
|---|---|---|---|
| **SMA (50-day)** | Short-term trend | Price above SMA, SMA trending up | Price below SMA |
| **SMA (200-day)** | Long-term trend | Price above 200 SMA | Price below 200 SMA |
| **EMA (20/50)** | Weighted recent trend | 20 EMA > 50 EMA (golden cross setup) | 20 EMA < 50 EMA |
| **MACD** | Momentum + trend | MACD line crosses above signal line | MACD crosses below signal |
| **ADX** | Trend strength | ADX > 25 = strong trend | ADX < 20 = no trend |

### Momentum Indicators

| Indicator | Range | Buy Signal | Sell Signal |
|---|---|---|---|
| **RSI (14)** | 0-100 | <30 (oversold) + rising | >70 (overbought) + falling |
| **Stochastic** | 0-100 | %K crosses above %D below 20 | %K crosses below %D above 80 |
| **Williams %R** | -100 to 0 | Below -80 (oversold) | Above -20 (overbought) |

### Volatility Indicators

| Indicator | What It Shows | Key Signal |
|---|---|---|
| **Bollinger Bands** | Volatility range | Price touching lower band = potential bounce; upper band = potential pullback |
| **ATR (14)** | Average True Range | High ATR = high volatility, wider stop loss needed |
| **VIX (India VIX)** | Market fear gauge | >25 = high fear (opportunity), <12 = complacency |

### Volume Indicators

| Indicator | What It Shows | Signal |
|---|---|---|
| **OBV (On Balance Volume)** | Volume trend | Rising OBV confirms uptrend |
| **VWAP** | Average price weighted by volume | Price > VWAP = bullish intraday |
| **Volume Profile** | Volume at price levels | High volume nodes = support/resistance |
| **MFI (Money Flow Index)** | Volume-weighted RSI | <20 = oversold, >80 = overbought |

---

## Key Levels — Support & Resistance

### How to Identify

**Support** — Price level where buying historically emerges:
- Previous swing lows
- Round numbers (₹1000, ₹500, ₹2000)
- 50-day and 200-day SMA values
- Previous breakout levels (now support)
- High volume nodes (from volume profile)

**Resistance** — Price level where selling historically emerges:
- Previous swing highs
- All-time highs
- Trendline connections
- Bollinger Band upper band
- Gap fill levels

### Indian Market Specifics

- **Round numbers matter more in India** — ₹500, ₹1000, ₹2000, ₹5000 act as psychological levels
- **NIFTY levels** — 22000, 22500, 23000 etc. are psychological barriers
- **Pre-budget / Pre-results** — Markets often consolidate near round numbers before events

---

## Candlestick Patterns

### Bullish Reversal

| Pattern | Description | Reliability |
|---|---|---|
| **Hammer** | Small body, long lower shadow, at bottom | High |
| **Bullish Engulfing** | Green candle fully engulfs previous red | High |
| **Morning Star** | Three-candle reversal at bottom | Very High |
| **Piercing Line** | Green opens below prior low, closes >50% into prior body | Medium |
| **Doji at Support** | Indecision candle at key support | Medium (confirm next candle) |

### Bearish Reversal

| Pattern | Description | Reliability |
|---|---|---|
| **Shooting Star** | Small body, long upper shadow, at top | High |
| **Bearish Engulfing** | Red candle fully engulfs previous green | High |
| **Evening Star** | Three-candle reversal at top | Very High |
| **Dark Cloud Cover** | Red opens above prior high, closes >50% into prior body | Medium |

### Continuation

| Pattern | Description |
|---|---|
| **Bull Flag** | Sharp rise + slight downward consolidation → breakout up |
| **Bear Flag** | Sharp fall + slight upward consolidation → breakout down |
| **Ascending Triangle** | Flat resistance + rising support → bullish breakout |
| **Descending Triangle** | Flat support + falling resistance → bearish breakout |
| **Wedge (Rising)** | Converging trendlines slanting up → bearish |
| **Wedge (Falling)** | Converging trendlines slanting down → bullish |

---

## Chart Patterns

### Reversal Patterns

| Pattern | Timeframe | Target |
|---|---|---|
| **Head & Shoulders** | Daily/Weekly | Height of pattern from neckline |
| **Inverse H&S** | Daily/Weekly | Height of pattern from neckline |
| **Double Top** | Daily | Distance from top to neckline, projected down |
| **Double Bottom** | Daily | Distance from bottom to neckline, projected up |
| **Triple Top/Bottom** | Weekly | Stronger than double, same target method |

### Continuation Patterns

| Pattern | Implication |
|---|---|
| **Cup & Handle** | Bullish continuation — handle breakout is entry |
| **Flag/Pennant** | Continuation in direction of prior trend |
| **Rectangle** | Range-bound; breakout direction matters |
| **Wedge** | Depending on slope, reversal or continuation |

---

## Trading Strategies

### Strategy 1: Moving Average Crossover

```
Entry: 20 EMA crosses above 50 EMA (Golden Cross)
Exit: 20 EMA crosses below 50 EMA (Death Cross)
Stop Loss: Below the 50 EMA at entry
Best for: Medium to long term, trending markets
Works well on: NIFTY 50 stocks, large caps
```

### Strategy 2: RSI Mean Reversion

```
Buy: RSI < 30 + price at support + bullish candle pattern
Sell: RSI > 70 + price at resistance
Stop Loss: Below recent swing low
Best for: Range-bound markets, individual stocks
```

### Strategy 3: MACD + Volume Confirmation

```
Buy: MACD bullish crossover + volume > 1.5x average
Sell: MACD bearish crossover + volume spike
Confirmation: OBV trending in same direction
Best for: Momentum stocks, mid/small caps
```

### Strategy 4: Breakout Trading

```
Identify: Stock in consolidation (rectangle/wedge)
Buy: Close above resistance with volume > 2x average
Stop Loss: Below breakout level (or below consolidation low)
Target: Height of consolidation projected upward
Best for: Pre-results, pre-event breakouts
```

### Strategy 5: Support Bounce

```
Buy: Price touches strong support (200 SMA / prior swing low / high volume node)
Confirm: RSI < 40 + bullish candle pattern (hammer, bullish engulfing)
Stop Loss: Below support by 2-3%
Target: Next resistance level
Best for: Blue chips, index stocks
```

---

## Timeframe Selection

| Timeframe | Use Case | Indicators to Focus |
|---|---|---|
| **Intraday (5/15 min)** | Day trading | VWAP, 9 EMA, 20 EMA, RSI, Volume |
| **Daily** | Swing trading (1-4 weeks) | 20/50 EMA, MACD, RSI, Bollinger Bands |
| **Weekly** | Position trading (1-6 months) | 50/200 SMA, MACD, Support/Resistance |
| **Monthly** | Long-term investing (1+ years) | 200 SMA, Annual trends, Sector rotation |

---

## Indian Market Technical Considerations

1. **Market hours**: 9:15 AM to 3:30 PM IST. First 15 mins (9:15-9:30) is high volatility — avoid fresh positions.
2. **Gap openings**: Common in India due to global cues. Wait for 15-30 mins before taking positions on gap-up/gap-down days.
3. **Expiry days**: Weekly expiry (Thursday for NIFTY/BANK NIFTY) brings high volatility. Options premium decay accelerates.
4. **FII-driven moves**: Foreign institutional flows can override technicals. Check FII data before relying purely on charts.
5. **Sector rotation**: Indian markets rotate between sectors. IT → Pharma → Banks → Auto → Consumption cycles are common.
6. **Pre-budget rally/dip**: Markets often show pattern breakouts before Union Budget. Be cautious of false breakouts.
7. **Monsoon impact**: Agri, FMCG, and auto sectors are monsoon-sensitive. Technicals may not work during monsoon uncertainty.
8. **India VIX**: Check before trading. VIX > 20 means high volatility — wider stops needed. VIX < 12 means low volatility — tight ranges expected.

---

## Chart Analysis Workflow

1. **Start with monthly chart** — Identify long-term trend (up/down/sideways)
2. **Move to weekly** — Identify major support/resistance zones
3. **Daily chart for entries** — Use indicators and patterns for timing
4. **Intraday for precision** — Fine-tune entry/exit on 15-min chart

Always trade in the direction of the higher timeframe trend.

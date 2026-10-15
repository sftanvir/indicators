# Gold Quant Stack — Spot XAUUSD

**Focus:** Gold. **Venue:** Spot CFD XAUUSD. **Account:** Personal, normal DD. **Stack:** TradingView (Pine) + MT5 (EA).
**Styles:** Scalping (M1/M5) + Day (M15/H1) + Swing (H4/D1).

> Not financial advice. No holy grail. These are the structures that survived decades on Gold net of realistic spread.

---

## Top 5 — Ranked by Long-Term Survival

| Rank | Quant | Style | Edge Source |
|------|-------|-------|-------------|
| 1 | Donchian 20 Breakout + 10 Trail | Swing D1 | Macro trend persistence, central bank bid |
| 2 | Real Yield Regime + 50/200MA Filter | Positional D1/H4 | Gold = anti-real-yield |
| 3 | NY ORB 8:30–9:30 EST + ATR Expansion | Day M15 | COMEX open liquidity + US data flow |
| 4 | London Fix + VWAP Z-Score Fade | Scalp M5 | Fix liquidity dump + mean reversion |
| 5 | DXY Inverse Confirm | Overlay all | -0.8 intraday correlation filter |

Wealth = #1 + #2. Income = #3. Extra = #4. #5 on everything.

---

## 1. SCALPING — M1/M5 — Gold Only

Silver spread kills most scalps. Scalp Gold, use Silver only as follower at 0.5x size.

### 1A. VWAP Z-Score Fade — Best Mean-Reversion

- **Timeframe:** M5
- **Logic:** Distance from VWAP > 2.0 × ATR(14) = fade back to VWAP.
- **Entry:** M5 wick + close back toward VWAP after extension.
- **Target:** VWAP. **SL:** 1.5 × M5 ATR. No scaling.
- **Best window:** Asia + early London. London Fix 10:30 AM / 3:00 PM London time = highest snap rate.
- **Filters:**
  - Spread > $0.35 = no trade.
  - No trade first 15 min of NY.
  - No fade if M15 ATR expanding > 1.2x — trend day, fades die.
- **Why it works:** Gold overextends on thin liquidity then snaps to volume-weighted fair value.

### 1B. NY Momentum Breakout — Best Trend Scalp

- **Timeframe:** M1
- **Logic:** M1 close beyond 9:30–10:00 NY 30-min high/low + range expansion = momentum continuation.
- **Entry:** Retest hold or next-candle continuation. No chase > 0.5 ATR past break.
- **Target:** 1.5R. **SL:** Breakout candle high/low.
- **Filters:**
  - DXY must agree: Long Gold = DXY red / below VWAP. No counter-DXY trades.
  - One loss = done for the 30-min window. No revenge.
- **Why it works:** NY is when real money moves Gold. Breakouts here follow through vs. Asia fakeouts.

---

## 2. DAY TRADING — M15/H1 — Gold + Silver

### 2A. DXY Inverse Trend Pullback — Edge #1

- **Timeframes:** H1 trend + M15 entry
- **Logic:** H1 EMA 20 > 50 = long bias only. Wait M15 pullback to 20 EMA, enter on rejection when DXY rejects opposite direction.
- **Entry:** M15 rejection candle at 20 EMA + DXY confirming inverse.
- **Target:** Prior H1 high / 2R. **SL:** Below M15 pullback low + 0.3 ATR buffer.
- **Silver use:** Take signal on Gold, mirror on Silver with 0.7x size. Silver lags Gold 2–5 candles — Gold leads.
- **Why it works:** ~80% of Gold intraday variance = DXY + yields. Trading with DXY removes half the false breaks.

### 2B. London / NY ORB + ATR Expansion — Edge #2

- **Timeframes:** M15
- **London ORB:** 3:00–4:00 AM EST range. Break + M15 ATR > 1.2x = day trend.
- **NY ORB:** 8:30–9:30 AM EST range. Same rule. NY ORB > London ORB in expectancy.
- **Entry:** M15 close outside ORB, enter on retest or next candle.
- **Target:** 1.5–2R / measured ORB width. **SL:** Opposite side of ORB.
- **Rules:** One trade per session. Skip FOMC/CPI inside-range chop. Widen SL 1.5x on red news or skip.
- **Why it works:** Gold/Silver are session-driven. Liquidity sweeps are timed to opens. ORB captures the institutional push.

**Day parameters:** ATR 14, EMA 20/50, ORB 60-min. Nothing exotic survives longer.

---

## 3. SWING — H4/D1 — Gold + Silver + Ratio

### 3A. Regime Trend — Core Holding

- **Timeframes:** D1 regime + H4 entry
- **Regime:** D1 close > 50 SMA + US10Y Real Yield falling (below 20D MA) = long bias only. Inverse = flat or short bias.
- **Entry:** H4 pullback to 20 EMA + hold.
- **Exit:** H4 close below 50 EMA or 3 × ATR trail. No fixed TP — let runners run.
- **Risk:** 0.5–1% per position.
- **Why it works:** Gold bull markets = falling real yields + central bank bid. Regime filter keeps you on the right side.

### 3B. Donchian 20 Breakout — Catches Runners

- **Timeframe:** D1
- **Logic:** D1 close > 20-day high = buy. Trail at 10-day low. Original Turtle logic, still alive on Gold.
- **Risk:** 0.5–1%. Needs 3 × ATR room — tight stops get hunted.
- **Silver adjustment:** 20% smaller size, 1.5x wider SL. Silver hunts stops harder.
- **Why it works:** Gold trends 3–8 weeks after CPI/FOMC/macro breaks. Breakout captures the full leg.
- **Dead zones:** 2013–2015 chop, 2021–2023 range. Expect 6–10 small losses before the runner. That is the system.

### 3C. Gold/Silver Ratio Rotation — Only Consistent Silver Edge

- **Logic:** Ratio > 85 = overweight Silver (high beta catch-up). Ratio < 75 = overweight Gold (defensive).
- **Execution:** Apply 3A/3B signals, tilt size toward the cheap leg.
- **Why it works:** Silver is high-beta Gold. Ratio extremes mean-revert as risk regime normalizes.

---

## 4. DXY OVERLAY — Apply to All

- Long Gold only if DXY < VWAP / red M15. Short Gold only if DXY green / > VWAP.
- Adds +0.3–0.5R expectancy by filtering false breaks.
- Exception: risk-off panic where Gold + DXY rally together. Then stand aside — correlation breaks, do not force.

---

## 5. SILVER (XAGUSD) — Appendix

- **Rule 1:** Gold leads, Silver follows. Enter on Gold signal, mirror Silver.
- **Rule 2:** 0.5–0.7x Gold size. Wider spread + slippage + stop hunts.
- **Rule 3:** M5 minimum for scalps. No M1 Silver scalping on spot — spread kills edge.
- **Rule 4:** 1.5x wider SL vs Gold in ATR terms.
- **Best Silver quants:** 2A (Gold-signal mirror), 3B (Donchian with wider trail), 3C (ratio rotation).

---

## 6. WHAT DOESN'T WORK ON SPOT GOLD/SILVER

RSI divergence alone, MACD cross, default Bollinger bands, grid/martingale, fixed TP without ATR normalization. All bleed on one NY spike. If it has no session filter, spread filter, and ATR stop — it dies on Gold.

---

## 7. BUILD ROADMAP — TradingView + MT5

1. `pine/vwap_zscore` — VWAP + 2σ bands + ATR spread guard
2. `pine/orb_ny_london` — Session ORB + ATR expansion flag
3. `pine/regime_dashboard` — 50/200MA + real-yield bias + DXY state
4. `mt5/ea_gold_orb` — ORB EA with spread filter + session filter + ATR SL/TP
5. `mt5/ea_gold_donchian` — Donchian 20/10 EA with 3×ATR room + ratio tilt
6. Backtest protocol: tick data, $0.30–0.40 spread, $0 swap-adjusted, 1:20–1:100 leverage check, FOMC/CPI exclusion test.

---

## 8. RISK — Personal Account

- Scalp: 0.25–0.5% risk/trade. Max 3 losses/day = stop.
- Day: 0.5–1% risk/trade. Max 2 trades/session.
- Swing: 0.5–1% risk/position. Max 3 concurrent swings.
- Prop-firm rules do NOT apply here. If you move to prop, halve risk and kill 1B (NY momentum) — DD limits murder it.

---

*Quant Tanvir stack. To the point. No repaint, no FOMO, no martingale.*

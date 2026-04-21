# quantforge-indicators

## Authors

 - https://willyalgotrader.pro/
 - https://chartprime.com/
 - https://bigbeluga.com/
 - https://www.luxalgo.com/
 - https://www.jackofalltrades.vip/
 - https://www.zeiierman.com/

## Indicators

### [Swing Profile \[BigBeluga\]](structure-aware-volume-profiling-per-swing.pine)
Builds a volume profile for each swing leg detected via ZigZag. Displays buy/sell volume distribution per bin, Point of Control (POC), and a heatmap mode. Tooltips show total/buy/sell/delta volume. Updates in real time as the current swing forms. Author: BigBeluga. License: CC BY-NC-SA 4.0.

### [DeltaPulse Wave \[ChartPrime\]](wave-chartprime-standardized-volume-delta-oscillator.pine)
Oscillator measuring relative delta strength — the balance of buy vs. sell volume as a percentage. Detects regular bullish/bearish divergences with configurable min gap. Includes a dashboard showing wave value, trend, and last divergence type. Author: ChartPrime. License: MPL 2.0.

### [StealthTrail SuperTrend ML Pro \[WillyAlgoTrader\]](supertrend-ml-pro-willyalgotrader.pine)
Adaptive SuperTrend with instrument profiling, regime classification (Trending / Ranging / Volatile), multi-timeframe confluence, a 13-feature ML scoring layer with self-learning gate adjustment, and a full TP/SL system (ATR / Band / Fixed %, trailing stop). Includes alerts, R:R display, and a detailed dashboard. Author: WillyAlgoTrader. Version: 5.1.0.

### [Clusters Volume Profile \[LuxAlgo\]](clusters-volume-profile-luxalgo-k-means-clustered-liquidity-zones.pine)
Groups the last N bars into K price clusters using volume-weighted K-Means, then draws a separate volume profile histogram for each cluster. POC per cluster is highlighted with a dashed line and volume labels. Author: LuxAlgo. License: CC BY-NC-SA 4.0.

### [Fair Value Gap Profile + Rolling POC \[BigBeluga\]](fvg-profile-rolling-poc-bigbeluga-fair-value-gap-heatmap-with-delta-volume.pine)
Scans historical bars for bullish and bearish Fair Value Gaps (FVGs), bins them by price level, and plots a dual-sided profile (bull vs. bear gap count per bin). Shows strength percentage, delta volume, and a smoothed Rolling POC line tracking the most active gap level. Optional heatmap background. Author: BigBeluga. License: CC BY-NC-SA 4.0.

### [Quantum Momentum Analyzer \[JOAT\]](quantum-momentum-analyzer-joat-multi-layer-rsi-with-regime-detection.pine)
Multi-layer RSI system with quantum phase modulation, volume-weighted RSI, and regime detection across 7 states (Extreme Bull → Extreme Bear). Detects regular and hidden divergences with strength scoring, momentum burst alerts, a momentum vortex particle visualization, and a comprehensive dashboard. Author: Jack of All Trades. License: MPL 2.0.

### [Smoothed Heiken Ashi Candles \[ChainSaffron\]](smoothed-heiken-ashi-chainsaffron-double-ema-noise-filter-with-trend-alerts.pine)
Double-smoothed Heikin Ashi candles: applies EMA to raw OHLC first, computes HA values, then applies a second EMA pass to reduce noise. Candles are colored lime/red by direction. Includes bullish/bearish flip alerts. Author: ChainSaffron.

### [Trading Activity Index \[Zeiierman\]](trading-activity-index-zeiierman-dollar-volume-heatmap-with-percentile-bands.pine)
Plots log-scaled dollar volume (price × volume) averaged over a formation window, with four rolling percentile bands (P20/P40/P60/P80) over a history window. The line color gradients from light blue (low activity) to orange-red (high activity) based on the current percentile rank. Author: Zeiierman. License: CC BY-NC-SA 4.0.

### [Volume by Time \[LuxAlgo\]](volume-by-time-luxalgo-intraday-volume-profile-with-historical-average.pine)
Intraday volume profile that groups volume by exact time-of-day (hour:minute:second) and computes a rolling average or median across historical sessions. Supports bi-directional display (bullish positive, bearish negative). Useful for identifying high- and low-activity time windows. Author: LuxAlgo. License: CC BY-NC-SA 4.0.

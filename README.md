# 📈 Multi-Pattern Candlestick-Based Buy/Sell Signal Indicator for TradingView

This TradingView Pine Script project provides a robust **multi-pattern candlestick indicator** that dynamically identifies potential **buy/sell signals**, **entry breakout points**, and **stop-loss triggers** based on well-known candlestick reversal patterns. It features two independent signal systems with clear visual cues (including custom Hindi tags like _"उड़ाओ"_ and _"गिराओ"_ for intuitive trade triggers).

---

## ✨ Features

- 📊 **Candlestick Pattern Detection**:
  - Bullish: Engulfing, Harami, Hammer, Piercing
  - Bearish: Engulfing, Harami, Inverted Hammer, Dark Cloud Cover

- 🧠 **Dual Indicator Systems**:
  - `Indicator 1`: Breakout-based confirmation with conditionally plotted buy/sell markers.
  - `Indicator 2`: Lighter version with instant signal plotting based on pattern detection.

- 🔔 **Dynamic Breakout & Stop-Loss Lines**:
  - Entry break levels and stop-loss points auto-adjust based on recent price action.

- 🟢🔴 **Signal Visuals**:
  - 'B' for bullish entries, 'S' for bearish entries.
  - "उड़ाओ" (Fly/Buy) and "गिराओ" (Drop/Sell) labels on breakout confirmation.
  - 'SL' label marks stop-loss triggers visually.

- ⏰ **3 PM Exit Marker (Optional)**:
  - Optional logic (commented out) to mark 3 PM candles for EOD exit consideration.

---

## 📌 How it Works

### Signal Logic

- **Up Move Logic** (Buy):
  - Pattern like Bullish Engulfing forms near PD Low/Close or Current Day Low.
  - Breaks above pattern high triggers `"उड़ाओ"` label and long bias.
  - Stop-loss placed slightly below pattern low.

- **Down Move Logic** (Sell):
  - Pattern like Bearish Engulfing forms near PD High/Close or Current Day High.
  - Breaks below pattern low triggers `"गिराओ"` label and short bias.
  - Stop-loss placed slightly above pattern high.

### Dual Indicator Mode

- `Indicator 1`: Conservative breakout-based logic.
- `Indicator 2`: Aggressive instant pattern signal plotting.
- Users can toggle either indicator or both via input flags.

---

## 📷 Screenshot

![Signal Preview](https://raw.githubusercontent.com/Avin-Chaudhary/YourRepoName/main/screenshots/signal-preview.png)

> _Replace the above URL with the actual screenshot path after uploading to your repo._

---

## 🛠️ Setup Instructions

1. Copy and paste the full Pine Script code into [TradingView Pine Editor](https://tradingview.com).
2. Add the indicator to your chart.
3. Enable/disable indicator-1 or indicator-2 using the toggle inputs.
4. (Optional) Adjust logic, time filters, or SL levels as per your strategy.

---

## 💡 Use Cases

- Short-term intraday signal confirmation
- Educational tool for learning price action-based reversals
- Visual aid for support/resistance breakout traders
- Resume/portfolio showcase for Pine Script skill

---

## 🧠 Author

**Avin Chaudhary**  
3rd Year Tech Enthusiast | Frontend Developer  
National Institute of Technology, Kurukshetra (IT '27)  
🔗 [LinkedIn](https://www.linkedin.com/in/avin-chaudhary/) | [GitHub](https://github.com/Avin-Chaudhary)

---

## 📄 License

This project is open-source and free to use under the MIT License.

---


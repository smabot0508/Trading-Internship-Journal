# Day 8 Internship Notes
**Date:** 09-06-2026

## Work Start Time
9:00 AM

---

# Today's Objective

- Liquidity Sweeps
- Liquidity & Market Imbalance
- Institutional Fake Breakouts
- DeepVue Moving Average Indicator

---

# Topics Learned Today

## Topic 1: Liquidity Sweeps

Today I learned about **Liquidity Sweeps**, also known as **Liquidity Grabs** or **Liquidity Hunts**.

**What is "Liquidity" in this context?**
Liquidity refers to the pool of pending orders sitting in the market at a given price — things like stop-loss orders, buy limit orders, and sell limit orders that are waiting to be triggered. Every one of these pending orders represents a trade that hasn't happened yet, but *will* happen the moment price touches that level.

**Why do institutions need liquidity?**
Large institutions (banks, hedge funds, market makers) need to fill very large positions — far larger than the average retail order. If they tried to buy or sell that size directly at the current price, they would move the market against themselves before their order was even filled. So instead, institutions look for zones where a large number of pending orders are already sitting, because those pending orders act as the "other side" of the trade they need to fill.

**How a liquidity sweep works, step by step:**
1. Price approaches an obvious support or resistance level (one that retail traders can clearly see on their charts).
2. Institutions push price slightly beyond that level, creating what looks like a genuine breakout.
3. Retail traders, believing a new trend has started, enter the market in the direction of the "breakout." Their stop-loss orders begin to stack up just behind the level.
4. Once enough orders (liquidity) have accumulated, the institutions execute their real position using that liquidity.
5. Price then reverses sharply, moving back in the opposite direction — trapping the retail traders who entered the fake breakout.

This is why a liquidity sweep is often followed by a strong, fast move in the *opposite* direction of the initial breakout.

**Diagram — Liquidity Sweep:**

![Diagram of a liquidity sweep: price forms equal highs, sweeps the liquidity pool above resistance, then reverses sharply lower](day8-liquidity-sweep-diagram.svg)

*Price builds equal highs, tagging the same resistance twice. A final push spikes into the liquidity pool sitting just above that level (triggering the resting buy-stops/sell-limit orders), then reverses hard once those orders are filled.*

---

## Types of Liquidity Pools

A **liquidity pool** is simply an area on the chart where a cluster of pending stop-loss or limit orders is likely sitting. Below are the main types I learned about:

### Swing Liquidity
Liquidity that builds up just above **swing highs** (recent peaks) and just below **swing lows** (recent troughs). Traders who bought near a swing low place stops just below it; traders who shorted near a swing high place stops just above it. These clusters make swing points attractive targets for institutions.

### Equal Highs (EQH)
When price touches the same resistance level two or more times without breaking through, it creates **equal highs**. Retail traders see this as a strong resistance zone and place sell-stop or short-entry orders just above it — creating a dense liquidity pool right above the equal highs.

### Equal Lows (EQL)
The mirror image of equal highs. When price touches the same support level multiple times, it forms **equal lows**, and buy-stop/long-entry orders accumulate just below that level.

### Range Liquidity
When a stock trades sideways in a **consolidation range**, liquidity builds up at both the top and bottom boundaries of that range, as breakout traders place orders on either side waiting for price to escape the range.

> **Key idea:** Institutions frequently target these exact locations (swing points, equal highs/lows, and range boundaries) right before they trigger a real reversal, because that's where the most liquidity is sitting.

---

## Topic 2: Combining Liquidity Sweeps with Market Imbalance (Fair Value Gaps)

I learned that a liquidity sweep becomes a much more reliable trading signal when it lines up with a **Market Imbalance**, also called a **Fair Value Gap (FVG)**.

**What is a Market Imbalance / Fair Value Gap?**
An imbalance happens when price moves so aggressively in one direction that buyers and sellers don't get a fair chance to trade at every price level in between. This leaves a visible "gap" on the chart — a zone with very few or no orders filled — which shows up as a three-candle pattern where the wick of the first candle and the wick of the third candle don't overlap. Because so few orders were filled inside that zone, price tends to be pulled back into it later, almost like a magnet, so the market can "fill in" the orders it skipped.

**FVG Validity Checklist (rules I learned to identify a *high-quality* FVG):**
1. **Unmitigated** – The FVG must not have been touched or re-tested since it was created. Once price has already returned into the gap once, it's considered "mitigated" and loses much of its strength.
2. **Candle Close Confirmation** – A strong signal is when a candle actually **closes** inside the FVG (not just wicks into it), confirming that sellers/buyers are stepping back in at that zone.
3. **Support/Resistance Confluence** – An FVG that lines up with a pre-existing support or resistance level is far more powerful than one sitting in open air, because it has two forms of confirmation instead of one.
4. **Priority Between Multiple FVGs** – If more than one FVG exists on the chart, they need to be ranked, not treated equally — the most recent and most well-formed one usually takes priority.
5. **Discount (Strength of the Gap)** – When several FVGs are present, price tends to favor trading toward the *larger* or "stronger" FVG first, since it represents a bigger imbalance and a bigger magnet for price.
6. **Break of Structure (BOS) Requirement** – Before trusting an FVG, check that a genuine **Break of Structure** occurred just before the FVG formed. A BOS confirms that the imbalance was created during a real shift in market direction, not just random volatility.

**The High-Probability Setup (Liquidity Sweep + FVG):**
- A liquidity pool exists (swing point, EQH/EQL, or range boundary).
- An FVG/imbalance lines up with that same liquidity area.
- Price sweeps the liquidity (the fake breakout / stop hunt happens).
- A reversal candlestick confirms rejection at that zone.

When all four of these conditions line up, it gives multiple layers of confirmation and significantly improves trade accuracy, because the trader isn't relying on just one signal — they're relying on liquidity, imbalance, and price action all agreeing at the same time.

**Diagram — Combining Liquidity Sweep with Market Imbalance (FVG):**

![Diagram combining a liquidity sweep with a Fair Value Gap: support liquidity is swept, an impulsive Break of Structure creates an FVG, price retraces into the FVG, then continues toward the target](day8-liquidity-sweep-fvg-combo-diagram.svg)

*Price sweeps the liquidity pool resting below equal lows, then reverses with an impulsive candle that both breaks structure and leaves behind an FVG. Price later retraces into that FVG (a lower-risk confirmation entry) before continuing on toward the target.*

**Chart Example — FVG / Market Imbalance on SPX:**

![FVG and Market Imbalance example on SPX 5-minute chart, showing Break of Structure, the FVG zone, and Support level](day8-fvg-market-imbalance.png)

*In the chart above, a Break of Structure occurs first, immediately followed by a large aggressive candle that creates the FVG (purple box). Price later returns to test this FVG, which also lines up with a horizontal Support level — exactly the kind of confluence described in the checklist above.*

---

## Topic 3: Institutional Fake Breakouts

Institutions deliberately create **fake breakouts** to attract retail participation and generate the liquidity they need. This is closely related to liquidity sweeps, but focuses specifically on how the "trap" is engineered around key levels.

**Step-by-step process:**
1. Institutions push price beyond a key support/resistance level, just far enough to look like a real breakout.
2. Retail traders, seeing the breakout, enter positions in the breakout direction.
3. Stop-loss orders from traders who were already positioned the other way begin to accumulate near that level.
4. Institutions use this accumulated liquidity to fill their own large orders.
5. Price then reverses sharply in the opposite direction, moving against the retail traders who just entered — trapping them in a losing position.

**Key takeaway:** Many "failed breakouts" that retail traders blame on bad luck are not random at all — they are liquidity sweeps deliberately engineered by institutions to fill large orders before reversing the market.

---

## Topic 4: DeepVue Moving Average Indicator

Today I explored the **DeepVue Key Moving Averages Indicator** on TradingView.

**What problem does it solve?**
Normally, if a trader wants to see, for example, the daily 50-period moving average while looking at an hourly chart, they would have to manually recalculate the equivalent period for that timeframe. This is time-consuming and error-prone. The DeepVue indicator solves this by automatically displaying the correct moving average values from other timeframes directly on the chart you're currently viewing — no manual conversion needed.

**Types of moving averages it supports:**
- **Simple Moving Average (SMA):** The average closing price over a set number of periods, with every period weighted equally. Good for identifying the overall trend direction in a smooth, simple way.
- **Exponential Moving Average (EMA):** Similar to SMA, but gives more weight to recent price action, so it reacts faster to new price changes. Useful for catching trend shifts earlier than an SMA would.

**Timeframes supported:**
- Intraday (e.g., 5-minute, 15-minute, 1-hour)
- Daily
- Weekly
- Monthly

**Why this matters for trading:**
By displaying key moving averages such as the **21 EMA, 50 SMA, 150 SMA, and 200 SMA** all on one chart, a trader can quickly judge:
- **Trend direction** – is price above or below the major averages?
- **Support/Resistance** – are these averages acting as dynamic support or resistance?
- **Trend strength** – how far is price stretched away from its average (is it likely to pull back)?
- **Potential reversal zones** – is price approaching a major average it hasn't tested in a while?

**Chart Example — DeepVue Moving Averages on NVDA (Daily):**

![DeepVue Key Moving Averages indicator applied to NVDA daily chart, alongside a Relative Measured Volatility indicator used to spot liquidity sweep conditions](day8-deepvue-liquidity-sweep.png)

*This NVDA daily chart shows the DeepVue Key Moving Averages (21 EMA, 50 SMA, 200 SMA lines) plotted together with the Relative Measured Volatility (RMV) indicator below. Sharp spikes in RMV often line up with the volatility bursts that occur during a liquidity sweep, making it a useful secondary confirmation tool when combined with the moving averages and FVG concepts above.*

---

# Practice

## Liquidity Sweep Analysis Practice

During today's practice session, I reviewed charts containing swing highs, swing lows, equal highs, and equal lows.

The exercise involved:
- Identifying liquidity pools.
- Observing fake breakouts.
- Finding liquidity sweeps.
- Monitoring reversal behavior.
- Studying institutional activity.

This helped me understand how institutions use liquidity to execute large positions.

---

# DeepVue Practice – Moving Average Indicator

During today's practical session, I explored the DeepVue Key Moving Averages Indicator and learned how it simplifies multi-timeframe trend analysis. I analyzed NVIDIA (NVDA) using the indicator and observed how multiple moving averages were displayed on a single chart. I learned how traders can monitor the relationship between price and important moving averages such as the 21 EMA, 50 SMA, 150 SMA, and 200 SMA to evaluate trend direction and market strength.

I also observed how the indicator automatically adjusts moving average calculations across different chart timeframes, eliminating the need for manual calculations. This allowed me to focus more on trend analysis and less on indicator setup. Through this practice, I gained a better understanding of how professional traders use moving averages to identify support, resistance, trend continuation, and potential reversal opportunities.

---

# Questions I Had and Answers I Got

## Q1. What is a liquidity sweep?
A liquidity sweep occurs when price intentionally moves beyond a key support or resistance level to trigger pending orders before reversing direction. Institutions use these areas to access the liquidity required for large positions.

## Q2. Why do institutions create fake breakouts?
Institutions create fake breakouts to attract retail traders into the market and generate liquidity. Once enough orders are available, they execute their positions and often reverse the market direction.

## Q3. How does the DeepVue Moving Average Indicator help traders?
The indicator allows traders to view multiple moving averages from different timeframes on a single chart. This simplifies trend analysis and improves decision-making across various trading timeframes.

## Q4. What makes a Fair Value Gap (FVG) high-probability rather than just any random gap?
An FVG becomes high-probability when it is unmitigated (untested since forming), gets a full candle close inside it, lines up with existing support/resistance, forms after a genuine Break of Structure, and — when multiple FVGs exist — is the strongest/largest of them.

---

# Key Takeaways From Day 8

- Liquidity sweeps target retail stop-losses sitting above/below swing highs, swing lows, equal highs/lows, and range boundaries.
- Institutions require liquidity to execute large trades without moving the market against themselves.
- Fake breakouts are often institutional traps designed to generate that liquidity.
- Fair Value Gaps (market imbalances) provide additional trade confirmation, especially when unmitigated and aligned with support/resistance.
- Moving averages (SMA/EMA) help identify trend direction, strength, and dynamic support/resistance.
- The DeepVue Moving Average Indicator simplifies multi-timeframe analysis by displaying the correct averages automatically.

---

# Conclusion

Day 8 focused on understanding institutional market behavior through liquidity sweeps and fake breakouts. I learned how institutions generate liquidity, how imbalances (FVGs) improve trade accuracy when combined with liquidity sweeps, and how the DeepVue Moving Average Indicator simplifies trend analysis across timeframes. These concepts improved my understanding of market structure, institutional activity, and professional trading workflows.

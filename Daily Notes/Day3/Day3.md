# Day 3 Internship Notes
 
**Date:** 03-06-2026
 
## Work Start Time
 
9:00 AM
 
---
 
# Today's Objective
 
- Learn candlestick patterns in detail.
- Understand Support and Resistance in depth.
- Analyze market trends using DeepVue's 21 EMA Strategy.
---
 
# Topic 1: Candlestick Patterns
 
Candlestick patterns are visual representations of price action that help traders understand the ongoing battle between buyers and sellers during a specific time frame. Every single candle — regardless of which timeframe it's drawn on — is built from exactly four values: **open, close, high, and low price**. Reading these patterns correctly is how a trader identifies potential **reversals** (the trend changing direction), **trend continuation** (the existing trend strengthening), and overall **market sentiment** (whether buyers or sellers are currently in control).
 
As a quick refresher tying back to Day 1: **green candles generally indicate buyer strength** (close finished higher than open), while **red candles represent seller dominance** (close finished lower than open). **Large candles indicate strong momentum** — a big, decisive move in one direction — whereas **long wicks show rejection** of a particular price level, meaning price tried to go further but was pushed back.
 
> <p align="center"><img src="Images/" width="700"></p>
> <p align="center"><img src="Images/" width="700"></p>
 
## Bullish Reversal Patterns
 
Bullish reversal patterns suggest that buyers are gaining control and the market may move upward after a period of decline.
 
**Hammer**
A hammer has a small body with a long lower wick. The long lower wick is the key story here: it shows that sellers initially pushed the price down hard during the period, but buyers stepped in with enough strength to push the price back upward before the candle closed — meaning the close ends up much higher than the low. This pattern becomes meaningfully stronger when it forms near an existing support level, since it suggests buyers are defending a level they've defended before.
 
**Bullish Engulfing**
This is a two-candle pattern where a large green candle completely "engulfs" — meaning its body fully covers — the previous red candle's body. Because the second candle's range is so much larger and moves in the opposite direction of the first, it indicates a sudden and strong shift in buying pressure, often marking a possible bullish reversal.
 
**Tweezer Bottom**
This pattern consists of a red candle followed by a green candle, where both candles have very similar lower wicks (i.e., they both touched roughly the same low price before reversing). This matching low shows that the same support area is being respected twice in a row, reinforcing that buyers are actively defending that price level.
 
**Dragonfly Doji**
This pattern has a long lower wick with the opening and closing prices landing near the same level (hence "Doji" — meaning indecision). It represents a clear rejection of lower prices within that single candle — sellers tried to push price down, but by the close, buyers had pulled it almost all the way back to where it opened, showing underlying buyer strength.
 
> 🖼️ **[Add Image Here — BULLISH REVERSAL PATTERNS]** — A focused image showing the four bullish patterns above, ideally pulled from a real chart example or a clean labeled diagram. Suggested file: `images/day3/bullish-reversal-patterns.png`
 
## Bearish Reversal Patterns
 
Bearish reversal patterns indicate that sellers are taking control and the market may move downward after a period of advance.
 
**Shooting Star**
A shooting star has a small body with a long upper wick — the mirror image of a hammer. It shows that buyers pushed the price upward during the period, but sellers forced the price back down before the candle closed, leaving a long wick above a small body near the bottom of the candle's range.
 
**Bearish Engulfing**
This pattern occurs when a large red candle completely engulfs the body of the previous green candle, indicating that seller dominance has suddenly and decisively taken over from the prior buying activity.
 
**Tweezer Top**
A green candle followed by a red candle, where both candles have matching upper wicks (both touched roughly the same high before reversing). This indicates strong resistance at that level and a clear rejection of higher prices, repeated twice in a row.
 
> 🖼️ **[Add Image Here — BEARISH REVERSAL PATTERNS]** — A focused image showing the three bearish patterns above. Suggested file: `images/day3/bearish-reversal-patterns.png`
 
## Momentum and Continuation Patterns
 
These patterns don't necessarily signal a reversal — instead, they tell you something about the *strength* of the current move, or help confirm an existing support/resistance zone.
 
**Momentum Candle**
A momentum candle is significantly larger than the candles immediately before it, and it usually signals strong buying or selling activity entering the market all at once. In sideways, range-bound markets, a sudden momentum candle often marks the *beginning* of a brand-new trend, since it shows one side has finally overwhelmed the other after a period of balance.
 
**Marubozu Candle**
A Marubozu candle has a large body with **no wicks at all** (or barely visible ones). The absence of wicks is the important detail — it means that whichever side was in control (buyers or sellers) stayed in complete control from the very first trade of the period to the very last, without ever being meaningfully pushed back.
 
**Multiple Candle Confirmation**
When multiple separate candles repeatedly reject the same price area using their wicks (touching that level but failing to close beyond it, again and again), it strengthens the reliability of that support or resistance zone. Essentially, this is "voting" — the more times price tests a level and fails to break it, the more confidently that level can be trusted going forward.
 
> 🖼️ **[Add Image Here — MOMENTUM AND CONTINUATION PATTERNS]** — An image showing a Momentum candle next to a Marubozu candle, plus an example of multiple wick rejections at the same level on a real chart. Suggested file: `images/day3/momentum-continuation-patterns.png`
 
---
 
# Topic 2: Support and Resistance
 
Support and resistance are foundational concepts in technical analysis, representing the key price levels where market behavior tends to change.
 
- **Support** acts like a floor where buying pressure becomes strong enough to stop price from falling further.
- **Resistance** acts like a ceiling where selling pressure becomes strong enough to stop price from moving higher.
These levels matter because traders react **emotionally** around them — they aren't just mathematical lines, they are psychological zones where large numbers of market participants have previously made buy or sell decisions, and tend to repeat similar decisions when price returns there.
 
## Role Reversal Principle
 
One of the most important concepts learned today was the **Role Reversal Principle**:
 
- **Broken support often becomes new resistance.**
- **Broken resistance often becomes new support.**
**Why this actually happens (the psychology behind it):** Imagine a group of traders bought a stock at a support level, expecting it to bounce. If price instead breaks *below* that support, those traders are now sitting on a loss. When price later rallies back up toward that old support level, many of those trapped traders will sell — not because they're confident the price will fall again, but simply to "get out even" and recover their original entry price. This wave of selling from previously trapped buyers is exactly what turns old support into new resistance. The same logic works in reverse for broken resistance becoming new support.
 
> 🖼️ **[Add Image Here — SUPPORT AND RESISTANCE]** — A chart example showing a level that was first respected as support, broken downward, and then rejected as resistance on a later retest (the classic Role Reversal visual). Suggested file: `images/day3/support-resistance-role-reversal.png`
 
## Drawing Support and Resistance
 
Support and resistance should be treated as **zones, not exact lines** — price rarely respects a level down to the exact cent, so drawing a thin band around a level (rather than one precise horizontal line) gives a more realistic picture.
 
**In Range Markets:** The major highs and lows of the trading range are used to identify the key support and resistance zones. The **"Most Touches Rule"** states that a level becomes statistically stronger and more reliable the more times price has reacted off that exact same area in the past.
 
**In Trending Markets:** Recent swing highs and swing lows are used instead, to identify likely pullback areas (where a trend might pause and continue) and trend continuation zones.
 
**A practical caution:** Minor, less significant levels should generally be avoided when marking up a chart, because too many overlapping lines create visual clutter and confusion, ultimately leading to poor trade decisions. It's better to mark fewer, high-conviction zones than many weak ones.
 
---
 
# Topic 3: Analyze Market Trends Like a Pro — The 21 EMA Strategy (DeepVue Tutorial)
 
The **21 EMA (Exponential Moving Average) Strategy** is used to identify market trends and manage trading risk at the same time — it's as much a risk-management rule as it is a trend-following tool. The strategy helps traders determine whether current market conditions are favorable (worth taking more trades) or weak (worth pulling back).
 
**What makes an EMA different from a simple moving average (SMA):** A simple moving average weighs every past price equally when calculating the average. An *exponential* moving average instead gives **more weight to recent prices**, which makes it react faster to new price movement. This is exactly why the 21 EMA is preferred here over a plain 21-period SMA — it picks up on fresh momentum shifts more quickly, which matters for timely trend identification.
 
**The core idea of the strategy is simple to state, but powerful in practice:**
 
- **Be aggressive during strong trends.**
- **Be defensive during weak market conditions.**
## Aggressive and Defensive Phases
 
**Aggressive Phase:** When price remains above a *rising* 21 EMA, it indicates a healthy uptrend with strong underlying momentum. During this phase, traders can take more swing trading opportunities with greater confidence, since the broader trend structure is actively supporting upward moves.
 
**Defensive Phase:** When price moves below a *declining* 21 EMA, it signals weak or deteriorating market conditions. During this phase, the correct response is to reduce risk, avoid unnecessary or forced trades, and maintain a larger cash position rather than staying fully invested. This approach is specifically designed to protect capital during market corrections, rather than trying to "catch a falling knife."
 
## Trend Identification
 
A new uptrend is typically identified through this specific sequence:
 
1. The previously declining 21 EMA starts **flattening out** (losing its downward slope).
2. **Price breaks above** the EMA line.
3. **Momentum increases** in the new direction.
This three-step sequence often marks the genuine beginning of a strong new trending move, as opposed to just a temporary, short-lived bounce that fails and rolls back over.
 
## Practice: DeepVue Platform Implementation
 
The DeepVue platform was used to practically implement the 21 EMA strategy on a real, live stock chart. The platform helped with:
 
- Identifying trends
- Observing market cycles
- Understanding bullish and bearish phases
- Analyzing pullback opportunities
### My 21 EMA Chart Practice — NVDA
 
Below is the actual chart I used to practice this strategy, applied to **NVIDIA (NVDA)** on the Daily timeframe inside DeepVue.
 
> 🖼️ **[Add Image Here — 21EMA IMAGE PROVIDED]** — This is your own DeepVue screenshot of NVDA with the 21 EMA plotted (the one you've already provided). Suggested file: `images/day3/nvda-21ema-practice.png`
 
**Reading the chart in the screenshot, applying today's framework:**
 
- The chart shows **NVDA on the 1D (Daily) timeframe**, with the **Exponential Moving Average (21)** plotted as the blue line, currently reading **215.49**.
- Price (last close **222.82**, pre-market **223.74**) is sitting **above** the rising 21 EMA — by today's rule, this places NVDA in the **Aggressive Phase**, suggesting the broader trend structure is currently healthy enough to consider swing trade opportunities with more confidence.
- The **DV – Stage Analysis** bar at the very top of the chart shows mostly green, reinforcing that this stock has spent most of the recent period in a constructive stage (this connects directly to the Stage Analysis framework from Day 4).
- The **RSI (Relative Strength Index)** panel below the price chart reads **58.79** — comfortably in the neutral-to-bullish zone (not yet overbought above 70), which supports the idea that there's still room for the uptrend to continue without being immediately "stretched."
- The **DV – Net New Highs/Lows** histogram at the bottom is mostly blue (positive) across the period shown, which reflects broad participation — more stocks within NVDA's universe/sector were making new highs than new lows for much of this window, adding confidence to the bullish read.
This practical example is exactly how the 21 EMA strategy is meant to be used: not in isolation, but read together with stage analysis and RSI to build one consistent picture of trend health.
 
Practical implementation like this helped improve my understanding of trend analysis and real market behavior, rather than just memorizing the rule in the abstract.
 
---
 
# Questions I Had
 
1. Why does the Role Reversal Principle actually work — why would broken support really turn into resistance?
2. Why is the 21 EMA preferred over a simple moving average for this strategy?
3. If I had **$50** to invest, how would I decide what trade to take, and what Risk:Reward would I target?
---
 
# Answers (With Detailed Reasoning)
 
**1. Why does the Role Reversal Principle actually work?**
 
This comes down to trader psychology rather than any mathematical rule. When support breaks, the traders who bought near that level are now holding a losing position. When price later rallies back up to that same old support level, those trapped traders frequently sell to exit at breakeven rather than risk a deeper loss. This wave of selling pressure is exactly what turns the old support into new resistance. The same psychology works in mirror image for broken resistance becoming new support — traders who shorted near the old resistance look to cover (buy back) their position when price returns there, creating fresh buying pressure.
 
**2. Why is the 21 EMA preferred over a simple moving average for this strategy?**
 
A Simple Moving Average (SMA) treats every price in its lookback period with equal importance — a price from 20 days ago counts exactly the same as yesterday's price. An Exponential Moving Average (EMA) instead applies more weighting to the most recent prices, which makes it more responsive to new momentum shifts. For a strategy that's specifically trying to catch the *early* signs of a trend changing (the flattening-then-breaking sequence described above), this faster responsiveness is valuable — an SMA would likely lag behind and confirm the trend change later, after more of the move has already happened.
 
**3. If I had $50 to invest, how would I decide what trade to take, and what Risk:Reward would I target?**
 
With a small amount like $50, the very first consideration is practical, not technical: most full shares of strong, liquid stocks (like the mega-cap names I've been studying, e.g. NVDA) cost well over $50 each, so a real $50 trade would likely require a fractional-share investing platform. Setting that aside and focusing purely on the *decision process* I've learned so far:
 
- I would only consider a stock that is in an **Aggressive Phase** under the 21 EMA strategy — price trading above a rising 21 EMA — since this signals the broader trend is currently healthy.
- I would look for the **entry point to sit near a support zone** (ideally one confirmed by the Most Touches Rule), since that gives a logical, nearby level to place a stop loss.
- I would set my **stop loss just below that support zone** — if price breaks below it, the original reason for the trade is no longer valid, so the trade should be closed.
- I would set my **take-profit target at the next meaningful resistance zone** above current price.
- I would only take the trade if the resulting **Risk:Reward ratio was at least 1:2** — meaning the distance from entry to target is at least twice the distance from entry to stop loss. For example, risking $1 per share to potentially make $2 or more per share.
With only $50 total, the position size is too small to meaningfully test this process in a real account, and I'm not in a position to recommend a specific live stock or price level as financial advice — but the *decision-making framework* above is exactly what I'd apply regardless of account size, scaling the same logic up as the account grows.
 
---
 
# Key Takeaways From Day 3
 
- Candlestick patterns reveal the real-time battle between buyers and sellers, and are split into bullish reversal, bearish reversal, and momentum/continuation categories.
- A pattern's reliability increases significantly when it forms at an existing support or resistance zone, rather than in the middle of nowhere on the chart.
- Support and Resistance should be drawn as zones, not exact lines, and the Most Touches Rule helps rank which zones are strongest.
- The Role Reversal Principle — broken support becomes resistance, and vice versa — is driven by trapped-trader psychology, not just chart geometry.
- The 21 EMA Strategy combines trend identification with risk management: be aggressive above a rising EMA, defensive below a declining one.
- Practicing the 21 EMA strategy live on NVDA connected the theory directly to a real chart, including cross-checking it against Stage Analysis and RSI for a fuller picture.
- When sizing any trade — even a small $50 example — the Risk:Reward ratio (ideally 1:2 or better) is the non-negotiable filter before entering.
---
 
# Conclusion
 
Day 3 of the internship mainly focused on understanding technical analysis and market psychology through candlestick patterns, support and resistance, and the 21 EMA strategy. The practical chart analysis performed using TradingView and DeepVue helped connect theoretical concepts with real market movement — particularly applying the 21 EMA strategy to a live NVDA chart and cross-referencing it with Stage Analysis and RSI. The session improved my understanding of trend analysis, price action, confirmation signals, and disciplined trading behavior, including how to think through position sizing and Risk:Reward even on a very small hypothetical account.

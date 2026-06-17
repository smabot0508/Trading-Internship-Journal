# Day 15 Internship Notes
 
**Date:** 17-06-2026
 
## Work Start Time
 
9:00 AM
 
---
 
# Today's Objective
 
- Understand Premium and Discount Zones and how they prevent buying too high or selling too low
- Revisit Market Structure and how it integrates with Premium and Discount
- Understand Supply and Demand zones and how to filter them using Premium/Discount
- Learn the TradingView tools used to apply this concept (Fibonacci tool + Bar Replay)
- Understand the Equilibrium Level as the anchor of the entire concept
---
 
# Topics Learned Today
 
## Topic 1: Premium and Discount
 
Understanding Premium and Discount helps prevent the common trap of buying too high or selling too low. It is a basic pricing principle that helps traders determine when an asset is relatively expensive or cheap within a specific price range, allowing for far more precise entries.
 
### The Core Concept
 
A specific price range is divided in half at the **50% equilibrium level**:
 
- **Premium Zone:** The area above the 50% equilibrium level. Price here is relatively expensive, there is typically more supply, and institutional traders look to sell or take short positions.
- **Discount Zone:** The area below the 50% equilibrium level. Price here is relatively cheap, creating demand, and traders should ideally look to buy or take long positions.
### How to Apply This to a Chart — 3 Steps
 
1. **Identify the market structure:** Determine the trend by finding a bullish or bearish break of structure.
2. **Identify the swing range:** Locate the specific swing high and swing low that form this structural range.
3. **Draw the tool:** Use a customized Fibonacci retracement tool to connect the swing low and swing high, visually splitting the chart into premium and discount territories.
### Combining with Supply and Demand
 
- **In a Bullish Market (Uptrend):** Wait for price to pull back below the 50% mark into the discount zone and mitigate a demand zone before buying. Entering long at demand zones still sitting in the premium area is premature, and those zones are highly likely to fail.
- **In a Bearish Market (Downtrend):** Wait for price to push up above the 50% mark into the premium zone and mitigate a supply zone before selling. Shorting at supply zones located within the discount area is generally too early, since price still has room to pull back higher.
### The Power of Extreme Zones
 
When multiple supply or demand zones exist within the correct half of the range, the **extreme zones** — those located furthest into the premium or discount areas — have the highest probability of holding. This is because extreme zones sit at the origin of the swing range; if an extreme zone fails, current market structure breaks and the entire trend direction shifts.
 
This concept is highly versatile and applies across all asset classes and all timeframes — from daily charts predicting multi-day moves to 5-minute charts predicting short-term fluctuations. Traders must manage expectations based on the timeframe used and always combine the tool with market structure context.
 
---
 
## Topic 2: Market Structure (Revisited in Context of Premium/Discount)
 
Market structure is the foundation for determining the overall trend direction of an asset by analyzing the sequence of swing highs and swing lows. Identifying this structure is the crucial first step before applying any pricing tool or looking for trade entries.
 
### Bullish vs. Bearish Structure
 
- **Bullish structure (uptrend):** A series of higher highs and higher lows. The defining rule is that the previous low must hold for the uptrend to remain intact. Traders look for a "bullish break of structure" — price pushing past a previous high — and then anticipate a pullback to form a new higher low before continuing upward.
- **Bearish structure (downtrend):** A series of lower highs and lower lows. For the bearish trend to survive, the previous lower high must hold. If price pushes up and takes out that last lower high, it triggers a market shift — signaling the trend is changing from bearish to bullish as buyers take control.
### Integrating Market Structure with Premium and Discount
 
The Premium and Discount tool cannot be effectively used without first identifying market structure. The process always follows this order:
 
1. **Identify the structure** — bullish or bearish break of structure.
2. **Find the range** — pinpoint the exact swing low and swing high that created that structural break.
3. **Apply the zones** — drag the Premium and Discount tool across that specific swing range to find where price is cheap or expensive.
This also explains why extreme supply and demand zones matter so much: an extreme demand zone sits at the very bottom (swing low) of a bullish structure, and an extreme supply zone sits at the very top (swing high) of a bearish structure. Because market structure dictates these origin points must hold to maintain the trend, these extreme zones offer the highest probability for a successful trade.
 
---
 
## Topic 3: Supply and Demand
 
Supply and Demand zones represent specific areas on a chart where significant buying or selling pressure previously originated. Identifying these zones helps traders anticipate where price is likely to react in the future.
 
- A **supply zone** is created at the origin point of a drastic, imbalanced move to the downside — where sellers took control.
- A **demand zone** is formed at the origin of a strong move to the upside — where buyers stepped in.
### How to Draw the Zones
 
| Method | Description |
|---|---|
| **Range Method** | Identify a small consolidation block or range just before price strongly breaks out |
| **Pivot Method** | A more precise approach — draw the zone exclusively around the specific reversal/pivot candle that sparked the move |
 
### How to Trade Supply and Demand
 
The fundamental rule: buy at demand zones during an uptrend (bullish structure), and sell at supply zones during a downtrend (bearish structure). The goal is to patiently wait for price to pull back and "mitigate" — tap into — these existing zones before looking for a trade entry.
 
### Filtering Zones Using Premium and Discount
 
Finding a zone is easy — knowing whether that zone sits in a high-probability area is what separates average traders from precise ones.
 
| Zone Quality | Description |
|---|---|
| **High-Quality** | A demand zone within a discount range, or a supply zone within a premium range — strong areas |
| **Low-Quality** | A demand zone within premium pricing, or a supply zone within discount pricing — price will likely "blast right through" these |
 
### The Importance of Extreme Zones
 
It's common to find multiple supply or demand zones within a single swing range. The extreme zones — located deepest into premium or discount territory at the very start of the swing — have the highest probability of holding. This ties directly back to market structure: because extreme zones sit at the absolute swing high or swing low, they must hold for the current trend to remain intact. If price breaks through an extreme zone, it triggers a market shift, signaling the entire trend direction is changing.
 
---
 
## Topic 4: TradingView Tools (Fibonacci Retracement + Bar Replay)
 
### 1. The Fibonacci Retracement Tool (Customized for Premium and Discount)
 
The primary tool used is the Fibonacci ("Fib") retracement tool, repurposed into a Premium and Discount tool.
 
- **Customization:** By default, the Fib tool in TradingView displays multiple levels and looks visually cluttered. Double-click the tool to modify its settings so it specifically highlights only the 50% equilibrium level, effectively splitting it into a top half and a bottom half.
- **Application:** First identify a market structure and its swing range, then click and drag the tool across that range, connecting the swing low to the swing high. The direction you drag it (high-to-low or low-to-high) does not matter — it yields the same visual result.
- **Function:** Once applied, the tool acts as an immediate visual guide, clearly separating the chart into premium pricing (above 50%, expensive) and discount pricing (below 50%, cheap). This allows quick determination of whether a trade entry is high-probability based on which half of the range price is sitting in.
### 2. The Bar Replay Tool
 
A feature used for practice and backtesting. Activating Bar Replay lets a trader go back to a random point in time on historical charts, erasing future price action. This allows practicing analysis on blank charts — determining market structure and applying the Premium and Discount tool step-by-step as if the market were live.
 
---
 
## Topic 5: Equilibrium Level
 
The equilibrium level is the exact 50% mark, or middle line, of a specific price range. It is the vital dividing line that anchors the entire Premium and Discount concept, visually splitting a chart into two distinct halves.
 
### How It Functions
 
- **The Defining Boundary:** The equilibrium level is the exact threshold between expensive and cheap pricing. Directly above it is the Premium zone (expensive); directly below it is the Discount zone (cheap).
- **The Threshold for Action:** Smart traders treat the equilibrium level as a strict boundary price must cross before considering a trade.
  - In a bullish uptrend, wait for price to pull back and drop below the equilibrium level into discount territory before buying.
  - In a bearish downtrend, wait for price to push up above the equilibrium level into premium territory before selling.
- **Filtering Premature Trades:** By marking the exact 50% point of a swing range, the equilibrium level prevents entering the market too early. For example, if looking to buy during an uptrend but price is currently at or above equilibrium, the pullback likely has more room to drop — entering long there would be premature.
Drawing the equilibrium level across a swing high and swing low allows immediate assessment of whether current price is mathematically favorable for a high-probability trade entry.
 
---
 
# Questions I Had and Answers I Got
 
## Q1. Does the direction I drag the Fibonacci tool (high-to-low vs low-to-high) change the premium/discount zones?
 
No. As covered in the TradingView Tools section, dragging the tool from swing high to swing low or from swing low to swing high produces the same visual result. The tool simply identifies the 50% midpoint of the range you select, and that midpoint stays the same regardless of the direction you dragged it in. What matters is selecting the correct swing high and swing low that define the current market structure range, not the order in which you drag the tool.
 
## Q2. What happens if there's no clear supply or demand zone in the correct premium/discount half?
 
If there is no clear supply or demand zone in the correct half of the range, it generally means there isn't a high-probability setup available yet, and patience is required. Forcing a trade in a low-quality zone — for example, buying from a demand zone sitting in the premium half — significantly increases the chance of price blasting straight through it. In this situation, the better approach is to wait for price to continue moving and either form a new zone in the correct half, or wait for an entirely new swing range and market structure to develop before applying the tool again.
 
## Q3. How does the Equilibrium Level relate back to Change of Character and Higher Timeframe Mitigation from Day 14?
 
These concepts work together as layers of confirmation. The equilibrium level tells you which half of the range price is in (premium or discount), helping filter whether a zone is worth trading. Higher Timeframe Mitigation, from Day 14, requires the price reversal to originate from an unmitigated higher timeframe zone. In practice, a high-probability setup often combines both: price sweeps liquidity, taps into an unmitigated higher timeframe demand zone that is also sitting within the discount half of a swing range, and then forms a Change of Character. The equilibrium level essentially adds another filter on top of the ChoCh validity criteria, increasing confidence that the zone being traded is in the right pricing area.
 
## Q4. Can the Premium and Discount concept be used on its own without supply and demand zones?
 
While the equilibrium level alone gives a general sense of whether price is "cheap" or "expensive" within a range, the sources are clear that combining it with supply and demand zones produces far higher-probability setups. Using premium and discount in isolation only tells you which half of the range you're in — it does not tell you exactly where price might react. Pairing it with supply and demand zones (and filtering out low-quality zones in the wrong half) gives both the pricing context and the precise level needed for a complete, high-probability trade setup.
 
---
 
# Key Takeaways From Day 15
 
- Premium and Discount zones prevent the common trap of buying too high or selling too low by splitting a swing range at the 50% equilibrium level.
- Premium = expensive, upper half, look to sell. Discount = cheap, lower half, look to buy.
- Always identify market structure and the swing range BEFORE applying the Premium and Discount tool.
- High-quality zones: demand in discount, supply in premium. Low-quality zones: demand in premium, supply in discount — these will likely fail.
- Extreme zones (furthest into premium/discount, at the origin of the swing) have the highest probability of holding, because their failure signals a full market structure shift.
- The Fibonacci retracement tool can be customized to show only the 50% equilibrium level, turning it into a dedicated Premium/Discount tool.
- The Bar Replay tool on TradingView is excellent for practicing structure identification and zone-drawing on historical data as if it were live.
- The Equilibrium Level is the strict boundary price must cross before a trade should even be considered — it filters out premature entries.
- This concept works across every timeframe and asset class, but expectations should always be scaled to the timeframe being used.
---
 
# Conclusion
 
Day 15 tied together several previously learned concepts — market structure, supply and demand, and liquidity — into one cohesive pricing framework: Premium and Discount. This was an important lesson because it added a crucial filtering layer on top of everything learned so far. Knowing how to identify a supply or demand zone is only half the job; knowing whether that zone sits in the correct half of the swing range is what actually determines whether the setup has a real probability of working. The equilibrium level gave me a precise, mathematical way to avoid premature entries, and the concept of extreme zones reinforced why origin points of a swing range are so significant. Learning the TradingView-specific application — customizing the Fib tool and using Bar Replay for practice — also gave me practical tools to start applying this concept directly on charts. Overall, Day 15 has sharpened my ability to combine structure, zones, and pricing context into a single high-probability trading decision.

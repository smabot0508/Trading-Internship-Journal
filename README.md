# Trading-Internship-Journal
Daily learning notes, market observations, and analysis during my US stock market internship.

# SMC Mastery Roadmap — Trading Internship Reference Notes

> **Purpose:** Personal reference for Smart Money Concepts (SMC) trading.  
> Whenever you feel lost on a concept, come back here, find the phase, and follow the chain.  
> Every concept builds on the one before it — do not skip phases.

---

## Table of Contents

- [The SMC Mental Model](#the-smc-mental-model)
- [The Fractal (Most Important Idea)](#the-fractal-most-important-idea)
- [Phase 1 — Foundations](#phase-1--foundations)
- [Phase 2 — Structure & Context](#phase-2--structure--context)
- [Phase 3 — Liquidity](#phase-3--liquidity)
- [Phase 4 — Entry Tools](#phase-4--entry-tools)
- [Phase 5 — Execution & Models](#phase-5--execution--models)
- [The Live Trade Checklist](#the-live-trade-checklist)
- [Common Mistakes to Avoid](#common-mistakes-to-avoid)
- [Key Terminology Quick Reference](#key-terminology-quick-reference)

---

## The SMC Mental Model

Smart Money Concepts is built around one core idea:

> **Banks and institutions move price to collect liquidity (retail stop losses) before delivering price in the real direction.**

Your job as a retail trader is to:
1. Identify **where liquidity is sitting** (where retail stops are clustered)
2. Wait for price to **sweep that liquidity**
3. Look for a **structural shift** on a lower timeframe
4. Enter at an **inefficiency** (FVG or OB) in the **discount/premium zone**

---

## The Fractal (Most Important Idea)

The same pattern repeats on **every single timeframe:**

```
BOS / CHoCH  →  Liquidity Sweep  →  OB or FVG  →  Move
```

This happens on:
- Monthly → Weekly → Daily → H4 → H1 → M15 → M5

**Rule:** Always get your **bias from the higher timeframe (HTF)** and take your **entry from the lower timeframe (LTF).**

| Timeframe | Purpose |
|-----------|---------|
| Monthly / Weekly | Overall trend direction |
| Daily / H4 | Swing structure, major liquidity levels |
| H1 / M15 | Entry confirmation, BOS/CHoCH |
| M5 / M1 | Precision entry, SL placement |

---

## Phase 1 — Foundations

> Build your eyes first. You cannot read SMC without these basics.

---

### 1. Candlestick Reading

**What to know:**
- Body = difference between open and close
- Wick = price rejection (upper wick = bearish rejection, lower wick = bullish rejection)
- **Displacement candles** — large-bodied candles with small wicks = strong institutional move
- **Doji / spinning top** = indecision, potential reversal

**Key candle types for SMC:**
- Bullish/Bearish engulfing
- Pin bar (strong wick rejection)
- Displacement (large body, momentum candle)

---

### 2. Market Structure

**Definition:** The pattern of highs and lows that defines trend direction.

| Structure | Meaning |
|-----------|---------|
| Higher High (HH) + Higher Low (HL) | Bullish trend |
| Lower High (LH) + Lower Low (LL) | Bearish trend |
| Equal Highs (EQH) | Liquidity resting above |
| Equal Lows (EQL) | Liquidity resting below |

**Types of highs/lows:**
- **Swing High / Swing Low** — major turning points (HTF)
- **Internal High / Internal Low** — minor turning points within a swing (LTF)

> **Rule:** Always label structure from the timeframe you're trading. HTF swings are more important than LTF swings.

---

### 3. Multi-Timeframe Analysis + Fractal

**The Top-Down Approach:**

```
Step 1: Weekly/Daily  → Identify HTF trend + major liquidity levels
Step 2: H4/H1        → Find where price is in the range (premium or discount?)
Step 3: M15/M5       → Wait for CHoCH, find OB or FVG, enter
```

**The Fractal Rule:**
Every BOS → Sweep → OB/FVG sequence on HTF contains the same sequence on LTF. Zoom in to find the LTF entry within the HTF setup.

---

### 4. Session Times (Killzones)

> Price moves with purpose during these windows. Outside these windows = chop / consolidation.

| Session | Time (UTC) | Character |
|---------|-----------|-----------|
| Asia | 00:00 – 06:00 | Range building, liquidity creation |
| London Open | 07:00 – 10:00 | Most volatile, major sweeps happen here |
| New York Open | 13:00 – 16:00 | Continuation or reversal of London |
| London Close | 15:00 – 17:00 | Profit-taking, liquidity grabs |

**Key insight:** London session often sweeps the Asia range. New York either continues the London move or reverses it after grabbing NY open liquidity.

---

## Phase 2 — Structure & Context

> Learn to read what the market is *doing* vs. what it is *faking.*

---

### 5. Break of Structure (BOS)

**Definition:** When price closes beyond a previous swing high (bullish BOS) or swing low (bearish BOS), confirming trend continuation.

```
Bullish BOS:  price breaks above previous HH  →  trend continues up
Bearish BOS:  price breaks below previous LL  →  trend continues down
```

**Key rule:** A BOS requires a **candle close** beyond the level, not just a wick.

**BOS confirms:** The existing trend is still valid. Look for pullbacks to OBs/FVGs to enter in trend direction.

---

### 6. Change of Character (CHoCH)

**Definition:** The first structural shift against the prevailing trend. This is the earliest signal of a potential reversal.

```
In a downtrend:  price breaks above a previous Lower High  →  CHoCH (possible reversal)
In an uptrend:   price breaks below a previous Higher Low  →  CHoCH (possible reversal)
```

**BOS vs CHoCH:**

| Signal | Meaning |
|--------|---------|
| BOS | Trend is continuing — trade with the trend |
| CHoCH | Trend may be reversing — wait for confirmation before counter-trend trade |

> **Note:** One CHoCH is not enough. Wait for CHoCH + BOS in the new direction before fully committing to a reversal trade.

---

### 7. Inducement (IDM)

**Definition:** A deliberate, engineered fake move by institutions to trigger retail stop losses and grab liquidity *before* the real move.

**How it works:**
1. Price is trending up
2. Price pulls back slightly, forming a minor low (inducement low)
3. Retail traders place stops *below* that minor low
4. Price dips below it briefly (inducement sweep) to grab those stops
5. Price then continues up — the real move

**Why it matters:** Without understanding IDM, liquidity sweeps look random. IDM is *how* the sweep is engineered.

```
Setup with IDM:
HTF bullish → Price creates IDM low → Sweeps it → CHoCH on LTF → Enter long
```

---

### 8. Premium & Discount Zones

**Definition:** The two halves of any price range, divided at the 50% midpoint (equilibrium).

```
Premium Zone  = above 50% of the range  →  sell here (price is expensive)
Discount Zone = below 50% of the range  →  buy here (price is cheap)
```

**How to draw:**
1. Identify a swing high and swing low
2. Use the 0.5 Fibonacci level as equilibrium
3. Above 0.5 = premium, below 0.5 = discount

**Rule:**
- In a **bullish** setup → look to **buy in discount**
- In a **bearish** setup → look to **sell in premium**

---

## Phase 3 — Liquidity

> Liquidity is the engine. Price always moves *toward* liquidity pools.

---

### 9. Liquidity Types

Liquidity = clusters of stop loss orders sitting in the market.

| Type | Location | Description |
|------|----------|-------------|
| Buy-side Liquidity (BSL) | Above swing highs / EQH | Retail short stops sitting here |
| Sell-side Liquidity (SSL) | Below swing lows / EQL | Retail long stops sitting here |
| Equal Highs (EQH) | Double/triple tops | Obvious target for BSL sweep |
| Equal Lows (EQL) | Double/triple bottoms | Obvious target for SSL sweep |
| Trendline Liquidity | Along slanted trendlines | Stops placed by trendline traders |

**Rule:** The more obvious a level is to retail traders, the more liquidity sits there, and the more likely institutions will target it.

---

### 10. Liquidity Sweeps

**Definition:** When price temporarily moves beyond a liquidity level (EQH, EQL, swing high/low) to trigger those stop orders, then reverses sharply.

**How to identify a sweep vs. a real breakout:**

| Sweep | Real Breakout |
|-------|--------------|
| Wick beyond level, closes back inside | Candle **closes** beyond level with body |
| Sharp reversal after | Continuation with momentum |
| Low volume on the push (if using volume) | Volume expansion |
| Occurs during killzone session | Can occur anytime |

**After a sweep — what to look for:**
1. Wick beyond the high/low
2. Strong displacement candle back in original direction
3. CHoCH on LTF
4. Entry at OB or FVG left behind by the displacement

---

### 11. AMD Model (Accumulation, Manipulation, Distribution)

**Definition:** The 3-phase daily/session price cycle that institutions use to deliver price.

```
Phase 1 — Accumulation (Asia):
  Price ranges, builds liquidity on both sides

Phase 2 — Manipulation (London open / early NY):
  Price sweeps one side (the inducement / fake move)
  Retail traders get trapped on the wrong side

Phase 3 — Distribution (London / NY continuation):
  Price delivers in the real direction, taking out the opposite liquidity
```

**How to use it:**
- Asia range = the liquidity pool being targeted
- London often sweeps Asia high or low (manipulation)
- NY continues in the real direction

---

## Phase 4 — Entry Tools

> These are the tools you use to time your actual entry after the setup is confirmed.

---

### 12. Fair Value Gap (FVG) / Imbalance

**Definition:** A 3-candle pattern where the middle candle moves so fast that a gap (imbalance) is left between candle 1's high and candle 3's low (bullish FVG) or candle 1's low and candle 3's high (bearish FVG).

```
Bullish FVG:
  Candle 1 high ←── gap ──→ Candle 3 low
  (price went up so fast, this gap was left unmitigated)

Bearish FVG:
  Candle 3 high ←── gap ──→ Candle 1 low
```

**Why price returns to FVGs:** Institutions need to fill unfilled orders left in that gap.

**How to trade:**
1. Identify HTF bias
2. Wait for displacement that creates FVG
3. Wait for price to retrace into the FVG
4. Enter at the 50% or bottom/top of the FVG
5. SL beyond the FVG, TP at next liquidity

**FVG quality:**
- Higher timeframe FVG = stronger
- FVG that aligns with an OB = highest quality
- FVG inside premium/discount = ideal

---

### 13. Order Blocks (OB)

**Definition:** The last opposing candle (or group of candles) before a significant displacement move. This is the zone where institutions placed their original orders.

```
Bullish OB:  last bearish candle before a strong bullish move
Bearish OB:  last bullish candle before a strong bearish move
```

**How to identify a valid OB:**
1. There must be a displacement (strong impulsive move) after it
2. The move after must take out a swing high or low (BOS/CHoCH)
3. Price should not have returned and mitigated it yet (unmitigated = valid)

**OB entry:**
- Price returns to the OB zone
- Look for confirmation on LTF (CHoCH, FVG inside OB)
- Enter at 50% or top/bottom of OB candle
- SL = just below OB low (bullish) or above OB high (bearish)
- TP = next liquidity pool

---

### 14. Breaker Blocks

**Definition:** A failed Order Block. When price comes back and breaks through the OB (mitigates and continues), the OB becomes a Breaker Block — now acting as resistance (if it was support) or support (if it was resistance).

```
Bullish OB → price returns → price breaks through (bearish) → OB becomes Bearish Breaker
```

**Trading Breakers:**
- Same entry rules as OB but now in the opposite direction
- Strong signal because trapped traders' stops will fuel the move

---

### 15. Mitigation Blocks

**Definition:** An order block from a *failed* price move that was never filled. Price eventually returns to mitigate (fill) those institutional orders.

**Difference from OB:**

| Order Block | Mitigation Block |
|-------------|-----------------|
| From a successful displacement | From a failed move |
| Untested, expecting return | Price must eventually return to fill |
| Entry when price first returns | Entry when price comes back after failure |

---

### 16. Optimal Trade Entry (OTE)

**Definition:** The ideal Fibonacci retracement zone within a discount (for longs) or premium (for shorts) where you look to enter.

**OTE levels:**
```
0.618 — first target zone (conservative)
0.705 — middle of OTE
0.786 — deepest OTE (aggressive, tightest SL)
```

**How to draw:**
1. Identify a swing low to swing high (for a pullback long setup)
2. Draw Fibonacci from the swing low to swing high
3. OTE zone = 0.618 to 0.786 retracement
4. Combine with OB or FVG in that zone = highest probability entry

---

## Phase 5 — Execution & Models

> Bring everything together into repeatable, testable setups.

---

### 17. IPDA & Price Delivery

**IPDA = Interbank Price Delivery Algorithm**

**Core idea:** Price is not random. It is delivered algorithmically by banks on a quarterly cycle to seek out liquidity above and below price.

**Quarterly Shifts:**
- Every quarter, price shifts to seek liquidity
- January / April / July / October = quarterly shift beginnings
- The algorithm targets previous quarter's high/low as liquidity

**IPDA Lookback:**
- 20-day lookback (short term)
- 40-day lookback (medium term)
- 60-day lookback (long term)

Price uses these lookback windows to identify where liquidity is parked and deliver toward it.

---

### 18. London & NY Session Models

**London Session Model:**
```
00:00–06:00  Asia builds range (creates liquidity)
07:00–08:00  London sweeps Asia high or low (manipulation)
08:00–10:00  Real London move begins (distribution)
Entry:        CHoCH on M15 after sweep → OB/FVG entry → TP at opposite Asia level
```

**New York Session Model:**
```
12:00–13:00  NY Pre-market — gauge London direction
13:00–14:00  NY Open — either continues London or reverses it with a sweep
14:00–16:00  NY Distribution — strongest trending move of the day
Entry:        NY open sweep → CHoCH M15 → OB/FVG → TP at previous liquidity
```

---

### 19. Risk Management & Trade Plan

**Non-negotiable rules:**

| Rule | Detail |
|------|--------|
| Risk per trade | Max 1–2% of account per trade |
| Stop Loss | Always placed beyond the OB/FVG, never arbitrary |
| Take Profit 1 | 1:1 or previous internal high/low (secure partials) |
| Take Profit 2 | Major liquidity pool (1:3 to 1:5+) |
| Max daily loss | 3–5% stop trading for the day |
| Trade during killzones only | London open & NY open only |

**SL placement logic:**
- Bullish OB entry → SL below the OB candle's low
- FVG entry → SL just below the FVG
- After sweep entry → SL beyond the wick of the sweep candle

---

### 20. Backtesting & Journaling

**The 500-trade rule:** Do not trade live until you have manually backtested at least 500 setups on replay. This builds pattern recognition that no amount of studying can replace.

**How to backtest:**
1. Use TradingView's Replay feature
2. Go to H4 timeframe, identify HTF structure
3. Replay candle by candle on M15
4. Mark every valid setup (sweep → CHoCH → OB/FVG)
5. Record entry, SL, TP, result

**Journal fields:**
```
Date | Pair | Session | HTF Bias | Setup Type | Entry Price | SL | TP | Result | Notes
```

**Review weekly:**
- Win rate by setup type
- Win rate by session
- Average RR achieved vs planned
- Mistakes (entering early, missing CHoCH, wrong bias)

---

## The Live Trade Checklist

Before clicking any buy or sell, confirm all of these:

- [ ] **HTF Bias confirmed** (daily/H4 structure is clear)
- [ ] **Liquidity identified** (where are the stops resting?)
- [ ] **In a killzone** (London open or NY open)
- [ ] **Sweep occurred** (liquidity was taken)
- [ ] **CHoCH on LTF confirmed** (structure shifted)
- [ ] **OB or FVG identified** (entry zone is clear)
- [ ] **In discount (long) or premium (short)**
- [ ] **SL placed correctly** (beyond OB/FVG/sweep wick)
- [ ] **TP at next liquidity** (clear target exists)
- [ ] **Risk is 1–2% maximum**

If any box is unchecked → **do not take the trade.**

---

## Common Mistakes to Avoid

| Mistake | Fix |
|---------|-----|
| Trading without HTF bias | Always start from Daily/H4 before M15 |
| Entering before CHoCH | Wait for structural confirmation |
| Confusing BOS with CHoCH | BOS = with trend, CHoCH = against trend |
| Trading outside killzones | Only trade London open + NY open |
| OB without displacement | If there's no strong move after, it's not a valid OB |
| Ignoring inducement | If you skip IDM, sweeps will confuse you |
| Moving SL to breakeven too early | Let price reach TP1 before managing |
| Over-trading after a loss | Max 3 trades per session, hard stop after daily loss limit |

---

## Key Terminology Quick Reference

| Term | Definition |
|------|-----------|
| BOS | Break of Structure — trend continuation |
| CHoCH | Change of Character — first sign of reversal |
| OB | Order Block — last opposing candle before impulse |
| FVG | Fair Value Gap — 3-candle imbalance zone |
| IDM | Inducement — engineered fake move to grab stops |
| BSL | Buy-side Liquidity — stops above highs |
| SSL | Sell-side Liquidity — stops below lows |
| EQH | Equal Highs — obvious BSL target |
| EQL | Equal Lows — obvious SSL target |
| HTF | Higher Timeframe (Daily, H4) |
| LTF | Lower Timeframe (H1, M15, M5) |
| OTE | Optimal Trade Entry — 0.618–0.786 fib zone |
| AMD | Accumulation, Manipulation, Distribution |
| IPDA | Interbank Price Delivery Algorithm |
| Premium | Above 50% of range — sell zone |
| Discount | Below 50% of range — buy zone |
| Mitigation | Price returning to fill an unfilled OB |
| Breaker | Failed OB that flips to opposite direction |
| Displacement | Strong impulsive candle with momentum |
| Killzone | High-probability session time window |

---

## Roadmap Summary (Topic Order)

```
PHASE 1 — FOUNDATIONS
  1.  Candlestick reading
  2.  Market structure
  3.  Multi-timeframe analysis + fractal
  4.  Session times (killzones)

PHASE 2 — STRUCTURE & CONTEXT
  5.  Break of Structure (BOS)
  6.  Change of Character (CHoCH)
  7.  Inducement (IDM)
  8.  Premium & discount zones

PHASE 3 — LIQUIDITY
  9.  Liquidity types (BSL, SSL, EQH, EQL)
  10. Liquidity sweeps
  11. AMD model

PHASE 4 — ENTRY TOOLS
  12. Fair Value Gap (FVG) / Imbalance
  13. Order Blocks (OB)
  14. Breaker Blocks
  15. Mitigation Blocks
  16. Optimal Trade Entry (OTE)

PHASE 5 — EXECUTION & MODELS
  17. IPDA & price delivery
  18. London / NY session models
  19. Risk management & trade plan
  20. Backtesting & journaling
```

---

*Notes maintained as part of Trading Internship Journey. Last updated: 2026.*

> "The market is not random. It is engineered. Your job is to read the engineering."

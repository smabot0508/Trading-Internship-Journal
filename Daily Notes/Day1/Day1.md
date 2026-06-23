# Day 1 Internship Notes

**Date:** 01-06-2026

## Work Start Time

9:00 AM

---

# Today's Objective

- Understand the basics of the US Market.
- Learn how the internship work will be conducted.
- Explore TradingView and market behaviour.
- Understand how to maintain GitHub Documentation.

---

# Topics Learned Today

## 1. Introduction to the US Stock Market

Today I learned the fundamentals of how the US stock market actually works — not just that prices "go up and down," but *why* they move, who is involved, and how a company's shares end up tradable in the first place.

### What is a Stock Exchange?

A stock exchange is essentially a regulated marketplace — physical or digital — where buyers and sellers come together to trade ownership shares ("stock") of publicly listed companies. When a company wants to raise money from the public instead of (or in addition to) borrowing from banks, it lists its shares on an exchange through a process called an **IPO (Initial Public Offering)**. Once listed, anyone with a brokerage account can buy or sell a piece of that company.

**The two major US exchanges I learned about:**

- **NYSE (New York Stock Exchange):** The oldest and largest stock exchange in the US by market value. It uses a hybrid model — partly electronic, partly involving human "designated market makers" on the physical trading floor in New York. Companies like Coca-Cola, JPMorgan, and Disney are listed here.
- **NASDAQ (National Association of Securities Dealers Automated Quotations):** A fully electronic exchange, historically associated with technology companies (Apple, Microsoft, NVIDIA, Tesla). There's no physical trading floor in the traditional sense — everything happens through computer networks.

<img src="Images/NASDAQ%20vs%20NYSE.jpeg" width="800">

### What Actually Moves a Stock's Price?

This was the core question of the day. A stock's price is **not set by any single authority** — it is the live result of buyers and sellers agreeing on a price in real time. I learned that price movement is driven by a combination of:

- **Demand and Supply:** If more people want to buy a stock than sell it, the price rises. If more people want to sell than buy, the price falls. This is the single most fundamental rule in all of trading.
- **Company Performance:** Quarterly earnings reports, revenue growth, profit margins, and management decisions directly affect how much investors are willing to pay for a share.
- **News:** Anything from a product launch, a lawsuit, a CEO change, or a geopolitical event can instantly shift investor sentiment and therefore price.
- **Earnings Reports:** Public companies report their financial results every quarter (every 3 months). These reports are major events — stocks often move sharply (sometimes 5–20% in a single day) right after earnings are released, depending on whether results beat or missed expectations.
- **Market Sentiment:** This refers to the overall "mood" of investors — whether they are feeling optimistic (bullish) or fearful (bearish) about the market in general, independent of any single company's fundamentals.

### Market Timings I Learned

| Session | Purpose |
|---|---|
| **Pre-Market Session** | Trading that happens before the official market opens. Usually lower volume, but reacts to overnight news (e.g., earnings released before the bell). |
| **Regular Market Hours** | The main trading session where the vast majority of daily volume happens. |
| **After-Hours Session** | Trading that continues after the official close, often reacting to news or earnings released right after the bell. |

Pre-market and after-hours sessions generally have **lower liquidity** (fewer participants), which means prices can swing more sharply on relatively small trades — something I'll need to keep in mind as I get further into the internship.

---

## 2. Understanding the Internship Workflow

Today I also understood the day-to-day structure of the internship — what is expected of me on a daily basis, separate from the theory itself.

### Daily Responsibilities

- **Stay Up to Date with Big Stock Companies:** Following major companies (large-cap stocks) daily to understand how real-world news translates into price action. This builds the habit of connecting headlines to charts.
- **Watch and Follow DeepVue Learning Videos:** DeepVue is the trading platform/tool used throughout this internship for screening stocks, analyzing charts, and learning structured trading concepts through video tutorials.
- **Monitor US Market Movements During Live Market Hours:** Actively watching the market while it's open (not just reviewing it afterward) to build a feel for real-time price behavior.
- **Maintain Daily GitHub Documentation:** Writing structured notes (like this one) every day to track what was learned, questions raised, and conclusions reached — this Day 1 to Day 19+ journal is the direct result of that habit.
- **Participate in Morning and Evening Standup Calls:** Short check-in meetings to report progress, raise questions, and stay aligned with the mentor's expectations.

> 🖼️ **[Add Image Here]** — A simple workflow diagram (Morning Standup → Market Hours Monitoring → DeepVue Learning → GitHub Documentation → Evening Standup) would visually summarize this daily cycle well. Suggested file: `images/day1/daily-workflow.png`

---

## 3. Introduction to TradingView

TradingView is the primary charting platform I'll be using throughout the internship to visually analyze stock price movements. Today was just the first hands-on exposure to its interface.

### What I Learned to Do

- **How to Open Charts:** Searching for any publicly listed stock by its ticker symbol (e.g., "TSLA" for Tesla) and instantly pulling up its price chart.
- **How to Search Stocks:** Using the search bar to look up companies either by name or ticker symbol.
- **How to Change Timeframes:** A chart can display price action over different intervals — for example, 1-minute candles, 1-hour candles, daily candles, or weekly candles. Each timeframe tells a different "story" about the same stock; a daily chart shows the long-term trend, while a 1-minute chart shows extremely short-term, noisy price action.
- **Basic Candlestick Observation:** A first look at how individual candlesticks appear on the chart and how they stack together to form a visual price history.

### Stocks Observed Today

- **Tesla (TSLA)**
- **NVIDIA (NVDA)**

These two were chosen specifically because they are highly liquid, highly volatile growth stocks — meaning they tend to show clear, dramatic price movements, which makes them excellent practice stocks for a beginner learning to read charts.

> 🖼️ **[Add Image Here]** — A screenshot of the actual TradingView chart for TSLA or NVDA from today's session would be the most valuable addition here, since it directly documents what was observed. Suggested file: `images/day1/tsla-nvda-chart-day1.png`

---

## 4. Basic Understanding of Candlestick Charts

Candlestick charts are the primary way price movement is visually represented in trading — and understanding their structure is foundational to every single technical concept that comes later in this internship (patterns, structure, order blocks, etc. — all built on this).

### The Four Core Components of Every Candle

Each candlestick represents price movement over a chosen time period (a minute, an hour, a day — depending on the timeframe selected) and is built from exactly four data points:

| Component | Meaning |
|---|---|
| **Open Price** | The price at which the stock started trading at the beginning of that time period. |
| **Close Price** | The price at which the stock finished trading at the end of that time period. |
| **High Price** | The highest price the stock reached at any point during that period. |
| **Low Price** | The lowest price the stock reached at any point during that period. |

The thick, rectangular part of the candle is called the **body**, and it represents the distance between the open and close price. The thin lines extending above and below the body are called **wicks** (or shadows), and they represent the high and low — i.e., how far price moved beyond the open/close before settling back.

> 🖼️ **[Add Image Here]** — This is the single most important image to add to this section: a labeled diagram showing a candlestick with arrows pointing to Open, Close, High, Low, Body, and Wick. Suggested file: `images/day1/candlestick-anatomy.png`

### Green vs. Red Candles

- **Green Candle (Bullish):** The close price is *higher* than the open price. This means buyers were in control during that time period — demand outweighed supply, pushing the price up by the end of the period.
- **Red Candle (Bearish):** The close price is *lower* than the open price. This means sellers were in control — supply outweighed demand, pushing the price down by the end of the period.

> 💡 **Why this matters beyond just color:** A single candle's color tells you who "won" that specific time period, but it says nothing on its own about the broader trend. A red candle inside an overall uptrend might just be a healthy pullback, not a reversal. This distinction — single candle vs. overall structure — becomes a major theme in later days of this internship (see Day 13's Break of Structure notes).

---

## 5. Market Observation

Beyond the theory, I spent time simply watching the live market and noted a few real-time behavioral patterns:

- **US market stocks are highly active during opening hours.** The first 30–60 minutes after the market opens (9:30 AM ET for NYSE/NASDAQ) typically see the highest volume and the sharpest price swings of the entire day.
- **Technology stocks like NVIDIA and Tesla show strong volatility.** Both stocks are known for large day-to-day percentage swings compared to more stable, established companies (like utility or consumer staples stocks).
- **Volume increases significantly during market opening.** Volume refers to the number of shares traded in a given period — higher volume at the open reflects the fact that overnight news, pre-market activity, and pending orders all get executed simultaneously once trading officially begins.

---

# Videos/Resources Followed

1. Basic US market structure videos
   (<https://youtu.be/icyXl7B-s-4?si=GRK3wsgR67ZpfJVH>)
2. DeepVue introductory videos
   (<https://youtu.be/7mJNvFbQSRk?si=AD7KVbLASsTv5Vfa>)

---

# Questions I Had

1. Why do stocks become highly volatile during market opening?
2. Why does volume suddenly increase at specific timings?
3. How do institutional investors affect stock prices?

---

# Answers (With Detailed Reasoning)

**1. Why do stocks become highly volatile during market opening?**

During the hours the market is closed (overnight, weekends), news, earnings reports, and global events still happen — but no one can trade on them yet. The moment the market opens, every trader and institution that wants to react to that overnight information places their orders **at the same time**. This sudden concentration of buy and sell orders, all competing to be filled within the same few minutes, causes the price to swing sharply until a new "fair" price is found. Think of it like a floodgate opening after being closed overnight — all the pressure that built up gets released at once.

**2. Why does volume suddenly increase at specific timings?**

Volume increases whenever there is a surge of genuine buying or selling activity — and certain times of day reliably attract more participants. The market open (as explained above) is one major spike point. The market close is another, because many institutional funds are required to settle their positions by end of day, and day traders close out positions before the overnight gap risk. Scheduled events — like earnings releases or major economic data (e.g., Federal Reserve interest rate announcements) — also cause sudden, predictable volume spikes at their exact release time.

**3. How do institutional investors affect stock prices?**

Institutional investors — banks, hedge funds, mutual funds, pension funds — trade with vastly larger amounts of capital than individual retail traders. A retail trader buying 100 shares barely moves the price of a large stock; an institution buying 5 million shares absolutely will. Because of this size, institutions can't simply place one giant order without causing the price to move sharply against themselves (buying that much at once would push the price up before they finish buying). This is *why* institutions often have to break up their orders, and it's the root reason concepts like liquidity, order blocks, and "smart money" — all covered later in this internship — exist in the first place. Understanding this single answer on Day 1 turned out to be the seed for nearly everything technical I learned afterward.

---

# Key Takeaways From Day 1

- The US market is highly dynamic and news-driven — price reflects real-time consensus between buyers and sellers, not a fixed value.
- NYSE and NASDAQ are the two major exchanges, with NASDAQ being fully electronic and historically tech-heavy.
- A candlestick's four components (Open, Close, High, Low) and its two visual parts (body, wick) are the foundational building blocks for all future chart analysis.
- Proper observation and documentation are very important — today's daily GitHub habit is what makes the entire internship traceable and reviewable.
- Trading is not just buying and selling — understanding market behavior, participant psychology, and structure is essential.
- Consistency in learning and market observation will improve understanding over time, and today's foundational concepts (institutional size, volume, candlesticks) directly set up everything learned in later weeks.

---

# Conclusion

Today was mainly focused on understanding the internship workflow, getting introduced to the US stock market, exploring TradingView, and learning the basics of stock chart observation. I also understood the importance of daily documentation, market analysis, and consistent learning throughout the internship. Looking back after several weeks of learning more advanced Smart Money Concepts, it's clear that Day 1's simple explanation of *why* institutional investors move price was actually the first seed of everything that followed — liquidity, order blocks, and market structure all build directly on this Day 1 foundation.

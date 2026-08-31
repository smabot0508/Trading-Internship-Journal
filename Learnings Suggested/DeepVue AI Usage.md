# Deepvue AI Webinar — Learning Notes

**Source:** Deepvue Live Webinar — "Mastering AI Trading Workflows with Deepvue" — https://www.youtube.com/watch?v=izb0CAypHvU&list=LL&index=1
**Date Watched:** Sunday, 30-08-2026
**Suggested by:** Mentor (weekend learning assignment)

---

## Overview

The webinar covers how traders can use Deepvue's built-in AI to streamline market research and speed up decision-making, rather than replacing the trader's own judgment. It walks through specific workflows — analyzing leading market themes, breaking down earnings reports, and investigating stock-specific catalysts via a right-click feature — and stresses that the AI only performs well when given clear instructions and specific context, such as an attached watchlist or screener. The session also previews upcoming features (custom indicators, model books for pattern study, and a built-in trading journal). The overarching goal: automate manual, procedural research tasks and compress complex data into actionable insights for growth stock investors.

---

## 1. AI Trading Workflows

### 1.1 The Core Framing — "Trust but Verify"

- AI is positioned as an **intern-level research assistant** — useful for offloading repetitive, procedural work and summarizing large amounts of market data, but never to be relied on blindly.
- The trader remains responsible for verifying anything the AI produces before acting on it.

### 1.2 Right-Click Catalyst Research

- **Workflow:** Right-click any price bar showing a significant gap or volume surge and select `Ask Deepvue AI`.
- **Function:** The AI researches the underlying news or earnings catalyst in real time while the trader keeps browsing charts.
- **Key Benefit:** Removes the need to manually search news sites or company filings, and anchors a persistent summary icon to that specific price bar for future reference.

### 1.3 Leading Theme Identification

- **Workflow:** Feed a high-performing stock list or custom screener (e.g., the Deepvue Leaders list) into the AI terminal as context.
- **Function:** Prompt the AI to group those leaders into overarching market themes (cybersecurity, enterprise SaaS, data infrastructure, AI infrastructure, etc.).
- **Key Benefit:** Quickly reveals where institutional money is concentrating across the strongest growth names.

### 1.4 Structured Earnings Breakdown

- **Workflow:** Run a structured earnings-analysis prompt on a company that just reported.
- **Function:** The AI extracts trader-relevant metrics from the report — revenue/EPS surprise, guidance changes, margin trends, buybacks, and management tone.
- **Key Benefit:** Removes the need to read full press releases or SEC filings just to judge the quality of an earnings gap.

### 1.5 Deep-Dive Stock Analysis & the "N Factor"

- **Workflow:** Run an in-depth research prompt on an unfamiliar ticker that shows up on the radar.
- **Function:** Evaluates the business model, revenue streams, TAM, key competitors, recent catalysts, and the company's unique growth driver — the **"N factor."**
- **Key Benefit:** Builds conviction on a potential new leader quickly, without a from-scratch research process.

### 1.6 Natural Language & Voice AI Screening

- **Workflow:** Type or speak screening criteria in plain English (e.g., price above $20, average daily dollar volume over $50M, trading above the 21-day EMA, forming an inside day).
- **Function:** The AI translates the natural-language request directly into platform screener filters.
- **Key Benefit:** Skips the manual process of configuring parameters across multiple filter menus.

---

## 2. Effective Prompt Engineering

### 2.1 The Guiding Principle

Better instructions produce better results — the same "trust but verify" AI is turned from a generic search tool into a specialized research assistant purely through prompt quality.

### 2.2 The Three Pillars of Effective Trading Prompts

1. **Be Specific and Procedural** — vague prompts return generic internet summaries; effective prompts spell out step-by-step frameworks, precise evaluation criteria, and a clear goal.
2. **Provide Rich Context** — attach a concrete dataset (a custom screener or curated watchlist like the Deepvue Leaders list) directly to the prompt so the AI only analyzes assets matching the intended trading style.
3. **Define the Output Structure** — specify exactly how the answer should look: length limits, a numerical rating (e.g., out of 100), or fixed thematic sections (revenue surprise, margin trend, guidance, TAM, competitive moat).

### 2.3 Prompt Comparison — Vague vs. Optimized

- ❌ **Poor prompt:** "What are the most interesting stocks in the market right now?" → produces broad, unstructured commentary pulled from random articles, not real growth trading setups.
- ✅ **Optimized prompt:** "What are the top 5 most promising growth stocks from this list that are part of leading themes, based on projected EPS growth and margin growth? For each, give a brief description, rate it out of 100 for potential, and break down its growth trajectory." (with a leader watchlist attached as context) → produces a structured, high-conviction analysis of actual leaders.

### 2.4 Iterative Dialogue & Follow-Ups

- Prompting is treated as a back-and-forth conversation, not a single query. A strong initial output should be followed with targeted follow-ups — digging deeper into a company's "N factor," analyzing named competitors, or evaluating management tone from an earnings call.

---

## 3. Contextual Stock Research

### 3.1 The Core Idea

Contextual research means anchoring the AI's analysis to specific data — watchlists, screeners, the active chart, or a single price bar — instead of letting it run an unconstrained, generic web search.

### 3.2 Attaching Watchlists & Screeners ("Add Context")

- Clicking **Add Context** in the AI terminal attaches a preset screener (e.g., Deepvue Leaders) or a custom watchlist directly to a prompt.
- This turns a vague question ("what stocks look interesting?") into a constrained one ("identify the top themes among only these stocks" / "evaluate projected EPS and margin growth across this list").
- Multiple watchlists, screens, or data panels can be attached simultaneously for richer, layered context.

### 3.3 Active Chart & Symbol Context

- The AI automatically recognizes whichever ticker is currently active on-screen as the trader spacebars through a watchlist, allowing preset prompts ("How were earnings?" / "What does this company do?") to run without retyping the symbol or switching apps.

### 3.4 Event-Specific Price Bar Context

- Right-clicking a price bar with a gap or volume surge and selecting `Ask Deepvue AI` tasks the AI with researching the exact catalyst behind that bar, and anchors an interactive summary icon to it — so the catalyst can be re-read months or years later directly from the chart.

### 3.5 Natural Language Screener Context

- Using `/create a screen from a description`, a trader can type or speak criteria (price over $20, 50-day average dollar volume over $50M, price above the 21-day EMA, forming an inside day) and the AI maps the request to Deepvue's actual data points and screening logic.

### 3.6 Key Benefits

- **Eliminates noise** by constraining analysis strictly to a defined watchlist or leader list.
- **Accelerates procedural work** — grouping stocks into themes or parsing earnings filings — down to seconds.
- **Integrates research with charting** by tying catalysts and fundamentals directly to price bars and ticker lists.

---

## 4. Automated Technical Screening

### 4.1 How It Works

1. **Activate the action:** type `/` in the AI terminal and select `/create a screen from a description`.
2. **Describe the setup in plain English:** e.g., stocks over $20, 50-day average dollar volume over $50M, trading above the 21-day EMA, forming an inside day.
3. **Logic mapping & confirmation:** the AI translates the description into Deepvue's filter logic and presents it back for confirmation, allowing extra rules to be added (e.g., price above the 50-day moving average) before building.
4. **Instant generation:** once confirmed, the screen is built and saved automatically, ready to run or fine-tune manually inside the screener UI.

### 4.2 Upcoming — AI-Generated Custom Indicators

- **Natural language scripting:** describing a custom setup in plain English (e.g., "mark price action where volume is 50% above its 20-day average") and having the AI generate the underlying technical script.
- **One-click script conversion:** pasting an existing indicator description or TradingView PineScript code and having the AI convert it into a native Deepvue script automatically.

---

## 5. How This Connects to the Internship Work So Far

- **Right-click catalyst research fits directly into the daily journal habit** — instead of manually looking up why a stock gapped (as was done by hand for PLTR/HOOD/DELL/ZETA screenshots so far), this could anchor the catalyst summary straight onto the chart.
- **The 3-pillar prompt framework (specific/procedural, rich context, defined output)** is directly reusable for structuring future research prompts around the CANSLIM 2 screener output, rather than asking generic "what looks good today" questions.
- **Natural language screening** overlaps with the existing CANSLIM 2 filter setup (Dollar Volume, AS 3M, EPS/Sales growth, Pre-Market conditions) — worth testing whether the same filter logic can be recreated by description instead of manually configuring each group.
- **Contextual research via attached watchlists** lines up well with the daily 10-stock screener result — attaching that exact list as context, instead of asking open-ended questions, should produce more directly usable output for picking which names to actually chart each day.

---

## Key Takeaways

1. AI in trading should be treated as an intern-level research assistant — genuinely useful for repetitive, procedural work, but always verified before being acted on.
2. Prompt quality is the single biggest lever on output quality: be specific and procedural, attach rich context (a watchlist or screener), and explicitly define the output format.
3. Contextual research — anchoring the AI to a watchlist, an active chart, or a single price bar — is what separates a useful, focused answer from a generic internet summary.
4. Natural language can now replace manual screener configuration entirely, translating a plain-English technical description directly into platform filter logic.
5. Follow-up: try attaching the daily CANSLIM 2 screener output as context for a structured "top themes" or "rate these out of 100" prompt, and compare the result against today's manual chart-by-chart process.

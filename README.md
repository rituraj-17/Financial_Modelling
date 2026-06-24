# Financial Modelling

A collection of financial modelling assignments and projects covering core valuation techniques — DCF (Discounted Cash Flow), Multiple Valuation, Merger & Acquisition Analysis, and comparative company analysis.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `HONDA MOTOR CO DCF .xlsx` | DCF valuation model for Honda Motor Co. (Assignment 3) |
| `NISSAN MOTORS DCF.xlsx` | DCF valuation model for Nissan Motors (Assignment 3) |
| `Merger Valuation.xlsx` | M&A valuation model for the Nissan–Mitsubishi–Honda merger (Assignment 3) |
| `EXTENSIVE REPORT.pdf` | Detailed written report covering the M&A analysis and conclusions |

---

## Assignments

### Assignment 1 — Multiple Valuation & Company Comparison

**Part A: Multiple Valuation — Bumble Inc.**

Valuation of **Bumble Inc. (BMBL)** using trading comps (comparable company analysis) for FY23.

Metrics used:
- **EV/EBITDA**
- **EV/Revenue**
- **P/E (Price-to-Earnings)**

Comparable companies were selected from the **online dating industry** (e.g., Match Group, MeetMe, Spark Networks, etc.) to ensure accuracy and relevance. The analysis concludes with an **investment recommendation** based on where Bumble trades relative to its peers.

**Part B: Company Comparison**

A structured comparison of two companies across key financial and strategic parameters, with a **10-year investment recommendation** based on fundamentals, growth trajectory, and competitive positioning.

> Document limited to 3 pages. Judged on: choice of companies, choice of parameters, and investment advice.

---

### Assignment 2 — DCF Valuation of Tesla Inc.

**Objective:** Estimate the intrinsic value of **Tesla Inc. (TSLA)** using the Discounted Cash Flow method.

**Key Assumptions:**

| Parameter | Value |
|-----------|-------|
| Beta (β) | 2.3 |
| Expected Market Return (rₘ) | 15.4% |
| Risk-Free Rate (rᶠ) | 10-year US Treasury Yield |
| Revenue Growth (Years 1–5) | 15% |
| Revenue Growth (Years 6–10) | 10% |
| Terminal Growth Rate | 4% |

**Methodology:**

1. **Cost of Equity via CAPM:**
   ```
   rₑ = rᶠ + β × (rₘ − rᶠ)
   ```

2. **WACC** — Used as the discount rate throughout the model.

3. **Revenue Projections** — 10-year forecast using tiered growth rates.

4. **Free Cash Flow (FCF)** — Estimated by applying an appropriate FCF margin to projected revenues.

5. **Terminal Value:**
   ```
   TV = FCF_final × (1 + g) / (WACC − g)
   ```

6. **Present Value** — All future FCFs and terminal value discounted back to today.

7. **Fair Value per Share** — Compared against the market price to determine if TSLA is undervalued or overvalued.

---

### Assignment 3 — M&A Valuation: Nissan × Mitsubishi × Honda

**Objective:** Analyze and value the proposed merger involving **Nissan Motors**, **Mitsubishi Motors**, and **Honda Motor Co.** — one of the most significant consolidations in the global automotive industry.

**Files:**
- `NISSAN MOTORS DCF.xlsx` — Standalone DCF valuation of Nissan Motors
- `HONDA MOTOR CO DCF .xlsx` — Standalone DCF valuation of Honda Motor Co.
- `Merger Valuation.xlsx` — Combined M&A valuation model for the three-way deal
- `EXTENSIVE REPORT.pdf` — Full written analysis covering deal rationale, synergies, and conclusions

**Analysis Covers:**

- **Standalone DCF valuations** of Nissan and Honda to establish intrinsic value baselines
- **Merger valuation model** assessing the combined entity's value post-acquisition
- **Synergy analysis** — cost and revenue synergies expected from the consolidation
- **Deal structure** — evaluation of terms, share exchange ratios, and implied premiums
- **Strategic rationale** — why the three automakers pursued this consolidation (EV transition, cost pressures, market share defense against Chinese OEMs)
- **Investment conclusion** — whether the merger creates or destroys shareholder value

**Context:**

The Nissan–Mitsubishi–Honda merger discussions gained prominence in late 2024 as the three Japanese automakers faced mounting pressure from slowing ICE vehicle demand, the accelerating shift to EVs, and intensifying competition from Chinese manufacturers like BYD. The merger aimed to pool R&D resources, reduce redundancies, and build scale to compete globally.

---

## Tools Used

- **Microsoft Excel** — All quantitative modelling and valuation
- **Google Docs / PDF** — Written reports and company comparisons

---

## Concepts Covered

- Discounted Cash Flow (DCF) Analysis
- Comparable Company Analysis (Trading Comps / Multiples)
- CAPM & WACC Calculation
- Terminal Value Estimation
- Merger & Acquisition (M&A) Valuation
- Synergy Analysis
- Investment Decision Frameworks

---

*Financial Modelling | FAC Wintercamp 2024*

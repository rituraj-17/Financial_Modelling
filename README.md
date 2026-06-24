# Financial Modelling

A collection of financial modelling assignments and projects covering core valuation techniques — DCF (Discounted Cash Flow), Multiple Valuation, Merger & Acquisition Analysis, and comparative company analysis. Completed as part of FAC Wintercamp 2024.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `HONDA MOTOR CO DCF .xlsx` | Standalone DCF valuation model for Honda Motor Co. |
| `NISSAN MOTORS DCF.xlsx` | Standalone DCF valuation model for Nissan Motors |
| `Merger Valuation.xlsx` | Three-way M&A valuation model — Nissan × Mitsubishi × Honda |
| `EXTENSIVE REPORT.pdf` | Buy-side M&A advisory report covering deal rationale, synergies, and risks |

---

## Assignments

### Assignment 1 — Multiple Valuation & Company Comparison
*Individual*

**Part A: Multiple Valuation — Bumble Inc.**

Valuation of **Bumble Inc. (BMBL)** using trading comps (comparable company analysis) for FY23.

Metrics used:
- **EV/EBITDA**
- **EV/Revenue**
- **P/E (Price-to-Earnings)**

Comparable companies were selected from the **online dating industry** (e.g., Match Group, MeetMe, Spark Networks, etc.) to ensure sector relevance. The analysis concludes with an **investment recommendation** based on where Bumble trades relative to its peers.

**Part B: Company Comparison**

A structured comparison of two companies across key financial and strategic parameters, with a **10-year investment recommendation** based on fundamentals, growth trajectory, and competitive positioning.

> Document limited to 3 pages. Judged on: choice of companies, choice of parameters, and investment advice.

---

### Assignment 2 — DCF Valuation of Tesla Inc.
*Individual*

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
7. **Fair Value per Share** — Compared against market price to determine if TSLA is undervalued or overvalued.

---

### Assignment 3 — M&A Valuation: Nissan × Mitsubishi × Honda
*Team Project (3–4 members)*

**Objective:** Assess the financial feasibility of a three-way Nissan–Honda–Mitsubishi merger by building independent valuation models to evaluate intrinsic value, synergy potential, and deal attractiveness from a strategic and shareholder-value perspective.

**Files:**
- `NISSAN MOTORS DCF.xlsx` — Standalone DCF valuation of Nissan Motors
- `HONDA MOTOR CO DCF .xlsx` — Standalone DCF valuation of Honda Motor Co.
- `Merger Valuation.xlsx` — Combined three-way M&A valuation model
- `EXTENSIVE REPORT.pdf` — Full written analysis structured as a buy-side M&A advisory deliverable

**Approach:**

- **Standalone DCF Valuations** — Built independent DCF models for Nissan, Honda, and Mitsubishi using CAPM-derived WACC, multi-stage revenue growth assumptions, and terminal value estimation.
- **Comparable Company Analysis** — Benchmarked the three automakers against global peers including Toyota, Volkswagen, and Tesla across EV/EBITDA, EV/Revenue, and P/E multiples.
- **Three-Way Merger Model** — Constructed a combined entity valuation assessing post-merger value, cost and revenue synergies, and accretion/dilution impact on shareholders.
- **M&A Advisory Report** — Authored a report evaluating deal rationale, integration risks, and regulatory considerations, structured as a buy-side M&A advisory deliverable.

**Strategic Context:**

The Nissan–Mitsubishi–Honda merger discussions gained prominence in late 2024 as the three Japanese automakers faced mounting pressure from slowing ICE vehicle demand, the accelerating global shift to EVs, and intensifying competition from Chinese manufacturers like BYD. The consolidation aimed to pool R&D resources, eliminate redundancies, and build the scale needed to compete globally.

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
- Synergy Analysis (Cost & Revenue)
- Accretion / Dilution Analysis
- Buy-Side M&A Advisory Framing
- Investment Decision Frameworks

---

## 👤 Author

**Rituraj** — [@rituraj-17](https://github.com/rituraj-17)

*Financial Modelling | FAC Wintercamp 2024*

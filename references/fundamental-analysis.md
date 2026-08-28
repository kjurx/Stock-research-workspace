# Fundamental Analysis Guide — Indian Markets

Detailed methodology for analyzing Indian stocks (NSE/BSE) using fundamental data.

---

## Key Metrics — What to Check

### Valuation Metrics

| Metric | What It Tells You | Good Range (India) | Red Flag |
|---|---|---|---|
| **P/E (Price to Earnings)** | How much you pay per ₹1 of earnings | 15-25 (mature), 25-40 (growth) | >50 without growth story |
| **P/B (Price to Book)** | Premium over book value | 1-3 (value), 3-8 (quality) | >10 for non-tech |
| **EV/EBITDA** | Enterprise value vs operating profit | 8-15 (healthy) | >25 |
| **PEG Ratio** | P/E adjusted for growth | <1 (undervalued), 1-2 (fair) | >3 |
| **P/S (Price to Sales)** | Revenue multiple | 1-5 (normal) | >10 for non-tech |
| **P/FCF (Price to Free Cash)** | Cash generation premium | 15-30 | >50 |

### Profitability Metrics

| Metric | Formula | Good Threshold (India) | Great |
|---|---|---|---|
| **ROE** | Net Profit / Shareholders' Equity | >15% | >20% |
| **ROCE** | EBIT / Capital Employed | >15% | >20% |
| **ROA** | Net Profit / Total Assets | >8% | >12% |
| **Net Profit Margin** | PAT / Revenue | >10% | >15% |
| **Operating Margin** | EBIT / Revenue | >15% | >20% |
| **Gross Margin** | Gross Profit / Revenue | >30% | >50% |

### Financial Health

| Metric | Formula | Safe | Risky |
|---|---|---|---|
| **D/E (Debt to Equity)** | Total Debt / Equity | <0.5 | >1.5 |
| **Interest Coverage** | EBIT / Interest Expense | >5 | <2 |
| **Current Ratio** | Current Assets / Current Liabilities | >1.5 | <1 |
| **Quick Ratio** | (Current Assets - Inventory) / CL | >1 | <0.5 |
| **Debt to EBITDA** | Total Debt / EBITDA | <3 | >5 |

### Growth Metrics

| Metric | What to Look For |
|---|---|
| **Revenue Growth (YoY)** | Consistent >10% is good, >20% is strong |
| **Profit Growth (YoY)** | Should track or exceed revenue growth |
| **EPS Growth** | Steady upward trend over 3-5 years |
| **Dividend Growth** | Increasing dividend = confident management |
| **Subscriber/User Growth** | For tech/consumer businesses |

### Promoter & Ownership

| Data Point | Where to Find | What to Look For |
|---|---|---|
| **Promoter Holding** | BSE shareholding pattern | >50% is stable, <40% is concerning |
| **Promoter Pledge** | BSE shareholding pattern | >10% is risky, >30% is red flag |
| **FII Holding** | Monthly disclosures | Increasing = foreign confidence |
| **DII Holding** | Monthly disclosures | Increasing = domestic institutional confidence |
| **Public/Retail Holding** | Shareholding pattern | High retail + low promoter = risky |

---

## Analysis Framework

### Step 1: Company Overview

Search for:
- `"{company} about business model"` 
- `"{company} annual report summary"`
- `"{company} revenue segments"`

Understand:
- What does the company do? (Primary business)
- Revenue breakdown by segment
- Geographic exposure (domestic vs export)
- Competitive position (market leader, challenger, niche)

### Step 2: Financial Health Check

Search for:
- `"{company} balance sheet"` or `"{company} financials Screener.in"`
- `"{company} cash flow statement"`

Check these in order:

1. **Is the company profitable?** — Look at PAT (Profit After Tax) trend over last 5 years
2. **Is it generating cash?** — Operating cash flow should be positive and growing
3. **Is debt manageable?** — D/E < 1, Interest Coverage > 3
4. **Is working capital healthy?** — Current ratio > 1.2, not consuming too much cash

### Step 3: Valuation

Compare the company's metrics against:
- **Sector peers** (same industry, similar size)
- **Historical averages** (is current P/E higher/lower than 5-year average?)
- **Growth rate** (PEG < 1 suggests undervalued relative to growth)

**Indian Sector P/E Benchmarks (approximate):**

| Sector | Typical P/E Range |
|---|---|
| IT Services | 25-35 |
| Banking/NBFC | 12-20 |
| FMCG | 40-60 |
| Pharma | 25-40 |
| Auto | 20-35 |
| Metal/Mining | 10-20 (cyclical) |
| Real Estate | 30-60 (cyclical) |
| Telecom | 20-40 |
| Energy/Oil & Gas | 8-15 |
| Chemicals | 25-40 |

### Step 4: Earnings Quality

Check quarterly results for:
- **Consistency** — Are quarters consistently profitable?
- **Seasonality** — Some sectors have seasonal patterns (agri, auto during festive)
- **One-time items** — Adjust for exceptional gains/losses
- **Guidance** — Management commentary on future outlook

Search: `"{company} Q{X} FY{YY} results analysis"`

### Step 5: Moat & Competitive Advantage

Assess what gives the company an edge:
- **Brand power** (HUL, Nestle, Asian Paints)
- **Network effects** (Paytm, Zomato)
- **Cost leadership** (Tata Steel, Reliance)
- **Regulatory barriers** (banks, insurance, telecom)
- **Switching costs** (TCS, Infosys long-term contracts)
- **IP/Patents** (pharma — Dr. Reddy's, Sun Pharma)

### Step 6: Management Quality

Search for:
- `"{company} CEO MD management track record"`
- `"{company} corporate governance"`

Check:
- Promoter background and track record
- Related party transactions (red flag if excessive)
- Capital allocation history (good acquisitions vs value destruction)
- Board independence
- Management commentary tone (confident vs defensive)

---

## Red Flags to Watch

| Red Flag | Why It Matters |
|---|---|
| Promoter pledging >20% | Forced selling risk if stock drops |
| Auditor qualifications | Accounting may not be reliable |
| Frequent equity dilution | Destroying shareholder value |
| Related party transactions >5% revenue | Potential self-dealing |
| Revenue growing but cash flow negative | Aggressive accounting or working capital issues |
| Promoter selling consistently | Insiders losing confidence |
| Debt increasing faster than EBITDA | Unsustainable leverage |
| Frequent changes in auditors | Possible red flag |
| Subsidiary losses masking parent profit | Hidden risks |
| Dividend payout inconsistent despite profits | Cash may not be real |

---

## Quick Valuation Methods

### 1. P/E Relative Valuation
```
Fair Price = Sector Avg P/E × Company EPS
If CMP < Fair Price → Potentially Undervalued
If CMP > Fair Price → Check growth premium
```

### 2. DCF Simplified
```
Estimate next year's EPS
Assume growth rate for 5 years
Assume terminal growth of 5-6% (India nominal GDP)
Discount at 12-15% (India equity risk premium)
Sum of PV = Intrinsic Value
```

### 3. PEG-Based
```
PEG = P/E / Earnings Growth Rate
PEG < 1 → Undervalued
PEG 1-1.5 → Fair
PEG > 2 → Overvalued (unless quality premium justified)
```

---

## Data Sources (via Web Search)

| Source | What It Provides | Search Query |
|---|---|---|
| **Screener.in** | Financials, ratios, peer comparison | `site:screener.in {company}` |
| **TickerTape** | Visual analysis, scorecard | `site:tickertape.in {company}` |
| **MoneyControl** | News, results, shareholding | `site:moneycontrol.com {company} results` |
| **BSE India** | Official filings, shareholding | `site:bseindia.com {company}` |
| **Trendlyne** | Technicals + fundamentals | `site:trendlyne.com {company}` |
| **Annual Reports** | Management discussion, detailed financials | `"{company} annual report PDF {FY}"` |

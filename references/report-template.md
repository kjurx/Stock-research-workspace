# Research Report Template — Indian Stock Market

Template for generating structured stock/sector research reports in markdown.

---

## Report Types

| Report Type | Use When | Length |
|---|---|---|
| **Quick Check** | "Reliance ka kya hai?" — single stock snapshot | 1-2 pages |
| **Full Stock Report** | Deep dive on a specific company | 5-10 pages |
| **Sector Report** | "IT sector ka outlook" — sector analysis | 4-8 pages |
| **Comparison Report** | "TCS vs Infosys" — stock comparison | 3-5 pages |
| **Portfolio Review** | "Mera portfolio review karo" — multi-stock review | 3-6 pages |
| **Market Outlook** | "Market kahan ja raha hai?" — broad market view | 3-5 pages |

---

## Full Stock Report Template

```markdown
# {Company Name} ({TICKER}.NS) — Research Report

**Date**: {DD MMM YYYY}
**Current Price**: ₹{CMP}
**Rating**: {BUY / HOLD / SELL / ACCUMULATE}
**Target Price**: ₹{target} ({upside}% upside)
**Stop Loss**: ₹{SL} ({downside}% risk)
**Time Horizon**: {3M / 6M / 1Y / 3Y}

---

## Executive Summary

{2-3 sentence overview. What does the company do? Why is it interesting now?
What's the key thesis?}

**Key Thesis**: {One sentence summary of why buy/sell/hold}

---

## Company Overview

### Business Profile
| Parameter | Details |
|---|---|
| Sector | {sector} |
| Industry | {sub-sector} |
| Market Cap | ₹{cap} Cr ({Large/Mid/Small} Cap) |
| Founded | {year} |
| HQ | {city} |
| Employees | {number} |
| Website | {url} |

### Revenue Breakdown
| Segment | Revenue (₹ Cr) | % of Total | YoY Growth |
|---|---|---|---|
| {Segment 1} | {value} | {%} | {%} |
| {Segment 2} | {value} | {%} | {%} |
| {Segment 3} | {value} | {%} | {%} |

### Business Model
{2-3 paragraphs explaining how the company makes money, its competitive advantages,
and key risks in the business model.}

---

## Financial Analysis

### Profit & Loss (Last 5 Years)
| Metric | FY{Y-4} | FY{Y-3} | FY{Y-2} | FY{Y-1} | FY{Y} | CAGR |
|---|---|---|---|---|---|---|
| Revenue (₹ Cr) | | | | | | {%} |
| EBITDA (₹ Cr) | | | | | | {%} |
| EBITDA Margin | | | | | | |
| PAT (₹ Cr) | | | | | | {%} |
| EPS (₹) | | | | | | {%} |

### Balance Sheet (Latest)
| Metric | Value |
|---|---|
| Total Assets (₹ Cr) | |
| Total Debt (₹ Cr) | |
| Cash & Equivalents (₹ Cr) | |
| Net Debt (₹ Cr) | |
| Shareholders' Equity (₹ Cr) | |

### Cash Flow (Last 3 Years)
| Metric | FY{Y-2} | FY{Y-1} | FY{Y} |
|---|---|---|---|
| Operating CF (₹ Cr) | | | |
| Investing CF (₹ Cr) | | | |
| Financing CF (₹ Cr) | | | |
| Free Cash Flow (₹ Cr) | | | |

### Key Ratios
| Ratio | FY{Y-2} | FY{Y-1} | FY{Y} | Sector Avg | Verdict |
|---|---|---|---|---|---|
| ROE | | | | | |
| ROCE | | | | | |
| Net Margin | | | | | |
| D/E | | | | | |
| Current Ratio | | | | | |
| Asset Turnover | | | | | |

---

## Valuation

### Relative Valuation
| Metric | Company | Sector Average | Premium/Discount |
|---|---|---|---|
| P/E (TTM) | | | {%} |
| P/B | | | {%} |
| EV/EBITDA | | | {%} |
| P/S | | | {%} |
| P/FCF | | | {%} |

### Valuation Verdict
{Is the stock overvalued, fairly valued, or undervalued relative to peers?
What growth premium/discount is justified?}

---

## Technical View

| Indicator | Current Value | Signal |
|---|---|---|
| Price vs 200 DMA | {above/below} | {bullish/bearish} |
| RSI (14) | {value} | {overbought/neutral/oversold} |
| MACD | {signal} | {bullish/bearish} |
| 52-Week Range | ₹{low} - ₹{high} | |
| Support Levels | ₹{s1}, ₹{s2}, ₹{s3} | |
| Resistance Levels | ₹{r1}, ₹{r2}, ₹{r3} | |

**Technical Verdict**: {Summary of chart pattern and momentum}

---

## Shareholding Pattern
| Category | Latest (%) | QoQ Change | Trend |
|---|---|---|---|
| Promoters | | | {↑/↓/→} |
| FII | | | {↑/↓/→} |
| DII | | | {↑/↓/→} |
| Public/Retail | | | {↑/↓/→} |

**Promoter Pledge**: {X}% (Risk level: Low/Medium/High)

---

## Key Catalysts

### Positive Catalysts
1. {catalyst 1}
2. {catalyst 2}
3. {catalyst 3}

### Negative Catalysts
1. {risk 1}
2. {risk 2}
3. {risk 3}

---

## Peer Comparison
| Metric | {Company} | {Peer 1} | {Peer 2} | {Peer 3} |
|---|---|---|---|---|
| Market Cap (₹ Cr) | | | | |
| Revenue Growth | | | | |
| Net Margin | | | | |
| ROE | | | | |
| P/E | | | | |
| D/E | | | | |

---

## Investment Thesis

### Bull Case (Target: ₹{upper_target})
{What needs to go right for the stock to reach upper target?}

### Base Case (Target: ₹{base_target})
{Most likely scenario with moderate execution}

### Bear Case (Target: ₹{lower_target})
{What could go wrong? Downside scenario}

---

## Verdict

### Rating: {BUY / HOLD / SELL / ACCUMULATE}
**Target**: ₹{target} | **Stop Loss**: ₹{SL} | **Time Horizon**: {duration}

{2-3 paragraph summary of the recommendation. Why this rating? What's the
risk-reward? Who should buy this stock?}

---

*Disclaimer: This report is for educational and informational purposes only.
It does not constitute financial advice, investment recommendation, or an offer
to buy or sell any securities. The author is not a SEBI-registered investment
advisor. Please consult a qualified financial advisor before making any investment
decisions. Past performance is not indicative of future results.*
```

---

## Sector Report Template

```markdown
# {Sector Name} — Sector Research Report

**Date**: {DD MMM YYYY}
**Outlook**: {BULLISH / NEUTRAL / BEARISH}
**Preferred Picks**: {Stock 1}, {Stock 2}, {Stock 3}

---

## Sector Overview
{2-3 paragraphs on the sector's current state, key drivers, and outlook}

## Key Metrics
| Metric | Current | 1Y Ago | Change |
|---|---|---|---|
| Index Performance | | | {%} |
| Avg P/E (Sector) | | | |
| Avg ROE (Sector) | | | |
| Revenue Growth (Sector) | | | |

## Top Holdings Analysis
For each major stock in the sector:
- Quick financial snapshot
- Relative valuation
- Technical position

## Sector Catalysts
### Tailwinds
1. {tailwind 1}
2. {tailwind 2}

### Headwinds
1. {headwind 1}
2. {headwind 2}

## Stock Recommendations
| Stock | Rating | Target | Rationale |
|---|---|---|---|
| {Stock 1} | BUY | ₹{target} | {reason} |
| {Stock 2} | HOLD | ₹{target} | {reason} |
| {Stock 3} | ACCUMULATE | ₹{target} | {reason} |

---
*Disclaimer: Educational purposes only. Not financial advice.*
```

---

## Comparison Report Template

```markdown
# {Stock 1} vs {Stock 2} — Comparison Report

**Date**: {DD MMM YYYY}

## Quick Verdict
| Parameter | Winner |
|---|---|
| Valuation | {Stock X} |
| Growth | {Stock X} |
| Profitability | {Stock X} |
| Financial Health | {Stock X} |
| Technical Strength | {Stock X} |
| **Overall** | **{Stock X}** |

## Detailed Comparison
{Side-by-side comparison on all key metrics}

## Analysis
{Narrative explaining the comparison, nuances, and recommendation}

## Verdict
{Which stock to buy and why?}

---
*Disclaimer: Educational purposes only. Not financial advice.*
```

---

## Formatting Guidelines

1. **Always use tables** for numerical data — they're easy to scan
2. **Bold key numbers** — highlight important metrics
3. **Use emoji sparingly** — only if user requests it
4. **Include disclaimer** in EVERY report — no exceptions
5. **Use Indian formatting** — ₹ symbol, crores, lakhs
6. **Cite data sources** — mention where data came from
7. **Be honest about gaps** — if data is unavailable, say so
8. **Language**: Match user's language (Hindi/Hinglish/English)

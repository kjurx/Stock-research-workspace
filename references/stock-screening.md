# Stock Screening Guide — Indian Markets

Methodology for finding stocks on NSE/BSE based on specific criteria.

---

## Screening Dimensions

### 1. Market Capitalization Segments

| Segment | Market Cap Range | Risk Profile | Typical P/E |
|---|---|---|---|
| **Large Cap** | >₹20,000 Cr | Lower risk, stable returns | 20-35 |
| **Mid Cap** | ₹5,000-20,000 Cr | Moderate risk, growth potential | 25-45 |
| **Small Cap** | ₹500-5,000 Cr | Higher risk, high growth potential | 15-60 |
| **Micro Cap** | <₹500 Cr | Highest risk, speculative | Highly variable |

### 2. Valuation Filters

| Screen Name | Criteria | Use Case |
|---|---|---|
| **Value** | P/E < 15 AND P/B < 2 AND D/E < 0.5 | Finding undervalued quality |
| **Growth at Reasonable Price (GARP)** | P/E < Earnings Growth AND ROE > 15% | Balanced value + growth |
| **Deep Value** | P/E < 10 AND P/B < 1 AND Div Yield > 3% | Contrarian plays |
| **Quality** | ROE > 20% AND ROCE > 20% AND D/E < 0.3 | High-quality compounders |

### 3. Profitability Filters

| Screen Name | Criteria |
|---|---|
| **Profitable & Growing** | PAT > 0 for last 5 years AND Revenue Growth > 15% YoY |
| **High Margin** | Net Profit Margin > 20% AND Operating Margin > 25% |
| **Efficient Capital User** | ROCE > 25% AND ROE > 20% |
| **Cash Rich** | Free Cash Flow positive for 3 years AND Low debt |

### 4. Growth Filters

| Screen Name | Criteria |
|---|---|
| **Revenue Acceleration** | Revenue growth increasing each quarter for 4 quarters |
| **Profit Explosion** | PAT growth > 30% YoY for 2 consecutive years |
| **EPS Momentum** | EPS growth > 20% for 3 years AND positive latest quarter |
| **Dividend Grower** | Dividend per share increasing for 5+ consecutive years |

### 5. Momentum Filters

| Screen Name | Criteria |
|---|---|
| **Near 52-Week High** | CMP > 90% of 52-week high AND RSI > 50 |
| **Breakout** | Price above 200 SMA AND 20 EMA > 50 EMA AND Volume > 1.5x avg |
| **RSI Recovery** | RSI crossing above 30 from oversold + MACD bullish crossover |
| **Volume Surge** | Volume > 3x 20-day average + price up > 3% |

### 6. Income/Dividend Filters

| Screen Name | Criteria |
|---|---|
| **High Dividend Yield** | Dividend Yield > 3% AND Payout Ratio < 60% |
| **Dividend Aristocrat** | Dividend increasing for 10+ years |
| **REIT/InvIT** | Yield > 7% (for REITs like Embassy, Mindspace) |

---

## Pre-Built Screens for Indian Market

### Screen 1: "Wealth Compounders" (Long-term Investors)
```
Market Cap > ₹10,000 Cr
ROE > 20% for last 5 years
Revenue growth > 12% CAGR (5 years)
D/E < 0.5
Promoter holding > 50%
Promoter pledge < 5%
```
**Purpose**: Find high-quality large/mid caps that compound wealth steadily.

### Screen 2: "Turnaround Candidates"
```
PAT positive for last 2 quarters (was negative before)
ROCE improving for 3 consecutive quarters
Debt reducing (D/E declining)
Sector not in deep structural decline
```
**Purpose**: Companies turning profitable after a rough patch.

### Screen 3: "Mid Cap Growth"
```
Market Cap ₹5,000-20,000 Cr
Revenue growth > 20% YoY
PAT growth > 25% YoY
ROE > 15%
Institutional holding > 20% (FII + DII)
```
**Purpose**: High-growth mid caps with institutional backing.

### Screen 4: "Dividend Income Portfolio"
```
Market Cap > ₹5,000 Cr
Dividend Yield > 2.5%
Payout Ratio 30-70%
Dividend per share increasing for 5 years
D/E < 1
```
**Purpose**: Steady dividend income with capital preservation.

### Screen 5: "Sector Rotation — defensive"
```
Sector: Pharma OR FMCG OR IT
Market Cap > ₹15,000 Cr
ROE > 18%
Debt free or very low debt
Revenue growth > 10% YoY
```
**Purpose**: Defensive sectors during market uncertainty.

### Screen 6: "Small Cap Multi-Bagger Hunt"
```
Market Cap ₹1,000-5,000 Cr
Revenue growth > 25% for 3 years
ROE > 18%
Promoter holding > 55%
FII/DII holding > 10%
Debt < 1x EBITDA
```
**Purpose**: Aggressive small cap screen for high-risk high-reward.

---

## Sector-Specific Screening Tips

### Banking / NBFC
- Focus on: **NIM** (Net Interest Margin), **GNPA** (Gross NPA), **NNPA**, **CAR** (Capital Adequacy Ratio), **CASA ratio**
- Avoid: Banks with GNPA > 5% or rising NNPA trend
- Good: NIM > 3%, GNPA < 2%, CASA > 40%

### IT Services
- Focus on: **Revenue growth in USD terms**, **attrition rate**, **deal TCV**, **client concentration**
- Avoid: High attrition > 25%, single client > 20% revenue
- Good: USD revenue growth > 10%, attrition < 15%, diversified client base

### Pharma
- Focus on: **ANDA pipeline**, **US sales growth**, **API vs formulations mix**, **R&D spend**
- Avoid: Companies with US FDA warnings/import alerts
- Good: Strong ANDA pipeline, growing US formulations business

### Auto / Auto Ancillary
- Focus: **Monthly sales data (SIAM)**, **market share**, **EV readiness**, **export mix**
- Avoid: Companies losing market share consistently
- Good: Gaining market share, EV portfolio, strong export revenue

### Real Estate
- Focus: **Pre-sales**, **collections**, **launch pipeline**, **land bank**, **net debt**
- Avoid: Low collection efficiency (<80%), very high debt
- Good: Strong pre-sales growth, high collections, large launches pipeline

### Chemicals
- Focus: **Custom synthesis vs commodity**, **US/EU client base**, **capex cycle**, **environmental compliance**
- Avoid: Companies with environmental issues, pure commodity players
- Good: Custom synthesis focus, global clients, recent capex coming online

---

## Screening Workflow

1. **Define objective** — What kind of stock are we looking for?
2. **Apply primary filters** — Market cap + valuation + profitability (these eliminate 80% of universe)
3. **Apply secondary filters** — Growth + momentum + ownership
4. **Sector filter** — If sector-specific, apply sector criteria
5. **Shortlist 5-10 stocks** — From the filtered list
6. **Deep dive** — Run fundamental analysis on each shortlisted stock
7. **Technical check** — Verify entry timing using technical analysis
8. **Final pick** — Select 3-5 stocks based on combined analysis

---

## Data Sources for Screening (via Web Search)

| Source | Search Query |
|---|---|
| **Screener.in** | `"best stocks" site:screener.in {criteria}` |
| **TickerTape** | `"stock screener" site:tickertape.in {criteria}` |
| **MoneyControl** | `moneycontrol stock screener {sector}` |
| **Trendlyne** | `site:trendlyne.com stock screen {criteria}` |
| **Chartink** | `site:chartink.com scan {criteria}` |
| **NSE India** | `nseindia.com top gainers {sector}` |

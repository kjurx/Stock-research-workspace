# Guru Skills — Indian Stock Market Researcher workspace

Indian stock market researcher for NSE/BSE. All-in-one skill covering fundamental analysis, technical analysis, stock screening, and research report generation.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./LICENSE.txt)

## Capabilities

| Capability | Description | Reference |
|---|---|---|
| Fundamental Analysis | Company financials, valuation, earnings | [references/fundamental-analysis.md](./references/fundamental-analysis.md) |
| Technical Analysis | Chart patterns, support/resistance | [references/technical-analysis.md](./references/technical-analysis.md) |
| Stock Screening | Find stocks by criteria | [references/stock-screening.md](./references/stock-screening.md) |
| Indian Market Context | Indices, sectors, trading rules | [references/indian-market.md](./references/indian-market.md) |
| Research Reports | Structured reports | [references/report-template.md](./references/report-template.md) |

## Usage

This is a Claude Code Skill. Install via:

```
/plugin marketplace add <your-github>/guru-skills
```

Or copy `SKILL.md` and `references/` to your Claude skills directory.

## Structure

```
guru-skills/
├── SKILL.md
├── LICENSE.txt
├── README.md
└── references/
    ├── fundamental-analysis.md
    ├── technical-analysis.md
    ├── stock-screening.md
    ├── indian-market.md
    ├── report-template.md
    └── analysis-bls-international-25aug2026.md
```

## Disclaimer

Educational analysis only, not financial advice. Consult SEBI-registered advisor.

## License

Apache 2.0 — see [LICENSE.txt](./LICENSE.txt)

# Analyze Markets and Portfolio

An evidence-first skill for producing independent market research, discovering sector and cross-asset opportunities, and only then mapping the conclusions to a user's portfolio.

## Core principle

The portfolio is an application of the market analysis, not the boundary of the research universe. This skill keeps independent research and personalization visibly separate.

## What it does

- Leads with a one-minute view of the three most important developments.
- Validates the previous report's thesis, scenarios, and unresolved watch items.
- Analyzes macro conditions, regional equities, rates, credit, currencies, commodities, earnings, valuation, flows, and sentiment.
- Scans mainland China, Hong Kong, and US sectors across multiple horizons.
- Builds an opportunity matrix with evidence, confidence, catalysts, risks, alternatives, and invalidation conditions.
- Adds a separate portfolio-impact appendix only after the market conclusion is locked.
- Supports current-market reports, historical-cutoff analysis, and recurring market-analysis tasks.

## Portfolio privacy and input

This repository contains no personal holdings. When personalized analysis is requested, the user must supply authoritative holdings in the current request, an explicitly configured automation, or a designated portfolio ledger.

At minimum, provide each product's name or identifier and exact share class. Portfolio weight or amount, currency, and recurring-investment plan are optional but useful. The skill does not treat conversational memory, inferred history, or example holdings as authoritative.

## Installation

Install or copy this repository as a skill named `analyze-markets-and-portfolio` using the skill mechanism supported by your agent environment. For a local Codex skills directory, one option is:

```bash
git clone https://github.com/stonebeast-river/analyze-markets-and-portfolio.git ~/.codex/skills/analyze-markets-and-portfolio
```

The skill has no Python or third-party package dependencies. It does require a host environment capable of retrieving current or historical market sources when the requested analysis needs them.

## Usage

```text
Use $analyze-markets-and-portfolio to produce today's evidence-first market report.
```

For personalized analysis:

```text
Use $analyze-markets-and-portfolio to analyze the market first, then assess these holdings: [product name or code, exact share class, optional weight or amount, currency, and recurring-investment plan].
```

## Repository structure

```text
analyze-markets-and-portfolio/
├── SKILL.md
├── agents/openai.yaml
├── assets/icon.svg
└── references/
    ├── automation-instructions.md
    ├── report-template.md
    ├── sector-opportunity-framework.md
    └── transmission-map.md
```

## Limitations

- The skill does not bundle Bloomberg, Wind, or another proprietary market-data feed.
- Output quality depends on the host's access to reliable, timestamped sources.
- Opportunity discovery is research support, not authorization to trade or a guarantee of returns.

## License

MIT

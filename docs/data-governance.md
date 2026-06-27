# Data Governance

## Public vs Private Sources

Crypto Radar is designed around public-safe source handling.

Allowed public-safe source categories may include:

- Public news
- Public regulatory materials
- Official project announcements
- Public exchange policy updates
- Public macroeconomic event summaries
- Public market narrative summaries

Excluded private or sensitive sources include:

- Private data feeds
- Paid sources
- Private Telegram configuration
- Account data
- Customer records
- Internal commercial materials
- Proprietary strategy rules
- Private prompts
- Credentials, API keys, tokens, and `.env` files

## Source Provenance

Each radar item should preserve source provenance. At minimum, it should identify source type, date, primary or secondary status, and review state.

Source provenance helps reviewers avoid treating unverified or secondary information as confirmed fact.

## Sensitive Data Exclusion

The public repository must exclude:

- API keys and tokens
- Credentials
- Private data sources
- Trading account data
- PnL
- Portfolio holdings
- Real trading signals
- Proprietary strategy parameters
- Customer information
- Production deployment details

## No Financial Advice

Crypto Radar is a market intelligence workflow and decision-support concept. It does not provide financial advice, trading recommendations, or instructions to buy, sell, or hold any asset.

## No Account Data

No exchange accounts, wallet addresses, balances, orders, positions, PnL records, or trading account exports are included.

## No Proprietary Signals

The public version does not include proprietary strategy rules, signal parameters, private watchlists, or production alert logic.

## Public-Safe Boundary

This repository contains only documentation, synthetic examples, diagrams, and portfolio-safe descriptions. It is intended to demonstrate workflow design, not trading performance.

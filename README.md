# US Data MCP Servers

Remote [Model Context Protocol](https://modelcontextprotocol.io) servers for AI agents, built on official US open data.

- **Free tier** on every server (no key)
- **Monthly Stripe subscription** for unlimited Pro tools
- **Pay-per-call USDC on Base** via [x402](https://x402.org) — no account

Vendor: Donnie Morrison · Contact: dmorrisonwebdesign@gmail.com

## Servers

| Worker | Title | Sub | x402/call | MCP | Manifest |
|--------|-------|-----|-----------|-----|----------|
| `us-bank-check-mcp` | US Bank Check (FDIC) | ? | $0.03 | https://us-bank-check-mcp.donniertf.workers.dev/mcp | https://us-bank-check-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-business-calendar-mcp` | US Business Calendar | ? | $0.02 | https://us-business-calendar-mcp.donniertf.workers.dev/mcp | https://us-business-calendar-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-company-financials-mcp` | US Company Financials (SEC XBRL) | ? | $0.05 | https://us-company-financials-mcp.donniertf.workers.dev/mcp | https://us-company-financials-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-disaster-declarations-mcp` | US Disaster Declarations (FEMA) | ? | $0.03 | https://us-disaster-declarations-mcp.donniertf.workers.dev/mcp | https://us-disaster-declarations-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-drug-shortages-mcp` | US Drug Shortages (FDA) | ? | $0.02 | https://us-drug-shortages-mcp.donniertf.workers.dev/mcp | https://us-drug-shortages-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-earthquake-alerts-mcp` | US Earthquake Risk & Alerts | ? | $0.02 | https://us-earthquake-alerts-mcp.donniertf.workers.dev/mcp | https://us-earthquake-alerts-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-epa-compliance-mcp` | US EPA Compliance Check | ? | $0.03 | https://us-epa-compliance-mcp.donniertf.workers.dev/mcp | https://us-epa-compliance-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-federal-grants-mcp` | US Federal Grants Finder | ? | $0.05 | https://us-federal-grants-mcp.donniertf.workers.dev/mcp | https://us-federal-grants-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-federal-register-mcp` | US Federal Register Watch | ? | $0.03 | https://us-federal-register-mcp.donniertf.workers.dev/mcp | https://us-federal-register-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-flood-claims-mcp` | US Flood Claims by ZIP | ? | $0.03 | https://us-flood-claims-mcp.donniertf.workers.dev/mcp | https://us-flood-claims-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-food-drug-recalls-mcp` | US FDA Recalls (Food, Drug, Device) | ? | $0.02 | https://us-food-drug-recalls-mcp.donniertf.workers.dev/mcp | https://us-food-drug-recalls-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-insider-trades-mcp` | US Insider Trades (SEC Form 4) | ? | $0.08 | https://us-insider-trades-mcp.donniertf.workers.dev/mcp | https://us-insider-trades-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-nonprofit-check-mcp` | US Nonprofit & Charity Check | ? | $0.02 | https://us-nonprofit-check-mcp.donniertf.workers.dev/mcp | https://us-nonprofit-check-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-npi-lookup-mcp` | US Healthcare Provider (NPI) Lookup | ? | $0.02 | https://us-npi-lookup-mcp.donniertf.workers.dev/mcp | https://us-npi-lookup-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-product-recalls-mcp` | US Consumer Product Recalls (CPSC) | ? | $0.02 | https://us-product-recalls-mcp.donniertf.workers.dev/mcp | https://us-product-recalls-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-sanctions-screen-mcp` | US OFAC Sanctions Screening | ? | $0.08 | https://us-sanctions-screen-mcp.donniertf.workers.dev/mcp | https://us-sanctions-screen-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-sec-filings-mcp` | US SEC Filings Watch | ? | $0.03 | https://us-sec-filings-mcp.donniertf.workers.dev/mcp | https://us-sec-filings-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-vehicle-recalls-mcp` | US Vehicle Recalls & VIN Check | ? | $0.02 | https://us-vehicle-recalls-mcp.donniertf.workers.dev/mcp | https://us-vehicle-recalls-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-visa-sponsors-mcp` | US H-1B Visa Sponsors | ? | $0.05 | https://us-visa-sponsors-mcp.donniertf.workers.dev/mcp | https://us-visa-sponsors-mcp.donniertf.workers.dev/.well-known/x402 |
| `us-weather-alerts-mcp` | US Severe Weather Alerts | ? | $0.02 | https://us-weather-alerts-mcp.donniertf.workers.dev/mcp | https://us-weather-alerts-mcp.donniertf.workers.dev/.well-known/x402 |

## Bundles

- https://us-mcp-bundles.donniertf.workers.dev/

## Agent discovery

- `/.well-known/mcp` — MCP server card
- `/llms.txt` — agent docs
- `/pricing.json` — Stripe + x402 pricing
- `/.well-known/x402` — x402 pay-per-call manifest
- `/sitemap.xml` · `/robots.txt`

## Topics

`mcp` `model-context-protocol` `x402` `usdc` `cloudflare-workers` `open-data` `us-data` `ai-agents`

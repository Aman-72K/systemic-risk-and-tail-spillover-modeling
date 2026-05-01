# Extreme Risk Spillovers in Commodity Markets: Multilayer Networks in the Frequency Domain

> A research paper extending Shahzad et al. (2025) to U.S. commodity markets using multilayer frequency-domain network analysis.

---

## What This Paper Is About

This paper studies how **extreme risks spread across commodity markets** — and crucially, *at what speed* those risks travel. It builds three-layer frequency networks (short, medium, and long-term) to map how shocks move through Energy, Metals, and Agricultural commodities, and identifies which commodities are the biggest sources and recipients of systemic risk.

The core argument: standard connectedness models miss the full picture because they treat all shocks as equal regardless of time horizon. This paper fixes that.

---

## Data

- **13 commodity futures** across 4 groups: Energy (Crude Oil, Heating Oil, Gasoline), Agricultural (Corn, Wheat, Soybeans, Rice, Sugar), Precious Metals (Gold, Silver, Platinum, Palladium), Industrial Metals (Copper)
- **Period:** January 1, 2006 – June 30, 2025 (~4,909 daily observations)
- Covers: Global Financial Crisis (2008–09), Oil Price Collapse (2014–16), COVID-19 (2020), Russia-Ukraine War (2022)

---

## Methodology

| Tool | Purpose |
|---|---|
| **CAViaR** (Engle & Manganelli, 2004) | Model extreme downside risk (VaR) for each commodity |
| **Leave-One-Out (LOO)** | Identify which commodities contribute most to systemic risk |
| **LASSO-VAR-BK** (Baruník & Křehlík, 2018) | Frequency-domain spillover estimation in high-dimensional settings |
| **Multilayer Networks** (3 layers) | Short-term (1–5 days), Medium-term (5–20 days), Long-term (20+ days) |
| **Network Measures** | ACS, AND, UER, AEO, MPC, P(out), P(in) — centrality and overlap metrics |

---

## Key Findings

**1. Risk is a short-term phenomenon**
Spillover intensity decays by over 90% between the 1-day and 22-day horizons. Systemic risk is concentrated at the shortest timescales, though the *structure* of who transmits to whom stays stable across all horizons.

**2. Energy dominates — always**
Crude Oil and Heating Oil rank #1 and #2 in LOO scores across all three frequency layers (~21% each). Energy is the unidirectional net risk exporter: it consistently pushes shocks to Metals and Agriculture, with almost no reverse flow.

**3. Crises don't rewire the network — they amplify it**
During the GFC and COVID-19, the fundamental risk hierarchy (energy → metals → agriculture) remained unchanged. Crises just made existing connections much stronger and faster.

**4. Two types of oil risk**
- **Crude Oil** = stable, structural risk node. Consistently the largest systemic vulnerability, regardless of market conditions.
- **Brent Crude** = dynamic, geopolitically sensitive risk driver. Its systemic role swings sharply with global events.

**5. Agricultural commodities offer the most diversification**
Agriculture shows the lowest intra-group connectedness and absorbs rather than transmits cross-sector shocks — making it the most useful diversifier in a commodity portfolio.

---

## Practical Implications

- **Investors:** Cross-sector diversification (especially into agriculture) reduces long-term exposure; within-sector diversification provides limited benefit given tight intra-group coupling.
- **Risk managers:** Short-term monitoring of Crude Oil LOO and network ACS serves as an effective early-warning system for systemic stress.
- **Policymakers:** Energy shocks translate rapidly into food and metal cost pressures — interventions targeting energy price volatility have cross-sector stabilizing effects.
